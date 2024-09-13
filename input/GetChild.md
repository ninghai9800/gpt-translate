### 格式
```typescript
Transform.GetChild(index)
```
#### 所属类: [`Transform`](../Transform.md)

### 描述
根据索引获取子Transform（索引从0开始）。

如果该变换没有子项，或者index参数的值大于子项数，会返回nil。子项数可以通过 [Transform.childCount](./childCount.md)获取。


### 参数
参数名|类型|描述
---|---|---
index|`number`|Transform的索引值


### 返回值
类型|描述
---|---
`Transform`|子Transform

### 代码示例
```typescript
OnStart(): void {
    let transform = this.transform;
    let child = transform.FindChild(0);
    }
```

