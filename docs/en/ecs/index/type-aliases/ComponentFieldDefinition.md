[@ue-too/ecs](../../modules.md) / [index](../index.md) / ComponentFieldDefinition

# Type Alias: ComponentFieldDefinition

> **ComponentFieldDefinition** = [`ComponentPrimitiveField`](../interfaces/ComponentPrimitiveField.md) \| [`ComponentArrayField`](../interfaces/ComponentArrayField.md)

Defined in: [index.ts:204](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/ecs/src/index.ts#L204)

Discriminated union for field definitions in a component schema.
Use type guards to distinguish between primitive and array fields.
