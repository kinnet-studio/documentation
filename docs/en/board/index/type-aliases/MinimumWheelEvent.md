[@ue-too/board](../../modules.md) / [index](../index.md) / MinimumWheelEvent

# Type Alias: MinimumWheelEvent

> **MinimumWheelEvent** = `object`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:64](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L64)

Minimal wheel event interface for framework interoperability.

## Remarks

This subset of the DOM WheelEvent interface allows the parser to work with
both vanilla JavaScript WheelEvents and framework-wrapped events.

## Properties

### clientX

> **clientX**: `number`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:74](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L74)

X coordinate in window space

***

### clientY

> **clientY**: `number`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:76](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L76)

Y coordinate in window space

***

### ctrlKey

> **ctrlKey**: `boolean`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:72](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L72)

Whether Ctrl key is pressed (for zoom)

***

### deltaX

> **deltaX**: `number`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:68](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L68)

Horizontal scroll delta

***

### deltaY

> **deltaY**: `number`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:70](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L70)

Vertical scroll delta

***

### preventDefault()

> **preventDefault**: () => `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:66](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L66)

Prevents default scroll behavior

#### Returns

`void`
