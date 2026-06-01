[@ue-too/board](../../modules.md) / [index](../index.md) / RawUserZoomInputEvent

# 型別別名: RawUserZoomInputEvent

> **RawUserZoomInputEvent** = `object` & [`RawUserZoomInputEventPayload`](RawUserZoomInputEventPayload.md)

定義於: [packages/board/src/input-interpretation/raw-input-publisher/raw-input-publisher.ts:61](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-publisher/raw-input-publisher.ts#L61)

Zoom input event with discriminated type.

## 型別宣告

### type

> **type**: `"zoom"`

## 備註

The `type` property allows TypeScript discriminated unions to distinguish
between different event types when subscribing to the "all" event stream.
