# TimLiu-iOS
====
自己总结的iOS、mac开源项目及库。 

###  目录
- [UI](#UI)
    - [模糊效果](#模糊效果)
    - [AutoLayout](#AutoLayout)
    - [富文本](#富文本)
- [动画](#动画)
    - [右滑返回手势](#右滑返回手势)
    - [POP动画](#POP动画)
- [网络相关](#网络相关)
    - [网络连接](#网络连接)
    - [网络测试](#网络测试)
- [数据库](#数据库)
- [测试](#测试)
- [响应式框架](#响应式框架)
- [消息推送](#消息推送)
    - [客户端](#客户端)
    - [服务器端](#服务器端)
- [中文iOS/Mac开发博客列表 ](#中文iOS-Mac开发博客列表)

### 具体内容 =============================
#### UI
##### 模糊效果
 * [FXBlurView](https://github.com/nicklockwood/FXBlurView) - 支持iOS5.0以上版本，支持静态、动态模糊效果，继承与UIView的模糊特效。

##### AutoLayout
 * [Masonry](https://github.com/Masonry/Masonry) - Masonry是一个轻量级的布局框架，拥有自己的描述语法，采用更优雅的链式语法封装自动布局，简洁明了并具有高可读性（ [使用介绍](http://adad184.com/2014/09/28/use-masonry-to-quick-solve-autolayout/) ）。

##### 富文本
 * [RTLabel](https://github.com/honcheng/RTLabel) - 富文本

#### 动画
##### 右滑返回手势
 * [SloppySwiper](https://github.com/fastred/SloppySwiper) - iOS系统自带的UINavigationController要7.0才支持，但不过该手势只能从屏幕左侧边缘识别，如果要扩大到整个屏幕范围怎么办？配合一个SloppySwiper无需代码就可以轻松实现。此库支持iOS5.0以上版本（另外：Nav的title滑动不明显，本人写了2个类似的控件）

##### POP动画
 * [popping](https://github.com/schneiderandre/popping) - popping是一个POP 使用实例工程 

#### 网络相关
##### 网络连接
* [AFNetworking](https://github.com/AFNetworking/AFNetworking) - ASI不升级以后，最多人用的网络连接开源库。
* [Alamofire](https://github.com/Alamofire/Alamofire) - Alamofire是AFNetworking的作者mattt新写的网络请求的swift库。
* [YTKNetwork](https://github.com/yuantiku/YTKNetwork) - 是基于 AFNetworking 封装的 iOS 网络库，提供了更高层次的网络访问抽象。相比 AFNetworking，YTKNetwork 提供了以下更高级的功能：按时间或版本号缓存网络请求内容、检查返回 JSON 内容的合法性、文件的断点续传、批量的网络请求发送、filter和插件机制等。

##### 网络测试
* [Reachability](https://github.com/tonymillion/Reachability) - 苹果提供过一个Reachability类，用于检测网络状态。但是该类由于年代久远，并不支持ARC。该项目旨在提供一个苹果的Reachability类的替代品，支持ARC和block的使用方式。

#### 数据库
* [FMDB](https://github.com/ccgus/fmdb) - sqlite的工具。
* [realm-cocoa](https://github.com/realm/realm-cocoa) - Realm是一个真正为移动设备打造的数据库，同时支持Objective-C和Swfit。Realm宣称其相比Sqlite，在移动设备上有着更好的性能表现。

#### 测试
* [HeapInspector](https://github.com/tapwork/HeapInspector-for-iOS) - HeapInspector是一个用于检测应用中的内存泄漏的开源调试工具。

#### 响应式框架
* [Objective-Chain](https://github.com/iMartinKiss/Objective-Chain) - Objective-Chain是一个面向对象的响应式框架，作者表示该框架吸收了 ReactiveCocoa 的思想，并且想做得更面向对象一些。

#### 消息推送
##### 客户端
* [SGPushDemo](https://github.com/sagiwei/SGPush/tree/master/SGPushDemo) - 消息推送客户端
* [Orbiter](https://github.com/mattt/Orbiter) - 消息推送客户端:Push Notification Registration for iOS.

##### 服务器端
 * [javapns源代码](https://code.google.com/p/javapns/downloads/list) - 消息推送的java服务端代码，注意：DeviceToken中间不能有空格。
 * [pushMeBaby](https://github.com/stefanhafeneger/PushMeBaby) - Mac端消息推送端代码，注意：DeviceToken中间要有空格。

##### 中文iOS-Mac开发博客列表
博客地址 | RSS地址
----- | -----
[OneV's Den](http://onevcat.com) | <http://onevcat.com/atom.xml>
[破船之家](http://beyondvincent.com) | <http://beyondvincent.com/atom.xml>
[NSHipster](http://nshipster.cn) | <http://nshipster.cn/feed.xml>
[Limboy 无网不剩](http://blog.leezhong.com/) | <http://feeds.feedburner.com/lzyy>
[唐巧的技术博客](http://blog.devtang.com) | <http://blog.devtang.com/atom.xml>
[Lex iOS notes](http://ios.lextang.com) | <http://ios.lextang.com/rss>
[念茜的博客](http://nianxi.net) | <http://nianxi.net/feed.xml>
[Xcode Dev](http://blog.xcodev.com) | <http://blog.xcodev.com/atom.xml>
[Ted's Homepage](http://wufawei.com/)| <http://wufawei.com/feed>
[txx's blog](http://blog.t-xx.me) | <http://blog.t-xx.me/atom.xml>
[KEVIN BLOG](http://imkevin.me) | <http://imkevin.me/rss>
[阿毛的蛋疼地](http://www.xiangwangfeng.com) | <http://www.xiangwangfeng.com/atom.xml>
[亚庆的 Blog](http://billwang1990.github.io) | <http://billwang1990.github.io/atom.xml>
[Nonomori](http://nonomori.farbox.com) | <http://nonomori.farbox.com/feed>
[言无不尽](http://tang3w.com) | <http://tang3w.com/atom.xml>
[Wonderffee's Blog](http://wonderffee.github.io) | <http://wonderffee.github.io/atom.xml>
[I'm TualatriX](http://imtx.me) | <http://imtx.me/feed/latest/>
[vclwei](http://vclwei.com) | <http://vclwei.com/posts.rss>
[Cocoabit](http://blog.cocoabit.com) | <http://blog.cocoabit.com/atom.xml>
[nixzhu on scriptogr.am](http://nixzhu.me) | <http://nixzhu.me/feed>
[不会开机的男孩](http://studentdeng.github.io) | <http://studentdeng.github.io/atom.xml>
[Nico](http://www.taofengping.com) | <http://www.taofengping.com/rss.xml>
[阿峰的技术窝窝](http://hufeng825.github.io) | <http://hufeng825.github.io/atom.xml>
[answer_huang](http://answerhuang.duapp.com) | <http://answerhuang.duapp.com/index.php/feed/>
[webfrogs](http://webfrogs.me) | <http://webfrogs.me/feed/>
[代码手工艺人](http://joeyio.com) | <http://joeyio.com/atom.xml>
[Lancy's Blog](http://gracelancy.com) | <http://gracelancy.com/atom.xml>
[I'm Allen](http://www.imallen.com) | <http://www.imallen.com/atom.xml>
[Travis' Blog](http://imi.im/)| <http://imi.im/feed>
[王中周的技术博客](http://wangzz.github.io/) |<http://wangzz.github.io/atom.xml>
[会写代码的猪](http://jiajun.org/)|<http://gaosboy.com/feed/atom/>
[克伟的博客](http://wangkewei.cnblogs.com/)|<http://feed.cnblogs.com/blog/u/23857/rss>
[摇滚诗人](http://cnblogs.com/biosli)|<http://feed.cnblogs.com/blog/u/35410/rss>
[Luke's Homepage](http://geeklu.com/) | <http://geeklu.com/feed/>
[萧宸宇](http://iiiyu.com/) | <http://iiiyu.com/atom.xml>
[Yuan博客](http://www.heyuan110.com/) | <http://www.heyuan110.com/?feed=rss2>
[Shining IO](http://shiningio.com/) | <http://shiningio.com/atom.xml>
[YIFEIYANG--易飞扬的博客](http://www.yifeiyang.net/) | <http://www.yifeiyang.net/feed>
[KooFrank's Blog](http://koofrank.com/) | <http://koofrank.com/rss>
[hello it works](http://helloitworks.com) | <http://helloitworks.com/feed>
[码农人生](http://msching.github.io/) | <http://msching.github.io/atom.xml>
[玉令天下的Blog](http://yulingtianxia.com) | <http://yulingtianxia.com/atom.xml>
[不掏蜂窝的熊](http://www.hotobear.com/) | <http://www.hotobear.com/?feed=rss2>
[猫·仁波切](https://andelf.github.io/) | <https://andelf.github.io/atom.xml>
[煲仔饭](http://ivoryxiong.org/) | <http://ivoryxiong.org/feed.xml>
[里脊串的开发随笔](http://adad184.com) | <http://adad184.com/atom.xml>
