[@ue-too/board](../../modules.md) / [index](../index.md) / KmtInputEventOutputMapping

# 型別別名: KmtInputEventOutputMapping

> **KmtInputEventOutputMapping** = `object`

定義於: [packages/board/src/input-interpretation/input-state-machine/kmt-input-state-machine.ts:193](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/input-state-machine/kmt-input-state-machine.ts#L193)

Mapping of events to their output types.

## 備註

Defines which events produce outputs. Not all events produce outputs - some only
cause state transitions. This mapping is used by the state machine framework for
type-safe output handling.

## 屬性

### leftPointerMove

> **leftPointerMove**: [`KmtOutputEvent`](KmtOutputEvent.md)

定義於: [packages/board/src/input-interpretation/input-state-machine/kmt-input-state-machine.ts:197](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/input-state-machine/kmt-input-state-machine.ts#L197)

***

### middlePointerMove

> **middlePointerMove**: [`KmtOutputEvent`](KmtOutputEvent.md)

定義於: [packages/board/src/input-interpretation/input-state-machine/kmt-input-state-machine.ts:194](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/input-state-machine/kmt-input-state-machine.ts#L194)

***

### scroll

> **scroll**: [`KmtOutputEvent`](KmtOutputEvent.md)

定義於: [packages/board/src/input-interpretation/input-state-machine/kmt-input-state-machine.ts:195](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/input-state-machine/kmt-input-state-machine.ts#L195)

***

### scrollWithCtrl

> **scrollWithCtrl**: [`KmtOutputEvent`](KmtOutputEvent.md)

定義於: [packages/board/src/input-interpretation/input-state-machine/kmt-input-state-machine.ts:196](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/input-interpretation/input-state-machine/kmt-input-state-machine.ts#L196)
