### 格式
```typescript
Transform.childCount
```
#### 所属类: [`Transform`](../Transform.md)

### 描述
（只读）当前Transform的子级数量（父级Transform不包括在内）。


### 参数
参数名|类型|描述
---|---|---


### 返回值
类型|描述
---|---
`number`|子级数量

### 代码示例
```typescript
OnStart(): void {
    let count = this.transform.childCount;
    Debug.Log(count);
    }
```

