[@ue-too/board](../../modules.md) / [index](../index.md) / ObservableInputTracker

# クラス: ObservableInputTracker

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:692](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L692)

Production implementation of KmtInputContext that tracks input state for the state machine.

## Remarks

This class provides the concrete implementation of the KMT input context, maintaining
all state required by the state machine to recognize and track gestures:

**State Tracking**:
- Initial cursor position for calculating pan deltas
- Input modality score to distinguish mouse vs trackpad
- Determined input mode (kmt/trackpad/TBD)
- Coordinate system alignment preference

**Input Modality Detection**:
The `kmtTrackpadTrackScore` accumulates evidence about the input device:
- Positive values indicate mouse behavior (middle-click, no horizontal scroll)
- Negative values indicate trackpad behavior (horizontal scroll, two-finger gestures)
- Score is used to determine zoom behavior (Ctrl+Scroll for mouse vs Scroll for trackpad)

**Design Pattern**:
This class follows the Context pattern from the @ue-too/being state machine library,
providing stateful data and operations that states can access and modify during transitions.

## 例

```typescript
const canvasProxy = new CanvasProxy(canvasElement);
const context = new ObservableInputTracker(canvasProxy);
const stateMachine = createKmtInputStateMachine(context);

// Context tracks state as the state machine processes events
stateMachine.happens("leftPointerDown", {x: 100, y: 200});
console.log(context.initialCursorPosition); // {x: 100, y: 200}
```

## 実装

- [`KmtInputContext`](../interfaces/KmtInputContext.md)

## コンストラクター

### コンストラクター

> **new ObservableInputTracker**(`canvasOperator`): `ObservableInputTracker`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:700](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L700)

#### パラメータ

##### canvasOperator

[`Canvas`](../interfaces/Canvas.md)

#### 戻り値

`ObservableInputTracker`

## アクセッサー

### alignCoordinateSystem

#### 署名を取得する

> **get** **alignCoordinateSystem**(): `boolean`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:748](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L748)

Whether to use standard screen coordinate system (vs inverted Y-axis)

##### 戻り値

`boolean`

#### 署名を設定する

> **set** **alignCoordinateSystem**(`value`): `void`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:760](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L760)

Whether to use standard screen coordinate system (vs inverted Y-axis)

##### パラメータ

###### value

`boolean`

##### 戻り値

`void`

Whether to use standard screen coordinate system (vs inverted Y-axis)

#### の実装

[`KmtInputContext`](../interfaces/KmtInputContext.md).[`alignCoordinateSystem`](../interfaces/KmtInputContext.md#aligncoordinatesystem)

***

### canvas

#### 署名を取得する

> **get** **canvas**(): [`Canvas`](../interfaces/Canvas.md)

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:752](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L752)

Canvas accessor for dimensions and cursor control

##### 戻り値

[`Canvas`](../interfaces/Canvas.md)

Canvas accessor for dimensions and cursor control

#### の実装

[`KmtInputContext`](../interfaces/KmtInputContext.md).[`canvas`](../interfaces/KmtInputContext.md#canvas)

***

### initialCursorPosition

#### 署名を取得する

> **get** **initialCursorPosition**(): `Point`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:756](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L756)

The cursor position when a pan gesture started

##### 戻り値

`Point`

The cursor position when a pan gesture started

#### の実装

[`KmtInputContext`](../interfaces/KmtInputContext.md).[`initialCursorPosition`](../interfaces/KmtInputContext.md#initialcursorposition)

***

### kmtTrackpadTrackScore

#### 署名を取得する

> **get** **kmtTrackpadTrackScore**(): `number`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:722](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L722)

Score tracking input modality: >0 for mouse, <0 for trackpad, 0 for undetermined

##### 戻り値

`number`

Score tracking input modality: >0 for mouse, <0 for trackpad, 0 for undetermined

#### の実装

[`KmtInputContext`](../interfaces/KmtInputContext.md).[`kmtTrackpadTrackScore`](../interfaces/KmtInputContext.md#kmttrackpadtrackscore)

***

### mode

#### 署名を取得する

> **get** **mode**(): `"kmt"` \| `"trackpad"` \| `"TBD"`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:708](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L708)

The current input modality: 'kmt' (mouse), 'trackpad', or 'TBD' (to be determined)

##### 戻り値

`"kmt"` \| `"trackpad"` \| `"TBD"`

The current input modality: 'kmt' (mouse), 'trackpad', or 'TBD' (to be determined)

#### の実装

[`KmtInputContext`](../interfaces/KmtInputContext.md).[`mode`](../interfaces/KmtInputContext.md#mode)

## メソッド

### addKmtTrackpadTrackScore()

> **addKmtTrackpadTrackScore**(): `void`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:737](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L737)

Increases the score toward mouse

#### 戻り値

`void`

#### の実装

[`KmtInputContext`](../interfaces/KmtInputContext.md).[`addKmtTrackpadTrackScore`](../interfaces/KmtInputContext.md#addkmttrackpadtrackscore)

***

### cancelCurrentAction()

> **cancelCurrentAction**(): `void`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:764](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L764)

Cancels the current action and resets cursor position

#### 戻り値

`void`

#### の実装

[`KmtInputContext`](../interfaces/KmtInputContext.md).[`cancelCurrentAction`](../interfaces/KmtInputContext.md#cancelcurrentaction)

***

### cleanup()

> **cleanup**(): `void`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:772](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L772)

#### 戻り値

`void`

#### の実装

[`KmtInputContext`](../interfaces/KmtInputContext.md).[`cleanup`](../interfaces/KmtInputContext.md#cleanup)

***

### enableInputModeDetection()

> **enableInputModeDetection**(): `void`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:717](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L717)

#### 戻り値

`void`

***

### setInitialCursorPosition()

> **setInitialCursorPosition**(`position`): `void`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:768](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L768)

Sets the initial cursor position when starting a pan gesture

#### パラメータ

##### position

`Point`

#### 戻り値

`void`

#### の実装

[`KmtInputContext`](../interfaces/KmtInputContext.md).[`setInitialCursorPosition`](../interfaces/KmtInputContext.md#setinitialcursorposition)

***

### setMode()

> **setMode**(`mode`): `void`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:712](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L712)

Sets the determined input modality

#### パラメータ

##### mode

`"kmt"` | `"trackpad"` | `"TBD"`

#### 戻り値

`void`

#### の実装

[`KmtInputContext`](../interfaces/KmtInputContext.md).[`setMode`](../interfaces/KmtInputContext.md#setmode)

***

### setup()

> **setup**(): `void`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:774](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L774)

#### 戻り値

`void`

#### の実装

[`KmtInputContext`](../interfaces/KmtInputContext.md).[`setup`](../interfaces/KmtInputContext.md#setup)

***

### subtractKmtTrackpadTrackScore()

> **subtractKmtTrackpadTrackScore**(): `void`

定義: [packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts:726](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/input-state-machine/kmt-input-context.ts#L726)

Decreases the score toward trackpad

#### 戻り値

`void`

#### の実装

[`KmtInputContext`](../interfaces/KmtInputContext.md).[`subtractKmtTrackpadTrackScore`](../interfaces/KmtInputContext.md#subtractkmttrackpadtrackscore)
