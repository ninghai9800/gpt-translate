# SceneManager

The SceneManager class is used to manage the loading, unloading, and switching of scenes, as well as to retrieve information about scenes.


## Static Variables

||
|:---|
|[`SceneManager.activeScene`](SceneManager/activeScene.md)  : `Scene` |
|The currently active scene.|
|[`SceneManager.mainScene`](SceneManager/mainScene.md)  : `Scene` |
|The main scene.|


## Static Methods

||
|:---|
|[`SceneManager.CreateScene`](SceneManager/CreateScene.md) ( name : `String`  ) : `Scene` |
|Creates a new empty scene with a given name at runtime. The new scene will be added to the hierarchy along with any currently open scenes.|
|[`SceneManager.GetSceneByName`](SceneManager/GetSceneByName.md) ( name : `String`  ) : `Scene` |
|Retrieves a scene based on its name.|
|[`SceneManager.UnloadScene`](UnloadScene.md) ( scene : `Scene`  ) : `boolean` |
|Unloads the target scene.|
|[`SceneManager.UnloadSceneByName`](UnloadSceneByName.md) ( name : `String`  ) : `boolean` |
|Unloads the scene with the specified name.|