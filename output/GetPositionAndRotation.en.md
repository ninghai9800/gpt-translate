### Format
```typescript
Transform.GetPositionAndRotation(ref_pos, ref_rot)
```
#### Belongs to class: [`Transform`](../Transform.md)

### Description
Get the position and rotation of the Transform component in world space.

When getting both the position and rotation of the Transform at the same time, calling this method is more efficient than querying them separately.


### Parameters
Parameter|Type|Description
---|---|---
ref_pos|`Vector3`|World coordinates
ref_rot|`Quaternion`|World rotation


### Return
Type|Description
---|---
`void`|

### Code Example
```typescript
let transform = this.transform;
let vec3_o = new Vector3;
let quat_o = new Quaternion;
transform.GetPositionAndRotation(vec3_o, quat_o);
```