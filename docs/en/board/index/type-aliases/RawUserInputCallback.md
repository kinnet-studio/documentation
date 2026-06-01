[@ue-too/board](../../modules.md) / [index](../index.md) / RawUserInputCallback

# Type Alias: RawUserInputCallback()\<K\>

> **RawUserInputCallback**\<`K`\> = (`event`) => `void`

Defined in: [packages/board/src/input-interpretation/raw-input-publisher/raw-input-publisher.ts:126](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/board/src/input-interpretation/raw-input-publisher/raw-input-publisher.ts#L126)

Callback function type for raw user input events.

## Type Parameters

### K

`K` *extends* keyof [`RawUserInputEventMap`](RawUserInputEventMap.md)

The event name key from RawUserInputEventMap

## Parameters

### event

[`RawUserInputEventMap`](RawUserInputEventMap.md)\[`K`\]

## Returns

`void`
