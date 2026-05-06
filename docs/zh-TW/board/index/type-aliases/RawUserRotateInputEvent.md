[@ue-too/board](../../modules.md) / [index](../index.md) / RawUserRotateInputEvent

# 型別別名: RawUserRotateInputEvent

> **RawUserRotateInputEvent** = `object` & [`RawUserRotateInputEventPayload`](RawUserRotateInputEventPayload.md)

定義於: [packages/board/src/input-interpretation/raw-input-publisher/raw-input-publisher.ts:85](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-publisher/raw-input-publisher.ts#L85)

Rotate input event with discriminated type.

## 型別宣告

### type

> **type**: `"rotate"`

## 備註

The `type` property allows TypeScript discriminated unions to distinguish
between different event types when subscribing to the "all" event stream.
