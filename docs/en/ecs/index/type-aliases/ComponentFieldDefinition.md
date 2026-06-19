[@ue-too/ecs](../../modules.md) / [index](../index.md) / ComponentFieldDefinition

# Type Alias: ComponentFieldDefinition

> **ComponentFieldDefinition** = [`ComponentPrimitiveField`](../interfaces/ComponentPrimitiveField.md) \| [`ComponentArrayField`](../interfaces/ComponentArrayField.md)

Defined in: [index.ts:204](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/ecs/src/index.ts#L204)

Discriminated union for field definitions in a component schema.
Use type guards to distinguish between primitive and array fields.
