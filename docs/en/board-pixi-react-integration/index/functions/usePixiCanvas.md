[@ue-too/board-pixi-react-integration](../../modules.md) / [index](../index.md) / usePixiCanvas

# Function: usePixiCanvas()

> **usePixiCanvas**\<`C`\>(): `PixiCanvasContextType`\<`C`\>

Defined in: [board-pixi-react-integration/src/contexts/pixi/index.tsx:68](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board-pixi-react-integration/src/contexts/pixi/index.tsx#L68)

Access the PixiJS canvas context with typed components.

## Type Parameters

### C

`C` *extends* `BaseAppComponents` = `BaseAppComponents`

The component type to resolve. Defaults to [ResolvedComponents](../type-aliases/ResolvedComponents.md)
which uses the global [PixiCanvasRegistry](../interfaces/PixiCanvasRegistry.md) augmentation if available,
otherwise falls back to BaseAppComponents.
For multi-page apps with different component types per page, pass the
specific component type explicitly.

## Returns

`PixiCanvasContextType`\<`C`\>

The pixi canvas context with typed result and setResult

## Example

```typescript
// Single-app project with module augmentation (no generic needed):
const { result } = usePixiCanvas();

// Multi-page project with explicit type:
const { result } = usePixiCanvas<TrainEditorComponents>();
```
