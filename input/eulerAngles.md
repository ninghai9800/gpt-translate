### 格式
```typescript
Transform.eulerAngles
```
#### 所属类: [`Transform`](../Transform.md)

### 描述
（只读）游戏对象以欧拉角表示的旋转（以度为单位）。

该方法返回游戏对象在世界空间中以欧拉角表示的旋转。在检视面板查看时，可能会看到此返回值与检视面板中的旋转值不同，这是因为检视面板显示本地旋转，更多信息请参考[Transform.localEulerAngles](./localEulerAngles.md)


### 参数
参数名|类型|描述
---|---|---


### 返回值
类型|描述
---|---
`Vector3`|以欧拉角表示的旋转（以度为单位）

### 代码示例
```typescript
OnStart(): void {
    let angle = this.transform.eulerAngles;
    Debug.Log(angle);
    }
```

