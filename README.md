

提供JPush SDK CocoaPods的镜像，由于官方没有提供相应的服务且网上未找到最新版本的CocoaPods Spec镜像，因此做个镜像方便大家使用CocoaPods 管理 JPush SDK 服务的项目  
=

`pod 'JPushSDK', '~> 1.7.4'`

*PS:因1.7.3版本的spec信息错误导致无法使用，修复该spec错误信息产生与官网版本不符的1.7.4版本*

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
详情请查看官网最新的技术支持文档：[http://docs.jpush.cn/](http://docs.jpush.cn)

若需要手动下载请到[官网下载最新的版本](https://www.jpush.cn/sdk/ios/)

##其他说明

建议每次发布都更新一下最新版本
历史版本实际上没有什么实用价值，只是可以用来重现一些QA的Bug
所有内容均来自[JPush官方网站](https://www.jpush.cn/)
