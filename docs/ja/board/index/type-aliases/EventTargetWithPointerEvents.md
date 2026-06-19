[@ue-too/board](../../modules.md) / [index](../index.md) / EventTargetWithPointerEvents

# 型エイリアス: EventTargetWithPointerEvents

> **EventTargetWithPointerEvents** = `object`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:104](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L104)

Minimal event target interface for framework interoperability.

## Remarks

This interface allows the parser to attach event listeners to different
types of event targets (HTMLElement, Canvas, PixiJS Container, etc.).

## プロパティ

### addEventListener()

> **addEventListener**: (`type`, `listener`, `options?`) => `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:105](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L105)

#### パラメータ

##### type

`string`

##### listener

(`event`) => `void`

##### options?

###### passive

`boolean`

#### 戻り値

`void`

***

### removeEventListener()

> **removeEventListener**: (`type`, `listener`) => `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:110](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L110)

#### パラメータ

##### type

`string`

##### listener

(`event`) => `void`

#### 戻り値

`void`
