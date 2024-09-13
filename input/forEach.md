### 格式
```typescript
Transform.forEach(c)
```
#### 所属类: [`Transform`](../Transform.md)

### 描述
遍历子Transform。


### 参数
参数名|类型|描述
---|---|---
c|`callback`|回调函数


### 返回值
类型|描述
---|---
`void`|

### 代码示例
```typescript
let foreachCallback = (child: Transform) => { 
    Debug.Log(child.name);
    };
//遍历子Transform，并输出子对象名称           
this.transform.forEach(foreachCallback);
```

