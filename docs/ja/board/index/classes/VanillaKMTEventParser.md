[@ue-too/board](../../modules.md) / [index](../index.md) / VanillaKMTEventParser

# クラス: VanillaKMTEventParser

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:166](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L166)

Interface for KMT (Keyboard/Mouse/Trackpad) event parsers.

## Remarks

Event parsers bridge the gap between DOM events and the state machine.
They listen for raw DOM events, convert them to state machine events,
and coordinate with the orchestrator for output processing.

## 実装

- [`KMTEventParser`](../interfaces/KMTEventParser.md)

## コンストラクター

### コンストラクター

> **new VanillaKMTEventParser**(`kmtInputStateMachine`, `orchestrator`, `canvas?`): `VanillaKMTEventParser`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:174](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L174)

#### パラメータ

##### kmtInputStateMachine

[`StateMachine`](../interfaces/StateMachine.md)

##### orchestrator

[`InputOrchestrator`](InputOrchestrator.md)

##### canvas?

`HTMLCanvasElement` | `SVGSVGElement`

#### 戻り値

`VanillaKMTEventParser`

## プロパティ

### \_canvas?

> `protected` `optional` **\_canvas**: `HTMLCanvasElement` \| `SVGSVGElement`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:172](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L172)

## アクセッサー

### disabled

#### 署名を取得する

> **get** **disabled**(): `boolean`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:187](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L187)

Whether the parser is currently disabled

##### 戻り値

`boolean`

Whether the parser is currently disabled

#### の実装

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`disabled`](../interfaces/KMTEventParser.md#disabled)

***

### stateMachine

#### 署名を設定する

> **set** **stateMachine**(`stateMachine`): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:386](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L386)

##### パラメータ

###### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)

##### 戻り値

`void`

## メソッド

### addEventListeners()

> **addEventListeners**(`signal`): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:199](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L199)

#### パラメータ

##### signal

`AbortSignal`

#### 戻り値

`void`

***

### attach()

> **attach**(`canvas`): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:380](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L380)

Attaches to a new canvas element

#### パラメータ

##### canvas

`HTMLCanvasElement`

#### 戻り値

`void`

#### の実装

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`attach`](../interfaces/KMTEventParser.md#attach)

***

### bindFunctions()

> **bindFunctions**(): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:240](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L240)

#### 戻り値

`void`

***

### disable()

> **disable**(): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:191](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L191)

Disables the parser; the event listeners are still attached just not processing any events

#### 戻り値

`void`

#### の実装

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`disable`](../interfaces/KMTEventParser.md#disable)

***

### enable()

> **enable**(): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:195](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L195)

Enables the parser

#### 戻り値

`void`

#### の実装

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`enable`](../interfaces/KMTEventParser.md#enable)

***

### keypressHandler()

> **keypressHandler**(`e`): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:340](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L340)

#### パラメータ

##### e

`KeyboardEvent`

#### 戻り値

`void`

***

### keyupHandler()

> **keyupHandler**(`e`): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:371](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L371)

#### パラメータ

##### e

`KeyboardEvent`

#### 戻り値

`void`

***

### pointerDownHandler()

> **pointerDownHandler**(`e`): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:262](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L262)

#### パラメータ

##### e

`PointerEvent`

#### 戻り値

`void`

***

### pointerMoveHandler()

> **pointerMoveHandler**(`e`): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:299](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L299)

#### パラメータ

##### e

`PointerEvent`

#### 戻り値

`void`

***

### pointerUpHandler()

> **pointerUpHandler**(`e`): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:282](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L282)

#### パラメータ

##### e

`PointerEvent`

#### 戻り値

`void`

***

### processEvent()

> `protected` **processEvent**\<`K`\>(...`args`): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:249](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L249)

#### 型パラメーター

##### K

`K` *extends* keyof [`KmtInputEventMapping`](../type-aliases/KmtInputEventMapping.md)

#### パラメータ

##### args

...`EventArgs`\<[`KmtInputEventMapping`](../type-aliases/KmtInputEventMapping.md), `K`\>

#### 戻り値

`void`

***

### scrollHandler()

> **scrollHandler**(`e`): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:320](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L320)

#### パラメータ

##### e

`WheelEvent`

#### 戻り値

`void`

***

### setUp()

> **setUp**(): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:227](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L227)

Initializes event listeners

#### 戻り値

`void`

#### の実装

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`setUp`](../interfaces/KMTEventParser.md#setup)

***

### tearDown()

> **tearDown**(): `void`

定義: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:234](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L234)

Removes event listeners and cleans up

#### 戻り値

`void`

#### の実装

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`tearDown`](../interfaces/KMTEventParser.md#teardown)
