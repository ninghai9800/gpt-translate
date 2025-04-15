### Format
```typescript
Transform.gameObject
```

#### Belongs to class: [`Transform`](../Transform.md)

### Description
(Read only) The game object to which the current Transform component is attached.
The component is always attached to a game object.

### Parameters
Parameter|Type|Description
---|---|---

### Return Value
Type|Description
---|---
`GameObject`|The game object

### Code Example
```typescript
OnStart(): void {
    let go = this.transform.gameObject;
}
```