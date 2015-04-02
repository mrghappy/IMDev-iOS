IMDev-iOS
=========

IMDev——爱萌开发者，是由爱萌基于IMSDK开发并完全开源的的第一款IM APP，面向于开发者群体。

最新版本号：v1.2.5 修复了群聊bug

## 一分钟集成IM SDK

* 1、下载IMSDK，并整合到现有项目中；
* 2、添加必要的系统框架，配置编译选项；
* 3、注册成为IMSDK开发者，并创建一个应用；
* 4、参照 iOS 无界面版API 和 iOS 界面控件版 实现各种IM业务功能。

1、下载IM SDK，并整合到现有项目中 

* a、进入IMSDK官网下载iOS无界面版IMSDK
![img](http://docs.imsdk.im/download/attachments/1343489/%E4%B8%8B%E8%BD%BD.jpg?version=1&modificationDate=1415244531000&api=v2&effects=border-polaroid,blur-border)

* b、将下载到的文件解压，得到一个IMSDKDemo的目录
* c、在IMSDKDemo/IMSDKDemo目录下找到Release-iphonesimulator，将Release-iphonesimulator目录拖入您所要嵌入的工程目录(Release-iphoneos为真机目录)：
![img](http://docs.imsdk.im/download/attachments/1343489/%E5%B5%8C%E5%85%A5IMSDK.png?version=1&modificationDate=1415249293000&api=v2&effects=border-polaroid,blur-border)

2、添加必要的系统框架，配置编译选项

* a、添加必要的系统框架，CoreLocation、CoreTelephony、SystemConfiguration、ImageIO、QuartzCore、CoreTelephony：
![img](http://docs.imsdk.im/download/attachments/1343489/%E6%B7%BB%E5%8A%A0%E7%B3%BB%E7%BB%9F%E6%A1%86%E6%9E%B6.png?version=1&modificationDate=1415247500000&api=v2&effects=border-polaroid,blur-border)

* b、设置链接选项，-licucore、 -ObjC：
![img](http://docs.imsdk.im/download/attachments/1343489/%E8%AE%BE%E7%BD%AE%E9%93%BE%E6%8E%A5%E9%80%89%E9%A1%B9.png?version=1&modificationDate=1415247460000&api=v2&effects=border-polaroid,blur-border)

3、注册成为IMSDK开发者，并创建一个应用

* a、打开浏览器，输入imsdk.im进入官网填写资料，注册开发者信息：
![img](http://docs.imsdk.im/download/attachments/1343489/%E6%B3%A8%E5%86%8C.jpg?version=1&modificationDate=1411802147000&api=v2&effects=border-polaroid,blur-border)

* b、添加应用，获取appKey
![img](http://docs.imsdk.im/download/attachments/1343489/%E6%B7%BB%E5%8A%A0%E5%BA%94%E7%94%A8.jpeg?version=1&modificationDate=1411802127000&api=v2&effects=border-polaroid,blur-border)
![img](http://docs.imsdk.im/download/attachments/1343489/%E8%8E%B7%E5%8F%96appkey.jpg?version=1&modificationDate=1411802134000&api=v2&effects=border-polaroid,blur-border)


* c、如需实现APNs则需要上传推送证书（可选）
1)、选择开发环境或生产环境（上线使用）    2)、上传苹果APNs推送证书文件并填写对应证书密码   3)、保存

注意：APNs p12证书（开发）指苹果APNs推送的开发环境证书，APNs p12证书（生产）指苹果APNs推送的生产环境证书。
![img](http://docs.imsdk.im/download/attachments/1343489/APNs%E8%AF%81%E4%B9%A6.png?version=1&modificationDate=1422872283000&api=v2)

4、参照 [here](http://docs.imsdk.im/pages/viewpage.action?pageId=1343957) 中的API接口文档实现IM功能。


##成功编译后IMSDK之后的效果
* 最近联系人界面
![img](http://static.oschina.net/uploads/code/201503/23165540_cmod.png)
* 好友列表
![img](http://static.oschina.net/uploads/code/201503/23165540_6DcO.png)
* 一对一聊天界面
![img](http://static.oschina.net/uploads/code/201503/23165540_OkIN.png)
* 群聊界面
![img](http://static.oschina.net/uploads/code/201504/02162330_aldW.png)
* 周围用户界面
![img](http://static.oschina.net/uploads/code/201503/23165540_8Zsh.png)
