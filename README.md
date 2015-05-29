# TimLiu-iOS
========
自己总结的iOS、mac开源项目及库。 github排名 [https://github.com/trending](https://github.com/trending),github搜索：[https://github.com/search](https://github.com/search)

###  目录
- [UI](#UI)
    - [下拉刷新](#下拉刷新)
    - [模糊效果](#模糊效果)
    - [AutoLayout](#AutoLayout)
    - [富文本](#富文本)
    - [图表](#图表)
    - [表相关](#表相关) 
    - [隐藏与显示](#隐藏与显示)
    - [HUD与Toast](#HUD与Toast)
    - [对话框](#对话框)
    - [其他UI](#其他UI)
- [动画](#动画)
    - [侧滑与右滑返回手势](#侧滑与右滑返回手势)
    - [其他动画](#POP动画)
- [网络相关](#网络相关)
    - [网络连接](#网络连接)
    - [网络测试](#网络测试)
    - [图像获取](#图像获取)
    - [网络聊天](#网络聊天)
    - [网络测试](#网络测试)
    - [WebView](#WebView)
- [Model](#Model)
- [其他](#其他)
- [数据库](#数据库)
- [缓存处理](#缓存处理)
- [PDF](#PDF)
- [图像浏览及处理](#图像浏览及处理)
- [摄像照相视频音频处理](#摄像照相视频音频处理)
- [响应式框架](#响应式框架)
- [消息相关](#消息相关)
    - [消息推送客户端](#消息推送客户端)
    - [消息推送服务器端](#消息推送服务器端)
    - [通知相关](#通知相关)
- [版本新API的Demo](#版本新API的Demo)
- [代码安全与密码](#代码安全与密码)
- [测试及调试](#测试及调试)
- [AppleWatch](#AppleWatch)
- [完整项目](#完整项目)
- [VPN](#VPN)
- [Xcode插件](#Xcode插件)
- [美工资源](#美工资源)
- [开发资源](#开发资源)
    - [开发资料](#开发资料)
    - [swift](#swift)
    - [他人开源总结](#他人开源总结)
    - [中文开发博客列表](#中文开发博客列表)

========
### 具体内容 =============================
========
#### UI
##### 下拉刷新
* [EGOTableViewPullRefresh](https://github.com/enormego/EGOTableViewPullRefresh) - 最早的下拉刷新控件。
* [SVPullToRefresh](https://github.com/samvermette/SVPullToRefresh) - 下拉刷新控件。 
* [MJRefresh](https://github.com/CoderMJLee/MJRefresh) - 仅需一行代码就可以为UITableView或者CollectionView加上下拉刷新或者上拉刷新功能。可以自定义上下拉刷新的文字说明。具体使用看“使用方法”。 （国人写）
* [XHRefreshControl](https://github.com/xhzengAIB/XHRefreshControl) - XHRefreshControl 是一款高扩展性、低耦合度的下拉刷新、上提加载更多的组件。（国人写）
* [CBStoreHouseRefreshControl](https://github.com/coolbeet/CBStoreHouseRefreshControl) - 一个效果很酷炫的下拉刷新控件。
* [BreakOutToRefresh](https://github.com/dasdom/BreakOutToRefresh) - 一个下拉刷新打砖块的开源 Swift 库，能让用户在等待下拉刷新的时候边玩撞球游戏边等待。
* [KYJellyPullToRefresh](https://github.com/KittenYang/KYJellyPullToRefresh) - 实现弹性物理效果的下拉刷新，神奇的贝塞尔曲线，配合UIDynamic写的一个拟物的下拉刷新动画。
* [MHYahooParallaxView](https://github.com/michaelhenry/MHYahooParallaxView) - 类似于Yahoo Weather和News Digest首屏的视差滚动。 
* [SDRefreshView](https://github.com/gsdios/SDRefreshView) - 简单易用的上拉和下拉刷新（多版本细节适配）。
* [ZLSwiftRefresh](https://github.com/MakeZL/ZLSwiftRefresh) - swift下拉刷新/上拉加载更多，支持自定义动画，集成简单，兼容UITableView/CollectionView/ScrollView/WebView。
* [BreakOutToRefresh](https://github.com/dasdom/BreakOutToRefresh) - swift，上拉和下拉刷新。
* [GearRefreshControl](https://github.com/andreamazz/GearRefreshControl) -  swift，上拉和下拉刷新。
* [refresher](https://github.com/jcavar/refresher) -  swift，上拉和下拉刷新。
* [可展开/收缩的下拉菜单--SvpplyTable](http://d.cocoachina.com/code/detail/237753) -  一个可展开可收缩的下拉菜单，类似Svpply app。
* [ODRefreshControl](https://github.com/Sephiroth87/ODRefreshControl) - 原iOS6上的橡皮糖刷新样式，很有意思。现在也很多大的 App 在用，比如虾米音乐和 QQ 客户端。
* [PullToMakeSoup](https://github.com/Yalantis/PullToMakeSoup) - PullToMakeSoup, 自定义下拉刷新的动画效果：煮饭, Yalantis新作！
* [TwitterCover](https://github.com/cyndibaby905/TwitterCover) -  Twitter iOS客户端的下拉封面模糊效果。

##### 模糊效果
 * [FXBlurView](https://github.com/nicklockwood/FXBlurView) -be 支持iOS5.0以上版本，支持静态、动态模糊效果，继承与UIView的模糊特效。
 * [VVBlurPresentation](https://github.com/onevcat/VVBlurPresentation) -很简单易用的在原来viewconntroller基础上做模糊，然后present新的viewcontroller的。
 * [UICustomActionSheet](https://github.com/pchernovolenko/UICustomActionSheet) - 通过模糊背景来着重强调与菜单相关的元素--对话框 里面已经收藏。
 * [SABlurImageView](https://github.com/szk-atmosphere/SABlurImageView) - 支持渐变动画效果的图像模糊化类库。P.S. 与前几天推存类库 SAHistoryNavigationViewController 是同一位作者。

##### AutoLayout
* [Masonry](https://github.com/Masonry/Masonry) - Masonry是一个轻量级的布局框架，拥有自己的描述语法，采用更优雅的链式语法封装自动布局，简洁明了并具有高可读性（ [使用介绍1](http://adad184.com/2014/09/28/use-masonry-to-quick-solve-autolayout/)  [使用介绍2](http://ios.jobbole.com/81483/)），[Masonry、Classy、ClassyLiveLayout介绍](http://www.jianshu.com/p/2ed5f7444900)。
* [Classy](https://github.com/cloudkite/Classy/) - Classy是一个能与UIKit无缝结合stylesheet(样式)系统。它借鉴CSS的思想，但引入新的语法和命名规则，[Classy官网](http://classy.as/getting-started/)，[Masonry、Classy、ClassyLiveLayout介绍](http://www.jianshu.com/p/2ed5f7444900)。
* [ClassyLiveLayout](https://github.com/olegam/ClassyLiveLayout) - ClassyLiveLayout通过结合Classy stylesheets与Masonry一起使用，能够在运行的模拟器中微调Auto Layout约束实时显示效果的工具，[Masonry、Classy、ClassyLiveLayout介绍](http://www.jianshu.com/p/2ed5f7444900)。
* [Snap](https://github.com/Masonry/Snap) - Snap是Masonry Auto Layout DSL的Swift版本，是一款轻量级的布局框架，使用了更良好的语法封装了AutoLayout。Snap支持iOS和OS X。
* [PureLayout](https://github.com/smileyborg/PureLayout) - 
* [UIView-AutoLayout](https://github.com/smileyborg/UIView-AutoLayout) - 
Deprecated in favor of PureLayout, which includes OS X support:https://github.com/smileyborg/PureLayout。
* [Cartography](https://github.com/robb/Cartography) - 
* [Auto-Layout-Showcase](https://github.com/philcn/Auto-Layout-Showcase) - swift,AutoLayout 进阶 Demo，宽高比约束、比例约束、不等约束、视差约束、低优先级约束等高级用法，无需写码即可进行复杂页面布局，Demo 还动态模拟了各屏幕下的效果。来自百度知道 iOS 小组的内部分享。


##### 富文本
* [RTLabel](https://github.com/honcheng/RTLabel) - 富文本。
* [TYAttributedLabel](https://github.com/12207480/TYAttributedLabel) -  TYAttributedLabel。 简单易用的属性文本控件(无需了解CoreText)，支持富文本，图文混排显示，支持添加链接，image和UIView控件，支持自定义排版显示。
* [TQRichTextView](https://github.com/TinyQ/TQRichTextView) - 用于做富文本视图控件显示，用于即时通讯的表情显示，以及资源评论的富文本显示。
* [TTTAttributedLabel](https://github.com/mattt/TTTAttributedLabel) - 一个文字视图开源组件，是UILabel的替代元件，可以以简单的方式展现渲染的属性字符串。另外，还支持链接植入，不管是手动还是使用UIDataDetectorTypes自动把电话号码、事件、地址以及其他信息变成链接。[用TTTAttributedLabel创建变化丰富的UILabel](http://blog.csdn.net/prevention/article/details/9998575) - 网易新闻iOS版使用。
* [MLEmojiLabel](https://github.com/molon/MLEmojiLabel) - 自动识别网址、号码、邮箱、@、#话题#和表情的label。可以自定义自己的表情识别正则，和对应的表情图像。(默认是识别微信的表情符号)，继承自TTTAttributedLabel，所以可以像label一样使用。label的特性全都有，使用起来更友好更方便。
* [FXLabel](https://github.com/nicklockwood/FXLabel) - FXLabel是一个功能强大使用简单的类库，通过提供一个子类改进了标准的UILabel组件，为字体增加了阴影、内阴影和渐变色等，可以被用在任何标准的UILabel中。FXLabel还提供了更多控件，可以对字体行距、字体间距等进行调整。
* [WFReader](https://github.com/TigerWf/WFReader) - 一款简单的coretext阅读器，支持文本选择、高亮以及字体大小选择等。
* [WPAttributedMarkup](https://github.com/nigelgrange/WPAttributedMarkup) - WPAttributedMarkup is a simple utility category that can be used to easily create an attributed string from text with markup tags and a style dictionary。
* [KMPlaceholderTextView](https://github.com/MoZhouqi/KMPlaceholderTextView) - 可显示多行 placeholder 的 textView，可以在IB里面设置 -- swift。
* [HHFlashSwitch](https://github.com/mrchenhao/HHFlashSwitch) - 一个另类的UISwitch，选择后，背景水波扩散变色效果。 
* [UITextViewDIYEmojiExample](https://github.com/zekunyan/UITextViewDIYEmojiExample) - [UITextView编辑时插入自定义表情-简单的图文混编](http://tutuge.me/2015/03/07/UITextView%E7%BC%96%E8%BE%91%E6%97%B6%E6%8F%92%E5%85%A5%E8%87%AA%E5%AE%9A%E4%B9%89%E8%A1%A8%E6%83%85-%E7%AE%80%E5%8D%95%E7%9A%84%E5%9B%BE%E6%96%87%E6%B7%B7%E7%BC%96/)。 
* [Shimmer](https://github.com/facebook/Shimmer) - BlingBling闪光效果，酷炫的Label的效果，可以用于加载等待提示。
* [ZSSRichTextEditor](https://github.com/nnhubbard/ZSSRichTextEditor) - 适用于iOS的富文本WYSIWYG编辑器，支持语法高亮和源码查看。ZSSRichTextEditor包含所有WYSIWYG标准的编辑器工具。
* [RichEditorView](https://github.com/cjwirth/RichEditorView) - swift，一套可定制富文本编辑器组件及示例。功能完整、代码简练、实现逻辑巧妙（编辑器核心与 WebView 结合，采用 HTML5 contentEditable 编辑模式，执行JS 配套命令 execCommand 实现富文本编辑功能）。
* [DTCoreText](https://github.com/Cocoanetics/DTCoreText) - 可以解析HTML与CSS最终用CoreText绘制出来，通常用于在一些需要显示富文本的场景下代替低性能的UIWebView。[DTCoreText源码解析](http://blog.cnbang.net/tech/2630/)。
* [CSGrowingTextView](https://github.com/cloverstudio/CSGrowingTextView) - 用作即时通讯文本框和评论文本框使用，可以显示多行输入。 
* [MarkdownTextView](https://github.com/indragiek/MarkdownTextView) - 显示Markdown的TextView。 
* [高仿微信限定行数文字内容](http://d.cocoachina.com/code/detail/300299) - 采用Autolayout高仿微信纯文字限定行数。
* [FuriganaTextView](https://github.com/lingochamp/FuriganaTextView) - 实现复杂的日文韩文排版。

##### 图表
* [PNChart](https://github.com/kevinzhow/PNChart) - 国内开源作者，动态的图表。
* [swift-linechart](https://github.com/zemirco/swift-linechart) - 功能完整、实用的折线图组件。使用方便，参数配置简单。是不可多得的优质组件--swift。
* [ios-charts](https://github.com/danielgindi/ios-charts) - 一款优秀 Android 图表开源库 MPAndroidChart 的 Swift 语言实现版（支持 Objective-C 和 Swift 调用）。缺省提供的示例代码为 Objective-C。
* [TEAChart](https://github.com/xhacker/TEAChart) - xhacker/TEAChart 一个简洁的 iOS 图表库，支持柱状图、饼图以及日历等。

##### 表相关
 * [SWTableViewCell](https://github.com/onevcat/SWTableViewCell) - 国内开源作者，带很多手势的表单元格。
 * [MCSwipeTableViewCell](https://github.com/alikaragoz/MCSwipeTableViewCell) - 带很多手势的表单元格。
 * [TMQuiltView](https://github.com/1000Memories/TMQuiltView) - 瀑布流。
 * [WaterfallFlowDemo](https://github.com/lengmolehongyan/WaterfallFlowDemo) - 一个简单的UICollectionView瀑布流布局演示demo。
 * [XLForm](https://github.com/xmartlabs/XLForm) - 很多表格类的table,写法更高冷一点，推荐使用。 
 * [RETableViewManager](https://github.com/romaonthego/RETableViewManager) - 可以十分方便地生成各种样式、各种功能的TableView。只要开发者能想到的列表效果或者功能，都可以利用这份代码迅速编写出来。比如，之前要实现一个填写各种资料的列表，可能需要很多代码，现在只需要几行代码就可以实现。 
 * [UIScrollSlidingPages](https://github.com/TomThorpe/UIScrollSlidingPages) - 允许添加多视图控件，并且可以横向滚动。有点类似于Groupon app。
 * [HBHorizontalTableView](https://github.com/izyhuang/HBHorizontalTableView) - swift，TableView 横向滚动小示例（仿照 AppStore 应用展示）。
 * [HorizontalScrollCell](https://github.com/mcelayir/HorizontalScrollCell) - HorizontalScrollCell是一款使用方便的水平方向可滚动的单元格，适用于UICollectionView中实现水片方向滚动视图。 。
 * [SYJiugonggeTableView](https://github.com/shiyuan17/SYJiugonggeTableView) - tableView封装的九宫格。
 * [UUChatTableView](https://github.com/ZhipingYang/UUChatTableView) - UUChatTableView 气泡聊天界面，支持文本、图片以及音频的气泡聊天界面。[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。
 * [Chats](https://github.com/acani/Chats) - 聊天 UI 示例程序。此项目应该只为演示或学习之用，没有服务器 -- swift。 
 * [Atlas-iOS](https://github.com/layerhq/Atlas-iOS) - 快速在iOS里集成聊天功能，类似开源版本的环信。Layer家开源了一套聊天app界面的解决方案.看起来很赞，很多蛮复杂的东西直接都帮封好了。不得不说现在做app开发真是很简单，大部分时间搭积木就可以了。[官方网站](https://atlas.layer.com/)。
 * [DLSlideView](https://github.com/agdsdl/DLSlideView) - DLSlideView对常见的顶部Tab页点击、滑动分页做了封装。它使用基于ViewController的container特性（而不是scrollview）来管理各个子页面，以支持无限分页，[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。
 * [VOVCManager](https://github.com/pozi119/VOVCManager) - 页面管理器:1.跳转指定页面,只需要知道viewController的Class名,如果有storyboard,则需要指定storyboard名；2.无需添加基类；3.支持URLScheme跳转指定页面。
 * [MBXPageViewController](https://github.com/Moblox/MBXPageViewController) - 简洁快速的页面切换--MBXPageViewController，带有按钮控件的UIPageController，非常整洁、简单以及快速。该项目通过三种形式展示页面之间的切换，比如导航栏上的多个tab切换、页面左右两端箭头指示切换，以及使用分段控件。
 * [GUITabPagerViewController](https://github.com/guilhermearaujo/GUITabPagerViewController) - 多个tab滑动切换。
 * [VOMetroLayoutDemo](https://github.com/pozi119/VOMetroLayoutDemo) - Metro风格的UICollectionView, 目前只支持横向布局,仅在iPad上应用。
 * [KYCellAnimation](https://github.com/KittenYang/KYCellAnimation) - 给UITableViewCell增加进入的动画。
 * [COBezierTableView](https://github.com/knutigro/COBezierTableView) - swift，通过编辑 Bezier 曲线四点位置设置 TableView 内 Cell 及对应按扭位置。实验效果很赞。
 * [RDVTabBarController](https://github.com/robbdimitrov/RDVTabBarController) - 一个TabBar组件，可以方便设置底部菜单的文字图片，点击效果，小红点提示等。
 * [横向展示文本内容的自定义cell](http://d.cocoachina.com/code/detail/298409) - 可以横向展示文本内容的自定义cell，根据文本无限滚动。
 * [UITableView-FDTemplateLayoutCell](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) - UITableView-FDTemplateLayoutCell 是一个方便缓存 UITableViewCell 的高度的框架。

##### 隐藏与显示
 * [SlideTapBar](http://d.cocoachina.com/code/detail/286102) - 滚动栏菜单，向上滚动时隐藏tabbar，向下滚动马上显示tabbar。
 * [FoldingTabBar.iOS](https://github.com/Yalantis/FoldingTabBar.iOS) - 可折叠Tab Bar和Tab Bar Controller。
 * [LTNavigationBar](https://github.com/ltebean/LTNavigationBar) - LTNavigationBar为app导航栏添加动态着色效果，可自定义其背景色。Demo包含：1.变换背景色；2.滚动视图，导航栏和状态栏重叠。
 * [BLKFlexibleHeightBar](https://github.com/bryankeller/BLKFlexibleHeightBar) - 固定Header的效果库。。

##### HUD与Toast
 * [MBProgressHUD](https://github.com/jdg/MBProgressHUD) - 最多人用的loading。
 * [SVProgressHUD](https://github.com/TransitApp/SVProgressHUD) - SVProgressHUD的loading。
 * [ProgressHUD](https://github.com/relatedcode/ProgressHUD) - ProgressHUD的loading，使用最简单。

##### 对话框
* [WCAlertView](https://github.com/m1entus/WCAlertView) - 自定义的对话框。
* [IOS7AlertView](https://github.com/wimagguc/ios-custom-alertview) - IOS7AlertView的对话框。
* [AMSmoothAlert](https://github.com/mtonio91/AMSmoothAlert) - 动画效果不错，最多star，但不支持arm64。
* [DQAlertView](https://github.com/dinhquan/DQAlertView) - 扁平化的样式不错。
* [HHAlertView](https://github.com/mrchenhao/HHAlertView) - 一个简易的alertview  有三种样式，有成功，失败，和警告三种样式，支持Delegate和block两种回调。
* [MJPopupViewController](https://github.com/martinjuhasz/MJPopupViewController) - 实现弹出视图的各种弹出和消失效果，包括淡入淡出（fade in，fade out），从屏幕上方飞进，下方飞出，从屏幕左方飞进，右方飞出等等效果。 
* [TAOverlay](https://github.com/TaimurAyaz/TAOverlay) - TAOverlay可通过叠加层展示有用的信息，可自定义文本和背景色，添加阴影和模糊效果，以及更改字体大小或者用自定义图片替换页面上的icon。
* [UICustomActionSheet](https://github.com/pchernovolenko/UICustomActionSheet) - 通过模糊背景来着重强调与菜单相关的元素--模糊效果 里面已经收藏。
* [ActionSheetPicker-3.0](http://code.cocoachina.com/detail/232178) - 该项目是此前热门项目ActionSheetPicker的新版本，快速复制了iOS 8上的下拉 UIPickerView/ActionSheet功能。
* [MJAlertView](https://github.com/mayuur/MJAlertView) - 3D效果转场效果警示图--MJAlertView。

##### 其他UI
 * [AwesomeMenu](https://github.com/levey/AwesomeMenu) - 最多人用的Path菜单。
 * [DCPathButton](https://github.com/Tangdixi/DCPathButton) - Path，4.0的弹出菜单，呼出或者关闭菜单时，多个小图标会分别按照逆时针和顺时针的方向进行滚动。
 * [SphereMenu](https://github.com/itouch2/SphereMenu) - 利用UIDynamicAnimator的有趣的菜单，path类似。 
 * [KYGooeyMenu](https://github.com/KittenYang/KYGooeyMenu) - KYGooeyMenu 是一个具有 Gooey Effects 带粘性的扇形菜单控件(卫星菜单、path)。
 * [TwitterPaggingViewer](https://github.com/xhzengAIB/TwitterPaggingViewer)  - 多个Tableview，左右滑动。
 * [CircularProgressControl](https://github.com/carantes/CircularProgressControl) - Circular Progress Control using CAShapeLayer ，环形进度控制条。
 * [KDCircularProgress](https://github.com/kaandedeoglu/KDCircularProgress) -  KDCircularProgress是使用swift制作的色彩炫丽的进度条，可以加入多种颜色来控制进度条的渐变效果。 
 * [XLPagerTabStrip](https://github.com/xmartlabs/XLPagerTabStrip) - 做的很棒的iOS下的PagerTabStrip。 
 * [RandomColorSwift](https://github.com/onevcat/RandomColorSwift) - 一个自动生成好看的颜色的 Swift 库，RandomColorSwift。
 * [HexColorService](https://github.com/ChangweiZhang/HexColorService) - 将16进制颜色字符串转成UIColor。
 * [Rainbow](https://github.com/NorthernRealities/Rainbow) - 旨在提高代码可读性及易用性的 UIColor 扩展，它使原先有限的预定义颜色（方法）选择，扩展至超过 1200 种。
 * [UIColor-ChineseTraditionalColors](https://github.com/zhxnlai/UIColor-ChineseTraditionalColors) - 中国传统颜色引用 UIColor 扩展。“UIColor.桃红()，UIColor.竹青() ...”，共158种。 
 * [kxmenu](https://github.com/kolyvan/kxmenu) - kxmenu弹出菜单，点击视图上任意位置的按钮，会弹出一个菜单，并且有个小箭头指向点击的按钮，类似气泡视图。弹出的菜单位置会根据按钮的位置来进行调整。 
 * [QBPopupMenu](https://github.com/questbeat/QBPopupMenu) - QBPopupMenu弹出菜单，实现类似 UIMenuItem 的弹出菜单按钮。点击按钮，会弹出一个菜单，上面可以排列多个按钮。纯代码实现，不需要任何图片。
 * [类似美团的下拉菜单](http://code.cocoachina.com/detail/284158) - 类似美团的下拉菜单，[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。 
 * [类似美团的下拉选项](http://code4app.com/ios/%E7%B1%BB%E4%BC%BC%E7%BE%8E%E5%9B%A2%E7%9A%84%E4%B8%8B%E6%8B%89%E9%80%89%E9%A1%B9/538606d4933bf06e0a8b496e) -  类似于美团、大众点评的下拉菜单选项，code4app代码，评论代码有瑕疵。
 * [CRMediaPickerController](http://code.cocoachina.com/detail/284267) - 一个简单易用的图片/视频选择器。1.可同时选择照片和视频。 2.挑选范围有Camera、Camera Roll、Photo Library以及最近拍摄的照片和视频。3.可自定义UIImagePickerController属性（Camera Overlay、Camera Device、Camera View Transform以及allowsEditing）。4.支持横屏和竖屏5.原生的iOS UI。，[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。 
 * [MDCSwipeToChoose](https://github.com/modocache/MDCSwipeToChoose) - MDCSwipeToChoose可简单地添加滑动手势来调用UIView，并使用该行为提供了一个组件以创建类似Tinder app的like或者dislike界面的轻扫。基于轻扫的方向，你可以决定执行什么样的行为，并且你可以自定义文本颜色和图片。该项目适用于教学用的抽认卡、图片查看器以及其他等。 
 * [iOS Material Design库](http://d.cocoachina.com/code/detail/285611) - 该项目借鉴于谷歌的Material Design guideline，用户可自定义背景色。 
 * [ZMaterialDesignUIButton](https://github.com/richzertuche/ZMaterialDesignUIButton) - Swift Material Design UIButton。
 * [MediumScrollFullScreen](https://github.com/pixyzehn/MediumScrollFullScreen) - Medium的可扩展滚动页面，上下滚动时，全屏显示内容，并自然消隐上下菜单。由此项目感知，作者是一位很注重细节的开发者，他的另外[几个菜单类项目](https://github.com/pixyzehn)也都不错，值得参考，比如：PathMenu, MediumMenu 等。
 * [SDProgressView](https://github.com/gsdios/SDProgressView) - 简便美观的进度指示器，此系列共有六种样式的进度指示器。 
 * [WZFlashButton](https://github.com/SatanWoo/WZFlashButton) - WZFlashButton，点击后button里面出现水波扩散效果。
 * [Twinkle](https://github.com/piemonte/Twinkle) - 为字体加上钻石版闪耀的效果。使用Swift编写。 
 * [ios-multi-back-button](https://github.com/palmin/ios-multi-back-button) - 可替换内置的UInavigationController返回按钮，长按左上角的返回按钮，实现多层级的快速返回。
 * [ASDayPicker](http://code.cocoachina.com/detail/226543) - 适用于iOS (iPhone)的日期选择器，类似于Calendar app的周视图。
 * [today extension](http://adad184.com/2014/10/29/2014-10-29-how-to-setup-today-extension-programmatically/) - 用纯代码构建一个Widget(today extension) 。
 * [FSCalendar](https://github.com/f33chobits/FSCalendar) - 日历视图，带有微妙和平滑的滚动效果，可自定义外观--国人。
 * [HSDatePickerViewController](https://github.com/EmilYo/HSDatePickerViewController) - 带有Dropbox Mailbox感觉的时间日期选择器。启动是背景被模糊化。界面也是主流的扁平化风格。 
 * [JTCalendar](https://github.com/jonathantribouharet/JTCalendar) - iOS下优美的 Calendar 组件，做 GTD 类 App 必备。
 * [Persei](https://github.com/Yalantis/Persei) - 动画隐藏或显示顶部菜单支持库及示例项目。--swift
 * [Form](https://github.com/hyperoslo/Form) - JSON 驱动的 Form表单系统，复杂的表单填写类 App 极其需要（比如淘宝呢！）。
 * [SwiftSpinner](https://github.com/icanzilb/SwiftSpinner) - SwiftSpinner是使用swift制作的一款精致带感的指示器，并且连带有字体信息显示，模糊背景，半透明，扁平化等IOS8的效果。
 * [AKPickerView-Swift](https://github.com/Akkyie/AKPickerView-Swift) - 一款小而美的 3D 效果选择器。
 * [ImagePickerSheet](https://github.com/larcus94/ImagePickerSheet) - 图片或视频选择器（可多选）组件及其示例项目。
 * [iOS-RatingBar](https://github.com/saiwu-bigkoo/iOS-RatingBar) - iOS-RatingBar swift版的评分控件,跟Android的RatingBar一样有两种模式，评分模式和只读模式'支持视图编辑，自定义星星数量，评分等级,另外还能支持非整数星，0.5颗星，0.1颗星,可以开启动画效果。
 * [RKNotificationHub](https://github.com/cwRichardKim/RKNotificationHub) - 快速给 UIView 添加上炫酷的通知图标（Badge、红点、提示）。 
 * [BubbleTransition](https://github.com/andreamazz/BubbleTransition) - 以气泡膨胀和缩小的动画效果来显示和移除 controller，Uber的就是这种取消操作的方式。
 * [KYFloatingBubble](https://github.com/KittenYang/KYFloatingBubble) - 类似iOS7中Game Center浮动气泡的效果。
 * [DKNightVersion](https://github.com/Draveness/DKNightVersion) - DKNightVersion 是一个支持夜间模式切换的框架。

========
#### 动画
* [Core Animation笔记，基本的使用方法](http://www.starming.com/index.php?v=index&view=62) - Core Animation笔记，基本的使用方法：1.基本动画，2.多步动画，3.沿路径的动画，4.时间函数，5.动画组。
* [awesome-ios-animation](https://github.com/sxyx2008/awesome-ios-animation) -iOS平台下的图表组件。

##### 侧滑与右滑返回手势
 * [SloppySwiper](https://github.com/fastred/SloppySwiper) - iOS系统自带的UINavigationController要7.0才支持，但不过该手势只能从屏幕左侧边缘识别，如果要扩大到整个屏幕范围怎么办？配合一个SloppySwiper无需代码就可以轻松实现。此库支持iOS5.0以上版本（另外：Nav的title滑动不明显，本人写了2个类似的控件），[SloppySwiper-demo](https://github.com/Tim9Liu9/SloppySwiper-Example) ：代码方式与storyboard方式。
 * [SCNavigation](https://github.com/singro/SCNavigation) - UINavigation可以右滑返回，隐藏UINavigationBar。
 * [UINavigationController-YRBackGesture](https://github.com/YueRuo/UINavigationController-YRBackGesture) - 支持右滑返回手势，标题栏不动。
 * [GHSidebarNav](https://github.com/gresrun/GHSidebarNav) - 现在比较流行使用侧开(侧滑)菜单设计。试了不少控件，感觉GHSidebarNav最成熟，尤其对纯代码创建的界面兼容性最好。[在Storyboard中使用GHSidebarNav侧开菜单控件](http://www.cnblogs.com/zyl910/archive/2013/06/14/ios_storyboard_sidemenu.html)。
 * [iOS-Slide-Menu](https://github.com/aryaxt/iOS-Slide-Menu) - 能够类似Facebook和Path那样弹出左右边栏侧滑菜单,还支持手势。多种可以自定义的属性。
 * [ECSlidingViewController](https://github.com/ECSlidingViewController/ECSlidingViewController) - 侧滑菜单。
 * [JASidePanels](https://github.com/gotosleep/JASidePanels) - 侧滑菜单,有左右菜单，有pop功能，支持手势侧滑,本人使用中：简单。
 * [animated-tab-bar](https://github.com/Ramotion/animated-tab-bar) - 让 Tabbar items能显示萌萌的动画。
 * [tabbar图标动画](http://code.cocoachina.com/detail/284346) - tabbar上图标的动画实现，[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。
 * [SideMenu](https://github.com/Yalantis/Side-Menu.iOS/tree/master/SideMenu) - swift实现，一款带动画效果可定制 Slide Menu，可以学习其动画实现思路。P.S. 对于Hamburger式菜单，虽然很常用，不过，苹果并不鼓励使用，甚至有开发小组对其弊病用自家上线应用前后数据对比进行了抨击。
 * [RESideMenu](https://github.com/romaonthego/RESideMenu) - 侧开菜单，qq类似。
 * [JHMenuTableViewDemo](https://github.com/Jiahai/JHMenuTableViewDemo) - 仿网易邮箱列表侧滑菜单。
 * [SlideMenuView](https://github.com/xudafeng/SlideMenuView) - 炫酷侧滑菜单布局框架，[Android版本的一致实现](Android 版本的一致实现请见：https://github.com/xudafeng/SlidingMenu)。
 * [QQConfiguration](https://github.com/shinept/QQConfiguration) - swift，QQ-iPhone端框架，左侧菜单栏拖动手势。
 * [KGFloatingDrawer](https://github.com/KyleGoddard/KGFloatingDrawer) - 侧滑菜单，qq类似，KyleGoddard/KGFloatingDrawer O网页链接：一款适合于大屏手机或平板的浮动抽屉式导航界面组件。效果很赞- 侧开菜单，qq类似（与RESideMenu类似）。
 * [AIFlatSwitch](https://github.com/cocoatoucher/AIFlatSwitch) - 一款带平滑过渡动画的 Switch 组件类，类相同风格的 Menu/Back[HamburgerButton](https://github.com/fastred/HamburgerButton),类似相同风格的 Menu/Close[hamburger-button](https://github.com/robb/hamburger-button).
 * [JHChainableAnimations](https://github.com/jhurray/JHChainableAnimations) - 在应用中采用链式写出酷炫的动画效果, 使代码更加清晰易读，利用block实现的链式编程 。
 

##### 其他动画
 * [popping](https://github.com/schneiderandre/popping) - popping是一个POP 使用实例工程 
 * [SinaMenuView](https://github.com/xhzengAIB/SinaMenuView) - 用POP动画引擎写的Sina微博的Menu菜单。
 * [MMTweenAnimation](https://github.com/adad184/MMTweenAnimation) - facebook POP的自定义动画扩展(基于POPCustomAnimation) 提供10种函数式动画。
 * [ZQLRotateMenu](https://github.com/pingguo-zangqilong/ZQLRotateMenu) - 这是一个旋转视图的选择器。
 * [CoolLoadAniamtion](https://github.com/pingguo-zangqilong/CoolLoadAniamtion) - 一个简单但是效果不错的loading动画。
 * [SequenRotateAnimation](https://github.com/pingguo-zangqilong/SequenRotateAnimation) - 一个简单的loading次序动画。
 * [SYAppStart](https://github.com/441088327/SYAppStart) - App启动插画的自定义过度。
 * [VJDeviceSpecificMedia](https://github.com/victorjiang/UIImage-VJDeviceSpecificMedia/) - [如何根据设备选择不同尺寸的图片](http://www.imooc.com/wenda/detail/249271) 可以通过设置不同尺寸设备的LaunchImage，来使得App适配这些设备，要是在不同不同尺寸设备上使用不同大小的图片，则需要在代码中一一判断，然后加载。 
 * [RMParallax](https://github.com/michaelbabiy/RMParallax) - RMParallax是一个app启动页引导开源项目，除了细微的翻页视差效果，描述文本的过渡也非常美观（版本新特性）。
 * [ADo_GuideView](https://github.com/Nododo/ADo_GuideView) - 转动的用户引导页(模仿网易bobo) 因为没有从app包里抓到@3x的图片,建议在iPhone5模拟器运行,保证效果~ （版本新特性）。
* [CoreNewFeatureVC](https://github.com/nsdictionary/CoreNewFeatureVC) - 版本新特性（引导页），1.封装并简化了版本新特性启动视图！2.添加了版本的本地缓存功能，3.集成简单，使用方便，没有耦合度，4.支持block回调。
 * [Spring](https://github.com/MengTo/Spring) - Spring是一个Swift编写的开源库，可简化Swift编写的iOS动画。支持shake、pop、morph、squeeze、wobble、swing、flipX、flipY、fall、squeezeLeft、squeezeRight以及squeezeDown等多种动画形式，用 IBDesignable 让使用者可以在 Xcode 中快速设置动画效果。
 * [KYBezierBounceView](https://github.com/KittenYang/KYBezierBounceView) - 手势控制贝塞尔曲线，取消手势贝塞尔曲线会有反弹效果。
 * [cadisplaylinkanduibezierpath](http://kittenyang.com/cadisplaylinkanduibezierpath/) - CADisplayLink结合UIBezierPath的神奇妙用。
 * [KYCuteView](https://github.com/KittenYang/KYCuteView) - 实现类似QQ消息拖拽消失的交互+GameCenter的浮动小球效果，[分析](http://kittenyang.com/drawablebubble/)。
 * [KYWaterWaveView](https://github.com/KittenYang/KYWaterWaveView) - 一个内置波浪动画的UIView，里面有鱼跳跃水溅起来的效果。
 * [KYPingTransition](https://github.com/KittenYang/KYPingTransition) - 实现圆圈放大放小的转场动画，可以根据自己的需要使用Paper中的弹性效果，有Material风格。
 * [KYNewtonCradleAnimiation](https://github.com/KittenYang/KYNewtonCradleAnimiation) - 牛顿摆动画。
 * [LayerPlayer](https://github.com/scotteg/LayerPlayer) - 一款全面展示核心动画 API 示例项目（上架应用）。包括 CALayer, CAScrollLayer, CATextLayer, AVPlayerLayer, CAGradientLayer, CAReplicatorLayer, CATiledLayer, CAShapeLayer, CAEAGLLayer, CATransformLayer, CAEmitterLayer 等使用的互动演示。
 * [JGTransitionCollectionView](https://github.com/JayGajjar/JGTransitionCollectionView) - swift，基于集合视图扩展实现完成自动布局及单元项 Flip式动画效果（效果很赞）。组件使用方便、自然（只需设置集合视图数据源的标准方式即可）。
 * [KYShareMenu](https://github.com/KittenYang/KYShareMenu) - 带弹性动画的分享菜单。
 * [Context-Menu.iOS](https://github.com/Yalantis/Context-Menu.iOS) - 可以为app的菜单添加漂亮的动画内容，可自定义icon，并可根据自己的喜好设计单元格和布局。
 * [DeformationButton](https://github.com/LuciusLu/DeformationButton) - 一个简单的变换形状动画按钮。
 * [UnReadBubbleView](https://github.com/heroims/UnReadBubbleView) - UnReadBubbleView是一个能够拖拽并拉长的气泡视图。拖拽到一定的长度会消失，可以通过系数设置来控制拖拽的长度。气泡也支持多种属性设置。 
 * [PPDragDropBadgeView](https://github.com/smallmuou/PPDragDropBadgeView) - 实现了类似于QQ 5.0 水滴拖拽效果. 支持iOS 5.0+ ARC，气泡能够带有数字标识，同时支持消失block方法。消失时还带有消失效果动画。
 * [GiftCard-Implementation](https://github.com/MartinRGB/GiftCard-Implementation) - 购买的炫酷动画。
 * [iCarousel](https://github.com/nicklockwood/iCarousel) - iCarousel是一个类，它继承于UIView。用于简化实现各种类型的旋转木马(分页滚动视图）。
 * [HotGirls](https://github.com/zangqilong198812/HotGirls) - 卡片动画。

========
#### 网络相关
##### 网络连接
* [AFNetworking](https://github.com/AFNetworking/AFNetworking) - ASI不升级以后，最多人用的网络连接开源库，[iOS网络编程之AFNetworking使用](http://www.superqq.com/blog/2014/11/07/ioswang-luo-bian-cheng-zhi-afnetworkingshi-yong/),[iOS开发下载文件速度计算](http://www.superqq.com/blog/2015/01/29/ioskai-fa-xia-zai-wen-jian-su-du-ji-suan/)。
* [Alamofire](https://github.com/Alamofire/Alamofire) - Alamofire是AFNetworking的作者mattt新写的网络请求的swift库。
* [YTKNetwork](https://github.com/yuantiku/YTKNetwork) - 是基于 AFNetworking 封装的 iOS网络库，提供了更高层次的网络访问抽象。相比AFNetworking，YTKNetwork提供了以下更高级的功能：按时间或版本号缓存网络请求内容、检查返回 JSON 内容的合法性、文件的断点续传、批量的网络请求发送、filter和插件机制等。
* [LxFTPRequest](https://github.com/DeveloperLx/LxFTPRequest) - 支持获取FTP服务器资源列表，下载/上传文件，创建/销毁ftp服务器文件/目录，以及下载断点续传，下载/上传进度，自动判断地址格式合法性跟踪等功能！国人开发，QQ：349124555。
* [WTRequestCenter](https://github.com/swtlovewtt/WTRequestCenter) - 方便缓存的请求库，提供了方便的HTTP请求方法，传入请求url和参数，返回成功和失败的回调。 UIKit扩展提供了许多不错的方法，快速缓存图片，图片查看，缩放功能， 颜色创建，设备UUID，网页缓存，数据缓存等功能。 无需任何import和配置，目前实现了基础需求。
* [MMWormhole](https://github.com/mutualmobile/MMWormhole) - Message passing between iOS apps and extensions 2个iOS设备之间通信。 
* [socket.io-client-swift](https://github.com/socketio/socket.io-client-swift) - WebSockect 客户端类库。开放的通讯协议，有利于构建强大地跨平台应用。 
* [Transporter](https://github.com/nghialv/Transporter) - swift， 短小、精悍、易用的多文件（并发或顺序）上传和下载传输库。还支持后台运行、传输进程跟踪、暂停/续传/取消/重试控制等功能。 
* [STNetTaskQueue](https://github.com/kevin0571/STNetTaskQueue) - STNetTaskQueue Objective-C 可扩展网络请求管理库。
* [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket) - 在iOS开发中使用socket，一般都是用第三方库AsyncSocket，不得不承认这个库确实很强大，[使用教程](http://www.superqq.com/blog/2015/04/03/ioskai-fa-zhi-asyncsocketshi-yong-jiao-cheng/)。
* [Just](https://github.com/JustHTTP/Just) - 小而美的 HTTP 类。功能简单、直接、完整且健壮性高-- swift。

##### 图像获取
* [SDWebImage](https://github.com/rs/SDWebImage) - SDWebImage 网络图片获取及缓存处理。
* [Kingfisher](https://github.com/onevcat/Kingfisher) - 纯 Swift 实现的类 SDWebImage 库，实现了异步下载和缓存图片。
* [KFSwiftImageLoader](https://github.com/kiavashfaisali/KFSwiftImageLoader) - Swift，一个图像缓存加载库。 
* [FastImageCache](https://github.com/path/FastImageCache) - FastImageCache 网络图片获取及缓存处理，[iOS图片加载速度极限优化—FastImageCache解析](http://www.imooc.com/wenda/detail/247239)。
* [EGOCache](https://github.com/enormego/EGOCache) - 十分知名的第三方缓存类库，可以缓存NSString、UIImage、NSImage以及NSData。除此，如果还可以缓存任何一个实现了<NSCoding>接口的对象。所有缓存的数据都可以自定义过期的时间，默认是1天。EGOCache 支持多线程（thread-safe），[UITableView加载多张照片导致内存上涨的问题](http://www.superqq.com/blog/2014/11/06/ioskai-fa-:uitableviewjia-zai-duo-zhang-zhao-pian-dao-zhi-nei-cun-shang-zhang-de-wen-ti/)。


##### 网络聊天
* [XMPPFramework](https://github.com/robbiehanson/XMPPFramework) - XMPPFramework openfire聊天。
* [环信](http://www.easemob.com/) - 给开发者更稳定IM云功能。8200万用户考验，好用！（暂无及时语音、视频通话）
* [融云](http://www.rongcloud.cn/) - 即时通讯云服务提供商。（暂无及时语音、视频通话）
* [容联云通讯](http://www.yuntongxun.com) - 提供基于互联网通话,视频会议,呼叫中心/IVR,IM等通讯服务。
* [chatsecure](https://github.com/ChatSecure/ChatSecure-iOS) - 基于XMPP的iphone、android加密式聊天软件， [chatsecure官网](https://chatsecure.org/) 。 [iOS代码1](https://github.com/chrisballinger/Off-the-Record-iOS)，[iOS代码2](https://github.com/chrisballinger/ChatSecure-iOS)， [iOS中文版](http://www.cocoachina.com/bbs/read.php?tid=153156)。
* [MessageDisplayKit](https://github.com/xhzengAIB/MessageDisplayKit) - 仿微信聊天，参考JSQMessagesViewController。（国人写）
* [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController) - 聊天 。 
* [SunFlower](https://github.com/HanYaZhou1990/-SunFlower) - 环信聊天demo，比较多功能 。
* [BlueTalk蓝牙聊天](http://code4app.com/ios/BlueTalk%E8%93%9D%E7%89%99%E8%81%8A%E5%A4%A9-%E6%89%8B%E6%9C%BA%E4%B9%8B%E9%97%B4/552b8190933bf0291e8b4748) - 以MultipeerConnectivity为基础， 实现了简单的蓝牙聊天。


##### 网络测试
* [Reachability](https://github.com/tonymillion/Reachability) - 苹果提供过一个Reachability类，用于检测网络状态。但是该类由于年代久远，并不支持ARC。该项目旨在提供一个苹果的Reachability类的替代品，支持ARC和block的使用方式。[iOS网络监测如何区分2、3、4G](http://www.jianshu.com/p/efcfa3c87306)   
* [SimpleCarrie](https://github.com/crazypoo/SimpleCarrie) - 简单的运营商信息获取!。 

##### WebView
* [MGTemplateEngine](https://github.com/mattgemmell/MGTemplateEngine) - MGTemplateEngine比较象 PHP 中的 Smarty、FreeMarker 和 Django的模版引擎，是一个轻量级的引擎，简单好用。只要设置很多不同的HMTL模版，就能轻松的实现一个View多种内容格式的显示，对于不熟悉HTML或者减轻 工作量而言，把这些工作让设计分担一下还是很好的，也比较容易实现设计想要的效果。
* [NJKWebViewProgress](https://github.com/ninjinkun/NJKWebViewProgress) - 一个 UIWebView 的进度条接口库,UIWebView 本身是不提供进度条的。 
* [GTMNSString-HTML](https://github.com/siriusdely/GTMNSString-HTML) - 谷歌开源的用于过滤HTML标签。 

========
#### Model
* [JSONKit](https://github.com/johnezang/JSONKit) - JSONKit库是非常简单易用而且效率又比较高的，重要的JSONKit适用于ios 5.0以下的版本,使用JSONKit库来解析json文件，只需要下载JSONKit.h 和JSONKit.m添加到工程中；然后加入libz.dylib即可。
* [JSONModel](https://github.com/icanzilb/JSONModel) - 解析服务器返回的Json数据的库,[JSONModel源码解析一](http://www.jianshu.com/p/3d795ea37835)。
* [Mantle](https://github.com/Mantle/Mantle) - Mantle主要用来将JSON数据模型化为OC对象, 大系统中使用。[为什么选择Mantle](http://www.iwangke.me/2014/10/13/Why-Changba-iOS-choose-Mantle/)。
* [RFJModel](https://github.com/refusebt/RFJModel) - RFJModel是一个IOS类库，可以将JSON字典自动装填到OBJC对象。相比JSONModel有一些非常好的特性，使用上也比较简单。
* [XMLDictionary](https://github.com/nicklockwood/XMLDictionary) - ios与mac os平台下xml与NSDictionary相互转化开源类库。
* [MJExtension](https://github.com/CoderMJLee/MJExtension) - 用于json转model进行使用，转换效率很高，使用也比较简单，只要前后台约定好，json直接就转成了model。
* [DDModel](https://github.com/openboy2012/DDModel) - 快速搭建项目Model层，支持ORM映射关系，能从JSON/XML直接实例一个Model对象。支持SQLite本地数据持久化，封装了HTTP， 减少HTTP代码与UIViewController的代码耦合，支持Cache；类似RESTKit、Mantle的功能；使用该类库以后简化了网络层的开发工作，把更多的精力放在UI上面；目前只支持GET/POST方法的请求。使用到的第三方库有：1.SQLitePersistentObject; 2.JTObjectMapping; 3.AFNetworking; 4.XMLDictionary;

========
#### 其他
* [DateTimeKit](https://github.com/exsortis/DateTimeKit) - 一个超赞的时间处理的库，Joda-Time ！ 他能帮你轻松处理时区，处理时间加减，计算到期时间等等场景下的问题。
* [SwiftDate](https://github.com/malcommac/SwiftDate) - 特别完整、强大的日期时间操作管理类库。它几乎涵盖了已知开源日期类库所有优秀特性。 他能帮你轻松处理时区，处理时间加减，计算到期时间等等场景下的问题。
* [iOS私有API](https://github.com/nst/iOS-Runtime-Headers) - 私有API，绿色 == public，红色 == private，蓝色 == dylib。
* [iOS源代码](http://opensource.apple.com/source/CF/) - iOS源代码。
* [libfacedetection](https://github.com/ShiqiYu/libfacedetection) - C++ 人脸识别 包含正面和多视角人脸检测两个算法.优点:速度快(OpenCV haar+adaboost的2-3倍), 准确度高 (FDDB非公开类评测排名第二），能估计人脸角度。 
* [Slidden](https://github.com/Brimizer/Slidden) - 一个老外开源的开发自定义键盘的库，利用这个开源库，可以方便的配置键位、颜色以及键位对应的图片。
* [TPKeyboardAvoiding](https://github.com/michaeltyson/TPKeyboardAvoiding) - 用户键盘弹出自动计算高度，进行屏幕滚动操作。
* [CDPMonitorKeyboard](http://d.cocoachina.com/code/detail/298267) - CDPMonitorKeyboard封装,可以解决输入视图(例如textField,textView等)被键盘覆盖问题，并可设置高于键盘多少。 
* [自动监听键盘高度](http://code.cocoachina.com/detail/297973/%E8%87%AA%E5%8A%A8%E7%9B%91%E5%90%AC%E9%94%AE%E7%9B%98%E9%AB%98%E5%BA%A6/) - 自动监听键盘高度，初始界面，输入框在屏幕最下方，当键盘出现时，输入框随即移动到键盘上方。 
* [SYKeyboardTextField](https://github.com/441088327/SYKeyboardTextField) - SYKeyboardTextField 是一个轻巧,简单,非侵入式的键盘附随输入框! 采用Swift编写。
* [BlocksKit](https://github.com/zwaldowski/BlocksKit) - block框架，为 OC 常用类提供了强大的 Block 语法支持，使得编写 OC 代码变得舒适、快速、优雅。
* [KVOController](https://github.com/facebook/KVOController) - 在项目中有使用 KVO ，那么 KVOController 绝对是个好选择。它是 facebook 开源的一个 KVO 增强框架。 
* [appirater](https://github.com/arashpayan/appirater) - 用于提醒用户给你的 APP 打分的工具。
* [MotionKitr](https://github.com/MHaroonBaig/MotionKitr) - 为核心运动框架（The Core Motion framework）提供友好的类库封装，以更方便使用三轴陀螺仪和加速感应器特性。
* [Review Monitor](https://launchkit.io/reviews/) -  第一时间自动推送 Apple Store 的用户评论到你的邮件箱或者 Slack，第一时间跟进用户反馈，打造优秀 App 必备工具！类似的有：App annie 的类似功能。
* [WBWebViewConsole](https://github.com/Naituw/WBWebViewConsole) - 类似微博iPhone客户端的 “调试选项” 吗？把其中的 “内置浏览器网页调试” 开源在 Github 上了。
* [ios-good-practices](https://github.com/futurice/ios-good-practices) - ios-good-practices iOS 开发最佳实践。
* [iOS开发最佳实践](http://ios.jobbole.com/81830/) - iOS 开发最佳实践 -- 中文。
* [TodayExtensionSharingDefaults](http://code.cocoachina.com/detail/232160) - TodayExtensionSharingDefaults是一个iOS 8 Today扩展示例，可以使用NSUserDefaults与其containing app分享数据。
* [QRCodeReader.swift](https://github.com/yannickl/QRCodeReader.swift) - QRCodeReader.swift一款简单的 QR 二维码阅读组件及示例，提供前后相机切换功能。
* [QRCatcher](https://github.com/100mango/QRCatcher) - 一个简洁美观的二维码扫描应用， [iOS学习：AVFoundation 视频流处理--二维码扫描](https://github.com/100mango/zen/blob/master/iOS%E5%AD%A6%E4%B9%A0%EF%BC%9AAVFoundation%20%E8%A7%86%E9%A2%91%E6%B5%81%E5%A4%84%E7%90%86/iOS%E5%AD%A6%E4%B9%A0%EF%BC%9AAVFoundation%20%E8%A7%86%E9%A2%91%E6%B5%81%E5%A4%84%E7%90%86%20.md)。
* [Parsimmon](https://github.com/ayanonagon/Parsimmon) - swift，小而美的语言学类库封装工具包。提供分词、标记词性、词形归并、朴素贝页斯分类、决策树等自然语言分析小工具。P.S. 英语分词效果好于中文，感兴趣的同学可以针对中文做一些优化开发。参考译文 NSHipster - [NSLinguistic​Tagger](http://nshipster.cn/nslinguistictagger/)。
* [Password-keyboard](https://github.com/liuchunlao/Password-keyboard) - 随机变换数字位置的密码键盘。 模仿银行类应用在付款时输入的随机密码键盘。
* [MKMapView-Extension](https://github.com/SemperIdem/MKMapView-Extension) - 这是关于 MKMapView 写的一个基于swift的扩展，可以扩展 MKMapView 的相关功能，减少复用代码量。
* [SemverKit](https://github.com/nomothetis/SemverKit) - 针对符合『语义化版本规范 2.0.0』版本号的解析、比较运算类库。不仅支持 Major, Minor, Patch，还支持 Alpha 和 Beta 预发布版本，以及相应地递增运算扩展。
* [SwiftValidator](https://github.com/jpotts18/SwiftValidator) - 基于规则的输入验证类库。项目良好的面向对象设计思想，使规则的扩展及自定义非常方便。更专业的规则引擎（甚至是基于自然语言的规则配置）解决方案，比如：开源的 Drools，商用的 ILOG 等。
* [Tesseract-OCR-iOS](https://github.com/gali8/Tesseract-OCR-iOS) - 有关OCR文字识别项目。
* [iOS-Categories](https://github.com/shaojiankui/IOS-Categories) - 收集了许多有助于开发的iOS扩展,各种category。
* [DKNightVersion](https://github.com/Draveness/DKNightVersion) - 用最快的方式给你的应用加上夜间和白天的切换效果。 
* [TouchVisualizer](https://github.com/morizotter/TouchVisualizer) - 实用的多点触摸可视化组件。扩展并作用于 UIWindows，结构上提供了简单地针对触摸显示定制，比如触摸点的颜色。
* [RegexKitLite](https://github.com/wezm/RegexKitLite) - 用来处理正则表达式。 

========
#### 数据库
* [FMDB](https://github.com/ccgus/fmdb) - sqlite的工具， [多线程FMDatabaseQueue实例](https://github.com/tangqiaoboy/FmdbSample)，[FMDB数据库的使用演示和封装工具类](https://github.com/liuchunlao/LVDatabaseDemo)。
* [GXDatabaseUtils](https://github.com/Gerry1218/GXDatabaseUtils) - 在FMDB基础上的工具。
* [realm-cocoa](https://github.com/realm/realm-cocoa) - Realm是一个真正为移动设备打造的数据库，同时支持Objective-C和Swfit。Realm宣称其相比Sqlite，在移动设备上有着更好的性能表现。
* [Breeze](https://github.com/andrelind/Breeze) - 用Swift写的一个轻量级的CoreData管理工具，并且还支持iCloud 。
* [AlecrimCoreData](https://github.com/Alecrim/AlecrimCoreData) - Swift，更容易地访问 CoreData 对象封装类库。除了 CRUD，还提供指针定位，强大的排序、筛选，异步数据获取，以及独立线程后台存取数据。

========
#### 缓存处理
* [YTKKeyValueStore](https://github.com/yuantiku/YTKKeyValueStore) - Key-Value存储工具类，[说明](http://tangqiaoboy.gitcafe.io/blog/2014/10/03/opensouce-a-key-value-storage-tool/)。
* [TMCache](https://github.com/tumblr/TMCache) - TMCache 是 Tumblr 开源的一个基于 key/value 的数据缓存类库,可以用于缓存一些临时数据或者需要频繁加载的数据,比如某些下载的数据或者一些临时处理结果。
* [JLKeychain](https://github.com/jl322137/JLKeychain) - 快捷使用keychain存储数据的类，使keychain像NSUserDefaults一样工作。
* [sskeychain](https://github.com/soffes/sskeychain) - SSKeyChains对苹果安全框架API进行了简单封装,支持对存储在钥匙串中密码、账户进行访问,包括读取、删除和设置。

========
#### PDF
* [Reader](https://github.com/vfr/Reader) - Reader可提供类似iBooks的文档导航，支持屏幕旋转和所有方向，并通过密码保护加密PDF文件，支持PDF链接和旋转页面。

========
#### 图像浏览及处理
* [FLAnimatedImage](https://github.com/liric28/FLAnimatedImage) - gif播放处理的工具。
* [CLImageEditor](https://github.com/yackle/CLImageEditor) - 超强的图片编辑库，快速帮你实现旋转，防缩，滤镜等等一系列麻烦的事情。
* [VIPhotoView](https://github.com/vitoziv/VIPhotoView) - 用于展示图片的工具类，因为是个 View，所以你可以放在任何地方显示。支持旋转，双击指定位置放大等。
* [SDPhotoBrowser](https://github.com/gsdios/SDPhotoBrowser) - 仿新浪动感图片浏览器,非常简单易用的图片浏览器，模仿微博图片浏览器动感效果，综合了图片展示和存储等多项功能。 
* [MWPhotoBrowser](https://github.com/mwaterfall/MWPhotoBrowser) - 一个非常不错的照片浏览器，在github的star接近3000个，[解决MWPhotoBrowser中的SDWebImage加载大图导致的内存警告问题](http://www.superqq.com/blog/2015/01/22/jie-jue-mwphotobrowserzhong-de-sdwebimagejia-zai-da-tu-dao-zhi-de-nei-cun-jing-gao-wen-ti/)。
* [core-image-explorer](https://github.com/objcio/issue-21-core-image-explorer) -  Core Image 滤镜处理图片-- swift ，[Core Image 介绍](http://objccn.io/issue-21-6/)。 
* [CoreImageShop](https://github.com/rFlex/CoreImageShop) - CoreImageShop图片滤镜处理-- Mac app that let you create a complete Core Image Filter usable on iOS using SCRecorder。
* [GPUImage](https://github.com/BradLarson/GPUImage) - 处理图片效果。
* [RSKImageCropper](https://github.com/ruslanskorb/RSKImageCropper) - 适用于iOS的图片裁剪器，类似Contacts app，可上下左右移动图片选取最合适的区域。
* [WZRecyclePhotoStackView](http://code.cocoachina.com/detail/232156) - 删除照片交互--WZRecyclePhotoStackView，就是模拟生活中是删除或保留犹豫不决的情形而产生的。 在上滑，下滑的部分，借鉴了[TinderSimpleSwipeCards](https://github.com/cwRichardKim/TinderSimpleSwipeCards)。
* [TimingFunctionEditor](https://github.com/schwa/TimingFunctionEditor) - TimingFunctionEditor用swift编写， 贝塞尔曲线编辑器，编辑后可以预览或拷贝代码片段直接使用。P.S. 该项目采用更简单的依赖管理器 [Carthage](https://github.com/Carthage/Carthage) ，而非常用的 CocoaPods。[Carthage介绍中文](http://www.cocoachina.com/ios/20141204/10528.html)。
* [AAFaceDetection](https://github.com/aaronabentheuer/AAFaceDetection) - AAFaceDetection--swift，简单、实用的面部识别封装库。虽然该技术从 iOS 5 发展，不过真正有趣的应用还不多。。
* [PhotoTweaks](https://github.com/itouch2/PhotoTweaks) - 这个库挺赞的，正好是对图像操作的。
* [Concorde](https://github.com/contentful-labs/Concorde) - swift, Concorde, 一个可用于下载和解码渐进式 JPEG 的库, 可用来改善应用的用户体验。
* [ZoomTransition](https://github.com/tristanhimmelman/ZoomTransition) - swift, 通过手势操控图片的放大、缩小、旋转等自由变化效果的组件及示例。
* [AFImageHelper](https://github.com/melvitax/AFImageHelper) - swift,一套针对 UIImage 和 UIImageView 的实用扩展库，功能包含填色和渐变、裁剪、缩放以及具有缓存机制的在线图片获取。

========
#### 摄像照相视频音频处理
* [SCRecorder](https://github.com/rFlex/SCRecorder) - SCRecorder 短视频录制。
* [VideoPushDemo](https://github.com/pingguo-zangqilong/VideoPushDemo) - 视频剪辑 [视频特效制作1](http://www.jianshu.com/p/3006502912aa) [视频特效制作2](http://www.jianshu.com/p/6313025349a9)。
* [LLSimpleCamera](https://github.com/omergul123/LLSimpleCamera) - A simple, customizable camera control for iOS， 摄像头。
* [EZAudio](https://github.com/syedhali/EZAudio) - EZAudio 是一个 iOS 和 OSX 上简单易用的音频框架，根据音量实时显示波形图，基于Core Audio，适合实时低延迟音频处理，非常直观。[中文介绍](http://segmentfault.com/blog/news/1190000000370957),[官网](http://www.syedharisali.com/about)。
* [ffmpeg](http://ffmpeg.org/) - ffmpeg官网，[FFmpeg在iOS上完美编译](http://www.cocoachina.com/ios/20150514/11827.html)。
* [VCL](http://www.videolan.org/) - VCL官网。 
* [kxmovie](https://github.com/kolyvan/kxmovie) - 使用ffmpeg的影片播放器，[修改说明](http://www.cocoachina.com/bbs/read.php?tid=145575)， [修改代码](https://github.com/kinglonghuang)。
* [ijkplayer](https://github.com/Bilibili/ijkplayer) - B站开源的视频播放器，支持Android和iOS。 
* [StreamingKit](https://github.com/tumtumtum/StreamingKit) - StreamingKit流媒体音乐播放器。 
* [FreeStreamer](https://github.com/muhku/FreeStreamer) - FreeStreamer流媒体音乐播放器，cpu占用非常小。
* [DOUAudioStreamer](https://github.com/douban/DOUAudioStreamer) - DOUAudioStreamer豆瓣的音乐流媒体播放器。
* [fmpro](https://github.com/fmpro/fmpro) - 电台播放器，支持锁屏歌词，支持基本播放流程，歌词展示，后台锁屏播放和控制以及锁屏后封面+歌词，[fmpro_R](https://github.com/jovisayhehe/fmpro_R) 。
* [IPDFCameraViewController](https://github.com/mmackh/IPDFCameraViewController) - 支持相机定焦拍摄、滤镜、闪光、实时边框检测以及透视矫正功能，并有简单易用的API。 
* [SCRecorder](https://github.com/rFlex/SCRecorder) - 酷似 Instagram/Vine 的音频/视频摄像记录器，以 Objective-C 为基础的过滤器框架。 你可以做很多如下的操作：记录多个视频录像片段。删除任何你不想要的记录段。可以使用任何视频播放器播放片段。保存的记录可以在序列化的 NSDictionary 中使用。（在 NSUserDefaults 的中操作）添加使用 Core Image 的视频滤波器。可自由选择你需要的 parameters 合并和导出视频。
* [Cool-iOS-Camera](https://github.com/GabrielAlva/Cool-iOS-Camera) - Cool-iOS-Camera。
* [FastttCamera](https://github.com/IFTTT/FastttCamera) - FastttCamera 快速照相。
* [ICGVideoTrimmer](https://github.com/itsmeichigo/ICGVideoTrimmer) - ICGVideoTrimmer提供提供视频剪切的视图（类似系统相册中浏览视频时顶部那个条状视图）。左右两个边界选择器还能够自定义。
* [IOS录音和播放功能demo](http://d.cocoachina.com/code/detail/285717) - 比较完整的ios录音和播放功能的实现。
* [CameraManager](https://github.com/imaginary-cloud/CameraManager) - 相机管理封装类库。看着极好用的样子----swift。
* [MCAudioInputQueue](https://github.com/msching/MCAudioInputQueue) - 简易录音类，基于AudioQueue的。
* [DraggableYoutubeFloatingVideo](https://github.com/vizllx/DraggableYoutubeFloatingVideo) - 展示像类似Youtube移动应用的那种浏览视频的效果，当点击某视频时能够从右下方弹出一个界面，并且该界面能够通过手势，再次收缩在右下方并继续播放。这是通过AutoLayout设计实现。
* [amr](http://www.penguin.cz/~utx/amr) - 做即时通讯的音频处理，录音文件是m4a，便于web端的音频播放。
* [FSVoiceBubble](https://github.com/f33chobits/FSVoiceBubble) - 一个轻量级播放录音音频的气泡：1.支持短时间的音频播放（支持网络音频）；2.播放时的声波动画；3.自定义包括声波的颜色，气泡的背景等。
* [KRVideoPlayer](https://github.com/36Kr-Mobile/KRVideoPlayer) - 类似Weico的播放器，支持竖屏模式下全屏播放。 

========
#### 响应式框架
* [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) - ReactiveCocoa 受函数响应式编程激发。不同于使用可变的变量替换和就地修改，RAC提供Signals来捕获当前值和将来值（ [使用介绍](http://yulingtianxia.com/blog/2014/07/29/reactivecocoa/) ），[不错的例子](http://iiiyu.com/2014/12/26/learning-ios-notes-thirty-six/),入门好教程：[ReactiveCocoa入门教程：第一部分 ](http://www.cocoachina.com/ios/20150123/10994.html)。
* [ReactiveAnimation](https://github.com/ReactiveCocoa/ReactiveAnimation) - ReactiveCocoa 推出了一个叫 ReactiveAnimation 的子项目，直接用完全用 Swift 来实现了。
* [BeeFramework](https://github.com/gavinkwoe/BeeFramework) -  与ReactiveCocoa类似，[BeeFramework用户指南 v1.0](http://www.lanrenios.com/tutorials/all/2012/1220/641.html)。
* [Objective-Chain](https://github.com/iMartinKiss/Objective-Chain) - Objective-Chain是一个面向对象的响应式框架，作者表示该框架吸收了 ReactiveCocoa 的思想，并且想做得更面向对象一些。


========
#### 消息相关
##### 消息推送客户端
* [SGPushDemo](https://github.com/sagiwei/SGPush/tree/master/SGPushDemo) - 消息推送客户端
* [Orbiter](https://github.com/mattt/Orbiter) - 消息推送客户端:Push Notification Registration for iOS.
* [PushDemo](https://github.com/ios44first/PushDemo) - 客户端消息接收消息代码，[IOS开发之 ---- IOS8推送消息注册](http://blog.sina.com.cn/s/blog_71715bf80102uy2k.html) ， [分分钟搞定IOS远程消息推送](http://my.oschina.net/u/2340880/blog/413584)。

##### 消息推送服务端
 * [javapns源代码](https://code.google.com/p/javapns/downloads/list) - 消息推送的java服务端代码，注意：DeviceToken中间不能有空格。
 * [pushMeBaby](https://github.com/stefanhafeneger/PushMeBaby) - Mac端消息推送端代码，注意：DeviceToken中间要有空格。


##### 通知相关
* [JSQNotificationObserverKit](https://github.com/jessesquires/JSQNotificationObserverKit) - 一款轻量、易用的通知发送及响应框架类库。作者是知名开源项目 JSQMessagesViewController（Objective-C 版即时聊天）的作者 Jesse Squires.
* [GLPubSub](https://github.com/Glow-Inc/GLPubSub) - 一个简短实用的 NSNotificationCenter 的封装。
* [Homeoff](https://github.com/lizyyy/Homeoff) - 用swift写了一个模仿Launcher通知中心快捷方式的应用。支持20个应用，并增加了一个返回到桌面来解放Home键的功能。
* [JDStatusBarNotification](https://github.com/jaydee3/JDStatusBarNotification) - 在状态栏顶部显示通知。可以自定义颜色字体以及动画。支持进度显示以及显示状态指示器。

========
#### 版本新API的Demo
* [iOS7-Sampler](https://github.com/shu223/iOS7-Sampler) - 整合了iOS7.0的一些十分有用的特性，比如：Dynamic Behaviors、碰撞检测、语音合成、视图切换、图像滤镜、三维地图、Sprite Kit（动画精灵）、Motion Effect（Parallax）、附近蓝牙或者wifi搜索连接、AirDrop、运动物体追踪（iPhone 5S以上，需要M7处理器）等等。对于日常的应用开发十分实用。 
* [iOS8-Sampler](https://github.com/shu223/iOS8-Sampler) - 日本的shuさん制作的 iOS8 参考代码集。01.Audio Effects ；02.New Image Filters；03.Custom Filters；04.Metal Basic；05.Metal Uniform Streaming；06.SceneKit；07.HealthKit；08.TouchID；09.Visual Effects；10.WebKit；11.UIAlertController；12.User Notification；13.Pedometer；14.AVKit；15.Histogram；16.Code Generator；17.New Fonts；18.Popover；19.Accordion Fold Transition

========
#### 代码安全与密码
* [ios-class-guard](https://github.com/Polidea/ios-class-guard) - 一个用于混淆iOS的类名、方法名以及变量名的开源库--有人反映编译出来的app运行不了。
* [《Protecting iOS Applications》](https://www.polidea.com/#!heartbeat/blog/Protecting_iOS_Applications)：文章系统地介绍了如何保护iOS程序的代码安全，防止反汇编分析。
* [fishhook](https://github.com/facebook/fishhook) - fishhook是Facebook开源的一个可以hook系统方法的工具。
* [GesturePassword](https://github.com/smilingxinyi/GesturePassword) - 一个iOS手势密码功能实现，iPad/iPhone 都可以用，没有使用图片，里面可以通过view自己添加。keychain做的数据持久化，利用苹果官方KeychainItemWrapper类。操作部分都在controller了。删除直接用一下clear。
* [JMPasswordView](https://github.com/Juuman/JMPasswordView) - 简单实用的手势密码，效果可自行调控。
* [仿密码锁-九宫格](http://code.cocoachina.com/detail/298556/%E4%BB%BF%E5%AF%86%E7%A0%81%E9%94%81-%E4%B9%9D%E5%AE%AB%E6%A0%BC/) - 仿密码锁-九宫格，主要是使用UIButton 手势事件  UIBezierPath画图，解锁失败弹出“密码错误”。
* [CoreLock](https://github.com/nsdictionary/CoreLock) - 本框架是高仿支付宝，并集成了所有功能，并非一个简单的解锁界面展示。个人制作用时1周多，打造解锁终结者框架。
* [LikeAlipayLockCodeView](https://github.com/crazypoo/LikeAlipayLockCodeView) - 高仿支付宝手势解锁（超级版）。

========
#### 测试及调试
* [HeapInspector](https://github.com/tapwork/HeapInspector-for-iOS) - HeapInspector是一个用于检测应用中的内存泄漏的开源调试工具。
* [Crashlytics](http://try.crashlytics.com/) - Crashlytics 崩溃报告 崩溃日志   [使用说明](http://www.infoq.com/cn/articles/crashlytics-crash-statistics-tools) 。
* [UIViewController-Swizzled](https://github.com/RuiAAPeres/UIViewController-Swizzled) - 把你进入的每一个controller的类名打出来,如果看一些特别复杂的项目的时候直接运行demo就可以知道执行次序了。
* [snoop-it](https://code.google.com/p/snoop-it/) - snoop-it比UIViewController-Swizzled好用，代码托管在google上。
* [Versions](https://github.com/zenangst/Versions) - 版本比较小工具。
* [MobileWebPageTest](http://code4app.com/ios/MobileWebPerformanceTest/5465d3e9933bf00c658b4f43) - MobileWebPageTest是用来测试移动网页性能的软件，它可以对页面的加载和渲染过程进行截屏，协助开发者分析出页面性能瓶颈。
* [KKLog](https://github.com/Coneboy-k/KKLog) - 一个日志管理系统。
* [CleanroomLogger](https://github.com/emaloney/CleanroomLogger) - 相当于 CocoaLumberjack 或 Log4j 的 Swift 版本，功能上甚至更强大。另外，源代码中已经内含了完整的 API 文档，使用非常方便。


========
#### AppleWatch
* [Tesla汽车AppleWatch app demo演示](https://github.com/eleks/rnd-apple-watch-tesla) - 通过AppleWatch控制特斯拉汽车，同时可以看到汽车的相关信息，比如剩余电量、可续行里程等，以及解锁/上锁车门、调节司机和乘客的四区域空调温度、开启车辆大灯、定位汽车等。[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。 
* [WatchKit-Apps](https://github.com/kostiakoval/WatchKit-Apps) - WatchKit 开源小项目示例集锦。是不可多得地学习 WatchKit 的示例式教程（1.如何创建一个简单的交互式计数器；2.如何从手表上控制iOS app；3.如何在WatchKit app和iOS app之间共享数据；4.如何创建一个拥有不同背景色的数字时钟；5.展示不同的UI层；6.如何创建支持滑动手势的应用程序。）。 
* [KYVoiceCurve](https://github.com/KittenYang/KYVoiceCurve) - 类似Apple Watch中语音的声音曲线动画。  
* [IGInterfaceDataTable](https://github.com/Instagram/IGInterfaceDataTable) - IGInterfaceDataTable是WKInterfaceTable对象的一个类别，可以让开发者更简单地配置多维数据。该项目使用类似UITableViewDataSource的数据源模式配置Apple Watch表格，而不是将数据结构扁平化成为数组。  
* [Apple Watch开发教程资料汇总](http://www.swiftkiller.com/?p=613) - Apple Watch开发教程资料汇总。
* [Stargate](https://github.com/contentful-labs/Stargate) - 通过 iPhone 桥接实现 Mac 与 Watch 的即时通讯。Stargate 通过封装两个优秀的基础类库 MMWormhole 和 PeerKit 实现高效的通讯应用。--swift


========
#### VPN
* [vpnon](https://github.com/lexrus/vpnon/) - swift的VPN On 的源码和本地化内容都是开放的: [官方网站](https://crowdin.com/project/vpnon)。
* [Hydro.network](https://github.com/CatchChat/Hydro.network) - [Hydro.network 的开发旅程](http://zhowkev.in/2015/03/09/hydro-network-de-kai-fa-lu-cheng/), [gitcafe](https://gitcafe.com/Catch/Hydro.network)。

========
#### 完整项目
* [v2ex](https://github.com/singro/v2ex) - v2ex 的客户端，新闻、论坛。 
* [apps-ios-wikipedia](https://github.com/wikimedia/apps-ios-wikipedia) - apps-ios-wikipedia 客户端。 
* [jetstream-ios](https://github.com/uber/jetstream-ios) - 一款 Uber 的 MVC 框架。它同时提供了多用户实时通讯支持，一旦启动 JetStream 后端服务，通过 WebSocket 协议可以分分钟建立多用户实时通讯应用。
* [DeckRocket](https://github.com/jpsim/DeckRocket) - 在相同 WiFi 网络环境内，通过iPhone 控制并播放 Mac 中的 PDF 文档。
* [ScanBook](https://github.com/JayFang1993/ScanBook) - 扫扫图书:可以扫描条形码查询图书，也可以关键字搜索，遇到合乎你口味的书，还可以看看别人的读书笔记，不同角度去体会。
* [DesignerNewsApp](https://github.com/MengTo/DesignerNewsApp) - Swift 开发的 DesignerNews 客户端，看着美美的！
* [KYWeibo](https://github.com/KittenYang/KYWeibo) - 调用新浪API自己写的第三方微博客户端。
* [DouQu_IOS](https://github.com/li6185377/DouQu_IOS) - 逗趣IOS手机端（一款笑话软件）,拥有完整的功能的手机应用app 。
* [IT江湖iOS客户端](https://github.com/itjhDev/itjh) - IT江湖iOS客户端。
* [Eidolon](https://github.com/artsy/eidolon) - 艺术品拍卖的投标亭平台，用swift与反应式编程框架 ReactiveCocoa。
* [CrazyPuzzle](https://github.com/nonstriater/CrazyPuzzle) - 模仿“看图猜成语”App，功能齐全，配有音效，效果很不错。游戏使用cocoa框架完成，没有使用cocos2d的框架。


========
#### Xcode插件
* [iOS开发进阶，从Xcode开始](http://www.cocoachina.com/special/xcode/) - 学习使用Xcode构建出色的应用程序！
* 在Xcode启动的时候，Xcode将会寻找位于~/Library/Application Support/Developer/Shared/Xcode/Plug-ins文件夹中的后缀名为.xcplugin的bundle作为插件进行加载（运行其中的可执行文件）。[Xcode5 Plugins 开发简介](http://studentdeng.github.io/blog/2014/02/21/xcode-plugin-fun/)  [写个自己的Xcode4插件](http://joeyio.com/ios/2013/07/25/write_xcode4_plugin_of_your_own/)

* [Xcode 4 插件制作入门](http://www.onevcat.com/2013/02/xcode-plugin/) - Xcode 4 插件制作入门:Xcode所使用的所有库都包含在Xcode.app/Contents/的Frameworks，SharedFrameworks和OtherFrameworks三个文件夹下。其中和Xcode关系最为直接以及最为重要的是Frameworks中的IDEKit和IDEFoundation，以及SharedFrameworks中的DVTKit和DVTFoundation四个。
 
* [RTImageAssets](https://github.com/rickytan/RTImageAssets) - 一个 Xcode 插件，用来生成 @3x 的图片资源对应的 @2x 和 @1x 版本。[Asset Catalog Creator](https://itunes.apple.com/app/asset-catalog-creator-free/id866571115?mt=12) 功能强大，能自动生成全部尺寸：包括App Icons、Image Sets、Launch Screens Generator。

* [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode) - 一个Xcode插件，build后，随手打开一个你之前的项目，然后在任意一个方法上面连按三下"/"键盘，就ok了。

* [java2Objective-c](https://github.com/google/j2objc) - Google公司出得java转Obje-C转换工具，转换逻辑，不转换UI。

* [RegX](https://github.com/kzaher/RegX) - 专治代码强迫症的 Xcode 插件，使用 Swift 和 Objective-C 编写。其用竖向对齐特定源代码的元素，使得代码更易读和易理解。[说明](http://www.cocoachina.com/ios/20141224/10743.html) ； 菜单：xcode——》Edit-》Regx 。

* [KSImageNamed](https://github.com/ksuther/KSImageNamed-Xcode) - 自动完成，特别是如果你正在写Objective-C，如果Xcode能自动完成文件名难道不会很伟大吗？比如图像文件的名称。

* [FuzzyAutocomplete](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin) - Xcode的实现自动完成还不完美，此插件能给出你所期望或想要的建议，设置：xcode-》Editor-》FuzzyAutocomplete-》plugin settings。

* [GitDiff](https://github.com/johnno1962/GitDiff) - Xcode的代码编辑器的一个微妙的补强，加上了足够的可见信息以了解上次git提交以来发生了什么变化，设置：xcode-》Edit-》GitDiff。

* [XToDo](https://github.com/trawor/XToDo) - 这个插件不仅凸显TODO，FIXME，???，以及！！！注释，也在便利列表呈现他们。 菜单：xcode-》view-》snippets;   调出列表显示: xcode-》view-》ToDo List ： ctrl + T 。 

* [Backlight](https://github.com/limejelly/Backlight-for-XCode) - 突出显示当前正在编辑的行。菜单：xcode-》view-》Backlight 。

* [CocoaPods](https://github.com/kattrali/cocoapods-xcode-plugin) - 该CocoaPods的插件增加了一个CocoaPods菜单到Xcode的产品菜单。如果你不喜欢命令行，那么你一定会喜欢这个插件。 [用CocoaPods做iOS程序的依赖管理 ]( 
http://tangqiaoboy.gitcafe.io/blog/2014/05/25/use-cocoapod-to-manage-ios-lib-dependency/)。

* [Peckham](https://github.com/markohlebar/Peckham) - 添加import语句比较麻烦，此插件 按Command-Control-P，给出的选项列表中选择要的头文件。先要安装[Alcatraz](http://alcatraz.io/) ,在终端输入： **curl -fsSL https://raw.github.com/supermarin/Alcatraz/master/Scripts/install.sh | sh** ； 重启xcode-》window-》Package Manager：搜索 **Peckham** 安装，打开Peckham.xcodeproj，编译 Peckham target，重启Xcode 。

* [Auto-Importer](https://github.com/lucholaf/Auto-Importer-for-Xcode) - Auto-Importer是一个自动导入类对应的头文件的Xcode插件。

* [Alcatraz](http://alcatraz.io/) -使用Alcatraz来管理Xcode插件 [使用说明](http://tangqiaoboy.gitcafe.io/blog/2014/03/05/use-alcatraz-to-manage-xcode-plugins/) 。

* [KSHObjcUML](https://github.com/kimsungwhee/KSHObjcUML) -KSHObjcUML 是一个 Objective-C 类引用关系图的 Xcode 插件。 

* [ColorSense-for-Xcode](https://github.com/omz/ColorSense-for-Xcode) - 颜色插件，安装之后，就不用根据RGB选择颜色，直接从取色板中取颜色，会自动补齐RGB代码。。

* [10款提高iOS开发效率的XCode插件](http://www.imooc.com/wenda/detail/237132) - 10款提高iOS开发效率的XCode插件：1. XcodeColors；5. ACCodeSnippetRepository；10. Dash for Xcode。 

* [ZLGotoSandboxPlugin](https://github.com/MakeZL/ZLGotoSandboxPlugin) - 支持Xcode快捷键了跳转当前应用沙盒了！快捷键是 Shift+Common+w。 

* [XcodeSwiftSnippets](https://github.com/burczyk/XcodeSwiftSnippets) - XcodeSwiftSnippets, 提供了很多可在 Xcode 上使用的 Swift 代码片段, 通过自动补全的方式极大的提高了开发效率， [另外还有 Objective-C 版的](https://github.com/Xcode-Snippets/Objective-C)。 


========
#### 美工资源
* [TWG_Retina_Icons](https://github.com/markohlebar/Peckham) - 一套支持 Retina 高清屏的 iPhone 免费图标集。
* [ASCIImage](https://github.com/cparnot/ASCIImage) - 使用 NSString 创建 image，[说明](http://cocoamine.net/blog/2015/03/20/replacing-photoshop-with-nsstring/)。
* [my-sketch-colors](https://github.com/RayPS/my-sketch-colors) - 配色。
* [Font Awesome](http://www.imooc.com/wenda/detail/250367) - Font Awesome：一套绝佳的图标字体库和CSS框架，详细的安装方法请参考[官方网站](http://fortawesome.github.io/Font-Awesome/icons/)[中文网站](http://fontawesome.dashgame.com/),[GitHub地址](https://github.com/FortAwesome/Font-Awesome) 。


#### 其他资源
* [githuber](http://githuber.info/#/index) - 最好用的GitHub人才搜索工具。   
* [codatlas](https://www.codatlas.com) - 源代码搜索利器。
* [searchcode](https://searchcode.com/) - 源代码搜索利器：来自悉尼的代码搜索引擎汇聚了 Github, Bitbucket, Sourceforge...等多家开源站点超20万个项目、180亿行源代码，能以特殊字符、语言、仓库和源方式从90多种语言找到函数、API的真实代码。
* [kitematic](https://github.com/kitematic/kitematic) - Mac 上使用 Docker 最简单的方案。 



========
#### 开发资源
##### 开发资料
* [豆瓣iOS开源库列表](http://www.douban.com/note/276160185/?type=like) - 豆瓣iOS开源库列表，很多开源项目。
* [iOS-Core-Animation-Advanced-Techniques](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques) - 中文版iOS 高级动画技术。 
* [iOS开发的一些奇巧淫技1](http://www.jianshu.com/p/50b63a221f09) - TableView不显示没内容的Cell怎么办; 键盘事件：[IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager);  app不流畅:[KMCGeigerCounter](https://github.com/kconner/KMCGeigerCounter);  CoreData用起来好烦:[MagicRecord](https://github.com/magicalpanda/MagicalRecord);  CollectionView实现悬停的header:[CSStickyHeaderFlowLayout](https://github.com/jamztang/CSStickyHeaderFlowLayout)。
* [iOS开发的一些奇巧淫技2](http://www.jianshu.com/p/08f194e9904c) -  用一个pan手势来代替UISwipegesture的各个方向、拉伸图片、播放GIF、上拉刷新、把tableview里cell的小对勾的颜色改变、navigationbar弄成透明的而不是带模糊的效果、改变uitextfield placeholder的颜色和位置。
* [cocoapods安装指南](http://code4app.com/article/cocoapods-install-usage) - cocoapods安装指南。
* [RemoteControl](https://github.com/johnno1962/Remote) - Control your iPhone from inside Xcode for end-to-end testing 。
* [MVVM 介绍](http://objccn.io/issue-13-1/) - 替换MVC的开发模式。
* [第三方接口](http://apistore.baidu.com/astore/index) - 基本所有第三方接口都在这，再也不用那么麻烦去找了。

###### swift
* [Swift中文指南](https://github.com/numbbbbb/the-swift-programming-language-in-chinese) - 中文版Apple官方Swift教程《The Swift Programming Language》，[老码版本](http://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/)  [历史版本更新说明](http://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/chapter1/03_revision_history.html)。 
* [swifttoolbox](http://www.swifttoolbox.io/) -  swifttoolbox swift开发的开源库汇总。 
* [SwiftGuide](https://github.com/ipader/SwiftGuide) -  这份指南汇集了Swift语言主流学习资源，并以开发者的视角整理编排-- 非常不错，值得推荐。
* [Swift开源项目精选](https://github.com/ipader/SwiftGuide/blob/master/Featured.md) - Swift开源项目精选--推荐，每周都有更新。
* [Awesome Swift](https://swift.zeef.com/robin.eggenkamp) - 一个收集了很多 Swift 开发资源的网站。

##### 他人开源总结
* [code4app](http://www.code4app.com/) - 最多国人用的代码库。
* [cocoachina](http://code.cocoachina.com/) - 国内最热门的iOS社区的代码库。
* [awesome-ios](https://github.com/vsouza/awesome-ios) - 一个老外整理的，[中文版](http://app.memect.com/doc/ios.html)。
* [awesome-ios-ui](https://github.com/cjwirth/awesome-ios-ui) - 收集了不少 iOS UI/UX 库, 包含了很多酷炫的动画效果。
* [ios-cosmos](http://ios-cosmos.com/) - The iOS Cosmos：收录了IOS绝大部分的开源框架和工具。
* [Awesome Haskell资料大全](https://haskell.zeef.com/konstantin.skipor#block_28362_basics) -    Awesome Haskell 资料大全：框架，库和软件。
* [Cosmos](http://ios-cosmos.com) - The iOS Cosmos：收录了IOS绝大部分的开源框架和工具。
* [cocoacontrols](http://cocoacontrols.com) -  收集了很多UI控件效果代码，缺点是需要翻墙，而且代码分类不够好。
* [lexrus](https://github.com/lexrus) -  lexrus国内出名的iOS开源coder，非常库的label动画、textfield动画。
* [open-source-ios-apps](https://github.com/dkhamsing/open-source-ios-apps) - iOS App集合，分：swift与Objective-C--国外人整理。 

* [适合iOS开发者的15大网站推荐](http://www.csdn.net/article/2015-03-04/2824108-ios-developers-sites) -  适合 iOS 开发者的 15 大网站推荐 --- 英文网站。

* [Objective-C GitHub 排名前 100 项目简介](https://github.com/Aufree/trip-to-iOS/blob/master/Top-100.md) -  主要对当前 GitHub 排名前 100 的项目做一个简单的简介, 方便初学者快速了解到当前 Objective-C 在 GitHub 的情况。 

* [Github-iOS备忘](http://github.ibireme.com/github/list/ios/) -整理了比较常用的iOS第三方组件，以及github上的统计。


##### 中文开发博客列表
 * [唐巧整理](https://github.com/tangqiaoboy/iOSBlogCN) - 猿题库唐巧整理。


博客地址 | RSS地址
----- | -----
[南峰子的技术博客](http://southpeak.github.io/) | 南峰子的技术博客。
[唐巧的技术博客](http://blog.devtang.com) | <http://blog.devtang.com/atom.xml>
[OneV's Den](http://onevcat.com) | <http://onevcat.com/atom.xml>
[破船之家](http://beyondvincent.com) | <http://beyondvincent.com/atom.xml>
[NSHipster](http://nshipster.cn) | <http://nshipster.cn/feed.xml>
[Limboy 无网不剩](http://blog.leezhong.com/) | <http://feeds.feedburner.com/lzyy>
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
