### Format
```typescript
Transform.forEach(c)
```

#### Class: [`Transform`](../Transform.md)

### Description
Iterates through child Transforms.

### Parameters
Parameter|Type|Description
---|---|---
c|`callback`|Callback function

### Return Value
Type|Description
---|---
`void`|

### Code Example
```typescript
let foreachCallback = (child: Transform) => { 
    Debug.Log(child.name);
};
// Iterate through child Transforms and output the name of each child object
this.transform.forEach(foreachCallback);
```