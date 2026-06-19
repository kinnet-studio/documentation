[@ue-too/board](../../modules.md) / [index](../index.md) / AllCameraEventPayload

# Type Alias: AllCameraEventPayload

> **AllCameraEventPayload** = [`CameraRotateEvent`](CameraRotateEvent.md) \| [`CameraPanEvent`](CameraPanEvent.md) \| [`CameraZoomEvent`](CameraZoomEvent.md)

Defined in: [packages/board/src/camera/update-publisher.ts:117](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/camera/update-publisher.ts#L117)

Union type of all camera event payloads with type discriminators.
Used for the 'all' event which fires for any camera change.
