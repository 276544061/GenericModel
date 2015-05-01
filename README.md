# GenericModel
Objective-C Model和JSON互相转换的简单高效框架

## Features
* GenericModel 支持`Objective-C` `Model`、`NSDictionary`、`JSON`之间互相转换，框架非常简单高效，内部字段反射设置有缓存，用`Objective-C`中的`Protocol`限定`NSArray`，`NSDictionary`等`容器`类的类型，防止容器类型变量类型使用错误，类似`Java`中容器类型的`泛型`。
* 支持的类型转换
  * `NSDictionary <--> Objective-C Model`
  * `JSON <--> Objective-C Model`
