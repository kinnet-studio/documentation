[@ue-too/board](../../modules.md) / [index](../index.md) / MinimumKeyboardEvent

# Type Alias: MinimumKeyboardEvent

> **MinimumKeyboardEvent** = `object`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:88](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L88)

Minimal keyboard event interface for framework interoperability.

## Remarks

This subset of the DOM KeyboardEvent interface allows the parser to work with
both vanilla JavaScript KeyboardEvents and framework-wrapped events.

## Properties

### key

> **key**: `string`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:92](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L92)

The key that was pressed

***

### preventDefault()

> **preventDefault**: () => `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:90](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L90)

Prevents default keyboard behavior

#### Returns

`void`
