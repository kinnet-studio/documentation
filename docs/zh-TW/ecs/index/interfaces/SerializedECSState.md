[@ue-too/ecs](../../modules.md) / [index](../index.md) / SerializedECSState

# 介面: SerializedECSState

定義於: [index.ts:370](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/ecs/src/index.ts#L370)

Serialized representation of the entire ECS state.

## 屬性

### entities

> **entities**: [`SerializedEntity`](SerializedEntity.md)[]

定義於: [index.ts:372](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/ecs/src/index.ts#L372)

Array of all entities with their component data

***

### schemas?

> `optional` **schemas**: [`SerializedComponentSchema`](SerializedComponentSchema.md)[]

定義於: [index.ts:374](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/ecs/src/index.ts#L374)

Optional: Array of component schemas (if using schema-based components)
