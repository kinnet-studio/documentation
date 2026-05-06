[@ue-too/being](../../modules.md) / [index](../index.md) / HierarchicalStatePath

# 型別別名: HierarchicalStatePath\<ParentStates, ChildStates\>

> **HierarchicalStatePath**\<`ParentStates`, `ChildStates`\> = `ParentStates` \| `` `${ParentStates}.${ChildStates}` ``

定義於: [hierarchical.ts:34](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/being/src/hierarchical.ts#L34)

Represents a hierarchical state path using dot notation.
Example: "PARENT.CHILD" means we're in CHILD state within PARENT state.

## 型別參數

### ParentStates

`ParentStates` *extends* `string`

### ChildStates

`ChildStates` *extends* `string`
