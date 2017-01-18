# TimLiu-iOS
github排名 [https://github.com/trending](https://github.com/trending),github搜索：[https://github.com/search](https://github.com/search)

[Objective-C版本点击这里](https://github.com/Tim9Liu9/TimLiu-iOS/blob/master/README.md)

主要工作说明：
  1. 将Swift从Objective-C混合的md文件中抽出（正在进行...）

使用方法：根据目录关键字搜索，记得包含@，以保证搜索目录关键字的唯一性。

问题反馈：请广大网友只按照目录结构（即使目录结构有问题）添加三方库，并pull request。目录问题大家提出issues后楼主会及时更改的。

## 目录
- [Swift学习资料@](#swift学习资料)
- [完整App@](#完整app)
- [Xcode8插件@](#xcode8插件)
- [App 框架@](#app框架)
  - [响应式框架@](#响应式框架)
- [UI@](#ui)
  - [日历@](#日历)
  - [下拉刷新@](#下拉刷新)
  - [模糊效果@](#模糊效果)
  - [富文本@](#富文本)
  - [颜色@](#颜色)
  - [图表@](#图表)
  - [表相关(TabbleView、Tabbar、即时聊天界面)@](#表相关tabbleviewtabbar即时聊天界面)
  - [隐藏与显示@](#隐藏与显示)
  - [HUD与Toast@](#hud与toast)
  - [对话框@](#对话框)
  - [状态栏@](#状态栏)
  - [导航栏@](#导航栏)
  - [设置@](#设置)
  - [Switch@](#switch)
  - [主题@](#主题)
  - [电影选座@](#电影选座)
  - [瀑布流@](#瀑布流)
  - [菜单@](#菜单)
  - [TabBar@](#tabbar)
  - [进度@](#进度)
  - [引导页@](#引导页)
  - [page@](#page)
  - [评分@](#评分)
  - [其他UI@](#其他ui)
- [多线程@](#多线程)
- [游戏@](#游戏)
- [动画@](#动画)
  - [侧滑与右滑返回手势@](#侧滑与右滑返回手势)
  - [gif动画@](#gif动画)
  - [其他动画@](#其他动画)
- [AutoLayout@](#autolayout)
- [网络相关@](#网络相关)
  - [网络连接@](#网络连接)
  - [图像获取@](#图像获取)
  - [网络聊天@](#网络聊天)
  - [网络测试@](#网络测试)
  - [网页框架@](#网页框架)
  - [网络解析@](#网络解析)
      - [CSV](#csv)
      - [JSON@](#json)
      - [XML&HTML@](#xmlhtml)
      - [Other Parsing@](#other-parsing)
- [二维码@](#二维码)
- [VR@](#VR)
- [开发资料@](#开发资料)
  - [播客@](#播客)
  - [学习资料@](#学习资料)
  - [他人开源总结@](#他人开源总结)
  - [开发博客列表@](#开发博客列表)
  - [学习笔记、书籍@](#学习笔记书籍)
  - [设计@](#设计)
  - [好的文章@](#好的文章)
  - [美工资源@](#美工资源)
- [开发工具@](#开发工具)
  - [Xcode插件@](#xcode插件)
  - [好用的软件@](#好用的软件)
  - [Cagegory@](#cagegory)
- [测试及调试@](#测试及调试)
- [数据存储@](#数据存储)
  - [缓存处理@](#缓存处理)
  - [CoreData@](#coredata)
  - [数据库@](#数据库)
  - [序列化@](#序列化)
- [WebView与WKWebView@](#webview与wkwebview)
- [FaceBook@](#faceBook)
- [通讯录@](#通讯录)
- [Email@](#email)
- [三方分享、支付、登录等等@](#三方分享支付登录等等)
- [其他库@](#其他库)
- [PDF@](#pdf)
- [图像浏览及处理@](#图像浏览及处理)
  - [图像圆角@](#图像圆角)
- [摄像照相视频音频处理@](#摄像照相视频音频处理)
- [视频@](#视频)
- [消息相关@](#消息相关)
  - [消息推送客户端@](#消息推送客户端)
  - [消息推送服务器端@](#消息推送服务器端)
  - [通知相关@](#通知相关)
- [时间日期@](#时间日期)
- [设计模式@](#设计模式)
- [版本新API的Demo@](#版本新api的demo)
- [代码安全与密码@](#代码安全与密码)
- [动态更新@](#动态更新)
- [AppleWatch@](#applewatch)
- [VPN@](#vpn)
- [物联网@](#物联网)
- [未分类@](#未分类)

-------
具体内容

## Swift学习资料@

* [SwiftGuide](https://github.com/ipader/SwiftGuide) 很赞 的Swift学习资料

## 完整App@
* [V2ex-Swift](https://github.com/Finb/V2ex-Swift) - 用 Swift 写的 V2EX 客户端。
* [iBBS-Swift](https://github.com/iAugux/iBBS-Swift) - “新手开源一个用Swift（2.0）写的论坛客户端”。[BBS 服务端](http://obbs.sinaapp.com/)。
* [NirZhihuDaily2.0_swift](https://github.com/zpz1237/NirZhihuDaily2.0) - 精仿了知乎日报iOS端练手，Swift2.0，注释相当详细。
* [DesignerNewsApp](https://github.com/MengTo/DesignerNewsApp) - Swift 开发的 DesignerNews 客户端，看着美美的！
* [Eidolon](https://github.com/artsy/eidolon) - 艺术品拍卖的投标亭平台，用swift与反应式编程框架 ReactiveCocoa。
* [BaiduFM-Swift](https://github.com/belm/BaiduFM-Swift) - 百度FM, swift语言实现，基于最新xcode6.3+swift1.2,初步只是为了实现功能，代码比较粗燥，后面有时间会整理，支持Apple Watch。
* [Tuan](https://github.com/aiqiuqiu/Tuan) - 模仿MJ老师iPad版美团（swift版），偶有bug 见谅。
* [CocoaChinaPlus](https://github.com/zixun/CocoaChinaPlus) - CocoaChina+是一款开源的第三方CocoaChina移动端。整个App都用Swift2.0编写(除部分第三方OC代码外，比如JPush和友盟)。
* [SimpleMemo](https://github.com/likumb/SimpleMemo) - 易便签已经转到Swift2.0，全面适配iOS9和Watch OS2，并支持iPhone6s和iPhone6sPlus的3D Touch功能，包括图标快捷键和内容预览。
* [furni-ios.swift](https://github.com/twitterdev/furni-ios) - furni-ios.swift是由 Twitter 开发团队出品的一款用 Swift 写的 iOS 家居商城应用, 其主要目的在于让开发者从这款 Demo 应用中看出 Fabric 的强大。
* [SelectionOfZhihu.swift](https://github.com/sheepy1/SelectionOfZhihu) - 『看知乎』iOS 客户端, [项目说明](http://www.jianshu.com/p/2c3a0f109788)。
* [Yep.swift](https://github.com/CatchChat/Yep) - Yep 一个由天才开发给天才们使用的社交软件。
* [LoveFreshBeen.swift](https://github.com/ZhongTaoTian/LoveFreshBeen) - 高仿爱鲜蜂 - Swift2.0
* [trySwiftApp.swift](https://github.com/ZhongTaoTian/LoveFreshBeen) - trySwiftApp一款较为完整的会议原型应用。有需求的同学可以做为开发参考。
* [PinGo.swift](https://github.com/gaowanli/PinGo) - PinGo.swift：纯Swift编写的仿“随遇”App。
* [UmbrellaWeather.swift](https://github.com/ZeroJian/UmbrellaWeather) - UmbrellaWeather.swift使用 Swift 编写的一款天气应用,现已上架 AppStore。
* [SwiftWeather](https://github.com/JakeLin/SwiftWeather) - SwiftWeather清新淡雅持续改进天气预报项目。
* [Phonetic.swift](https://github.com/iAugux/Phonetic) - Phonetic一个 iOS 版的 Phonetic Contacts，功能很多，其中昵称功能非常实用，已在 GitHub 开源并上架 App Store。
* [edhita.swift](https://github.com/tnantoka/edhita) - edhita.swift支持Markdown, HTML预览的文本编辑器。
* [PilesSugar.swift](https://github.com/cornerAnt/PilesSugar) - PilesSugar.swift:Swift高仿项目,堆糖。
* [react-native-gitfeed](https://github.com/xiekw2010/react-native-gitfeed) - 目前最实用简洁的github客户端了。
* [SoundCloudSwift](https://github.com/pepibumur/SoundCloudSwift) - SoundCloud的Swift版本，采用Swift2.0，Reactive API with ReactiveCocoa 4.0。
* [LeagueofLegends](https://github.com/HarrisHan/LeagueofLegends) - 一个关于英雄联盟的完整iOS开源项目，接口均来自多玩，腾讯各大游戏平台。
* [Coderpursue.swift](https://github.com/wenghengcong/Coderpursue) - 一款 Github 第三方客户端，使用最新 Swift 语言编写。
* [BTApp](https://github.com/Ryan0520/BTApp) - BTApp 仿半糖 iOS App 的 Demo 应用。
* [LXFFM](https://github.com/LinXunFeng/LXFFM) 高仿喜马拉雅FM

## Xcode8插件@

* [FileExplorer](https://github.com/Augustyniak/FileExplorer) 完整的文件资源管理器组件.

## App框架@

* [katana-swift](https://github.com/BendingSpoons/katana-swift) - Swift Apps in a Swoosh! A modern framework for creating iOS apps, inspired by React and Redux. http://katana.bendingspoons.com

#### 响应式框架
* [RxSwift](https://github.com/ReactiveX/RxSwift) - RxSwift:函数响应式编程框架。
* [RxPermission.swift](https://github.com/sunshinejr/RxPermission) - 通过绑定 RxSwift 实现的 RxPermission。
* [Permission.swift](https://github.com/delba/Permission) - 统一的 API 请求 iOS 本地设备及资源权限类库。
* [ReactiveAnimation](https://github.com/ReactiveCocoa/ReactiveAnimation) - ReactiveCocoa 推出了一个叫 ReactiveAnimation 的子项目，直接用完全用 Swift 来实现了。
* [Swiftest](https://github.com/bppr/Swiftest) - BDD 全称 Behavior Driven Development，行为驱动开发。各种 DD 数不胜数，孰优孰劣争论不休，其实归根结底还是要根据使用场景进行选择。

## UI@

#### 日历@

* [FSCalendar](https://github.com/WenchaoD/FSCalendar) - 一个包含objective-c和Swift版本的优秀的日历
* [FSCalendar](https://github.com/WenchaoD/FSCalendar) 一款漂亮，强大的 iOS 日历组件 A fully customizable iOS calendar library, compatible with Objective-C and Swift

#### 下拉刷新@

* [ZLSwiftRefresh](https://github.com/MakeZL/ZLSwiftRefresh) - swift下拉刷新/上拉加载更多，支持自定义动画，集成简单，兼容UITableView/CollectionView/ScrollView/WebView。
* [BreakOutToRefresh](https://github.com/dasdom/BreakOutToRefresh) - swift，上拉和下拉刷新。
* [GearRefreshControl](https://github.com/andreamazz/GearRefreshControl) -  swift，上拉和下拉刷新。
* [refresher](https://github.com/jcavar/refresher) -  swift，上拉和下拉刷新。
* [ReplaceAnimation.swift](https://github.com/fruitcoder/ReplaceAnimation) - 基于 @ZeeYoung欧阳哲 同学的创意下拉刷新动画实现。值得称赞还有额外增加了“取消及滚动”效果支持。
* [PullToReflesh-Swift](https://github.com/cbangchen/PullToReflesh-Swift) - 一款炫酷的下拉刷新封装库（Mobile page refresh concept inspired by Google and for something like a news app）。[源码分析 ](http://cbang.info/2016/03/04/CBReflesh%EF%BC%9A%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90/)
* [pull-to-refresh.swift](https://github.com/eggswift/pull-to-refresh) - 是一款非常易于开发者使用的下拉刷新和加载更多组件。通过一个 UIScrollView 的扩展，可以轻松为 UIScrollView 的所有子类添加下拉刷新功能。

#### 模糊效果@

* [Blurable.swift](https://github.com/FlexMonkey/Blurable) - swift模糊组件。

#### 富文本@

* [RichEditorView](https://github.com/cjwirth/RichEditorView) - swift，一套可定制富文本编辑器组件及示例。功能完整、代码简练、实现逻辑巧妙（编辑器核心与 WebView 结合，采用 HTML5 contentEditable 编辑模式，执行JS 配套命令 execCommand 实现富文本编辑功能）。
* [SwiftyMarkdown.swift](https://github.com/SimonFairbairn/SwiftyMarkdown) - 用swift写的markdown解析库。
* [Marklight.swift](https://github.com/macteo/Marklight) - Markdown 语法高亮显示编辑库（Swift）。
* [LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel) - swift 能够实现文字变形动画效果的Label，用Swift写的一个能够实现文字变形动画效果的Label，很炫。
* [Splitflap.swift](https://github.com/yannickl/Splitflap) - 可用于快速给 iOS 应用创建文字翻转的动画效果。
* [FloatLabelFields.swift](https://github.com/FahimF/FloatLabelFields) - FloatLabelFields.swift浮动标签输入效果类。
* [cleartext-mac.swift](https://github.com/mortenjust/cleartext-mac) - 提供一千个常用单词的编辑器。
* [GlitchLabel.swift](https://github.com/kciter/GlitchLabel) - 可定制“黑（故障）文字标签”类库，熟称晃瞎你的眼文字标签。

#### 颜色@

#### 图表@
* [swift-linechart](https://github.com/zemirco/swift-linechart) - 功能完整、实用的折线图组件。使用方便，参数配置简单。是不可多得的优质组件--swift。
* [ios-charts](https://github.com/danielgindi/Charts) - 一款优秀 Android 图表开源库 MPAndroidChart 的 Swift 语言实现版（支持 Objective-C 和 Swift 调用）。缺省提供的示例代码为 Objective-C。
* [Scrollable-GraphView.swift](https://github.com/philackm/Scrollable-GraphView) - 灵动感十足的自适应、可定制滚动曲（折）线图表库。

#### 表相关(TabbleView、Tabbar、即时聊天界面)@

* [Eureka.swift](https://github.com/xmartlabs/Eureka) - Eureka 是 XLForm 的 Swift 的移植版本, 一个可以帮助开发者们快速构建 iOS 各种复杂表单的库, 具有较高的可扩展性, 方便自定制样式。
* [HBHorizontalTableView](https://github.com/izyhuang/HBHorizontalTableView) - swift，TableView 横向滚动小示例（仿照 AppStore 应用展示）。
* [Chats](https://github.com/acani/Chats) - 聊天 UI 示例程序。此项目应该只为演示或学习之用，没有服务器 -- swift。
* [Chatto.swift](https://github.com/badoo/Chatto) - Chatto.swift:轻量级聊天应用框架及示例。文字及图片可扩展输入栏，汽泡效果等聊天核心特性，分页及自动布局完善。
* [COBezierTableView](https://github.com/knutigro/COBezierTableView) - swift，通过编辑 Bezier 曲线四点位置设置 TableView 内 Cell 及对应按扭位置。实验效果很赞。
* [LxTabBarController](https://github.com/DeveloperLx/LxTabBarController) - 改变了原生tabbar切换tab时的生硬效果，并加入滑动切换手势（有和界面上的其它手势发生冲突的风险，可根据具体项目予以关闭），[swift版本](https://github.com/DeveloperLx/LxTabBarController-swift)。
* [Sapporo](https://github.com/nghialv/Sapporo) - swift 单元格模型驱动的集合视图管理器组件。又一个超实用的“轮子”。
* [NavTopImage.swift](https://github.com/itjhDev/NavTopImage) - NavigationController动态缩放titleView。
* [paper-onboarding.swift](https://github.com/Ramotion/paper-onboarding) - 漂亮的 material design 风格页面滑块。示例完整，易用。
* [Material.swift](https://github.com/CosmicMind/Material) - 基于 Material Design 动画和图像框架库 （作者 Daniel Dahan）。
* [ReorderableGridView-Swift](https://github.com/cemolcay/ReorderableGridView-Swift) - 拖拽排序卡片。
* [ZYThumbnailTableView.swift](https://github.com/liuzhiyi1992/ZYThumbnailTableView) - 可展开型预览TableView，开放接口，完全自由定制。[实现教程](http://zyden.vicp.cc/zythumbnailtableview/)
* [WHC_CollectionViewFramework.swift](https://github.com/netyouli/WHC_CollectionViewFramework) - 高仿支付宝可拖拽排序编辑动画效果cell的CollectionView集合视图。
* [SwipeViewController.swift](https://github.com/fortmarek/SwipeViewController) - 一款好用的页面滑动和标签选项卡类库及示例。功能相当于 Objective-C 版 RKSwipeBetweenViewControllers。
* [TabDrawer.swift](https://github.com/winslowdibona/TabDrawer) - 更适合单手操作的可定制 Tab Bar 组件库。P.S. 自动布局选择了 EasyPeasy。
* [SFFocusViewLayout.swift](https://github.com/fdzsergio/SFFocusViewLayout) - UICollectionViewLayout实现的图片浏览器。
* [ESTabBarController.swift](https://github.com/eggswift/ESTabBarController) - 自定义TabBarController组件，继承自UITabBarControlle，可添加动画和自定义样式。[swift 高度自定义TabBarController，支持自定义TabBarItem样式或添加动画](http://www.jianshu.com/p/9e52630e7368)

#### 隐藏与显示@

#### HUD与Toast@
* [Toast-Swift](https://github.com/scalessec/Toast-Swift) - 高可定制易用的 Toast 弹出信息或通知用户界面组件类。

#### 对话框@
* [SwiftyDrop](https://github.com/morizotter/SwiftyDrop) - 轻量、易用的小清新弹出列表及信息提示组件真心不错。
* [PCLBlurEffectAlert.swift](https://github.com/hryk224/PCLBlurEffectAlert) - 细节定制较丰富的弹出警报窗口组件。
* [GSAlert.swftt](https://github.com/wxxsw/GSAlert) - 苹果在iOS8推出了全新的UIAlertController，旧的UIAlertView和UIActionSheet渐渐被废弃，但如果你仍然支持iOS7系统，你将不得不写两套代码。GSAlert解决了这个问题。
* [TKSwarmAlert.swift](https://github.com/entotsu/TKSwarmAlert) - TKSwarmAlert.swift:模仿 Swarm app 的 Alert 提醒框动画工具。
* [PMAlertController.Swift](https://github.com/Codeido/PMAlertController) - 可定制弹窗组件替代官版不可定制的 UIAlertController。
* [TBActionSheet.swift](https://github.com/yulingtianxia/TBActionSheet) - 支持Carthage，可自定义度100%的 ActionSheet，支持微信样式。
* [NoticeBar](https://github.com/qiuncheng/NoticeBar)Notice View相关的简易库，叫做NoticeBar, 在NavigationBar、Tabbar、statusBar上显示提示信息，信息可包含文字和图片等，并且内置了四种提示消息。

#### 状态栏@

#### 导航栏@

* [Tiptoes](https://github.com/caiyue1993/Tiptoes) 提供了一种自定义 Navigation Bar 的新思路，并实现了转场渐变效果，灵感来自于 Unread 。

#### 设置@

#### Switch@

#### Label@

* [LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel) 炫酷的Label效果 Graceful morphing effects for UILabel written in Swift.

#### 主题@

#### 电影选座@

#### 瀑布流@

#### 菜单@

* [Swift-CircleMenu](https://github.com/Sufi-Al-Hussaini/Swift-CircleMenu) Swift-CircleMenu：一款圆盘式菜单,Rotating circle menu written in Swift 3

#### TabBar@

* [CBMDTabbarController](https://github.com/cbangchen/CBMDTabbarController) It is a smooth MD tabbarController used on iOS, which implement by Swift.

## 进度@

* [KYCircularProgress](https://github.com/kentya6/KYCircularProgress) - 简单、实用路径可定进程条。

## 引导页@

* [MZGuidePages](https://github.com/MachelleZhang/MZGuidePages) - 自己写的通用导航页，可以直接引入工程使用，请参考案例（版本新特性、导航页、引导页）。
* [Intro](https://github.com/nbolatov/Intro)简单的功能引导组件
* [Wizardry.swift](https://github.com/ijoshsmith/Wizardry) - 可重用的方法和框架实现向导式用户界面管理。（版本新特性、导航页、引导页）。

## page@

* [XLPagerTabStrip](https://github.com/xmartlabs/XLPagerTabStrip) - 非常赞 的iOS下的PagerTabStrip。
* [PinterestSegment](https://github.com/TBXark/PinterestSegment) 仿 Pinterest 的 Segment 控件(swift), 行数 200+

## 评分@

* [iOS-RatingBar](https://github.com/saiwu-bigkoo/iOS-RatingBar) - iOS-RatingBar swift版的评分控件,跟Android的RatingBar一样有两种模式，评分模式和只读模式'支持视图编辑，自定义星星数量，评分等级,另外还能支持非整数星，0.5颗星，0.1颗星,可以开启动画效果。
* [SwiftyStarRatingView](https://github.com/Jerrrr/SwiftyStarRatingView) SwiftyStarRatingView 是一个用 swift 3.0 编写的评分控件，可以支持自定义图片和颜色，并且可以支持在XIB、StoreBoard中使用，并支持AutoLayout。

#### 其他UI@
* [KDCircularProgress](https://github.com/kaandedeoglu/KDCircularProgress) -  KDCircularProgress是使用swift制作的色彩炫丽的进度条，可以加入多种颜色来控制进度条的渐变效果。
* [RandomColorSwift](https://github.com/onevcat/RandomColorSwift) - 一个自动生成好看的颜色的 Swift 库，RandomColorSwift。
* [Hue.Swift](https://github.com/hyperoslo/Hue) - Hue.Swift：颜色常规功能集于一身的定义、使用 Color 工具类库（含图片取色）。
* [KtColor.swift](https://github.com/bestswifter/MySampleCode/tree/master/KtColor) - 利用 Swift 的语法特性简化创建 UIColor对象的过程。具体文章可以参考博客：[当UIColor遇上 Swift](http://www.jianshu.com/p/f2173235cde8)。
* [YPDropMenuViewDemo.swift](https://github.com/MakeBetterMe/YPDropMenuViewDemo) - 一款DropMenu,menuView,类似之前美团的下拉菜单，支持swift2.2，因为用到iOS8.的毛玻璃。所以想支持到iOS8.0,支持自定义，支持等宽排列，支持从左向右排列。
* [ZMaterialDesignUIButton](https://github.com/richzertuche/ZMaterialDesignUIButton) - Swift Material Design UIButton。
* [Twinkle](https://github.com/piemonte/Twinkle) - 为字体加上钻石版闪耀的效果。使用Swift编写。
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

## 多线程@

* [Overdrive](https://github.com/arikis/Overdrive)专注于类型安全、并发和多线程的，快速 、专业的异步任务库 Fast async task based Swift framework with focus on type safety, concurrency and multi threading
* [Jobs](https://github.com/BrettRToomey/Jobs)Swift Job 队列

## 游戏@

## 动画@

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
* [popping](https://github.com/schneiderandre/popping) - popping是一个POP 使用实例工程
* [PopMenu](https://github.com/xhzengAIB/PopMenu) - 用POP动画引擎写的Sina微博的Menu菜单。
* [Spring](https://github.com/MengTo/Spring) - Spring是一个Swift编写的开源库，可简化Swift编写的iOS动画。支持shake、pop、morph、squeeze、wobble、swing、flipX、flipY、fall、squeezeLeft、squeezeRight以及squeezeDown等多种动画形式，用 IBDesignable 让使用者可以在 Xcode 中快速设置动画效果。
* [JGTransitionCollectionView](https://github.com/JayGajjar/JGTransitionCollectionView) - swift，基于集合视图扩展实现完成自动布局及单元项 Flip式动画效果（效果很赞）。组件使用方便、自然（只需设置集合视图数据源的标准方式即可）。
* [KYShareMenu](https://github.com/KittenYang/KYShareMenu) - 带弹性动画的分享菜单。
* [BuildAnInfiniteCarousel](https://github.com/johnlui/Swift-On-iOS/tree/master/BuildAnInfiniteCarousel) - 自己动手造无限循环图片轮播，[教程](https://autolayout.club/2015/10/29/%E8%87%AA%E5%B7%B1%E5%8A%A8%E6%89%8B%E9%80%A0%E6%97%A0%E9%99%90%E5%BE%AA%E7%8E%AF%E5%9B%BE%E7%89%87%E8%BD%AE%E6%92%AD/)。
* [tispr-card-stack](https://github.com/tispr/tispr-card-stack) - swift 卡片风格动画切换组件及完整交互示例。
* [ZLSwipeableViewSwift](https://github.com/zhxnlai/ZLSwipeableViewSwift) - swift 卡片堆叠效果的实现（ZLSwipeableView)】可实现类似Tinder和Potluck应用程序的卡片堆叠效果，该项目基于[ZLSwipeableView objective-c](https://github.com/zhxnlai/ZLSwipeableView/)实现。1.自定义动画。2.自定义滑动切换。3.自定义方向。4.撤销。
* [Koloda](https://github.com/Yalantis/Koloda) - 基于卡片的 Tinder-style 动画效果示例。精细绝人。更赞的是额外附了详细开发教程 How We Built Tinder-Like Koloda Animation in Swift [网页链接](https://yalantis.com/blog/how-we-built-tinder-like-koloda-in-swift/) 。Yalantis 出品动画程序款款精品。
* [KDIntroView](https://github.com/likedan/KDIntroView) - swift 动态介绍视图框架及演示。另外两个相似的类库是 RazzleDazzle和 Presentation，择需使用。
* [RazzleDazzle](https://github.com/IFTTT/RazzleDazzle) - 【IFTTT开源Swift编写的帧动画框架--RazzleDazzle】RazzleDazzle 是IFTTT开源的一个iOS帧动画框架，非常适用于APP初次使用时的介绍和引导信息。JazzHands是UIKit一个简单的关键帧基础动画框架，可通过手势、scrollview、KVO等控制动画，被IFTTT应用在IFTTT for iPhone上。
* [SIFloatingCollection_Swift](https://github.com/ProudOfZiggy/SIFloatingCollection_Swift) - 可定制的 Apple Music 风格浮动形状动画组件及演示。
* [CKWaveCollectionViewTransition](https://github.com/CezaryKopacz/CKWaveCollectionViewTransition) - swift， UICollectionViewController之间切换的动画。
* [CardsAnimationDemo](https://github.com/adow/CardsAnimationDemo) - swift， [《使用 UICollectionView 实现的一个卡片动画》](http://swiftcn.io/topics/64?f=w)不是直接操作所有 UIView 和 CALayer 的 transform3D 属性来实现整个效果的，而是使用 UICollectionView 来完成所有的视图管理和实现。
* [TKRubberIndicator.swift](https://github.com/TBXark/TKRubberIndicator) - 一个很不错的 page control。
* [TTGEmojiRate.swift](https://github.com/zekunyan/TTGEmojiRate) - TTGEmojiRate.swift以Emoji表情为基础绘图，[Swift开源项目: TTGEmojiRate的实现](http://tutuge.me/2015/10/25/ttgemojirate-lib/)。
* [CardAnimation.swift](https://github.com/seedante/CardAnimation) - CardAnimation 是国人开发的一个用 Swift 实现卡片垂直翻转动画的 Demo, [实现思路](http://www.jianshu.com/p/286222d4edf8)。
* [CoreAnimationCode.swift](https://github.com/lzwjava/CoreAnimationCode) - 提供了 "iOS Core Animation Advanced Techniques" 书籍中的代码实例, 方便开发者们进行参考学习。
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

## AutoLayout@
* [Snap](https://github.com/SnapKit/SnapKit) - Snap是Masonry Auto Layout DSL的Swift版本，是一款轻量级的布局框架，使用了更良好的语法封装了AutoLayout。Snap支持iOS和OS X。
* [Neon.swift](https://github.com/mamaral/Neon) - 功能强大的 UI 布局神器。
* [EasyPeasy.swift](https://github.com/nakiostudio/EasyPeasy) - 编程方式自动布局框架库。
* [TangramKit](https://github.com/youngsoft/TangramKit) TangramKit is a powerful iOS UI framework implemented by Swift. It integrates the functions with Android layout,iOS AutoLayout,SizeClass, HTML CSS float and flexbox and bootstrap. So you can use LinearLayout,RelativeLayout,FrameLayout,TableLayout,FlowLayout,FloatLayout,LayoutSizeClass to build your App 自动布局 UIView UITableView UICollectionView

## 网络相关@

#### 网络连接@
* [Alamofire](https://github.com/Alamofire/Alamofire) - Alamofire是AFNetworking的作者mattt新写的网络请求的swift库。[Alamofire 最佳实践](https://github.com/ipader/SwiftGuide/wiki/Alamofire%20%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5)
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
* [Moya](https://github.com/Moya/Moya) - 对Alamofire的封装，使用枚举将网络层实现细节与页面逻辑代码分离，方便单元测试，支持stub测试，配合RxSwift食用更佳，[博客教程](http://www.hmttommy.com/2015/12/15/Moya/)

#### 图像获取@
* [Kingfisher](https://github.com/onevcat/Kingfisher) - 非常👍 纯 Swift 实现的类 SDWebImage 库，实现了异步下载和缓存图片。
* [KFSwiftImageLoader](https://github.com/kiavashfaisali/KFSwiftImageLoader) - Swift，一个图像缓存加载库。

#### 网络聊天@
* [MessageKit.swift](https://github.com/MessageKit/MessageKit) - 消息 UI 库 JSQMessagesViewController 的 Swift 版。
* [jchat-swift](https://github.com/jpush/jchat-swift) - 一个聊天 App,具有完备的即时通讯功能,JChat 的功能基于极光 JMessage SDK 来开发。

#### 网络测试@
* [Reachability.swift](https://github.com/ashleymills/Reachability.swift) - 用于替换苹果的 Reachability 类，可以方便地检测当前是否联网以及具体的联网状态。
* [NetReachability](https://github.com/crazypoo/SimpleCarrie) - swift2.0 简单的方法检查网络连接的连通性，提供通知中心集成接口。
* [SimpleBS.swift](https://github.com/bin1991/SimpleBS) - 网络测试小工具。


#### 网页框架@
* [Perfect.swift](https://github.com/PerfectlySoft/Perfect) - Perfect 致力于 Swift 服务端应用，从打造专业应用服务器开始。[Swift服务端编程：Perfect项目上手指南](http://blog.csdn.net/kinfey/article/details/50644752)
* [swift-http](https://github.com/huytd/swift-http) - Swift HTTP Server，又一个 Swift 服务器，最大的亮点是支持 Docker 部署。
* [Swifton](https://github.com/necolt/Swifton) - Swifton是一个优秀的Swift on Rails 的Web Framework。
* [Taylor.swift](https://github.com/izqui/Taylor) - Taylor一个swift的轻量级的http服务器的库。
* [NetworkObjects.swift](https://github.com/colemancda/NetworkObjects) - NetworkObjects.swift轻量版HttpServer框架，跨平台解决方案。
* [vapor.swift](https://github.com/qutheory/vapor) - vapor.swift：swift的服务器库 vapor。
* [Kitura.swift](https://github.com/IBM-Swift/Kitura) - Kitura.swift：安装、使用步骤及文档最为清晰地来自 IBM Swift 开发组的开源 Web 服务器。此外，IBM 云服务 Bluemix 也为 Swift 打开通路。

#### 网络解析@

##### CSV@
* [CSwiftV](https://github.com/Daniel1of1/CSwiftV) - A csv parser written in swift conforming to rfc4180 :large_orange_diamond:
* [SwiftCSV](https://github.com/naoty/SwiftCSV) - CSV parser for Swift :large_orange_diamond:

##### Json@
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with JSON data in Swift. :large_orange_diamond:
* [ObjectMapper](https://github.com/Hearst-DD/ObjectMapper) - 很赞 ObjectMapper 是一个基于 Swift 语言开发的能够让 JSON 与 Object 之间轻易转换的类库。通过 ObjectMapper 我们可以将 JSON 数据转换成 Model 对象或将 Model 对象转换成 JSON 数据。 Simple JSON Object mapping written in Swift
* [Decodable](https://github.com/Anviking/Decodable) - Swift 2 JSON parsing done (more) right :large_orange_diamond:
* [Jay](https://github.com/czechboy0/Jay) - Pure-Swift JSON parser & formatter. Linux & OS X ready. :large_orange_diamond:
* [XMLDictionary](https://github.com/nicklockwood/XMLDictionary) - ios与mac os平台下xml与NSDictionary相互转化开源类库。
* [AEXML.swift](https://github.com/tadija/AEXML) - AEXML.swift简单又易于的XML解析类及示例。
* [CFRuntime](https://github.com/CoderMJLee/MJExtension) - “Swift 版的 MJExtension，运行时、反射与一键字典模型互转”。
* [protobuf-swift](https://github.com/alexeyxo/protobuf-swift) - Protocol Buffers 的 Swift 语言实现库。P.S. Protocol Buffers 是 Google 开源项目，主要功能是实现直接序列化结构化的对象数据，方便跨平台快速传递，开发者也可以直接修改 protobuf 中的数据。相比 XML 和 JSON，protobuf 解析更快，存储更小。
* [JSONCodable](https://github.com/matthewcheok/JSONCodable) - 基于 Swift 2.0 新特性（Protocol Extensions and Error Handling）的JSON 解析类。
* [JSONNeverDie.swift](https://github.com/johnlui/JSONNeverDie) - JSON 到 Model 类的自动映射工具。
* [Fuzi.swift](https://github.com/cezheng/Fuzi) - Swift实现的轻量快速的 XML/HTML 解析器。
* [SWXMLHash.swift](https://github.com/drmohundro/SWXMLHash) - 易用的 XML 解析类库。非常实用的“轮子”。
* [YYModel](https://github.com/ibireme/YYModel) - 高性能的 iOS JSON 模型框架。
* [TidyJSON.swift](https://github.com/benloong/TidyJSON) - TidyJSON.swift一款简单、易用、明了的 JSON 解析小类库。
* [PMJSON.swift](https://github.com/postmates/PMJSON) - PMJSON.swift简单、实用、高效的 JSON 解析类库。
* [Unbox.swift](https://github.com/JohnSundell/Unbox) - 极为易用、轻量，更少辅助代码的 JSON 解析类。
* [Wrap.swift](https://github.com/JohnSundell/Wrap) - 方便、易用的对象转 JSON 类库。
* [JASON](https://github.com/delba/JASON) - 高效的Json解析（Swift） Fast JSON parsing for Swift
* [JSONCodable](https://github.com/matthewcheok/JSONCodable) - Swift json编码解码三方库 Hassle-free JSON encoding and decoding in Swift
* [Coolie](https://github.com/nixzhu/Coolie) - Swift json转model的三方库 Coolie helps you to create models (& their constructors) from JSON file.
* [Tailor](https://github.com/zenangst/Tailor) - 一个非常快和方便的对象映射Swift三方库 A super fast & convenient object mapper tailored for your needs.
* [alexander](https://github.com/hodinkee/alexander) - 一个非常简洁的json处理三方库 An extremely simple JSON helper written in Swift.
* [Freddy](https://github.com/bignerdranch/Freddy) - 一个可以重用的json解析库 A reusable framework for parsing JSON in Swift.
* [mapper](https://github.com/lyft/mapper) - 一个json反序列化库 A JSON deserialization library for Swift
* [AlamofireJsonToObjects](https://github.com/evermeer/AlamofireJsonToObjects) - 一个将json data转为Swift对象的类扩展 An Alamofire extension which converts JSON response data into swift objects using EVReflection
* [Alembic](https://github.com/ra1028/Alembic) - 功能性的json解析库 Functional JSON parsing, mapping to objects, and serialize to JSON :large_orange_diamond:
* [Wrap](https://github.com/JohnSundell/Wrap) - The easy to use Swift JSON encoder :large_orange_diamond:
* [Arrow](https://github.com/freshOS/Arrow) - 一个Swift JSON解析库 JSON Parsing Library for Swift
* [Genome](https://github.com/LoganWright/Genome) - 一个易用、多样、安全，包含错误映射的JSON转Model的Swift库. A simple, type safe, failure driven mapping library for serializing JSON to models in Swift 2.0 (Supports Linux)

##### XML&HTML@
##### Other Parsing@

## 二维码@

* [LBXScan](https://github.com/MxABC/LBXScan) 赞 A barcode and qr code scanner (二维码、扫码、扫一扫、ZXing和ios系统自带扫码封装，扫码界面效果封装)(Objective-C和Swift均支持).
## VR@

* [VRDemo-Swift](https://github.com/Huanhoo/VRDemo-Swift) VRDemo是用Swift配合OpenGL ES实现的360度全景播放器

## 开发资料@

#### 播客@
#### 学习资料@

* [SwiftGuide](https://github.com/ipader/SwiftGuide) 非常赞 这份指南汇集了Swift语言主流学习资源，并以开发者的视角整理编排。http://dev.swiftguide.cn
* [the-swift-programming-language-in-chinese](https://github.com/numbbbbb/the-swift-programming-language-in-chinese) 非常赞  中文版 Apple 官方 Swift 教程《The Swift Programming Language》
* [iOS-Swift-Demos](https://github.com/Lax/iOS-Swift-Demos) 精心收集并分类整理的Swift开发学习资源，包括Apple官方提供的示例代码和文档，以及github上的项目和国内外开发者的技术博客。欢迎提交pull-request一起维护。[iOS Swift Demos from Apple] http://blog.liulantao.com/SwiftBeginnersGuide/
* [Swift 开源项目精选－v1.0](http://dev.swiftguide.cn/archive/featured-open-source-projects-in-swift_v1.0.html) - Swift 开源项目精选－v1.0。
* [Swift开源项目精选](https://github.com/ipader/SwiftGuide/blob/master/Featured.md) - Swift开源项目精选--推荐，每周都有更新。
* [Swift中文指南](https://github.com/numbbbbb/the-swift-programming-language-in-chinese) - 中文版Apple官方Swift教程《The Swift Programming Language》，[老码版本](https://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/)  [历史版本更新说明](https://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/chapter1/03_revision_history.html)。
* [The Swift Programming Language 中文版](http://wiki.jikexueyuan.com/project/swift/) - The Swift Programming Language 中文版。
* [swifttoolbox](http://www.swifttoolbox.io/) -  swifttoolbox swift开发的开源库汇总。
* [SwiftGuide](https://github.com/ipader/SwiftGuide) -  这份指南汇集了Swift语言主流学习资源，并以开发者的视角整理编排-- 非常不错，值得推荐。
* [Awesome Swift](https://swift.zeef.com/robin.eggenkamp) - 一个收集了很多 Swift 开发资源的网站。
* [Developing_iOS_8_Apps_With_Swift](https://github.com/CS193P-Translation-Group/Developing_iOS_8_Apps_With_Swift) - Developing iOS 8 Apps with Swift 字幕简体中文翻译项目（斯坦福白胡子老头swift教学视频）。
* [Swift-On-iOS](https://github.com/johnlui/Swift-On-iOS) - JohnLui 的 Swift On iOS 代码仓库。
* [30DaysofSwift](https://github.com/allenwong/30DaysofSwiftp) - 30DaysofSwift 自学 iOS - [三十天三十个 Swift 项目](http://weibo.com/ttarticle/p/show?id=2309403942494873235448)。

#### 他人开源总结@

* [awesome-swift](https://github.com/matteocrippa/awesome-swift) - A collaborative list of awesome swift resources. Feel free to contribute!
* [awesome-swift](https://github.com/Wolg/awesome-swift) - A curated list of awesome Swift frameworks, libraries and software.
* [SwiftMarch](https://github.com/SwiftOldDriver/SwiftMarch) - 从开发者角度介绍被广泛运用于实际Swift项目中的开源库。

#### 开发博客列表@
#### 学习笔记、书籍@
#### 设计@
#### 好的文章@

* [RxSwift入坑手册](http://blog.callmewhy.com/2015/09/21/rxswift-getting-started-0/) - RxSwift入坑手册。
* [Xcode使用技巧](http://www.jianshu.com/p/cda4b0fe07e0) - SwiftGG 交流分享：Xcode使用技巧。
* [Swift编程的15个技巧](http://geek.csdn.net/news/detail/58593) - Swift编程的15个技巧。


#### 美工资源@

## 开发工具@
#### Xcode插件@

* [Swimat](https://github.com/Jintin/Swimat) - Swimat，是一款Xcode 插件，帮你一键格式化 swift 代码。
* [XcodeSwiftSnippets](https://github.com/burczyk/XcodeSwiftSnippets) - XcodeSwiftSnippets, 提供了很多可在 Xcode 上使用的 Swift 代码片段, 通过自动补全的方式极大的提高了开发效率。


#### 好用的软件@
#### Cagegory@

## 测试及调试@
* [depcheck](https://github.com/wojteklu/depcheck) Swift 工程分析工具(Dependency analyzer tool for Swift projects)
* [CleanroomLogger](https://github.com/emaloney/CleanroomLogger) - 相当于 CocoaLumberjack 或 Log4j 的 Swift 版本，功能上甚至更强大。另外，源代码中已经内含了完整的 API 文档，使用非常方便。
* [Quick](https://github.com/Quick/Quick) - 用于Swift中的单元测试（也可用于Objective-C），与Xcode整合在一起。如果你是Objective-C的粉丝，我建议用Specta代替这个，但是对Swift使用者来说，Quick是最佳选择。
* [Sleipnir](https://github.com/railsware/Sleipnir) - Swift的测试框架。
* [XXPlaceHolder.swift](https://github.com/adad184/XXPlaceHolder) - MMPlaceHolder的swift版本。
* [SwiftyBeaver](https://github.com/SwiftyBeaver/SwiftyBeaver) - 一个完善的日志工具，支持彩色输出、输出内容到文件、重要性分级、多输出目标。工具执行在后台，不影响性能，可以极大提高开发效率。
* [swiftlog](https://github.com/iachievedit/swiftlog) - 为Swift 应用提供快捷添加日志信息的方法，Swift 包管理支持（SPM）、 使用惊艳的 Rainbow 包输出彩色日志、支持写入文件。[使用 swiftlog](https://segmentfault.com/a/1190000004512773)
* [Log.swift](https://github.com/delba/Log) - 灵活、易用、可定制输出格式和主题风格的日志类（Swift）,支持控制台彩色输出。
* [Cuckoo.swift](https://github.com/SwiftKit/Cuckoo) - Cuckoo.swift一款用法更接近于传统单元测试 Mock 框架库（区别之处在于需要用脚本预先生成 Mock 类）。
* [XCGLogger.swift](https://github.com/DaveWoodCom/XCGLogger) - XCGLogger.swift功能完整的日志管理类库。
* [Peek.swift](https://github.com/shaps80/Peek) - 更友好、手势方式检查界面内组件布局信息（相当于浏览器元素检查功能），界面调试利器。

## 数据存储@

#### 缓存处理@
* [Cache.swift](https://github.com/soffes/Cache) - 一款简单、易用的缓存库。支持 MemoryCache, DiskCache 以及前两项组合的 MultiCache。
* [Cache.swift](https://github.com/hyperoslo/Cache) - Nothing but Cache。
* [AwesomeCache.swift](https://github.com/aschuch/AwesomeCache) - Delightful on-disk cache (written in Swift)。
* [Track.swift](https://github.com/maquannene/Track) - 基于文件系统和链表的 Cache。分为 Disk 和 Memory，线程安全，支持 LRU 淘汰，性能尚可。

#### CoreData@

* [JSQCoreDataKit](https://github.com/jessesquires/JSQCoreDataKit) - A swifter Core Data stack :large_orange_diamond:

#### 数据库@
* [RealmIncrementalStore.swift](https://github.com/eure/RealmIncrementalStore) - RealmIncrementalStore.swift:集 Realm 数据库和 CoreData 对象模型两者优势的 Realm 数据库访问类库。
* [Breeze](https://github.com/andrelind/Breeze) - 用Swift写的一个轻量级的CoreData管理工具，并且还支持iCloud 。
* [AlecrimCoreData](https://github.com/Alecrim/AlecrimCoreData) - Swift，更容易地访问 CoreData 对象封装类库。除了 CRUD，还提供指针定位，强大的排序、筛选，异步数据获取，以及独立线程后台存取数据。
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift) - 纯swift实现的类型安全的SQLite3封装，数据存储和JSON解析是永恒的话题。
* [fluent.swift](https://github.com/qutheory/fluent) - 纯swift实现的类型安全的SQLite3封装，数据存储和JSON解析是永恒的话题。
* [swiftydb](http://www.appcoda.com/swiftydb/) - 是一个第三方 SQLite 工具，能够大大简化数据库操作。如果你不放心 Realm，那就用 SwiftyDB 吧。[使用教程](http://swift.gg/2016/05/17/swiftydb/)、[demo](https://github.com/appcoda/SwiftyDB-Demo)
* [Graph.swift](https://github.com/CosmicMind/Graph) - 设计新颖、使用简单基于 Core Data 的数据驱动框架库 （作者Daniel Dahan）。
* [SwiftStore](https://github.com/hemantasapkota/SwiftStore) - Key-Value store for Swift backed by LevelDB :large_orange_diamond:

#### 序列化@

## WebView与WKWebView@
* [IOSCallJsOrJsCallIOS](https://github.com/CoderJackyHuang/IOSCallJsOrJsCallIOS) - IOSCallJsOrJsCallIOS：利用iOS7.0后出来的JavaScriptCore framework，webview与Js交互是常见的需求。OC版本与swift版本。[《OC JavaScriptCore与js交互》](http://www.henishuo.com/oc-js/),[《Swift JavaScriptCore与js交互》](http://www.henishuo.com/swift-js/)。
* [WKWebViewTestDemo.swift](https://github.com/CoderJackyHuang/WKWebViewTestDemo) - WKWebViewTestDemo：WKWebView新特性及JS交互,[文章讲解](http://www.henishuo.com/wkwebview-js/)。
* [React.swift](https://github.com/alexdrone/Render) - 启发自 React 的纯 Swift 函数版基于 UIKit 封装类库。这种结构是否似曾相识。
* [GRMustache] (https://github.com/groue/GRMustache) 一个类似templateEngine的html渲染工具，可以更加有效的帮助大家完成数据生成HTML的过程。

## FaceBook@

## 通讯录@
* [PPGetAddressBookSwift](https://github.com/jkpang/PPGetAddressBookSwift) - 一行代码获取按A~Z分组精准排序的通讯录联系人 Swift版( 已处理姓名所有字符的排序问题)

## Email@
* [Postal](https://github.com/snipsco/Postal) A swift framework for working with emails,Postal is a swift framework providing simple access to common email providers.

## 三方分享、支付、登录等等@

## 其他库@
* [SwiftDate](https://github.com/malcommac/SwiftDate) - 特别完整、强大的日期时间操作管理类库。它几乎涵盖了已知开源日期类库所有优秀特性。 他能帮你轻松处理时区，处理时间加减，计算到期时间等等场景下的问题。
* [SYKeyboardTextField](https://github.com/yushuyi/SYKeyboardTextField) - SYKeyboardTextField 是一个轻巧,简单,非侵入式的键盘附随输入框! 采用Swift编写。
* [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager) - 处理键盘事件强大的库，有OC和Swift版本，纯代码、Storyboard和Xib都适用。
* [ZFScan](https://github.com/Zirkfied/ZFScan) - 仿微信 二维码/条形码 扫描。
* [QRCodeReader.swift](https://github.com/yannickl/QRCodeReader.swift) - QRCodeReader.swift一款简单的 QR 二维码阅读组件及示例，提供前后相机切换功能。
* [swiftScan](https://github.com/MxABC/swiftScan) - 具有丰富功能的二维码扫描组件及类库。[对应OC版本LBXScan](https://github.com/MxABC/LBXScan)。
* [QR-Code-Generator.swift](https://github.com/appcoda/QR-Code-Generator) - 生成二维码。
* [Parsimmon](https://github.com/ayanonagon/Parsimmon) - swift，小而美的语言学类库封装工具包。提供分词、标记词性、词形归并、朴素贝页斯分类、决策树等自然语言分析小工具。P.S. 英语分词效果好于中文，感兴趣的同学可以针对中文做一些优化开发。参考译文 NSHipster - [NSLinguistic​Tagger](http://nshipster.cn/nslinguistictagger/)。
* [MKMapView-Extension](https://github.com/SemperIdem/MKMapView-Extension) - 这是关于 MKMapView 写的一个基于swift的扩展，可以扩展 MKMapView 的相关功能，减少复用代码量。
* [SwiftValidator](https://github.com/jpotts18/SwiftValidator) - 基于规则的输入验证类库。项目良好的面向对象设计思想，使规则的扩展及自定义非常方便。更专业的规则引擎（甚至是基于自然语言的规则配置）解决方案，比如：开源的 Drools，商用的 ILOG 等。
* [Validated.swift](https://github.com/Ben-G/Validated) - Validated.swift通过值验证或限定，快速定义新类型的微类库（约50行代码）。
* [SwiftOCR](https://github.com/garnele007/SwiftOCR) - 识别字母和数字相较于 Tesseract 有压倒性优势（附图）的 OCR 类库。
* [Regex.swift](https://github.com/sharplet/Regex) - 实用的正则表达式微框架类库。
* [PySwiftyRegex.swift](https://github.com/cezheng/PySwiftyRegex) - 像Python一样简洁高效地作正则处理。
* [PhoneNumberKit.swift](https://github.com/marmelroy/PhoneNumberKit) -  解析、格式化及验证国际电话号码工具库（相当于 Google 的 libphonenumber 库的 Swift 版本）。
* [BFKit-Swift](https://github.com/FabrizioBrancati/BFKit-Swift) - BFKit-Swift 这套工具库可以提高应用开发效率。
* [SwiftSequence](https://github.com/oisdk/SwiftSequence) - 简洁、灵活、多变的操作 SequenceType 的类库（基于微框架（μframework）设计思想）。
* [IDNFeedParser](https://github.com/photondragon/IDNFeedParser) - 一个简单易用的Rss解析库。
* [Swifternalization](https://github.com/tomkowz/Swifternalization) - 一套实用的本地化工具库。使用教程及 API 文档完整。值得收入项目的“轮子”。
* [Localize-Swift](https://github.com/marmelroy/Localize-Swift) - Localize-Swift一款开发者不可或缺的国际化及本地化字符串框架支持类库。同样地，使用简单、直观又方便。
* [apous](https://github.com/owensd/apous) - 一款有趣的 Swift 应用 － 让 Swift 成为脚本语言。
* [ControlOrientation](https://github.com/johnlui/Swift-On-iOS/tree/master/ControlOrientation/ControlOrientation) - 如何用代码控制以不同屏幕方向打开新页面【iOS】， [使用说明](https://lvwenhan.com/ios/458.html)。
* [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit) - 一款轻量级的 iOS 应用内购买框架。
* [Device-swift](https://github.com/Ekhoo/Device) - 可以非常方便的获取设备型号和屏幕尺寸，实现起来难度不大，大家可以学习一下源码。
* [RunKit.swift](https://github.com/khoiln/RunKit) - 针对 GCD 框架的一个友好访问封装库（支持方法链式调用）。
* [Plum-O-Meter](https://github.com/FlexMonkey/Plum-O-Meter) - swift 称重应用， (3D Touch之我见)[http://swift.gg/2015/10/23/3d-touch-impressions-and-thoughts/]。
* [打开自带地图、百度地图、腾讯地图](http://code.cocoachina.com/view/128249) - 打开自带地图、百度地图、腾讯地图。
* [MapManager.swift](https://github.com/varshylmobile/MapManager) - MapManager.swift地图及路径管理封装库。
* [eviltransform.swift](https://github.com/googollee/eviltransform) - eviltransform.swift解决国内GPS地图坐标偏移问题,它将政府加密过的GCJ-02坐标，转成世界通用的WGS-84坐标。
* [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - 是一个非常容易使用的蓝牙库, 适用于 iOS 和 Mac OS, 基于原生 CoreBluetooth 框架封装, 可以帮开发者们更简单地使用 CoreBluetooth API, 使用链式方法体, 使得代码更简洁、优雅。[iOS蓝牙开发（四）：BabyBluetooth蓝牙库介绍](http://www.cocoachina.com/ios/20160219/15301.html)
* [RxBluetoothKit.swift](https://github.com/Polidea/RxBluetoothKit) - 基于 RxSwift 的蓝牙通讯库。
* [BluetoothKit.swift](https://github.com/rasmusth/BluetoothKit) - 基于 CoreBluetooth API 实现iOS/OS X 设备间蓝牙通讯封装类库。功能强大、传输稳定，示例完整，很酷。
* [CoreDataStack.swift](https://github.com/bignerdranch/CoreDataStack) - 存储栈。
* [SYNQueue.swift](https://github.com/THREDOpenSource/SYNQueue) - 执行队列类库。
* [DDMathParser.swift](https://github.com/davedelong/DDMathParser) - 相比 NSExpression 和 GCMathPaser，功能更强大的数学表达式解析器。
* [RateLimit.swift](https://github.com/soffes/RateLimit) - 简单、实用定时执行任务工具类库。
* [shoppingCart.swift](https://github.com/6ag/shoppingCart) - swift的购物车demo，采用纯代码UI，autolayout自动布局，core animation动画效果。
* [SwiftyGPIO](https://github.com/uraimo/SwiftyGPIO) - 通过 Swift 语言去控制基于 Linux 主板（比如：C.H.I.P. 和 树莓派） 的 GPIO（General Purpose Input Output ），去完成简单的工控功能（比如 LED 灯的显示）。
* [Scale.swifty](https://github.com/onmyway133/Scale) - 简单直观的单位计算及换算类库（支持常用计量类型）。代码简洁性、直观性杠杠的。
* [swift-pons](https://github.com/dankogai/swift-pons) - 面向协议的不受长度限制数字类型及数学计算扩充类库。用它做一款最牛科学计算器妥妥地。
* [SwiftString](https://github.com/amayne/SwiftString) - SwiftString:String 扩展功能很丰富（无论格式化杂乱字符串，还是子串查找，亦或是格式转换都很强大）。
* [FileBrowser.swift](https://github.com/marmelroy/FileBrowser) - FileBrowser.swift 一款开源的 iOS 文件浏览器, 支持文件搜索, 文件预览和 3D touch 功能。
* [AFBrushBoard.swift](https://github.com/marmelroy/FileBrowser) -  AFBrushBoard.swift基于swift的毛笔画板Demo。包含多阶贝塞尔曲线的抽取、模拟画笔速度等算法。
* [SwiftForms](https://github.com/ortuman/SwiftForms) - SwiftForms表单递交库，快速开发利器。
* [Design-Patterns-In-Swift](https://github.com/ochococo/Design-Patterns-In-Swift) - Design-Patterns-In-Swift如何使用常用设计模式及示例。
* [Dollar.swift](https://github.com/ankurp/Dollar) - Dollar.swift是一个Swift库，无需扩展任何内置对象就为Swift语言提供有效的函数式编程辅助方法，类似于Lo-Dash或JavaScript中的Underscore。而Cent则是通过扩展功能来扩展Swift中的特定对象类型。
* [Underscore.swift](https://github.com/JakeLin/Underscore) - 函数式编程辅助方法，可靠性上压倒目标对手是 Dollar。
* [PathKit.swift](https://github.com/kylef/PathKit) - PathKit.swift小而美的路径管理类。
* [Surge.swift](https://github.com/mattt/Surge) - Surge.swift基于苹果Accelerate高性能计算数学框架封装库。
* [Async.swift](https://github.com/duemunk/Async) - Async.swift简洁的后台执行代码的异步封装库。
* [AlecrimAsyncKit.swift](https://github.com/Alecrim/AlecrimAsyncKit) - 一款很优雅的异步执行框架库。
* [BrightFutures.swift](https://github.com/Thomvis/BrightFutures) - BrightFutures.swift漫长或复杂计算由独立线程异步来完成。
* [Euler.swift](https://github.com/mattt/Euler) - Euler.swift直观、简洁的数学表达式∛27÷3+∑[3,1,2]。
* [Siren.swift](https://github.com/ArtSabintsev/Siren) - Siren.swift当应用更新时，通知用户并提供App Store链接。
* [BTree.swift](https://github.com/lorentey/BTree) - BTree.swift:相对于标准集合类型具有更优执行性能的基于B-Tree的优化集合类型实现类库。
* [PromiseKit](https://github.com/mxcl/PromiseKit) - 同时支持 Swift 及 Objective-C 的 Promise 类库，异步编程类库 提供了很多实用的异步函数 让异步编程更简单。
* [Duration.swift](https://github.com/SwiftStudies/Duration) - 测量代码片段执行时间工具类库（Swift）。
* [Bolts-Swift](https://github.com/BoltsFramework/Bolts-Swift) - 全平台（所有支持 Swift 的设备）任务管理 futures/promises 异步实现类库。
* [BCColor.swift](https://github.com/boycechang/BCColor) - 轻量而强大的颜色处理库，纯 Swift 版。 支持从图片拾取一套主题色，类似AppleMusic；支持图片黑白化、对颜色的加深和变浅、生成渐变颜色等。
* [AIToolbox.swift](https://github.com/KevinCoble/AIToolbox) - AI 主流模块集工具箱库。其中涉及 AI 知识实在广阔又高端。
* [EZSwiftExtensions](https://github.com/goktugyil/EZSwiftExtensions) - 对Swift标准库， Foundation， UIKit 提供了很多高级扩展函数。
* [TempiBeatDetection.swift](https://github.com/jscalo/TempiBeatDetection) - Swift 语言写的音乐节奏节拍检测库。
* [Venice.swift](https://github.com/VeniceX/Venice) - 让 Swift 3 提前支持协程（Coroutine）。P.S.  Chris  曾答疑过，Coroutine 不在 Swift 3 支持范围中，将在更晚时候讨论语言级支持。
* [FlatBuffersSwift](https://github.com/mzaks/FlatBuffersSwift) - Swift 版 FlatBuffers 实现类库。P.S. FlatBuffers 是跨平台、高效，提供了 C++/Java 接口的序列化开源工具库。
* [Lyft.swift](https://github.com/genadyo/Lyft) - 一套面向 Lyft 开发者的 Swift API 类库。
* [Up-Down.swift](https://github.com/gjiazhe/Up-Down) - Up-Down.swift:在 OS X 菜单栏上实时显示网络上传和下载速度小工具。
* [Algorithm.swift](https://github.com/genadyo/Lyft) - 算法和概率模型工具集。（作者 Daniel Dahan）
* [Spots.swift](https://github.com/hyperoslo/Spots) - 一套为了加速开发效率、将 view models 采用 JSON 格式存储于云端 view controller 框架库。
* [PinpointKit.swift](https://github.com/Lickability/PinpointKit) - 简单的手势动作快速触发反馈组件。主要功能包含自动截屏、附加说明和日志。支持添加可定制箭头、着重框、文本、模糊打码等常用快照编辑功能。它非常适合开发过程中测试人员反馈缺陷。
* [Switcher.swift](https://github.com/X140Yu/Switcher) - 一个 OS X 小 App，可以很轻松地切换 App Store 和 iTunes 的账号，对于同时使用多个 Apple ID 的人来说非常地方便。

## PDF@

## 图像浏览及处理@
* [ShinpuruImage](https://github.com/FlexMonkey/ShinpuruImage) - Syntactic Sugar for Accelerate/vImage and Core Image Filters :large_orange_diamond:
* [core-image-explorer](https://github.com/objcio/issue-21-core-image-explorer) -  Core Image 滤镜处理图片-- swift ，[Core Image 介绍](http://objccn.io/issue-21-6/)。
* [GPUImage2.swift](https://github.com/BradLarson/GPUImage2) - Swift 版基于 GPU 图像和视频处理框架库。
* [TimingFunctionEditor](https://github.com/schwa/TimingFunctionEditor) - TimingFunctionEditor用swift编写， 贝塞尔曲线编辑器，编辑后可以预览或拷贝代码片段直接使用。P.S. 该项目采用更简单的依赖管理器。 [Carthage](https://github.com/Carthage/Carthage) ，而非常用的 CocoaPods。[Carthage介绍中文](http://www.cocoachina.com/ios/20141204/10528.html)。
* [AAFaceDetection](https://github.com/aaronabentheuer/AAFaceDetection) - AAFaceDetection--swift，简单、实用的面部识别封装库。虽然该技术从 iOS 5 发展，不过真正有趣的应用还不多。
* [Concorde](https://github.com/contentful-labs/Concorde) - swift, Concorde, 一个可用于下载和解码渐进式 JPEG 的库, 可用来改善应用的用户体验。
* [ZoomTransition](https://github.com/tristanhimmelman/ZoomTransition) - swift, 通过手势操控图片的放大、缩小、旋转等自由变化效果的组件及示例。
* [AFImageHelper](https://github.com/melvitax/AFImageHelper) - swift,一套针对 UIImage 和 UIImageView 的实用扩展库，功能包含填色和渐变、裁剪、缩放以及具有缓存机制的在线图片获取。
* [PinterestSwift](https://github.com/demonnico/PinterestSwift) - swift,Pinterest 风格图片缩放、切换示例。
* [PhotoStackView-Swift](https://github.com/ijoyc/PhotoStackView-Swift) - PhotoStackView——照片叠放视图，[使用说明](http://blog.csdn.net/u013604612/article/details/46336657)。
* [MPParallaxView](https://github.com/DroidsOnRoids/MPParallaxView) - 是用 Swift 写的类似 Apple TV Parallax 效果的视图。
* [SDECollectionViewAlbumTransition](https://github.com/seedante/SDECollectionViewAlbumTransition) - 用自定义的 push 和 pop 实现了有趣的 iOS 相册翻开动画效果。
* [SKPhotoBrowser.swift](https://github.com/xujingzhou/BeautyHour) - swift中规中矩、实用的图片浏览类库。示例也很完整。
* [Nuke.swift](https://github.com/kean/Nuke) - 完整、强大、实用的图片管理类库。主要功能包括可定制装载，缓存，滤镜及尺寸变换。
* [PagingView.swift](https://github.com/KyoheiG3/PagingView) - 注重细节的自动布局分页视图组件。
* [DouBanMeinv.swift](https://github.com/luzefeng/DouBanMeinv) - 抓取豆瓣美女图片，瀑布流显示。
* [SwViewCapture.swift](https://github.com/startry/SwViewCapture) - SwViewCapture.swift一个用起来还不错的iOS截图库.(支持截取所有内容, 适用于所有ScrollView组成的视图, 包括WebView)。
* [Filterpedia.swift](https://github.com/FlexMonkey/Filterpedia) - 强大的图片滤镜库演示。
* [preview-transition.swift](https://github.com/Ramotion/preview-transition) - 通过向导式代码实现步骤，实现完整、自然流畅的图片预览及转场功能。
* [CartoonEyes.swift](https://github.com/FlexMonkey/CartoonEyes) - 前置摄像头捕获图像后，采用 Core Image 脸部识别 CIDetector 和漫画效果滤镜复合出卡通效果眼睛。

####图像圆角@

## 摄像照相视频音频处理@

* [CameraManager](https://github.com/imaginary-cloud/CameraManager) - 相机管理封装类库。看着极好用的样子----swift。
* [Sharaku](https://github.com/makomori/Sharaku) 类似Instagram的图片滤镜库 Image filtering UI library like Instagram.
* [recordDemo.swift](https://github.com/lfb-cd/recordDemo) - 一个Swift语言实现直接可以用的录音Demo，[实现说明](http://www.jianshu.com/p/f0b88355d7cb)。
* [Swift-Radio-Pro](https://github.com/swiftcodex/Swift-Radio-Pro) - 集成 LastFM 的专业电台应用（基于 Swift 2.0）。
* [mobileplayer-ios.swift](https://github.com/mobileplayer/mobileplayer-ios) - 很不错的高度可定制播放器项目。
* [Periscope-VideoViewController.swift](https://github.com/gontovnik/Periscope-VideoViewController) - 简洁实用的视频快进、倒带控制视图类库。
* [AudioKit.swift](https://github.com/audiokit/AudioKit) - 音频合成、加工及分析平台（支持 iOS、OS X、tvOS）框架库。无论其易用性，还是功能性及专业性。
* [SkfSwiftCammer](https://github.com/wubianxiaoxian/SkfSwiftCammer) - 一个相机demo，在oc里面调用了swift。
* [BMPlayer.swift](https://github.com/BrikerMan/BMPlayer) - 基于 AVPlayer 使用 Swift 封装的视频播放器，方便快速集成,支持横屏、竖屏，上下滑动调节音量、屏幕亮度，左右滑动调节播放进度。
* [JHFilterDemo](https://github.com/China131/JHFilterDemo) 图片滤镜生成器

## 视频@
## 消息相关@
#### 消息推送客户端@
#### 消息推送服务器端@

#### 通知相关@
* [Homeoff](https://github.com/lizyyy/Homeoff) - 用swift写了一个模仿Launcher通知中心快捷方式的应用。支持20个应用，并增加了一个返回到桌面来解放Home键的功能。
* [SwiftNotificationCenter](https://github.com/100mango/SwiftNotificationCenter) - 一个面向协议的类型安全、线程安全、内存安全的通知中心。


## 时间日期@
## 设计模式@

## 版本新API的Demo@
* [MTSwift-Learning](https://github.com/MartinRGB/MTSwift-Learning) - 通过一些简单项目实战演练开始学习 Swift 。
* [iOS8-day-by-day](https://github.com/shinobicontrols/iOS8-day-by-day) - swift。
* [iOS9-day-by-day](https://github.com/shinobicontrols/iOS9-day-by-day) - swfit [iOS9 Day-by-Day :: Day 2 :: UI Testing](http://www.jianshu.com/p/039f8de6ee4d)。
* [iOS 9 分屏多任务](http://www.cocoachina.com/ios/20150714/12557.html) - iOS 9 分屏多任务：Slide Over & Split View快速入门（中文版）。
* [uistackview-sample.swift](https://github.com/uraimo/uistackview-sample) - iOS 9 引进了 UIStackViews，提供 auto-layout 特性。如果你开发过 Android 应用，会发现它和 LinearLayouts 概念上很类似，它是增强版。你可以手动创建，也可以使用 IB 自动创建，本文用的是代码实现。

## 代码安全与密码@
* [OAuthSwift](https://github.com/OAuthSwift/OAuthSwift) - OAuthSwift国外主流网站OAuth授权类库。
* [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - swift加密库, 支持md5,sha1,sha224,sha256...。

## 动态更新@

## AppleWatch@
* [Apple Watch开发教程资料汇总](http://www.swiftkiller.com/?p=613) - Apple Watch开发教程资料汇总。
* [Stargate](https://github.com/contentful-labs/Stargate) - 通过 iPhone 桥接实现 Mac 与 Watch 的即时通讯。Stargate 通过封装两个优秀的基础类库 MMWormhole 和 PeerKit 实现高效的通讯应用。--swift
* [soon](https://github.com/sandofsky/soon) - 一款倒计时 WatchKit 示例应用。作者从架构的角度，思考如何设计一款完整、通讯高效且性能又好的 WatchKit 扩展应用。
* [MMWormhole.swift](https://github.com/mutualmobile/MMWormhole) - MMWormhole.swift:iOS或OS X扩展与宿主应用的通讯框架。
* [overlook](https://github.com/wess/overlook) 可以监测目标目录文件改变，执行对应命令的后台及命令行工具 The Judge, Jury and Executioner for the file system.

## VPN@

* [vpnon](https://github.com/lexrus/vpnon/) - swift的VPN On 的源码和本地化内容都是开放的: [官方网站](https://crowdin.com/project/vpnon)。

## 物联网@

## 未分类@

* [Eureka](https://github.com/xmartlabs/Eureka ) 简洁方便的 iOS 表单生成器 （Swift 3）
