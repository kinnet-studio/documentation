[@ue-too/being](../../modules.md) / [index](../index.md) / Delay

# Type Alias: Delay\<Context, EventPayloadMapping, States, EventOutputMapping\>

> **Delay**\<`Context`, `EventPayloadMapping`, `States`, `EventOutputMapping`\> = `object`

Defined in: [interface.ts:431](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/being/src/interface.ts#L431)

## Type Parameters

### Context

`Context` *extends* [`BaseContext`](../interfaces/BaseContext.md)

### EventPayloadMapping

`EventPayloadMapping`

### States

`States` *extends* `string`

### EventOutputMapping

`EventOutputMapping` *extends* `Partial`\<`Record`\<keyof `EventPayloadMapping`, `unknown`\>\> = [`DefaultOutputMapping`](DefaultOutputMapping.md)\<`EventPayloadMapping`\>

## Properties

### action

> **action**: [`Action`](Action.md)\<`Context`, `EventPayloadMapping`, `States`, `EventOutputMapping`\>

Defined in: [interface.ts:440](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/being/src/interface.ts#L440)

***

### time

> **time**: `number`

Defined in: [interface.ts:439](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/being/src/interface.ts#L439)
