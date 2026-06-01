[@ue-too/board](../../modules.md) / [index](../index.md) / PanControlOutputEvent

# Type Alias: PanControlOutputEvent

> **PanControlOutputEvent** = \{ `delta`: `Point`; `type`: `"panByViewPort"`; \} \| \{ `target`: `Point`; `type`: `"panToWorld"`; \} \| \{ `type`: `"none"`; \}

Defined in: [packages/board/src/camera/camera-mux/animation-and-lock/pan-control-state-machine.ts:76](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/camera/camera-mux/animation-and-lock/pan-control-state-machine.ts#L76)

Discriminated union of output events from pan control state machine.

## Remarks

Output events instruct the camera system what pan operation to perform:
- `panByViewPort`: Relative pan in viewport coordinates
- `panToWorld`: Absolute pan to world position
- `none`: No operation (input blocked)
