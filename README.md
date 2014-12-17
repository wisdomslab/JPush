

提供JPush SDK CocoaPods的镜像，由于官方没有提供相应的服务且网上未找到最新版本的CocoaPods Spec镜像，因此做个镜像方便大家使用CocoaPods 管理 JPush SDK 服务的项目  
=

`pod 'JPushSDK', '~> 1.8.2'`

*PS:对于旧版本 xcode 用户或者暂不想支持到 iOS 8 的可以继续使用旧的版本* `pod 'JPushSDK', '~>1.7.4'`

##JPush iOS SDK v1.8.2 版本发布

Change Log
优化改进：修复一些可能引起崩溃问题  
优化改进：修复部分情况下获取不到 RegistrationID 的问题

##JPush iOS SDK v1.8.1 版本发布  

Change Log  
优化改进：修改与部分第三方 SDK 变量冲突问题  
优化改进：修复 iOS5 版本 Demo 按钮异常  


##JPush iOS SDK v1.8.0 版本发布  

Change Log  
新增功能：增加 iOS8 支持  
新增功能：增加本地推送 API  
新增功能：增加地理位置信息上报  
新增功能：增加崩溃日志上报  
新增功能：增加日志等级修改  
优化改进：修改上报重试机制  
优化改进：修复 setTagAlias 时回调类被释放时崩溃bug  
优化改进：全新的参考 Demo  


##JPush iOS SDK v1.7.4 版本发布

Change Log  
新增功能：增加设置 badge 值更新到 JPush 服务器功能。  
此 SDK 版本配合服务器端推送通知 badge +1 功能使用，实现群推 iOS 通知时 badge 值各用户不同的值。  


##JPush iOS SDK v1.7.3 版本发布  

Change Log  
优化改进：配合 API V3，更好的支持自定义消息的解析。  
升级提示  
建议升级。

##升级指南
替换 lib 文件夹里的文件 .a 文件为新版本;  
替换 lib 文件夹里的文件 .h 文件为新版本;  
工程添加libz.dylib、Security.framework两个库;  
新版本不再需要 libPushSDK-Simulator.a 。如果你的老版本 SDK 包含此文件，请删除。  

##技术支持
详情请查看官网最新的技术支持文档：[http://docs.jpush.cn/](http://docs.jpush.cn)  或 [http://docs.jpush.io/](http://docs.jpush.io/)

若需要手动下载请到[官网下载最新的版本](https://www.jpush.cn/sdk/ios/)

##其他说明

建议每次发布都更新一下最新版本
历史版本实际上没有什么实用价值，只是可以用来重现一些QA的Bug
所有内容均来自[JPush官方网站](https://www.jpush.cn/)
