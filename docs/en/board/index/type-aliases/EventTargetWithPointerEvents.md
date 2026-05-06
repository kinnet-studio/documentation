[@ue-too/board](../../modules.md) / [index](../index.md) / EventTargetWithPointerEvents

# Type Alias: EventTargetWithPointerEvents

> **EventTargetWithPointerEvents** = `object`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:104](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L104)

Minimal event target interface for framework interoperability.

## Remarks

This interface allows the parser to attach event listeners to different
types of event targets (HTMLElement, Canvas, PixiJS Container, etc.).

## Properties

### addEventListener()

> **addEventListener**: (`type`, `listener`, `options?`) => `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:105](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L105)

#### Parameters

##### type

`string`

##### listener

(`event`) => `void`

##### options?

###### passive

`boolean`

#### Returns

`void`

***

### removeEventListener()

> **removeEventListener**: (`type`, `listener`) => `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:110](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L110)

#### Parameters

##### type

`string`

##### listener

(`event`) => `void`

#### Returns

`void`
