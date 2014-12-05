# TimLiu-iOS
==========
自己总结的iOS、mac开源项目及库。

###  目录
- [UI](#UI)
    - [模糊效果](#模糊效果) 

- [动画](#动画)
    - [右滑返回手势](#右滑返回手势) 

- [消息推送](#消息推送)
    - [客户端](#客户端) 
    - [服务器端](#服务器端) 


## 具体内容 =============================
## UI
### 模糊效果
 * [FXBlurView](https://github.com/nicklockwood/FXBlurView) - 支持iOS5.0以上版本，支持静态、动态模糊效果，继承与UIView的模糊特效。

## 动画
### 右滑返回手势
 * [SloppySwiper](https://github.com/fastred/SloppySwiper) - iOS系统自带的UINavigationController要7.0才支持，但不过该手势只能从屏幕左侧边缘识别，如果要扩大到整个屏幕范围怎么办？配合一个SloppySwiper无需代码就可以轻松实现。此库支持iOS5.0以上版本（另外：Nav的title滑动不明显，本人写了2个类似的控件）

# 消息推送
### 客户端
### 服务器端
 * [javapns源代码](https://code.google.com/p/javapns/downloads/list) - 消息推送的java服务端代码，注意：DeviceToken中间不能有有空格。
 * [pushMeBaby](https://github.com/stefanhafeneger/PushMeBaby) - Mac端消息推送端代码，注意：DeviceToken中间有空格。
