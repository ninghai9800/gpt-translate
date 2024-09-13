# SceneManager

SceneManager类，用于管理场景的加载、卸载和切换，以及获取场景的相关信息。


## 静态变量

||
|:---|
|[`SceneManager.activeScene`](SceneManager/activeScene.md)  : `Scene` |
|活动的场景。|
|[`SceneManager.mainScene`](SceneManager/mainScene.md)  : `Scene` |
|主场景。|


## 静态方法

||
|:---|
|[`SceneManager.CreateScene`](SceneManager/CreateScene.md) ( name : `String`  ) : `Scene` |
|在运行时使用一个给定的名称创建一个空的新场景。新的场景将与当前打开的任何现有场景一起添加到层级结构中。|
|[`SceneManager.GetSceneByName`](SceneManager/GetSceneByName.md) ( name : `String`  ) : `Scene` |
|根据场景的名称获取场景。|
|[`SceneManager.UnloadScene`](SceneManager/UnloadScene.md) ( scene : `Scene`  ) : `boolean` |
|卸载目标场景。|
|[`SceneManager.UnloadSceneByName`](SceneManager/UnloadSceneByName.md) ( name : `String`  ) : `boolean` |
|卸载指定名称的场景。|



