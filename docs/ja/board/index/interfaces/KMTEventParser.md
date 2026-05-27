[@ue-too/board](../../modules.md) / [index](../index.md) / KMTEventParser

# インターフェイス: KMTEventParser

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:18](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L18)

Interface for KMT (Keyboard/Mouse/Trackpad) event parsers.

## Remarks

Event parsers bridge the gap between DOM events and the state machine.
They listen for raw DOM events, convert them to state machine events,
and coordinate with the orchestrator for output processing.

## プロパティ

### disabled

> **disabled**: `boolean`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:20](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L20)

Whether the parser is currently disabled

## メソッド

### attach()

> **attach**(`canvas`): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:26](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L26)

Attaches to a new canvas element

#### パラメータ

##### canvas

`HTMLCanvasElement`

#### 戻り値

`void`

***

### disable()

> **disable**(): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:28](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L28)

Disables the parser; the event listeners are still attached just not processing any events

#### 戻り値

`void`

***

### enable()

> **enable**(): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:30](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L30)

Enables the parser

#### 戻り値

`void`

***

### setUp()

> **setUp**(): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:22](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L22)

Initializes event listeners

#### 戻り値

`void`

***

### tearDown()

> **tearDown**(): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:24](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L24)

Removes event listeners and cleans up

#### 戻り値

`void`
