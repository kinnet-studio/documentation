[@ue-too/ecs](../../modules.md) / [index](../index.md) / createComponentName

# 函式: createComponentName()

> **createComponentName**(`name`): `symbol`

定義於: [index.ts:234](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/ecs/src/index.ts#L234)

Helper function to create a component name from a string.
This creates a unique symbol for the component name.

## 參數

### name

`string`

The string name for the component

## 回傳

`symbol`

A unique symbol for the component name

## 範例

```typescript
const Position = createComponentName('Position');
coordinator.registerComponent<Position>(Position);
```
