[@ue-too/being](../../modules.md) / [index](../index.md) / HierarchicalStatePath

# 型エイリアス: HierarchicalStatePath\<ParentStates, ChildStates\>

> **HierarchicalStatePath**\<`ParentStates`, `ChildStates`\> = `ParentStates` \| `` `${ParentStates}.${ChildStates}` ``

定義: [hierarchical.ts:34](https://github.com/ue-too/ue-too/blob/454bcd14d73823b9ce9a2152a4b45cddef4ad346/packages/being/src/hierarchical.ts#L34)

Represents a hierarchical state path using dot notation.
Example: "PARENT.CHILD" means we're in CHILD state within PARENT state.

## 型パラメーター

### ParentStates

`ParentStates` *extends* `string`

### ChildStates

`ChildStates` *extends* `string`
