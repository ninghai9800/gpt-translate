### Format
```typescript
Transform.eulerAngles
```

#### Class: [`Transform`](../Transform.md)

### Description
(Read Only) The rotation of the game object as represented in Euler angles (in degrees).

This method returns the rotation of the game object in world space as Euler angles. When viewed in the inspector panel, you may see that this return value is different from the rotation value in the inspector panel. This is because the inspector panel displays local rotation. For more information, please refer to [Transform.localEulerAngles](./localEulerAngles.md).

### Parameters
Parameter|Type|Description
---|---|---

### Return Value
Type|Description
---|---
`Vector3`|The rotation represented in Euler angles (in degrees)

### Code Example
```typescript
OnStart(): void {
    let angle = this.transform.eulerAngles;
    Debug.Log(angle);
}
```