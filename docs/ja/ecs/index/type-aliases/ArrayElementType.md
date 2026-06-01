[@ue-too/ecs](../../modules.md) / [index](../index.md) / ArrayElementType

# 型エイリアス: ArrayElementType

> **ArrayElementType** = \{ `kind`: `"builtin"`; `type`: `Exclude`\<[`ComponentFieldType`](ComponentFieldType.md), `"array"`\>; \} \| \{ `kind`: `"custom"`; `typeName`: [`ComponentName`](ComponentName.md); \}

定義: [index.ts:158](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/ecs/src/index.ts#L158)

Discriminated union for array element types.
Supports both built-in types and custom component types.
