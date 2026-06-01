[@ue-too/board](../../modules.md) / [index](../index.md) / VanillaKMTEventParser

# Class: VanillaKMTEventParser

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:166](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L166)

Interface for KMT (Keyboard/Mouse/Trackpad) event parsers.

## Remarks

Event parsers bridge the gap between DOM events and the state machine.
They listen for raw DOM events, convert them to state machine events,
and coordinate with the orchestrator for output processing.

## Implements

- [`KMTEventParser`](../interfaces/KMTEventParser.md)

## Constructors

### Constructor

> **new VanillaKMTEventParser**(`kmtInputStateMachine`, `orchestrator`, `canvas?`): `VanillaKMTEventParser`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:174](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L174)

#### Parameters

##### kmtInputStateMachine

[`StateMachine`](../interfaces/StateMachine.md)

##### orchestrator

[`InputOrchestrator`](InputOrchestrator.md)

##### canvas?

`HTMLCanvasElement` | `SVGSVGElement`

#### Returns

`VanillaKMTEventParser`

## Properties

### \_canvas?

> `protected` `optional` **\_canvas**: `HTMLCanvasElement` \| `SVGSVGElement`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:172](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L172)

## Accessors

### disabled

#### Get Signature

> **get** **disabled**(): `boolean`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:187](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L187)

Whether the parser is currently disabled

##### Returns

`boolean`

Whether the parser is currently disabled

#### Implementation of

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`disabled`](../interfaces/KMTEventParser.md#disabled)

***

### stateMachine

#### Set Signature

> **set** **stateMachine**(`stateMachine`): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:386](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L386)

##### Parameters

###### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)

##### Returns

`void`

## Methods

### addEventListeners()

> **addEventListeners**(`signal`): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:199](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L199)

#### Parameters

##### signal

`AbortSignal`

#### Returns

`void`

***

### attach()

> **attach**(`canvas`): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:380](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L380)

Attaches to a new canvas element

#### Parameters

##### canvas

`HTMLCanvasElement`

#### Returns

`void`

#### Implementation of

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`attach`](../interfaces/KMTEventParser.md#attach)

***

### bindFunctions()

> **bindFunctions**(): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:240](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L240)

#### Returns

`void`

***

### disable()

> **disable**(): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:191](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L191)

Disables the parser; the event listeners are still attached just not processing any events

#### Returns

`void`

#### Implementation of

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`disable`](../interfaces/KMTEventParser.md#disable)

***

### enable()

> **enable**(): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:195](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L195)

Enables the parser

#### Returns

`void`

#### Implementation of

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`enable`](../interfaces/KMTEventParser.md#enable)

***

### keypressHandler()

> **keypressHandler**(`e`): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:340](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L340)

#### Parameters

##### e

`KeyboardEvent`

#### Returns

`void`

***

### keyupHandler()

> **keyupHandler**(`e`): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:371](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L371)

#### Parameters

##### e

`KeyboardEvent`

#### Returns

`void`

***

### pointerDownHandler()

> **pointerDownHandler**(`e`): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:262](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L262)

#### Parameters

##### e

`PointerEvent`

#### Returns

`void`

***

### pointerMoveHandler()

> **pointerMoveHandler**(`e`): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:299](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L299)

#### Parameters

##### e

`PointerEvent`

#### Returns

`void`

***

### pointerUpHandler()

> **pointerUpHandler**(`e`): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:282](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L282)

#### Parameters

##### e

`PointerEvent`

#### Returns

`void`

***

### processEvent()

> `protected` **processEvent**\<`K`\>(...`args`): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:249](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L249)

#### Type Parameters

##### K

`K` *extends* keyof [`KmtInputEventMapping`](../type-aliases/KmtInputEventMapping.md)

#### Parameters

##### args

...`EventArgs`\<[`KmtInputEventMapping`](../type-aliases/KmtInputEventMapping.md), `K`\>

#### Returns

`void`

***

### scrollHandler()

> **scrollHandler**(`e`): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:320](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L320)

#### Parameters

##### e

`WheelEvent`

#### Returns

`void`

***

### setUp()

> **setUp**(): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:227](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L227)

Initializes event listeners

#### Returns

`void`

#### Implementation of

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`setUp`](../interfaces/KMTEventParser.md#setup)

***

### tearDown()

> **tearDown**(): `void`

Defined in: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:234](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L234)

Removes event listeners and cleans up

#### Returns

`void`

#### Implementation of

[`KMTEventParser`](../interfaces/KMTEventParser.md).[`tearDown`](../interfaces/KMTEventParser.md#teardown)
