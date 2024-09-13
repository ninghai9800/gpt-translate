### 格式
```typescript
Transform.forward
```
#### 所属类: [`Transform`](../Transform.md)

### 描述
（只读）游戏对象在世界空间中沿Z轴正方向的单位向量。

旋转游戏对象时，该值也会改变方向。


### 参数
参数名|类型|描述
---|---|---


### 返回值
类型|描述
---|---
`Vector3`|z轴正方向的单位向量

### 代码示例
```typescript
OnStart(): void {
    let forward = this.transform.forward;
    }
```

