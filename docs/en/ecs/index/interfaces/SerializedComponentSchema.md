[@ue-too/ecs](../../modules.md) / [index](../index.md) / SerializedComponentSchema

# Interface: SerializedComponentSchema

Defined in: [index.ts:350](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/ecs/src/index.ts#L350)

Serialized representation of a component schema for JSON storage.
Component names are stored as strings (using Symbol.for keys for global symbols).

## Properties

### componentName

> **componentName**: `string`

Defined in: [index.ts:351](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/ecs/src/index.ts#L351)

***

### fields

> **fields**: `SerializedComponentField`[]

Defined in: [index.ts:352](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/ecs/src/index.ts#L352)
