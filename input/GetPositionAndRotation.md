### 格式
```typescript
Transform.GetPositionAndRotation(ref_pos, ref_rot)
```
#### 所属类: [`Transform`](../Transform.md)

### 描述
获取Transform组件在世界空间中的位置和旋转。

当同时获取Transform的位置和旋转时，调用此方法比单独查询位置和旋转更有效。


### 参数
参数名|类型|描述
---|---|---
ref_pos|`Vector3`|世界坐标
ref_rot|`Quaternion`|世界旋转


### 返回值
类型|描述
---|---
`void`|

### 代码示例
```typescript
let transform = this.transform;
let vec3_o = new Vector3;
let quat_o = new Quaternion;
transform.GetPositionAndRotation(vec3_o, quat_o);
```

