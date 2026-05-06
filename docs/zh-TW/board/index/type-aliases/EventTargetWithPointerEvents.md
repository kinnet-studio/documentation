[@ue-too/board](../../modules.md) / [index](../index.md) / EventTargetWithPointerEvents

# 型別別名: EventTargetWithPointerEvents

> **EventTargetWithPointerEvents** = `object`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:104](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L104)

Minimal event target interface for framework interoperability.

## 備註

This interface allows the parser to attach event listeners to different
types of event targets (HTMLElement, Canvas, PixiJS Container, etc.).

## 屬性

### addEventListener()

> **addEventListener**: (`type`, `listener`, `options?`) => `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:105](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L105)

#### 參數

##### type

`string`

##### listener

(`event`) => `void`

##### options?

###### passive

`boolean`

#### 回傳

`void`

***

### removeEventListener()

> **removeEventListener**: (`type`, `listener`) => `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:110](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L110)

#### 參數

##### type

`string`

##### listener

(`event`) => `void`

#### 回傳

`void`
