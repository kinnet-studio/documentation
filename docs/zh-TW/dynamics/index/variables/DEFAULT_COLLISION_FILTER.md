[@ue-too/dynamics](../../modules.md) / [index](../index.md) / DEFAULT\_COLLISION\_FILTER

# 變數: DEFAULT\_COLLISION\_FILTER

> `const` **DEFAULT\_COLLISION\_FILTER**: [`CollisionFilter`](../interfaces/CollisionFilter.md)

定義於: [collision-filter.ts:67](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/dynamics/src/collision-filter.ts#L67)

Default collision filter that collides with everything.

## 備註

Uses category 0x0001 and mask 0xFFFF, meaning it belongs to the first
category and can collide with all 16 categories.
