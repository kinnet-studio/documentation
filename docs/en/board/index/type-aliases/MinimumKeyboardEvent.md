[@ue-too/board](../../modules.md) / [index](../index.md) / MinimumKeyboardEvent

# Type Alias: MinimumKeyboardEvent

> **MinimumKeyboardEvent** = `object`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:88](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L88)

Minimal keyboard event interface for framework interoperability.

## Remarks

This subset of the DOM KeyboardEvent interface allows the parser to work with
both vanilla JavaScript KeyboardEvents and framework-wrapped events.

## Properties

### key

> **key**: `string`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:92](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L92)

The key that was pressed

***

### preventDefault()

> **preventDefault**: () => `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:90](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L90)

Prevents default keyboard behavior

#### Returns

`void`
