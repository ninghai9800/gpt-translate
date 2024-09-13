### 格式
```typescript
Transform.name
```
#### 所属类: [`Transform`](../Transform.md)

### 描述
（只读）当前变化组件附加上的游戏对象的名称。


### 参数
参数名|类型|描述
---|---|---


### 返回值
类型|描述
---|---
`string`|游戏对象的名称

### 代码示例
```typescript
OnStart(): void {
    let name = this.transform.name;
    Debug.Log(name);
    }
```

