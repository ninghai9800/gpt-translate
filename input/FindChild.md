### 格式
```typescript
Transform.FindChild(name)
```
#### 所属类: [`Transform`](../Transform.md)

### 描述
根据当前Transform附加游戏对象的名称查找子Transform。

该方法是查找相对路径，即相对于当前Transform对象的路径。


### 参数
参数名|类型|描述
---|---|---
name|`string`|Transform附加游戏对象名称


### 返回值
类型|描述
---|---
`Transform`|子Transform

### 代码示例
```typescript
OnStart(): void {
    let transform = this.transform;
    let child = transform.FindChild("childname");
    }
```

