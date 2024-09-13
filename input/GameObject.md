# GameObject

###### *继承自 `EngineObject`*
游戏实体对象类，用于操作游戏中的各种实体对象。


## 构造方法

||
|:---|
|[`GameObject.new`](GameObject/GameObject.md) ( name : `string?`  )|
||


## 成员变量

||
|:---|
|[`GameObject.instanceID`](GameObject/instanceID.md)  : `number` |
|（只读）当前对象的实例ID。|
|[`GameObject.transform`](GameObject/transform.md)  : `Transform` |
|（只读）当前对象的 transform 属性。|
|[`GameObject.name`](GameObject/name.md)  : `string` |
|当前对象的名字。|
|[`GameObject.scene`](GameObject/scene.md)  : `Scene` |
|（只读）当前对象所在的场景。|
|[`GameObject.allowEnable`](GameObject/allowEnable.md)  : `boolean` |
|（只读）当前对象在对象所在的对象树上的链式启用状态。|
|[`GameObject.isStatic`](GameObject/isStatic.md)  : `boolean` |
|（只读）当前对象是否是静态对象。|
|[`GameObject.enable`](GameObject/enable.md)  : `boolean` |
|当前对象是否启用。|
|[`GameObject.layer`](GameObject/layer.md)  : `number` |
|当前对象的层级。|


## 成员方法

||
|:---|
|[`GameObject.GetComponents`](GameObject/GetComponents.md) ( type : `Component`  ) : `T\|null` []  |
|返回 GameObject 中类型为 type 的所有组件。|
|[`GameObject.AddComponent`](GameObject/AddComponent.md) ( type : `Component`  ) : `T\|null` |
|根据组件类型为当前游戏对象添加组件。|
|[`GameObject.GetComponentsInChildren`](GameObject/GetComponentsInChildren.md) ( type : `Component`  ) : `T\|null` []  |
|获取指定类型的组件在一个GameObject及其所有子GameObject中的实例。|
|[`GameObject.GetComponent`](GameObject/GetComponent.md) ( type : `Component`  ) : `T\|null` |
|通过指定组件的类型来获取游戏对象上的组件。|
|[`GameObject.GetComponentInChildren`](GameObject/GetComponentInChildren.md) ( type : `Component`  ) : `T\|null` |
|获取指定游戏对象或游戏对象的任何子级上的第一个该类型的组件。|
|[`GameObject.GetComponentsInParent`](GameObject/GetComponentsInParent.md) ( type : `Component`  ) : `T\|null` []  |
|获取指定类型的组件在一个GameObject及其所有父级GameObject中的实例。|
|[`GameObject.GetComponentInParent`](GameObject/GetComponentInParent.md) ( type : `Component`  ) : `T\|null` |
|获取指定游戏对象或游戏对象的任何父级上的第一个该类型的组件。|


## 静态方法

||
|:---|
|[`GameObject.DestroyGameObject`](GameObject/DestroyGameObject.md) ( go : `GameObject`  ) : `void` |
|删除实体对象。|
|[`GameObject.DestroyComponent`](GameObject/DestroyComponent.md) ( com : `Component`  ) : `void` |
|删除组件。|
|[`GameObject.CreatePrimitive`](GameObject/CreatePrimitive.md) ( type : `PrimitiveType`  ) : `GameObject` |
|创建一个带有MeshRender组件的 GameObject 对象，并且具有与 type 对应的网格数据。|
|[`GameObject.Instantiate`](GameObject/Instantiate.md) ( origin : `GameObject`  ) : `GameObject` |
|实例化一个与参数对象属性相同的实体对象。|



