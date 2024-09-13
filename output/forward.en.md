### Format
```typescript
Transform.forward
```

#### Belongs to Class: [`Transform`](../Transform.md)

### Description
(Read Only) The unit vector in the positive z-axis direction in world space for the game object.

This value will also change direction when the game object is rotated.

### Parameters
Parameter|Type|Description
---|---|---

### Return Value
Type|Description
---|---
`Vector3`|The unit vector in the positive z-axis direction

### Code Example
```typescript
OnStart(): void {
    let forward = this.transform.forward;
}
```