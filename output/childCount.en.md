### Format
```typescript
Transform.childCount
```

#### Class: [`Transform`](../Transform.md)

### Description
(Read only) The number of child Transform of the current Transform (excluding the parent Transform).

### Parameters
Parameter|Type|Description
---|---|---

### Return Value
Type|Description
---|---
`number`|Number of child Transform

### Code Example
```typescript
OnStart(): void {
    let count = this.transform.childCount;
    Debug.Log(count);
}
```