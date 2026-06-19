[@ue-too/being](../../modules.md) / [index](../index.md) / Delay

# 型エイリアス: Delay\<Context, EventPayloadMapping, States, EventOutputMapping\>

> **Delay**\<`Context`, `EventPayloadMapping`, `States`, `EventOutputMapping`\> = `object`

定義: [interface.ts:431](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/being/src/interface.ts#L431)

## 型パラメーター

### Context

`Context` *extends* [`BaseContext`](../interfaces/BaseContext.md)

### EventPayloadMapping

`EventPayloadMapping`

### States

`States` *extends* `string`

### EventOutputMapping

`EventOutputMapping` *extends* `Partial`\<`Record`\<keyof `EventPayloadMapping`, `unknown`\>\> = [`DefaultOutputMapping`](DefaultOutputMapping.md)\<`EventPayloadMapping`\>

## プロパティ

### action

> **action**: [`Action`](Action.md)\<`Context`, `EventPayloadMapping`, `States`, `EventOutputMapping`\>

定義: [interface.ts:440](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/being/src/interface.ts#L440)

***

### time

> **time**: `number`

定義: [interface.ts:439](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/being/src/interface.ts#L439)
