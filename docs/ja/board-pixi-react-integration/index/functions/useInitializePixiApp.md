[@ue-too/board-pixi-react-integration](../../modules.md) / [index](../index.md) / useInitializePixiApp

# 関数: useInitializePixiApp()

> **useInitializePixiApp**\<`T`\>(`option`, `initFunction`): `object`

定義: [board-pixi-react-integration/src/hooks/pixi/initialization.ts:6](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board-pixi-react-integration/src/hooks/pixi/initialization.ts#L6)

## 型パラメーター

### T

`T` *extends* `InitAppOptions` = `InitAppOptions`

## パラメータ

### option

`Partial`\<`T`\>

### initFunction

(`canvas`, `option`) => `Promise`\<`BaseAppComponents`\>

## 戻り値

`object`

### canvasRef

> **canvasRef**: `RefObject`\<`HTMLCanvasElement` \| `null`\>
