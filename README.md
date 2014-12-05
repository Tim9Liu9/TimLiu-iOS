# TimLiu-iOS
====
自己总结的iOS、mac开源项目及库。

###  目录
- [UI](#UI)
    - [模糊效果](#模糊效果) 
    - [AutoLayout](#AutoLayout) 
    - [POP动画](#POP动画) 
- [动画](#动画)
    - [右滑返回手势](#右滑返回手势) 
- [网络相关](#网络相关)
    - [网络连接](#网络连接)
    - [网络测试](#网络测试)
- [数据库](#数据库)
- [测试](#测试)
- [消息推送](#消息推送)
    - [客户端](#客户端) 
    - [服务器端](#服务器端) 


### 具体内容 =============================
#### UI
##### 模糊效果
 * [FXBlurView](https://github.com/nicklockwood/FXBlurView) - 支持iOS5.0以上版本，支持静态、动态模糊效果，继承与UIView的模糊特效。

##### AutoLayout 
 * [Masonry](https://github.com/Masonry/Masonry) - Masonry是一个轻量级的布局框架，拥有自己的描述语法，采用更优雅的链式语法封装自动布局，简洁明了并具有高可读性（ [使用介绍](http://adad184.com/2014/09/28/use-masonry-to-quick-solve-autolayout/) ）。

##### POP动画 
 * [popping](https://github.com/schneiderandre/popping) - popping是一个POP 使用实例工程。

#### 动画
##### 右滑返回手势
 * [SloppySwiper](https://github.com/fastred/SloppySwiper) - iOS系统自带的UINavigationController要7.0才支持，但不过该手势只能从屏幕左侧边缘识别，如果要扩大到整个屏幕范围怎么办？配合一个SloppySwiper无需代码就可以轻松实现。此库支持iOS5.0以上版本（另外：Nav的title滑动不明显，本人写了2个类似的控件）

#### 网络相关
##### 网络连接
* [AFNetworking](https://github.com/AFNetworking/AFNetworking) - ASI不升级以后，最多人用的网络连接开源库。
* [Alamofire](https://github.com/Alamofire/Alamofire) - Alamofire是AFNetworking的作者mattt新写的网络请求的swift库。

##### 网络测试
* [Reachability](https://github.com/tonymillion/Reachability) - 苹果提供过一个Reachability类，用于检测网络状态。但是该类由于年代久远，并不支持ARC。该项目旨在提供一个苹果的Reachability类的替代品，支持ARC和block的使用方式。

#### 数据库
* [FMDB](https://github.com/ccgus/fmdb) - sqlite的工具。
* [realm-cocoa](https://github.com/realm/realm-cocoa) - Realm是一个真正为移动设备打造的数据库，同时支持Objective-C和Swfit。Realm宣称其相比Sqlite，在移动设备上有着更好的性能表现。

#### 测试
* [HeapInspector](https://github.com/tapwork/HeapInspector-for-iOS) - HeapInspector是一个用于检测应用中的内存泄漏的开源调试工具。

#### 消息推送
##### 客户端
* [SGPushDemo](https://github.com/sagiwei/SGPush/tree/master/SGPushDemo) - 消息推送客户端
* [Orbiter](https://github.com/mattt/Orbiter) - 消息推送客户端:Push Notification Registration for iOS.

##### 服务器端
 * [javapns源代码](https://code.google.com/p/javapns/downloads/list) - 消息推送的java服务端代码，注意：DeviceToken中间不能有空格。
 * [pushMeBaby](https://github.com/stefanhafeneger/PushMeBaby) - Mac端消息推送端代码，注意：DeviceToken中间要有空格。
