[@ue-too/board](../../modules.md) / [index](../index.md) / decomposeTRS

# 関数: decomposeTRS()

> **decomposeTRS**(`matrix`): `object`

定義: [packages/board/src/camera/utils/matrix.ts:368](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/camera/utils/matrix.ts#L368)

Decomposes a 2D transformation matrix into Translation, Rotation, and Scale (TRS)

## パラメータ

### matrix

[`TransformationMatrix`](../type-aliases/TransformationMatrix.md)

The transformation matrix to decompose

## 戻り値

`object`

Object containing translation, rotation (in radians), and scale components

### rotation

> **rotation**: `number`

### scale

> **scale**: `object`

#### scale.x

> **x**: `number`

#### scale.y

> **y**: `number`

### translation

> **translation**: `object`

#### translation.x

> **x**: `number`

#### translation.y

> **y**: `number`
