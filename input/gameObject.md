### 格式
```typescript
Transform.gameObject
```
#### 所属类: [`Transform`](../Transform.md)

### 描述
（只读）当前Transform组件附加到的游戏对象。
组件始终附加在游戏对象上。


### 参数
参数名|类型|描述
---|---|---


### 返回值
类型|描述
---|---
`GameObject`|游戏对象

### 代码示例
```typescript
OnStart(): void {
    let go = this.transform.gameObject;
    }
```

