[@ue-too/board](../../modules.md) / [index](../index.md) / MinimumKeyboardEvent

# 型エイリアス: MinimumKeyboardEvent

> **MinimumKeyboardEvent** = `object`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:88](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L88)

Minimal keyboard event interface for framework interoperability.

## Remarks

This subset of the DOM KeyboardEvent interface allows the parser to work with
both vanilla JavaScript KeyboardEvents and framework-wrapped events.

## プロパティ

### key

> **key**: `string`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:92](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L92)

The key that was pressed

***

### preventDefault()

> **preventDefault**: () => `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:90](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L90)

Prevents default keyboard behavior

#### 戻り値

`void`
