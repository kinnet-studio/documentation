[@ue-too/board](../../modules.md) / [index](../index.md) / MinimumKeyboardEvent

# 型別別名: MinimumKeyboardEvent

> **MinimumKeyboardEvent** = `object`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:88](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L88)

Minimal keyboard event interface for framework interoperability.

## 備註

This subset of the DOM KeyboardEvent interface allows the parser to work with
both vanilla JavaScript KeyboardEvents and framework-wrapped events.

## 屬性

### key

> **key**: `string`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:92](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L92)

The key that was pressed

***

### preventDefault()

> **preventDefault**: () => `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:90](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L90)

Prevents default keyboard behavior

#### 回傳

`void`
