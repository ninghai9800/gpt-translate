### Format
```typescript
Transform.name
```

#### Belongs to class: [`Transform`](../Transform.md)

### Description
(Read-only) The name of the game object attached to the current transform component.

### Parameters
Parameter|Type|Description
---|---|---

### Return Value
Type|Description
---|---
`string`|The name of the game object

### Code Example
```typescript
OnStart(): void {
    let name = this.transform.name;
    Debug.Log(name);
}
```