[@ue-too/board](../../modules.md) / [index](../index.md) / MinimumPointerEvent

# Type Alias: MinimumPointerEvent

> **MinimumPointerEvent** = `object`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:42](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L42)

Minimal pointer event interface for framework interoperability.

## Remarks

This subset of the DOM PointerEvent interface allows the parser to work with
both vanilla JavaScript PointerEvents and framework-wrapped events (e.g., PixiJS).

## Properties

### button

> **button**: `number`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:44](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L44)

Mouse button number (0=left, 1=middle, 2=right)

***

### buttons

> **buttons**: `number`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:52](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L52)

Bitmask of currently pressed buttons

***

### clientX

> **clientX**: `number`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:48](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L48)

X coordinate in window space

***

### clientY

> **clientY**: `number`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:50](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L50)

Y coordinate in window space

***

### pointerType

> **pointerType**: `string`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:46](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L46)

Pointer type ("mouse", "pen", "touch")
