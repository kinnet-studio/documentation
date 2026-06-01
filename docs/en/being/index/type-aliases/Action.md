[@ue-too/being](../../modules.md) / [index](../index.md) / Action

# Type Alias: Action\<Context, EventPayloadMapping, States, EventOutputMapping, Output\>

> **Action**\<`Context`, `EventPayloadMapping`, `States`, `EventOutputMapping`, `Output`\> = `object`

Defined in: [interface.ts:409](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/being/src/interface.ts#L409)

## Type Parameters

### Context

`Context` *extends* [`BaseContext`](../interfaces/BaseContext.md)

### EventPayloadMapping

`EventPayloadMapping`

### States

`States` *extends* `string`

### EventOutputMapping

`EventOutputMapping` *extends* `Partial`\<`Record`\<keyof `EventPayloadMapping`, `unknown`\>\> = [`DefaultOutputMapping`](DefaultOutputMapping.md)\<`EventPayloadMapping`\>

### Output

`Output` = `void`

## Properties

### action()

> **action**: (`context`, `event`, `stateMachine`) => `Output` \| `void`

Defined in: [interface.ts:418](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/being/src/interface.ts#L418)

#### Parameters

##### context

`Context`

##### event

`EventPayloadMapping`\[keyof `EventPayloadMapping`\]

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<`EventPayloadMapping`, `Context`, `States`, `EventOutputMapping`\>

#### Returns

`Output` \| `void`

***

### defaultTargetState?

> `optional` **defaultTargetState**: `States`

Defined in: [interface.ts:428](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/being/src/interface.ts#L428)
