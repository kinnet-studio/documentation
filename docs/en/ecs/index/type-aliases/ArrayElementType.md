[@ue-too/ecs](../../modules.md) / [index](../index.md) / ArrayElementType

# Type Alias: ArrayElementType

> **ArrayElementType** = \{ `kind`: `"builtin"`; `type`: `Exclude`\<[`ComponentFieldType`](ComponentFieldType.md), `"array"`\>; \} \| \{ `kind`: `"custom"`; `typeName`: [`ComponentName`](ComponentName.md); \}

Defined in: [index.ts:158](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/ecs/src/index.ts#L158)

Discriminated union for array element types.
Supports both built-in types and custom component types.
