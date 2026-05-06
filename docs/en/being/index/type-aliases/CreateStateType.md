[@ue-too/being](../../modules.md) / [index](../index.md) / CreateStateType

# Type Alias: CreateStateType\<ArrayLiteral\>

> **CreateStateType**\<`ArrayLiteral`\> = `ArrayLiteral`\[`number`\]

Defined in: [interface.ts:57](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/being/src/interface.ts#L57)

Utility type to derive a string literal union from a readonly array of string literals.

## Type Parameters

### ArrayLiteral

`ArrayLiteral` *extends* readonly `string`[]

## Remarks

This helper type extracts the element types from a readonly array to create a union type.
Useful for defining state machine states from an array.

## Example

```typescript
const TEST_STATES = ["one", "two", "three"] as const;
type TestStates = CreateStateType<typeof TEST_STATES>; // "one" | "two" | "three"
```
