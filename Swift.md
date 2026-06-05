# TimLiu-iOS

[Objective-C版本点击这里](https://github.com/Tim9Liu9/TimLiu-iOS/blob/master/README.md)
欢迎加入QQ群交流:  594119878

### About

A curated list of iOS objective-C ecosystem.

### How to Use

- Simply press <kbd>command</kbd> + <kbd>F</kbd> + <kbd>"xxx@"</kbd> to search for a keyword
- Go through our *Content Menu*

### Feedback

期待大家和我们一起共同维护，同时也期望大家随时能提出宝贵的意见（直接提交issues即可）。请广大网友只按照目录结构（即使目录结构有问题）添加三方库，并提交pull request。目录问题大家提出issues后楼主会及时更改的。

## 目录
- [完整App@](#完整app)
- [App框架@](#app框架)
  - [响应式框架@](#响应式框架)
  - [页面路由@](#页面路由)
  - [版本管理@](#版本管理)
  - [混合开发@](#混合开发)
- [安全@](#安全)
- [网络@](#网络)
  - [网络请求@](#网络请求)
  - [图像获取@](#图像获取)
  - [网络聊天@](#网络聊天)
  - [网络测试@](#网络测试)
  - [网页框架@](#网页框架)
  - [网络解析@](#网络解析)
      - [JSON@](#json)
      - [xml@](#xml)
      - [CSV@](#csv)
- [数据存储@](#数据存储)
  - [缓存处理@](#缓存处理)
  - [CoreData@](#CoreData)
  - [数据库@](#数据库)
  - [钥匙链@](#钥匙链)
- [多线程@](#多线程)
- [多媒体@](#多媒体)
  - [相机@](#相机)
  - [二维码@](#二维码)
  - [PDF@](#pdf)
  - [GIF@](#GIF)
  - [音频@](#音频)
  - [媒体流@](#媒体流)
  - [视频@](#视频)
    - [视频播放@](#视频播放)
    - [视频处理@](#视频处理)
- [图像@](#图像)
  - [人脸识别@](#人脸识别)
  - [图像识别@](#图像识别)
  - [图像处理@](#图像处理)
  - [图像缓存@](#图像缓存)
  - [图像浏览@](#图像浏览)
  - [相册@](相册#)
- [数据结构/算法@](#数据结构/算法)
  - [数学@](#数学)
- [动画@](#动画)
  - [转场动画@](#转场动画)
  - [特效@](@特效)
  - [侧滑与右滑返回手势@](#侧滑与右滑返回手势)
  - [gif动画@](#gif动画)
  - [其他动画@](#其他动画)
- [富文本@](富文本)
 - [文本@](文本)
 - [字体@](字体)
- [UI@](#ui)
  - [SwiftUI@](#SwiftUI)
  - [AutoLayout@](#autolayout)
  - [列表@](#列表)
  - [scrollView@](#scrollView)
  - [HUD与Toast@](#hud与toast)
  - [图表@](#图表)
  - [IM@](#IM)
  - [WebView@](#webview)
  - [日历@](#日历)
  - [时间@](#时间)
  - [下拉刷新@](#下拉刷新)
  - [模糊效果@](#模糊效果)
  - [选择器@](#选择器)
  - [隐藏与显示@](#隐藏与显示)
  - [对话框@](#对话框)
  - [pop@](#pop)
  - [导航栏@](#导航栏)
  - [瀑布流@](#瀑布流)
  - [菜单@](#菜单)
  - [TabBar@](#tabbar)
  - [进度@](#进度)
  - [引导页@](#引导页)
  - [page@](#page)
  - [评分@](#评分)
  - [键盘@](#键盘)
  - [搜索@](#搜索)
  - [Button@](#Button)
  - [3D@](#3D)
  - [Slider@](#Slider)
  - [其他UI@](#其他ui)
- [工具@](#工具)
  - [Category@](#category)
  - [Color@](#Color)
  - [Xcode工具@](#Xcode工具)
  - [压缩解压@](#压缩解压)
- [测试调试@](#测试调试)
  - [分析@](#分析)
  - [优化@](#优化)
  - [日志@](#日志)
- [游戏@](#游戏)
- [小样@](#小样)
  - [VR@](#VR)
  - [AR@](#AR)
  - [机器学习@](#机器学习)
  - [AI@](#AI)
  - [全景@](#全景)
  - [VPN@](#vpn)
  - [蓝牙@][#蓝牙]
  - [地图@](#地图)
  - [通知@](#通知)
  - [电池@](#电池)
- [Swift学习资料@](#swift学习资料)
  - [Swift小Demo@](#Swift小Demo)
- [其他开源总结@](#其他开源总结)
- [iOS版本适配@](#iOS版本适配)
- [其他库@](#其他库)
- [AppleWatch@](#applewatch)
- [TV@](#TV)
- [mac@](#mac)
- [服务端@](#服务端)

-------
具体内容

#### rumtime@

* [swift-corelibs-foundation](https://github.com/apple/swift-corelibs-foundation/) - CFRunLoopRef源码.

#### 完整App@

* [open-source-ios-apps](https://github.com/dkhamsing/open-source-ios-apps) - Collaborative List of Open-Source iOS Apps 非常赞👍👍👍 .
* [Swift 30 Projects](https://github.com/soapyigu/Swift30Projects) - 最新 Swift 3.0 的30个小App，更注重代码规范和架构设计(故胤道长).
* [V2ex-Swift](https://github.com/Finb/V2ex-Swift) - 用 Swift 写的 V2EX 客户端.
* [iBBS-Swift](https://github.com/iAugux/iBBS-Swift) - “新手开源一个用Swift（2.0）写的论坛客户端”。[BBS 服务端](http://obbs.sinaapp.com/).
* [NirZhihuDaily2.0_swift](https://github.com/zpz1237/NirZhihuDaily2.0) - 精仿了知乎日报iOS端练手，Swift2.0，注释相当详细.
* [DesignerNewsApp](https://github.com/MengTo/DesignerNewsApp) - Swift 开发的 DesignerNews 客户端，看着美美的.
* [Eidolon](https://github.com/artsy/eidolon) - 艺术品拍卖的投标亭平台，用swift与反应式编程框架 ReactiveCocoa.
* [BaiduFM-Swift](https://github.com/belm/BaiduFM-Swift) - 百度FM, swift语言实现，基于最新xcode6.3+swift1.2,初步只是为了实现功能，代码比较粗燥，后面有时间会整理，支持Apple Watch。
* [Tuan](https://github.com/aiqiuqiu/Tuan) - 模仿MJ老师iPad版美团（swift版），偶有bug 见谅.
* [ios-oss](https://github.com/kickstarter/ios-oss) - Kickstarter for iOS. Bring new ideas to life, anywhere.
* [Swiftfin](https://github.com/jellyfin/Swiftfin) - 为 iOS 和 tvOS 设计的原生 Jellyfin 客户端，旨在提供流畅的视频播放体验.
* [HealthSync](https://healthsync.megabyte.sh/apple-health-app-sync) - SwiftUI iOS app for syncing selected Apple Health data from HealthKit to a private backend API, with source code on [GitHub](https://github.com/megabyte0x/healthykit).
* [CocoaChinaPlus](https://github.com/zixun/CocoaChinaPlus) - CocoaChina+是一款开源的第三方CocoaChina移动端。整个App都用Swift2.0编写(除部分第三方OC代码外，比如JPush和友盟).
* [SimpleMemo](https://github.com/likumb/SimpleMemo) - 易便签已经转到Swift2.0，全面适配iOS9和Watch OS2，并支持iPhone6s和iPhone6sPlus的3D Touch功能，包括图标快捷键和内容预览.
* [SelectionOfZhihu.swift](https://github.com/sheepy1/SelectionOfZhihu) - 『看知乎』iOS 客户端, [项目说明](http://www.jianshu.com/p/2c3a0f109788).
* [Yep.swift](https://github.com/CatchChat/Yep) - Yep 一个由天才开发给天才们使用的社交软件.
* [LoveFreshBeen.swift](https://github.com/ZhongTaoTian/LoveFreshBeen) - 高仿爱鲜蜂 - Swift2.0.
* [trySwiftApp.swift](https://github.com/ZhongTaoTian/LoveFreshBeen) - trySwiftApp一款较为完整的会议原型应用。有需求的同学可以做为开发参考.
* [PinGo.swift](https://github.com/gaowanli/PinGo) - PinGo.swift：纯Swift编写的仿“随遇”App.
* [UmbrellaWeather.swift](https://github.com/ZeroJian/UmbrellaWeather) - UmbrellaWeather.swift使用 Swift 编写的一款天气应用,现已上架 AppStore.
* [SwiftWeather](https://github.com/JakeLin/SwiftWeather) - SwiftWeather清新淡雅持续改进天气预报项目.
* [Phonetic.swift](https://github.com/iAugux/Phonetic) - Phonetic一个 iOS 版的 Phonetic Contacts，功能很多，其中昵称功能非常实用，已在 GitHub 开源并上架 App Store.
* [edhita.swift](https://github.com/tnantoka/edhita) - edhita.swift支持Markdown, HTML预览的文本编辑器.
* [PilesSugar.swift](https://github.com/cornerAnt/PilesSugar) - PilesSugar.swift:Swift高仿项目,堆糖.
* [duckduckgo](https://github.com/duckduckgo/iOS) - DuckDuckGo iOS Application.
* [react-native-gitfeed](https://github.com/xiekw2010/react-native-gitfeed) - 目前最实用简洁的github客户端了.
* [SoundCloudSwift](https://github.com/pepibumur/SoundCloudSwift) - SoundCloud的Swift版本，采用Swift2.0，Reactive API with ReactiveCocoa 4.0.
* [LeagueofLegends](https://github.com/HarrisHan/LeagueofLegends) - 一个关于英雄联盟的完整iOS开源项目，接口均来自多玩，腾讯各大游戏平台.
* [Coderpursue.swift](https://github.com/wenghengcong/Coderpursue) - 一款 Github 第三方客户端，使用最新 Swift 语言编写.
* [BTApp](https://github.com/Ryan0520/BTApp) - BTApp 仿半糖 iOS App 的 Demo 应用.
* [有妖气漫画](https://github.com/spicyShrimp/U17) - 精仿有妖气漫画(Swift4).
* [MarkLite](https://github.com/zhubinchen/MarkLite) - iOS markdown编辑器.
* [LXFFM](https://github.com/LinXunFeng/LXFFM) - 高仿喜马拉雅FM.
* [TodayNews](https://github.com/hrscy/TodayNews) - Swift4 模仿今日头条.
* [notGIF](https://github.com/atuooo/notGIF) - 一款展示、管理和分享相册中 GIF 的应用，并适配了 iMessage Extension.
* [TheGreatGame](https://github.com/dreymonde/TheGreatGame) - Open-source first-class iOS app dedicated to Women’s Euro 2017.
* [trust-wallet-ios](https://github.com/TrustWallet/trust-wallet-ios) - 📱 Trust - Ethereum Wallet for iOS.
* [Instagram](https://github.com/Imputes/Instagram) - 📱 💯 A simple imitation of Instagram  app.
* [cnode-swift](https://github.com/nswbmw/cnode-swift) - iOS 上更好用的 CNode 客户端.
* [Postal](https://github.com/snipsco/Postal) A swift framework for working with emails,Postal is a swift framework providing simple access to common email providers.
* [LBXMLYFM-Swift](https://github.com/lb2281075105/LBXMLYFM-Swift) - 仿写喜马拉雅App.
* [ios-mail](https://github.com/ProtonMail/ios-mail) - iOS-mail — ProtonMail iOS client app.

#### App框架@

* [swift-composable-architecture](https://github.com/pointfreeco/swift-composable-architecture) - 一个基于 ReactiveSwift 的架构库，旨在帮助开发者以一致且易于理解的方式构建应用程序。它提供了强大的工具来管理状态、处理副作用以及进行模块化开发.
* [katana-swift](https://github.com/BendingSpoons/katana-swift) - Swift Apps in a Swoosh! A modern framework for creating iOS apps, inspired by React and Redux. http://katana.bendingspoons.com
* [SlackKit](https://github.com/SlackKit/SlackKit) SlackKit makes it easy to build Slack apps in Swift.
* [Lona](https://github.com/airbnb/Lona) - A tool for defining design systems and using them to generate cross-platform UI code, Sketch files, images, and other artifacts.
* [ReSwift](https://github.com/ReSwift/ReSwift) - ReSwift 是一个轻量级的框架，能够帮助你很轻松的去构建一个 Redux 架构的app.
* [Lotusoot](https://github.com/Vegetarians/Lotusoot) - 灵活的 Swift 组件通信和路由工具.
* [katana-swift](https://github.com/BendingSpoons/katana-swift)一个用于编写iOS应用程序的现代Swift框架，灵感来自React和Redux。 Swift Apps in a Swoosh! A modern framework for creating iOS apps, inspired by React and Redux.
* [SwiftyMocky](https://github.com/MakeAWishFoundation/SwiftyMocky) - Framework for mock generation.
* [Flix](https://github.com/DianQK/Flix) - 快速搭建列表类界面的框架.
* [IBAnimatable](https://github.com/IBAnimatable/IBAnimatable) - Design and prototype customized UI, interaction, navigation, transition and animation for App Store ready Apps in Interface Builder with IBAnimatable.
* [Sourcery](https://github.com/krzysztofzablocki/Sourcery) - 一个将元程序引入Swift的工具，允许你生成Swift的代码.
* [PromiseKit](https://github.com/mxcl/PromiseKit) - 同时支持 Swift 及 Objective-C 的 Promise 类库，异步编程类库 提供了很多实用的异步函数 让异步编程更简单.
* [Alicerce](https://github.com/Mindera/Alicerce) - A base for iOS Applications made with ❤️ by Mindera 🤠.
* [EasyReact](https://github.com/meituan/EasyReact) - Are you confused by the functors, applicatives, and monads in RxSwift and ReactiveCocoa? It doesn't matter, the concepts are so complicated that not many developers actually use them in normal projects. Is there an easy-to-use way to use reactive programming? EasyReact is born for this reason.
* [react-native-maps](https://github.com/react-community/react-native-maps) - React Native Mapview component for iOS + Android.
* [Receiver](https://github.com/RuiAAPeres/Receiver) - Swift µframework implementing the Observer pattern 📡 .
* [Hanson](https://github.com/blendle/Hanson) - 轻量级的KVO

#### 响应式框架@

* [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) Streams of values over time  一个支持FRP(函数响应式编程)的框架 非常👍👍👍 .
* [RxSwift](https://github.com/ReactiveX/RxSwift) - RxSwift:函数响应式编程框架，非常👍👍👍 .
* [RxPermission.swift](https://github.com/sunshinejr/RxPermission) - 通过绑定 RxSwift 实现的 RxPermission。
* [ReactiveAnimation](https://github.com/ReactiveCocoa/ReactiveAnimation) - ReactiveCocoa 推出了一个叫 ReactiveAnimation 的子项目，直接用完全用 Swift 来实现了。
* [Swiftest](https://github.com/bppr/Swiftest) - BDD 全称 Behavior Driven Development，行为驱动开发。各种 DD 数不胜数，孰优孰劣争论不休，其实归根结底还是要根据使用场景进行选择。
* [SemanticUI](https://github.com/aaronbrethorst/SemanticUI) - Semantic UI 是一套开源的 CSS 与 JavaScript 框架，提供了一些设计好的界面组件，你可以在项目里直接使用这些组件。它还提供了一套很方便的定制主题的方法，你可以用自己的想法去改变界面组件的样式。在这个教程里我们学习一下安装 Semantic UI.

#### 页面路由@

* [ACRouter](https://github.com/Archerlly/ACRouter) - Swift版页面路由, 组件化过程中快速页面解耦.
* [SwiftyURLRouter](https://github.com/iAllenC/SwiftyRouter) - 基于模块结构的Swift页面路由，支持DSL式调用.
* [routing-kit](https://github.com/vapor/routing-kit) - routing-kit.

#### 版本管理@

* [Carthage](https://github.com/Carthage/Carthage) - 非常好用的类似CocoaPods的依赖库管理工具.
* [CocoaPods](https://github.com/CocoaPods/CocoaPods) - 非常好用的依赖库管理工具.
* [Sword](https://github.com/Azoy/Sword) - Discord library for Swift http://sword.azoy.me.

#### 混合开发@

* [SwiftPython](https://github.com/johnno1962/SwiftPython) - Experiments in bridging Swift to Python.
* [hera](https://github.com/weidian-inc/hera) - Hera 是一个用小程序方式来写跨平台应用的开发框架，使用它可以让你的小程序除了在微信上运行，还可以打包成 Android 、 iOS应用，以及以h5的方式跑在浏览器端.

#### 安全@

* [PermissionScope](https://github.com/nickoneill/PermissionScope) - PermissionScope 是一个 Swift 框架，为了向用户巧妙地请求权限。它不只包含简单的权限请求 UI，还有统一的权限 API 可以告诉你任意给定的系统权限的状态，当然也可以轻松地请求它们.
* [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - swift加密库, 支持md5,sha1,sha224,sha256...
* [RequestPermission](https://github.com/IvanVorobei/RequestPermission) - simple permission request with beautiful UI.
* [Money](https://github.com/Flight-School/Money) - A precise, type-safe representation of a monetary amount in a given currency.
* [NativeLogin](https://github.com/IvanVorobei/NativeLogin) - Authorization form in native iOS style.
* [Permission.swift](https://github.com/delba/Permission) - 统一的 API 请求 iOS 本地设备及资源权限类库。
* [Proposer](https://github.com/nixzhu/Proposer) - Proposer 用单个 API 处理 iOS 上的权限请求，以便使用前确认可访问“相册”、“相机”、“麦克风”、“通讯录”或“用户位置”.
* [OAuthSwift](https://github.com/OAuthSwift/OAuthSwift) - OAuthSwift国外主流网站OAuth授权类库。
* [KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess) - Simple Swift wrapper for Keychain that works on iOS, watchOS, tvOS and macOS
* [AppAuth-iOS](https://github.com/openid/AppAuth-iOS) - iOS and macOS SDK for communicating with OAuth 2.0 and OpenID Connect providers. 用于iOS和MacOS的OAuth和OpenID Connect客户端.
* [KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess) - KeychainAccess is a simple Swift wrapper for Keychain that works on iOS and OS X. Makes using Keychain APIs extremely easy and much more palatable to use in Swift.


#### 网络@
#### 网络请求@

* [Alamofire](https://github.com/Alamofire/Alamofire) - 非常赞👍👍👍 Alamofire是AFNetworking的作者mattt新写的网络请求的swift库。[Alamofire 最佳实践](https://github.com/ipader/SwiftGuide/wiki/Alamofire%20%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5)
* [Moya](https://github.com/Moya/Moya) - 对Alamofire的封装，使用枚举将网络层实现细节与页面逻辑代码分离，方便单元测试，支持stub测试，配合RxSwift食用更佳，[博客教程](http://www.hmttommy.com/2015/12/15/Moya/)
* [RxNetworks](https://github.com/yangKJ/RxNetworks) - 基于 RxSwift + Moya 搭建响应式数据绑定网络API架构，多种插件模式，构建简单易用的网络架构。
* [Hedwig](https://github.com/onevcat/Hedwig) - 提供了一组高级 API，可以让你轻松地发送电子邮件到SMTP服务器。如果你打算在下一个神奇的 Swift 服务器 app里发送 email，Hedwig 可能是一个好的选择.
* [swift-nio](https://github.com/apple/swift-nio) - 苹果开源的一个事件驱动的非阻塞的网络框架，用来写高性能网络应用.
* [SwiftRouter](https://github.com/skyline75489/SwiftRouter) - A URL Router for iOS, written in Swift 2.2 :large_orange_diamond:
* [AlamofireObjectMapper.swift](https://github.com/tristanhimmelman/AlamofireObjectMapper) - 将Alamofire JSON响应数据 转为swift对象。
* [RxAlamofire.swift](https://github.com/RxSwiftCommunity/RxAlamofire) - 为Alamofire提供函数响应式（FRP）调用接口,以优雅的方式使用Alamofire进行网络请求。
* [socket.io-client-swift](https://github.com/socketio/socket.io-client-swift) - WebSockect 客户端类库。开放的通讯协议，有利于构建强大地跨平台应用。
* [Transporter](https://github.com/nghialv/Transporter) - swift， 短小、精悍、易用的多文件（并发或顺序）上传和下载传输库。还支持后台运行、传输进程跟踪、暂停/续传/取消/重试控制等功能。
* [Just](https://github.com/JustHTTP/Just) - 小而美的 HTTP 类。功能简单、直接、完整且健壮性高-- swift。
* [Future](https://github.com/nghialv/Future) - 基于微框架设计思想的异步执行及结果响应类，代码即简单又干净-- swift。
* [HFDownLoad](https://github.com/hongfenglt/HFDownLoad) - iOS开发网络篇之文件下载、大文件下载、断点下载:NSData方式、NSURLConnection方式、NSURLSession下载方式 [下载方式具体的思路、区别见Blog](http://blog.csdn.net/hongfengkt/article/details/48290561) 。
* [Pitaya.swift](https://github.com/johnlui/Pitaya) - Pitaya 是纯 Swift 写的 iOS 网络库，支持 Basic Authorization、SSL 钢钉、HTTP raw body / JSON body、快速文件上传等特性，并通过内置 JSONNeverDie 实现了对 JSON 的完全支持，开箱即用。 [中文文档](https://github.com/johnlui/Pitaya/wiki/%E4%B8%AD%E6%96%87%E6%96%87%E6%A1%A3)
* [starscream.swift](https://github.com/daltoniam/starscream) - starscream.swift:WebSocket客户端类库。
* [SwiftNet.swift](https://github.com/FengDeng/SwiftNet) - 基于 RxSwift 和 Alamofire 的网络请求简易封装库。
* [Networking.Swift](https://github.com/3lvis/Networking) - 使用简单、功能惊喜，基于 NSURLSession 的网络封装。
* [EFInternetIndicator](https://github.com/ezefranca/EFInternetIndicator)swift 轻巧的一款 iOS 网络变更通知工具。
* [SWNetworking](https://github.com/isamankumara/skywite) - Powerful high-level iOS, macOS and tvOS networking library. from the creator of SWNetworking 🔶
* [Transporter](https://github.com/nghialv/Transporter) - A tiny library makes uploading and downloading easier. :large_orange_diamond:
* [TRON](https://github.com/MLSDev/TRON) - Lightweight network abstraction layer, written on top of Alamofire :large_orange_diamond:
* [Pitaya](https://github.com/johnlui/Pitaya) - A Swift HTTP / HTTPS networking library just incidentally execute on machines :large_orange_diamond:
* [ws ☁️](https://github.com/freshOS/ws) - Elegant JSON WebService in Swift.:large_orange_diamond:
* [Netdiag](https://github.com/qiniu/iOS-netdiag) - A network diagnosis library. Support Ping/TcpPing/Rtmp/TraceRoute/DNS/external IP/external DNS.
* [AFNetworkingHelper](https://github.com/betacraft/AFNetworkingHelper) - A custom wrapper over AFNetworking library that we use inside RC extensively
* [SwiftyZeroMQ](https://github.com/azawawi/SwiftyZeroMQ) - ZeroMQ Swift Bindings for iOS, macOS, tvOS and watchOS. :large_orange_diamond: ⌚
* [Frisbee](https://github.com/ronanrodrigo/Frisbee) - Another network wrapper for URLSession. Built to be simple, small and easy to create tests at the network layer of your application.
* [Restofire](https://github.com/Restofire/Restofire) - Restofire is a protocol oriented network abstraction layer in swift that is built on top of Alamofire to use services in a declartive way.
* [SolarNetwork](https://github.com/ThreeGayHub/SolarNetwork) - 基于Alamofire封装，揉和了Alamofire和Moya两者优点的一套简单易用的网络库。
* [socket.io-client-swift](https://github.com/socketio/socket.io-client-swift) - socket.

#### 网络测试@

* [Reachability.swift](https://github.com/ashleymills/Reachability.swift) - 用于替换苹果的 Reachability 类，可以方便地检测当前是否联网以及具体的联网状态.
* [NetReachability](https://github.com/crazypoo/SimpleCarrie) - swift2.0 简单的方法检查网络连接的连通性，提供通知中心集成接口.
* [SimpleBS.swift](https://github.com/bin1991/SimpleBS) - 网络测试小工具.
* [NEKit](https://github.com/zhuhaow/NEKit) - 一个网络扩展工具库,A toolkit for Network Extension Framework.

#### 网页框架@

* [Perfect.swift](https://github.com/PerfectlySoft/Perfect) - Perfect 致力于 Swift 服务端应用，从打造专业应用服务器开始。[Swift服务端编程：Perfect项目上手指南](http://blog.csdn.net/kinfey/article/details/50644752)
* [swift-http](https://github.com/huytd/swift-http) - Swift HTTP Server，又一个 Swift 服务器，最大的亮点是支持 Docker 部署。
* [Swifton](https://github.com/necolt/Swifton) - Swifton是一个优秀的Swift on Rails 的Web Framework。
* [Taylor.swift](https://github.com/izqui/Taylor) - Taylor一个swift的轻量级的http服务器的库。
* [NetworkObjects.swift](https://github.com/colemancda/NetworkObjects) - NetworkObjects.swift轻量版HttpServer框架，跨平台解决方案。
* [Kitura.swift](https://github.com/IBM-Swift/Kitura) - Kitura.swift：安装、使用步骤及文档最为清晰地来自 IBM Swift 开发组的开源 Web 服务器。此外，IBM 云服务 Bluemix 也为 Swift 打开通路。

#### 网络解析@

##### Json@

* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with JSON data in Swift. :large_orange_diamond:.
* [ObjectMapper](https://github.com/Hearst-DD/ObjectMapper) - 很赞 ObjectMapper 是一个基于 Swift 语言开发的能够让 JSON 与 Object 之间轻易转换的类库。通过 ObjectMapper 我们可以将 JSON 数据转换成 Model 对象或将 Model 对象转换成 JSON 数据。 Simple JSON Object mapping written in Swift.
* [Mantle](https://github.com/Mantle/Mantle) - Model framework for Cocoa and Cocoa Touch.
* [Decodable](https://github.com/Anviking/Decodable) - Swift 2 JSON parsing done (more) right :large_orange_diamond:.
* [Jay](https://github.com/czechboy0/Jay) - Pure-Swift JSON parser & formatter. Linux & OS X ready. :large_orange_diamond:.
* [XMLDictionary](https://github.com/nicklockwood/XMLDictionary) - ios与mac os平台下xml与NSDictionary相互转化开源类库.
* [AEXML.swift](https://github.com/tadija/AEXML) - AEXML.swift简单又易于的XML解析类及示例.
* [CFRuntime](https://github.com/CoderMJLee/MJExtension) - “Swift 版的 MJExtension，运行时、反射与一键字典模型互转”.
* [protobuf-swift](https://github.com/alexeyxo/protobuf-swift) - Protocol Buffers 的 Swift 语言实现库。P.S. Protocol Buffers 是 Google 开源项目，主要功能是实现直接序列化结构化的对象数据，方便跨平台快速传递，开发者也可以直接修改 protobuf 中的数据。相比 XML 和 JSON，protobuf 解析更快，存储更小.
* [JSONCodable](https://github.com/matthewcheok/JSONCodable) - 基于 Swift 2.0 新特性（Protocol Extensions and Error Handling）的JSON 解析类.
* [JSONNeverDie.swift](https://github.com/johnlui/JSONNeverDie) - JSON 到 Model 类的自动映射工具.
* [Fuzi.swift](https://github.com/cezheng/Fuzi) - Swift实现的轻量快速的 XML/HTML 解析器.
* [SWXMLHash.swift](https://github.com/drmohundro/SWXMLHash) - 易用的 XML 解析类库。非常实用的“轮子”.
* [YYModel](https://github.com/ibireme/YYModel) - 高性能的 iOS JSON 模型框架.
* [Gloss](https://github.com/hkellaway/Gloss) - A shiny JSON parsing library in Swift ✨.
* [TidyJSON.swift](https://github.com/benloong/TidyJSON) - TidyJSON.swift一款简单、易用、明了的 JSON 解析小类库.
* [PMJSON.swift](https://github.com/postmates/PMJSON) - PMJSON.swift简单、实用、高效的 JSON 解析类库.
* [Unbox.swift](https://github.com/JohnSundell/Unbox) - 极为易用、轻量，更少辅助代码的 JSON 解析类.
* [Wrap.swift](https://github.com/JohnSundell/Wrap) - 方便、易用的对象转 JSON 类库.
* [CollectionKit](https://github.com/SoySauceLab/CollectionKit) - A modern Swift framework for building reusable data-driven collection components.
* [JASON](https://github.com/delba/JASON) - 高效的Json解析（Swift） Fast JSON parsing for Swift.
* [JSONCodable](https://github.com/matthewcheok/JSONCodable) - Swift json编码解码三方库 Hassle-free JSON encoding and decoding in Swift.
* [Coolie](https://github.com/nixzhu/Coolie) - Swift json转model的三方库 Coolie helps you to create models (& their constructors) from JSON file.
* [Tailor](https://github.com/zenangst/Tailor) - 一个非常快和方便的对象映射Swift三方库 A super fast & convenient object mapper tailored for your needs.
* [alexander](https://github.com/hodinkee/alexander) - 一个非常简洁的json处理三方库 An extremely simple JSON helper written in Swift.
* [Freddy](https://github.com/bignerdranch/Freddy) - 一个可以重用的json解析库 A reusable framework for parsing JSON in Swift.
* [mapper](https://github.com/lyft/mapper) - 一个json反序列化库 A JSON deserialization library for Swift.
* [AlamofireJsonToObjects](https://github.com/evermeer/AlamofireJsonToObjects) - 一个将json data转为Swift对象的类扩展 An Alamofire extension which converts JSON response data into swift objects using EVReflection.
* [Alembic](https://github.com/ra1028/Alembic) - 功能性的json解析库 Functional JSON parsing, mapping to objects, and serialize to JSON :large_orange_diamond:
* [Wrap](https://github.com/JohnSundell/Wrap) - The easy to use Swift JSON encoder :large_orange_diamond:
* [Arrow](https://github.com/freshOS/Arrow) - 一个Swift JSON解析库 JSON Parsing Library for Swift
* [Genome](https://github.com/LoganWright/Genome) - 一个易用、多样、安全，包含错误映射的JSON转Model的Swift库. A simple, type safe, failure driven mapping library for serializing JSON to models in Swift 2.0 (Supports Linux)
* [FeedKit](https://github.com/nmdias/FeedKit) - An RSS and Atom feed parser written in Swift :large_orange_diamond:
* [typewriter](https://github.com/typwr/typewriter) - 客户端翻译服务端数据交换格式的代码翻译器.

##### CSV@

* [CSwiftV](https://github.com/Daniel1of1/CSwiftV) - A csv parser written in swift conforming to rfc4180 :large_orange_diamond:
* [SwiftCSV](https://github.com/naoty/SwiftCSV) - CSV parser for Swift :large_orange_diamond:

#### xml@

* [AEXML](https://github.com/tadija/AEXML) - Simple and lightweight XML parser written in Swift. :large_orange_diamond:

#### 数据存储@

* [DataSources](https://github.com/muukii/DataSources) 💾 🔜📱 Type-safe data-driven List-UI Framework. (We can also use ASCollectionNode).
* [Disk](https://github.com/saoudrizwan/Disk) Delightful framework for iOS to easily persist structs, images, and data.
* [FileKit](https://github.com/nvzqz/FileKit) - 提供了简单和富有表现力的文件管理.
* [UserDefaultsStore](https://github.com/omaralbeik/UserDefaultsStore) - Why not use UserDefaults to store Codable objects 😉.
* [realm-swift](https://github.com/realm/realm-swift) - 跨平台的移动数据库引擎.

#### 缓存处理@
* [Cache.swift](https://github.com/soffes/Cache) - 一款简单、易用的缓存库。支持 MemoryCache, DiskCache 以及前两项组合的 MultiCache。
* [Cache.swift](https://github.com/hyperoslo/Cache) - Nothing but Cache。
* [AwesomeCache.swift](https://github.com/aschuch/AwesomeCache) - Delightful on-disk cache (written in Swift)。
* [Track.swift](https://github.com/maquannene/Track) - 基于文件系统和链表的 Cache。分为 Disk 和 Memory，线程安全，支持 LRU 淘汰，性能尚可。

#### CoreData@

* [JSQCoreDataKit](https://github.com/jessesquires/JSQCoreDataKit) - A swifter Core Data stack :large_orange_diamond:
* [Sync](https://github.com/3lvis/Sync) - :arrows_counterclockwise: Modern Swift JSON synchronization to Core Data :large_orange_diamond:
* [AlecrimCoreData](https://github.com/Alecrim/AlecrimCoreData) - A powerful and simple Core Data wrapper framework written in Swift. :large_orange_diamond:
* [AERecord](https://github.com/tadija/AERecord) - Super awesome Core Data wrapper in Swift. :large_orange_diamond:
* [Graph](https://github.com/CosmicMind/Graph) - An elegant data-driven framework for CoreData in Swift. :large_orange_diamond:
* [JSQCoreDataKit](https://github.com/jessesquires/JSQCoreDataKit) - A swifter Core Data stack :large_orange_diamond:
* [DATAStack](https://github.com/3lvis/DATAStack) - 100% Swift Simple Boilerplate Free Core Data Stack. NSPersistentContainer. :large_orange_diamond:
* [Cadmium](https://github.com/jmfieldman/cadmium) - A complete swift framework that wraps CoreData and helps facilitate best practices. :large_orange_diamond:

#### 数据库@

* [realm-cocoa](https://github.com/realm/realm-cocoa) 一个号称要代替Core Data & SQLite的用于移动端的数据库，非常不错👍👍 ，同时支持Objective-C.
* [RealmIncrementalStore.swift](https://github.com/eure/RealmIncrementalStore) - RealmIncrementalStore.swift:集 Realm 数据库和 CoreData 对象模型两者优势的 Realm 数据库访问类库。
* [Breeze](https://github.com/andrelind/Breeze) - 用Swift写的一个轻量级的CoreData管理工具，并且还支持iCloud 。
* [AlecrimCoreData](https://github.com/Alecrim/AlecrimCoreData) - Swift，更容易地访问 CoreData 对象封装类库。除了 CRUD，还提供指针定位，强大的排序、筛选，异步数据获取，以及独立线程后台存取数据。
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift) - 纯swift实现的类型安全的SQLite3封装，数据存储和JSON解析是永恒的话题。
* [fluent.swift](https://github.com/qutheory/fluent) - 纯swift实现的类型安全的SQLite3封装，数据存储和JSON解析是永恒的话题。
* [swiftydb](http://www.appcoda.com/swiftydb/) - 是一个第三方 SQLite 工具，能够大大简化数据库操作。如果你不放心 Realm，那就用 SwiftyDB 吧。[使用教程](http://swift.gg/2016/05/17/swiftydb/) [demo](https://github.com/appcoda/SwiftyDB-Demo)
* [Graph.swift](https://github.com/CosmicMind/Graph) - 设计新颖、使用简单基于 Core Data 的数据驱动框架库 （作者Daniel Dahan）。
* [SwiftStore](https://github.com/hemantasapkota/SwiftStore) - Key-Value store for Swift backed by LevelDB :large_orange_diamond:
* [Prephirences](https://github.com/phimage/Prephirences) - Prephirences is a Swift library that provides useful protocols and convenience methods to manage application preferences, configurations and app-state. :large_orange_diamond:
* [SwiftyUserDefaults](https://github.com/radex/SwiftyUserDefaults) - 让 user defaults 用起来很愉悦，通过结合意味深长的 Swifty API 和静态输入的益处。在一个地方定义键，轻松地使用值类型，获得额外的安全性和方便的编译时检查.
* [SugarRecord](https://github.com/carambalabs/SugarRecord) - Data persistence management library written in Swift 3.0 :large_orange_diamond:
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift) - A type-safe, Swift-language layer over SQLite3. :large_orange_diamond:
* [GRDB.swift](https://github.com/groue/GRDB.swift) - A versatile SQLite toolkit for Swift, with WAL mode support :large_orange_diamond:
* [Fluent](https://github.com/vapor/fluent) - Simple ActiveRecord implementation for working with your database in Swift. :large_orange_diamond:
* [YapDatabaseExtensions](https://github.com/danthorpe/YapDatabaseExtensions) - YapDatabase extensions for use with Swift :large_orange_diamond:
* [SwiftMongoDB](https://github.com/Danappelxx/SwiftMongoDB) - A MongoDB interface for Swift :large_orange_diamond:
* [SwiftStore](https://github.com/hemantasapkota/SwiftStore) - Key-Value store for Swift backed by LevelDB :large_orange_diamond:
* [MongoDB](https://github.com/PerfectlySoft/Perfect-MongoDB) - A Swift wrapper around the mongo-c client library, enabling access to MongoDB servers. Part of the
* [apollo-ios](https://github.com/apollographql/apollo-ios) - GraphQL是一种用于API的开源数据查询和操作语言，并且是用于使用现有数据执行查询的运行时.
* [SQLite](https://github.com/PerfectlySoft/Perfect-SQLite) - A Swift wrapper around the SQLite 3 client library, enabling access to SQLite servers. Part of the
* [PersistDB](https://github.com/PersistX/PersistDB) - Projection-based Database Persistence in Swift.
* [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [MySQL](https://github.com/PerfectlySoft/Perfect-MySQL) - A Swift wrapper around the MySQL client library, enabling access to MySQL servers. Part of the
* [Redis](https://github.com/PerfectlySoft/Perfect-Redis) - A Swift wrapper around the Redis client library, enabling access to Redis. Part of the
* [PostgresApp](https://github.com/PostgresApp/PostgresApp) - 以加州大学伯克利分校计算机系开发的 POSTGRES，现在已经更名为PostgreSQL，版本 4.2为基础的对象关系型数据库管理系统（ORDBMS).
* [PostgreSQL](https://github.com/PerfectlySoft/Perfect-PostgreSQL) - A Swift wrapper around the libpq client library, enabling access to PostgreSQL servers. Part of the
* [FileMaker](https://github.com/PerfectlySoft/Perfect-FileMaker) - A Swift wrapper around the FileMaker XML Web publishing interface, enabling access to FileMaker servers. Part of the
* [AppFolder](https://github.com/dreymonde/AppFolder) - Never use NSSearchPathForDirectoriesInDomains again.
* [GRDB.swift](https://github.com/groue/GRDB.swift) - A toolkit for SQLite databases, with a focus on application development.

#### 钥匙链@

* [EllipticCurveKeyPair](https://github.com/agens-no/EllipticCurveKeyPair) - Sign, verify, encrypt and decrypt using the Secure Enclave.
* [keychain-swift](https://github.com/evgenyneu/keychain-swift) - Helper functions for saving text in Keychain securely for iOS, OS X, tvOS and watchOS.

#### 多媒体@
#### 相机@

* [CameraManager](https://github.com/imaginary-cloud/CameraManager) - 相机管理封装类库。看着极好用的样子----swift。
* [SkfSwiftCammer](https://github.com/wubianxiaoxian/SkfSwiftCammer) - 一个相机demo，在oc里面调用了swift。
* [TLStoryCamera](https://github.com/timelessg/TLStoryCamera) 仿照instagramStory & WeiBoStory。可以在拍摄视频后贴图，贴字，涂鸦。

#### 二维码@

* [EFQRCode](https://github.com/EyreFree/EFQRCode) - 快速生成炫酷的二维码.
* [ZFScan](https://github.com/Zirkfied/ZFScan) - 仿微信 二维码/条形码 扫描。
* [QRCodeReader.swift](https://github.com/yannickl/QRCodeReader.swift) - QRCodeReader.swift一款简单的 QR 二维码阅读组件及示例，提供前后相机切换功能。
* [swiftScan](https://github.com/MxABC/swiftScan) - 具有丰富功能的二维码扫描组件及类库。[对应OC版本LBXScan](https://github.com/MxABC/LBXScan).
* [QR-Code-Generator.swift](https://github.com/appcoda/QR-Code-Generator) - 生成二维码.
* [LLPhotoBrowser](https://github.com/LvJianfeng/LLPhotoBrowser) - Swift3图片浏览库，支持网络图，本地图，UIImage同时使用，支持识别二维码，支持横屏看图，支持长按弹出功能窗口.
* [ImageDetect](https://github.com/Feghal/ImageDetect) - ✂️ Detect and crop faces, barcodes and texts in image with iOS 11 Vision api.

#### PDF@

* [FolioReaderKit](https://github.com/FolioReader/FolioReaderKit) - 非常棒👍的阅读器框架，支持自定义字体、字体大小、文本高亮、列表编辑删除、主题、白天夜间模式等等非常多的特性。
* [PDFGenerator](https://github.com/sgr-ksmt/PDFGenerator) - 一个简单的PDF生成器.
* [SimplePDF](https://github.com/nRewik/SimplePDF) - 轻松创建一个简单的PDF文件或者Data，能够增加文本、图片、空格、线、表格，支持页面布局，调整内容样式.
* [PSPDFKit](https://pspdfkit.com/) - Render PDF, add/edit annotations, fill forms, add/edit pages, view/create digital signatures.
* [TPPDF](https://github.com/Techprimate/TPPDF) - 一个容易使用的创建PDF的库
* [Reader](https://github.com/vfr/Reader) - PDF Reader Core for iOS.
* [UIView 2 PDF](https://github.com/RobertAPhillips/UIView_2_PDF) - PDF generator using UIViews or UIViews with an associated XIB
* [FolioReaderKit](https://github.com/FolioReader/FolioReaderKit) - A Swift ePub reader and parser framework for iOS. :large_orange_diamond:
* [PDFGenerator](https://github.com/sgr-ksmt/PDFGenerator) - A simple Generator of PDF in Swift. Generate PDF from view(s) or image(s). :large_orange_diamond:
* [SimplePDF](https://github.com/nRewik/SimplePDF) - Create a simple PDF effortlessly. :large_orange_diamond:
* [SwiftPDFGenerator](https://github.com/kayoslab/SwiftPDFGenerator) - PDF generator using UIViews; Swift Version of 'UIView 2 PDF'. :large_orange_diamond:
* [PSPDFKit](https://pspdfkit.com/) - Render PDF, add/edit annotations, fill forms, add/edit pages, view/create digital signatures.
* [TPPDF](https://github.com/Techprimate/TPPDF) - Generate PDF using commands and automatic layout. :large_orange_diamond:

#### GIF@

* [AImage](https://github.com/wangjwchn/AImage) - A animated GIF&APNG engine for iOS in Swift with low memory & cpu usage.Optimized for Multi-Image case.:large_orange_diamond:
* [gifu](https://github.com/kaishin/gifu) - Highly performant animated GIF support for iOS in Swift :large_orange_diamond:

#### 音频@

* [recordDemo.swift](https://github.com/lfb-cd/recordDemo) - 一个Swift语言实现直接可以用的录音Demo，[实现说明](http://www.jianshu.com/p/f0b88355d7cb).
* [Swift-Radio-Pro](https://github.com/swiftcodex/Swift-Radio-Pro) - 集成 LastFM 的专业电台应用（基于 Swift 2.0）.
* [AudioKit](https://github.com/audiokit/AudioKit) - 一个非常强大的音频合成、加工、分析平台工具，支持iOS、macOS、tvOS.
* [DeckTransition](https://github.com/HarshilShah/DeckTransition) - A library to recreate the iOS 10 Apple Music now playing transition.
* [AudioBus](https://developer.audiob.us/) - 下一代的音频路由 Add Next Generation Live App-to-App Audio Routing.
* [Cephalopod](https://github.com/evgenyneu/Cephalopod) - 一个基于AVIudioPlayer的音效推子，支持 iOS，tvOS和macOS.
* [Chirp](https://github.com/trifl/Chirp) - 播放和删除声音最容易的方法.
* [Beethoven](https://github.com/vadymmarkov/Beethoven) - 音高检测大师.
* [AudioPlayerSwift]( https://github.com/tbaranes/AudioPlayerSwift) - 一个使音频播放更简单的类AudioPlayer，支持 iOS, macOS and tvOS apps.
* [AudioPlayer](https://github.com/delannoyk/AudioPlayer) - 一个基于AVPlayer的播放本地和网络音频的库.
* [TuningFork](https://github.com/comyar/TuningFork) - 简单的调音师.
* [MusicKit](https://github.com/benzguo/MusicKit) - 一个合成和转换音乐的框架.
* [TheAmazingAudioEngine2](https://github.com/TheAmazingAudioEngine/TheAmazingAudioEngine2) - 一个惊人的、精致的用于音频App的音频库.
* [InteractivePlayerView](https://github.com/AhmettKeskin/InteractivePlayerView) - 自定义音乐播放View.
* [ESTMusicIndicator](https://github.com/Aufree/ESTMusicIndicator) - 很酷的音乐动画指示View.
* [SwiftySound](https://github.com/adamcichy/SwiftySound) - 一个让你一行代码就可以播放音频的三方库.
* [ROMPlayer](https://github.com/AudioKit/ROMPlayer) - AudioKit Sample Player (ROM Player) - EXS24, Sound Font, Wave Player.

#### 媒体流@

* [lf.swift](https://github.com/shogo4405/lf.swift) - 相机和麦克风流媒体库，支持RTMP，HLS for iOS，macOS。
* [StreamingKit](https://github.com/tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for OSX and iOS.
* [Jukebox](https://github.com/teodorpatras/Jukebox) - 音频播放器，可播放本地和网络音频流
* [Airstream](https://github.com/qasim/Airstream) - 一个基于AirPlay在Apple devices之间进行音频流传输的库，比如iphone音乐在Apple TV上面播放。
* [OTAcceleratorCore](https://github.com/opentok/accelerator-core-ios) - 通过Tokbox将音频/视频（屏幕共享）轻松集成到任何iOS应用程序.包括视频通话、语音通话等。

#### 视频@
#### 视频播放@

* [MobilePlayer](https://github.com/mobileplayer/mobileplayer-ios) - 一个强大、可自定义的媒体播放器.
* [Periscope-VideoViewController.swift](https://github.com/gontovnik/Periscope-VideoViewController) - 简洁实用的视频快进、倒带控制视图类库.
* [MPMoviePlayerController-Subtitles](https://github.com/mhergon/MPMoviePlayerController-Subtitles) - 一个播放STR文件的简单方法.
* [Player](https://github.com/piemonte/Player) - ▶️  一个简单方法播放视频和流媒体的播放器，支持iOS和tvOS.
* [YoutubeKit](https://github.com/rinov/YoutubeKit) - YoutubeKit is a video player that fully supports Youtube IFrame API and YoutubeDataAPI for easily create a Youtube app.
* [mobileplayer-ios.swift](https://github.com/mobileplayer/mobileplayer-ios) - 很不错的高度可定制播放器项目.
* [BMPlayer.swift](https://github.com/BrikerMan/BMPlayer) - 基于 AVPlayer 使用 Swift 封装的视频播放器，方便快速集成,支持横屏、竖屏，上下滑动调节音量、屏幕亮度，左右滑动调节播放进度.
* [PlayerView](https://github.com/davidlondono/PlayerView) - 一个使用代理和AVPlayer的播放View.
* [VGPlayer](https://github.com/VeinGuo/VGPlayer) - A simple iOS video player by Vein.
* [Swift-YouTube-Player](https://github.com/gilesvangruisen/Swift-YouTube-Player) - Swift library for embedding and controlling YouTube videos in your iOS applications.
* [PlayerKit](https://github.com/vimeo/PlayerKit)
* [DDDKit](https://github.com/gsabran/DDDKit) - 360 video player for iOS written in swift - a subset of SceneKit that works.

#### 视频处理@

* [PryntTrimmerView](https://github.com/prynt/PryntTrimmerView) - A set of tools to trim, crop and select frames inside a video.

####图像@

* [FlagKit](https://github.com/madebybowtie/FlagKit) - 漂亮的Icon Beautiful flag icons for usage in apps and on the web. :large_orange_diamond:

#### 人脸识别@

* [APKenBurnsView](https://github.com/Alterplay/APKenBurnsView) - 面部识别
* [AAFaceDetection](https://github.com/aaronabentheuer/AAFaceDetection) - AAFaceDetection--swift，简单、实用的面部识别封装库。虽然该技术从 iOS 5 发展，不过真正有趣的应用还不多。

#### 图像识别@

* [ChineseIDCardOCR](https://github.com/KevinGong2013/ChineseIDCardOCR) 🇨🇳中国二代身份证光学识别

#### 图像处理@

* [GPUImage2.swift](https://github.com/BradLarson/GPUImage2) - Swift 版基于 GPU 图像和视频处理框架库。
* [Harbeth](https://github.com/yangKJ/Harbeth) - 基于Metal滤镜框架，包括图像、相机、视频注入滤镜功能，支持 UIImage, CGImage, CIImage, MTLTexture, CMSampleBuffer, CVPixelBuffer 直接注入滤镜功能，同时也兼容`CoreImage`滤镜。
* [Sharaku](https://github.com/makomori/Sharaku) 类似Instagram的图片滤镜库 Image filtering UI library like Instagram.
* [UIImageColors](https://github.com/jathu/UIImageColors) - iTunes style color fetcher for UIImage.
* [FaceAware](https://github.com/BeauNouvelle/FaceAware) - 一个焦点显示图片面部部分的UIImageView的扩展.
* [JHFilterDemo](https://github.com/China131/JHFilterDemo) 图片滤镜生成器
* [ComplimentaryGradientView](https://github.com/gkye/ComplimentaryGradientView) - 创建颜色渐变和颜色突出显示的库.
* [SnapSliderFilters](https://github.com/pauljeannot/SnapSliderFilters) 给图像加贴图、文字的类似阅后即焚的功能
* [SABlurImageView](https://github.com/marty-suzuki/SABlurImageView) - 很容易的给Image添加模糊效果和动画，只需要两个方法
* [Filterpedia.swift](https://github.com/FlexMonkey/Filterpedia) - 强大的图片滤镜库演示。
* [Concorde](https://github.com/contentful-labs/Concorde/) - 下载和编码JPEG图片.
* [core-image-explorer](https://github.com/objcio/issue-21-core-image-explorer) -  Core Image 滤镜处理图片-- swift ，[Core Image 介绍](http://objccn.io/issue-21-6/)。
* [CTPanoramaView](https://github.com/scihant/CTPanoramaView) - 显示球面、圆柱形的摄像.
* [Toucan](https://github.com/gavinbunney/Toucan) - 非常不错的图片处理库，支持图片裁剪、圆角、尺寸调整等.
* [JLStickerTextView](https://github.com/luiyezheng/JLStickerTextView) - 一个给UIImageView添加一个、多个Label的库，并且可以对其进行编辑、旋转、大小调整.
* [YUCIHighPassSkinSmoothing](https://github.com/YuAo/YUCIHighPassSkinSmoothing) -using Apple's Core Image Framework 实现的平滑的美化图片的库.
* [SwiftyAvatar](https://github.com/dkalaitzidis/SwiftyAvatar) - 一个创建圆形图片的UIImageView类.
* [JMCMarchingAnts](https://github.com/izotx/JMCMarchingAnts) - Library that lets you add marching ants (animated) selection to the edges of the images.
* [ShinpuruImage](https://github.com/FlexMonkey/ShinpuruImage) - 一个图片过滤的语法糖.
* [TinyCrayon](https://github.com/TinyCrayon/TinyCrayon-iOS-SDK) - 一个智能、易用的图片裁剪、Image markingSDK
* [ZoomTransition](https://github.com/tristanhimmelman/ZoomTransition) - swift, 通过手势操控图片的放大、缩小、旋转等自由变化效果的组件及示例。
* [AFImageHelper](https://github.com/melvitax/AFImageHelper) - swift,一套针对 UIImage 和 UIImageView 的实用扩展库，功能包含填色和渐变、裁剪、缩放以及具有缓存机制的在线图片获取。
* [PinterestSwift](https://github.com/demonnico/PinterestSwift) - swift,Pinterest 风格图片缩放、切换示例。
* [Nuke.swift](https://github.com/kean/Nuke) - 完整、强大、实用的图片管理类库，主要功能包括可定制装载，缓存，滤镜及尺寸变换。
* [SwViewCapture.swift](https://github.com/startry/SwViewCapture) - SwViewCapture.swift一个用起来还不错的iOS截图库.(支持截取所有内容, 适用于所有ScrollView组成的视图, 包括WebView)
* [CartoonEyes.swift](https://github.com/FlexMonkey/CartoonEyes) - 前置摄像头捕获图像后，采用 Core Image 脸部识别 CIDetector 和漫画效果滤镜复合出卡通效果眼睛。

#### 图像缓存@

* [Kingfisher](https://github.com/onevcat/Kingfisher) - 👍👍👍 一个轻量级的纯粹的用于从web下载和缓存图片的Swift库.
* [HanekeSwift](https://github.com/Haneke/HanekeSwift) - 一个用于iOS的轻量级通用的高速缓存库,使用Swift编写,对图像有特别优化.
* [MWPhotoBrowser](https://github.com/mwaterfall/MWPhotoBrowser) - 一个非常赞，非常简单的图片、视频浏览库，网格状的样式.
* [MapleBacon](https://github.com/zalando-incubator/MapleBacon) - 一个图片下载、缓存库
* [ImageViewer](https://github.com/MailOnline/ImageViewer) - 类似Twitter的图片查看器.
* [Moa](https://github.com/evgenyneu/moa) - 一个非常棒的图片下载的扩展
* [Nuke](https://github.com/kean/Nuke) - 一个强大的图片加载、缓存库.
* [Concorde](https://github.com/contentful-labs/Concorde) - swift, Concorde, 一个可用于下载和解码渐进式 JPEG 的库, 可用来改善应用的用户体验。
* [KFSwiftImageLoader](https://github.com/kiavashfaisali/KFSwiftImageLoader) - 一个高性能的、轻量级的web图片异步下载和缓存库.
* [ImageLoaderSwift](https://github.com/hirohisa/ImageLoaderSwift) - 一个轻量级的快速加载图片的库.
* [ImageScout](https://github.com/kaishin/ImageScout) - 一个预知远程图片尺寸的库，支持图片下载，支持PNG, GIF, and JPEG.
* [PASImageView](https://github.com/abiaad/PASImageView) - 一个圆形的异步图片加载、缓存库.
* [Navi](https://github.com/nixzhu/Navi) - 头像缓存.
* [Imaginary](https://github.com/hyperoslo/Imaginary) - 远程图片异步下载，缓存.
* [Vulcan](https://github.com/jinSasaki/Vulcan) - 带有优先级的多图下载.
* [url-image](https://github.com/dmytro-anokhin/url-image) - Asynchronous image loading in SwiftUI. SwiftUI Image view that displays an image downloaded from URL, with cache and filters.

#### 图像浏览@

* [NYTPhotoViewer](https://github.com/NYTimes/NYTPhotoViewer) - 图片浏览库，支持图片点击缩放、标题、多选、缩放动画等.
* [IDMPhotoBrowser](https://github.com/thiagoperes/IDMPhotoBrowser) - 照片浏览，支持猛击消失等.
* [ImagePickerSheetController](https://github.com/lbrndnr/ImagePickerSheetController) - 流畅、遍历的照片选择器.
* [ImageViewer](https://github.com/Krisiacik/ImageViewer) - 模仿 Twitter 的图片浏览器.
* [Agrume](https://github.com/JanGorman/Agrume) - 一个图片查看库
* [SwiftPhotoGallery](https://github.com/Inspirato/SwiftPhotoGallery) - 一个简单的、全屏显示图片的库，支持缩放、手势、单击关闭、Twitter的关闭风格、Includes a customizable page indicator 等等.
* [ImageSlideshow](https://github.com/zvonicek/ImageSlideshow) - 图片幻灯片和图片轮播器.
* [react-native-image-crop-picker](https://github.com/ivpusic/react-native-image-crop-picker) iOS/Android image picker with support for camera, configurable compression, multiple images and cropping
* [CDFlipView](https://github.com/jibeex/CDFlipView) - 多组图片的翻转的库， A view that takes a set of images, make transition from one to another by using flipping effects.
* [TGLParallaxCarousel](https://github.com/taglia3/TGLParallaxCarousel) - 一个轻量级的3D线性旋转木马.
* [Lightbox](https://github.com/hyperoslo/Lightbox) - 一个方便的图片查看器.
* [AvatarImageView](https://github.com/ayushn21/AvatarImageView) - AvatarImageView是UIImageView的一个可定制的子类，旨在显示用户的个人资料图片。 如果没有提供个人资料图片，则会以随机背景颜色返回到用户的缩写。
* [FacebookImagePicker](https://github.com/terflogag/FacebookImagePicker) - 类似Facebook album photo picker 的照片选择器
* [PhotoStackView-Swift](https://github.com/ijoyc/PhotoStackView-Swift) - PhotoStackView——照片叠放视图，[使用说明](http://blog.csdn.net/u013604612/article/details/46336657)。
* [MPParallaxView](https://github.com/DroidsOnRoids/MPParallaxView) - 是用 Swift 写的类似 Apple TV Parallax 效果的视图。
* [SDECollectionViewAlbumTransition](https://github.com/seedante/SDECollectionViewAlbumTransition) - 用自定义的 push 和 pop 实现了有趣的 iOS 相册翻开动画效果。
* [PagingView.swift](https://github.com/KyoheiG3/PagingView) - 注重细节的自动布局分页视图组件。
* [DouBanMeinv.swift](https://github.com/luzefeng/DouBanMeinv) - 抓取豆瓣美女图片，瀑布流显示。
* [preview-transition.swift](https://github.com/Ramotion/preview-transition) - 通过向导式代码实现步骤，实现完整、自然流畅的图片预览及转场功能。
* [Gemini](https://github.com/shoheiyokoyama/Gemini) Gemini is rich scroll based animation framework for iOS, written in Swift.

#### 相册@

* [DKImagePickerController](https://github.com/zhangao0086/DKImagePickerController) 相册选取
* [TLPhotoPicker](https://github.com/tilltue/TLPhotoPicker) 类似facebook的一个相册多图选取框架.
* [SKPhotoBrowser](https://github.com/suzuki-0000/SKPhotoBrowser) Simple PhotoBrowser/Viewer inspired by facebook, twitter photo browsers written by swift.
* [MediaBrowser](https://github.com/younatics/MediaBrowser) — 照片/视频浏览器，支持UIImage对象、PHAsset对象、资源库URL、网络图像/视频、本地文件.
* [ImagePicker](https://github.com/hyperoslo/ImagePicker) -  Reinventing the way ImagePicker works.

#### 数据结构/算法@

* [swift-algorithm-club](https://github.com/raywenderlich/swift-algorithm-club) - 很多流行的算法和数据结构的具体实现，非常赞👍👍👍 .
* [SwiftSortedList](https://github.com/bemindinteractive/SwiftSortedList) - A sorted list implementation written in Swift :large_orange_diamond:
* [LeetCode-Swift](https://github.com/soapyigu/LeetCode-Swift) - Solutions to LeetCode by Swift.
* [BTree](https://github.com/attaswift/BTree) - Fast ordered collections for Swift using in-memory B-trees :large_orange_diamond:
* [SwiftStructures](https://github.com/waynewbishop/SwiftStructures) - Examples of commonly used data structures and algorithms in Swift. :large_orange_diamond:
* [diff](https://github.com/soffes/diff) - Simple diff library in pure Swift :large_orange_diamond:
* [Dollar](https://github.com/ankurp/Dollar) - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript https://www.dollarswift.org/. :large_orange_diamond:
* [Result](https://github.com/antitypical/Result) - Swift type modeling the success/failure of arbitrary operations. :large_orange_diamond:
* [Buffer](https://github.com/alexdrone/Buffer) - Swift μ-framework for efficient array diffs, collection observation and cell configuration. :large_orange_diamond:
* [SwiftGraph](https://github.com/davecom/SwiftGraph) - Graph data structure and utility functions in pure Swift. :large_orange_diamond:
* [SwiftPriorityQueue](https://github.com/davecom/SwiftPriorityQueue) - A priority queue with a classic binary heap implementation in pure Swift. :large_orange_diamond:
* [HeckelDiff](https://github.com/mcudich/HeckelDiff) - A fast Swift diffing library. :large_orange_diamond:
* [Dekoter](https://github.com/artemstepanenko/Dekoter) - `NSCoding`'s counterpart for Swift structs. :large_orange_diamond:

#### 数学@

* [Surge.swift](https://github.com/mattt/Surge) - Surge.swift基于苹果Accelerate高性能计算数学框架封装库.
* [swift-numerics](https://github.com/apple/swift-numerics) - 苹果出品的Numerical APIs for Swift.

#### 动画@

* [Hero](https://github.com/HeroTransitions/Hero) - 构建 iOS 试图控制器过渡动画的库。它在 UIKit 繁琐的过渡动画 API 之上提供了一个层，使得自定义过渡动画对于开发人员来说是一个轻松的任务.
* [ViewAnimator](https://github.com/marcosgriselli/ViewAnimator) - ViewAnimator brings your UI to life with just one line.
* [FleaMarket](https://github.com/SunLiner/FleaMarket) - "咸鱼"新特性-视频动画.
* [fave-button](https://github.com/xhamr/fave-button) - 给button增加了很多可爱的动画.
* [Sica](https://github.com/cats-oss/Sica) - Simple Interface Core Animation. Run type-safe animation sequencially or parallelly.
* [UIWindowTransitions](https://github.com/malcommac/UIWindowTransitions) - Animated transitions for UIWindow's rootViewController property.
* [Spring](https://github.com/MengTo/Spring) - A library to simplify iOS animations in Swift.
* [LoginCritter](https://github.com/cgoldsby/LoginCritter) - An animated avatar that responds to text field interactions.
* [SPPermission](https://github.com/IvanVorobei/SPPermission) - Simple request permission with native UI and interactive animation.

#### 转场动画@

* [Hero](https://github.com/lkzhao/Hero) - 非常👍👍👍 的转场动画库.
* [EasyTransitions](https://github.com/marcosgriselli/EasyTransitions) - A simple way to create custom interactive UIViewController transitions.

#### 特效@

* [Pastel](https://github.com/cruisediary/Pastel) 类似Instagram的梯度背景色界面动画效果. 🎨 Gradient animation effect like Instagram

#### 侧滑与右滑返回手势@

* [SideMenu](https://github.com/Yalantis/Side-Menu.iOS/tree/master/SideMenu) - swift实现，一款带动画效果可定制 Slide Menu，可以学习其动画实现思路。P.S. 对于Hamburger式菜单，虽然很常用，不过，苹果并不鼓励使用，甚至有开发小组对其弊病用自家上线应用前后数据对比进行了抨击。
* [QQConfiguration](https://github.com/shinept/QQConfiguration) - swift，QQ-iPhone端框架，左侧菜单栏拖动手势。
* [SwiftPages](https://github.com/GabrielAlva/SwiftPages) - 高可定制类似 Instagram 视图滑动切换功能类库。API 简单、易用。
* [FlowingMenu.swift](https://github.com/yannickl/FlowingMenu) - 菜单如此出场方式（橡皮筋弹跳式动画）好玩又有趣。

#### gif动画@

* [YLGIFImage-Swift](https://github.com/liyong03/YLGIFImage-Swift) - YLGIFImage-Swift。
* [gifu.Swift](https://github.com/kaishin/gifu) - gifu.Swift高性能GIF显示类库。
* [droptogif](https://github.com/mortenjust/droptogif) -  droptogif视频拖拽到应用窗口后自动转换为 GIF 动画（其转换进程动画效果也超赞）。
* [JWAnimatedImage.swift](https://github.com/wangjwchn/JWAnimatedImage) - JWAnimatedImage.swift集中了目前主流的 GIF 显示库(如 FLAnimatedImage,Gifu 等)的优点，进行重构，代码短小精悍。而且使用了新的 frame 提取算法。
* [SwiftyGif](https://github.com/kirualex/SwiftyGif) - 高性能 Gif 播放引擎。
* [PHImageKit.swift](https://github.com/producthunt/PHImageKit) - 出自 Product Hunter 开发小组的带下载、缓存的 GIF 播放组件库。使用简单又方便。

#### 其他动画@

* [GoogleNewsStandAnimation](https://github.com/AbhimanyuForiOS/GoogleNewsStandAnimation) It is same like Google News Stand Animation with Customise Configuration file in Swift iOS Technology.
* [popping](https://github.com/schneiderandre/popping) - popping是一个POP 使用实例工程
* [JHChainableAnimations](https://github.com/jhurray/JHChainableAnimations) 一个容易读，和使用的链式动画库.同时支持Objective-C
* [PopMenu](https://github.com/xhzengAIB/PopMenu) - 用POP动画引擎写的Sina微博的Menu菜单。
* [Spring](https://github.com/MengTo/Spring) - Spring是一个Swift编写的开源库，可简化Swift编写的iOS动画。支持shake、pop、morph、squeeze、wobble、swing、flipX、flipY、fall、squeezeLeft、squeezeRight以及squeezeDown等多种动画形式，用 IBDesignable 让使用者可以在 Xcode 中快速设置动画效果。
* [JGTransitionCollectionView](https://github.com/JayGajjar/JGTransitionCollectionView) - swift，基于集合视图扩展实现完成自动布局及单元项 Flip式动画效果（效果很赞）。组件使用方便、自然（只需设置集合视图数据源的标准方式即可）。
* [KYShareMenu](https://github.com/KittenYang/KYShareMenu) - 带弹性动画的分享菜单。
* [BuildAnInfiniteCarousel](https://github.com/johnlui/Swift-On-iOS/tree/master/BuildAnInfiniteCarousel) - 自己动手造无限循环图片轮播，[教程](https://autolayout.club/2015/10/29/%E8%87%AA%E5%B7%B1%E5%8A%A8%E6%89%8B%E9%80%A0%E6%97%A0%E9%99%90%E5%BE%AA%E7%8E%AF%E5%9B%BE%E7%89%87%E8%BD%AE%E6%92%AD/)。
* [LLCycleScrollView](https://github.com/LvJianfeng/LLCycleScrollView) - iOS图片轮播(图片循环播放), 支持文本图片结合,支持图片数据的延时加载,支持StoryBoard,支持本地图片显示及与网络图的混合显示
* [tispr-card-stack](https://github.com/tispr/tispr-card-stack) - swift 卡片风格动画切换组件及完整交互示例。
* [ZLSwipeableViewSwift](https://github.com/zhxnlai/ZLSwipeableViewSwift) - swift 卡片堆叠效果的实现（ZLSwipeableView)】可实现类似Tinder和Potluck应用程序的卡片堆叠效果，该项目基于[ZLSwipeableView objective-c](https://github.com/zhxnlai/ZLSwipeableView/)实现。1.自定义动画。2.自定义滑动切换。3.自定义方向。4.撤销。
* [Koloda](https://github.com/Yalantis/Koloda) - 基于卡片的 Tinder-style 动画效果示例。精细绝人。更赞的是额外附了详细开发教程 How We Built Tinder-Like Koloda Animation in Swift [网页链接](https://yalantis.com/blog/how-we-built-tinder-like-koloda-in-swift/) 。Yalantis 出品动画程序款款精品。
* [KDIntroView](https://github.com/likedan/KDIntroView) - swift 动态介绍视图框架及演示。另外两个相似的类库是 RazzleDazzle和 Presentation，择需使用。
* [RazzleDazzle](https://github.com/IFTTT/RazzleDazzle) - 【IFTTT开源Swift编写的帧动画框架--RazzleDazzle】RazzleDazzle 是IFTTT开源的一个iOS帧动画框架，非常适用于APP初次使用时的介绍和引导信息。JazzHands是UIKit一个简单的关键帧基础动画框架，可通过手势、scrollview、KVO等控制动画，被IFTTT应用在IFTTT for iPhone上。
* [SIFloatingCollection_Swift](https://github.com/ProudOfZiggy/SIFloatingCollection_Swift) - 可定制的 Apple Music 风格浮动形状动画组件及演示。
* [CKWaveCollectionViewTransition](https://github.com/CezaryKopacz/CKWaveCollectionViewTransition) - swift， UICollectionViewController之间切换的动画。
* [CardsAnimationDemo](https://github.com/adow/CardsAnimationDemo) - swift， [《使用 UICollectionView 实现的一个卡片动画》](http://swiftcn.io/topics/64?f=w)不是直接操作所有 UIView 和 CALayer 的 transform3D 属性来实现整个效果的，而是使用 UICollectionView 来完成所有的视图管理和实现。
* [TKRubberIndicator.swift](https://github.com/TBXark/TKRubberIndicator) - 一个很不错的 page control。
* [CHIPageControl.swift](https://github.com/ChiliLabs/CHIPageControl) - 一个多种样式的 page control。
* [TTGEmojiRate.swift](https://github.com/zekunyan/TTGEmojiRate) - TTGEmojiRate.swift以Emoji表情为基础绘图，[Swift开源项目: TTGEmojiRate的实现](http://tutuge.me/2015/10/25/ttgemojirate-lib/)。
* [CardAnimation.swift](https://github.com/seedante/CardAnimation) - CardAnimation 是国人开发的一个用 Swift 实现卡片垂直翻转动画的 Demo, [实现思路](http://www.jianshu.com/p/286222d4edf8)。
* [UIViewXXYBoom.swift](https://github.com/xxycode/UIViewXXYBoom) - 一个炫酷好玩的爆炸效果，[如何实现这个效果](http://xxycode.com/ru-he-zhi-zuo-ge-xuan-ku-hao-wan-de-bao-zha-xiao-guo-2/)。
* [ZLSwipeableViewSwift](https://github.com/zhxnlai/ZLSwipeableViewSwift) - [ZLSwipeableView](https://github.com/zhxnlai/ZLSwipeableView) - ZLSwipeableViewSwift在Tinder and Potluck中的动画效果实现思路（连续卡片翻页效果），最贴心的是作者提供了OC和Swift两个版本来供开发者使用，非常丝滑顺畅的效果。
* [RYCuteView](https://github.com/Resory/RYCuteView) - 用UIBezierPath实现果冻效果。 [教程](http://www.jianshu.com/p/21db20189c40)
* [IBAnimatable.swift](https://github.com/JakeLin/IBAnimatable) - 第三方开源库IBAnimatable可以帮助我们在Interface Builder和Swift Playground里面设计UI, 交互, 导航模式, 换场和动画。整个App 都是通过 IBAnimatable 在Interface Builder 设计完成，没有任何一行代码。
* [MotionMachine.swift](https://github.com/poetmountain/MotionMachine) - 功能强大、优雅、模块化动画库。
* [circle-menu.swift](https://github.com/Ramotion/circle-menu) - 动画效率很赞的圆形缩放菜单演示及类库。
* [BWWalkthrough.swift](https://github.com/ariok/BWWalkthrough) - BWWalkthrough.swift界面切换中加入灵动的动画效果。
* [hamburger-button.swift](https://github.com/robb/hamburger-button) - hamburger-button.swift一个汉堡包动画关闭按钮。
* [HamburgerButton.swift](https://github.com/fastred/HamburgerButton) - HamburgerButton.swift一个汉堡包动画返回按钮。
* [MDCSwipeToChooseView](https://github.com/modocache/MDCSwipeToChoose) - MDCSwipeToChooseView翻牌子效果。
* [Advance.swift](https://github.com/storehouse/Advance) - 简单易用、功能强大的动画框架库。在手势交互、帧动画、自定义动画及仿真类型将是不错的选择。
* [HWAnimationTransition_Swift](https://github.com/Loveway/HWAnimationTransition_Swift) 、[HWAnimationTransition_OC](https://github.com/Loveway/HWAnimationTransition_OC) - 类似于格瓦拉启动页中的放大转场动画（objective-C && Swift）。[教程](http://www.jianshu.com/p/8c29fce5a994)
* [NumberMorphView.swift](https://github.com/me-abhinav/NumberMorphView) - 可爱的数字补间（变身）动画类库。
* [DisplaySwitcher.swift](https://github.com/Yalantis/DisplaySwitcher) - 两个集合视图在不同布局（平铺和列表）间平滑切换。Yalantis 出品。
* [DynamicButton.swift](https://github.com/yannickl/DynamicButton) - 一套完整、且带动画过渡的图标按钮库。
* [TKDotSegment.swift](https://github.com/TBXark/TKDotSegment) - 是一个带有圆点动画的 segment。
* [LiquidLoader.swift](https://github.com/yoavlt/LiquidLoader) - 液态加载动画的轻量级 UI 组件。
* [15DaysofAnimationsinSwift](https://github.com/larrynatalicio/15DaysofAnimationsinSwift) - 15DaysofAnimationsinSwift动画。
* [Interpolate.swift](https://github.com/marmelroy/Interpolate) - 手势驱动交互式转场动画框架库。这个很专业，且非常有意思。
* [PeekPop.swift](https://github.com/marmelroy/PeekPop) - 3DTouch动画组件。
* [fantastic-ios-animation.swift](https://github.com/onmyway133/fantastic-ios-animation) - 基于 UI 组件类别分类，且带精彩动画效果的 iOS 组件库集合。
* [GridPanelDemo](https://github.com/JasonZengJ/GridPanelDemo) 赞，一个点击翻转的动画Demo
* [astrology-motion-ios](https://github.com/handsomecode/astrology-motion-ios) Astrology animation written in Swift 3

#### 富文本@

* [RichEditorView](https://github.com/cjwirth/RichEditorView) - swift，一套可定制富文本编辑器组件及示例。功能完整、代码简练、实现逻辑巧妙（编辑器核心与 WebView 结合，采用 HTML5 contentEditable 编辑模式，执行JS 配套命令 execCommand 实现富文本编辑功能）。
* [Ink](https://github.com/JohnSundell/Ink) - A fast and flexible Markdown parser written in Swift.
* [SwiftyMarkdown.swift](https://github.com/SimonFairbairn/SwiftyMarkdown) - 用swift写的markdown解析库。
* [Marklight.swift](https://github.com/macteo/Marklight) - Markdown 语法高亮显示编辑库（Swift）。
* [LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel) - swift 能够实现文字变形动画效果的Label，用Swift写的一个能够实现文字变形动画效果的Label，很炫。
* [Splitflap.swift](https://github.com/yannickl/Splitflap) - 可用于快速给 iOS 应用创建文字翻转的动画效果。
* [FloatLabelFields.swift](https://github.com/FahimF/FloatLabelFields) - FloatLabelFields.swift浮动标签输入效果类。
* [cleartext-mac.swift](https://github.com/mortenjust/cleartext-mac) - 提供一千个常用单词的编辑器。
* [GlitchLabel.swift](https://github.com/kciter/GlitchLabel) - 可定制“黑（故障）文字标签”类库，熟称晃瞎你的眼文字标签。

#### 文本@

* [PowerMode](https://github.com/younatics/PowerMode) - TextView输入时的水花效果.
* [Stryng](https://github.com/BalestraPatrick/Stryng) - Swift strings taken to a whole new syntax level.
* [MessageViewController](https://github.com/GitHawkApp/MessageViewController) - A SlackTextViewController replacement written in Swift for the iPhone X.

#### 字体@

* [FontAwesomeKit](https://github.com/PrideChung/FontAwesomeKit) 图片字体库，支持超级字体、基础Icon等，支持同时支持Swift.
* [Twinkle](https://github.com/piemonte/Twinkle) - 为字体加上钻石版闪耀的效果。使用Swift编写.

* [DefaultStringConvertible](https://github.com/jessesquires/DefaultStringConvertible) - A default CustomStringConvertible implementation for Swift types 🔶[e]


#### UI@

* [AsyncDisplayKit](https://github.com/facebookarchive/AsyncDisplayKit) - Facebook 为他们的 app Paper 创造了这个异步 UI SDK。如果你想让你的 app 总是每秒用 60 帧的速度来渲染，可以看看这个库.
* [Material](https://github.com/CosmicMind/Material) - A UI/UX framework for creating beautiful applications.
* [IBLinter](https://github.com/kateinoigakukun/IBLinter) - A linter tool for Interface Builder.

### SwiftUI@

* [swift-markdown-ui](https://github.com/gonzalezreal/swift-markdown-ui) - 用于在 SwiftUI 中显示和自定义 Markdown 文本的开源库.


#### AutoLayout@

* [Snap](https://github.com/SnapKit/SnapKit) - Snap是Masonry Auto Layout DSL的Swift版本，是一款轻量级的布局框架，使用了更良好的语法封装了AutoLayout。Snap支持iOS和OS X.
* [Cartography](https://github.com/robb/Cartography) - 一个很赞的Auto Layout库.
* [Neon](https://github.com/mamaral/Neon) - 功能强大的 UI 布局神器.
* [TinyConstraints](https://github.com/roberthein/TinyConstraints) - TinyConstraints is the syntactic sugar that makes Auto Layout sweeter for human use.
* [EasyPeasy](https://github.com/nakiostudio/EasyPeasy) - 编程方式自动布局框架库.
* [TangramKit](https://github.com/youngsoft/TangramKit) - TangramKit is a powerful iOS UI framework implemented by Swift. It integrates the functions with Android layout,iOS AutoLayout,SizeClass, HTML CSS float and flexbox and bootstrap. So you can use LinearLayout,RelativeLayout,FrameLayout,TableLayout,FlowLayout,FloatLayout,LayoutSizeClass to build your App 自动布局 UIView UITableView UICollectionView.
* [layout](https://github.com/schibsted/layout) - A declarative UI framework for iOS.
* [CassowarySwift](https://github.com/tribalworldwidelondon/CassowarySwift) - A Swift port of the Cassowary linear constraint solver.
* [Windless](https://github.com/Interactive-Studio/Windless) - Windless makes it easy to implement invisible layout loading view.
* [KeyboardLayoutGuide](https://github.com/freshOS/KeyboardLayoutGuide) - ⌨️ Apple's missing KeyboardLayoutGuide.
* [Yalta](https://github.com/kean/Yalta) - An intuitive and powerful Auto Layout library.

#### 列表@
#### TableView、CollectionView、表相关、即时聊天UI等

* [folding-cell](https://github.com/Ramotion/folding-cell) - FoldingCell is an expanding content cell with animation inspired by folding paper material design UI.
* [SwipeCellKit](https://github.com/jerkoch/SwipeCellKit) - 很赞的tableView左滑删除效果.
* [Eureka.swift](https://github.com/xmartlabs/Eureka) - Eureka 是 XLForm 的 Swift 的移植版本, 一个可以帮助开发者们快速构建 iOS 各种复杂表单的库, 具有较高的可扩展性, 方便自定制样式.
* [HBHorizontalTableView](https://github.com/izyhuang/HBHorizontalTableView) - TableView 横向滚动小示例（仿照 AppStore 应用展示）.
* [Chats](https://github.com/acani/Chats) - 聊天 UI 示例程序。此项目应该只为演示或学习之用，没有服务器.
* [Chatto](https://github.com/badoo/Chatto) - 轻量级聊天应用框架及示例。文字及图片可扩展输入栏，汽泡效果等聊天核心特性，分页及自动布局完善.
* [COBezierTableView](https://github.com/knutigro/COBezierTableView) - swift，通过编辑 Bezier 曲线四点位置设置 TableView 内 Cell 及对应按扭位置。实验效果很赞。
* [LxTabBarController](https://github.com/DeveloperLx/LxTabBarController) - 改变了原生tabbar切换tab时的生硬效果，并加入滑动切换手势（有和界面上的其它手势发生冲突的风险，可根据具体项目予以关闭），[swift版本](https://github.com/DeveloperLx/LxTabBarController-swift).
* [ABExpandableView](https://github.com/alicanbatur/ABExpandableView) - Expandable, collapsible, filterable and single/multi selectable table view.
* [RxDataSources](https://github.com/RxSwiftCommunity/RxDataSources) - UITableView and UICollectionView Data Sources for RxSwift (sections, animated updates, editing ...).
* [Cards](https://github.com/PaoloCuscela/Cards) - Awesome iOS 11 appstore cards in swift 4.
* [Sapporo](https://github.com/nghialv/Sapporo) - swift 单元格模型驱动的集合视图管理器组件。又一个超实用的“轮子”.
* [NavTopImage](https://github.com/itjhDev/NavTopImage) - NavigationController动态缩放titleView.
* [paper-onboarding.swift](https://github.com/Ramotion/paper-onboarding) - 漂亮的 material design 风格页面滑块。示例完整，易用.
* [ReorderableGridView-Swift](https://github.com/cemolcay/ReorderableGridView-Swift) - 拖拽排序卡片.
* [ZYThumbnailTableView](https://github.com/liuzhiyi1992/ZYThumbnailTableView) - 可展开型预览TableView，开放接口，完全自由定制。[实现教程](http://zyden.vicp.cc/zythumbnailtableview/)
* [WHC_CollectionViewFramework](https://github.com/netyouli/WHC_CollectionViewFramework) - 高仿支付宝可拖拽排序编辑动画效果cell的CollectionView集合视图.
* [SwipeViewController](https://github.com/fortmarek/SwipeViewController) - 一款好用的页面滑动和标签选项卡类库及示例。功能相当于 Objective-C 版 RKSwipeBetweenViewControllers.
* [TabDrawer](https://github.com/winslowdibona/TabDrawer) - 更适合单手操作的可定制 Tab Bar 组件库。P.S. 自动布局选择了 EasyPeasy.
* [SFFocusViewLayout](https://github.com/fdzsergio/SFFocusViewLayout) - UICollectionViewLayout实现的图片浏览器.
* [ESTabBarController](https://github.com/eggswift/ESTabBarController) - 自定义TabBarController组件，继承自UITabBarControlle，可添加动画和自定义样式。[swift 高度自定义TabBarController，支持自定义TabBarItem样式或添加动画](http://www.jianshu.com/p/9e52630e7368).
* [GLTableCollectionView](https://github.com/giulio92/GLTableCollectionView) - Netflix and App Store like UITableView with UICollectionView, written in pure Swift 3.0.
* [EditDistance](https://github.com/kazuhiro4949/EditDistance) - tableView、CollectionView 数据重载更新效果Demo.
* [CenteredCollectionView](https://github.com/BenEmdon/CenteredCollectionView) - 轻量级的CollectionViewCell左右滑动效果，类似电影App选电影的效果.
* [WCLWaterFallLayout](https://github.com/631106979/WCLWaterFallLayout) - 用swift写的简易的瀑布流布局，简单易用，支持多行展示，实现过程：http://blog.csdn.net/wang631106979/article/details/53793046 .
* [LNZTreeView](https://github.com/gringoireDM/LNZTreeView) - 一个树状的列表View.
* [FunctionalTableData](https://github.com/Shopify/FunctionalTableData) - Declarative UITableViewDataSource implementation.
* [DeepDiff](https://github.com/onmyway133/DeepDiff) - 支持列表和宫格列表快速变换的列表库.
* [TiltedTabView](https://github.com/IMcD23/TiltedTabView) - iOS control to replicate the tab switcher in Safari for iOS.
* [TabView](https://github.com/IMcD23/TabView) - Easily add multiple tabs to your iOS app, styled similar to Safari for iPad.
* [Parade](https://github.com/HelloElephant/Parade) - Parallax Scroll-Jacking Effects Engine for iOS / tvOS.
* [MagazineLayout](https://github.com/airbnb/MagazineLayout) - A collection view layout capable of laying out views in vertically scrolling grids and lists.

#### scrollView@

* [ScrollableGraphView](https://github.com/philackm/ScrollableGraphView) - 自适应滚动视图的图表控件.

#### HUD与Toast@

* [SwiftProgressHUD](https://github.com/stackhou/SwiftProgressHUD) -SwiftProgressHUD is a user-friendly pure swift HUD. 支持Cocoapods 及 Carthage.
* [SwiftEntryKit](https://github.com/huri000/SwiftEntryKit) - SwiftEntryKit is a banner presenter library for iOS. It can be used to easily display pop-ups and notification-like views within your iOS apps.
* [InputBarAccessoryView](https://github.com/nathantannar4/InputBarAccessoryView) - A simple and easily customizable InputAccessoryView for making message input bars! As featured in MessageKit.
* [Toast-Swift](https://github.com/scalessec/Toast-Swift) - 高可定制易用的 Toast 弹出信息或通知用户界面组件类.
* [SkeletonView](https://github.com/Juanpe/SkeletonView) - An elegant way to show users that something is happening and also prepare them to which contents he is waiting.
* [StatusAlert](https://github.com/LowKostKustomz/StatusAlert) - Display Apple system-like self-hiding status alerts. It is well suited for notifying user without interrupting user flow in iOS-like way.

#### 图表@

* [Charts](https://github.com/danielgindi/Charts) - 一款非常👍👍👍 优秀的图表开源库 MPAndroidChart 的 Swift 语言实现版（支持 Objective-C 和 Swift 调用）.漂亮的线图、饼图、条形图、分布图、气泡图、雷达图还有更多种类.
* [swift-linechart](https://github.com/zemirco/swift-linechart) - 功能完整、实用的折线图组件。使用方便，参数配置简单。是不可多得的优质组件--swift.
* [SpreadsheetView](https://github.com/kishikawakatsumi/SpreadsheetView) - 很棒👍 的电子表格库. 可以完全配置的电子表格View,使用此库你能很容易的创建出复杂布局的表格，比如时间表、甘特图、课程表，就像你使用Excel一样.
* [Scrollable-GraphView.swift](https://github.com/philackm/Scrollable-GraphView) - 灵动感十足的自适应、可定制滚动曲（折）线图表库.
* [SwiftChart](https://github.com/gpbl/SwiftChart) - Line and area chart library for iOS.

#### IM@

* [MessageKit.swift](https://github.com/MessageKit/MessageKit) - 消息 UI 库 JSQMessagesViewController 的 Swift 版。
* [jchat-swift](https://github.com/jpush/jchat-swift) - 一个聊天 App,具有完备的即时通讯功能,JChat 的功能基于极光 JMessage SDK 来开发。

#### WebView@

* [IOSCallJsOrJsCallIOS](https://github.com/CoderJackyHuang/IOSCallJsOrJsCallIOS) - IOSCallJsOrJsCallIOS：利用iOS7.0后出来的JavaScriptCore framework，webview与Js交互是常见的需求。OC版本与swift版本。[《OC JavaScriptCore与js交互》](http://www.henishuo.com/oc-js/),[《Swift JavaScriptCore与js交互》](http://www.henishuo.com/swift-js/)。
* [WKWebViewTestDemo.swift](https://github.com/CoderJackyHuang/WKWebViewTestDemo) - WKWebViewTestDemo：WKWebView新特性及JS交互,[文章讲解](http://www.henishuo.com/wkwebview-js/)。
* [React.swift](https://github.com/alexdrone/Render) - 启发自 React 的纯 Swift 函数版基于 UIKit 封装类库。这种结构是否似曾相识。
* [GRMustache](https://github.com/groue/GRMustache) 一个类似templateEngine的html渲染工具，可以更加有效的帮助大家完成数据生成HTML的过程。
* [MarkdownView](https://github.com/keitaoouchi/MarkdownView) Markdown View for iOS. MarkdownView is a WKWebView based UI element, and internally use bootstrap, highlight.js, markdown-it.
* [swift-deep-linking](https://github.com/ijoshsmith/swift-deep-linking) 深度链接 A simple way to consume custom deep link URLs in a Swift app
* [highlight](https://github.com/taggon/highlight) Rich featured syntax highlighter for Keynote slides.
* [WKZombie](https://github.com/mkoehnke/WKZombie) - WKZombie is a Swift framework for iOS/OSX to navigate within websites and collect data without the need of User Interface or API, also known as Headless browser. It can be used to run automated tests or manipulate websites using Javascript. :large_orange_diamond:

#### 日历@

* [Timepiece](https://github.com/naoty/Timepiece) - Swift 里直观的日期处理.
* [JTAppleCalendar](https://github.com/patchthecode/JTAppleCalendar) The Unofficial Apple iOS Swift Calendar View. iOS calendar Library. iOS calendar Control. 100% Customizable.
* [FSCalendar](https://github.com/WenchaoD/FSCalendar) 一款漂亮，强大的 iOS 日历组件 A fully customizable iOS calendar library, compatible with Objective-C and Swift.
* [CalendarKit](https://github.com/richardtop/CalendarKit) 一 类似于iOS日历应用程序的库 A fully customizable day view calendar library written in Swift.

#### 时间@

* [Chronology](https://github.com/davedelong/Chronology) - Building a better date/time library for Swift.
* [D2PDatePicker](https://github.com/di2pra/D2PDatePicker) - Elegant and Easy-to-Use iOS Swift Date Picker.

#### 下拉刷新@

* [PullUpController](https://github.com/MarioIannotta/PullUpController) - Pull up controller with multiple sticky points like in iOS Maps.
* [BreakOutToRefresh](https://github.com/dasdom/BreakOutToRefresh) - swift，上拉和下拉刷新.
* [GearRefreshControl](https://github.com/andreamazz/GearRefreshControl) -  swift，上拉和下拉刷新.
* [refresher](https://github.com/jcavar/refresher) -  swift，上拉和下拉刷新.
* [ReplaceAnimation.swift](https://github.com/fruitcoder/ReplaceAnimation) - 基于 @ZeeYoung欧阳哲 同学的创意下拉刷新动画实现。值得称赞还有额外增加了“取消及滚动”效果支持。
* [PullToReflesh-Swift](https://github.com/cbangchen/PullToReflesh-Swift) - 一款炫酷的下拉刷新封装库（Mobile page refresh concept inspired by Google and for something like a news app）。[源码分析 ](http://cbang.info/2016/03/04/CBReflesh%EF%BC%9A%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90/)
* [pull-to-refresh.swift](https://github.com/eggswift/pull-to-refresh) - 是一款非常易于开发者使用的下拉刷新和加载更多组件。通过一个 UIScrollView 的扩展，可以轻松为 UIScrollView 的所有子类添加下拉刷新功能。
* [GSRefresh](https://github.com/wxxsw/GSRefresh) 完全自定义视图和动画的下拉刷新、上拉加载库，易扩展。

#### 模糊效果@

* [Blurable.swift](https://github.com/FlexMonkey/Blurable) - swift模糊组件。

#### 选择器@

* [AGCircularPicker](https://github.com/agilie/AGCircularPicker) - AGCircularPicker is helpful component for creating a controller aimed to manage any calculated parameter.
* [McPicker](https://github.com/kmcgill88/McPicker-iOS) - A customizable, closure driven UIPickerView drop-in solution with animations that is rotation ready. :large_orange_diamond:
* [Mandoline](https://github.com/blueapron/Mandoline) - An iOS picker view to serve all your "picking" needs.

#### 对话框@

* [AZDialogViewController](https://github.com/Minitour/AZDialogViewController) - A highly customizable alert dialog controller that mimics Snapchat's alert dialog.
* [Alerts-Pickers](https://github.com/dillidon/Alerts-Pickers) - Advanced usage of UIAlertController with TextField, DatePicker, PickerView, TableView and CollectionView.
* [SPStorkController](https://github.com/IvanVorobei/SPStorkController) - Modal controller as in mail or Apple music application.
* [SwiftyDrop](https://github.com/morizotter/SwiftyDrop) - 轻量、易用的小清新弹出列表及信息提示组件真心不错.
* [PCLBlurEffectAlert.swift](https://github.com/hryk224/PCLBlurEffectAlert) - 细节定制较丰富的弹出警报窗口组件.
* [GSAlert.swftt](https://github.com/wxxsw/GSAlert) - 苹果在iOS8推出了全新的UIAlertController，旧的UIAlertView和UIActionSheet渐渐被废弃，但如果你仍然支持iOS7系统，你将不得不写两套代码。GSAlert解决了这个问题.
* [TKSwarmAlert.swift](https://github.com/entotsu/TKSwarmAlert) - TKSwarmAlert.swift:模仿 Swarm app 的 Alert 提醒框动画工具.
* [PMAlertController.Swift](https://github.com/Codeido/PMAlertController) - 可定制弹窗组件替代官版不可定制的 UIAlertController.
* [TBActionSheet.swift](https://github.com/yulingtianxia/TBActionSheet) - 支持Carthage，可自定义度100%的 ActionSheet，支持微信样式.
* [NoticeBar](https://github.com/qiuncheng/NoticeBar)Notice View相关的简易库，叫做NoticeBar, 在NavigationBar、Tabbar、statusBar上显示提示信息，信息可包含文字和图片等，并且内置了四种提示消息.
* [PPAssetsActionController](https://github.com/pantuspavel/PPAssetsActionController) - 高度可定制的Action Sheet.
* [SwiftMessages](https://github.com/SwiftKickMobile/SwiftMessages) - 用于以屏幕顶部或底部的状态栏的形式显示简短的消息.

#### pop@

* [alerts-and-pickers](https://github.com/dillidon/alerts-and-pickers) - Advanced usage of UIAlertController and pickers based on it: Telegram, Contacts, Location, PhotoLibrary, Country, Phone Code, Currency, Date...
* [panelkit](https://github.com/louisdh/panelkit) - 手势拖动弹出面板视图 A UI framework that enables panels on iOS.
* [FloatingPanel](https://github.com/SCENEE/FloatingPanel) - 易于使用的浮动面板UI组件.
* [ElongationPreview](https://github.com/Ramotion/elongation-preview) - 一个优雅的push-pop风格的视图控制器  ElongationPreview is an elegant push-pop style view controller with 3D-Touch support and gestures. :large_orange_diamond:
* [PopupWindow](https://github.com/shin8484/PopupWindow) - PopupWindow is a simple Popup using another UIWindow in Swift.
* [Pageboy](https://github.com/MerrickSapsford/Pageboy) -  一个简单、易学的page View Controller A simple, highly informative page view controller. :large_orange_diamond:
* [GTSheet](https://github.com/gametimesf/GTSheet) - An easy to integrate solution for presenting UIViewControllers in a bottom sheet

#### 导航栏@

* [Bartinter](https://github.com/MaximKotliar/Bartinter) - Dynamically changes status bar style depending on content behind it.
* [Tiptoes](https://github.com/caiyue1993/Tiptoes) - 提供了一种自定义 Navigation Bar 的新思路，并实现了转场渐变效果，灵感来自于 Unread.
* [RxFlow](https://github.com/RxSwiftCommunity/RxFlow) - RxFlow is a navigation framework for iOS applications based on a Reactive Flow Coordinator pattern.

#### Label@

* [LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel) 炫酷的Label效果 [EXPERIMENTAL] Graceful morphing effects for UILabel written in Swift.

#### 瀑布流@

* [ELWaterFallLayout](https://github.com/NicolasKim/ELWaterFallLayout）  swift可定制瀑布流布局 UI 组件。

#### 菜单@

* [Swift-CircleMenu](https://github.com/Sufi-Al-Hussaini/Swift-CircleMenu) Swift-CircleMenu：一款圆盘式菜单,Rotating circle menu written in Swift 3

#### TabBar@

* [animated-tab-bar](https://github.com/Ramotion/animated-tab-bar) 给tabbar item增加动画效果的一个组件.
* [CBMDTabbarController](https://github.com/cbangchen/CBMDTabbarController) It is a smooth MD tabbarController used on iOS, which implement by Swift.
* [TransitionableTab](https://github.com/Interactive-Studio/TransitionableTab) - 简单、易用、tab、可定制的标签栏切换效果.

#### 进度@

* [ButtonProgressBar-iOS](https://github.com/thePsguy/ButtonProgressBar-iOS) A small and flexible UIButton subclass with animated loading progress, and completion animation.
* [KYCircularProgress](https://github.com/kentya6/KYCircularProgress) - 简单、实用路径可定进程条。
* [KDCircularProgress](https://github.com/kaandedeoglu/KDCircularProgress) - KDCircularProgress是使用swift制作的色彩炫丽的进度条，可以加入多种颜色来控制进度条的渐变效果.

#### 引导页@

* [WhatsNewKit](https://github.com/SvenTiigi/WhatsNewKit) - Showcase your awesome new app features（高可定制应用更新特性展示视图）.
* [WhatsNew](https://github.com/BalestraPatrick/WhatsNew) - Showcase new features after an app update similar to Pages, Numbers and Keynote.
* [MZGuidePages](https://github.com/MachelleZhang/MZGuidePages) - 自己写的通用导航页，可以直接引入工程使用，请参考案例（版本新特性、导航页、引导页）.
* [Intro](https://github.com/nbolatov/Intro) - 简单的功能引导组件.
* [Wizardry.swift](https://github.com/ijoshsmith/Wizardry) - 可重用的方法和框架实现向导式用户界面管理。（版本新特性、导航页、引导页）.
* [liquid-swipe](https://github.com/Cuberto/liquid-swipe) - Cuberto is a leading digital agency with solid design and development expertise. We build mobile and web products for startups. Drop us a line.

#### page@

* [FSPagerView](https://github.com/WenchaoD/FSPagerView) FSPagerView is an elegant Screen Slide Library. It is extremely helpful for making Banner View、Product Show、Welcome/Guide Pages、Screen/ViewController Sliders.
* [Tabman](https://github.com/uias/Tabman) - ™️ A powerful paging view controller with indicator bar.
* [XLPagerTabStrip](https://github.com/xmartlabs/XLPagerTabStrip) - 非常赞 的iOS下的PagerTabStrip。
* [PinterestSegment](https://github.com/TBXark/PinterestSegment) 仿 Pinterest 的 Segment 控件(swift), 行数 200+

#### 评分@

* [iOS-RatingBar](https://github.com/saiwu-bigkoo/iOS-RatingBar) - iOS-RatingBar swift版的评分控件,跟Android的RatingBar一样有两种模式，评分模式和只读模式'支持视图编辑，自定义星星数量，评分等级,另外还能支持非整数星，0.5颗星，0.1颗星,可以开启动画效果。
* [SwiftyStarRatingView](https://github.com/Jerrrr/SwiftyStarRatingView) SwiftyStarRatingView 是一个用 swift 3.0 编写的评分控件，可以支持自定义图片和颜色，并且可以支持在XIB、StoreBoard中使用，并支持AutoLayout。

#### 键盘@

* [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager) - 处理键盘事件强大的库，有OC和Swift版本，纯代码、Storyboard和Xib都适用。

#### 搜索@

* [YNSearch](https://github.com/younatics/YNSearch) 一个非常棒，完全自定义的搜索View，支持历史记录，标签等等功能.
* [fuse-swift](https://github.com/krisk/fuse-swift) A lightweight fuzzy-search library, with zero dependencies

#### 倒计时@

* [SRCountdownTimer](https://github.com/rsrbk/SRCountdownTimer) 一个圆形倒计时View
* [Time](https://github.com/dreymonde/Time) 🕰 Type-safe time calculations in Swift, powered by generics

#### Button@

* [ZFRippleButton](https://github.com/zoonooz/ZFRippleButton) Custom UIButton effect inspired by Google Material Design
* [ZMaterialDesignUIButton](https://github.com/richzertuche/ZMaterialDesignUIButton) - Swift Material Design UIButton.

#### 3D@

* [Euclid](https://github.com/nicklockwood/Euclid) - A Swift library for creating and manipulating 3D geometry.

#### Slider@

* [Sliders](https://github.com/SwiftUIExtensions/Sliders) - SwiftUI Sliders with custom styles.

#### 其他UI@

* [Persei](https://github.com/Yalantis/Persei) - 非常赞 动画隐藏或显示顶部菜单支持库及示例项目。--swift
* [DateRangePicker.swift](https://github.com/MrMage/DateRangePicker) - 可能是目前最好的 OS X 日期选择器,高扩展性，界面风格看起来很舒服，不过注意，是 OS X 开发专用。
* [SwiftyFORM](https://github.com/neoneye/SwiftyFORM) - swift 表单输入框架（亮点是表单验证规则引擎），是我见过地最易用的 Swift 表单组件。
* [SwiftSpinner](https://github.com/icanzilb/SwiftSpinner) - SwiftSpinner是使用swift制作的一款精致带感的指示器，并且连带有字体信息显示，模糊背景，半透明，扁平化等IOS8的效果。
* [AKPickerView-Swift](https://github.com/Akkyie/AKPickerView-Swift) - 一款小而美的 3D 效果选择器。
* [LxGridView-oc](https://github.com/DeveloperLx/LxGridView) [LxGridView-swift](https://github.com/DeveloperLx/LxGridView-swift) - 利用UICollectionView模仿iOS系统桌面图标的交互，作用如动图。
* [WMDragView](https://github.com/zhengwenming/WMDragView) WMDragView可以自由拖曳的view
* [GMStepper](https://github.com/gmertk/GMStepper) - swift 带动画效果、支持手势滑动操作的步进标签。
* [LayoutTrait](https://github.com/yushuyi/LayoutTrait) - swift 一个小类库。 做iPad 多任务分屏 适配的同学可以看一下。
* [BTNavigationDropdownMenu](https://github.com/PhamBaTho/BTNavigationDropdownMenu) -  下拉列表暨导航标题组件。简单、直接、易用 -swift。
* [InceptionTouch.swift](https://github.com/richzertuche/InceptionTouch) - 让没有 3D Touch 设备也有类似交互体验的 InceptionTouch 类（基于 UITextView 实现，支持日期，链接，电话号码，地址触摸响应）。
* [TWControls.swift](https://github.com/txaidw/TWControls) - 简单的开关和按钮控制器,使用闭包来执行由控件触发的操作。
* [Instructions.swift](https://github.com/ephread/Instructions) - 可定制嵌入式操作指引框架及演示。
* [SMSegmentView.swift](https://github.com/sima-11/SMSegmentView) - 高可定制化，既支持横向，也支持纵向布局的图文 Segment Control 组件，节选器。
* [Gecco.Swift](https://github.com/yukiasai/Gecco) - Gecco.Swift 是一款支持对视图进行局部高亮的 Swift 库, 帮助 iOS 开发者快速创建产品的新手指导界面。
* [SubtleVolume.swift](https://github.com/andreamazz/SubtleVolume) - 更隐蔽的系统音量替代指示器。
* [InkKit.swift](https://github.com/shaps80/InkKit) - 该类库帮助开发者绘制简单图形更容易。
* [SwiftSVG](https://github.com/mchoe/SwiftSVG) - 支持多种接口（String, NS/UIBezierPath, CAShapeLayer, and NS/UIView）绘制 SVG 类库。
* [LeeGo.swift](https://github.com/wangshengjia/LeeGo) - 带来更 声明式的，可配置的和易复用的UI开发方式，让UI开发变得像玩乐高积木一样简单直观，某种程度上取代ComponentKit。[用 struct 和 enum 来构建你的整套 UI](http://allblue.me/swift/2016/05/26/LeeGo-chinese-version/)
* [Caishen.swift](https://github.com/prolificinteractive/Caishen) - 简易、实用的付款输入及校验 UI 组件。
* [CreditCardForm-iOS](https://github.com/orazz/CreditCardForm-iOS) 信用卡输入效果
* [StackViewController](https://github.com/seedco/StackViewController) - 方便 iOS 开发者使用 UIStackView 构建表单或其它静态内容视图。
* [LLBootstrapButton](https://github.com/lilei644/LLBootstrapButton) - Bootstrap 3.0扁平化风格按钮，自带图标，一句代码直接调用！
* [JMRoundedCorner](https://github.com/raozhizhen/JMRoundedCorner) - UIView设置不触发离屏渲染的圆角！
* [PagingMenuController](https://github.com/kitasuke/PagingMenuController) - 侧滑页面切换ViewController库，支持页面标题定制
* [ZSeatSelector](https://github.com/richzertuche/ZSeatSelector) - 电影院位置排座位，电影选座。
* [JMRoundedCornerSwift](https://github.com/raozhizhen/JMRoundedCornerSwift) - swift版本：UIView设置不触发离屏渲染的圆角！
* [PPNumberButtonSwift](https://github.com/jkpang/PPNumberButtonSwift) - 仿京东淘宝商品数量的加减按钮 Swift 版,可定制程度高,使用简单!

#### 多线程@

* [Overdrive](https://github.com/arikis/Overdrive)专注于类型安全、并发和多线程的，快速 、专业的异步任务库 Fast async task based Swift framework with focus on type safety, concurrency and multi threading
* [Jobs](https://github.com/BrettRToomey/Jobs)Swift Job 队列
* [Kommander-iOS](https://github.com/intelygenz/Kommander-iOS) Swift 多线程任务管理库，很强大。
* [GCDKit](https://github.com/JohnEstropia/GCDKit) 简单的GCD用法
* [Async](https://github.com/duemunk/Async) GCD异步派遣的语法糖
* [SwiftSafe](https://github.com/nodes-ios/SwiftSafe) 线程同步、线程安全
* [YYDispatchQueuePool](https://github.com/ibireme/YYDispatchQueuePool) 管理全局派遣队列的实用类
* [AlecrimAsyncKit](https://github.com/Alecrim/AlecrimAsyncKit) Swift关于异步、等待的一些好的经验
* [Threader](https://github.com/mitchtreece/Threader) - 漂亮的GCD使用和简单执行
* [Dispatch](https://github.com/Swiftification/Dispatch) 让GCD更容易、简单使用的轻量级的库 Just a tiny library to make using GCD easier and intuitive :large_orange_diamond:
* [GCDTimer](https://github.com/hemantasapkota/GCDTimer) - Well tested Grand Central Dispatch (GCD) Timer in Swift.
* [Chronos-Swift](https://github.com/comyar/Chronos-Swift) GCD工具类
* [Me](https://github.com/pascalbros/Me) 嵌套异步计算的一个超级轻量级的解决方案
* [SwiftyTask](https://github.com/CR-Creations/SwiftyTask) 一个高性能的排队系统，用于管理App中的全部任务。
* [Queuer](https://github.com/FabrizioBrancati/Queuer) Queuer is a queue manager, built on top of OperationQueue and Dispatch (aka GCD).

#### 工具@
#### category@

* [SwifterSwift](https://github.com/SwifterSwift/SwifterSwift) - SwifterSwift 是一个用 Swift 编写的 Extension 的集合，涵盖了开发过程中大部分会用到的方法和函数，是一个不错的工具库.
* [BFKit-Swift](https://github.com/FabrizioBrancati/BFKit-Swift) 一个非常不错的分类集合工具库，大幅提高开发效率.同时包含Objective-C版本

#### Color@

* [Chameleon](https://github.com/ViccAlexander/Chameleon) - Chameleon是一个非常棒👍👍👍iOS的色彩框架。它运用现代化flat color将UIColor扩展地非常美观。我们还可以通过它运用自定义颜色创建调色板。它还有很多功用，请浏览readme。同时支持Objective-C.
* [UIImageColors](https://github.com/jathu/UIImageColors) - Fetches the most dominant and prominent colors from an image.
* [IGColorPicker](https://github.com/iGenius-Srl/IGColorPicker) - 一个自定义颜色选择器 🎨 A customizable color picker for iOS in Swift 🔶
* [RandomColorSwift](https://github.com/onevcat/RandomColorSwift) - 一个自动生成好看的颜色的 Swift 库，RandomColorSwift.
* [Hue.Swift](https://github.com/hyperoslo/Hue) - Hue.Swift：颜色常规功能集于一身的定义、使用 Color 工具类库（含图片取色).
* [KtColor.swift](https://github.com/bestswifter/MySampleCode/tree/master/KtColor) - 利用 Swift 的语法特性简化创建 UIColor对象的过程。具体文章可以参考博客：[当UIColor遇上 Swift](http://www.jianshu.com/p/f2173235cde8).

#### Xcode工具@

* [CopilotForXcode](https://github.com/github/CopilotForXcode) - 专为Xcode开发者打造的AI编程助手.
* [injectionforxcode](https://github.com/johnno1962/injectionforxcode) - Injection for Xcode：成吨的提高开发效率,[使用说明](http://www.jianshu.com/p/27be46d5e5d4).
* [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) - 用于重新格式化 Swift 代码的命令行工具.
* [Reminders](https://github.com/tiagomartinho/Reminders) - Clean Architecture.
* [SwiftGen](https://github.com/SwiftGen/SwiftGen) - SwiftGen is a tool to auto-generate Swift code for resources of your projects, to make them type-safe to use.
* [FileExplorer](https://github.com/Augustyniak/FileExplorer) - 完整的文件资源管理器组件.
* [Drafter](https://github.com/L-Zephyr/Drafter) - 在iOS项目中自动生成类图和方法调用图 - Generate call graph in iOS project.
* [Swimat](https://github.com/Jintin/Swimat) - Swimat，是一款Xcode 插件，帮你一键格式化 swift 代码.
* [XcodeSwiftSnippets](https://github.com/burczyk/XcodeSwiftSnippets) - XcodeSwiftSnippets, 提供了很多可在 Xcode 上使用的 Swift 代码片段, 通过自动补全的方式极大的提高了开发效率.
* [SwiftLint](https://github.com/realm/SwiftLint) - 是一个用于强制检查Swift 代码风格和规定的一个工具，基本上以GitHub's Swift 代码风格指南为基础.
* [XcodeGen](https://github.com/yonaskolb/XcodeGen) - Command line tool that generates your Xcode project from a simple spec and your folder structure.
* [SwiftRewriter](https://github.com/inamiy/SwiftRewriter) - Swift code formatter using SwiftSyntax.
* [sake](https://github.com/xcodeswift/sake) - Sake is a Swift command line tool that helps you automate tasks in your projects.
* [SourceKitten](https://github.com/jpsim/SourceKitten) - 一个可爱的用于与SourceKit交互的小框架与命令行工具.
* [xcbeautify](https://github.com/thii/xcbeautify) - A little beautifier tool for xcodebuild.
* [quicktype-xcode](https://github.com/quicktype/quicktype-xcode) - 将json数据快速转换为模型类.
* [MotherShip](https://github.com/thecb4/MotherShip) - iTunes Connect Library inspired by FastLane.
* [FengNiao](https://github.com/onevcat/FengNiao) - 一个清理Xcode中没使用的资源文件的命令行工具.
* [stylesync](https://github.com/dylanslewis/stylesync) - A command line tool to extract shared styles from a Sketch document, and generate native code for any platform.

#### 压缩解压@

* [Zip](https://github.com/marmelroy/Zip) - Swift framework for zipping and unzipping files.

#### 测试调试@

* [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) - 是一个快速、简单，但很强大的日志框架，可以自定义打印日志的颜色.
* [Nimble](https://github.com/Quick/Nimble) - Swift 和 Objective-C 的匹配器.
* [ResponseDetective](https://github.com/netguru/ResponseDetective) - 一个非嵌入式框架，用于拦截应用程序和服务器之间的任何传出请求和传入响应以用于调试目的.
* [GDPerformanceView-Swift](https://github.com/dani-gavrilov/GDPerformanceView-Swift) - 在状态栏上方显示 FPS，CPU 使用情况，app 和 iOS 版本，并通过 delegate 报告 FPS 和 CPU 使用情况.
* [Quick](https://github.com/Quick/Quick) - 非常赞👍👍👍 用于Swift中的单元测试（也可用于Objective-C），与Xcode整合在一起。如果你是Objective-C的粉丝，我建议用Specta代替这个，但是对Swift使用者来说，Quick是最佳选择.
* [XCGLogger](https://github.com/DaveWoodCom/XCGLogger) - XCGLogger.swift功能完整的日志管理类库.
* [FBSimulatorControl](https://github.com/facebook/FBSimulatorControl) - 支持同时启动多个模拟器的库，FaceBook出品.
* [depcheck](https://github.com/wojteklu/depcheck) - Swift 工程分析工具(Dependency analyzer tool for Swift projects).
* [CleanroomLogger](https://github.com/emaloney/CleanroomLogger) - 相当于 CocoaLumberjack 或 Log4j 的 Swift 版本，功能上甚至更强大。另外，源代码中已经内含了完整的 API 文档，使用非常方便.
* [SwiftyBeaver](https://github.com/SwiftyBeaver/SwiftyBeaver) - 一个完善的日志工具，支持彩色输出、输出内容到文件、重要性分级、多输出目标。工具执行在后台，不影响性能，可以极大提高开发效率.
* [Cuckoo](https://github.com/Brightify/Cuckoo) - First boilerplate-free mocking framework for Swift.
* [LifetimeTracker](https://github.com/krzysztofzablocki/LifetimeTracker) - 内存分析，帮助找出循环引用等内存问题.Find retain cycles / memory leaks sooner.
* [swift-snapshot-testing](https://github.com/pointfreeco/swift-snapshot-testing) - 一个快照测试库，以方便您对视图进行UI测试.
* [Sleipnir](https://github.com/railsware/Sleipnir) - Swift的测试框架.
* [XXPlaceHolder.swift](https://github.com/adad184/XXPlaceHolder) - MMPlaceHolder的swift版本。
* [swiftlog](https://github.com/iachievedit/swiftlog) - 为Swift 应用提供快捷添加日志信息的方法，Swift 包管理支持（SPM）、 使用惊艳的 Rainbow 包输出彩色日志、支持写入文件。[使用 swiftlog](https://segmentfault.com/a/1190000004512773).
* [Log.swift](https://github.com/delba/Log) - 灵活、易用、可定制输出格式和主题风格的日志类（Swift）,支持控制台彩色输出.
* [Cuckoo.swift](https://github.com/SwiftKit/Cuckoo) - Cuckoo.swift一款用法更接近于传统单元测试 Mock 框架库（区别之处在于需要用脚本预先生成 Mock 类）.
* [Peek](https://github.com/shaps80/Peek) - 更友好、手势方式检查界面内组件布局信息（相当于浏览器元素检查功能），界面调试利器.
* [CocoaDebug](https://github.com/CocoaDebug/CocoaDebug) - iOS内置调试工具(日志打印/网络监控/内存监控/沙盒查看...)[兼容Swift和Objective-C].

#### 分析@

* [GoogleReporter](https://github.com/ksmandersen/GoogleReporter) Easily integrate your app with Google Analytics

#### 优化@

* [Optimizing-Swift-Build-Times](https://github.com/fastred/Optimizing-Swift-Build-Times) - Collection of advice on optimizing compile times of Swift projects.
* [Lotusoot](https://github.com/Vegetarians/Lotusoot) - 灵活的 Swift 组件解耦和通信工具.

#### 日志@

* [swift-log](https://github.com/apple/swift-log) - A Logging API for Swift.

#### 游戏@

* [FlappySwift](https://github.com/fullstackio/FlappySwift) - swift implementation of flappy bird.
* [Legend-Wings](https://github.com/woguan/Legend-Wings) iOS Swift Game - Push SpriteKit to the limit

#### 小样@
#### VR@

* [swift-360-videos](https://github.com/team-pie/DDDKit) - 360度视频播放器，以swift3编写的iOS - SceneKit的一个子集. Pure swift (no SceneKit) 3D library with focus on video and 360.
* [VRDemo-Swift](https://github.com/Huanhoo/VRDemo-Swift) VRDemo是用Swift配合OpenGL ES实现的360度全景播放器

#### AR@

* [awesome-arkit](https://github.com/olucurious/awesome-arkit) - 👍👍👍 A curated list of awesome ARKit projects and resources.
* [ARuler](https://github.com/duzexu/ARuler) - Mesure distance using apple ARKit.
* [Findme](https://github.com/mmoaay/Findme) - An ARKit App that can help your friends to find you.
* [ARKit-CoreLocation](https://github.com/ProjectDent/ARKit-CoreLocation) - Combines the high accuracy of AR with the scale of GPS data.
* [Measure](https://github.com/levantAJ/Measure) - Using ARKit to make calculate distance of real world objects.
* [ARCharts](https://github.com/Boris-Em/ARCharts) - Lovely Augmented Reality Charts for iOS - Built with ARKit.
* [arkit-smb-homage](https://github.com/bjarnel/arkit-smb-homage) - An implementation of a Super Mario Bros-like game in augmented reality with ARKit and SceneKit.
* [ARKit-Sampler](https://github.com/shu223/ARKit-Sampler) - Code examples for ARKit.
* [ARVideoKit](https://github.com/AFathi/ARVideoKit) - Capture & record ARKit videos 📹, photos 🌄, Live Photos 🎇, and GIFs 🎆..
* [SmileToUnlock](https://github.com/rsrbk/SmileToUnlock) - This library uses ARKit Face Tracking in order to catch a user's smile.

#### 机器学习@

* [SeeFood](https://github.com/kingreza/SeeFood) - Inspired by HBO's Silicon Valley: SeeFood is an iOS app that uses CoreML to detect various dishes

#### AI@

* [SwiftAI](https://github.com/hhfa008/SwiftAI) - SwiftAI, write Swift code smart. SwiftAI can generate Model class from JSON now. Codable and HandyJSON is supported. More features will be add.

#### 全景@

* [BSPanoramaView](https://github.com/bestswifter/BSPanoramaView) - 超轻量级的 iOS 全景图组件.

#### VPN@

* [ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG) - Next Generation of ShadowsocksX.
* [V2rayU](https://github.com/yanue/V2rayU) - V2rayU,基于v2ray核心的mac版客户端,用于科学上网,使用swift编写,支持vmess,shadowsocks,socks5等服务协议,支持订阅, 支持二维码,剪贴板导入,手动配置,二维码分享等.
* [vpnon](https://github.com/lexrus/vpnon/) - swift的VPN On 的源码和本地化内容都是开放的: [官方网站](https://crowdin.com/project/vpnon).
* [Potatso](https://github.com/haxpor/Potatso) - 一个实现Shadowsocks代理的客户端.
* [mac-app](https://github.com/ProtonVPN/mac-app) - Official ProtonVPN macOS app.

#### 蓝牙@

* [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - 是一个非常容易使用的蓝牙库, 适用于 iOS 和 Mac OS, 基于原生 CoreBluetooth 框架封装, 可以帮开发者们更简单地使用 CoreBluetooth API, 使用链式方法体, 使得代码更简洁、优雅。[iOS蓝牙开发（四）：BabyBluetooth蓝牙库介绍](http://www.cocoachina.com/ios/20160219/15301.html)
* [RxBluetoothKit.swift](https://github.com/Polidea/RxBluetoothKit) - 基于 RxSwift 的蓝牙通讯库。
* [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - The easiest way to use Bluetooth (BLE) in iOS/MacOS.

#### 地图@

* [Cluster](https://github.com/efremidze/Cluster) - 非常不错的地图标注聚合.
* [ArcKit](https://github.com/sobri909/ArcKit) - Location and activity recording framework for iOS

#### 通知@

* [NotificationBanner](https://github.com/Daltron/NotificationBanner) - 最容易的方法显示高度自定义的通知.
* [Homeoff](https://github.com/lizyyy/Homeoff) - 用swift写了一个模仿Launcher通知中心快捷方式的应用。支持20个应用，并增加了一个返回到桌面来解放Home键的功能。
* [SwiftNotificationCenter](https://github.com/100mango/SwiftNotificationCenter) - 一个面向协议的类型安全、线程安全、内存安全的通知中心。

#### 电池@

* [DeviceKit](https://github.com/dennisweissmann/DeviceKit) - DeviceKit 是 UIDevice 的值类型替换。轻松获取设备信息和电池电量.

#### Swift学习资料@

* [swift-evolution](https://github.com/apple/swift-evolution) Swift更新日志
* [SwiftGuide](https://github.com/ipader/SwiftGuide) - 这份文档汇集了Swift 开源精选资源，思维导图形式呈现.
* [ioscreator](https://github.com/ioscreator/ioscreator) - Tutorials from ioscreator.com.
* [SwiftGuide](https://github.com/ipader/SwiftGuide) 很赞 这份指南汇集了Swift语言主流学习资源，并以开发者的视角整理编排-- 非常不错，值得推荐。
* [leetcode](https://leetcode.com/accounts/login/) 一个练习、评估自己水平的代码平台，跟ACM有点类似
* [Swift中文指南](https://github.com/numbbbbb/the-swift-programming-language-in-chinese) - 中文版Apple官方Swift教程《The Swift Programming Language》，[老码版本](https://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/)  [历史版本更新说明](https://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/chapter1/03_revision_history.html)。
* [iOS-Swift-Demos](https://github.com/Lax/iOS-Swift-Demos) 精心收集并分类整理的Swift开发学习资源，包括Apple官方提供的示例代码和文档，以及github上的项目和国内外开发者的技术博客。欢迎提交pull-request一起维护。[iOS Swift Demos from Apple] http://blog.liulantao.com/SwiftBeginnersGuide/
* [Swift 开源项目精选－v1.0](http://dev.swiftguide.cn/archive/featured-open-source-projects-in-swift_v1.0.html) - Swift 开源项目精选－v1.0.
* [The Swift Programming Language 中文版](http://wiki.jikexueyuan.com/project/swift/) - The Swift Programming Language 中文版。
* [swifttoolbox](http://www.swifttoolbox.io/) -  swifttoolbox swift开发的开源库汇总。
* [Awesome Swift](https://swift.zeef.com/robin.eggenkamp) - 一个收集了很多 Swift 开发资源的网站。
* [Developing_iOS_8_Apps_With_Swift](https://github.com/CS193P-Translation-Group/Developing_iOS_8_Apps_With_Swift) - Developing iOS 8 Apps with Swift 字幕简体中文翻译项目（斯坦福白胡子老头swift教学视频）.
* [Swift-On-iOS](https://github.com/johnlui/Swift-On-iOS) - JohnLui 的 Swift On iOS 代码仓库.
* [30DaysofSwift](https://github.com/allenwong/30DaysofSwift) - 30DaysofSwift 自学 iOS - [三十天三十个 Swift 项目](http://weibo.com/ttarticle/p/show?id=2309403942494873235448).
* [MySampleCode](https://github.com/bestswifter/MySampleCode) Swift的一些Demo.
* [iOS与swift学习之路](https://toutiao.io/subjects/35291#187)
* [iOS-Weekly](https://github.com/SwiftOldDriver/iOS-Weekly) - 老司机 iOS 周报.
* [Mocker](https://github.com/WeTransfer/Mocker) - A simple mocker framework for Swift.

#### Swift小Demo@

* [MTSwift-Learning](https://github.com/MartinRGB/MTSwift-Learning) - 通过一些简单项目实战演练开始学习 Swift 。
* [iOS8-day-by-day](https://github.com/shinobicontrols/iOS8-day-by-day) - swift。
* [iOS9-day-by-day](https://github.com/shinobicontrols/iOS9-day-by-day) - swfit [iOS9 Day-by-Day :: Day 2 :: UI Testing](http://www.jianshu.com/p/039f8de6ee4d)。
* [iOS 9 分屏多任务](http://www.cocoachina.com/ios/20150714/12557.html) - iOS 9 分屏多任务：Slide Over & Split View快速入门（中文版）。
* [uistackview-sample.swift](https://github.com/uraimo/uistackview-sample) - iOS 9 引进了 UIStackViews，提供 auto-layout 特性。如果你开发过 Android 应用，会发现它和 LinearLayouts 概念上很类似，它是增强版。你可以手动创建，也可以使用 IB 自动创建，本文用的是代码实现。

#### 其他开源总结@

* [awesome-swift](https://github.com/matteocrippa/awesome-swift) - A collaborative list of awesome swift resources 非常👍👍👍 .
* [awesome-swift](https://github.com/Wolg/awesome-swift) - A curated list of awesome Swift frameworks, libraries and software.
* [SwiftMarch](https://github.com/SwiftOldDriver/SwiftMarch) - 从开发者角度介绍被广泛运用于实际Swift项目中的开源库。
* [swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries) - Swift UI libraries, iOS components and animations.
* [top](https://github.com/app-developers/top) - Top App Developers - December 2018.

#### iOS版本适配@

* [iOS-11-by-Examples](https://github.com/artemnovichkov/iOS-11-by-Examples) Examples of new iOS 11 APIs.
* [NotchKit](https://github.com/HarshilShah/NotchKit) A simple way to hide the notch on the iPhone X.
* [HairPowder](https://github.com/intmain/HairPowder) Hair Powder for iPhoneX "M" Shape pattern baldness design.
* [iPhoneMoCapiOS](https://github.com/johnjcsmith/iPhoneMoCapiOS) - Real-time Facial Performance Capture with iPhone X.

#### 其他库@

* [SwiftDate](https://github.com/malcommac/SwiftDate) - 特别完整、强大的日期时间操作管理类库。它几乎涵盖了已知开源日期类库所有优秀特性。 他能帮你轻松处理时区，处理时间加减，计算到期时间等等场景下的问题.
* [SYKeyboardTextField](https://github.com/yushuyi/SYKeyboardTextField) - SYKeyboardTextField 是一个轻巧,简单,非侵入式的键盘附随输入框! 采用Swift编写.
* [RandomKit](https://github.com/nvzqz/RandomKit) - 简单易用的随机数据生成.
* [Parsimmon](https://github.com/ayanonagon/Parsimmon) - swift，小而美的语言学类库封装工具包。提供分词、标记词性、词形归并、朴素贝页斯分类、决策树等自然语言分析小工具。P.S. 英语分词效果好于中文，感兴趣的同学可以针对中文做一些优化开发。参考译文 NSHipster - [NSLinguistic​Tagger](http://nshipster.cn/nslinguistictagger/).
* [MKMapView-Extension](https://github.com/SemperIdem/MKMapView-Extension) - 这是关于 MKMapView 写的一个基于swift的扩展，可以扩展 MKMapView 的相关功能，减少复用代码量.
* [SwiftValidator](https://github.com/jpotts18/SwiftValidator) - 基于规则的输入验证类库。项目良好的面向对象设计思想，使规则的扩展及自定义非常方便。更专业的规则引擎（甚至是基于自然语言的规则配置）解决方案，比如：开源的 Drools，商用的 ILOG 等.
* [Validated.swift](https://github.com/Ben-G/Validated) - Validated.swift通过值验证或限定，快速定义新类型的微类库（约50行代码).
* [Regex.swift](https://github.com/sharplet/Regex) - 实用的正则表达式微框架类库.
* [PySwiftyRegex.swift](https://github.com/cezheng/PySwiftyRegex) - 像Python一样简洁高效地作正则处理.
* [PhoneNumberKit.swift](https://github.com/marmelroy/PhoneNumberKit) -  解析、格式化及验证国际电话号码工具库（相当于 Google 的 libphonenumber 库的 Swift 版本）.
* [SwiftSequence](https://github.com/oisdk/SwiftSequence) - 简洁、灵活、多变的操作 SequenceType 的类库（基于微框架（μframework）设计思想).
* [IDNFeedParser](https://github.com/photondragon/IDNFeedParser) - 一个简单易用的Rss解析库.
* [Swifternalization](https://github.com/tomkowz/Swifternalization) - 一套实用的本地化工具库。使用教程及 API 文档完整。值得收入项目的“轮子”.
* [Localize-Swift](https://github.com/marmelroy/Localize-Swift) - Localize-Swift一款开发者不可或缺的国际化及本地化字符串框架支持类库。同样地，使用简单、直观又方便.
* [apous](https://github.com/owensd/apous) - 一款有趣的 Swift 应用 － 让 Swift 成为脚本语言.
* [ControlOrientation](https://github.com/johnlui/Swift-On-iOS/tree/master/ControlOrientation/ControlOrientation) - 如何用代码控制以不同屏幕方向打开新页面【iOS】， [使用说明](https://lvwenhan.com/ios/458.html).
* [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit) - 一款轻量级的 iOS 应用内购买框架.
* [Device-swift](https://github.com/Ekhoo/Device) - 可以非常方便的获取设备型号和屏幕尺寸，实现起来难度不大，大家可以学习一下源码.
* [Plum-O-Meter](https://github.com/FlexMonkey/Plum-O-Meter) - swift 称重应用， (3D Touch之我见)[http://swift.gg/2015/10/23/3d-touch-impressions-and-thoughts/]。
* [打开自带地图、百度地图、腾讯地图](http://code.cocoachina.com/view/128249) - 打开自带地图、百度地图、腾讯地图.
* [MapManager.swift](https://github.com/varshylmobile/MapManager) - MapManager.swift地图及路径管理封装库.
* [eviltransform.swift](https://github.com/googollee/eviltransform) - eviltransform.swift解决国内GPS地图坐标偏移问题,它将政府加密过的GCJ-02坐标，转成世界通用的WGS-84坐标.
* [BluetoothKit.swift](https://github.com/rasmusth/BluetoothKit) - 基于 CoreBluetooth API 实现iOS/OS X 设备间蓝牙通讯封装类库。功能强大、传输稳定，示例完整，很酷.
* [CoreDataStack.swift](https://github.com/bignerdranch/CoreDataStack) - 存储栈.
* [SYNQueue.swift](https://github.com/THREDOpenSource/SYNQueue) - 执行队列类库.
* [DDMathParser.swift](https://github.com/davedelong/DDMathParser) - 相比 NSExpression 和 GCMathPaser，功能更强大的数学表达式解析器.
* [RateLimit.swift](https://github.com/soffes/RateLimit) - 简单、实用定时执行任务工具类库.
* [shoppingCart.swift](https://github.com/6ag/shoppingCart) - swift的购物车demo，采用纯代码UI，autolayout自动布局，core animation动画效果.
* [SwiftyGPIO](https://github.com/uraimo/SwiftyGPIO) - 通过 Swift 语言去控制基于 Linux 主板（比如：C.H.I.P. 和 树莓派） 的 GPIO（General Purpose Input Output ），去完成简单的工控功能（比如 LED 灯的显示）.
* [Scale.swifty](https://github.com/onmyway133/Scale) - 简单直观的单位计算及换算类库（支持常用计量类型）。代码简洁性、直观性杠杠的.
* [swift-pons](https://github.com/dankogai/swift-pons) - 面向协议的不受长度限制数字类型及数学计算扩充类库。用它做一款最牛科学计算器妥妥地.
* [SwiftString](https://github.com/amayne/SwiftString) - SwiftString:String 扩展功能很丰富（无论格式化杂乱字符串，还是子串查找，亦或是格式转换都很强大）.
* [FileBrowser.swift](https://github.com/marmelroy/FileBrowser) - FileBrowser.swift 一款开源的 iOS 文件浏览器, 支持文件搜索, 文件预览和 3D touch 功能.
* [AFBrushBoard.swift](https://github.com/marmelroy/FileBrowser) -  AFBrushBoard.swift基于swift的毛笔画板Demo。包含多阶贝塞尔曲线的抽取、模拟画笔速度等算法.
* [SwiftForms](https://github.com/ortuman/SwiftForms) - SwiftForms表单递交库，快速开发利器.
* [Design-Patterns-In-Swift](https://github.com/ochococo/Design-Patterns-In-Swift) - Design-Patterns-In-Swift如何使用常用设计模式及示例.
* [Dollar.swift](https://github.com/ankurp/Dollar) - Dollar.swift是一个Swift库，无需扩展任何内置对象就为Swift语言提供有效的函数式编程辅助方法，类似于Lo-Dash或JavaScript中的Underscore。而Cent则是通过扩展功能来扩展Swift中的特定对象类型.
* [Underscore.swift](https://github.com/JakeLin/Underscore) - 函数式编程辅助方法，可靠性上压倒目标对手是 Dollar.
* [PathKit.swift](https://github.com/kylef/PathKit) - PathKit.swift小而美的路径管理类.
* [Async.swift](https://github.com/duemunk/Async) - Async.swift简洁的后台执行代码的异步封装库.
* [AlecrimAsyncKit.swift](https://github.com/Alecrim/AlecrimAsyncKit) - 一款很优雅的异步执行框架库.
* [BrightFutures.swift](https://github.com/Thomvis/BrightFutures) - BrightFutures.swift漫长或复杂计算由独立线程异步来完成.
* [Euler.swift](https://github.com/mattt/Euler) - Euler.swift直观、简洁的数学表达式∛27÷3+∑[3,1,2].
* [Siren.swift](https://github.com/ArtSabintsev/Siren) - Siren.swift当应用更新时，通知用户并提供App Store链接.
* [BTree.swift](https://github.com/lorentey/BTree) - BTree.swift:相对于标准集合类型具有更优执行性能的基于B-Tree的优化集合类型实现类库.
* [Duration.swift](https://github.com/SwiftStudies/Duration) - 测量代码片段执行时间工具类库（Swift）.
* [Bolts-Swift](https://github.com/BoltsFramework/Bolts-Swift) - 全平台（所有支持 Swift 的设备）任务管理 futures/promises 异步实现类库.
* [BCColor.swift](https://github.com/boycechang/BCColor) - 轻量而强大的颜色处理库，纯 Swift 版。 支持从图片拾取一套主题色，类似AppleMusic；支持图片黑白化、对颜色的加深和变浅、生成渐变颜色等.
* [AIToolbox.swift](https://github.com/KevinCoble/AIToolbox) - AI 主流模块集工具箱库。其中涉及 AI 知识实在广阔又高端.
* [EZSwiftExtensions](https://github.com/goktugyil/EZSwiftExtensions) - 对Swift标准库， Foundation， UIKit 提供了很多高级扩展函数.
* [Venice.swift](https://github.com/VeniceX/Venice) - 让 Swift 3 提前支持协程（Coroutine）。P.S.  Chris  曾答疑过，Coroutine 不在 Swift 3 支持范围中，将在更晚时候讨论语言级支持.
* [FlatBuffersSwift](https://github.com/mzaks/FlatBuffersSwift) - Swift 版 FlatBuffers 实现类库。P.S. FlatBuffers 是跨平台、高效，提供了 C++/Java 接口的序列化开源工具库.
* [Lyft.swift](https://github.com/genadyo/Lyft) - 一套面向 Lyft 开发者的 Swift API 类库.
* [Up-Down.swift](https://github.com/gjiazhe/Up-Down) - Up-Down.swift:在 OS X 菜单栏上实时显示网络上传和下载速度小工具.
* [Algorithm.swift](https://github.com/genadyo/Lyft) - 算法和概率模型工具集。（作者 Daniel Dahan）.
* [Spots.swift](https://github.com/hyperoslo/Spots) - 一套为了加速开发效率、将 view models 采用 JSON 格式存储于云端 view controller 框架库.
* [PinpointKit.swift](https://github.com/Lickability/PinpointKit) - 简单的手势动作快速触发反馈组件。主要功能包含自动截屏、附加说明和日志。支持添加可定制箭头、着重框、文本、模糊打码等常用快照编辑功能。它非常适合开发过程中测试人员反馈缺陷.
* [Switcher.swift](https://github.com/X140Yu/Switcher) - 一个 OS X 小 App，可以很轻松地切换 App Store 和 iTunes 的账号，对于同时使用多个 Apple ID 的人来说非常地方便.
* [MotionBook](https://github.com/younatics/MotionBook) - Awesome iOS UI/UX Animation Book.
* [AlternativeIcon-Example](https://github.com/KimDarren/AlternativeIcon-Example) 😱 Change your iOS application's icon programmatically since iOS 10.3.
* [Eureka](https://github.com/xmartlabs/Eureka) 简洁方便的 iOS 表单生成器 （Swift 3）.
* [SwiftKotlin](https://github.com/angelolloqui/SwiftKotlin) A tool to convert Swift code to Kotlin.
* [Archit-iOS](https://github.com/intelygenz/Archit-iOS) - Intelygenz iOS Architecture.
* [Snap.swift](https://github.com/skyweb07/Snap.swift) - Snapshot testing in a snap 🎨 .

#### AppleWatch@

* [Apple Watch开发教程资料汇总](http://www.swiftkiller.com/?p=613) - Apple Watch开发教程资料汇总。
* [WatchKit-Apps](https://github.com/kostiakoval/WatchKit-Apps) WatchKit教程
* [Stargate](https://github.com/contentful-labs/Stargate) - 通过 iPhone 桥接实现 Mac 与 Watch 的即时通讯。Stargate 通过封装两个优秀的基础类库 MMWormhole 和 PeerKit 实现高效的通讯应用。--swift
* [soon](https://github.com/sandofsky/soon) - 一款倒计时 WatchKit 示例应用。作者从架构的角度，思考如何设计一款完整、通讯高效且性能又好的 WatchKit 扩展应用。
* [MMWormhole.swift](https://github.com/mutualmobile/MMWormhole) - MMWormhole.swift:iOS或OS X扩展与宿主应用的通讯框架。
* [overlook](https://github.com/wess/overlook) 可以监测目标目录文件改变，执行对应命令的后台及命令行工具 The Judge, Jury and Executioner for the file system.
* [CircularCrownSelector](https://github.com/mkchoi212/CircularCrownSelector) - watchOS UI for a circular selection menu.

#### TV@

* [PopcornTimeTV](https://github.com/PopcornTimeTV/PopcornTimeTV) - Popcorn Time for Apple TV 4, iPhone and iPad.

#### mac@

* [open-source-mac-os-apps](https://github.com/serhii-londar/open-source-mac-os-apps) - Awesome list of open source applications for macOS.
* [stats](https://github.com/exelban/stats) - Stats is an application that allows you to monitor your macOS system.
* [twig](https://github.com/lukakerr/twig) - A modern macOS markdown editor.
* [VoiceInk](https://github.com/Beingpax/VoiceInk) - mac App 即时语音转文字工具.
* [Aerial](https://github.com/JohnCoates/Aerial) - Apple TV Aerial Screensaver for Mac.
* [iina](https://github.com/lhc70000/iina) - The modern video player for macOS,非常👍👍👍 .
* [mas](https://github.com/mas-cli/mas) - Mac App Store command line interface.
* [iOSLocalizationEditor](https://github.com/igorkulman/iOSLocalizationEditor) - Simple macOS editor app to help you manage iOS app localizations by allowing you to edit all the translations side by side(一款在 macOS 上帮助用户编辑和管理 app localizations 的图形化工具，它会显示每种语言的所有本地化版本，并能方便快捷的找出你缺失的 key).
* [AltStore](https://github.com/rileytestut/AltStore) - AltStore 是一个 iOS 应用程序，允许您仅使用 Apple ID 将其他应用程序（.ipa 文件）侧面加载到您的 iOS 设备上.
* [DockDoor](https://github.com/ejbills/DockDoor) - 一个为macOS设计的开源工具，允许用户通过鼠标悬停在Dock栏图标上来预览应用程序的窗口，从而提高多窗口操作的效率.
* [Atoll](https://github.com/Ebullioscopic/Atoll) - 一个为macOS系统设计的开源项目，旨在利用刘海屏（如Face ID区域）实现类似iPhone的动态岛交互功能，提供实时信息展示和交互体验.
* [swift14macOSApps](https://github.com/KrisYu/swift14macOSApps) - 几个Mac小Demo.
* [SpotMenu](https://github.com/kmikiy/SpotMenu) - 菜单栏中的Spotify和iTunes.
* [xi-mac](https://github.com/google/xi-mac) - The xi editor project is an attempt to build a high quality text editor.
* [mas](https://github.com/mas-cli/mas) - 📦 Mac App Store command line interface.
* [Dozer](https://github.com/Mortennn/Dozer) - Hide status bar icons on macOS.
* [fsnotes](https://github.com/glushchenko/fsnotes) - Notes manager for macOS/iOS.
* [SidecarPatcher](https://github.com/pookjw/SidecarPatcher) - Enables Sidecar on old Mac and iPad for macOS 10.15.
* [SpechtLite](https://github.com/zhuhaow/SpechtLite) - A rule-based proxy for macOS.
* [swift-argument-parser](https://github.com/apple/swift-argument-parser) - Apple 最近新开源了一个库，叫 ArgumentParser，它是由 Swift 实现的，用于解析命令行参数（command-line arguments）的.

#### game@

* [VirtualGameController](https://github.com/robreuss/VirtualGameController) - Software-based game controllers for iOS, tvOS, OS X and watchOS in Swift 4.
* [SaveTheDot](https://github.com/JakeLin/SaveTheDot) - A game developed using UIViewPropertyAnimator.
* [TouchBreakout](https://github.com/songkuixi/TouchBreakout) - Play Breakout Game on your Touch Bar, using SpriteKit.

#### 服务端@

* [Httper-iOS](https://github.com/MuShare/Httper-iOS) - App for developers to test REST API. https://httper.mushare.cn.
* [Publish](https://github.com/JohnSundell/Publish) - Publish是一款专门为Swift开发者打造的静态网站生成器。它使用Swift构建整个网站，并支持主题、插件和其他大量的定制选项.
* [README.zh_CN.md](https://github.com/PerfectlySoft/Perfect/blob/master/README.zh_CN.md) - Swift 语言服务器端软件框架.
* [PersistQL](https://github.com/PersistX/PersistQL) - Projection-based GraphQL Clients and Servers in Swift.
* [Perfect](https://github.com/PerfectlySoft/Perfect) - Server-side Swift. The Perfect core toolset and framework for Swift Developers. (For mobile back-end development, website and API development, and more…)
* [PerfectTemplate](https://github.com/PerfectlySoft/PerfectTemplate) Empty Starter Project (for Perfect).
* [vapor](https://github.com/vapor/vapor) - A server-side Swift web framework.
* [SwiftQ](https://github.com/John-Connolly/SwiftQ) - SwiftQ is a distributed task queue for server side swift applications.
* [SwiftServerSide-Vapor](https://github.com/Jinxiansen/SwiftServerSide-Vapor) - Swift server open source projects based on the Swift 4.1 and Vapor 3 frameworks. (Swift 服务端开源项目).
* [http](https://github.com/vapor/http) -  Non-blocking, event-driven HTTP built on Swift NIO.
