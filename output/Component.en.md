# Component

###### *Inherited from `EngineObject`*
The base class for all content attached to game objects.

You can get a Component object in the following way:
```typescript
let go = new GameObject();
// Add a BoxCollider component to the game object
let com = go.AddComponent<BoxCollider>(BoxCollider);
```


## Member Variables

||
|:---|
|[`Component.instanceID`](Component/instanceID.md)  : `number` |
|(Read-only) The instance ID of the object.|
|[`Component.transform`](Component/transform.md)  : `Transform` |
|(Read-only) The transform component attached to this game object.|
|[`Component.gameObject`](Component/gameObject.md)  : `GameObject` |
|(Read-only) The game object the current component is attached to.|
|[`Component.enable`](Component/enable.md)  : `boolean` |
|The state of whether the component is enabled or not.|
|[`Component.allowEnable`](Component/allowEnable.md)  : `boolean` |
|(Read-only) Whether the component is enabled or not.|


## Member Methods

||
|:---|
|[`Component.toString`](Component/toString.md) (  ) : `string` |
|Returns the type alias (component name) of the component.|
|[`Component.OnTriggerEnter`](Component/OnTriggerEnter.md) ( collider : `Collider`  ) : `void` |
|Called when a collider enters a trigger.|
|[`Component.OnTriggerStay`](Component/OnTriggerStay.md) ( collider : `Collider`  ) : `void` |
|Called while a collider is colliding with a trigger.|
|[`Component.OnTriggerExit`](Component/OnTriggerExit.md) ( collider : `Collider`  ) : `void` |
|Called when a collider exits a trigger.|
|[`Component.OnCollisionEnter`](Component/OnCollisionEnter.md) ( collision : `Collision`  ) : `void` |
|Called when a collider enters another collider.|
|[`Component.OnCollisionStay`](Component/OnCollisionStay.md) ( collision : `Collision`  ) : `void` |
|Called while two colliders are colliding.|
|[`Component.OnCollisionExit`](Component/OnCollisionExit@method.md) ( collision : `Collision`  ) : `void` |
||
|[`Component.OnCollisionExit`](Component/OnCollisionExit@method.md) ( collision : `ControllerColliderHit`  ) : `void` |
||
|[`Component.OnControllerColliderHit`](Component/OnControllerColliderHit.md) ( collision : `ControllerColliderHit`  ) : `void` |
|Called after a collision occurs when a CharactoerController is executing the Move method.|
|[`Component.OnDestroy`](Component/OnDestroy.md) (  ) : `void` |
|Called when the component is destroyed.|
|[`Component.OnDisable`](Component/OnDisable.md) (  ) : `void` |
|Called when the component is disabled.|
|[`Component.OnEnable`](Component/OnEnable.md) (  ) : `void` |
|Called when the component is enabled.|
|[`Component.OnDrawGizmos`](Component/OnDrawGizmos.md) (  ) : `void` |
|Called when drawing Gizmos.|
|[`Component.OnDrawGizmosSelected`](Component/OnDrawGizmosSelected.md) (  ) : `void` |
|Called when drawing Gizmos while the game object is selected, allowing you to draw specific Gizmos in a selected state in the editor.|
|[`Component.OnUpdate`](Component/OnUpdate.md) (  ) : `void` |
|If this method is registered, it will be executed at the beginning of each frame.|
|[`Component.OnLateUpdate`](Component/OnLateUpdate.md) (  ) : `void` |
|Called after the Update method of each frame.|
|[`Component.OnFixedUpdate`](Component/OnFixedUpdate.md) (  ) : `void` |
|If this method is registered, it will be called at fixed intervals instead of every frame.|
|[`Component.OnGUI`](Component/OnGUI.md) (  ) : `void` |
|Used to handle graphical user interface (GUI) events.|
|[`Component.OnStart`](Component/OnStart.md) (  ) : `void` |
|Called after the object is loaded and before the OnUpdate method is executed for the first time.|
|[`Component.OnPostRender`](Component/OnPostRender.md) (  ) : `void` |
|Called after all rendering operations are completed.|
|[`Component.OnPreRender`](Component/OnPreRender.md) (  ) : `void` |
|Called before the camera renders.|
|[`Component.OnLastRender`](Component/OnLastRender.md) (  ) : `void` |
|Called after drawing UI elements.|
|[`Component.OnPreCull`](Component/OnPreCull.md) (  ) : `void` |
|Called before the camera performs culling.|
|[`Component.OnRenderImage`](Component/OnRenderImage.md) ( src : `RenderTexture` , dst : `RenderTexture`  ) : `void` |
|Called after the camera finishes rendering.|
|[`Component.OnRenderObject`](Component/OnRenderObject.md) (  ) : `void` |
|Called after the camera renders the scene.|