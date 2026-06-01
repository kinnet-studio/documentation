[@ue-too/board-vue-adapter](../../modules.md) / [index](../index.md) / useAnimationFrameWithBoard

# 関数: useAnimationFrameWithBoard()

> **useAnimationFrameWithBoard**(`callback?`): `void`

定義: [useBoard.ts:89](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board-vue-adapter/src/useBoard.ts#L89)

Hook to run an animation loop integrated with the Board's step function.

## パラメータ

### callback?

(`timestamp`, `ctx`) => `void`

Optional function to call after board.step(), receives timestamp and canvas context

## 戻り値

`void`
