[@ue-too/being](../../modules.md) / [index](../index.md) / DefaultOutputMapping

# 型エイリアス: DefaultOutputMapping\<EventPayloadMapping\>

> **DefaultOutputMapping**\<`EventPayloadMapping`\> = `{ [K in keyof EventPayloadMapping]: void }`

定義: [interface.ts:169](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/being/src/interface.ts#L169)

## 型パラメーター

### EventPayloadMapping

`EventPayloadMapping`

## Description

A default output mapping that maps all events to void.
Used as default when no output mapping is provided.
