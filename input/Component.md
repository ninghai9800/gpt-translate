# Component

###### *继承自 `EngineObject`*
附加到游戏对象的所有内容的基类。

可以通过以下方式获取Component对象:
```typescript
let go = new GameObject();
//为游戏对象添加一个BoxCollider组件
let com = go.AddComponent<BoxCollider>(BoxCollider);
```


## 成员变量

||
|:---|
|[`Component.instanceID`](Component/instanceID.md)  : `number` |
|（只读）对象的实例ID。|
|[`Component.transform`](Component/transform.md)  : `Transform` |
|（只读）附加到此游戏对象的变换组件。|
|[`Component.gameObject`](Component/gameObject.md)  : `GameObject` |
|（只读）当前组件附加到的游戏对象。|
|[`Component.enable`](Component/enable.md)  : `boolean` |
|该组件是否启用的状态。|
|[`Component.allowEnable`](Component/allowEnable.md)  : `boolean` |
|（只读）组件是否启用。|


## 成员方法

||
|:---|
|[`Component.toString`](Component/toString.md) (  ) : `string` |
|返回组件的类型别称(组件名称)。|
|[`Component.OnTriggerEnter`](Component/OnTriggerEnter.md) ( collider : `Collider`  ) : `void` |
|在碰撞器与触发器发生碰撞时调用此方法。|
|[`Component.OnTriggerStay`](Component/OnTriggerStay.md) ( collider : `Collider`  ) : `void` |
|在碰撞器与触发器持续碰撞时调用此方法。|
|[`Component.OnTriggerExit`](Component/OnTriggerExit.md) ( collider : `Collider`  ) : `void` |
|在碰撞器与触发器结束碰撞时调用此方法。|
|[`Component.OnCollisionEnter`](Component/OnCollisionEnter.md) ( collision : `Collision`  ) : `void` |
|在碰撞器与另一个碰撞器发生碰撞时调用此方法。|
|[`Component.OnCollisionStay`](Component/OnCollisionStay.md) ( collision : `Collision`  ) : `void` |
|在两个碰撞器之间的碰撞持续期间调用此方法。|
|[`Component.OnCollisionExit`](Component/OnCollisionExit@method.md) ( collision : `Collision`  ) : `void` |
||
|[`Component.OnCollisionExit`](Component/OnCollisionExit@method.md) ( collision : `ControllerColliderHit`  ) : `void` |
||
|[`Component.OnControllerColliderHit`](Component/OnControllerColliderHit.md) ( collision : `ControllerColliderHit`  ) : `void` |
|当CharactoerController 在执行 Move 方法时发生碰撞后调用此方法。|
|[`Component.OnDestroy`](Component/OnDestroy.md) (  ) : `void` |
|当组件被销毁时调用此方法。|
|[`Component.OnDisable`](Component/OnDisable.md) (  ) : `void` |
|当组件被禁用时调用该方法。|
|[`Component.OnEnable`](Component/OnEnable.md) (  ) : `void` |
|当组件被启用时调用该方法。|
|[`Component.OnDrawGizmos`](Component/OnDrawGizmos.md) (  ) : `void` |
|绘制Gizmos时调用此方法。|
|[`Component.OnDrawGizmosSelected`](Component/OnDrawGizmosSelected.md) (  ) : `void` |
|在选中游戏对象并绘制Gizmos时调用此方法，允许你在编辑器中以选中状态下绘制特定的Gizmos。|
|[`Component.OnUpdate`](Component/OnUpdate.md) (  ) : `void` |
|如果注册此方法，那么在每一帧的开始时都会执行此方法。|
|[`Component.OnLateUpdate`](Component/OnLateUpdate.md) (  ) : `void` |
|在每一帧的 Update 方法之后调用此方法。|
|[`Component.OnFixedUpdate`](Component/OnFixedUpdate.md) (  ) : `void` |
|如果注册此方法，会在固定的时间间隔内被调用，而不是每一帧都被调用。|
|[`Component.OnGUI`](Component/OnGUI.md) (  ) : `void` |
|用于处理图形用户界面（GUI）事件。|
|[`Component.OnStart`](Component/OnStart.md) (  ) : `void` |
|对象加载完成，第一次执行OnUpdate方法前执行此方法。|
|[`Component.OnPostRender`](Component/OnPostRender.md) (  ) : `void` |
|在所有渲染操作完成后调用此方法。|
|[`Component.OnPreRender`](Component/OnPreRender.md) (  ) : `void` |
|在相机渲染之前调用此方法。|
|[`Component.OnLastRender`](Component/OnLastRender.md) (  ) : `void` |
|在绘制ui之后调用。|
|[`Component.OnPreCull`](Component/OnPreCull.md) (  ) : `void` |
|在摄像机进行剔除之前调用此方法。|
|[`Component.OnRenderImage`](Component/OnRenderImage.md) ( src : `RenderTexture` , dst : `RenderTexture`  ) : `void` |
|在相机完成渲染之后调用此方法。|
|[`Component.OnRenderObject`](Component/OnRenderObject.md) (  ) : `void` |
|相机渲染场景后调用此方法。|



