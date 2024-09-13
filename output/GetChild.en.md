### Format
```typescript
Transform.GetChild(index)
```

#### Class: [`Transform`](../Transform.md)

### Description
Get the child Transform based on the index (index starts from 0).

If the transform has no children, or if the value of the index parameter is greater than the number of children, it will return nil. The number of children can be obtained through [Transform.childCount](./childCount.md).

### Parameters
Parameter|Type|Description
---|---|---
index|`number`|The index value of the Transform

### Return Value
Type|Description
---|---
`Transform`|The child Transform

### Code Example
```typescript
OnStart(): void {
    let transform = this.transform;
    let child = transform.FindChild(0);
}
```