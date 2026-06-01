[@ue-too/ecs](../../modules.md) / [index](../index.md) / deserializeComponentSchema

# Function: deserializeComponentSchema()

> **deserializeComponentSchema**(`serialized`): [`ComponentSchema`](../interfaces/ComponentSchema.md)

Defined in: [index.ts:437](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/ecs/src/index.ts#L437)

Deserialize a component schema from a JSON-compatible format.

## Parameters

### serialized

[`SerializedComponentSchema`](../interfaces/SerializedComponentSchema.md)

The serialized schema

## Returns

[`ComponentSchema`](../interfaces/ComponentSchema.md)

The component schema with symbols restored
