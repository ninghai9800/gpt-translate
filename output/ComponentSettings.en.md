# ComponentSettings

Script decorator used to control the order of script initialization.


## Static Methods

||
|:---|
|[`ComponentSettings.ExecuteOrder`](ComponentSettings/ExecuteOrder.md) ( order : `number`  ) : `void` |
Controls the order of script execution, with a default value of 2000. Scripts with smaller values will execute first, while scripts with larger values will execute later.|
|[`ComponentSettings.ExecuteMultiple`](ComponentSettings/ExecuteMultiple.md) (  ) : `void` |
By default, only one component of the same type can be added to the same object. Using this decorator allows multiple components of the same type to be added to the same object.|