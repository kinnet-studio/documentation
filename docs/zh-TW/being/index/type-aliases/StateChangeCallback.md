[@ue-too/being](../../modules.md) / [index](../index.md) / StateChangeCallback

# 型別別名: StateChangeCallback()\<States\>

> **StateChangeCallback**\<`States`\> = (`currentState`, `nextState`) => `void`

定義於: [interface.ts:264](https://github.com/ue-too/ue-too/blob/869d507317a2d8be79359e34a957c2cb9a03e24c/packages/being/src/interface.ts#L264)

## 型別參數

### States

`States` *extends* `string` = `"IDLE"`

## 參數

### currentState

`States`

### nextState

`States`

## 回傳

`void`

## Description

This is the type for the callback that is called when the state changes.
