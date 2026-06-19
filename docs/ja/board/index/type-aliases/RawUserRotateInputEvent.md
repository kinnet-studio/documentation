[@ue-too/board](../../modules.md) / [index](../index.md) / RawUserRotateInputEvent

# 型エイリアス: RawUserRotateInputEvent

> **RawUserRotateInputEvent** = `object` & [`RawUserRotateInputEventPayload`](RawUserRotateInputEventPayload.md)

定義: [packages/board/src/input-interpretation/raw-input-publisher/raw-input-publisher.ts:85](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-publisher/raw-input-publisher.ts#L85)

Rotate input event with discriminated type.

## 型宣言

### type

> **type**: `"rotate"`

## Remarks

The `type` property allows TypeScript discriminated unions to distinguish
between different event types when subscribing to the "all" event stream.
