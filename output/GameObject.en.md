# GameObject

###### *Inherited from `EngineObject`*
A class for game entity objects, used to manipulate various entity objects in the game.


## Constructor

||
|:---|
|[`GameObject.new`](GameObject/GameObject.md) ( name : `string?`  )|
||


## Member Variables

||
|:---|
|[`GameObject.instanceID`](GameObject/instanceID.md)  : `number` |
|(Read-only) The instance ID of the current object.|
|[`GameObject.transform`](GameObject/transform.md)  : `Transform` |
|(Read-only) The transform property of the current object.|
|[`GameObject.name`](GameObject/name.md)  : `string` |
|The name of the current object.|
|[`GameObject.scene`](GameObject/scene.md)  : `Scene` |
|(Read-only) The scene where the current object is located.|
|[`GameObject.allowEnable`](GameObject/allowEnable.md)  : `boolean` |
|(Read-only) The chained enable status of the current object in the object tree it belongs to.|
|[`GameObject.isStatic`](GameObject/isStatic.md)  : `boolean` |
|(Read-only) Whether the current object is a static object.|
|[`GameObject.enable`](GameObject/enable.md)  : `boolean` |
|Whether the current object is enabled.|
|[`GameObject.layer`](GameObject/layer.md)  : `number` |
|The layer of the current object.|


## Member Methods

||
|:---|
|[`GameObject.GetComponents`](GameObject/GetComponents.md) ( type : `Component`  ) : `T\|null` []  |
|Returns all components of type `type` in the GameObject.|
|[`GameObject.AddComponent`](GameObject/AddComponent.md) ( type : `Component`  ) : `T\|null` |
|Adds a component of the specified type to the current game object.|
|[`GameObject.GetComponentsInChildren`](GameObject/GetComponentsInChildren.md) ( type : `Component`  ) : `T\|null` []  |
|Gets instances of the specified type of component in a GameObject and all its child GameObjects.|
|[`GameObject.GetComponent`](GameObject/GetComponent.md) ( type : `Component`  ) : `T\|null` |
|Gets the component of the specified type on the game object.|
|[`GameObject.GetComponentInChildren`](GameObject/GetComponentInChildren.md) ( type : `Component`  ) : `T\|null` |
|Gets the first component of the specified type on the specified game object or any of its children.|
|[`GameObject.GetComponentsInParent`](GameObject/GetComponentsInParent.md) ( type : `Component`  ) : `T\|null` []  |
|Gets instances of the specified type of component in a GameObject and all its parent GameObjects.|
|[`GameObject.GetComponentInParent`](GameObject/GetComponentInParent.md) ( type : `Component`  ) : `T\|null` |
|Gets the first component of the specified type on the specified game object or any of its parents.|


## Static Methods

||
|:---|
|[`GameObject.DestroyGameObject`](GameObject/DestroyGameObject.md) ( go : `GameObject`  ) : `void` |
|Deletes the entity object.|
|[`GameObject.DestroyComponent`](GameObject/DestroyComponent.md) ( com : `Component`  ) : `void` |
|Deletes the component.|
|[`GameObject.CreatePrimitive`](GameObject/CreatePrimitive.md) ( type : `PrimitiveType`  ) : `GameObject` |
|Creates a GameObject object with a MeshRender component and mesh data corresponding to the `type`.|
|[`GameObject.Instantiate`](GameObject/Instantiate.md) ( origin : `GameObject`  ) : `GameObject` |
|Instantiates an entity object with the same properties as the parameter object.|