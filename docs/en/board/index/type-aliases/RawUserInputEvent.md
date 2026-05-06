[@ue-too/board](../../modules.md) / [index](../index.md) / RawUserInputEvent

# Type Alias: RawUserInputEvent

> **RawUserInputEvent** = [`RawUserPanInputEvent`](RawUserPanInputEvent.md) \| [`RawUserZoomInputEvent`](RawUserZoomInputEvent.md) \| [`RawUserRotateInputEvent`](RawUserRotateInputEvent.md)

Defined in: [packages/board/src/input-interpretation/raw-input-publisher/raw-input-publisher.ts:114](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/raw-input-publisher/raw-input-publisher.ts#L114)

Union type of all raw user input events.

## Remarks

Use the `type` discriminator property to determine which event variant you have.
