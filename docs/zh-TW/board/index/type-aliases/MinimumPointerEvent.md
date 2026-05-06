[@ue-too/board](../../modules.md) / [index](../index.md) / MinimumPointerEvent

# 型別別名: MinimumPointerEvent

> **MinimumPointerEvent** = `object`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:42](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L42)

Minimal pointer event interface for framework interoperability.

## 備註

This subset of the DOM PointerEvent interface allows the parser to work with
both vanilla JavaScript PointerEvents and framework-wrapped events (e.g., PixiJS).

## 屬性

### button

> **button**: `number`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:44](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L44)

Mouse button number (0=left, 1=middle, 2=right)

***

### buttons

> **buttons**: `number`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:52](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L52)

Bitmask of currently pressed buttons

***

### clientX

> **clientX**: `number`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:48](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L48)

X coordinate in window space

***

### clientY

> **clientY**: `number`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:50](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L50)

Y coordinate in window space

***

### pointerType

> **pointerType**: `string`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:46](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L46)

Pointer type ("mouse", "pen", "touch")
