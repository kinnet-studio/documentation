[@ue-too/board](../../modules.md) / [index](../index.md) / MinimumWheelEvent

# 型別別名: MinimumWheelEvent

> **MinimumWheelEvent** = `object`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:64](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L64)

Minimal wheel event interface for framework interoperability.

## 備註

This subset of the DOM WheelEvent interface allows the parser to work with
both vanilla JavaScript WheelEvents and framework-wrapped events.

## 屬性

### clientX

> **clientX**: `number`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:74](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L74)

X coordinate in window space

***

### clientY

> **clientY**: `number`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:76](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L76)

Y coordinate in window space

***

### ctrlKey

> **ctrlKey**: `boolean`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:72](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L72)

Whether Ctrl key is pressed (for zoom)

***

### deltaX

> **deltaX**: `number`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:68](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L68)

Horizontal scroll delta

***

### deltaY

> **deltaY**: `number`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:70](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L70)

Vertical scroll delta

***

### preventDefault()

> **preventDefault**: () => `void`

定義於: [packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts:66](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-parser/vanilla-kmt-event-parser.ts#L66)

Prevents default scroll behavior

#### 回傳

`void`
