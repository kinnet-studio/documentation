[@ue-too/board](../../modules.md) / [index](../index.md) / VanillaKMTEventParser

# 類別: VanillaKMTEventParser

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:166](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L166)

Interface for KMT (Keyboard/Mouse/Trackpad) event parsers.

## 備註

Event parsers bridge the gap between DOM events and the state machine.
They listen for raw DOM events, convert them to state machine events,
and coordinate with the orchestrator for output processing.

## 實作

- [`KMTEventParser`](../interfaces/KMTEventParser.md)

## 建構函式

### 建構函式

> **new VanillaKMTEventParser**(`kmtInputStateMachine`, `orchestrator`, `canvas?`): `VanillaKMTEventParser`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:174](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L174)

#### 參數

##### kmtInputStateMachine

[`StateMachine`](../interfaces/StateMachine.md)

##### orchestrator

[`InputOrchestrator`](InputOrchestrator.md)

##### canvas?

`HTMLCanvasElement` | `SVGSVGElement`

#### 回傳

`VanillaKMTEventParser`

## 屬性

### \_canvas?

> `protected` `optional` **\_canvas**: `HTMLCanvasElement` \| `SVGSVGElement`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:172](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L172)

## 存取器

### disabled

#### Getter 簽章

> **get** **disabled**(): `boolean`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:187](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L187)

Whether the parser is currently disabled

##### 回傳

`boolean`

Whether the parser is currently disabled

#### 實作了

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`disabled`](../interfaces/KMTEventParser.md#disabled)

***

### stateMachine

#### Setter 簽章

> **set** **stateMachine**(`stateMachine`): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:386](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L386)

##### 參數

###### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)

##### 回傳

`void`

## 方法

### addEventListeners()

> **addEventListeners**(`signal`): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:199](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L199)

#### 參數

##### signal

`AbortSignal`

#### 回傳

`void`

***

### attach()

> **attach**(`canvas`): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:380](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L380)

Attaches to a new canvas element

#### 參數

##### canvas

`HTMLCanvasElement`

#### 回傳

`void`

#### 實作了

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`attach`](../interfaces/KMTEventParser.md#attach)

***

### bindFunctions()

> **bindFunctions**(): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:240](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L240)

#### 回傳

`void`

***

### disable()

> **disable**(): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:191](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L191)

Disables the parser; the event listeners are still attached just not processing any events

#### 回傳

`void`

#### 實作了

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`disable`](../interfaces/KMTEventParser.md#disable)

***

### enable()

> **enable**(): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:195](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L195)

Enables the parser

#### 回傳

`void`

#### 實作了

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`enable`](../interfaces/KMTEventParser.md#enable)

***

### keypressHandler()

> **keypressHandler**(`e`): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:340](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L340)

#### 參數

##### e

`KeyboardEvent`

#### 回傳

`void`

***

### keyupHandler()

> **keyupHandler**(`e`): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:371](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L371)

#### 參數

##### e

`KeyboardEvent`

#### 回傳

`void`

***

### pointerDownHandler()

> **pointerDownHandler**(`e`): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:262](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L262)

#### 參數

##### e

`PointerEvent`

#### 回傳

`void`

***

### pointerMoveHandler()

> **pointerMoveHandler**(`e`): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:299](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L299)

#### 參數

##### e

`PointerEvent`

#### 回傳

`void`

***

### pointerUpHandler()

> **pointerUpHandler**(`e`): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:282](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L282)

#### 參數

##### e

`PointerEvent`

#### 回傳

`void`

***

### processEvent()

> `protected` **processEvent**\<`K`\>(...`args`): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:249](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L249)

#### 型別參數

##### K

`K` *extends* keyof [`KmtInputEventMapping`](../type-aliases/KmtInputEventMapping.md)

#### 參數

##### args

...`EventArgs`\<[`KmtInputEventMapping`](../type-aliases/KmtInputEventMapping.md), `K`\>

#### 回傳

`void`

***

### scrollHandler()

> **scrollHandler**(`e`): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:320](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L320)

#### 參數

##### e

`WheelEvent`

#### 回傳

`void`

***

### setUp()

> **setUp**(): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:227](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L227)

Initializes event listeners

#### 回傳

`void`

#### 實作了

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`setUp`](../interfaces/KMTEventParser.md#setup)

***

### tearDown()

> **tearDown**(): `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:234](https://github.com/kinnet-studio/ue-too/blob/11b72200b1b18016a77852cb2769e3d421704115/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L234)

Removes event listeners and cleans up

#### 回傳

`void`

#### 實作了

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`tearDown`](../interfaces/KMTEventParser.md#teardown)
