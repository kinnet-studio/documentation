[@ue-too/board](../../modules.md) / [index](../index.md) / deg2rad

# Function: deg2rad()

> **deg2rad**(`deg`): `number`

Defined in: [packages/board/src/camera/utils/rotation.ts:307](https://github.com/ue-too/ue-too/blob/3358b0ff9b18cc8206e49089d5071b18926b4244/packages/board/src/camera/utils/rotation.ts#L307)

Converts degrees to radians.

## Parameters

### deg

`number`

Angle in degrees

## Returns

`number`

Equivalent angle in radians

## Example

```typescript
deg2rad(0);     // 0
deg2rad(90);    // π/2
deg2rad(180);   // π
deg2rad(360);   // 2π
deg2rad(-45);   // -π/4
```
