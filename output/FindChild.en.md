### Format
```typescript
Transform.FindChild(name)
```
#### Class: [`Transform`](../Transform.md)

### Description
Find a child Transform by the name of the GameObject attached to the current Transform.

This method searches by relative path, meaning it searches relative to the current Transform object.

### Parameters
Parameter|Type|Description
---|---|---
name|`string`|Name of the GameObject attached to the Transform

### Return Value
Type|Description
---|---
`Transform`|Child Transform

### Code Example
```typescript
OnStart(): void {
    let transform = this.transform;
    let child = transform.FindChild("childname");
}
```