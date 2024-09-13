### 格式
```typescript
Transform.hasChanged
```
#### 所属类: [`Transform`](../Transform.md)

### 描述
（只读）Transform是否发生变化。
对Transform的更改可以是任何可以导致其矩阵重新计算的内容：对其位置、旋转或比例的任何调整。在设置该值前，会检查旧值和新值是否不同。


### 参数
参数名|类型|描述
---|---|---


### 返回值
类型|描述
---|---
`boolean`|Transform是否有更改

### 代码示例

