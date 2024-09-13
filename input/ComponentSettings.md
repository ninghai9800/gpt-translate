# ComponentSettings

脚本装饰器，用于控制脚本初始化的顺序。


## 静态方法

||
|:---|
|[`ComponentSettings.ExecuteOrder`](ComponentSettings/ExecuteOrder.md) ( order : `number`  ) : `void` |
|控制脚本执行顺序，默认值为2000，值越小的越先执行，值越大越后执行。|
|[`ComponentSettings.ExecuteMultiple`](ComponentSettings/ExecuteMultiple.md) (  ) : `void` |
|默认情况下同一个对象只能添加一个同类型的组件。使用此装饰器之后，同一个对象可添加多个同类型组件。|



