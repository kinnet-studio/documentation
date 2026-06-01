[@ue-too/board](../../modules.md) / [index](../index.md) / ZoomControlStates

# 型別別名: ZoomControlStates

> **ZoomControlStates** = `"ACCEPTING_USER_INPUT"` \| `"TRANSITION"` \| `"LOCKED_ON_OBJECT"`

定義於: [packages/board/src/camera/camera-mux/animation-and-lock/zoom-control-state-machine.ts:16](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/camera/camera-mux/animation-and-lock/zoom-control-state-machine.ts#L16)

State identifiers for the zoom control state machine.

## 備註

Three states manage zoom input and animations:
- `ACCEPTING_USER_INPUT`: Normal state, accepts user zoom input
- `TRANSITION`: Animation/transition state, may block user input
- `LOCKED_ON_OBJECT`: Camera locked to follow a specific object with zoom
