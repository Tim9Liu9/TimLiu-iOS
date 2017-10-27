# TimLiu-iOS
[![Test Status](https://travis-ci.org/douban/rexxar-ios.svg?branch=master)](https://travis-ci.org/douban/rexxar-ios)
[![Language](https://img.shields.io/badge/language-ObjC-blue.svg)](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)  

[Swift版本点击这里](https://github.com/Tim9Liu9/TimLiu-iOS/blob/master/Swift.md)
欢迎加入QQ群交流:  594119878

### About

A curated list of iOS objective-C ecosystem.

### How to Use

- Simply press <kbd>command</kbd> + <kbd>F</kbd> + <kbd>"xxx@"</kbd> to search for a keyword
- Go through our *Content Menu*

### Feedback

期待大家和我们一起共同维护，同时也期望大家随时能提出宝贵的意见（直接提交issues即可）。请广大网友只按照目录结构（即使目录结构有问题）添加三方库，并提交pull request。目录问题大家提出issues后楼主会及时更改的。

###  目录
- [参考@](#参考)
- [版本管理@](#版本管理)
- [完整App@](#完整App)
- [框架@](#框架)
  - [react@](#react)
  - [响应式@](#响应式)
  - [framework@](#framework)
  - [混合开发@](#混合开发)
  - [样例App@](#样例App)
- [服务端@后台@](#服务端#后台)
- [网络@](#网络)
  - [网络请求@](#网络请求)
  - [socket@](#socket)
  - [网络下载@](#网络下载@)
  - [图像获取@](#图像获取)
  - [网络聊天@](#网络聊天)
  - [网络测试@](#网络测试)
  - [网页框架@](#网页框架)
  - [网络解析@](#网络解析)
      - [CSV](#csv)
      - [JSON@](#json)
      - [XML&HTML@](#xml--html)
      - [Other Parsing@](#other-parsing)
- [数据存储@](#数据存储)
  - [缓存处理@](#缓存处理)
  - [序列化@](#序列化)
  - [coreData@](#coreData)
- [动画@](#动画)
  - [侧滑与右滑返回手势@](#侧滑与右滑返回手势)
  - [转场@](#转场)
- [多媒体@](#多媒体)
  - [GIF@](#GIF)
  - [VR@](#VR)
  - [AR@](#AR)
  - [二维码@](#二维码)
  - [PDF@](#PDF)
  - [流媒体@](#流媒体)
  - [音频@](#音频)
  - [视频@](#视频)
    - [视频播放@](#视频播放)
    - [视频处理@](#视频处理)
    - [视频录制@](#视频录制)
    - [视频剪切@](#视频剪切)
    - [弹幕@](#弹幕)
    - [直播@](#直播)
- [图像@](#图像)
  - [拍照@](#拍照)
  - [图像处理@](#图像处理)
  - [图像浏览@](#图像浏览)
  - [图像缓存@](#图像缓存)
  - [图像识别@](#图像识别)
  - [图像圆角@](#图像圆角)
- [数据结构/算法@](#数据结构/算法)
- [上架@](#上架)
- [Xcode8插件@](#Xcode8插件)
- [动态更新@](#动态更新)
- [App更新提示@](#App更新提示)
- [UI@](#UI)
  - [综合UI@](#综合UI)
  - [日历三方库@](#日历三方库)
  - [下拉刷新@](#下拉刷新)
  - [模糊效果@](#模糊效果)
  - [图表@](#图表)
  - [颜色@](#颜色)
  - [列表相关@](#列表相关)
    - [TableView@](#TableView)
    - [TableView适配@](#TableView适配)
    - [CollectionView@](#CollectionView)
  - [对话交互@](#对话交互)
    - [隐藏与显示@](#隐藏与显示)
    - [HUD与Toast@](#HUD与Toast)
    - [对话框@](#对话框)
    - [Pop@](#Pop)
    - [通知相关@](#通知相关)
  - [状态栏@](#状态栏)
  - [导航栏@](#导航栏)
  - [设置@](#设置)
  - [Switch@](#Switch)
  - [Label@](#Label)
  - [Search@](#Search)
  - [主题@](#主题)
  - [电影选座@](#电影选座)
  - [瀑布流@](#瀑布流)
  - [菜单@](#菜单)
  - [Tabbar@](#Tabbar)
  - [进度@](#进度)
  - [小红点@](#小红点)
  - [page@](#page)
  - [轮播@](#轮播)
  - [选择器@](#选择器)
  - [购物车@](#购物车)
  - [引导@](#引导)
  - [其他UI@](#其他UI)
- [工具@](工具@)
  - [提醒用户评分@](@提醒用户评分)
  - [压缩解压@](@压缩解压)
  - [Category@](#Category)
  - [Color@](#Color)
  - [Github相关@](#Github相关)
  - [键盘@](#键盘)
- [文本@](#文本)
  - [文本输入@](#文本输入)
  - [富文本@](#富文本)
  - [字体@](#字体)
- [多线程@](#多线程)
- [ipad@](#ipad)
- [通讯@](#通讯)
- [AutoLayout@](#AutoLayout)
- [学习资料@](#学习资料)
  - [播客@](#播客)
  - [他人开源总结@](#他人开源总结)
  - [开发博客列表@](#开发博客列表)
  - [学习笔记、书籍@](#学习笔记、书籍)
  - [CodeLiararyWebSite@](#CodeLiararyWebSite)
  - [设计@](#设计)
  - [好的文章@](#好的文章)
  - [美工资源@](#美工资源)
- [测试调试@](#测试调试)
  - [调试优化@](#调试优化)
  - [Xcode工具@](#Xcode工具)
  - [crash@](#crash)
  - [Runtime@](#Runtime)
  - [Xcode插件@](#Xcode插件)
  - [接口调试工具@](#接口调试工具)
- [版本适配@](#版本适配)
- [WebView与WKWebView@](#WebView与WKWebView)
- [游戏@](#cocos2d-objc)
- [通讯录@](#通讯录)
- [其他库@](#其他库)
- [三方分享、支付、登录等等@](#三方分享、支付、登录等等)
- [消息相关@](#消息相关)
  - [消息推送客户端@](#消息推送客户端)
  - [消息推送服务器端@](#消息推送服务器端)
  - [通知相关请搜索“对话交互@”@](#通知相关请搜索“对话交互@”@)
- [时间日期@](#时间日期)
- [设计模式@](#设计模式)
- [皮肤@语言国际化@](#皮肤#语言国际化)
- [版本新API的Demo@](#版本新API的Demo)
- [代码安全与密码@](#代码安全与密码)
- [AppleWatch@](#AppleWatch)
- [VPN@](#VPN)
- [深度学习@](#深度学习)
- [mac@](#mac)
- [未分类@](#未分类)
- [其他领域@](#其他领域)
- [开发环境@](#开发环境)

#### 具体内容 =============================

#### 版本管理@
- [Git用法@](#Git用法)
- [GitHub@](#GitHub)
- [GitBook@](#GitBook)
- [Git文章@](#Git文章)
- [GithubRank@](#GithubRank)
- [桌面工具@](#桌面工具)
- [Github客户端@](#Github客户端)
- [Github插件@](#Github插件)
- [命令行@](#命令行)
- [Git平台与工具@](#Git平台与工具)
- [Github项目@](#Github项目)
- [Git库@](#Git库)
- [Github浏览器工具@](#Github浏览器工具)

#### Git用法@           [返回Git](#Git)                                   

* [git-recipes](https://github.com/geeeeeeeeek/git-recipes)  Git recipes in Chinese. 高质量的Git中文教程.   ---- (Star:4,722) (Fork:1,321) (Watch:301)  
* [lark](https://github.com/larkjs/lark/wiki/怎样贡献代码) 怎样在Github上面贡献代码   ---- (Star:144) (Fork:18) (Watch:23)  
* [my-git](https://github.com/xirong/my-git)有关 git 的学习资料   ---- (Star:3,986) (Fork:1,571) (Watch:384)  
* [gitignore](https://github.com/github/gitignore) 非常赞 有用的.gitignore模板集合(忽略上传的文件集合)，包含了各种语言.   ---- (Star:56,559) (Fork:24,911) (Watch:2,284)  
* [Linus讲解git](https://www.youtube.com/watch?v=4XpnKHJAok8) - Google大会演讲，Linus介绍他创造git的原因，对比了git和svn。
* [Git教程 - 廖雪峰的官方网站](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000) - 史上最浅显易懂的Git教程！
* [git - 简明指南](http://rogerdudler.github.io/git-guide/index.zh.html) - 助你入门 git 的简明指南，木有高深内容 ;)
* [常用 Git 命令清单](http://www.ruanyifeng.com/blog/2015/12/git-cheat-sheet.html) - 来自阮一峰的网络日志，列出了 Git 最常用的命令。
* [Pro Git（中文版）](https://git.oschina.net/progit/) - 书
* [Git Submodule使用完整教程](http://www.kafeitu.me/git/2012/03/27/git-submodule.html) - Git Submodule功能刚刚开始学习可能觉得有点怪异，所以本教程把每一步的操作的命令和结果都用代码的形式展现给大家，以便更好的理解。
* [Git权威指南](http://www.worldhello.net/gotgit/) - 书
* [git-flow 备忘清单](http://danielkummer.github.io/git-flow-cheatsheet/index.zh_CN.html) - git-flow 是一个 git 扩展集，按 Vincent Driessen 的分支模型提供高层次的库操作。
* [Git Magic](http://www-cs-students.stanford.edu/~blynn/gitmagic/intl/zh_cn/) -stanford出品
* [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials/setting-up-a-repository/) - atlassian出品
* [Try Git ( Interactive)](https://try.github.io/levels/1/challenges/1) -互动性的教你使用git
* [Git (简体中文)](https://wiki.archlinux.org/index.php/Git_(%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87)) -archlinux出品
* [Git Community Book 中文版](http://gitbook.liuhui998.com/index.html) -这本书汇聚了Git社区的很多精华,  其目的就是帮助你尽快的掌握Git.
 * [awesome-github-templates](https://github.com/devspace/awesome-github-templates) - github issue 和 pull request教程模板.   ---- (Star:343) (Fork:23) (Watch:13)  
* [git-recipes](https://github.com/geeeeeeeeek/git-recipes) -高质量的Git中文教程，来自国外社区的优秀文章和个人实践   ---- (Star:4,722) (Fork:1,321) (Watch:301)  
* [git-it](http://jlord.us/git-it/) - GitHub一位女员工写的Git教程，繁体中文版在这里可以找到: http://jlord.us/git-it/index-zhtw.html
* [Git Town](http://www.git-town.com/) - GitTown 定义了很多高级的 git 命令，例如 git ship / git sync 等以方便 git 的使用
* [git-tips](https://github.com/git-tips/tips) - 最常用的Git的提示和技巧。   ---- (Star:11,318) (Fork:836) (Watch:439)  
* [「Githug」Git 游戏通关流程](http://www.jianshu.com/p/482b32716bbe) - 这个命令行工具通过游戏的方式来练习你的 Git 技能
* [progit2-zh](https://github.com/progit/progit2-zh) - Pro Git，第二版，简体中文   ---- (Star:756) (Fork:225) (Watch:83)  
* [git-style-guide](https://github.com/agis-/git-style-guide)- git风格指南   ---- (Star:3,811) (Fork:303) (Watch:131)  
* [Git 进阶技巧](https://github.com/xhacker/GitProTips/blob/master/zh_CN.md) - 适合了解 Git 的基本使用，知道 commit、push、pull，希望掌握 Git 更多功能的人阅读。   ---- (Star:41) (Fork:12) (Watch:5)  
* [learn-git-basics](https://github.com/NataliaLKB/learn-git-basics) - git 指南   ---- (Star:41) (Fork:86) (Watch:5)  
* [30 天精通 Git 版本控管](https://github.com/doggy8088/Learn-Git-in-30-days/blob/master/zh-tw/README.md)   ---- (Star:1,416) (Fork:1,171) (Watch:205)  
* [图解Git](http://marklodato.github.io/visual-git-guide/index-zh-cn.html) - 图解git中的最常用命令。如果你稍微理解git的工作原理，这篇文章能够让你理解的更透彻。
* [沉浸式学 Git](http://igit.linuxtoy.org/contents.html) - 简洁github教程，每步信息量都不大，可以尝试一下。
* [工作中常用的Git命令行](https://github.com/DefaultYuan/Git-Pro) - 自己在工作中常用的Git命令行的小总结！   ---- (Star:9) (Fork:8) (Watch:3)  

#### GitHub@

 * [python_github_collect_star](https://github.com/Tim9Liu9/python_github_collect_star) 收集github上项目的star数、fork数、watch数   ---- (Star:15) (Fork:0) (Watch:2)  
 * [GitHub Pages 指南](http://jekyllcn.com/) - 官方文档翻译版
 * [GitHub Pages 指南 - 极客学院](http://wiki.jikexueyuan.com/project/github-pages-basics/) - 本指南是 GitHub Pages 官网 GitHub Pages Basics 的中文翻译版本。
 * [github-cheat-sheet](https://github.com/tiimgreen/github-cheat-sheet) -一些酷酷的Git和GitHub功能收集   ---- (Star:23,401) (Fork:3,460) (Watch:1,178)  
 * [jekyll官方文档中文翻译版](http://jekyllcn.com/) - 将纯文本转换为静态博客网站
 * [搭建一个免费的，无限流量的Blog----github Pages和Jekyll入门
](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html) - 示范如何在github上搭建Blog，你可以从中掌握github的Pages功能，以及Jekyll软件的基本用法。更重要的是，你会体会到一种建立网站的全新思路。
 * [免费使用Jekyll+Github Page搭建博客入门攻略](http://www.cellier.me/2015/01/04/jekyll%E6%90%AD%E5%BB%BA%E5%8D%9A%E5%AE%A2%E6%95%99%E7%A8%8B/) - Jekyll建站
 * [jekyll 学习资料整理](https://github.com/mba811/jekyll-study) - 在学习的同时将内容整理很多相关资料   ---- (Star:0) (Fork:1) (Watch:1)  
 * [jekyll-style-guide](http://ben.balter.com/jekyll-style-guide/)
 * [hexo你的博客](http://ibruce.info/2013/11/22/hexo-your-blog/) - hexo出自台湾大学生[tommy351](https://twitter.com/tommy351)之手，是一个基于Node.js的静态博客程序，其编译上百篇文字只需要几秒。
 * [如何搭建一个独立博客——简明Github Pages与Hexo教程](http://www.jianshu.com/p/05289a4bc8b2) - 这是一篇很详尽的独立博客搭建教程，里面介绍了域名注册、DNS设置、github和Hexo设置等过程。
 * [Hexo 中文版](https://hexo.io/zh-cn/) - hexo官网中文版
 * [像 geek 一样写博客](http://wiki.jikexueyuan.com/project/github-page/) - 结合了Octopress

#### GitBook@

 * [GitBook 简明教程](http://www.chengweiyang.cn/gitbook/index.html) - 本教程主要围绕 GitBook 的安装，使用，集成，书籍发布，个性化以及实用插件几个方面。
 * [Gitbook 入门教程](https://yuzeshan.gitbooks.io/gitbook-studying/content/index.html) - 本书将简单介绍如何安装、编写、生成、发布一本在线图书,且示例全部在windows下展示(其他系统差不多一致):
 * [Git教学](https://kingofamani.gitbooks.io/git-teach/content/index.html) - GIT版本控制
 * [Gitbook 使用入门](https://github.com/wwq0327/gitbook-zh) - 本书将简单介绍如何安装、编写、生成、发布一本在线图书。   ---- (Star:142) (Fork:68) (Watch:20)  
 * [api-guide](https://github.com/GitbookIO/api-guide) - gitbook 的api 文档   ---- (Star:18) (Fork:15) (Watch:12)  

#### Git文章@

* [如何高效利用GitHub](http://www.yangzhiping.com/tech/github.html) - 本文尝试谈谈GitHub的文化、技巧与影响
* [GitHub连击500天：让理想的编程成为习惯](https://www.phodal.com/blog/github-500-program-as-usual/) - phodal对于GitHub的看法
* [Github装逼指南——Travis CI 和 Codecov](https://segmentfault.com/a/1190000004415437) - 关于持续集成和统计单测覆盖率
* [如何用Github去管理你的Idea](http://zhuanlan.zhihu.com/phodal/20442311) - 用Github的README.md和Issues来管理我的idea
* [GitHub开源项目负责人谈开源](http://www.infoq.com/cn/news/2015/10/GitHub-OpenSource) - Brandon就其与开源的缘分、当前工作的职责、GitHub及员工与开源的关系等方面的问题一一进行了回答。
* [亲爱的GitHub](https://github.com/dear-github/dear-github) - 致GitHub的一封公开信   ---- (Star:4,557) (Fork:98) (Watch:112)  
* [thank-you-github](https://github.com/thank-you-github/thank-you-github) - 一封从GitHub毕业的公开信   ---- (Star:1,532) (Fork:1,443) (Watch:15)  
* [用Github issues作为blog的例子](https://github.com/lifesinger/blog/labels/blog)   ---- (Star:4,045) (Fork:665) (Watch:1,257)  
* [2014年GitHub 中国开发者年度报告](http://githuber.info/report) - 使用python分析数据后的报告
* [Gist介绍与用法](http://platinhom.github.io/2015/11/26/gist/) - Gist https://gist.github.com/ 是Github的一个子服务
* [最活跃的GitHub用户](https://gist.github.com/paulmillr/2657075/) - 想看最活跃用户可以看这里
* [10+ HELPFUL GITHUB HACKS TO IMMEDIATELY BOOST YOUR PRODUCTIVITY](http://usersnap.com/blog/github-hacks-productivity/) - 10个立即提高你生产力的GitHub技能
* [Top 10 Git Tutorials for Beginners](http://sixrevisions.com/resources/git-tutorials-beginners/) -教你使用git最好的10本书
* [使用GitHub进行团队合作](http://xiaocong.github.io/blog/2013/03/20/team-collaboration-with-github/) - 译文
* [一键收藏至Github](http://www.jianshu.com/p/19d2f3a3b5d8) - 通过 Rails 收藏文章，并自动提交至 github。
* [Github Hacking](http://www.jianshu.com/p/d6b54f1d60f1) - Github的各种黑客技能
* [如何参与一个GitHub开源项目？](http://www.csdn.net/article/2014-04-14/2819293-Contributing-to-Open-Source-on-GitHub) - 本文是Github官方给出的参与Github上开源项目的一些指导，对希望加入开源社区的开发者是一个不错的参考。
* [试译：开源项目成功的十条准则](http://www.zhuangbiaowei.com/blog/?cat=31) -作者将自己30年来的开发经验，总结为开源软件的十条成功法则。
* [漫谈Github与开源](http://www.wdk.pw/802.html) -本文作者为大二在读Geek学生关于GitHub与开源的理解。
* [关于Pull Request的十个建议](http://blog.ploeh.dk/2015/01/15/10-tips-for-better-pull-requests/) -作者Mark Seemann
* [Github上都有哪些有用但不为大家熟知的小功能？](https://www.zhihu.com/question/36974348) - 知乎问题
* [如果你用GitHub，可以这样提高效率](http://huang-jerryc.com/2016/01/15/%E5%A6%82%E6%9E%9C%E4%BD%A0%E7%94%A8GitHub%EF%BC%8C%E5%8F%AF%E4%BB%A5%E8%BF%99%E6%A0%B7%E6%8F%90%E9%AB%98%E6%95%88%E7%8E%87/) - 基于Github，搭建一整套代码管理服务
* [如何选择开源许可证？](http://www.ruanyifeng.com/blog/2011/05/how_to_choose_free_software_licenses.html) - 六种开源协议GPL、BSD、MIT、Mozilla、Apache和LGPL之间的区别
* [如何用好github中的watch、star、fork](http://www.jianshu.com/p/6c366b53ea41) - 介绍watch、star、fork的具体作用
* [git-commit-guide](https://github.com/bluejava/git-commit-guide) - git commit message 指南   ---- (Star:41) (Fork:9) (Watch:3)  
* [git操作是不是很难记住？](http://www.jianshu.com/p/e870fdd971fc) - 笔者试着分类git的常用操作，方便同样是刚入门git的你查阅。
* [GUI for git|SourceTree|入门基础](http://www.jianshu.com/p/be9f0484af9d) - SourceTree简介
* [话说Svn与Git的区别](http://www.jianshu.com/p/bfec042349ca) - SVN的特点是简单，只是需要一个放代码的地方时用是OK的。Git的特点版本控制可以不依赖网络做任何事情，对分支和合并有更好的支持。
* [多用Git少交税](http://www.jianshu.com/p/8a985c622e61)
* [Git版本控制与工作流](http://www.jianshu.com/p/67afe711c731) - 针对git版本控制和工作流的总结
* [在github上写博客](http://www.jianshu.com/p/1260517bbedb)
* [GitHub & Bitbucket & GitLab & Coding 的对比分析](http://blog.flow.ci/github-bitbucket-gitlab-coding)

#### GithubRank@

* [GitHub Rank (China)](http://githubrank.com/) - GitHub上中国程序员的排名网站，根据follower
* [GitHub Ranking | GitHub Awards](http://github-awards.com/) - GitHub上程序员的排名网站，根据star
* [GitHub Ranking](https://github-ranking.com/) - GitHub用户和仓库排名，根据star，不区分语言
* [diycode - GitHub Ranking](http://www.diycode.cc/trends) - GitHub 全球 Developers, Organizations and Repositories 排行榜

#### 桌面工具@

* [ohmystar](http://www.ohmystarapp.com/) - Mac上管理你GitHub star的工具
* [GithubPulse](https://github.com/tadeuzagallo/GithubPulse) - OS X状态栏的APP，帮你记住你在GitHub每天的贡献   ---- (Star:516) (Fork:22) (Watch:13)  
* [githubtrending](http://www.githubtrending.com/) - OS X状态栏的APP，显示GitHub Trending，也有iOS端
* [ghstatus](https://itunes.apple.com/cn/app/ghstatus/id883585153?mt=12) - OS X状态栏的APP，显示GitHub Status
* [pophub](http://questbe.at/pophub/) - OS X状态栏的APP，显示GitHub 的activities
* [git-dude](https://github.com/sickill/git-dude) - git commit通知   ---- (Star:914) (Fork:71) (Watch:26)  
* [gitee](https://github.com/Nightonke/Gitee) - Gitee, OS X status bar application for Github 漂亮的GitHub数据统计工具，还有notifications功能   ---- (Star:765) (Fork:25) (Watch:15)  

#### Github客户端@

* [MVVMReactiveCocoa](https://github.com/leichunfeng/MVVMReactiveCocoa) - GitBucket iOS App，一个GitHub第三方客户端   ---- (Star:2,978) (Fork:706) (Watch:116)  
* [Monkey](https://github.com/coderyi/Monkey) - Monkey是一个GitHub第三方iOS客户端，主要是用来展示GitHub上的开发者的排名，以及仓库的排名。   ---- (Star:1,483) (Fork:350) (Watch:68)  
* [react-native-gitfeed](https://github.com/xiekw2010/react-native-gitfeed) - 一个React Native写的Github客户端，支持iOS和Android   ---- (Star:1,619) (Fork:276) (Watch:62)  
* [githot](https://github.com/andyiac/githot) - GitHot是一个Android App,用来发现世界上最流行的项目和人   ---- (Star:378) (Fork:106) (Watch:26)  
* [CodeHub](https://github.com/thedillonb/CodeHub) - CodeHub是C#写的，它是iOS设备上最好的GitHub仓库浏览和维护工具。   ---- (Star:11,094) (Fork:391) (Watch:3,088)  
* [ioctocat](https://github.com/dennisreimann/ioctocat) - GitHub的iOS客户端   ---- (Star:1,690) (Fork:276) (Watch:62)  
* [napcat](https://itunes.apple.com/cn/app/napcat-github-client-for-open/id606238223?mt=8) - 一个比较全面的GitHub的iOS客户端
* [RepoStumble](https://github.com/thedillonb/RepoStumble) - 查看GitHub仓库的手机客户端   ---- (Star:111) (Fork:12) (Watch:11)  
* [GithubTrends](https://github.com/laowch/GithubTrends) - Material Design风格的查看GitHub仓库trending app   ---- (Star:633) (Fork:105) (Watch:34)  
* [ForkHub](https://github.com/jonan/ForkHub) - Android平台的GitHub客户端   ---- (Star:2,212) (Fork:174) (Watch:48)  
* [GitEgo](https://github.com/hrules6872/GitEgo) - Android平台的GitHub客户端   ---- (Star:29) (Fork:3) (Watch:1)  
* [Sources](https://github.com/vulgur/Sources) - 一个极简的 Github 客户端，Sources。内置几十个语法高亮的主题可供选择。   ---- (Star:83) (Fork:6) (Watch:3)  
* [igithub](https://github.com/schacon/igithub) - github 的iPhone端   ---- (Star:102) (Fork:39) (Watch:4)  
* [gitmonitor-ios](https://github.com/theotow/gitmonitor-ios) - 一个通知你不用再push代码的iOS app   ---- (Star:57) (Fork:4) (Watch:3)  
* [GithubWidget](https://github.com/Nightonke/GithubWidget) - 轻量级显示Github用户的贡献、星数、Follower数、热门仓库的App。   ---- (Star:655) (Fork:73) (Watch:18)  
* [GitPocket](https://github.com/jindulys/GitPocket) - Swift编写GitHub客户端   ---- (Star:9) (Fork:0) (Watch:1)  
* [GitHubContributionsiOS](https://github.com/JustinFincher/GitHubContributionsiOS) - 显示你的GitHub Contributions的Today Extension,App Store链接,[Contributions for GitHub](https://itunes.apple.com/us/app/contributions-for-github/id1153432612?l=zh&ls=1&mt=8)   ---- (Star:268) (Fork:21) (Watch:8)  

#### Github插件@

* [octotree](https://github.com/buunguyen/octotree) -浏览器扩展，树状格式显示GitHub的代码   ---- (Star:10,504) (Fork:864) (Watch:260)  
* [octo-linker](https://github.com/octo-linker/chrome-extension) - 这款谷歌 Chrome 扩展允许您轻松地浏览 GitHub.com 上的文件和包。   ---- (Star:2,357) (Fork:178) (Watch:72)  
* [github-hovercard](https://github.com/Justineo/github-hovercard) - GitHub Hovercard 是一个浏览器扩展，实现了展示用户在 Github 上信息的信息卡功能，支持 Firefox 和 Chrome 浏览器。   ---- (Star:1,005) (Fork:64) (Watch:24)  
* [notifier-for-github-chrome](https://github.com/sindresorhus/notifier-for-github-chrome) - 一个浏览器扩展，它能显示 Github 通知的未读数量   ---- (Star:521) (Fork:82) (Watch:39)  
* [github-menu-back](https://github.com/summerblue/github-menu-back) - 一款修改 GitHub 导航栏为之前状态的 Chrome 插件   ---- (Star:48) (Fork:2) (Watch:6)  
* [gitsense-extensions](https://github.com/gitsense/gitsense-extensions) - GitSense 是一个 Chrome 插件，可以让你在浏览 Github 的时候体验更好。   ---- (Star:46) (Fork:4) (Watch:9)  
* [git-draw](https://github.com/ben174/git-draw) - 谷歌 Chrome 扩展，给GitHub提交历史画个画   ---- (Star:1,578) (Fork:60) (Watch:36)  
* [ShowInGitHub](https://github.com/larsxschneider/ShowInGitHub) - Xcode插件，打开选中行的GitHub提交页面   ---- (Star:241) (Fork:41) (Watch:15)  
* [Reveal-In-GitHub](https://github.com/lzwjava/Reveal-In-GitHub) - 有关GitHub的Xcode插件   ---- (Star:269) (Fork:19) (Watch:5)  
* [Visual Studio](https://github.com/github/VisualStudio) - 有关GitHub的Visual Studio插件   ---- (Star:924) (Fork:445) (Watch:136)  
* [github-sublime-theme](https://github.com/AlexanderEkdahl/github-sublime-theme) - GitHub Sublime 主题   ---- (Star:54) (Fork:24) (Watch:4)  
* [GitHubinator](https://github.com/ehamiter/GitHubinator) - sublime插件，显示选中文本上的远程GitHub仓库   ---- (Star:127) (Fork:34) (Watch:3)  
* [alfred-github-workflow](https://github.com/gharlan/alfred-github-workflow) - Alfred 2上使用GitHub命令   ---- (Star:1,132) (Fork:62) (Watch:31)  
* [ZenHub](https://github.com/ZenHubIO/support) -ZenHub 能优化你的 GitHub 工作流，是轻量级的 Chrome 浏览器插件。   ---- (Star:307) (Fork:39) (Watch:38)  
* [github-gmail](https://github.com/muan/github-gmail) - 在Gmail内快速打开GitHub的通知   ---- (Star:790) (Fork:212) (Watch:119)  
* [chrome-github-avatars](https://github.com/anasnakawa/chrome-github-avatars) - 谷歌Chrome扩展，可以让你的GitHub主页显示用户的头像。   ---- (Star:143) (Fork:6) (Watch:6)  
* [tab-size-on-github](https://github.com/sindresorhus/tab-size-on-github) - 谷歌Chrome和Opera扩展，让代码缩进为4个空格而不是8个   ---- (Star:204) (Fork:40) (Watch:10)  
* [hide-files-on-github](https://github.com/sindresorhus/hide-files-on-github) - 谷歌Chrome和Opera扩展，隐藏点文件   ---- (Star:179) (Fork:23) (Watch:9)  
* [github-highlight-selected](https://github.com/Nuclides/github-highlight-selected) - 谷歌Chrome和Safari扩展，代码高亮，看起来像sublime   ---- (Star:109) (Fork:13) (Watch:7)  
* [github-awesome-autocomplete](https://github.com/algolia/github-awesome-autocomplete) - 谷歌Chrome和Safari以及Firefox扩展，在GitHub的搜索栏加入自动补全功能   ---- (Star:656) (Fork:52) (Watch:69)  
* [chrome-github-mate](https://github.com/rubyerme/chrome-github-mate) - 谷歌Chrome扩展，下载单个文件   ---- (Star:250) (Fork:42) (Watch:13)  
* [Pages2Repo](https://github.com/Frozenfire92/Pages2Repo) - 谷歌Chrome扩展，通过GitHub Pages网站就能访问仓库。   ---- (Star:19) (Fork:3) (Watch:3)  
* [lovely-forks](https://github.com/musically-ut/lovely-forks) - 谷歌Chrome扩展，显示fork你仓库中star最多的   ---- (Star:156) (Fork:12) (Watch:10)  
* [github-pr-filter](https://github.com/danielhusar/github-pr-filter) - 谷歌Chrome扩展，在pr中过滤文件   ---- (Star:17) (Fork:2) (Watch:2)  
* [github-ast-viewer](https://github.com/lukehorvat/github-ast-viewer) - 谷歌Chrome扩展，增加代码的抽象语法树   ---- (Star:41) (Fork:3) (Watch:4)  
* [github-canned-responses](https://github.com/notwaldorf/github-canned-responses) - 谷歌Chrome扩展，评论pr或者issue的时候有一些可选项   ---- (Star:385) (Fork:36) (Watch:10)  
* [categoric](https://github.com/ozlerhakan/categoric) - 谷歌Chrome扩展，为你的通知分类   ---- (Star:7) (Fork:0) (Watch:2)  
* [octo-preview](https://github.com/DrewML/octo-preview) - 谷歌Chrome扩展，预览你评论的markdown内容   ---- (Star:23) (Fork:6) (Watch:4)  
* [GifHub](https://github.com/DrewML/GifHub) - 谷歌Chrome扩展，GifHub一个往GitHub评论里边插入Gif动画的Chrome插件   ---- (Star:603) (Fork:37) (Watch:7)  
* [star-history-plugin](https://github.com/timqian/star-history-plugin) - 查看仓库star历史的插件   ---- (Star:126) (Fork:12) (Watch:4)  
* [open-on-github](https://github.com/atom/open-on-github) - atom插件，打开文件在github.com   ---- (Star:66) (Fork:49) (Watch:37)  
* [refined-github](https://github.com/sindresorhus/refined-github) - chrome插件，简化你的github，增加了一些可用的功能   ---- (Star:2,706) (Fork:201) (Watch:62)  
* [gitpress](https://github.com/enricob/gitpress) - github的wordpress插件，用于列出用户的仓库   ---- (Star:11) (Fork:0) (Watch:2)  
* [jquery-github](https://github.com/zenorocha/jquery-github) -jquery的插件显示github仓库   ---- (Star:296) (Fork:78) (Watch:18)  
* [sublime-text-git](https://github.com/kemayo/sublime-text-git) - sublime的git插件   ---- (Star:2,721) (Fork:381) (Watch:117)  
* [git-plugin](https://github.com/jenkinsci/git-plugin) - jenkins的git插件   ---- (Star:461) (Fork:732) (Watch:165)  
* [github-oauth-plugin](https://github.com/jenkinsci/github-oauth-plugin) - jenkins的github oauth登录插件   ---- (Star:66) (Fork:104) (Watch:137)  
* [twitter-for-github](https://github.com/bevacqua/twitter-for-github) - 在github上显示用户twitter的chrome插件   ---- (Star:119) (Fork:5) (Watch:5)  
* [Hudson-GIT-plugin](https://github.com/magnayn/Hudson-GIT-plugin) - Hudson上的GIT插件   ---- (Star:47) (Fork:732) (Watch:4)  
* [git-time-machine](https://github.com/littlebee/git-time-machine) - atom插件查看提交历史   ---- (Star:1,065) (Fork:43) (Watch:16)  
* [GitDiff](https://github.com/johnno1962/GitDiff) - Xcode插件   ---- (Star:867) (Fork:57) (Watch:23)  
* [vim-gitgutter](https://github.com/airblade/vim-gitgutter) - git的vim 插件   ---- (Star:4,516) (Fork:181) (Watch:73)  

#### Git平台与工具@

* [git](https://github.com/git/git) - git源码   ---- (Star:19,527) (Fork:11,287) (Watch:1,776)  
* [sourcetree](https://www.atlassian.com/software/sourcetree) - Windows 和Mac OS X 下免费的 Git客户端
* [gitbucket](https://github.com/gitbucket/gitbucket) - Scala编写的开源Git平台，扩展性好，兼容GitHub   ---- (Star:6,623) (Fork:873) (Watch:553)  
* [gogs](https://github.com/gogits/gogs) - Gogs (Go Git Service) 是一款极易搭建的自助 Git 服务，由[无闻](https://github.com/Unknwon)编写并开源在GitHub。   ---- (Star:21,408) (Fork:2,479) (Watch:928)  
* [gitlab](https://about.gitlab.com/gitlab-com/) - GitLab 是一个用于仓库管理系统的开源项目，地址在[gitlabhq](https://github.com/gitlabhq/gitlabhq)   ---- (Star:19,995) (Fork:5,319) (Watch:1,041)  
* [git-annex](https://github.com/joeyh/git-annex) - git管理大文件   ---- (Star:8) (Fork:0) (Watch:4)  
* [gitx](https://github.com/pieter/gitx) - Mac平台上的Git GUI客户端   ---- (Star:1,755) (Fork:621) (Watch:29)  
* [gity](https://github.com/beheadedmyway/gity) - mac的git客户端   ---- (Star:388) (Fork:37) (Watch:15)  
* [svn2git](https://github.com/nirvdrum/svn2git) - ruby 实现的迁移svn工程到git   ---- (Star:1,784) (Fork:358) (Watch:78)  
* [stupidgit](https://github.com/gyim/stupidgit) - python编写的git的跨平台GUI   ---- (Star:46) (Fork:6) (Watch:5)  
* [GitUp](https://github.com/git-up/GitUp) - Objective-C编写的Mac上的Git客户端   ---- (Star:6,942) (Fork:405) (Watch:153)  

#### 命令行@

* [hub](https://github.com/github/hub) - github官方出品的命令行工具，让你更好地使用github   ---- (Star:11,561) (Fork:1,093) (Watch:249)  
* [gitflow](https://github.com/nvie/gitflow)   ---- (Star:18,547) (Fork:2,021) (Watch:567)  
* [gh](https://github.com/jingweno/gh) -gh 是一个用 Go 语言开发的 Github 命令行客户端。   ---- (Star:738) (Fork:50) (Watch:18)  
* [node-gh](https://github.com/node-gh/gh) -Node GH 是基于 Node.js 编写的 Github 命令行工具。   ---- (Star:1,340) (Fork:156) (Watch:38)  
* [gitsome](https://github.com/donnemartin/gitsome/) - supercharged Github Client   ---- (Star:5,358) (Fork:250) (Watch:119)  
* [git-blame-someone-else](https://github.com/jayphelps/git-blame-someone-else) - 吐槽别人的烂代码   ---- (Star:4,317) (Fork:139) (Watch:56)  
* [git-pulls](https://github.com/schacon/git-pulls) - github pull requests的命令后行工具   ---- (Star:297) (Fork:53) (Watch:13)  
* [git-scribe](https://github.com/schacon/git-scribe) - 写电子书的命令行工具   ---- (Star:1,313) (Fork:123) (Watch:63)  
* [github-gem](https://github.com/defunkt/github-gem) - github命令行工具   ---- (Star:1,096) (Fork:191) (Watch:29)  
* [ghterm](https://github.com/github-archive/ghterm) - github终端   ---- (Star:43) (Fork:8) (Watch:12)  
* [git-sh](https://github.com/rtomayko/git-sh) - 适合git的bash工作环境   ---- (Star:678) (Fork:64) (Watch:25)  
* [legit](https://github.com/kennethreitz/legit) - 灵感来自于github for mac的git 命令行工具   ---- (Star:4,511) (Fork:189) (Watch:80)  
* [git-sweep](https://github.com/arc90/git-sweep) - git命令行工具，帮助你清理已经merge到master的分支   ---- (Star:1,650) (Fork:103) (Watch:44)  
* [github-email](https://github.com/paulirish/github-email) - 获取用户的邮箱   ---- (Star:140) (Fork:13) (Watch:5)  
* [git-town](https://github.com/Originate/git-town) Generic, high-level Git workflow support!   ---- (Star:1,470) (Fork:53) (Watch:46)  
* [git-fire](https://github.com/qw3rtman/git-fire) - 紧急情况下保存代码   ---- (Star:1,900) (Fork:78) (Watch:30)  
* [gitsome](https://github.com/donnemartin/gitsome) - Git/GitHub命令行工具   ---- (Star:5,358) (Fork:250) (Watch:119)  
* [maintainer](https://github.com/gaocegege/maintainer) - 让你的 GitHub repo 对开发者更加友好的命令行工具   ---- (Star:120) (Fork:8) (Watch:6)  

#### Github项目@

* [resume.github.com](https://github.com/resume/resume.github.com) - 根据用户的github信息生成简历   ---- (Star:32,857) (Fork:874) (Watch:288)  
* [github-trending](https://github.com/josephyzhou/github-trending) - 记录下GitHub历史上的每日trending   ---- (Star:1,519) (Fork:114) (Watch:145)  
* [GitHub-Dark](https://github.com/StylishThemes/GitHub-Dark) - 黑色的GitHub网站风格   ---- (Star:2,143) (Fork:190) (Watch:60)  
* [github-gists](https://github.com/kevva/github-gists) - 拿到一个GitHub用户的所有gist   ---- (Star:44) (Fork:3) (Watch:9)  
* [Get-Your-GitHub-Card](https://github.com/codesboy/Get-Your-GitHub-Card) - 基于jquery拿到你的GitHub用户资料   ---- (Star:18) (Fork:4) (Watch:1)  
* [ohmyrepo](https://github.com/no13bus/ohmyrepo) - 一个 GitHub 仓库分析工具   ---- (Star:124) (Fork:12) (Watch:4)  
* [greenhat](https://github.com/4148/greenhat) - 一个让GitHub全绿的“旁门左道”的东西。   ---- (Star:1,296) (Fork:160) (Watch:37)  
* [gitfiti](https://github.com/gelstudios/gitfiti) - 滥用github提交历史   ---- (Star:3,503) (Fork:278) (Watch:74)  
* [Github-profile-name-writer](https://github.com/ironmaniiith/Github-profile-name-writer) - 把github提交历史变成你的名字   ---- (Star:85) (Fork:27) (Watch:2)  
* [github-contributions](https://github.com/IonicaBizau/github-contributions) - 可以让你的 github 提交日历排出有趣的图案   ---- (Star:1,063) (Fork:104) (Watch:28)  
* [github-corners](https://github.com/tholman/github-corners) - 显示 "Fork me on GitHub"   ---- (Star:3,049) (Fork:101) (Watch:44)  
* [GitHub-jQuery-Repo-Widget](https://github.com/JoelSutherland/GitHub-jQuery-Repo-Widget) - 一个GitHub风格的挂件，方便在页面中展示GitHub项目   ---- (Star:284) (Fork:79) (Watch:15)  
* [GitHub Archive](https://github.com/igrigorik/githubarchive.org) - GitHub Archive 是一个记录GitHub时间线的项目   ---- (Star:1,550) (Fork:136) (Watch:73)  
* [github-cards](https://github.com/lepture/github-cards) - GitHub Cards 用来展示你的简介   ---- (Star:1,369) (Fork:90) (Watch:26)  
* [githut](https://github.com/littleark/githut) - 可视化了GitHub Archive的数据，网站链接，[http://githut.info/](http://githut.info/)   ---- (Star:1,011) (Fork:88) (Watch:42)  
* [lolcommits](https://github.com/mroth/lolcommits) - 每次提交Git都自拍一张   ---- (Star:3,885) (Fork:249) (Watch:47)  
* [github-selfies](https://github.com/thieman/github-selfies) - Github Selfies 可以在你 Github 的需求和贡献上加上你的自拍照。   ---- (Star:648) (Fork:67) (Watch:18)  
* [badges](https://github.com/boennemann/badges) - 收集GitHub上readme页显示的与javascript有关的各种徽章   ---- (Star:668) (Fork:406) (Watch:23)  
* [MediumArticles](http://www.jianshu.com/p/19d2f3a3b5d8) - 一键收藏至Github
* [GitHunt](https://github.com/apollostack/GitHunt) - 为你喜欢的仓库投票的项目   ---- (Star:705) (Fork:151) (Watch:41)  
* [githug](https://github.com/Gazler/githug) - 通过游戏的方式来练习Git的命令行工具   ---- (Star:4,907) (Fork:770) (Watch:170)  
* [css3-github-buttons](https://github.com/necolas/css3-github-buttons) - 帮助你创建github风格的 button   ---- (Star:1,128) (Fork:347) (Watch:64)  
* [git-crypt](https://github.com/AGWA/git-crypt) - git加密   ---- (Star:2,508) (Fork:180) (Watch:81)  
* [is-github-down](https://github.com/sindresorhus/is-github-down) - 检查github有没有down机   ---- (Star:119) (Fork:9) (Watch:7)  
* [miaopull](https://github.com/aquarhead/miaopull) - 自动化pull工具   ---- (Star:1) (Fork:0) (Watch:1)  
* [go-git](https://github.com/src-d/go-git)- 通过go来从git服务器读取仓库   ---- (Star:1,624) (Fork:151) (Watch:57)  
* [GitViz](https://github.com/Readify/GitViz) - 帮助你训练git时的可视化工具   ---- (Star:158) (Fork:30) (Watch:122)  
* [learnGitBranching](https://github.com/pcottle/learnGitBranching) - 学习git的可视化工具   ---- (Star:5,565) (Fork:1,779) (Watch:283)  

#### Git库@

* [octokit](https://github.com/octokit) - GitHub API的官方封装库
* [GitHub Java API (org.eclipse.egit.github.core)](https://github.com/eclipse/egit-github/tree/master/org.eclipse.egit.github.core) - eclipse出品，Java写的GitHub API的封装库   ---- (Star:541) (Fork:418) (Watch:92)  
* [github - michael](https://github.com/michael/github) - JavaScript写的GitHub API的封装库   ---- (Star:2,509) (Fork:589) (Watch:99)  
* [PyGithub](https://github.com/PyGithub/PyGithub) - Python的GitHub API封装库   ---- (Star:1,485) (Fork:523) (Watch:72)  
* [UAGithubEngine](https://github.com/owainhunt/uagithubengine) - Objective-C的GitHub API封装库   ---- (Star:230) (Fork:61) (Watch:12)  
* [RxGitHubAPI](https://github.com/FengDeng/RxGitHubAPI) -基于RxSwift的GitHub API封装库   ---- (Star:75) (Fork:14) (Watch:2)  
* [GitHub API for Java](http://github-api.kohsuke.org/) -面向对象的GitHub API库
* [GitHubObjC](https://github.com/ernstsson/GitHubObjC) -Objective-C实现的GitHub API库   ---- (Star:32) (Fork:4) (Watch:1)  
* [go-github](https://github.com/google/go-github) -Go实现的GitHub API库   ---- (Star:2,976) (Fork:705) (Watch:135)  
* [ruby-github](https://github.com/peter-murach/github) -Ruby实现的GitHub API库   ---- (Star:908) (Fork:272) (Watch:44)  
* [libgit2](https://github.com/libgit2/libgit2) - Git核心库，通过它可以写一个自己的git应用。   ---- (Star:6,242) (Fork:1,594) (Watch:424)  
* [Gift](https://github.com/modocache/Gift) - 通过Swift绑定libgit2，通过它你可以clone一个仓库，查看commit，提交等。   ---- (Star:268) (Fork:17) (Watch:12)  
* [gitkit-js](https://github.com/SamyPesse/gitkit-js) - gitkit-js，SamyPesse开源的git的javascript实现，包含一系列API,可以管理git仓库，包括读文件，commit， clone，push，fetch等，可以工作在浏览器和node.js上   ---- (Star:573) (Fork:26) (Watch:23)  
* [github3.py](https://github.com/sigmavirus24/github3.py) - GitHub API v3的python接口   ---- (Star:728) (Fork:267) (Watch:34)  
* [PyGithub](https://github.com/PyGithub/PyGithub) - GitHub API v3的python接口   ---- (Star:1,485) (Fork:523) (Watch:72)  
* [github-backup](https://github.com/joeyh/github-backup) - 备份GitHub仓库，包括branches, tags, other forks, issues, comments, wikis, milestones, pull requests, watchers, and stars. 通过haskell编写   ---- (Star:5) (Fork:1) (Watch:2)  
* [github - Haskell](https://github.com/PyGithub/PyGithub) - GitHub API 的Haskell接口   ---- (Star:1,485) (Fork:523) (Watch:72)  
* [objective-git](https://github.com/schacon/objective-git) - Git的Objective-C实现   ---- (Star:85) (Fork:16) (Watch:4)  
* [node-gitlab](https://github.com/node-gitlab/node-gitlab) - gitlab的node api   ---- (Star:396) (Fork:130) (Watch:23)  
* [php-github-api](https://github.com/KnpLabs/php-github-api) - php的github api   ---- (Star:1,149) (Fork:396) (Watch:85)  
* [cocoagit](https://github.com/geoffgarside/cocoagit) - git的objetive-c实现   ---- (Star:83) (Fork:16) (Watch:9)  
* [ruby-github](https://github.com/mbleigh/ruby-github) - mbleigh写的ruby的github api   ---- (Star:59) (Fork:9) (Watch:3)  
* [Git.framework](https://github.com/geoffgarside/Git.framework) - mac os x 平台的objective-c的git实现   ---- (Star:138) (Fork:21) (Watch:11)  
* [pygit2](https://github.com/libgit2/pygit2) - libgit2的python版   ---- (Star:984) (Fork:238) (Watch:70)  
* [git.js](https://github.com/danlucraft/git.js) - git的js实现   ---- (Star:1,287) (Fork:84) (Watch:35)  
* [nodegit](https://github.com/nodegit/nodegit) - git的node实现   ---- (Star:3,009) (Fork:439) (Watch:72)  
* [GitSharp](https://github.com/henon/GitSharp) - .Net实现的git   ---- (Star:616) (Fork:145) (Watch:45)  
* [erlangit](https://github.com/schacon/erlangit) - erlang 的git实现   ---- (Star:70) (Fork:13) (Watch:3)  
* [github4j](https://github.com/defunct/github4j) - 一个github 下载的java api   ---- (Star:2) (Fork:1) (Watch:1)  
* [libgit2sharp](https://github.com/libgit2/libgit2sharp) - .Net实现的git   ---- (Star:1,289) (Fork:511) (Watch:118)  
* [Gift](https://github.com/modocache/Gift) - Swift编写的git实现   ---- (Star:268) (Fork:17) (Watch:12)  
* [SwiftGit2](https://github.com/SwiftGit2/SwiftGit2) - Swift编写的git实现   ---- (Star:212) (Fork:28) (Watch:11)  
* [GithubPilot](https://github.com/jindulys/GithubPilot) - Swift的GitHub API 封装   ---- (Star:48) (Fork:7) (Watch:3)  
* [GitYourFeedback](https://github.com/gabek/GitYourFeedback) - 让你可以直接在iOS App内feedback时向GitHub提交issue   ---- (Star:52) (Fork:14) (Watch:6)  

#### Github浏览器工具@

* [awesome-browser-extensions-for-github](https://github.com/stefanbuck/awesome-browser-extensions-for-github) GitHub浏览器扩展收集列表   ---- (Star:913) (Fork:79) (Watch:51)  

#### 完整App@

* [PPRows for Mac](https://github.com/jkpang/PPRows) - 在Mac上优雅的计算你写了多少行代码。   ---- (Star:780) (Fork:88) (Watch:18)  
* [open-source-ios-apps](https://github.com/dkhamsing/open-source-ios-apps) - iOS开源App集合，分：swift与Objective-C--国外人整理。   ---- (Star:14,587) (Fork:2,552) (Watch:973)  
* [NewsBlur](https://github.com/samuelclay/NewsBlur) 作者独自一个人 Samuel Clay 做出来的一款名为 NewsBlur 的新闻阅读器, 很多人都称其为 Google Reader 的替代品, 这是它的源码 NewsBlur is a personal news reader that brings people together to talk about the world. A new sound of an old instrument.   ---- (Star:4,752) (Fork:865) (Watch:251)  
* [HackerNews-React-Native](https://github.com/iSimar/HackerNews-React-Native)用 React Native 完成的 HackerNews 客户端。   ---- (Star:3,158) (Fork:555) (Watch:147)  
* [WeChat](https://github.com/zhengwenming/WeChat) 实现类似微信朋友圈或者QQ空间，评论回复，九宫格布局。处理键盘弹出后定位到当前点击的被评论人处。另：滑动时候FPS在57-60之间，纵享丝滑！   ---- (Star:1,060) (Fork:304) (Watch:48)  
* [MessageDisplayKit](https://github.com/xhzengAIB/MessageDisplayKit) An IM App like WeChat App has to send text, pictures, audio, video, location messaging, managing local address book, share a circle of friends, drifting friends, shake a fun and more interesting features.   ---- (Star:3,991) (Fork:1,241) (Watch:245)  
* [iOSAppTemplate](https://github.com/tbl00c/iOSAppTemplate)高仿微信，iOS应用开发模板，个人总结。   ---- (Star:435) (Fork:172) (Watch:36)  
* [Bilibili_Wuxianda](https://github.com/MichaelHuyp/Bilibili_Wuxianda)赞 高仿Bilibili客户端   ---- (Star:2,137) (Fork:575) (Watch:84)  
* [Coding-iOS](https://github.com/Coding/Coding-iOS) - Coding iOS 客户端源代码   ---- (Star:2,902) (Fork:1,180) (Watch:217)  
* [Coding-iPad](https://github.com/Coding/Coding-iPad) - Coding iPad 客户端源代码   ---- (Star:272) (Fork:102) (Watch:27)  
* [Monkey](https://github.com/coderyi/Monkey) - GitHub第三方iOS客户端   ---- (Star:1,483) (Fork:350) (Watch:68)  
* [firefox-ios](https://github.com/mozilla/firefox-ios) Firefox for iOS   ---- (Star:7,523) (Fork:1,619) (Watch:415)  
* [RSSRead](https://github.com/ming1016/RSSRead) “已阅”（iOS上开源RSS新闻阅读器）   ---- (Star:828) (Fork:243) (Watch:74)  
* [zulip-ios](https://github.com/zulip/zulip-ios) Dropbox收购公司内部社交服务商Zulip,然后全部开源，这是iOS App   ---- (Star:636) (Fork:203) (Watch:48)  
* [ChatSecure-iOS](https://github.com/ChatSecure/ChatSecure-iOS) - Objective-C写的XMPP聊天应用   ---- (Star:2,476) (Fork:917) (Watch:193)  
* [FirebaseChat](https://github.com/relatedcode/FirebaseChat) - Objective-C写的完整的聊天应用   ---- (Star:2,853) (Fork:725) (Watch:173)  
* [Meizi](https://github.com/Sunnyyoung/Meizi) - 豆瓣妹子图iOS客户端   ---- (Star:621) (Fork:220) (Watch:39)  
* [PlainReader](https://github.com/guojiubo/PlainReader) 简阅是一款 iOS(iPhone + iPad) 新闻类客户端，内容抓取自 cnBeta.COM。在售期间倍受好评，但由于版权问题已于今年一月从 AppStore 下架，下架至今，每天仍有几千人在使用这款 App。   ---- (Star:474) (Fork:175) (Watch:32)  
* [ECMobile_iOS](https://github.com/GeekZooStudio/ECMobile_iOS) 基于ECShop的手机商城客户端   ---- (Star:897) (Fork:536) (Watch:97)  
* [wikipedia-ios](https://github.com/wikimedia/wikipedia-ios) 维基百科官方App, 已上架   ---- (Star:1,180) (Fork:353) (Watch:78)  
* [Sol](https://github.com/comyarzaheri/Sol) 漂亮的扁平风格的天气App   ---- (Star:1,332) (Fork:312) (Watch:73)  
* [v2ex](https://github.com/singro/v2ex)v2ex第三方iOS客户端。V2EX是一个知名技术创意网站，由设计师、程序员及有创意的人参与的社区。 它基于兴趣将用户创建的内容组织分类成不同“节点”，网站以内容的活跃程度决定在首页排序的位置。   ---- (Star:1,816) (Fork:481) (Watch:87)  
* [WNXHuntForCity](https://github.com/ZhongTaoTian/WNXHuntForCity)城觅By-Objective-C   ---- (Star:1,904) (Fork:525) (Watch:96)  
* [breadwallet](https://github.com/voisine/breadwallet) breadwallet - bitcoin wallet   ---- (Star:731) (Fork:348) (Watch:82)  
* [GreatReader](https://github.com/semweb/GreatReader) GreatReader PDF阅读客户端   ---- (Star:546) (Fork:124) (Watch:37)  
* [Tropos](https://github.com/thoughtbot/Tropos)天气客户端   ---- (Star:1,428) (Fork:197) (Watch:83)  
* [WordPress-iOS](https://github.com/wordpress-mobile/WordPress-iOS)WordPress iOS官方客户端. 笔者强烈推荐的开源项目.   ---- (Star:2,066) (Fork:730) (Watch:149)  
* [TeamTalk](https://github.com/mogujie/TeamTalk) 蘑菇街TeamTalk. 开源IM. 笔者强烈推荐.   ---- (Star:4,789) (Fork:2,566) (Watch:576)  
* [MessageDisplayKit](https://github.com/xhzengAIB/MessageDisplayKit)一个类似微信App的IM应用，拥有发送文字、图片、语音、视频、地理位置消息，管理本地通信录、分享朋友 圈、漂流交友、摇一摇和更多有趣的功能。笔者推荐的学习IM的好东西.   ---- (Star:3,991) (Fork:1,241) (Watch:245)  
* [iOS-Oncenote](https://github.com/chenyufeng1991/iOS-Oncenote) 这是一款类似于印象笔记Evernote的生活类iOS应用——朝夕笔记 Oncenote。我希望能为更多的iOS开发者提供帮助与服务。当然App中还有不少bug和可扩展的功能模块，也希望各位开发者为该项目贡献自己的code力量。大家可以通过点击右上角的fork到自己的Github仓库，也可以点击star实时关注项目进度。   ---- (Star:333) (Fork:196) (Watch:32)  
* [GSD_WeiXin](https://github.com/gsdios/GSD_WeiXin) 高仿微信   ---- (Star:2,436) (Fork:851) (Watch:135)  
* [v2ex](https://github.com/singro/v2ex) - v2ex 的客户端，新闻、论坛。   ---- (Star:1,816) (Fork:481) (Watch:87)  
* [wikipedia-ios](https://github.com/wikimedia/wikipedia-ios) - wikipedia-ios 客户端。   ---- (Star:1,180) (Fork:353) (Watch:78)  
* [DeckRocket](https://github.com/jpsim/DeckRocket) - 在相同 WiFi 网络环境内，通过iPhone 控制并播放 Mac 中的 PDF 文档。   ---- (Star:355) (Fork:60) (Watch:14)  
* [DSLolita](https://github.com/sam408130/DSLolita) - 模仿新浪微博做的一款app，有发送博文，评论，点赞，私聊功能。   ---- (Star:504) (Fork:193) (Watch:28)  
* [STPhotoBrowser](https://github.com/STShenZhaoliang/STPhotoBrowser) - 高仿新浪微博的图片浏览器，极佳的编写方式，易扩展，低耦合。   ---- (Star:269) (Fork:69) (Watch:8)  
* [Tropos](https://github.com/thoughtbot/Tropos) - Tropos, 由 thoughtbot 推出的一款用 Objective-C 写的开源天气类应用, 截至今天, thoughtbot 已在 GitHub 上贡献了 174 个开源项目, 实在令人敬佩。   ---- (Star:1,428) (Fork:197) (Watch:83)  
* [SmileWeather](https://github.com/liu044100/SmileWeather) -开源天气类应用,天气图标很完整。     ---- (Star:441) (Fork:76) (Watch:16)  
* [MVVMReactiveCocoa](https://github.com/leichunfeng/MVVMReactiveCocoa) - GitBucket 2.0 通过审核啦，她是我在公司实践了一年多 MVVM 和 RAC 的基础上，利用业余时间开发的第三方 GitHub 客户端，旨在能够对想实践 MVVM 和 RAC 的 iOS 开发者有所帮助。[AppStore地址](https://itunes.apple.com/cn/app/id961330940?mt=8)，欢迎下载使用GitBucket和收藏MVVMReactiveCocoa。   ---- (Star:2,978) (Fork:706) (Watch:116)  
* [Tomate](https://github.com/dasdom/Tomate) - 这个圆盘式计时器让你更专注于工作或学习。P.S. App Store 上架收费应用（0.99 欧）。   ---- (Star:466) (Fork:76) (Watch:10)  
* [WNXHuntForCity](https://github.com/ZhongTaoTian/WNXHuntForCity) - iOS高仿城觅项目（开发思路和代码）。   ---- (Star:1,904) (Fork:525) (Watch:96)  
* [ZYChat](https://github.com/zyprosoft/ZYChat) - 关于聊天界面的可消息类型扩展，响应绑定设计。   ---- (Star:926) (Fork:358) (Watch:58)  
* [meituan](https://github.com/lookingstars/meituan) - 美团5.7iOS版（高仿），功能包括，团购首页，高德地图搜索附近美食并显示在地图上，上门服务，商家，友盟分享。   ---- (Star:1,536) (Fork:674) (Watch:88)  
* [JFMeiTuan](https://github.com/tubie/JFMeiTuan) - 造美团应用界面构建的 iOS 应用, 第二个是 @tubiebutu 的 JFMeiTuan。   ---- (Star:523) (Fork:147) (Watch:28)  
* [SXNews](https://github.com/dsxNiubility/SXNews) - 模仿网易新闻做的新闻软件，完成了主导航页，新闻详情页，图片浏览页，评论页。效果不错，比网上流传的各种和网易新闻UI架构有关的代码都要完整，都要好。   ---- (Star:3,237) (Fork:1,089) (Watch:190)  
* [Monkey](https://github.com/coderyi/Monkey) - Monkey for GitHub是一个GitHub开发者和仓库排名的开源App。这次主要增加了登录GitHub的功能，随手follow和star，并且增加发现模块，包括GitHub的trending，动态，showcases等。   ---- (Star:1,483) (Fork:350) (Watch:68)  
* [Uther](https://github.com/callmewhy/Uther) -  跟蠢萌的外星人聊天，还能帮你记事”。[itunes下载](https://itunes.apple.com/cn/app/uther/id1024104920) 。   ---- (Star:374) (Fork:67) (Watch:16)  
* [高仿斗鱼TV](http://code.cocoachina.com/view/128246) - 高仿斗鱼TV，点击头部滚动视图可以播放视频。
* [Coding-iPad](https://github.com/Coding/Coding-iPad) - Coding-iPad 是@Coding的官方 iPad 客户端, 又是一个完整的开源应用。   ---- (Star:272) (Fork:102) (Watch:27)  
* [react-native-gitfeed](https://github.com/xiekw2010/react-native-gitfeed) - 目前最实用简洁的github客户端了。   ---- (Star:1,619) (Fork:276) (Watch:62)  
* [phphub-ios](https://github.com/Aufree/phphub-ios) - PHPHub的iOS客户端，同时兼容iPhone和iPad。   ---- (Star:1,147) (Fork:338) (Watch:55)  
* [LeagueofLegends](https://github.com/HarrisHan/LeagueofLegends) - 一个关于英雄联盟的完整iOS开源项目，接口均来自多玩，腾讯各大游戏平台。
* [BTApp](https://github.com/Ryan0520/BTApp) - BTApp 仿半糖 iOS App 的 Demo 应用。   ---- (Star:347) (Fork:77) (Watch:8)  
* [iOS完整App资源收集](https://github.com/CoderJackyHuang/MDArtileFiles) - iOS开发学习者都希望得到实战训练，但是很多资料都是只有一小部分代码，并不能形成完成的App，笔者在此处收集了很多开源的完整的App，都有源代码哦！--标哥的技术博客   ---- (Star:77) (Fork:24) (Watch:3)  
* [XCFApp-1](https://github.com/callmejoejoe/XCFApp) - 高仿下厨房App，Objective-C，Xcode7.2，数据通过Charles抓的，有接口也有本地数据。说明：关于代码被清空，会用git的你肯定明白，[教程](http://www.jianshu.com/p/a8f619a2c622/)   ---- (Star:364) (Fork:122) (Watch:10)  
* [YoCelsius](https://github.com/YouXianMing/YoCelsius) - 已经上线的一款天气预报的应用,几乎所有的交互动画效果，想学习动画的开发人员可以作为参考。   ---- (Star:2,468) (Fork:545) (Watch:86)  
* [DayDayNews](https://github.com/gaoyuhang/DayDayNews) 仿网易新闻客户端，实现新闻浏览，视频播放，仿搜狐视频、百思不得姐等当前主流视频播放器，实现流媒体播放，自动监听屏幕转动，实现横屏播放 , 抓取百度图片，瀑布流显示，夜间模式，环信即时通讯   ---- (Star:310) (Fork:123) (Watch:18)  
* [ECMobile_iOS](https://github.com/GeekZooStudio/ECMobile_iOS)基于ECShop的手机商城客户端（iOS、Android、Php一体）   ---- (Star:897) (Fork:536) (Watch:97)  
* [TKeyboard](https://github.com/music4kid/TKeyboard) 这款应用名为：TKeyboard。有一个 Mac 端和一个 iOS 端 App。简单来说，可以通过蓝牙，使用 Mac 的键盘输入内容到 iPhone 设备中。   ---- (Star:704) (Fork:120) (Watch:10)  
* [BDJProjectExample](https://github.com/yizzuide/BDJProjectExample) 基于VIPER设计模式，以XFLegoVIPER框架为引擎的仿《百思不得姐》项目   ---- (Star:71) (Fork:32) (Watch:5)  
* [UberSignature](https://github.com/uber/UberSignature) 一个通过触摸前面的App.   ---- (Star:345) (Fork:19) (Watch:11)  
* [HiPDA](https://github.com/leizh007/HiPDA) HiPDA的非官方客户端（iOS版）！   ---- (Star:46) (Fork:14) (Watch:5)  
* [yanxuan-weex-demo](https://github.com/zwwill/yanxuan-weex-demo) a demo developed using weex/weex高仿网易严选App.   ---- (Star:517) (Fork:118) (Watch:19)  
* [MeiTuan](https://github.com/huanxsd/MeiTuan) 高仿美团客户端 React-Native版，支持iOS、Android   ---- (Star:1,649) (Fork:385) (Watch:96)  

#### 框架@                                                        [返回目录](#目录)

* [nimbus](https://github.com/jverkoey/nimbus) Nimbus是一个开源的iOS框架，比起Three20，Nimbus的文档更为全面、丰富，能够实现很多非常炫的界面特效。因此，开发者可以借助Nimbus来降低项目设计的复杂度。   ---- (Star:6,349) (Fork:1,389) (Watch:438)  
* [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) - ReactiveCocoa 受函数响应式编程激发。不同于使用可变的变量替换和就地修改，RAC提供Signals来捕获当前值和将来值（ [使用介绍](http://yulingtianxia.com/blog/2014/07/29/reactivecocoa/) ），[不错的例子](http://iiiyu.com/2014/12/26/learning-ios-notes-thirty-six/),入门好教程：[ReactiveCocoa入门教程：第一部分 ](http://www.cocoachina.com/ios/20150123/10994.html)。[Reactive Cocoa 3.0 在 MVVM 中的应用](http://ios.jobbole.com/82232/) ,[小码哥：快速让你上手ReactiveCocoa之基础篇](http://www.jianshu.com/p/87ef6720a096)。   ---- (Star:17,980) (Fork:3,346) (Watch:936)  
* [react-native-maps](https://github.com/airbnb/react-native-maps) React Native Mapview component for iOS + Android.   ---- (Star:5,684) (Fork:1,486) (Watch:175)  
* [react-native-svg](https://github.com/react-native-community/react-native-svg) SVG library for React Native. react-native-svg is built to provide a SVG interface to react native on both iOS and Android.   ---- (Star:1,739) (Fork:239) (Watch:68)  
* [react-native-code-push](https://github.com/Microsoft/react-native-code-push) React Native module for CodePush.   ---- (Star:3,624) (Fork:473) (Watch:187)  
* [CYLTabBarController](https://github.com/ChenYilong/CYLTabBarController) - 低耦合集成TabBarController,最低只需传两个数组即可完成主流App框架搭建。   ---- (Star:3,751) (Fork:903) (Watch:130)  
* [samurai-native](https://github.com/hackers-painters/samurai-native) 是一个基于浏览器内核通过HTML+CSS 开发原生移动应用的iOS框架。   ---- (Star:2,285) (Fork:399) (Watch:186)  
* [HHRouter](https://github.com/Huohua/HHRouter) 一言以蔽之，URL Router 即将 UIViewController 映射成 URL，从而支持通过 URL 进行界面跳转。是的，就和 Web 一样。当然，这并不是 Web Developer 转职为 iOS Developer 后所做的无聊玩具。URL Router 有着许多切实的好处。   ---- (Star:53) (Fork:196) (Watch:4)  
* [katana-swift]（https://github.com/BendingSpoons/katana-swift）一个用于编写iOS应用程序的现代Swift框架，灵感来自React和Redux。 Swift Apps in a Swoosh! A modern framework for creating iOS apps, inspired by React and Redux.
* [AsyncDisplayKit](https://github.com/facebook/AsyncDisplayKit) 异步界面渲染库,为极限优化View效果而生（同时提供 UIView bridge 接口） Smooth asynchronous user interfaces for iOS apps.   ---- (Star:12,034) (Fork:2,161) (Watch:557)  
* [XFLegoVIPER](https://github.com/yizzuide/XFLegoVIPER) A lightweight framework base on VIPER architecture for iOS, to build robust and maintained large scale project.   ---- (Star:134) (Fork:42) (Watch:15)  
* [publishImageAndVideoAnsRecord](https://github.com/DayCrazy/publishImageAndVideoAnsRecord) 因为公司有很多模块，几乎每个模块都需要发布视频、语言、照片。所以在很多库的基础上，搭建了一个集合，其中包括带placeHolder的TextView、录制小视频、录制音频、选择照片或拍照。其中包括了很多网络上的资源，只是做了集合，在此留个记录，也希望对一些有需求额的朋友有帮助。   ---- (Star:154) (Fork:39) (Watch:5)  
* [XBSettingController](https://github.com/changjianfeishui/XBSettingController) 快速搭建类个人中心及应用设置界面   ---- (Star:78) (Fork:28) (Watch:5)  
* [EVNEstorePlatform](https://github.com/zonghongyan/EVNEstorePlatform) App项目框架 [简书解析](http://www.jianshu.com/p/89e25c288d76?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)   ---- (Star:79) (Fork:18) (Watch:2)  
* [TemplateCocoa](https://github.com/turkeyaa/TemplateCocoa) 本教程旨在让我们更加快速、高效的开发移动app   ---- (Star:9) (Fork:2) (Watch:1)  

#### React@

* [react-native](https://github.com/facebook/react-native) A framework for building native apps with React.   ---- (Star:55,084) (Fork:12,865) (Watch:3,208)  
* [weex](https://github.com/alibaba/weex) A framework for building Mobile cross-platform UI.   ---- (Star:15,229) (Fork:2,055) (Watch:1,934)  

#### 响应式@

* [LoginWithReactiveCocoa](https://github.com/CrazySurfBoy/LoginWithReactiveCocoa) - ReactiveCocoa - 登录交互效果的实现。   ---- (Star:29) (Fork:5) (Watch:2)  
* [BeeFramework](https://github.com/gavinkwoe/BeeFramework) -  与ReactiveCocoa类似，[BeeFramework用户指南 v1.0](http://www.lanrenios.com/tutorials/all/2012/1220/641.html)。   ---- (Star:3,379) (Fork:1,186) (Watch:416)  
* [Objective-Chain](https://github.com/Tricertops/Objective-Chain) - Objective-Chain是一个面向对象的响应式框架，作者表示该框架吸收了 ReactiveCocoa 的思想，并且想做得更面向对象一些。   ---- (Star:253) (Fork:22) (Watch:12)  
* [MVVMFramework](https://github.com/lovemo/MVVMFramework) - (OC版)总结整理下一个快速开发框架，分离控制器中创建tableView和collectionView的代码，已加入cell自适应高度，降低代码耦合，提高开发效率。   ---- (Star:1,004) (Fork:302) (Watch:49)  

#### framework@

* [Small](https://github.com/wequick/Small) A small framework to split app into small parts   ---- (Star:3,550) (Fork:895) (Watch:254)  

#### 混合开发@

* [rexxar-ios](https://github.com/douban/rexxar-ios) 豆瓣推的混合开发库 Mobile Hybrid Framework Rexxar iOS Container   ---- (Star:450) (Fork:74) (Watch:20)  

#### 服务端@后台@

* [GCDWebServer](https://github.com/swisspol/GCDWebServer) 基于GCD的轻量级的HTTP服务器   ---- (Star:3,608) (Fork:585) (Watch:176)  

#### 网络@
#### 网络请求@

* [AFNetworking](https://github.com/AFNetworking/AFNetworking) - ASI不升级以后，最多人用的网络连接开源库 [iOS开发下载文件速度计算](http://www.superqq.com/blog/2015/01/29/ioskai-fa-xia-zai-wen-jian-su-du-ji-suan/) , [AFNetworking 3.0迁移指南](http://www.cocoachina.com/ios/20151022/13831.html) , [AFNetworking2.0源码解析<一>](http://www.cocoachina.com/ios/20140829/9480.html) 、[AFNetworking2.0源码解析<二>](http://www.cocoachina.com/ios/20140904/9523.html)、[AFNetworking源码解析<三>](http://www.cocoachina.com/ios/20140916/9632.html)、[AFNetworking源码解析<四>](http://www.cocoachina.com/ios/20141120/10265.html)。   ---- (Star:30,145) (Fork:9,406) (Watch:1,792)  
* [YTKNetwork](https://github.com/yuantiku/YTKNetwork) - 是基于 AFNetworking 封装的 iOS网络库，提供了更高层次的网络访问抽象。相比AFNetworking，YTKNetwork提供了以下更高级的功能：按时间或版本号缓存网络请求内容、检查返回 JSON 内容的合法性、文件的断点续传、批量的网络请求发送、filter和插件机制等，猿题库出品.   ---- (Star:4,774) (Fork:1,362) (Watch:233)  
* [RestKit](https://github.com/RestKit/RestKit) RestKit是一款专为iOS设计的Objective-C框架，旨在与RESTful web服务的交互变得更简单快速。它基于强大的对象映射系统，并且结合了一个干净、简单的HTTP请求/响应API，大大减少了完成任务所需的代码量。 RestKit is a framework for consuming and modeling RESTful web resources on iOS and OS X   ---- (Star:10,164) (Fork:2,256) (Watch:468)  
* [HYBNetworking](https://github.com/CoderJackyHuang/HYBNetworking) - 基于AFN封装的网络库，可以通用。[基于AFNetworking封装网络库说明](http://www.henishuo.com/base-on-afnetworking-wrapper/)目前已经提供了通用的GET/POST、上传、下载API等。   ---- (Star:519) (Fork:174) (Watch:28)  
* [LxFTPRequest](https://github.com/DeveloperLx/LxFTPRequest) - 支持获取FTP服务器资源列表，下载/上传文件，创建/销毁ftp服务器文件/目录，以及下载断点续传，下载/上传进度，自动判断地址格式合法性跟踪等功能！国人开发，QQ：349124555。   ---- (Star:99) (Fork:31) (Watch:8)  
* [ASIHTTPRequest](https://github.com/pokeb/asi-http-request) - Easy to use CFNetwork wrapper for HTTP requests, Objective-C, macOS and iPhone.   ---- (Star:5,794) (Fork:1,499) (Watch:292)  
* [HSDownloadManager](https://github.com/HHuiHao/HSDownloadManager) - HSDownloadManager，下载音乐、视频、图片各种资源，支持多任务、断点下载。   ---- (Star:204) (Fork:84) (Watch:7)  
* [MutableUploadDemo](https://github.com/HHuiHao/MutableUploadDemo) - 模拟需求：图文混编，要求用户选择图片后就上传，可选择多图，并行上传，用户确定提交后后台执行，必须全部图片上传完才能提交文字。   ---- (Star:20) (Fork:9) (Watch:2)  
* [WTRequestCenter](https://github.com/swtlovewtt/WTRequestCenter) - 方便缓存的请求库，提供了方便的HTTP请求方法，传入请求url和参数，返回成功和失败的回调。 UIKit扩展提供了许多不错的方法，快速缓存图片，图片查看，缩放功能， 颜色创建，设备UUID，网页缓存，数据缓存等功能。 无需任何import和配置，目前实现了基础需求。   ---- (Star:293) (Fork:93) (Watch:27)  
* [MMWormhole](https://github.com/mutualmobile/MMWormhole) - Message passing between iOS apps and extensions 2个iOS设备之间通信。   ---- (Star:3,311) (Fork:244) (Watch:141)  
* [STNetTaskQueue](https://github.com/kevin0571/STNetTaskQueue) - STNetTaskQueue Objective-C 可扩展网络请求管理库。   ---- (Star:83) (Fork:11) (Watch:5)  
* [MZDownloadManager](https://github.com/mzeeshanid/MZDownloadManager) - 下载管理。   ---- (Star:829) (Fork:162) (Watch:43)  
* [DVR](https://github.com/venmo/DVR) - 针对网络请求的测试框架，超实用的工具。且支持 iOS, OSX, watchOS 全平台。   ---- (Star:506) (Fork:54) (Watch:35)  
* [HFDownLoad](https://github.com/hongfenglt/HFDownLoad) - iOS开发网络篇之文件下载、大文件下载、断点下载:NSData方式、NSURLConnection方式、NSURLSession下载方式 [下载方式具体的思路、区别见Blog](http://blog.csdn.net/hongfengkt/article/details/48290561) 。   ---- (Star:94) (Fork:33) (Watch:4)  
* [PPNetworkHelper](https://github.com/jkpang/PPNetworkHelper) - AFN3.x与YYCache的二次封装,一句话搞定网络请求与缓存,和FMDB说拜拜!   ---- (Star:834) (Fork:205) (Watch:30)  
* [WANetworkRouting](https://github.com/Wasappli/WANetworkRouting) - An iOS library to route API paths to objects on client side with request, mapping, routing and auth layers   ---- (Star:10) (Fork:1) (Watch:2)  
* [Overcoat](https://github.com/Overcoat/Overcoat) - Small but powerful library that makes creating REST clients simple and fun.   ---- (Star:1,136) (Fork:109) (Watch:42)  
* [ROADFramework](https://github.com/epam/road-ios-framework) - Attributed-oriented approach for interacting with web services. The framework has built-in json and xml serialization for requests and responses and can be easily extensible.   ---- (Star:50) (Fork:17) (Watch:27)  
* [TWRDownloadManager](https://github.com/chasseurmic/TWRDownloadManager) - A modern download manager based on NSURLSession to deal with asynchronous downloading, management and persistence of multiple files.   ---- (Star:329) (Fork:90) (Watch:13)  
* [HappyDns](https://github.com/qiniu/happy-dns-objc) - A Dns library, support custom dns server, dnspod httpdns. Only support A record.   ---- (Star:311) (Fork:48) (Watch:18)  
* [Bridge](https://github.com/BridgeNetworking/Bridge) - A simple extensible typed networking library. Intercept and process/alter requests and responses easily. :large_orange_diamond:   ---- (Star:93) (Fork:4) (Watch:7)  
* [EVCloudKitDao](https://github.com/evermeer/EVCloudKitDao) - Simplified access to Apple's CloudKit :large_orange_diamond:   ---- (Star:507) (Fork:53) (Watch:28)  
* [Siesta](https://bustoutsolutions.github.io/siesta/) - Elegant abstraction for RESTful resources that untangles stateful messes. An alternative to callback- and delegate-based networking. :large_orange_diamond:
* [OctopusKit](https://github.com/icoco/OctopusKit) - A simplicity but graceful solution for invoke RESTful web service APIs.   ---- (Star:1) (Fork:3) (Watch:0)  
* [EVURLCache](https://github.com/evermeer/EVURLCache) - a NSURLCache subclass for handling all web requests that use NSURLRequest :large_orange_diamond:   ---- (Star:249) (Fork:50) (Watch:13)  
* [ResponseDetective](https://github.com/netguru/ResponseDetective) - Sherlock Holmes of the networking layer. :large_orange_diamond:   ---- (Star:1,651) (Fork:67) (Watch:32)  
* [agent](https://github.com/hallas/agent) - Minimalistic Swift HTTP request agent for iOS and macOS :large_orange_diamond:   ---- (Star:610) (Fork:51) (Watch:31)  
* [Reach](https://github.com/Isuru-Nanayakkara/Reach) - A simple class to check for internet connection availability in Swift. :large_orange_diamond:、   ---- (Star:420) (Fork:116) (Watch:25)  
* [SwiftHTTP](https://github.com/daltoniam/SwiftHTTP) - Thin wrapper around NSURLSession in swift. Simplifies HTTP requests. :large_orange_diamond:   ---- (Star:1,699) (Fork:325) (Watch:104)  
* [NetKit](https://github.com/azizuysal/NetKit) - A Concise HTTP Framework in Swift. :large_orange_diamond:   ---- (Star:4) (Fork:4) (Watch:2)  
* [MonkeyKing](https://github.com/nixzhu/MonkeyKing) - MonkeyKing helps you post messages to Chinese Social Networks. :large_orange_diamond:   ---- (Star:1,869) (Fork:168) (Watch:52)  
* [NetworkKit](https://github.com/imex94/NetworkKit) - Lightweight Networking and Parsing framework made for iOS, Mac, WatchOS and tvOS. :large_orange_diamond:   ---- (Star:27) (Fork:5) (Watch:3)  
* [APIKit](https://github.com/ishkawa/APIKit) - A networking library for building type safe web API client in Swift. :large_orange_diamond:   ---- (Star:1,277) (Fork:126) (Watch:56)  
* [SPTDataLoader](https://github.com/spotify/SPTDataLoader) - The HTTP library used by the Spotify iOS client.   ---- (Star:582) (Fork:53) (Watch:125)  
* [SWNetworking](https://github.com/skywite/SWNetworking) - Powerful high-level iOS, macOS and tvOS networking library.   ---- (Star:21) (Fork:11) (Watch:5)  
* [SOAPEngine](https://github.com/priore/SOAPEngine) - This generic SOAP client allows you to access web services using a your iOS app, macOS app and AppleTV app.   ---- (Star:426) (Fork:76) (Watch:29)  
* [Swish](https://github.com/thoughtbot/Swish) - Nothing but Net(working) :large_orange_diamond:   ---- (Star:353) (Fork:31) (Watch:17)  
* [Malibu](https://github.com/hyperoslo/Malibu) - :surfer: Malibu is a networking library built on promises :large_orange_diamond:   ---- (Star:296) (Fork:20) (Watch:23)  
* [UnboxedAlamofire](https://github.com/serejahh/UnboxedAlamofire) - Alamofire + Unbox: the easiest way to download and decode JSON into swift objects. :large_orange_diamond:   ---- (Star:56) (Fork:10) (Watch:5)  
* [MMLanScan](https://github.com/mavris/MMLanScan) - An iOS LAN Network Scanner library   ---- (Star:218) (Fork:52) (Watch:19)  
* [Domainer](https://github.com/FelixLinBH/Domainer) - Manage multi-domain url auto mapping ip address table   ---- (Star:6) (Fork:0) (Watch:2)  
* [Restofire](https://github.com/Restofire/Restofire) - Restofire is a protocol oriented network abstraction layer in swift that is built on top of Alamofire to use services in a declartive way :large_orange_diamond:   ---- (Star:146) (Fork:9) (Watch:6)  
* [AFNetworking+RetryPolicy](https://github.com/kubatruhlar/AFNetworking-RetryPolicy) - An objective-c category that adds the ability to set the retry logic for requests made with AFNetworking.   ---- (Star:152) (Fork:19) (Watch:8)  
* [Nikka](https://github.com/JustaLab/Nikka) - A super simple Networking wrapper that supports many JSON libraries, Futures and Rx :large_orange_diamond: ⌚   ---- (Star:12) (Fork:1) (Watch:3)  
* [XMNetworking](https://github.com/kangzubin/XMNetworking) - A lightweight but powerful network library with simplified and expressive syntax based on AFNetworking.   ---- (Star:710) (Fork:114) (Watch:35)  
* [Merhaba](https://github.com/abdullahselek/Merhaba) - Bonjour networking for discovery and connection between iOS, macOS and tvOS devices.   ---- (Star:33) (Fork:3) (Watch:3)  
* [DBNetworkStack](https://github.com/dbsystel/DBNetworkStack) - Resource-oritented networking which is typesafe, extendable, composeable and makes testing a lot easier. :large_orange_diamond:   ---- (Star:17) (Fork:0) (Watch:5)  
* [EFInternetIndicator](https://github.com/ezefranca/EFInternetIndicator) - A little swift Internet error status indicator using ReachabilitySwift. :large_orange_diamond:   ---- (Star:105) (Fork:4) (Watch:4)  
* [AFNetworking-Synchronous](https://github.com/paulmelnikow/AFNetworking-Synchronous) - Synchronous requests for AFNetworking 1.x, 2.x, and 3.x.   ---- (Star:143) (Fork:20) (Watch:11)  
* [QwikHttp](https://github.com/logansease/QwikHttp) - a robust, yet lightweight and simple to use HTTP networking library designed for RESTful APIs. 🔶   ---- (Star:1) (Fork:1) (Watch:1)  
* [NetClient](https://github.com/intelygenz/NetClient-iOS) - Versatile HTTP networking library written in Swift 3. :large_orange_diamond:   ---- (Star:56) (Fork:5) (Watch:9)  
* [Reactor](https://github.com/MailOnline/Reactor) - Powering your RAC architecture :large_orange_diamond:   ---- (Star:179) (Fork:12) (Watch:52)  

#### socket@

* [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket) - 无疑是目前封装得最完善的Socket库了：支持异步TCP/UDP，支持GCD，Objective-C接口封装[使用教程](http://www.superqq.com/blog/2015/04/03/ioskai-fa-zhi-asyncsocketshi-yong-jiao-cheng/)。   ---- (Star:9,282) (Fork:2,469) (Watch:581)  
* [SocketRocket](https://github.com/facebook/SocketRocket) 一个非常不错的 Objective-C 的Socket 库   ---- (Star:7,228) (Fork:1,486) (Watch:326)  
* [AsyncSocket](https://github.com/roustem/AsyncSocket) - AsyncSocket。   ---- (Star:183) (Fork:88) (Watch:19)  
* [Socket通信](http://code.cocoachina.com/view/128711) - 通过AsyncSocket封装的Socket通讯方法，简单实用，通俗易懂，初学者不能错过 。
* [GCDAsyncSocket](https://github.com/eugenehp/GCDAsyncSocket) - GCDAsyncSocket ， [不错的Demo](https://github.com/smalltask/TestTcpConnection)。   ---- (Star:53) (Fork:22) (Watch:5)  

#### 网络下载@

* [WHCNetWorkKit](https://github.com/netyouli/WHCNetWorkKit) WHCNetWorkKit 是http网络请求开源库(支持GET/POST 文件上传 后台文件下载 UIButton UIImageView 控件设置网络图片 网络数据工具json/xml 转模型类对象 网络状态监听)   ---- (Star:412) (Fork:125) (Watch:26)  
* [HSDownloadManager](https://github.com/HHuiHao/HSDownloadManager)下载音乐、视频、图片各种资源，支持多任务、断点下载！   ---- (Star:204) (Fork:84) (Watch:7)  

#### 网络聊天@

* [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController) - 非常👍👍👍 的聊天界面框架   ---- (Star:10,810) (Fork:2,653) (Watch:415)  
* [XMPPFramework](https://github.com/robbiehanson/XMPPFramework) - XMPPFramework openfire聊天。   ---- (Star:5,269) (Fork:2,025) (Watch:407)  
* [MessageDisplayKit](https://github.com/xhzengAIB/MessageDisplayKit) - 仿微信聊天，参考JSQMessagesViewController。（国人写）   ---- (Star:3,991) (Fork:1,241) (Watch:245)  
* [SXTheQQ](https://github.com/dsxNiubility/SXTheQQ) - 用xmppFramework框架编写QQ程序，主要为了练习通讯的一些原理，界面比较渣 必须要先在本地配置好环境才可以运行。   ---- (Star:59) (Fork:18) (Watch:5)  
* [环信](http://www.easemob.com/) - 给开发者更稳定IM云功能。8200万用户考验，好用！（暂无及时语音、视频通话）
* [融云](http://www.rongcloud.cn/) - 即时通讯云服务提供商。（暂无及时语音、视频通话）
* [容联云通讯](http://www.yuntongxun.com) - 提供基于互联网通话,视频会议,呼叫中心/IVR,IM等通讯服务。
* [ChatSecure-iOS](https://github.com/ChatSecure/ChatSecure-iOS) - 基于XMPP的iphone、android加密式聊天软件， [chatsecure官网](https://chatsecure.org/) 。 [iOS代码1](https://github.com/ChatSecure/ChatSecure-iOS)，[iOS代码2](https://github.com/ChatSecure/ChatSecure-iOS)， [iOS中文版](http://www.cocoachina.com/bbs/read.php?tid=153156)。   ---- (Star:2,476) (Fork:917) (Watch:193)  
* [chatsecure](https://github.com/ChatSecure/ChatSecure-iOS) - 基于XMPP的iphone、android加密式聊天软件， [chatsecure官网](https://chatsecure.org/) 。 [iOS代码1](https://github.com/ChatSecure/ChatSecure-iOS)，[iOS代码2](https://github.com/ChatSecure/ChatSecure-iOS)， [iOS中文版](http://www.cocoachina.com/bbs/read.php?tid=153156)。   ---- (Star:2,476) (Fork:917) (Watch:193)  
* [SunFlower](https://github.com/HanYaZhou1990/-SunFlower) - 环信聊天demo，比较多功能 。   ---- (Star:12) (Fork:0) (Watch:6)  
* [BlueTalk蓝牙聊天](http://code4app.com/ios/BlueTalk%E8%93%9D%E7%89%99%E8%81%8A%E5%A4%A9-%E6%89%8B%E6%9C%BA%E4%B9%8B%E9%97%B4/552b8190933bf0291e8b4748) - 以MultipeerConnectivity为基础， 实现了简单的蓝牙聊天。

#### 网络测试@

* [Reachability](https://github.com/tonymillion/Reachability) - 苹果提供过一个Reachability类，用于检测网络状态。但是该类由于年代久远，并不支持ARC。该项目旨在提供一个苹果的Reachability类的替代品，支持ARC和block的使用方式。[iOS网络监测如何区分2、3、4G](http://www.jianshu.com/p/efcfa3c87306)      ---- (Star:6,448) (Fork:1,196) (Watch:289)  
* [SimpleCarrier](https://github.com/crazypoo/SimpleCarrier) - 简单的运营商信息获取!。   ---- (Star:15) (Fork:5) (Watch:1)  
* [NetworkEye](https://github.com/coderyi/NetworkEye) - 一个网络调试库，可以监控App内HTTP请求并显示请求相关的详细信息，方便App开发的网络调试。   ---- (Star:1,014) (Fork:171) (Watch:44)  
* [RealReachability](https://github.com/dustturtle/RealReachability) - [iOS下的实际网络连接状态检测](http://www.cocoachina.com/ios/20160224/15407.html)，解决“如何判断设备是否真正连上互联网？而不是只有网络连接”的问题。   ---- (Star:2,417) (Fork:407) (Watch:96)  
* [LDNetDiagnoService_IOS](https://github.com/Lede-Inc/LDNetDiagnoService_IOS) IOS平台利用ping和traceroute的原理，对指定域名（通常为后台API的提供域名）进行网络诊断，并收集诊断日志。   ---- (Star:529) (Fork:139) (Watch:30)  
* [Netfox](https://github.com/kasketis/netfox) - A lightweight, one line setup, iOS / macOS network debugging library! :large_orange_diamond:   ---- (Star:1,993) (Fork:134) (Watch:44)  

#### WebView与WKWebView@

* [WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge) 是一个连接javascript和iOS Native交互的开源框架。使用它可以在UIWebview中响应事件并执行Native方法,也可以使用Native方法调用javascript方法, 正如其名,它好像已做桥梁连接了两端.   ---- (Star:9,538) (Fork:2,205) (Watch:464)  
* [MGTemplateEngine](https://github.com/mattgemmell/MGTemplateEngine) - MGTemplateEngine比较象 PHP 中的 Smarty、FreeMarker 和 Django的模版引擎，是一个轻量级的引擎，简单好用。只要设置很多不同的HMTL模版，就能轻松的实现一个View多种内容格式的显示，对于不熟悉HTML或者减轻 工作量而言，把这些工作让设计分担一下还是很好的，也比较容易实现设计想要的效果。   ---- (Star:373) (Fork:81) (Watch:12)  
* [GTMNSString-HTML](https://github.com/siriusdely/GTMNSString-HTML) - 谷歌开源的用于过滤HTML标签。   ---- (Star:315) (Fork:65) (Watch:12)  
* [D3Generator](https://github.com/mozhenhau/D3Generator/) - D3Generator根据dict字典生成对象。 适用webview和push推送时，根据后台传回字典实现动态跳转。[实现说明](http://mozhenhau.com/2016/02/07/D3Generator实现万能跳转界面，UIWebview与js随意交互/)   ---- (Star:25) (Fork:6) (Watch:2)  
* [GRMustache] (https://github.com/groue/GRMustache) 一个类似templateEngine的html渲染工具，可以更加有效的帮助大家完成数据生成HTML的过程。   ---- (Star:1,323) (Fork:180) (Watch:44)  
* [iOS-WebView-JavaScript](https://github.com/shaojiankui/iOS-WebView-JavaScript) iOS UIWebView,WKWebView 与 JavaScript的深度交互   ---- (Star:137) (Fork:44) (Watch:6)  
* [WKWebView](https://github.com/XFIOSXiaoFeng/WKWebView) OC版WKWebView 支持POST请求 加载本地页面 直接加载网页 JS交互 集成支付宝/微信URL支付功能 仿微信返回按钮   ---- (Star:138) (Fork:38) (Watch:4)  
* [BAWKWebView](https://github.com/BAHome/BAWKWebView) 用分类封装 WKWebView，一行代码搞定 request、URL、URLString、本地 HTML文件、HTMLString等请求，一个 block 搞定 title、progress、currentURL、当前网页的高度等等所需   ---- (Star:103) (Fork:16) (Watch:2)  

#### 网络解析@
#### JSON@

* [MJExtension](https://github.com/CoderMJLee/MJExtension) - 用于json转model进行使用，转换效率很高，使用也比较简单，只要前后台约定好，json直接就转成了model。   ---- (Star:7,284) (Fork:2,121) (Watch:354)  
* [YYModel](https://github.com/ibireme/YYModel) - High performance model framework for iOS/OSX.   ---- (Star:3,122) (Fork:645) (Watch:86)  
* [jsonmodel](https://github.com/jsonmodel/jsonmodel) Magical Data Modeling Framework for JSON - allows rapid creation of smart data models. You can use it in your iOS, macOS, watchOS and tvOS apps.   ---- (Star:6,336) (Fork:1,058) (Watch:277)  
* [JSONKit](https://github.com/johnezang/JSONKit) - JSONKit库是非常简单易用而且效率又比较高的，重要的JSONKit适用于ios 5.0以下的版本,使用JSONKit库来解析json文件，只需要下载JSONKit.h 和JSONKit.m添加到工程中；然后加入libz.dylib即可。   ---- (Star:6,143) (Fork:1,773) (Watch:355)  
* [JSONModel](https://github.com/icanzilb/JSONModel) - 解析服务器返回的Json数据的库,[JSONModel源码解析一](http://www.jianshu.com/p/3d795ea37835)。   ---- (Star:6,336) (Fork:1,058) (Watch:277)  
* [Mantle](https://github.com/Mantle/Mantle) - Mantle主要用来将JSON数据模型化为OC对象, 大系统中使用。[为什么选择Mantle](http://blog.csdn.net/itianyi/article/details/40789273)。   ---- (Star:10,771) (Fork:1,464) (Watch:431)  
* [RFJModel](https://github.com/refusebt/RFJModel) - RFJModel是一个IOS类库，可以将JSON字典自动装填到OBJC对象。相比JSONModel有一些非常好的特性，使用上也比较简单。   ---- (Star:143) (Fork:31) (Watch:9)  
* [XMLDictionary](https://github.com/nicklockwood/XMLDictionary) - ios与mac os平台下xml与NSDictionary相互转化开源类库。   ---- (Star:1,132) (Fork:255) (Watch:39)  
* [DDModel](https://github.com/openboy2012/DDModel) - 快速搭建项目Model层，支持ORM映射关系，能从JSON/XML直接实例一个Model对象。支持SQLite本地数据持久化，封装了HTTP， 减少HTTP代码与UIViewController的代码耦合，支持Cache；类似RESTKit、Mantle的功能；使用该类库以后简化了网络层的开发工作，把更多的精力放在UI上面；目前只支持GET/POST方法的请求。使用到的第三方库有：1.SQLitePersistentObject; 2.JTObjectMapping; 3.AFNetworking; 4.XMLDictionary;   ---- (Star:67) (Fork:19) (Watch:3)  
* [TouchJSON](https://github.com/TouchCode/TouchJSON) - JSon解析库(早已停止更新)   ---- (Star:821) (Fork:180) (Watch:26)  
* [JSON-Framework](https://github.com/stig/json-framework) -  JSON解析库   ---- (Star:3,800) (Fork:770) (Watch:164)  
* [Groot](https://github.com/gonzalezreal/Groot) - From JSON to Core Data and back.   ---- (Star:478) (Fork:52) (Watch:24)  
* [KZPropertyMapper](https://github.com/krzysztofzablocki/KZPropertyMapper) - 可以帮助你在对象与Array、Dict数据间进行转换，尤其适用于将json对象转换成objective-c中的实体对象。作者还写了一篇文章[stop-writing-data-parsing-code-in-your-apps](http://merowing.info/2013/07/stop-writing-data-parsing-code-in-your-apps/)介绍它的使用。   ---- (Star:1,119) (Fork:89) (Watch:29)  
* [FastEasyMapping](https://github.com/Yalantis/FastEasyMapping) - 一个快速对json进行序列化和反序列化的工具 A tool for fast serializing & deserializing of JSON.   ---- (Star:522) (Fork:78) (Watch:39)  
* [OCMapper](https://github.com/aryaxt/OCMapper) - （一年未更新）OCMapper 是 Objective-C 和 Swift 库，它可以很容易地将 NSDictionary 映射到模型目标上。Objective-C & Swift library to easily map NSDictionary to model objects, works perfectly with Alamofire. ObjectMapper works similar to GSON   ---- (Star:348) (Fork:40) (Watch:18)  
* [Gloss](https://github.com/hkellaway/Gloss) - 一个很棒的Swift +json解析库.   ---- (Star:1,569) (Fork:131) (Watch:43)  
* [Cereal](https://github.com/Weebly/Cereal) - 对象序列化三方库 Swift object serialization   ---- (Star:376) (Fork:17) (Watch:16)  
* [SwiftyJSONAccelerator](https://github.com/insanoid/SwiftyJSONAccelerator) - json转model的三方库 Generate Swift model files from JSON using either SwiftyJSON or ObjectMapper. Supports NSCoding and provides method for JSON string representation of the model.   ---- (Star:648) (Fork:79) (Watch:45)  

* [Tyro](htt  ps://github.com/typelift/Tyro) - Functional JSON parsing and encoding :large_orange_diamond:
* [Unbox](https://github.com/JohnSundell/Unbox) - The easy to use Swift JSON decoder :large_orange_diamond:   ---- (Star:1,740) (Fork:121) (Watch:29)  
* [JSONJoy-Swift](https://github.com/daltoniam/JSONJoy-Swift) - Convert JSON to Swift objects. :large_orange_diamond:   ---- (Star:349) (Fork:67) (Watch:30)  
* [LazyObject](https://github.com/iwasrobbed/LazyObject) - Lazily deserialize JSON into strongly typed Swift objects :large_orange_diamond:   ---- (Star:10) (Fork:0) (Watch:3)  
* [Elevate](https://github.com/Nike-Inc/Elevate) - Elevate is a JSON parsing framework that leverages Swift to make parsing simple, reliable and composable. :large_orange_diamond:   ---- (Star:606) (Fork:40) (Watch:28)  
* [AlamofireObjectMapper](https://github.com/tristanhimmelman/AlamofireObjectMapper) - An Alamofire extension which converts JSON response data into swift objects using ObjectMapper :large_orange_diamond:   ---- (Star:2,006) (Fork:274) (Watch:55)  
* [WAMapping](https://github.com/Wasappli/WAMapping) 一个将字典和iOS对象相互转化的库. A library to turn dictionary into object and vice versa for iOS. Designed for speed!   ---- (Star:9) (Fork:1) (Watch:2)  

#### XML&HTML@

* [AEXML](https://github.com/tadija/AEXML) - Simple and lightweight XML parser written in Swift. :large_orange_diamond:   ---- (Star:699) (Fork:146) (Watch:37)  
* [Ji](https://github.com/honghaoz/Ji) - XML/HTML parser for Swift. :large_orange_diamond:   ---- (Star:731) (Fork:48) (Watch:17)  
* [Ono](https://github.com/mattt/Ono) - A sensible way to deal with XML & HTML for iOS & OS X   ---- (Star:2,174) (Fork:173) (Watch:54)  
* [AlamofireXmlToObjects](https://github.com/evermeer/AlamofireXmlToObjects) - Fetch a XML feed and parse it into objects :large_orange_diamond:   ---- (Star:62) (Fork:7) (Watch:5)  
* [Fuzi](https://github.com/cezheng/Fuzi) - A fast & lightweight XML & HTML parser in Swift with XPath & CSS support :large_orange_diamond:   ---- (Star:613) (Fork:66) (Watch:28)  
* [Kanna](https://github.com/tid-kijyun/Kanna)  - Kanna(鉋) is an XML/HTML parser for MacOSX/iOS. :large_orange_diamond:   ---- (Star:1,424) (Fork:141) (Watch:43)  
* [SwiftyXMLParer](https://github.com/yahoojapan/SwiftyXMLParser) - Simple XML Parser implemented in Swift  :large_orange_diamond:   ---- (Star:141) (Fork:21) (Watch:6)  
* [HTMLKit](https://github.com/iabudiab/HTMLKit) - An Objective-C framework for your everyday HTML needs.   ---- (Star:86) (Fork:6) (Watch:4)  
* [SWXMLHash](https://github.com/drmohundro/SWXMLHash) - Simple XML parsing in Swift :large_orange_diamond:   ---- (Star:856) (Fork:141) (Watch:28)  

#### Other Parsing@

* [WKZombie](https://github.com/mkoehnke/WKZombie) - WKZombie is a Swift framework for iOS/OSX to navigate within websites and collect data without the need of User Interface or API, also known as Headless browser. It can be used to run automated tests or manipulate websites using Javascript. :large_orange_diamond:   ---- (Star:874) (Fork:62) (Watch:26)  
* [URLPreview](https://github.com/itsmeichigo/URLPreview) - An NSURL extension for showing preview info of webpages :large_orange_diamond: [e]   ---- (Star:182) (Fork:12) (Watch:7)  
* [FeedKit](https://github.com/nmdias/FeedKit) - An RSS and Atom feed parser written in Swift :large_orange_diamond:   ---- (Star:370) (Fork:33) (Watch:12)  
* [Erik](https://github.com/phimage/Erik) - Erik is an headless browser based on WebKit. An headless browser allow to run functional tests, to access and manipulate webpages using javascript. :large_orange_diamond:   ---- (Star:249) (Fork:24) (Watch:11)  
[Erik](https://github.com/phimage/Erik) - Erik is an headless browser based on WebKit. An headless browser allow to run functional tests, to access and manipulate webpages using javascript. :large_orange_diamond:

#### 数据存储@

* [FMDB](https://github.com/ccgus/fmdb) - sqlite的工具， [多线程FMDatabaseQueue实例](https://github.com/tangqiaoboy/FmdbSample)，[FMDB数据库的使用演示和封装工具类](https://github.com/liuchunlao/LVDatabaseDemo)，[基于fmdb 的基本操作](http://code.cocoachina.com/view/128312) 通过 fmdb 进行的数据库的 基本操作(增删改查 )查找是使用 UISearchBar 和UISearchDisplayController 进行混合使用。   ---- (Star:11,996) (Fork:2,662) (Watch:582)  
* [GDataBase](https://github.com/GIKICoder/GDataBase) - 基于FMDB的ORM数据库存储解决方案. 面向模型和线程安全的API. 一句代码存储,读取.对存储模型无需继承BaseObject. 可自定义多主键,可使用sqlite关键字.可自定义序列化字段等.支持模型黑名单.支持数据库表存储value base64编/解码.对模型无侵入,只需遵守相关协议即可.极大方便项目中使用.   ---- (Star:32) (Fork:7) (Watch:2)  
* [realm-cocoa](https://github.com/realm/realm-cocoa) 一个号称要代替Core Data & SQLite的用于移动端的数据库，非常不错👍👍 ，同时支持Swift.   ---- (Star:11,404) (Fork:1,463) (Watch:413)  
* [YapDatabase](https://github.com/yapstudios/YapDatabase) - YapDatabase is an extensible database for iOS & Mac.   ---- (Star:2,929) (Fork:316) (Watch:108)  
* [CoreModel](https://github.com/CharlinFeng/CoreModel) Replace CoreData   ---- (Star:748) (Fork:182) (Watch:53)  
* [WHC_ModelSqliteKit](https://github.com/netyouli/WHC_ModelSqliteKit) 专业的数据库存储解决方案   ---- (Star:427) (Fork:105) (Watch:20)  
* [JQFMDB](https://github.com/gaojunquan/JQFMDB) FMDB的封装,操作简单,线程安全,扩展性强,直接操作model或dictionary   ---- (Star:274) (Fork:52) (Watch:3)  
* [RealmObjectEditor](https://github.com/Ahmed-Ali/RealmObjectEditor) Realm Object Editor is a visual editor where you can create your Realm entities, attributes and relationships inside a nice user interface. Once you finish, you can save your schema document for later use and you can export your entities in Swift, Objective-C and Java.   ---- (Star:406) (Fork:42) (Watch:22)  
* [sqlitebrowser](https://github.com/sqlitebrowser/sqlitebrowser) Official home of the DB Browser for SQLite (DB4S) project. Previously known as "SQLite Database Browser" and "Database Browser for SQLite". Website at: http://sqlitebrowser.org   ---- (Star:7,084) (Fork:922) (Watch:382)  
* [GXDatabaseUtils](https://github.com/Gerry1218/GXDatabaseUtils) - 在FMDB基础上的工具。   ---- (Star:26) (Fork:8) (Watch:2)  
* [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) - CoreData第一库，MagicalRecord就像是给Core Data提供了一层外包装，隐藏掉所有不相关的东西。 其中事务管理及查询是其比较大的亮点，整套 API 功能完整。   ---- (Star:10,510) (Fork:1,863) (Watch:457)  
* [GKDatabase](https://github.com/ChrisCaixx/GKDatabase) -基于SQLite3简单封装了下,实现了一行代码解决增删改查等常用的功能!并没有太过高深的知识,主要用了runtime和KVC:请看Demo~ 原理篇请看这里:[简书地址](http://www.jianshu.com/p/0e598147debc)   ---- (Star:102) (Fork:19) (Watch:3)  
* [CoreStore](https://github.com/AfryMask/AFBrushBoard) -  Core Data 管理类库。 其中事务管理及查询是其比较大的亮点，整套 API 功能完整。   ---- (Star:522) (Fork:69) (Watch:14)  
* [mogenerator](http://rentzsch.github.io/mogenerator/) - mogenerator为你定义了的Core Data生成默认的数据类。与xCode不一样的是(xCode一个Entity只生成一个NSManagedObject的子类)，mogenerator会为每一个Entity生成两个类。一个为机器准备，一个为人类准备。为机器准备的类一直去匹配data model。为人类准备的类就给你轻松愉快的去修改和保存。
* [Presentation](https://github.com/hyperoslo/Presentation) - 重量级好项目 Presentation，它可以方便你制作定制的动画式教程、Release Notes、个性化演讲稿等。   ---- (Star:2,278) (Fork:135) (Watch:66)  
* [SQLCipher](https://github.com/sqlcipher/sqlcipher) - SQLCipher使用256-bit AES加密，SQLCipher分为收费版本和免费版本。[官方教程](https://www.zetetic.net/sqlcipher/ios-tutorial/)， [加密你的SQLite](http://foggry.com/blog/2014/05/19/jia-mi-ni-de-sqlite/) - 各种sqlite数据库加密介绍。 [SQLCipherDemo下载](http://download.csdn.net/detail/wzzvictory_tjsd/7379055) 。   ---- (Star:2,555) (Fork:641) (Watch:206)  
* [Couchbase Mobile](https://developer.couchbase.com/mobile/) - Couchbase document store for mobile with cloud sync.
* [FCModel](https://github.com/marcoarment/FCModel) - An alternative to Core Data for people who like having direct SQL access.   ---- (Star:1,638) (Fork:175) (Watch:71)  
* [Zephyr](https://github.com/ArtSabintsev/Zephyr) - Effortlessly synchronize NSUserDefaults over iCloud. :large_orange_diamond:   ---- (Star:381) (Fork:27) (Watch:10)  
* [Storez](https://github.com/SwiftKitz/Storez) - Safe, statically-typed, store-agnostic key-value storage (with namespace support). :large_orange_diamond:   ---- (Star:46) (Fork:3) (Watch:5)  
* [ParseAlternatives](https://github.com/relatedcode/ParseAlternatives) - A collaborative list of Parse alternative backend service providers.   ---- (Star:2,598) (Fork:301) (Watch:146)  
* [TypedDefaults](https://github.com/tasanobu/TypedDefaults) - TypedDefaults is a utility library to type-safely use NSUserDefaults. :large_orange_diamond:   ---- (Star:109) (Fork:3) (Watch:2)  
* [realm-cocoa-converter](https://github.com/realm/realm-cocoa-converter) - A library that provides the ability to import/export Realm files from a variety of data container formats. :large_orange_diamond:   ---- (Star:140) (Fork:15) (Watch:11)  
* [RealmGeoQueries](https://github.com/mhergon/RealmGeoQueries) - RealmGeoQueries simplifies spatial queries with Realm Cocoa. In the absence of and official functions, this library provide the possibility to do proximity search.  :large_orange_diamond:[e]   ---- (Star:95) (Fork:15) (Watch:6)  
* [ObjectiveRocks](https://github.com/iabudiab/ObjectiveRocks) - An Objective-C wrapper of Facebook's RocksDB - A Persistent Key-Value Store for Flash and RAM Storage.   ---- (Star:37) (Fork:6) (Watch:1)  
* [OHMySQL](https://github.com/oleghnidets/OHMySQL) - An Objective-C wrapper of MySQL C API.   ---- (Star:33) (Fork:8) (Watch:5)  
* [OneStore](https://github.com/muukii/OneStore) - A single value proxy for NSUserDefaults, with clean API. :large_orange_diamond:   ---- (Star:17) (Fork:1) (Watch:0)  
* [Nora](https://github.com/SD10/Nora) - Nora is a Firebase abstraction layer for working with FirebaseDatabase and FirebaseStorage. :large_orange_diamond:   ---- (Star:202) (Fork:18) (Watch:8)  
* [PersistentStorageSerializable](https://github.com/IvanRublev/PersistentStorageSerializable) - Swift library that makes easier to serialize the user's preferences (app's settings) with system User Defaults or Property List file on disk. :large_orange_diamond:   ---- (Star:162) (Fork:4) (Watch:5)  
* [WCDB](https://github.com/Tencent/wcdb) - WCDB is an efficient, complete, easy-to-use mobile database framework for iOS, macOS.   ---- (Star:4,308) (Fork:510) (Watch:209)  
* [StorageKit](https://github.com/StorageKit/StorageKit) - Your Data Storage Troubleshooter 🛠   ---- (Star:155) (Fork:5) (Watch:7)  

#### 缓存处理@

* [YTKKeyValueStore](https://github.com/yuantiku/YTKKeyValueStore) - Key-Value存储工具类，[说明](http://tangqiaoboy.gitcafe.io/blog/2014/10/03/opensouce-a-key-value-storage-tool/)。   ---- (Star:1,767) (Fork:432) (Watch:98)  
* [JLKeychain](https://github.com/jl322137/JLKeychain) - 快捷使用keychain存储数据的类，使keychain像NSUserDefaults一样工作。   ---- (Star:52) (Fork:10) (Watch:2)  
* [UICKeyChainStore](https://github.com/kishikawakatsumi/UICKeyChainStore) - 封装keychain，使keychain像NSUserDefaults一样简单   ---- (Star:2,453) (Fork:278) (Watch:86)  
* [sskeychain](https://github.com/soffes/sskeychain) - SSKeyChains对苹果安全框架API进行了简单封装,支持对存储在钥匙串中密码、账户进行访问,包括读取、删除和设置。   ---- (Star:4,582) (Fork:827) (Watch:160)  
* [KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess) - 管理Keychain接入的小助手。   ---- (Star:3,265) (Fork:340) (Watch:85)  
* [YYCache](https://github.com/ibireme/YYCache) - 高性能的 iOS 缓存框架。   ---- (Star:1,502) (Fork:329) (Watch:51)  
* [RuntimeDemo](https://github.com/CoderJackyHuang/RuntimeDemo) - runtime自动归档/解档,[源码分析](http://www.henishuo.com/runtime-archive-unarchive-automaticly/)。   ---- (Star:80) (Fork:44) (Watch:4)  

#### 序列化@

* [FastCoding](https://github.com/nicklockwood/FastCoding) 是用来替代OSX及iOS中默认的序列化实现。它结构简单（仅头文件和.m文件两个）、支持ARC，线程安全，速度较内置实现更快。下次做项目的时候可以试着用用。   ---- (Star:887) (Fork:70) (Watch:28)  

#### coreData@

* [CWCoreData](https://github.com/jayway/CWCoreData) - Additions and utilities to make it concurrency easier with the Core Data framework.   ---- (Star:71) (Fork:8) (Watch:26)  
* [ObjectiveRecord](https://github.com/supermarin/ObjectiveRecord) - ActiveRecord for Objective-C.   ---- (Star:1,335) (Fork:196) (Watch:64)  
* [SSDataKit](https://github.com/soffes/SSDataKit) - Eliminate your Core Data boilerplate code.   ---- (Star:466) (Fork:58) (Watch:19)  
* [ios-queryable](https://github.com/martydill/ios-queryable) - ios-queryable is an implementation of IQueryable/IEnumerable for Core Data.   ---- (Star:237) (Fork:21) (Watch:14)  
* [Ensembles](https://github.com/drewmccormack/ensembles) - A synchronization framework for Core Data.   ---- (Star:1,539) (Fork:123) (Watch:73)  
* [SLRESTfulCoreData](https://github.com/OliverLetterer/SLRESTfulCoreData) - Objc naming conventions, autogenerated accessors at runtime, URL substitutions and intelligent attribute mapping.   ---- (Star:186) (Fork:13) (Watch:10)  
* [Mogenerator](https://github.com/rentzsch/mogenerator) - Automatic Core Data code generation.   ---- (Star:2,944) (Fork:397) (Watch:113)  
* [HardCoreData](https://github.com/Krivoblotsky/HardCoreData) - CoreData stack and controller that will never block UI thread.   ---- (Star:206) (Fork:21) (Watch:10)  
* [encrypted-core-data](https://github.com/project-imas/encrypted-core-data) - Core Data encrypted SQLite store using SQLCipher.   ---- (Star:644) (Fork:177) (Watch:68)  
* [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) - Super Awesome Easy Fetching for Core Data.   ---- (Star:10,510) (Fork:1,863) (Watch:457)  
* [QueryKit](https://github.com/QueryKit/QueryKit) - A simple type-safe Core Data query language. :large_orange_diamond:   ---- (Star:1,280) (Fork:72) (Watch:35)  
* [CoreStore](https://github.com/JohnEstropia/CoreStore) - Powerful Core Data framework for Incremental Migrations, Fetching, Observering, etc. :large_orange_diamond:   ---- (Star:1,677) (Fork:117) (Watch:51)  
* [Core Data Query Interface](https://github.com/prosumma/CoreDataQueryInterface) A type-safe, fluent query framework for Core Data. :large_orange_diamond:   ---- (Star:20) (Fork:4) (Watch:4)  
* [CoreDataDandy](https://github.com/fuzz-productions/CoreDataDandy) - A feature-light wrapper around Core Data that simplifies common database operations. :large_orange_diamond:   ---- (Star:32) (Fork:3) (Watch:7)  
* [CoreDataStack](https://github.com/bignerdranch/CoreDataStack) - The Big Nerd Ranch Core Data Stack :large_orange_diamond:   ---- (Star:518) (Fork:69) (Watch:50)  
* [Skopelos](https://github.com/albertodebortoli/Skopelos) - A minimalistic, thread safe, non-boilerplate and super easy to use version of Active Record on Core Data. Simply all you need for doing Core Data. Swift flavour. :large_orange_diamond:   ---- (Star:178) (Fork:13) (Watch:9)  
* [DataKernel](https://github.com/mrdekk/DataKernel) - Simple CoreData wrapper to ease operations. :large_orange_diamond:   ---- (Star:6) (Fork:4) (Watch:1)  
* [JustPersist](https://github.com/justeat/JustPersist) - JustPersist is the easiest and safest way to do persistence on iOS with Core Data support out of the box.   ---- (Star:92) (Fork:3) (Watch:21)  
* [PrediKit](https://github.com/KrakenDev/PrediKit) - An NSPredicate DSL for iOS, macOS, tvOS, & watchOS. Inspired by SnapKit and lovingly written in Swift. :large_orange_diamond:   ---- (Star:473) (Fork:21) (Watch:12)  

#### 动画@

* [lottie-ios](https://github.com/airbnb/lottie-ios) 非常赞 一个用来渲染After Effects矢量动画的iOS库   ---- (Star:11,083) (Fork:1,313) (Watch:310)  
* [AIAnimationDemo](https://github.com/aizexin/AIAnimationDemo) 非常不错的一个各种动画Demo集合库👍👍 .   ---- (Star:301) (Fork:84) (Watch:7)  
* [AwesomeMenu](https://github.com/levey/AwesomeMenu) 作者是一位中国人, 该项目主要是使用 CoreAnimation 还原了 Path menu 的动画效果 Path 2.0 menu using CoreAnimation :) https://github.com/levey/AwesomeMenu   ---- (Star:5,119) (Fork:838) (Watch:211)  
* [MMTweenAnimation](https://github.com/adad184/MMTweenAnimation)一个基于 POP 的扩展，提供了 10 种自定义的动效。   ---- (Star:1,080) (Fork:137) (Watch:35)  
* [pop](https://github.com/facebook/pop) - facebook出品的非常赞的动画引擎。   ---- (Star:18,247) (Fork:2,832) (Watch:1,128)  
* [Core Animation笔记，基本的使用方法](http://www.starming.com/index.php?v=index&view=62) - Core Animation笔记，基本的使用方法：1.基本动画，2.多步动画，3.沿路径的动画，4.时间函数，5.动画组。
* [awesome-ios-animation](https://github.com/sxyx2008/awesome-ios-animation) - [iOS Animation 主流炫酷动画框架(特效)收集整理](https://github.com/sxyx2008/DevArticles/issues/91) 收集整理了下iOS平台下比较主流炫酷的几款动画框架。   ---- (Star:2,868) (Fork:592) (Watch:198)  
* [FleaMarket](https://github.com/SunLiner/FleaMarket) "咸鱼"新特性-视频动画   ---- (Star:151) (Fork:49) (Watch:2)  
* [JHChainableAnimations](https://github.com/jhurray/JHChainableAnimations) - 在应用中采用链式写出酷炫的动画效果, 使代码更加清晰易读，利用block实现的链式编程，同时支持Swift。   ---- (Star:2,994) (Fork:313) (Watch:100)  
* [awesome-animation](https://github.com/Animatious/awesome-animation) -  在内的十多位童鞋们一起发起的一起动画开源组正式成立啦~Github组织名称：Animatious，这是我们第一期成员先前开源的一些动效库，我们的第一个合作开源项目正在紧锣密鼓的准备~请大家期待设计和代码的碰撞吧。   ---- (Star:1,585) (Fork:190) (Watch:100)  
* [BCMagicTransition](https://github.com/boycechang/BCMagicTransition)一个动效框架，用于自定义UINavigationController的切换动画，效果类似 Keynote 软件中 Magic Move 切换。它可以用于任意两个UIViewController之间，只需指定两个VC中的相同元素即可。   ---- (Star:526) (Fork:72) (Watch:15)  
* [popping](https://github.com/schneiderandre/popping) - popping是一个POP 使用实例工程   ---- (Star:5,292) (Fork:721) (Watch:189)  
* [MMTweenAnimation](https://github.com/adad184/MMTweenAnimation) - facebook POP的自定义动画扩展(基于POPCustomAnimation) 提供10种函数式动画。   ---- (Star:1,080) (Fork:137) (Watch:35)  
* [ZQLRotateMenu](https://github.com/zangqilong198812/ZQLRotateMenu) - 这是一个旋转视图的选择器。   ---- (Star:85) (Fork:17) (Watch:5)  
* [CoolLoadAniamtion](https://github.com/zangqilong198812/CoolLoadAniamtion) - 一个简单但是效果不错的loading动画。   ---- (Star:14) (Fork:4) (Watch:2)  
* [Animations](https://github.com/YouXianMing/Animations)The Animation Collection.   ---- (Star:2,091) (Fork:488) (Watch:86)  
* [JSDownloadView](https://github.com/Josin22/JSDownloadView) 精巧顺滑的下载动画   ---- (Star:475) (Fork:72) (Watch:14)  
* [SYAppStart](https://github.com/yushuyi/SYAppStart) - App启动插画的自定义过度。   ---- (Star:56) (Fork:15) (Watch:5)  
* [VJDeviceSpecificMedia](https://github.com/victorjiang/UIImage-VJDeviceSpecificMedia/) - [如何根据设备选择不同尺寸的图片](http://www.imooc.com/wenda/detail/249271) 可以通过设置不同尺寸设备的LaunchImage，来使得App适配这些设备，要是在不同不同尺寸设备上使用不同大小的图片，则需要在代码中一一判断，然后加载。   ---- (Star:6) (Fork:0) (Watch:1)  
* [RMParallax](https://github.com/michaelbabiy/RMParallax) - RMParallax是一个app启动页引导开源项目，除了细微的翻页视差效果，描述文本的过渡也非常美观（版本新特性、导航页、引导页）。   ---- (Star:632) (Fork:47) (Watch:21)  
* [ADo_GuideView](https://github.com/Nododo/ADo_GuideView) - 转动的用户引导页(模仿网易bobo) 因为没有从app包里抓到@3x的图片,建议在iPhone5模拟器运行,保证效果~ （版本新特性、导航页、引导页）。   ---- (Star:170) (Fork:35) (Watch:6)  
* [CoreNewFeatureVC](https://github.com/CharlinFeng/CoreNewFeatureVC) - 版本新特性（引导页），1.封装并简化了版本新特性启动视图！2.添加了版本的本地缓存功能，3.集成简单，使用方便，没有耦合度，4.支持block回调（版本新特性、导航页、引导页）。   ---- (Star:180) (Fork:67) (Watch:15)  
* [MZGuidePages](https://github.com/MachelleZhang/MZGuidePages) - 自己写的通用导航页，可以直接引入工程使用，请参考案例（版本新特性、导航页、引导页）。   ---- (Star:5) (Fork:1) (Watch:1)  
* [ABCIntroView](https://github.com/AdamBCo/ABCIntroView) - ABCIntroView是一个易于使用的入门类，让你到达主屏幕之前介绍你的应用程序（版本新特性、导航页、引导页）。   ---- (Star:257) (Fork:47) (Watch:7)  
* [KYBezierBounceView](https://github.com/KittenYang/KYBezierBounceView) - 手势控制贝塞尔曲线，取消手势贝塞尔曲线会有反弹效果。   ---- (Star:132) (Fork:23) (Watch:7)  
* [cadisplaylinkanduibezierpath](http://kittenyang.com/cadisplaylinkanduibezierpath/) - CADisplayLink结合UIBezierPath的神奇妙用。
* [KYCuteView](https://github.com/KittenYang/KYCuteView) - 实现类似QQ消息拖拽消失的交互+GameCenter的浮动小球效果，[分析](http://kittenyang.com/drawablebubble/)。   ---- (Star:919) (Fork:199) (Watch:36)  
* [KYWaterWaveView](https://github.com/KittenYang/KYWaterWaveView) - 一个内置波浪动画的UIView，里面有鱼跳跃水溅起来的效果。   ---- (Star:472) (Fork:72) (Watch:14)  
* [KYPingTransition](https://github.com/KittenYang/KYPingTransition) - 实现圆圈放大放小的转场动画，可以根据自己的需要使用Paper中的弹性效果，有Material风格。   ---- (Star:177) (Fork:32) (Watch:3)  
* [KYNewtonCradleAnimiation](https://github.com/KittenYang/KYNewtonCradleAnimiation) - 牛顿摆动画。   ---- (Star:19) (Fork:9) (Watch:1)  
* [LayerPlayer](https://github.com/scotteg/LayerPlayer) - 一款全面展示核心动画 API 示例项目（上架应用）。包括 CALayer, CAScrollLayer, CATextLayer, AVPlayerLayer, CAGradientLayer, CAReplicatorLayer, CATiledLayer, CAShapeLayer, CAEAGLLayer, CATransformLayer, CAEmitterLayer 等使用的互动演示。   ---- (Star:970) (Fork:180) (Watch:43)  
* [KYShareMenu](https://github.com/KittenYang/KYShareMenu) - 带弹性动画的分享菜单。   ---- (Star:90) (Fork:10) (Watch:1)  
* [Context-Menu.iOS](https://github.com/Yalantis/Context-Menu.iOS) - 可以为app的菜单添加漂亮的动画内容，可自定义icon，并可根据自己的喜好设计单元格和布局。   ---- (Star:1,774) (Fork:261) (Watch:93)  
* [DeformationButton](https://github.com/LuciusLu/DeformationButton) - 一个简单的变换形状动画按钮。   ---- (Star:300) (Fork:53) (Watch:11)  
* [UnReadBubbleView](https://github.com/heroims/UnReadBubbleView) - UnReadBubbleView是一个能够拖拽并拉长的气泡视图。拖拽到一定的长度会消失，可以通过系数设置来控制拖拽的长度。气泡也支持多种属性设置。   ---- (Star:81) (Fork:25) (Watch:10)  
* [PPDragDropBadgeView](https://github.com/smallmuou/PPDragDropBadgeView) - 实现了类似于QQ 5.0 水滴拖拽效果. 支持iOS 5.0+ ARC，气泡能够带有数字标识，同时支持消失block方法。消失时还带有消失效果动画。   ---- (Star:307) (Fork:72) (Watch:16)  
* [GiftCard-iOS](https://github.com/MartinRGB/GiftCard-iOS) - 礼品卡购买的炫酷动画。   ---- (Star:447) (Fork:61) (Watch:15)  
* [GiftCard-Implementation](https://github.com/MartinRGB/GiftCard-iOS) - 购买的炫酷动画。   ---- (Star:447) (Fork:61) (Watch:15)  
* [KIPageView](https://github.com/smartwalle/KIPageView) - 无限循环PageView，横向TableView，无限轮播。   ---- (Star:30) (Fork:6) (Watch:4)  
* [简单实用的无限循环轮播图](http://code.cocoachina.com/view/128288) - 简单实用的无限循环轮播图 。
* [CPInfiniteBanner](https://github.com/crespoxiao/CPInfiniteBanner) - 是一个循环播放的组件，可以左右无缝滑动,3个imageview实现。[高效图片轮播，两个ImageView实现](http://ios.jobbole.com/84711/)。     ---- (Star:67) (Fork:14) (Watch:3)  
* [XTLoopScroll](https://github.com/Akateason/XTLoopScroll) - 用两个 timer 三个重用的 view 实现无限循环 scrollView，1自动轮播 2点击监听回调当前图片 3手动滑动后重新计算轮播的开始时间, 良好的用户体验。   ---- (Star:20) (Fork:3) (Watch:1)  
* [HotGirls](https://github.com/zangqilong198812/HotGirls) - 卡片动画。   ---- (Star:279) (Fork:53) (Watch:20)  
* [KYAnimatedPageControl](https://github.com/KittenYang/KYAnimatedPageControl) - 除了滚动视图时PageControl会以动画的形式一起移动，点击目标页还可快速定位。支持两种样式：粘性小球和旋转方块。   ---- (Star:1,208) (Fork:196) (Watch:30)  
* [Presentation](https://github.com/hyperoslo/Presentation) - 一个类似RazzleDazzle的框架。   ---- (Star:2,278) (Fork:135) (Watch:66)  
* [FillableLoaders](https://github.com/poolqf/FillableLoaders) - 基于 CGPaths 可定制个性化填空式装载类库。附水波上涨式示例。   ---- (Star:1,744) (Fork:138) (Watch:39)  
* [SXWaveAnimate](https://github.com/dsxNiubility/SXWaveAnimate) - 实现非常美观的灌水动画。   ---- (Star:1,153) (Fork:270) (Watch:48)  
* [LSPaomaView](https://github.com/liusen001/LSPaomaView) - 可循环滚动的较长文字，跑马灯，效果很好，一句话集成。   ---- (Star:103) (Fork:25) (Watch:5)  
* [Cheetah](https://github.com/suguru/Cheetah) - 易用、高可读链式动画类库。另一个类似类库是 [DKChainableAnimationKit](https://github.com/Draveness/DKChainableAnimationKit)。   ---- (Star:558) (Fork:39) (Watch:17)  
* [CKWaveCollectionViewTransition](https://github.com/CezaryKopacz/CKWaveCollectionViewTransition) - swift， UICollectionViewController之间切换的动画。   ---- (Star:1,584) (Fork:112) (Watch:36)  
* [TKSubmitTransition](https://github.com/entotsu/TKSubmitTransition) - 基于 UIButton 的登录加载、返回按钮转场动画组件及示例。   ---- (Star:1,936) (Fork:202) (Watch:39)  
* [ARAnimation](https://github.com/AugustRush/ARAnimation) - ARAnimation 对 Core Animation 进行了封装, 帮助 iOS 开发者能更加便捷的在项目中使用动画。   ---- (Star:573) (Fork:80) (Watch:16)  
* [渐变特效文字](http://code.cocoachina.com/view/127174) - 做了一个仿iPhone的移动滑块来解锁的渐变特效文字,还有一个类似ktv歌词显示的文字特效。
* [HYAwesomeTransition](https://github.com/nathanwhy/HYAwesomeTransition) - 模仿格瓦拉的转场效果。   ---- (Star:363) (Fork:53) (Watch:13)  
* [RYCuteView](https://github.com/Resory/RYCuteView) - 用UIBezierPath实现果冻效果。 [教程](http://www.jianshu.com/p/21db20189c40)   ---- (Star:136) (Fork:39) (Watch:3)  
* [STLBGVideo](https://github.com/StoneLeon/STLBGVideo) - STLBGVideo让您的视图控制器的自定义backgroundvideo,[实现说明1](http://www.jianshu.com/p/c4704c086b67)、[实现说明2](http://www.jianshu.com/p/3dcebf0493d1)。   ---- (Star:292) (Fork:39) (Watch:10)  
* [MYBlurIntroductionView](https://github.com/MatthewYork/MYBlurIntroductionView) - 方便好用的引导类库，在App注册登录页面可以用到。   ---- (Star:1,537) (Fork:211) (Watch:64)  
* [ZFCityGuides](https://github.com/WZF-Fei/ZFCityGuides) - 实现City Guides的动画效果，数字动态变化的动画效果。   ---- (Star:352) (Fork:85) (Watch:13)  
* [INPopoverController](https://github.com/indragiek/INPopoverController) - OS X可自由定制的  Popover 视图。   ---- (Star:179) (Fork:31) (Watch:9)  
* [WZXJianShuPopDemo](https://github.com/Wzxhaha/WZXJianShuPopDemo) - 仿简书、淘宝等等的View弹出效果，已封装好，使用简单。[实现原理](http://www.jianshu.com/p/a697d2a38b3c)   ---- (Star:175) (Fork:45) (Watch:8)  
* [LSAnimator](https://github.com/Lision/LSAnimator) 非侵入式的多链式动画   ---- (Star:190) (Fork:25) (Watch:5)  

#### 转场@

* [AnimatedTransitionGallery](https://github.com/shu223/AnimatedTransitionGallery) A gallery app of custom animated transitions for iOS.   ---- (Star:2,229) (Fork:275) (Watch:83)  
* [VCTransitionsLibrary](https://github.com/ColinEberhardt/VCTransitionsLibrary) 不错的转场动画库   ---- (Star:4,220) (Fork:627) (Watch:174)  
* [WXSTransition](https://github.com/alanwangmodify/WXSTransition) 转场动画集合   ---- (Star:926) (Fork:180) (Watch:29)  

#### 多媒体@
#### GIF@

* [FLAnimatedImage](https://github.com/liric28/FLAnimatedImage) - 非常不错的gif播放处理的工具。   ---- (Star:11) (Fork:963) (Watch:1)  
* [YLGIFImage](https://github.com/liyong03/YLGIFImage) - 异步方式实现突Gif突破编码、显示，低内存占用。   ---- (Star:1,681) (Fork:199) (Watch:48)  
* [FLAnimatedImage](https://github.com/Flipboard/FLAnimatedImage) - 高性能GIF动画引擎.Performant animated GIF engine for iOS   ---- (Star:6,146) (Fork:963) (Watch:234)  
* [AnimatedGIFImageSerialization](https://github.com/mattt/AnimatedGIFImageSerialization) - Complete Animated GIF Support for iOS, with Functions, NSJSONSerialization-style Class, and (Optional) UIImage Swizzling   ---- (Star:1,027) (Fork:108) (Watch:26)  
* [XAnimatedImage](https://github.com/khaledmtaha/XAnimatedImage) - XAnimatedImage is a performant animated GIF engine for iOS written in Swift based on FLAnimatedImage :large_orange_diamond:   ---- (Star:576) (Fork:36) (Watch:17)  
* [SwiftGif](https://github.com/bahlo/SwiftGif) - :sparkles: A small UIImage extension with gif support :large_orange_diamond:   ---- (Star:712) (Fork:128) (Watch:20)  
* [APNGKit](https://github.com/onevcat/APNGKit) - High performance and delightful way to play with APNG format in iOS. :large_orange_diamond:   ---- (Star:1,278) (Fork:123) (Watch:42)  
* [YYImage](https://github.com/ibireme/YYImage) - Image framework for iOS to display/encode/decode animated WebP, APNG, GIF, and more.   ---- (Star:1,024) (Fork:193) (Watch:37)  
* [NSGIF2](https://github.com/metasmile/NSGIF2) - Simplify creation of a GIF from the provided video file url.   ---- (Star:55) (Fork:131) (Watch:3)  
* [SwiftyGif](https://github.com/kirualex/SwiftyGif) - High performance GIF engine :large_orange_diamond:   ---- (Star:697) (Fork:75) (Watch:16)  
* [UIImageView-PlayGIF](https://github.com/yfme/UIImageView-PlayGIF) - UIImageView-PlayGIF。   ---- (Star:417) (Fork:80) (Watch:21)  
* [droptogif](https://github.com/mortenjust/droptogif) -  droptogif视频拖拽到应用窗口后自动转换为 GIF 动画（其转换进程动画效果也超赞）。   ---- (Star:2,098) (Fork:108) (Watch:47)  

#### VR@

* [HTY360Player](https://github.com/hanton/HTY360Player) 一款360度全景视频播放器   ---- (Star:1,689) (Fork:405) (Watch:99)  
* [ios-360-videos](https://github.com/NYTimes/ios-360-videos) - 基于AVPlayer的360度全景视频播放器   ---- (Star:186) (Fork:29) (Watch:14)  

#### AR@

* [AR-Source](https://github.com/GeekLiB/AR-Source) AR 开发资料汇总   ---- (Star:680) (Fork:194) (Watch:66)  

#### 二维码@

* [ZXingObjC](https://github.com/TheLevelUp/ZXingObjC)  赞 An Objective-C Port of ZXing   ---- (Star:2,521) (Fork:662) (Watch:153)  
* [LBXScan](https://github.com/MxABC/LBXScan) 赞 A barcode and qr code scanner (二维码、扫码、扫一扫、ZXing和ios系统自带扫码封装，扫码界面效果封装)(Objective-C和Swift均支持).   ---- (Star:1,950) (Fork:468) (Watch:61)  
* [原生实现扫描二维码条码](http://code.cocoachina.com/view/129108) - iOS原生实现扫描二维码条码.
* [ZFScan](https://github.com/Zirkfied/ZFScan) - 仿微信 二维码/条形码 扫描。   ---- (Star:82) (Fork:17) (Watch:3)  
* [QRCatcher](https://github.com/100mango/QRCatcher) - 一个简洁美观的二维码扫描应用， [iOS学习：AVFoundation 视频流处理--二维码   ---- (Star:273) (Fork:67) (Watch:9)  
* [BarcodeScanner](https://github.com/hyperoslo/BarcodeScanner) 带状态控制的条码扫描库，支持处理相机权限、自定义颜色和提示信息，不依赖其他第三方库。扫描](https://github.com/100mango/zen/blob/master/iOS%E5%AD%A6%E4%B9%A0%EF%BC%9AAVFoundation%20%E8%A7%86%E9%A2%91%E6%B5%81%E5%A4%84%E7%90%86/iOS%E5%AD%A6%E4%B9%A0%EF%BC%9AAVFoundation%20%E8%A7%86%E9%A2%91%E6%B5%81%E5%A4%84%E7%90%86%20.md)。   ---- (Star:759) (Fork:100) (Watch:38)  
* [MQRCodeReaderViewController](https://github.com/zhengjinghua/MQRCodeReaderViewController) - 二维码扫描控件, UI 做了优化, 仿造微信, 直接拖进项目就可使用。   ---- (Star:348) (Fork:57) (Watch:8)  
* [MQRCodeReaderViewController](https://github.com/zhengjinghua/MQRCodeReaderViewController) iOS 二维码扫描控件, UI 做了优化, 仿造微信, 直接拖进项目就可使用, 支持 CocoaPods 安装. WeChat-like QRCode reader, drop-in version, support for CocoaPods   ---- (Star:348) (Fork:57) (Watch:8)  
* [QRWeiXinDemo](https://github.com/lcddhr/QRWeiXinDemo)仿微信二维码扫描，中间透明区域   ---- (Star:219) (Fork:75) (Watch:15)  
* [EFQRCode](https://github.com/EyreFree/EFQRCode) - iOS 花式二维码生成库   ---- (Star:1,909) (Fork:164) (Watch:52)  

#### PDF@

* [Reader](https://github.com/vfr/Reader) - Reader可提供类似iBooks的文档导航，支持屏幕旋转和所有方向，并通过密码保护加密PDF文件，支持PDF链接和旋转页面。   ---- (Star:3,919) (Fork:1,148) (Watch:268)  
* [PDFXKit](https://github.com/PSPDFKit/PDFXKit) A drop-in replacement for Apple PDFKit powered by our PSPDFKit framework under the hood.   ---- (Star:134) (Fork:2) (Watch:6)  

#### 流媒体@

#### 音频@

* [ESTMusicPlayer](https://github.com/Aufree/ESTMusicPlayer) 一个简洁、易用的音乐播放器   ---- (Star:1,825) (Fork:373) (Watch:78)  
* [EZAudio](https://github.com/syedhali/EZAudio) - EZAudio 是一个 iOS 和 OSX 上简单易用的音频框架，根据音量实时显示波形图，基于Core Audio，适合实时低延迟音频处理，非常直观。[中文介绍](https://segmentfault.com/blog/news/1190000000370957),[官网](http://www.syedharisali.com/about)。   ---- (Star:4,096) (Fork:687) (Watch:156)  
* [novocaine](https://github.com/alexbw/novocaine) - 高性能的音频，支持iOS and Mac OS X.   ---- (Star:2,077) (Fork:289) (Watch:106)  
* [SubtleVolume](https://github.com/andreamazz/SubtleVolume) - 用更微妙的指示器替换系统卷弹出窗口   ---- (Star:588) (Fork:30) (Watch:15)  
* [NVDSP](https://github.com/bartolsthoorn/NVDSP) - iOS/OSX DSP for audio (with Novocaine)   ---- (Star:328) (Fork:62) (Watch:28)  
* [IQAudioRecorderController](https://github.com/hackiftekhar/IQAudioRecorderController) - 一个可以内置App的、通用的、带有漂亮的用户界面音频录制程序   ---- (Star:425) (Fork:105) (Watch:25)  
* [QuietModemKit](https://github.com/quiet/QuietModemKit) 静态调制解调器的iOS框架（声音数据）   ---- (Star:302) (Fork:17) (Watch:12)  
* [IOS录音和播放功能demo](http://d.cocoachina.com/code/detail/285717) - 比较完整的ios录音和播放功能的实现。
* [MCAudioInputQueue](https://github.com/msching/MCAudioInputQueue) - 简易录音类，基于AudioQueue的。   ---- (Star:63) (Fork:11) (Watch:2)  
* [MusicPlayert](https://github.com/liuFangQiang/MusicPlayer) - MusicPlayert音乐播放器，用reveal可以查看层次关系，主要实现了歌词的同步显示。   ---- (Star:9) (Fork:8) (Watch:2)  
* [音乐播放器](http://code.cocoachina.com/view/129435) - 音乐播放器：显示歌词。
* [amr](http://www.penguin.cz/~utx/amr) - 做即时通讯的音频处理，录音文件是m4a，便于web端的音频播放。
* [边录音边转码](http://code4app.com/ios/%E8%BE%B9%E5%BD%95%E9%9F%B3%E8%BE%B9%E8%BD%AC%E7%A0%81/521c65d56803fab864000001) - 一边录音，一边将录制成的 wav 格式音频文件转码成 amr 音频格式。只支持真机运行调试。

#### 视频@
#### 视频播放@

* [FFmpeg](https://github.com/FFmpeg/FFmpeg) 一个处理多媒体数据的开源、免费的库 [ffmpeg](http://ffmpeg.org/) - ffmpeg官网，[FFmpeg在iOS上完美编译](http://www.cocoachina.com/ios/20150514/11827.html)。   ---- (Star:8,617) (Fork:3,902) (Watch:843)  
* [vlc)](https://github.com/videolan/vlc) VLC media player   ---- (Star:3,235) (Fork:1,380) (Watch:401)  
* [mpv](https://github.com/mpv-player/mpv) - 非常👍👍👍 🎥 Video player based on MPlayer/mplayer2   ---- (Star:6,535) (Fork:842) (Watch:366)  
* [ijkplayer](https://github.com/Bilibili/ijkplayer) - 非常赞 B站开源的视频播放器，支持Android和iOS。 [iOS中集成ijkplayer视频直播框架](http://www.jianshu.com/p/1f06b27b3ac0)。   ---- (Star:15,941) (Fork:4,659) (Watch:960)  
* [ZFPlayer](https://github.com/renzifeng/ZFPlayer) - 非常赞 基于AVPlayer，支持横屏、竖屏（全屏播放还可锁定屏幕方向），上下滑动调节音量、屏幕亮度，左右滑动调节播放进度   ---- (Star:3,636) (Fork:882) (Watch:122)  
* [WMPlayer](https://github.com/zhengwenming/WMPlayer) 赞 WMPlayer视频播放器，AVPlayer的封装，继承UIView，想怎么玩就怎么玩。支持播放mp4、m3u8、3gp、mov，网络和本地视频同时支持。全屏和小屏播放同时支持。 cell中播放视频，全屏小屏切换自如。   ---- (Star:1,982) (Fork:550) (Watch:76)  
* [XCDYouTubeKit](https://github.com/0xced/XCDYouTubeKit) 一个能够在国内播放YouTube视频的播放器   ---- (Star:2,198) (Fork:373) (Watch:125)  
* [HJDanmakuDemo](https://github.com/panghaijiao/HJDanmakuDemo) iOS端视频弹幕   ---- (Star:644) (Fork:167) (Watch:23)  
* [MRVLCPlayer](https://github.com/Maru-zhang/MRVLCPlayer) - 相信Mac用户都很熟悉一款VLC播放器，这款播放器在Mac上表现异常优异，支持的格式几乎涵盖了所有格式（就是这么屌！）。没错，就是它创造者--VideoLAN，开源了一款牛逼的视频播放框架MobileVLCKit！[介绍信息：] (http://gold.xitu.io/entry/578c304b2e958a0054320503?from=singlemessage&isappinstalled=1)   ---- (Star:238) (Fork:73) (Watch:8)  
* [plask](https://github.com/deanm/plask) Plask is a multimedia programming environment.   ---- (Star:393) (Fork:33) (Watch:29)  
* [KRVideoPlayer](https://github.com/36Kr-Mobile/KRVideoPlayer) - 36Kr出品的类似Weico的播放器，支持竖屏模式下全屏播放。   ---- (Star:1,972) (Fork:418) (Watch:64)  
* [JPVideoPlayer](https://github.com/Chris-Pan/JPVideoPlayer) 类似微博主页在列表中自动播放视频   ---- (Star:706) (Fork:149) (Watch:19)  
* [HcdCachePlayer](https://github.com/Jvaeyhcd/HcdCachePlayer) 在线视频边下边播，支持缓存到本地   ---- (Star:165) (Fork:40) (Watch:6)  
* [bilibili-mac-client](https://github.com/typcn/bilibili-mac-client) 👍bilibili非官方的mac客户端   ---- (Star:3,015) (Fork:362) (Watch:119)  
* [PBJVideoPlayer](https://github.com/piemonte/PBJVideoPlayer) 一个易用的流媒体播放器   ---- (Star:561) (Fork:114) (Watch:35)  
* [KrVideoPlayerPlus](https://github.com/PlutusCat/KrVideoPlayerPlus) 根据36Kr开源的KRVideoPlayer 进行修改和补充实现一个轻量级的视频播放器，满足大部分视频播放需求   ---- (Star:288) (Fork:81) (Watch:16)  
* [VKVideoPlayer](https://github.com/viki-org/VKVideoPlayer) 一个非常不错的拥有上百万用户的视频播放器   ---- (Star:1,810) (Fork:414) (Watch:125)  
* [PKShortVideo](https://github.com/pepsikirk/PKShortVideo) iOS仿微信小视频功能开发优化记录   ---- (Star:382) (Fork:85) (Watch:9)  
* [AVAnimator](http://www.modejong.com/AVAnimator/) - 一个不错的原生的开源视频库，可以轻松实现视频、音频的功能
* [SSVideoPlayer](https://github.com/immrss/SSVideoPlayer) - 一个支持本地和网络视频播放的库   ---- (Star:181) (Fork:41) (Watch:11)  
* [SRGMediaPlayer-iOS](https://github.com/SRGSSR/SRGMediaPlayer-iOS) - 一个提供简洁的方法为iOS应用添加通用的音频、视频播放的库   ---- (Star:67) (Fork:25) (Watch:9)  
* [ABMediaView](https://github.com/andrewboryk/ABMediaView) - 一个UIImageView的子类，可以播放本地和来源于网络的图片、视频、GIF和音频。可以最小化和全屏。同时支持视频设置GIF预览图。 UIImageView subclass for drop-in image, video, GIF, and audio display, with functionality for fullscreen and minimization to the bottom-right corner.   ---- (Star:31) (Fork:4) (Watch:2)  
* [kxmovie](https://github.com/kolyvan/kxmovie) - 使用ffmpeg的影片播放器，[修改说明](http://www.cocoachina.com/bbs/read.php?tid=145575)， [修改代码](https://github.com/kinglonghuang)，[基于FFmpeg的kxMoive艰难的编译运行](https://github.com/namebryant/FFmpeg-Compilation)。   ---- (Star:2,368) (Fork:879) (Watch:196)  
* [StreamingKit](https://github.com/tumtumtum/StreamingKit) - StreamingKit流媒体音乐播放器。   ---- (Star:1,656) (Fork:393) (Watch:86)  
* [FreeStreamer](https://github.com/muhku/FreeStreamer) - FreeStreamer流媒体音乐播放器，cpu占用非常小。   ---- (Star:1,385) (Fork:332) (Watch:81)  
* [DOUAudioStreamer](https://github.com/douban/DOUAudioStreamer) - DOUAudioStreamer豆瓣的音乐流媒体播放器。   ---- (Star:2,365) (Fork:519) (Watch:142)  
* [fmpro](https://github.com/fmpro/fmpro) - 电台播放器，支持锁屏歌词，支持基本播放流程，歌词展示，后台锁屏播放和控制以及锁屏后封面+歌词，[fmpro_R](https://github.com/jovisayhehe/fmpro_R) 。   ---- (Star:24) (Fork:9) (Watch:1)  
* [TBPlayer](https://github.com/suifengqjn/TBPlayer) - 视频变下变播，把播放器播放过的数据流缓存到本地，支持拖动。采用avplayer。[实现说明](http://www.jianshu.com/p/990ee3db0563)   ---- (Star:971) (Fork:201) (Watch:20)  
* [IWatch](https://github.com/280772270/IWatch) - 一个视频日报类的app 播放器用到了AVFoudation。   ---- (Star:13) (Fork:0) (Watch:1)  
* [自定义视频播放器AVPlayer](http://code.cocoachina.com/view/128253) - 利用系统类AVPlayer实现完全自定义视频播放器，显示播放时间，缓存等功能。代码清晰，注释详细。
* [DraggableYoutubeFloatingVideo](https://github.com/vizllx/DraggableYoutubeFloatingVideo) - 展示像类似Youtube移动应用的那种浏览视频的效果，当点击某视频时能够从右下方弹出一个界面，并且该界面能够通过手势，再次收缩在右下方并继续播放。这是通过AutoLayout设计实现。   ---- (Star:284) (Fork:69) (Watch:22)  

#### 视频处理@

* [BeautifyFaceDemo](https://github.com/Guikunzhi/BeautifyFaceDemo) - 一个基于 GPUImage 的实时直播磨皮滤镜的开源实现,主要功能脸部去斑磨皮！   ---- (Star:1,733) (Fork:378) (Watch:78)  
* [simplest_ffmpeg_mobile](https://github.com/leixiaohua1020/simplest_ffmpeg_mobile) ffmpeg examples in Android / IOS / WinPhone   ---- (Star:1,090) (Fork:533) (Watch:78)  

#### 视频录制@

* [SCRecorder](https://github.com/rFlex/SCRecorder) - 酷似 Instagram/Vine 的音频/视频摄像记录器，以 Objective-C 为基础的过滤器框架。 你可以做很多如下的操作：记录多个视频录像片段。删除任何你不想要的记录段。可以使用任何视频播放器播放片段。保存的记录可以在序列化的 NSDictionary 中使用。（在 NSUserDefaults 的中操作）添加使用 Core Image 的视频滤波器。可自由选择你需要的 parameters 合并和导出视频。   ---- (Star:2,694) (Fork:538) (Watch:143)  
* [LLSimpleCamera](https://github.com/omergul123/LLSimpleCamera)视频录制 A simple, customizable camera control - video recorder for iOS.   ---- (Star:1,083) (Fork:198) (Watch:52)  
* [SlowMotionVideoRecorder](https://github.com/shu223/SlowMotionVideoRecorder) 120 fps SLO-MO video recorder using AVFoundation. Including convenient wrapper class. Available on the iPhone5s.   ---- (Star:440) (Fork:102) (Watch:29)  
* [PBJVision](https://github.com/piemonte/PBJVision) iOS媒体捕获，点击录制视频，显示运动和照片. 📸 iOS Media Capture – features touch-to-record video, slow motion, and photography   ---- (Star:1,730) (Fork:332) (Watch:77)  
* [ALCameraViewController](https://github.com/AlexLittlejohn/ALCameraViewController) - ALCameraViewController 摄像头视图控制器（含可定制照片选择器，图片简单裁切功能）及演示。   ---- (Star:1,460) (Fork:236) (Watch:40)  
* [VideoBeautify](https://github.com/xujingzhou/VideoBeautify) - 功能酷似美拍,秒拍等应用的源码：对视频进行各种美化处理，采用主题形式进行分类，内含各种滤镜，动画特效和音效等。   ---- (Star:368) (Fork:116) (Watch:27)  
* [IPDFCameraViewController](https://github.com/mmackh/IPDFCameraViewController) - 支持相机定焦拍摄、滤镜、闪光、实时边框检测以及透视矫正功能，并有简单易用的API。   ---- (Star:908) (Fork:178) (Watch:60)  

#### 视频剪切@

* [ICGVideoTrimmer](https://github.com/itsmeichigo/ICGVideoTrimmer) - ICGVideoTrimmer提供提供视频剪切的视图（类似系统相册中浏览视频时顶部那个条状视图）。左右两个边界选择器还能够自定义。   ---- (Star:485) (Fork:90) (Watch:20)  
* [VideoEditing](https://github.com/ShelinShelin/VideoEditing) Video processing of the video capture and add background music   ---- (Star:79) (Fork:37) (Watch:3)  

#### 弹幕@

* [BarrageRenderer](https://github.com/unash/BarrageRenderer) 一个 iOS 上的弹幕渲染库.   ---- (Star:1,349) (Fork:327) (Watch:50)  
* [LiveSendGift](https://github.com/Jonhory/LiveSendGift) 直播发送弹幕效果   ---- (Star:186) (Fork:38) (Watch:6)  

#### 直播@

* [LFLiveKit](https://github.com/LaiFengiOS/LFLiveKit) 开源遵循RTMP协议的直播SDK   ---- (Star:2,728) (Fork:670) (Watch:139)  
* [MiaowShow](https://github.com/SunLiner/MiaowShow) iOS视频直播项目 http://www.jianshu.com/users/9723687edfb5   ---- (Star:2,288) (Fork:819) (Watch:119)  
* [LMLiveStreaming](https://github.com/chenliming777/LMLiveStreaming) IOS Live,H264 and AAC Hard coding，support GPUImage Beauty， rtmp and flv transmission，weak network lost frame，Dynamic switching rate [参考文档](http://www.jianshu.com/p/b8db6c142aad)   ---- (Star:691) (Fork:209) (Watch:42)  
* [PLPlayerKit](https://github.com/pili-engineering/PLPlayerKit) PLPlayerKit 是 Pili 直播 SDK 的 iOS 播放器。支持所有直播常用的格式，如：RTMP、HLS、FLV。拥有优秀的功能和特性，如：首屏秒开、追帧优化、丰富的数据和状态回调、硬解软解支持。而且可以根据自己的业务进行高度定制化开发。   ---- (Star:1,132) (Fork:282) (Watch:76)  
* [PLMediaStreamingKit](https://github.com/pili-engineering/PLMediaStreamingKit) PLMediaStreamingKit 是 Pili 直播 SDK 的 iOS 推流端，支持 RTMP 推流，h.264 和 AAC 编码，硬编、软编支持。具有丰富的数据和状态回调，方便用户根据自己的业务定制化开发。具有直播场景下的重要功能，如：美颜、背景音乐、水印等功能。   ---- (Star:288) (Fork:109) (Watch:26)  
* [520Linkee](https://github.com/GrayJIAXU/520Linkee)本项目实现了作为一个直播App的基本功能，比如本地视频流采集、播放、美颜、礼物、点赞出心等。   ---- (Star:1,540) (Fork:493) (Watch:69)  
* [LMLiveStreaming](https://github.com/chenliming777/LMLiveStreaming) iOS直播，支持H246/AAC，支持GPUImage美化，支持rtmp和flv，较慢的网络优化   ---- (Star:691) (Fork:209) (Watch:42)  
* [直播技术的总结](https://github.com/tiantianlan/LiveExplanation)   ---- (Star:291) (Fork:103) (Watch:20)  
* [Tencent-NOW](https://github.com/ChinaArJun/Tencent-NOW) IOS视频直播:高仿 腾讯旗下 < NOW > 直播 类似 映客 斗鱼 直播类型 喜欢的记点star谢谢 IOS Live video   ---- (Star:382) (Fork:163) (Watch:21)  

#### 图像@

* [SVGKit](https://github.com/SVGKit/SVGKit) SVGKit是一个非常强大的，可以快速渲染SVG文件的框架。你可以直接把SVG文件加载至app中，并且SVG中的每个图形会变成一个CAShapeLayer，可以方便地进行缩放和动画你的图形。如果你想渲染app中的矢量图形，SVGKit是个不错的解决办法。   ---- (Star:2,885) (Fork:620) (Watch:122)  

#### 拍照@

* [Cool-iOS-Camera](https://github.com/GabrielAlva/Cool-iOS-Camera) - Cool-iOS-Camera。   ---- (Star:1,174) (Fork:153) (Watch:47)  
* [FastttCamera](https://github.com/IFTTT/FastttCamera) - FastttCamera 快速照相   ---- (Star:1,717) (Fork:194) (Watch:59)  
* [DBCamera](https://github.com/danielebogo/DBCamera) DBCamera is a simple custom camera with AVFoundation   ---- (Star:1,268) (Fork:272) (Watch:42)  
* [ZPCamera](https://github.com/hawk0620/ZPCamera) An OpenSource Camera App   ---- (Star:493) (Fork:115) (Watch:13)  
* [HeartBeatsPlugin](https://github.com/YvanLiu/HeartBeatsPlugin) 手机摄像头测心率 带心率折线图 和 返回瞬时心率   ---- (Star:151) (Fork:43) (Watch:9)  

#### 图像处理@

* [GPUImage](https://github.com/BradLarson/GPUImage) - 处理图片效果。   ---- (Star:16,498) (Fork:4,067) (Watch:735)  
* [LearnOpenGLES](https://github.com/loyinglin/LearnOpenGLES)OpenGL ES的各种尝试   ---- (Star:664) (Fork:315) (Watch:28)  
* [GPUImage详解](http://www.jianshu.com/nb/4268718) GPUImage详解
* [OpenGLES详解](http://www.jianshu.com/p/64d9c58d8344) 一个相对完整的OpenGLES的学习博客，包含源码
* [OpenGLES系列教程](http://www.jianshu.com/nb/2135411) OpenGLES系列教程
* [CTPanoramaView](https://github.com/scihant/CTPanoramaView) - 显示球面、圆柱形的摄像.   ---- (Star:748) (Fork:36) (Watch:18)  
* [HCPhotoEdit](https://github.com/gmfxch/HCPhotoEdit) 仿 Camera360 SDK，利用GPUImage框架实现基本的图片处理功能   ---- (Star:11) (Fork:3) (Watch:4)  
* [YYImage](https://github.com/ibireme/YYImage) - 功能强大的 iOS 图像框架，支持大部分动画图像、静态图像的播放/编码/解码。   ---- (Star:1,024) (Fork:193) (Watch:37)  
* [TOCropViewController](https://github.com/TimOliver/TOCropViewController) - 图片裁剪   ---- (Star:1,784) (Fork:350) (Watch:52)  
* [BKAsciiImage](https://github.com/bkoc/BKAsciiImage) - Convert UIImage to ASCII art   ---- (Star:401) (Fork:25) (Watch:16)  
* [TinyCrayon](https://github.com/TinyCrayon/TinyCrayon-iOS-SDK) - 一个智能、易用的图片裁剪、Image markingSDK   ---- (Star:1,446) (Fork:93) (Watch:43)  
* [GPUImage Demo](https://github.com/loyinglin/GPUImage) 源码级别对GPUImage进行剖析 以及 尝试   ---- (Star:182) (Fork:114) (Watch:14)  
* [YBPasterImage](https://github.com/wangyingbo/YBPasterImage) 给图片添加滤镜、贴纸和标签功能，支持14种滤镜效果，17种标签样式。   ---- (Star:69) (Fork:25) (Watch:3)  
* [hotoimagefilter](https://www.kancloud.cn/trent/hotoimagefilter/102786) 专业介绍图像处理中各种滤镜的算法实现，C#版本.

#### 图像浏览@

* [MWPhotoBrowser](https://github.com/mwaterfall/MWPhotoBrowser) - 一个非常不错的照片浏览器，在github的star超过6000个，[解决MWPhotoBrowser中的SDWebImage加载大图导致的内存警告问题](http://www.superqq.com/blog/2015/01/22/jie-jue-mwphotobrowserzhong-de-sdwebimagejia-zai-da-tu-dao-zhi-de-nei-cun-jing-gao-wen-ti/)。   ---- (Star:7,774) (Fork:2,463) (Watch:330)  
* [TZImagePickerController](https://github.com/banchichen/TZImagePickerController) - 很赞 一个支持多选、选原图和视频的图片选择器，同时有预览功能，适配了iOS6789系统。[教程](http://www.cocoachina.com/ios/20160112/14942.html).   ---- (Star:3,879) (Fork:925) (Watch:123)  
* [RMPZoomTransitionAnimator](https://github.com/recruit-mp/RMPZoomTransitionAnimator)一个放大缩小的动效开源库，可以实现图片的放大缩小效果。   ---- (Star:1,557) (Fork:172) (Watch:55)  
* [ZLPhotoBrowser](https://github.com/longitachi/ZLPhotoBrowser) 方便易用的相册多选框架，支持预览/相册内拍照、预览快速多选相片，3DTouch预览照片，单选gif、Live Photo及video；相册混合选择；原图功能；支持多语言国际化（中文简/繁，英语，日语）；在线下载iCloud端图片；自定义最大选择量及最大预览量；自定义照片升序降序排列；自定义照片显示圆角弧度   ---- (Star:1,331) (Fork:256) (Watch:40)  
* [CLImageEditor](https://github.com/yackle/CLImageEditor) - 超强的图片编辑库，快速帮你实现旋转，防缩，滤镜等等一系列麻烦的事情。   ---- (Star:1,803) (Fork:498) (Watch:112)  
* [XBImageFilters](https://github.com/xissburg/XBImageFilters) - 图像滤镜。   ---- (Star:618) (Fork:105) (Watch:39)  
* [CoreImageShop](https://github.com/rFlex/CoreImageShop) - CoreImageShop图片滤镜处理-- Mac app that let you create a complete Core Image Filter usable on iOS using SCRecorder。   ---- (Star:375) (Fork:51) (Watch:18)  
* [EBPhotoPages](https://github.com/EddyBorja/EBPhotoPages) 类似facebook的相册浏览库.   ---- (Star:1,609) (Fork:205) (Watch:63)  
* [RSKImageCropper](https://github.com/ruslanskorb/RSKImageCropper) - 适用于iOS的图片裁剪器，类似Contacts app，可上下左右移动图片选取最合适的区域。   ---- (Star:1,852) (Fork:369) (Watch:63)  
* [WZRecyclePhotoStackView](http://code.cocoachina.com/detail/232156) - 删除照片交互--WZRecyclePhotoStackView，就是模拟生活中是删除或保留犹豫不决的情形而产生的。 在上滑，下滑的部分，借鉴了[TinderSimpleSwipeCards](https://github.com/cwRichardKim/TinderSimpleSwipeCards)。   ---- (Star:2,018) (Fork:23) (Watch:76)  
* [PhotoTweaks](https://github.com/itouch2/PhotoTweaks) - 这个库挺赞的，正好是对图像操作的。   ---- (Star:1,002) (Fork:135) (Watch:40)  
* [KYElegantPhotoGallery](https://github.com/KittenYang/KYElegantPhotoGallery) - 一个优雅的图片浏览库。   ---- (Star:423) (Fork:51) (Watch:8)  
* [SDPhotoBrowser](https://github.com/gsdios/SDPhotoBrowser) - 仿新浪动感图片浏览器,非常简单易用的图片浏览器，模仿微博图片浏览器动感效果，综合了图片展示和存储等多项功能。   ---- (Star:872) (Fork:246) (Watch:36)  
* [HZPhotoBrowser](https://github.com/chennyhuang/HZPhotoBrowser) - 一个类似于新浪微博图片浏览器的框架（支持显示和隐藏动画；支持双击缩放，手势放大缩小；支持图片存储；支持网络加载gif图片，长图滚动浏览；支持横竖屏显示）。   ---- (Star:504) (Fork:130) (Watch:15)  
* [ZZPhotoKit](https://github.com/ACEYL/ZZPhotoKit) 基于Photos和AVFoundation框架开源，相册多选与相机连拍。   ---- (Star:125) (Fork:32) (Watch:2)  
* [MarkingMenu](https://github.com/FlexMonkey/MarkingMenu) - 基于手势、类似 Autodesk Maya 风格标记菜单及图片渲染。   ---- (Star:206) (Fork:19) (Watch:8)  
* [SXPhotoShow](https://github.com/dsxNiubility/SXPhotoShow) - UICollectionViewFlowLayout流水布局 是当下collectionView中常用且普通的布局方式。本代码也写了三种好看的布局，其中LineLayout和流水布局有很大的相同点就直接继承UICollectionViewFlowLayout，然后StackLayout，CircleLayout这两种都是直接继承自最原始的UICollectionViewLayout 布局方案。   ---- (Star:186) (Fork:68) (Watch:6)  
* [PictureWatermark](https://github.com/cgwangding/PictureWatermark) - 主要实现了给图片加文字以及图片水印的功能，已封装成了UIImage的类别，方便使用。   ---- (Star:74) (Fork:18) (Watch:2)  
* [PhotoBrowser](https://github.com/CharlinFeng/PhotoBrowser) 照片浏览器   ---- (Star:562) (Fork:118) (Watch:26)  
* [StitchingImage](https://github.com/zhengjinghua/StitchingImage) - 仿微信群组封面拼接控件, 直接拖进项目就可使用，[教程](http://gold.xitu.io/entry/56395f5360b20b143a9178f6)。   ---- (Star:419) (Fork:107) (Watch:21)  
* [SDECollectionViewAlbumTransition](https://github.com/seedante/SDECollectionViewAlbumTransition) - 用自定义的 push 和 pop 实现了有趣的 iOS 相册翻开动画效果。   ---- (Star:209) (Fork:48) (Watch:8)  
* [DNImagePicker](https://github.com/AwesomeDennis/DNImagePicker) - 类似wechat的图片选择。   ---- (Star:353) (Fork:69) (Watch:13)  
* [CocoaPicker](https://github.com/lioonline/CocoaPicker) - 仿QQ图片选择器（OC）。   ---- (Star:173) (Fork:36) (Watch:1)  
* [JFImagePickerController](https://github.com/johnil/JFImagePickerController) - vvebo作者：多选照片、预览已选照片、针对超大图片优化。   ---- (Star:567) (Fork:82) (Watch:12)  
* [VIPhotoView](https://github.com/vitoziv/VIPhotoView) - 图片浏览，用于展示图片的工具类，因为是个 View，所以你可以放在任何地方显示。支持旋转，双击指定位置放大等。   ---- (Star:202) (Fork:24) (Watch:10)  
* [YUCIHighPassSkinSmoothing](https://github.com/YuAo/YUCIHighPassSkinSmoothing) - 磨皮滤镜！   ---- (Star:746) (Fork:137) (Watch:44)  
* [YUGPUImageHighPassSkinSmoothing](https://github.com/YuAo/YUGPUImageHighPassSkinSmoothing) - 一个基于 GPUImage 的磨皮滤镜！   ---- (Star:102) (Fork:28) (Watch:9)  
* [XHImageViewer] (https://github.com/JackTeam/XHImageViewer) XHImageViewer is images viewer, zoom image.   ---- (Star:366) (Fork:95) (Watch:25)  
* [card.io-iOS-SDK] (https://github.com/AllLuckly/card.io-iOS-SDK) OCR光学识别储蓄卡以及信用卡,[oc与swift使用教程](http://www.jianshu.com/p/82f73c23a76a).   ---- (Star:193) (Fork:440) (Watch:7)  
* [自定义宽高比的相册框 拍照](http://code.cocoachina.com/detail/320603/) - 取出照片时 弹出自定义view。在这个自定义view上创建一个需要的相框大小的view层 把取出的图片赋值给UIImageView按缩放添加到这个层上。对uiimageView添加捏合、移动 手势。添加按钮 选取，最后根据位移和缩放比例 裁剪image。
* [LGPhotoBrowser](https://github.com/gang544043963/LGPhotoBrowser) - LGPhotoBrowser:相册选择/浏览器/照相机（仿微信）,包含三个模块：照片浏览器，相册选择器，照相机。   ---- (Star:357) (Fork:98) (Watch:9)  
* [BeautyHour](https://github.com/xujingzhou/BeautyHour) - 完整应用，功能与“美图秀秀”雷同。   ---- (Star:97) (Fork:59) (Watch:6)  
* [WSImagePicker](https://github.com/wsjtwzs/WSImagePicker) 高性能多选图片库，类似于微信发布朋友圈中 ‘获取相册及拍照’模块   ---- (Star:47) (Fork:17) (Watch:3)  
* [JTSImageViewController](https://github.com/jaredsinclair/JTSImageViewController) - 图片浏览   ---- (Star:2,264) (Fork:273) (Watch:62)  
* [SGPhotoBrowser](https://github.com/Soulghost/SGPhotoBrowser) 图片浏览.   ---- (Star:76) (Fork:11) (Watch:4)  

#### 图像缓存@

* [Kingfisher](https://github.com/onevcat/Kingfisher) 👍👍👍一个轻量级的纯粹的用于从web下载和缓存图片的Swift库.   ---- (Star:10,033) (Fork:1,104) (Watch:259)  
* [SDWebImage](https://github.com/rs/SDWebImage) - 非常优秀的图像缓存库.   ---- (Star:18,730) (Fork:4,974) (Watch:852)  
* [UIActivityIndicator-for-SDWebImage](https://github.com/JJSaccolo/UIActivityIndicator-for-SDWebImage) 为SDWebImage显示加载效果   ---- (Star:836) (Fork:178) (Watch:28)  
* [FastImageCache](https://github.com/path/FastImageCache) - 👍 非常棒的一个 一个高效显示图片的库，支持图片缓存、平滑滚动和图片检索。   ---- (Star:7,563) (Fork:929) (Watch:349)  
* [DFImageManager](https://github.com/kean/DFImageManager) -图片加载、处理、缓存、预加载   ---- (Star:1,219) (Fork:96) (Watch:43)  
* [Twitter Image Pipline](https://github.com/twitter/ios-twitter-image-pipeline) - Twitter出品的一个高性能的图片下载、缓存库.   ---- (Star:1,420) (Fork:56) (Watch:28)  
* [AlamofireImage](https://github.com/Alamofire/AlamofireImage) - Alamofire的一个图片组件，支持图片序列化，UIImage扩展（压缩、缩放、圆角、核心图像），单个、多个的图片过滤、自动清除内存，队列图片下载、URL鉴定、图片占位和异步远程图片下载、UIImageView过滤和转换等. An image component library for Alamofire.   ---- (Star:2,697) (Fork:330) (Watch:90)  
* [AsyncImageView](https://github.com/nicklockwood/AsyncImageView) - 一个易用的UIImageView扩展，用于异步加载、显示图片，对UI显示无影响。   ---- (Star:944) (Fork:216) (Watch:66)  
* [PINRemoteImage](https://github.com/pinterest/PINRemoteImage) - 一个线程安全、高效的远程图片管理库，支持图片下载、缓存、处理，也支持GIF.   ---- (Star:3,156) (Fork:330) (Watch:87)  
* [FastImageCache](https://github.com/path/FastImageCache) -非常赞 FastImageCache 网络图片获取及缓存处理，[iOS图片加载速度极限优化—FastImageCache解析](http://blog.cnbang.net/tech/2578/)。   ---- (Star:7,563) (Fork:929) (Watch:349)  
* [YYWebImage](https://github.com/ibireme/YYWebImage) - 异步图片加载库 (supports WebP, APNG, GIF).   ---- (Star:2,925) (Fork:524) (Watch:81)  
* [EGOCache](https://github.com/enormego/EGOCache) - 十分知名的第三方缓存类库，可以缓存NSString、UIImage、NSImage以及NSData。除此，如果还可以缓存任何一个实现了<NSCoding>接口的对象。所有缓存的数据都可以自定义过期的时间，默认是1天。EGOCache 支持多线程（thread-safe），[UITableView加载多张照片导致内存上涨的问题](http://www.superqq.com/blog/2014/11/06/ioskai-fa-:uitableviewjia-zai-duo-zhang-zhao-pian-dao-zhi-nei-cun-shang-zhang-de-wen-ti/)。   ---- (Star:1,289) (Fork:297) (Watch:60)  
* [YYWebImage](https://github.com/ibireme/YYWebImage/) - 一个图片加载库 YYWebImage，支持 APNG、WebP、GIF 播放，支持渐进式图片加载，更高性能的缓存，更多图像处理方法，可以替代 SDWebImage 等开源库，[相关文章](http://blog.ibireme.com/2015/11/02/mobile_image_benchmark/)。   ---- (Star:2,925) (Fork:524) (Watch:81)  
* [JDSwiftAvatarProgress](https://github.com/JellyDevelopment/JDSwiftAvatarProgress) - 容易定制的异步图片加载进度条   ---- (Star:82) (Fork:13) (Watch:8)  
* [ImageButter](https://github.com/dollarshaveclub/ImageButter) - 平滑的处理网络图片，支持缓存，异步编码，加载进度View，GIFs动画等.   ---- (Star:382) (Fork:18) (Watch:34)  


#### 图像识别@

* [libfacedetection](https://github.com/ShiqiYu/libfacedetection) - C++ 人脸识别 包含正面和多视角人脸检测两个算法.优点:速度快(OpenCV haar+adaboost的2-3倍), 准确度高 (FDDB非公开类评测排名第二），能估计人脸角度。   ---- (Star:1,521) (Fork:762) (Watch:219)  
* [YLFaceuDemo](https://github.com/Guikunzhi/YLFaceuDemo) - 在直播应用中添加Faceu贴纸效果。Faceu贴纸效果其实就是在人脸上贴一些图片，同时这些图片是跟随着人脸的位置改变的。[说明](http://www.jianshu.com/p/ba1f79f8f6fa)   ---- (Star:214) (Fork:58) (Watch:12)  
* [IDCardRecognition](https://github.com/zhongfenglee/IDCardRecognition)中国大陆第二代身份证识别，自动读出身份证上的信息（姓名、性别、民族、住址、身份证号码）并截取身份证照片 Edit   ---- (Star:682) (Fork:164) (Watch:22)  
* [AiyaEffectsIOS](https://github.com/aiyaapp/AiyaEffectsIOS) 宝宝特效 SDK IOS Demo，支持美颜，3D特效，3D动画特效，2D特效等，免费使用 visual effects IOS demo, support 3D effect, 3D Animation, 2D effect for FREE http://www.bbtexiao.com/   ---- (Star:229) (Fork:47) (Watch:5)  

#### 图像圆角@

* [ZYCornerRadius](https://github.com/liuzhiyi1992/ZYCornerRadius) 赞 一句代码，圆角风雨无阻。A Category to make cornerRadius for UIImageView have no Offscreen-Rendered, be more efficiency. http://zyden.vicp.cc/zycornerradius/   ---- (Star:1,030) (Fork:181) (Watch:18)  

#### 数据结构/算法@

* [LearningMasteringAlgorithms-C](https://github.com/yourtion/LearningMasteringAlgorithms-C) Mastering Algorithms with C 《算法精解：C语言描述》源码及Xcode工程、Linux工程   ---- (Star:176) (Fork:54) (Watch:16)  
* [Changeset](https://github.com/osteslag/Changeset) - Minimal edits from one collection to another :large_orange_diamond:   ---- (Star:698) (Fork:33) (Watch:18)  
* [Brick](https://github.com/hyperoslo/Brick) - :droplet: A generic view model for both basic and complex scenarios :large_orange_diamond:   ---- (Star:53) (Fork:4) (Watch:12)  
* [Algorithm](https://github.com/CosmicMind/Algorithm) - Algorithm is a collection of data structures that are empowered by a probability toolset. :large_orange_diamond:   ---- (Star:589) (Fork:61) (Watch:29)  
* [AnyObjectConvertible](https://github.com/tarunon/AnyObjectConvertible) - Convert your own struct/enum to AnyObject easily. :large_orange_diamond:   ---- (Star:56) (Fork:1) (Watch:2)  
* [EKAlgorithms](https://github.com/EvgenyKarkan/EKAlgorithms) - Some well known CS algorithms & data structures in Objective-C.   ---- (Star:2,266) (Fork:364) (Watch:232)  
* [Monaka](https://github.com/naru-jpn/Monaka) - Convert custom struct and fundamental values to NSData.   ---- (Star:22) (Fork:2) (Watch:5)  
* [Pencil](https://github.com/naru-jpn/pencil) - Write values to file and read it more easily. :large_orange_diamond:   ---- (Star:70) (Fork:5) (Watch:7)  

#### 上架@

* [Solve-App-Store-Review-Problemm](https://github.com/wg689/Solve-App-Store-Review-Problem) (ipv6,ipv6被拒绝,后台定位等审核问题的终极解决方案汇总)。   ---- (Star:2,340) (Fork:364) (Watch:137)  

#### Xcode8插件@

* [Import](https://github.com/markohlebar/Import) 快捷导入头文件-Xcode extension for adding imports from anywhere in the code.   ---- (Star:689) (Fork:22) (Watch:14)  
* [XcodeSourceEditorExtension-Alignment](https://github.com/tid-kijyun/XcodeSourceEditorExtension-Alignment) 对齐属性声明 This Xcode source editor extension align your assignment statement.   ---- (Star:151) (Fork:10) (Watch:9)  
* [Dash-iOS](https://github.com/Kapeli/Dash-iOS) Dash gives your iPad and iPhone instant offline access to 150+ API documentation sets https://kapeli.com/dash_ios   ---- (Star:6,220) (Fork:888) (Watch:212)  
* [HYBUnicodeReadable](https://github.com/CoderJackyHuang/HYBUnicodeReadable) -解决打印日志对于Unicode编码不能正常显示中文的问题，只需要将文件导入工程，不需要引用，就能达到打印日志显示Unicode编码中文数据   ---- (Star:253) (Fork:79) (Watch:11)  
* [JSONExport](https://github.com/Ahmed-Ali/JSONExport) - 一个json转模型的mac软件，ESJsonFormat-Xcode的替代产品,非常不错👍 .   ---- (Star:2,877) (Fork:462) (Watch:117)  
* [WHC_DataModelFactory](https://github.com/netyouli/WHC_DataModelFactory) Mac上iOS开发辅助工具，快速把json/xml数据转换生成对应模型类属性，省去麻烦手动创建，提高开发效率。   ---- (Star:690) (Fork:148) (Watch:22)  

#### UI@

#### 综合UI@

* [Texture](https://github.com/TextureGroup/Texture)Texture——保持最复杂的用户界面的流畅和响应  Smooth asynchronous user interfaces for iOS apps.   ---- (Star:2,150) (Fork:256) (Watch:72)  
* [Material-Controls-For-iOS](https://github.com/fpt-software/Material-Controls-For-iOS) Many Google Material Design Controls for iOS native application   ---- (Star:2,128) (Fork:395) (Watch:121)  
* [Material-Controls-For-iOS](https://github.com/fpt-software/Material-Controls-For-iOS) 大神模仿谷歌做的各种各样的iOS原生特效控件，非常全面.   ---- (Star:2,128) (Fork:395) (Watch:121)  

#### 日历三方库@

* [TEAChart](https://github.com/xhacker/TEAChart) - xhacker/TEAChart 一个简洁的 iOS 图表库，支持柱状图、饼图以及日历等。   ---- (Star:1,136) (Fork:141) (Watch:44)  
* [CVCalendar](https://github.com/Mozharovsky/CVCalendar) - 是一个方便开发者集成自定义日历视图到自己 iOS 应用的项目, 支持 Storyboard 和手动配置, 使用 CocoaPods 进行安装, 提供了丰富的 API 供开发者使用。   ---- (Star:2,737) (Fork:531) (Watch:107)  

#### 下拉刷新@

* [MJRefresh](https://github.com/CoderMJLee/MJRefresh) - 仅需一行代码就可以为UITableView或者CollectionView加上下拉刷新或者上拉刷新功能。可以自定义上下拉刷新的文字说明。具体使用看“使用方法”。 （国人写）   ---- (Star:11,121) (Fork:3,276) (Watch:467)  
* [XHRefreshControl](https://github.com/xhzengAIB/XHRefreshControl) - XHRefreshControl 是一款高扩展性、低耦合度的下拉刷新、上提加载更多的组件。（国人写）   ---- (Star:702) (Fork:156) (Watch:37)  
* [CBStoreHouseRefreshControl](https://github.com/coolbeet/CBStoreHouseRefreshControl) - 一个效果很酷炫的下拉刷新控件。   ---- (Star:3,955) (Fork:561) (Watch:133)  
* [KYJellyPullToRefresh](https://github.com/KittenYang/KYJellyPullToRefresh) - 实现弹性物理效果的下拉刷新，神奇的贝塞尔曲线，配合UIDynamic写的一个拟物的下拉刷新动画。   ---- (Star:547) (Fork:65) (Watch:34)  
* [MHYahooParallaxView](https://github.com/michaelhenry/MHYahooParallaxView) - 类似于Yahoo Weather和News Digest首屏的视差滚动。   ---- (Star:652) (Fork:80) (Watch:27)  
* [SDRefreshView](https://github.com/gsdios/SDRefreshView) - 简单易用的上拉和下拉刷新（多版本细节适配）。   ---- (Star:269) (Fork:110) (Watch:18)  
* [可展开/收缩的下拉菜单--SvpplyTable](http://d.cocoachina.com/code/detail/237753) -  一个可展开可收缩的下拉菜单，类似Svpply app。
* [ODRefreshControl](https://github.com/Sephiroth87/ODRefreshControl) - 原iOS6上的橡皮糖刷新样式，很有意思。现在也很多大的 App 在用，比如虾米音乐和 QQ 客户端。   ---- (Star:2,139) (Fork:419) (Watch:111)  
* [PullToMakeSoup](https://github.com/Yalantis/PullToMakeSoup) - PullToMakeSoup, 自定义下拉刷新的动画效果：煮饭, Yalantis新作！   ---- (Star:1,700) (Fork:198) (Watch:64)  
* [TwitterCover](https://github.com/cyndibaby905/TwitterCover) -  Twitter iOS客户端的下拉封面模糊效果。   ---- (Star:1,181) (Fork:164) (Watch:38)  
* [Replace-iOS](https://github.com/MartinRGB/Replace-iOS) - Replace-iOS 让人眼前一亮的下拉刷新（iOS）。   ---- (Star:1,068) (Fork:136) (Watch:31)  
* [Animations](https://github.com/KittenYang/Animations) - 封装了一下，使用的时候只要两行代码。一些动画的飞机稿，都是一些单独分离出来的用于测试的子动画，现在统一归类一下。   ---- (Star:612) (Fork:98) (Watch:20)  
* [PullToBounce](https://github.com/entotsu/PullToBounce) - 下拉刷新的动画 for UIScrollView。   ---- (Star:1,646) (Fork:158) (Watch:39)  
* [WaterDropRefresh](https://github.com/li6185377/WaterDropRefresh) - 仿Path 水滴的下拉刷新效果 还有视差滚动。   ---- (Star:130) (Fork:36) (Watch:5)  
* [ESRefreshControl](https://github.com/EnjoySR/ESRefreshControl) - 仿新浪微博、百度外卖、网易新闻下拉刷新样式Demo（仅供参考）。   ---- (Star:139) (Fork:31) (Watch:5)  
* [WaveRefresh](https://github.com/alienjun/AJWaveRefresh) - 下拉刷新水波纹动画。   ---- (Star:110) (Fork:23) (Watch:1)  
* [DGElasticPullToRefresh](https://github.com/gontovnik/DGElasticPullToRefresh) - 是一款带有弹性效果的 iOS 下拉刷新组件。   ---- (Star:2,949) (Fork:349) (Watch:65)  
* [BanTangAnimation](https://github.com/zangqilong198812/BanTangAnimation) - 半糖下拉刷新的原理。简单来说是利用CGGlyph，字符图形转换成cgpath，然后绘制strokeEnd动画。把timeoffset和scrolloffset结合就行了。   ---- (Star:129) (Fork:23) (Watch:2)  
* [SURefresh](https://github.com/DaMingShen/SURefresh) - BOSS直聘APP下拉刷新动画实现，效果展示图－> [实现思路](http://mp.weixin.qq.com/s?__biz=MzA4ODk0NjY4NA==&mid=2701606115&idx=1&sn=98a486103668a30e16a328cbb529fe5e&scene=23&srcid=0728iIHfF3zMvIvdpqrIXCOK#rd)再复杂的动画都可以拆分成许多简单的动画组合起来，这个动画大概可以分成两个主体，我把它分别录制出来给大家看看   ---- (Star:74) (Fork:27) (Watch:2)  
* [TGRefreshOC](https://github.com/targetcloud/TGRefreshOC) 弹簧、橡皮筋下拉刷新控件，类似QQ下拉刷新效果，同时支持其他样式   ---- (Star:97) (Fork:24) (Watch:3)  

#### 模糊效果@

* [FXBlurView](https://github.com/nicklockwood/FXBlurView) - 是一个UIView子类，支持iOS5.0以上版本，支持静态、动态模糊效果，继承与UIView的模糊特效。   ---- (Star:5,001) (Fork:767) (Watch:162)  
* [VVBlurPresentation](https://github.com/onevcat/VVBlurPresentation) -很简单易用的在原来viewconntroller基础上做模糊，然后present新的viewcontroller的。   ---- (Star:912) (Fork:95) (Watch:26)  
* [UICustomActionSheet](https://github.com/pchernovolenko/UICustomActionSheet) - 通过模糊背景来着重强调与菜单相关的元素--对话框 里面已经收藏。   ---- (Star:356) (Fork:50) (Watch:10)  
* [SABlurImageView](https://github.com/szk-atmosphere/SABlurImageView) - 支持渐变动画效果的图像模糊化类库。P.S. 与前几天推存类库 SAHistoryNavigationViewController 是同一位作者。   ---- (Star:473) (Fork:39) (Watch:10)  

#### AutoLayout@

* [Masonry](https://github.com/SnapKit/Masonry) - 非常赞-Masonry是一个轻量级的布局框架，拥有自己的描述语法，采用更优雅的链式语法封装自动布局，简洁明了并具有高可读性（ [使用介绍1](http://adad184.com/2014/09/28/use-masonry-to-quick-solve-autolayout/)  [使用介绍2](http://ios.jobbole.com/81483/)），[iOS自适应前段库-Masonry的使用](http://www.cocoachina.com/ios/20150702/12217.html)），[Masonry、Classy、ClassyLiveLayout介绍](http://www.jianshu.com/p/2ed5f7444900)。[使用DEMO](https://github.com/lcddhr/DDMasonryTest) 视图居中显示、子视图含边距、视图等距离摆放、计算ScrollView的contentsize。   ---- (Star:15,566) (Fork:2,978) (Watch:767)  
* [PureLayout](https://github.com/PureLayout/PureLayout) 非常简单强大的AutoLayout库，同时支持Objective-C。非常赞👍👍👍   ---- (Star:6,686) (Fork:706) (Watch:249)  
* [Classy](https://github.com/ClassyKit/Classy) - Classy是一个能与UIKit无缝结合stylesheet(样式)系统。它借鉴CSS的思想，但引入新的语法和命名规则，[Classy官网](http://classy.as/getting-started/)，[Masonry、Classy、ClassyLiveLayout介绍](http://www.jianshu.com/p/2ed5f7444900)。   ---- (Star:760) (Fork:90) (Watch:27)  
* [ClassyLiveLayout](https://github.com/olegam/ClassyLiveLayout) - ClassyLiveLayout通过结合Classy stylesheets与Masonry一起使用，能够在运行的模拟器中微调Auto Layout约束实时显示效果的工具，[Masonry、Classy、ClassyLiveLayout介绍](http://www.jianshu.com/p/2ed5f7444900)。   ---- (Star:279) (Fork:32) (Watch:9)  
* [PureLayout](https://github.com/PureLayout/PureLayout) - PureLayout 是 iOS & OS X Auto Layout 的终极 API——非常简单，又非常强大。PureLayout 通过一个全面的Auto Layout API 扩展了 UIView/NSView, NSArray 和 NSLayoutConstraint，仿照苹果自身的框架。   ---- (Star:6,686) (Fork:706) (Watch:249)  
* [UIView-AutoLayout](https://github.com/smileyborg/UIView-AutoLayout) -   ---- (Star:1,512) (Fork:237) (Watch:75)  
Deprecated in favor of PureLayout, which includes OS X support:https://github.com/smileyborg/PureLayout。
* [UIView-FDCollapsibleConstraints](https://github.com/forkingdog/UIView-FDCollapsibleConstraints) - 一个AutoLayout辅助工具，最优雅的方式解决自动布局中子View的动态显示和隐藏的问题。第二个Demo模拟了一个经典的FlowLayout，任意一个元素隐藏时，底下的元素需要自动“顶”上来，配合这个扩展，你可以在IB里连一连，选一选，不用一行代码就能搞定。   ---- (Star:1,046) (Fork:155) (Watch:39)  
* [Autolayout_Demo](https://github.com/luodezhao/Autolayout_Demo) - 在项目中用自动布局实现的类似抽屉效果。   ---- (Star:18) (Fork:4) (Watch:1)  
* [当view隐藏的时候也隐藏其autolayout的NSLayoutAttribute](http://code.cocoachina.com/detail/320405/) - 当view隐藏的时候也隐藏其autolayout的NSLayoutAttribute，从而不用大量的代码工作
* [SDAutoLayout](https://github.com/gsdios/SDAutoLayout) - AutoLayout 一行代码搞定自动布局！支持Cell、Label和Tableview高度自适应，致力于做最简单易用的AutoLayout库。   ---- (Star:4,784) (Fork:1,202) (Watch:232)  
* [MyLinearLayout](https://github.com/youngsoft/MyLinearLayout) MyLayout is a powerful iOS UI framework implemented by Objective-C. It integrates the functions with Android Layout,iOS AutoLayout,SizeClass, HTML CSS float and flexbox and bootstrap. So you can use LinearLayout,RelativeLayout,FrameLayout,TableLayout,FlowLayout,FloatLayout,PathLayout,LayoutSizeClass to build your App 自动布局 UIView UITableView UICo…   ---- (Star:2,477) (Fork:585) (Watch:144)  
* [WHC_AutoLayoutKit](https://github.com/netyouli/WHC_AutoLayoutKit) Had better use the auto layout of open source framework，致力打造使用最简单功能最强大的自动布局开源库   ---- (Star:700) (Fork:138) (Watch:35)  
* [NerdyUI](https://github.com/nerdycat/NerdyUI) 好用的快速布局 UI 库，适用于 iOS 8 及以上版本。   ---- (Star:282) (Fork:47) (Watch:14)  

#### 图表@

* [PNChart](https://github.com/kevinzhow/PNChart) - 国内开源作者，动态的图表。   ---- (Star:8,859) (Fork:1,767) (Watch:350)  
* [XJYChart](https://github.com/JunyiXie/XJYChart) 优秀的的图表框架。支持动画，点击，滑动，区域高亮   ---- (Star:225) (Fork:34) (Watch:9)  
* [YOChartImageKit](https://github.com/yasuoza/YOChartImageKit) - 支持在watchOS上绘制图表，看它最近更新挺勤快的，可以关注一下。   ---- (Star:357) (Fork:43) (Watch:17)  
* [RealtimeGradientText](https://github.com/kevinzhow/RealtimeGradientText) - Fun With CALayer Mask 刚好今天开源了一个有趣的项目 RealtimeGradientText，所以也好聊一下 CALayer 的 Mask，[说明](http://blog.zhowkev.in/2015/07/06/fun-with-mask/)。   ---- (Star:604) (Fork:54) (Watch:15)  
* [XYPieChart](https://github.com/xyfeng/XYPieChart) -XYPieChart:饼状图,  饼图,  数据统计,  数据可视化,可以在图形上标注数据。效果十分漂亮，而且没有用到一张图片。   ---- (Star:1,736) (Fork:319) (Watch:78)  
* [ZFChart](https://github.com/Zirkfied/ZFChart) - 模仿PNChart写的一个图表库，用法简单，暂时有柱状图，线状图，饼图三种类型，后续可能会更新新的类型。   ---- (Star:536) (Fork:135) (Watch:18)  
* [ios-charts](https://github.com/danielgindi/Charts) - 一款优秀 Android 图表开源库 MPAndroidChart 的 Swift 语言实现版（支持 Objective-C 和 Swift 调用）。缺省提供的示例代码为 Objective-C。   ---- (Star:16,162) (Fork:3,032) (Watch:559)  
* [JYRadarChart](https://github.com/johnnywjy/JYRadarChart) 一个很赞的图表库   ---- (Star:390) (Fork:95) (Watch:25)  

#### 颜色@

* [Colours](https://github.com/bennyguitar/Colours) Colours–颜色库,包含100种预定义的颜色和方法   ---- (Star:2,926) (Fork:332) (Watch:113)  
* [DKNightVersion](https://github.com/Draveness/DKNightVersion) - Manage Colors, Integrate Night/Multiple Themes   ---- (Star:2,831) (Fork:444) (Watch:82)  



#### 列表相关@

#### TableView@

* [SWTableViewCell](https://github.com/CEWendel/SWTableViewCell) 非常赞 UITableViewCell 的子类, 实现了左右滑动显示信息视图并调出按钮 An easy-to-use UITableViewCell subclass that implements a swippable content view which exposes utility buttons (similar to iOS 7 Mail Application)   ---- (Star:6,923) (Fork:1,321) (Watch:285)  
* [RETableViewManager](https://github.com/romaonthego/RETableViewManager) 赞 一个非常强大的使用数据驱动的 UITableView 内容管理。可以十分方便地生成各种样式、各种功能的TableView。只要开发者能想到的列表效果或者功能，都可以利用这份代码迅速编写出来。比如，之前要实现一个填写各种资料的列表，可能需要很多代码，现在只需要几行代码就可以实现。   ---- (Star:2,328) (Fork:420) (Watch:107)  
* [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet) - 非常赞 DZNEmptyDataSet算是一个很标准的iOS内建方式，适合用来处理空的tableview和collection view。会自动将collection view处理完善，并将用户消息以合适美观的方式显示出来。每个iOS项目都可以自动处理。   ---- (Star:9,331) (Fork:1,341) (Watch:237)  
* [folding-cell](https://github.com/Ramotion/folding-cell) 很赞 一个比较酷炫的cell折叠动画效果   ---- (Star:6,545) (Fork:814) (Watch:199)  
* [VVeboTableViewDemo](https://github.com/johnil/VVeboTableViewDemo) 此项目由VVebo剥离，希望你能通过这个demo看到我是如何进行TableView流畅度优化的。   ---- (Star:2,058) (Fork:393) (Watch:79)  
* [SWTableViewCell](https://github.com/onevcat/SWTableViewCell) - 国内开源作者，带很多手势的表单元格。   ---- (Star:96) (Fork:1,321) (Watch:5)  
* [MGSwipeTableCell](https://github.com/MortimerGoro/MGSwipeTableCell) - 另一个常见于很多应用中的UI组件，苹果应该考虑在标准的iOS SDK中加入一些类似的内容。Swipeable表格cell是这个pod的最佳描述，也是最好的。非常👍👍👍   ---- (Star:5,824) (Fork:942) (Watch:206)  
* [MCSwipeTableViewCell](https://github.com/alikaragoz/MCSwipeTableViewCell) - 带很多手势的表单元格。   ---- (Star:3,011) (Fork:436) (Watch:155)  
* [TMQuiltView](https://github.com/1000Memories/TMQuiltView) - 瀑布流。   ---- (Star:594) (Fork:135) (Watch:58)  
* [XRWaterfallLayout](https://github.com/codingZero/XRWaterfallLayout) - 超简单的瀑布流实现,[实现说明](http://www.cocoachina.com/ios/20160407/15872.html)。   ---- (Star:153) (Fork:33) (Watch:4)  
* [WaterfallFlowDemo](https://github.com/lengmolehongyan/WaterfallFlowDemo) - 一个简单的UICollectionView瀑布流布局演示demo。   ---- (Star:79) (Fork:37) (Watch:5)  
* [XLForm](https://github.com/xmartlabs/XLForm) - 很多表格类的table,写法更高冷一点，推荐使用。   ---- (Star:4,705) (Fork:827) (Watch:151)  
* [UIScrollSlidingPages](https://github.com/TomThorpe/UIScrollSlidingPages) - 允许添加多视图控件，并且可以横向滚动。有点类似于Groupon app。   ---- (Star:946) (Fork:157) (Watch:58)  
* [HorizontalScrollCell](https://github.com/mcelayir/HorizontalScrollCell) - HorizontalScrollCell是一款使用方便的水平方向可滚动的单元格，适用于UICollectionView中实现水片方向滚动视图。 。   ---- (Star:92) (Fork:16) (Watch:7)  
* [SYJiugonggeTableView](https://github.com/shiyuan17/syTableView) - tableView封装的九宫格。   ---- (Star:31) (Fork:8) (Watch:2)  
* [UUChatTableView](https://github.com/ZhipingYang/UUChatTableView) - UUChatTableView 气泡聊天界面，支持文本、图片以及音频的气泡聊天界面。[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。   ---- (Star:1,703) (Fork:420) (Watch:77)  
* [Atlas-iOS](https://github.com/layerhq/Atlas-iOS) - 快速在iOS里集成聊天功能，类似开源版本的环信。Layer家开源了一套聊天app界面的解决方案.看起来很赞，很多蛮复杂的东西直接都帮封好了。不得不说现在做app开发真是很简单，大部分时间搭积木就可以了。[官方网站](https://atlas.layer.com/)。   ---- (Star:3,683) (Fork:546) (Watch:130)  
* [DLSlideView](https://github.com/agdsdl/DLSlideView) - DLSlideView对常见的顶部Tab页点击、滑动分页做了封装。它使用基于ViewController的container特性（而不是scrollview）来管理各个子页面，以支持无限分页，[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。   ---- (Star:525) (Fork:122) (Watch:23)  
* [VOVCManager](https://github.com/pozi119/VOVCManager) - 页面管理器:1.跳转指定页面,只需要知道viewController的Class名,如果有storyboard,则需要指定storyboard名；2.无需添加基类；3.支持URLScheme跳转指定页面。   ---- (Star:83) (Fork:20) (Watch:8)  
* [MBXPageViewController](https://github.com/Moblox/MBXPageViewController) - 简洁快速的页面切换--MBXPageViewController，带有按钮控件的UIPageController，非常整洁、简单以及快速。该项目通过三种形式展示页面之间的切换，比如导航栏上的多个tab切换、页面左右两端箭头指示切换，以及使用分段控件。   ---- (Star:150) (Fork:36) (Watch:7)  
* [PagerTab](https://github.com/ming1016/PagerTab) - UIScrollView实现滑动转换页面，类似网易云音乐iOS版的页面滑动切换效果。   ---- (Star:333) (Fork:59) (Watch:8)  
* [BATabBarController](https://github.com/antiguab/BATabBarController) - A TabBarController with a unique animation for selection [GUITabPagerViewController](https://github.com/guilhermearaujo/GUITabPagerViewController) - 多个tab滑动切换。   ---- (Star:640) (Fork:90) (Watch:18)  
* [VOMetroLayoutDemo](https://github.com/pozi119/VOMetroLayoutDemo) - Metro风格的UICollectionView, 目前只支持横向布局,仅在iPad上应用。   ---- (Star:12) (Fork:0) (Watch:1)  
* [KYCellAnimation](https://github.com/KittenYang/KYCellAnimation) - 给UITableViewCell增加进入的动画。   ---- (Star:20) (Fork:0) (Watch:1)  
* [RDVTabBarController](https://github.com/robbdimitrov/RDVTabBarController) - 一个TabBar组件，可以方便设置底部菜单的文字图片，点击效果，小红点提示等。   ---- (Star:2,039) (Fork:483) (Watch:76)  
* [WXTabBarController](https://github.com/leichunfeng/WXTabBarController) - 在系统 UITabBarController 的基础上完美实现了安卓版微信 TabBar 的滑动切换功能，单手操作 iPhone 6 Plus 切换 TabBar 一直是一件很痛苦的事情，而滑动切换是一种不错的解决方案，支持屏幕旋转。   ---- (Star:927) (Fork:193) (Watch:23)  
* [GooeyTabbar](https://github.com/KittenYang/GooeyTabbar) - 皮筋式弹性缩放工具栏示例及演示。   ---- (Star:695) (Fork:59) (Watch:21)  
* [横向展示文本内容的自定义cell](http://d.cocoachina.com/code/detail/298409) - 可以横向展示文本内容的自定义cell，根据文本无限滚动。
* [ExpandingStackCells](https://github.com/jozsef-vesza/ExpandingStackCells) - 采用 UIStackView 实现表格单元格扩展内容显示示例及解决方案。   ---- (Star:289) (Fork:13) (Watch:9)  
* [FDStackView](https://github.com/forkingdog/FDStackView) - 可以将 UIStackView 的最低支持版本拉低到 iOS6，无需配置，没有代码侵染，扔到工程里后直接用系统 UIStackView 的 API 即可，同时兼容 Storyboard。   ---- (Star:2,324) (Fork:320) (Watch:76)  
* [MDIHorizontalSectionTableViewController](https://github.com/WeeTom/MDIHorizontalSectionTableViewController) - 根据产品需求开源了一个交互项目，可以理解为横向Section的TableView，section和cell同时支持拖拽，后续安卓版本也会开源出来。   ---- (Star:120) (Fork:11) (Watch:6)  
* [JZNavigationExtension](https://github.com/JazysYu/JZNavigationExtension) - 多功能导航控制器，可以透明返回栏。   ---- (Star:1,213) (Fork:175) (Watch:33)  
* [QuickRearrangeTableView](https://github.com/okla/QuickRearrangeTableView) - 基于 UITableView 的快速重排功能扩展子类。通过长按选定单元格然后滚动移动到指定位置。   ---- (Star:479) (Fork:34) (Watch:18)  
* [uicollectionview-reordering](https://github.com/nshintio/uicollectionview-reordering) - UICollectionViews的拖拽(拖动、移动)效果,[实例教程](http://nshint.io/blog/2015/07/16/uicollectionviews-now-have-easy-reordering/).   ---- (Star:429) (Fork:99) (Watch:19)  
* [LLNoDataView](https://github.com/LvJianfeng/LLNoDataView) - 超简单的空数据提示通用View支持UIScrollView、UITableView、UICollectionView、UIWebView。   ---- (Star:86) (Fork:17) (Watch:2)  
* [XLPlainFlowLayout](https://github.com/HebeTienCoder/XLPlainFlowLayout) - 可以让UICollectionView的header也支持悬停效果，类似于tableView的Plain风格。   ---- (Star:413) (Fork:115) (Watch:13)  
* [WMPageController](https://github.com/wangmchn/WMPageController) - 一个方便的 pageContrller 的控件，里面还包括滚动视图。   ---- (Star:1,785) (Fork:392) (Watch:54)  
* [PSTCollectionView](https://github.com/steipete/PSTCollectionView) - PSTCollectionView。   ---- (Star:2,511) (Fork:528) (Watch:173)  
* [LLRiseTabBar-iOS](https://github.com/lianleven/LLRiseTabBar-iOS) - 直接使用系统的特性实现的tabbar，比较简单。   ---- (Star:56) (Fork:132) (Watch:2)  
* [MTMaterialDelete](https://github.com/MartinRGB/MTMaterialDelete) - 非常有趣的Material Design动画，动画删除表里面的单元格。   ---- (Star:834) (Fork:108) (Watch:24)  
* [BusyNavigationBar](https://github.com/gmertk/BusyNavigationBar) - 进度条式NavigationBar导航条。   ---- (Star:870) (Fork:57) (Watch:17)  
* [LGSettingView](https://github.com/LiGoEX/LGSettingView) - LGSettingView仅需三句代码即可快速集成设置界面，免去每次开发新应用都要重新布置设置界面的烦恼。   ---- (Star:45) (Fork:10) (Watch:0)  
* [微博cell自动布局](http://code.cocoachina.com/view/129212) - 使用autoLayout对微博的cell进行自动布局，自适应cell的高度。
* [TreeTableView](https://github.com/TyroneWing/TreeTableView) - ZYTreeTableView：TreeView 模仿好友列表的实现方式。   ---- (Star:2) (Fork:0) (Watch:1)  
* [ZWSlideViewController](https://github.com/squarezw/ZWSlideViewController) - ZWSlideViewController多页滑动视图控制器（类似新闻类门户APP）,可以用最简单的继承方法使用，也可以不用继承，只用菜单或主视图页面，可实现丰富的定制，可以使用在多种不同形态的APP下，还可以将其做为多页或多图的滑动介绍。   ---- (Star:77) (Fork:15) (Watch:7)  
* [XWCatergoryView](https://github.com/wazrx/XWCatergoryView) - 一个轻量级的顶部分类视图控件，只需要通过简单的设置，你就可以快速集成该控件， 控件目前暂时有底部横条移动，椭圆背景移动，文字缩放，文字颜色变化，和文字颜色渐变五种效果，五种效果可以叠加使用也可以单一使用。[实现教程](http://www.jianshu.com/p/274d19f97564)   ---- (Star:91) (Fork:21) (Watch:4)  
* [jingDongFenLei](http://code.cocoachina.com/view/129675) - 简单仿写京东分类中的多级分类页面。
* [RKSwipeBetweenViewControllers](https://github.com/cwRichardKim/RKSwipeBetweenViewControllers) - 页面滑动和标签选项卡类库。   ---- (Star:1,651) (Fork:168) (Watch:56)  
* [FriendSearch](http://www.cocoachina.com/ios/20160407/15870.html) - 两种UI的搜索，搜索的算法可以满足中英文互搜，联想搜索等，其中还包含对一组数据自动进行按字母分组等功能。
* [YX_UITableView_IN_UITableView](https://github.com/yixiangboy/YX_UITableView_IN_UITableView) - UITableview嵌套UITableView案例实践（仿淘宝商品详情页实现），[项目讲解](http://blog.csdn.net/yixiangboy/article/details/51009010)。   ---- (Star:227) (Fork:52) (Watch:5)  
* [TYPagerController](https://github.com/12207480/TYPagerController) - 简单，支持定制，页面控制器,可以滚动内容和标题栏,包含多种style。   ---- (Star:736) (Fork:123) (Watch:15)  
* [YZHeaderScaleImage](https://github.com/iThinkerYZ/YZHeaderScaleImage)一行代码快速集成tableView中头部缩放视图   ---- (Star:163) (Fork:50) (Watch:11)  
* [ExpandTableView](https://github.com/zhengwenming/ExpandTableView) 可折叠展开的tableView，QQ好友分组列表。   ---- (Star:97) (Fork:29) (Watch:5)  
* [SwipeTableView](https://github.com/Roylee-ML/SwipeTableView) Both scroll horizontal and vertical for segment scrollview which have a same header. — 类似半糖、美丽说主页与QQ音乐歌曲列表布局效果，实现不同菜单的左右滑动切换，同时支持类似tableview的顶部工具栏悬停（既可以左右滑动，又可以上下滑动）。兼容下拉刷新，自定义 collectionview实现自适应 contentSize 还可实现瀑布流功能   ---- (Star:1,162) (Fork:269) (Watch:39)  
* [TableViewAnimationKit](https://github.com/alanwangmodify/TableViewAnimationKit) TableView Animation ，move your tableView   ---- (Star:364) (Fork:60) (Watch:7)  

#### TableView适配@

* [UITableView-FDTemplateLayoutCell](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) - UITableView-FDTemplateLayoutCell 是一个方便缓存 UITableViewCell 的高度的框架。   ---- (Star:8,183) (Fork:1,806) (Watch:331)  

#### CollectionView@

* [SFFocusViewLayout](https://github.com/fdzsergio/SFFocusViewLayout)UICollectionView的高级使用方法哦SFFocusViewLayou   ---- (Star:1,587) (Fork:189) (Watch:39)  
* [RACollectionViewReorderableTripletLayout](https://github.com/ra1028/RACollectionViewReorderableTripletLayout)自定义的CollectionView布局，可以通过拖动进行cell的重新排序。   ---- (Star:1,390) (Fork:196) (Watch:53)  
* [IGListKit](https://github.com/Instagram/IGListKit) IGListKit是Instagram推出的新的UICollectionView框架，使用数据驱动，旨在创造一个更快更灵活的列表控件。   ---- (Star:6,937) (Fork:668) (Watch:233)  
* [CollectionViewClassifyMenu](https://github.com/ChenYilong/CollectionViewClassifyMenu)CollectionView做的两级菜单，可以折叠第二级菜单   ---- (Star:1,293) (Fork:351) (Watch:43)  
* [TableFlip](https://github.com/mergesort/TableFlip) A simpler way to do cool UITableView animations   ---- (Star:343) (Fork:32) (Watch:11)  
* [DraggingSort](https://github.com/HelloYeah/DraggingSort) 长按拖拽排序   ---- (Star:212) (Fork:57) (Watch:5)  
* [WCLWaterFallLayout](https://github.com/631106979/WCLWaterFallLayout) 用swift写的简易的瀑布流布局，简单易用，支持多行展示，实现过程：http://blog.csdn.net/wang631106979/article/details/53793046   ---- (Star:14) (Fork:4) (Watch:1)  
* [AppStore-Horizontal-Demo](https://github.com/liao3841054/AppStore-Horizontal-Demo) 仿半糖App 个人中心可以横向滚动的 列表 UICollectionView UITableView UISrcrollView   ---- (Star:109) (Fork:38) (Watch:4)  

#### 对话交互@
#### 隐藏与显示@

* [SlideTapBar](http://d.cocoachina.com/code/detail/286102) - 滚动栏菜单，向上滚动时隐藏tabbar，向下滚动马上显示tabbar。
* [FoldingTabBar.iOS](https://github.com/Yalantis/FoldingTabBar.iOS) - 可折叠Tab Bar和Tab Bar Controller。   ---- (Star:3,353) (Fork:443) (Watch:138)  
* [KMNavigationBarTransition](https://github.com/MoZhouqi/KMNavigationBarTransition) - LTNavigationBar在右滑返回的时候NavigationBar显示都不完美,KMNavigationBarTransition一个用来统一管理导航栏转场以及当 push 或者 pop 的时候使动画效果更加顺滑的通用库，并且同时支持竖屏和横屏。   ---- (Star:2,215) (Fork:279) (Watch:49)  
* [HYNavBarHidden](https://github.com/HelloYeah/HYNavBarHidden) - 导航条滚动透明，超简单好用的监听滚动,导航条渐隐的UI效果实现。   ---- (Star:329) (Fork:50) (Watch:6)  
* [BLKFlexibleHeightBar](https://github.com/bryankeller/BLKFlexibleHeightBar) - 非常赞，是一个使导航栏高度可以动态变化的 UI 库。固定Header的效果库，一个拥有非常灵活高度的标题栏，可以为使用软件的用户提供更多的阅读和滑动空间，现在已经被众多app所采用。   ---- (Star:2,953) (Fork:344) (Watch:87)  
* [JXT_iOS_Demos](https://github.com/kukumaluCN/JXT_iOS_Demos) - AboutNavigationBar:一些关于navigationBar的非常规的但是较为实用的操作，包括利用毛玻璃、动态透明、动态隐藏，以及头视图的动态缩放，并同时涉及了statusBar的动态设置（换色）。[教程](http://www.jianshu.com/p/b2585c37e14b)。   ---- (Star:264) (Fork:62) (Watch:7)  
* [NavigationBarScaleViewDemo](https://github.com/CoderJackyHuang/NavigationBarScaleViewDemo) - iOS导航条自由缩放头像效果。[原理剖析](http://www.henishuo.com/nav-photo-scale/)。   ---- (Star:30) (Fork:9) (Watch:3)  

#### HUD与Toast@

* [MBProgressHUD](https://github.com/jdg/MBProgressHUD) - 非常赞 最多人用的loading。   ---- (Star:13,835) (Fork:3,359) (Watch:618)  
* [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) - 非常赞 SVProgressHUD的loading，如果你需要定制化的等待提示器，这个就是了（也许是最好的）。   ---- (Star:10,283) (Fork:2,190) (Watch:340)  
* [JDStatusBarNotification](https://github.com/calimarkus/JDStatusBarNotification) 非常赞👍👍👍 的自定义顶部通知. Easy, customizable notifications displayed on top of the statusbar.   ---- (Star:3,305) (Fork:490) (Watch:105)  
* [Toast](https://github.com/scalessec/Toast) An Objective-C category that adds toast notifications to the UIView object class.   ---- (Star:2,737) (Fork:568) (Watch:109)  
* [EBuyCommon](https://github.com/LvJianfeng/EBuyCommon) - 1.基于MBProgressHUD实现得图形加载提示方式，及其它标题方式提醒。2.弹窗。   ---- (Star:65) (Fork:35) (Watch:5)  
* [WZDraggableSwitchHeaderView](https://github.com/wongzigii/WZDraggableSwitchHeaderView)Show status for transition across viewControllers.   ---- (Star:510) (Fork:46) (Watch:16)  
* [ProgressHUD](https://github.com/relatedcode/ProgressHUD) - ProgressHUD的loading，使用最简单。   ---- (Star:954) (Fork:194) (Watch:37)  
* [MMProgressHUD](https://github.com/mutualmobile/MMProgressHUD) - 设置HUD出现和消失的方式（包括上下、左右、淡入淡出、放大缩小等等），设置HUD的内容（可以在HUD中加入帧动画、动态图片等等），设置HUD出现时的底部覆盖层颜色，等等。总而言之，这是一份集大成的HUD代码。慢慢看视频吧，括了所有效果。   ---- (Star:716) (Fork:148) (Watch:50)  
* [WSProgressHUD](https://github.com/devSC/WSProgressHUD) - 一个小巧精致的HUD,支持添加到自定义View上, 还有更多小细节.。   ---- (Star:532) (Fork:82) (Watch:20)  
* [PreLoader](https://github.com/liuzhiyi1992/PreLoader) - 一个很有意思的HUD loading ，通过运动污点和固定污点之间的粘黏动画吸引用户的眼球跟踪，能有效分散等待注意力。[PreLoader的实现讲解](http://www.cocoachina.com/ios/20160427/16029.html)   ---- (Star:135) (Fork:25) (Watch:5)  
* [FillableLoaders](https://github.com/poolqf/FillableLoaders) - 自定义加载进度UI-Completely customizable progress based loaders drawn using custom CGPaths written in Swift :large_orange_diamond:   ---- (Star:1,744) (Fork:138) (Watch:39)  
* [TopAlert](https://github.com/roycms/TopAlert) 顶部提示View.   ---- (Star:23) (Fork:6) (Watch:9)  

#### 对话框@

* [LCActionSheet](https://github.com/iTofu/LCActionSheet) 一款简约而不失强大的 ActionSheet，微信和微博都采取了极其类似的样式。   ---- (Star:549) (Fork:129) (Watch:15)  
* [WCAlertView](https://github.com/m1entus/WCAlertView) - 自定义的对话框。   ---- (Star:650) (Fork:102) (Watch:52)  
* [IOS7AlertView](https://github.com/wimagguc/ios-custom-alertview) - IOS7AlertView的对话框。   ---- (Star:1,544) (Fork:398) (Watch:65)  
* [STPopup](https://github.com/kevin0571/STPopup) - 提供了一个可在 iPhone 和 iPad 上使用的具有 UINavigationController 弹出效果的 STPopupController 类, 并能在 Storyboard 上很好的工。   ---- (Star:2,022) (Fork:282) (Watch:62)  
* [AMSmoothAlert](https://github.com/mtonio91/AMSmoothAlert) - 动画效果不错，最多star，但不支持arm64。   ---- (Star:1,304) (Fork:182) (Watch:46)  
* [DQAlertView](https://github.com/dinhquan/DQAlertView) - 扁平化的样式不错。   ---- (Star:191) (Fork:45) (Watch:9)  
* [HHAlertView](https://github.com/mrchenhao/HHAlertView) - 一个简易的alertview  有三种样式，有成功，失败，和警告三种样式，支持Delegate和block两种回调。   ---- (Star:163) (Fork:42) (Watch:6)  
* [MJPopupViewController](https://github.com/martinjuhasz/MJPopupViewController) - 实现弹出视图的各种弹出和消失效果，包括淡入淡出（fade in，fade out），从屏幕上方飞进，下方飞出，从屏幕左方飞进，右方飞出等等效果，弹窗。   ---- (Star:987) (Fork:243) (Watch:58)  
* [MMPopupView](https://github.com/adad184/MMPopupView) - 弹出框的基类组件（弹窗）。   ---- (Star:1,773) (Fork:358) (Watch:63)  
* [Menu](https://github.com/fengchuanxiang/Menu) - 项目中可能会用到的常用菜单，以后有时间会继续补充，弹窗。   ---- (Star:41) (Fork:11) (Watch:1)  
* [EasyTipView](https://github.com/teodorpatras/EasyTipView) - 弹出提示框类及演示示例。同样地，API 简单、易用。好“轮子”，弹窗。     ---- (Star:1,714) (Fork:224) (Watch:43)  
* [kxmenu](https://github.com/kolyvan/kxmenu) - kxmenu弹出菜单，点击视图上任意位置的按钮，会弹出一个菜单，并且有个小箭头指向点击的按钮，类似气泡视图。弹出的菜单位置会根据按钮的位置来进行调整。   ---- (Star:1,712) (Fork:390) (Watch:84)  
* [QBPopupMenu](https://github.com/questbeat/QBPopupMenu) - QBPopupMenu弹出菜单，实现类似 UIMenuItem 的弹出菜单按钮。点击按钮，会弹出一个菜单，上面可以排列多个按钮。纯代码实现，不需要任何图片。   ---- (Star:1,274) (Fork:221) (Watch:45)  
* [GMenuController](https://github.com/GIKICoder/GMenuController) - 具有和系统UIMenuController行为,交互一致的Menu弹出控件.相比UIMenuController.具有更加友好的使用方式. 支持MenuItem指定target.使用更加灵活,支持更改menuview 外观设置。   ---- (Star:16) (Fork:4) (Watch:3)  
* [STModalDemo](https://github.com/zhenlintie/STModalDemo) - 弹出视图（通知，提示，选择，窗口）。   ---- (Star:96) (Fork:33) (Watch:2)  
* [TAOverlay](https://github.com/TaimurAyaz/TAOverlay) - TAOverlay可通过叠加层展示有用的信息，可自定义文本和背景色，添加阴影和模糊效果，以及更改字体大小或者用自定义图片替换页面上的icon。   ---- (Star:691) (Fork:64) (Watch:17)  
* [UICustomActionSheet](https://github.com/pchernovolenko/UICustomActionSheet) - 通过模糊背景来着重强调与菜单相关的元素--模糊效果 里面已经收藏。   ---- (Star:356) (Fork:50) (Watch:10)  
* [ActionSheetPicker-3.0](http://code.cocoachina.com/detail/232178) - 该项目是此前热门项目ActionSheetPicker的新版本，快速复制了iOS 8上的下拉 UIPickerView/ActionSheet功能。
* [MJAlertView](https://github.com/mayuur/MJAlertView) - 3D效果转场效果警示图--MJAlertView。   ---- (Star:279) (Fork:38) (Watch:13)  
* [PSTAlertController](https://github.com/steipete/PSTAlertController) - 兼容 iOS7的 XXAlertController，接口跟UIAlertController 一模一样，做到高低版本通用。   ---- (Star:760) (Fork:92) (Watch:23)  
* [PCLBlurEffectAlert.swfit](https://github.com/hryk224/PCLBlurEffectAlert) - 细节定制较丰富的弹出警报窗口组件。   ---- (Star:125) (Fork:15) (Watch:6)  
* [GSAlert.swfit](https://github.com/wxxsw/GSAlert) - 苹果在iOS8推出了全新的UIAlertController，旧的UIAlertView和UIActionSheet渐渐被废弃，但如果你仍然支持iOS7系统，你将不得不写两套代码。GSAlert解决了这个问题。   ---- (Star:25) (Fork:4) (Watch:1)  
* [SweetAlert-iOS](https://github.com/codestergit/SweetAlert-iOS) - SweetAlert-iOS 带动画效果弹窗对话框封装类。   ---- (Star:1,762) (Fork:248) (Watch:61)  
* [CCActionSheet](https://github.com/maxmoo/CCActionSheet) - CCActionSheet：仿照微信朋友圈自定义actionsheet，一行代码即可使用。   ---- (Star:26) (Fork:7) (Watch:2)  
* [CustomPopOverView](https://github.com/maltsugar/CustomPopOverView) - 自定义弹出视图，内容支持传一组菜单标题，也支持自定义view，或者自定义viewController，支持任意按钮触发，会显示在按钮底部，也支持切换按钮的对齐方式：左对齐、居中、右对齐。   ---- (Star:59) (Fork:19) (Watch:3)  
* [TOActionSheet](https://github.com/TimOliver/TOActionSheet) 是一个 iOS UI 控件，提供一个模态提示控制，类似于 UIActionSheet。不同于 UIActionSheet 的是，它可以深度重设主题，通过对每个按钮使用块来避免委托模式   ---- (Star:156) (Fork:19) (Watch:13)  

#### Pop@

* [AMPopTip](https://github.com/andreamazz/AMPopTip) 一个可以定义frame的带动画的popover. An animated popover that pops out a given frame, great for subtle UI tips and onboarding.   ---- (Star:1,941) (Fork:281) (Watch:49)  
* [DXPopover](https://github.com/xiekw2010/DXPopover) 很赞 DXPopover微信右上角的+点击展示列表效果，弹窗菜单。 A Popover mimic Facebook app popover using UIKit   ---- (Star:629) (Fork:142) (Watch:24)  
* [zhPopupController](https://github.com/snail-z/zhPopupController) Popup your custom view is easy, support custom mask style, transition effects and gesture to drag.   ---- (Star:767) (Fork:151) (Watch:21)  
* [LewPopupViewController](https://github.com/pljhonglu/LewPopupViewController) ios 弹出视图   ---- (Star:127) (Fork:31) (Watch:8)  
* [PopMenu](https://github.com/xhzengAIB/PopMenu) - 用POP动画引擎写的Sina微博的Menu菜单。   ---- (Star:810) (Fork:208) (Watch:23)  
* [MLMOptionSelectView](https://github.com/MengLiMing/MLMOptionSelectView) 弹出-选择-展示框   ---- (Star:113) (Fork:23) (Watch:5)  

#### 通知相关@

* [JSQNotificationObserverKit](https://github.com/jessesquires/JSQNotificationObserverKit) - 一款轻量、易用的通知发送及响应框架类库。作者是知名开源项目 JSQMessagesViewController（Objective-C 版即时聊天）的作者 Jesse Squires.   ---- (Star:169) (Fork:9) (Watch:7)  
* [CWStatusBarNotification](https://github.com/cezarywojcik/CWStatusBarNotification) 酷炫的通知栏，多种通知样式，使用简单,非常赞👍 .   ---- (Star:1,881) (Fork:256) (Watch:52)  
* [GLPubSub](https://github.com/Glow-Inc/GLPubSub) - 一个简短实用的 NSNotificationCenter 的封装。   ---- (Star:235) (Fork:27) (Watch:9)  
* [JDStatusBarNotification](https://github.com/jaydee3/JDStatusBarNotification) - 在状态栏顶部显示通知。可以自定义颜色字体以及动画。支持进度显示以及显示状态指示器。   ---- (Star:3,305) (Fork:490) (Watch:105)  

#### 状态栏@

* [MTStatusBarOverlay](https://github.com/myell0w/MTStatusBarOverlay) MTStatusBarOverlay 是一个定制的 iOS 状态栏，用于覆盖系统默认的状态栏，类似 Reeder, Evernote and Google Mobile App。支持两种点击动作：1. 当用户点击状态栏时，状态栏会收缩，仅仅遮盖住状态栏右方的电池图标；2. 当用户点击状态栏时，一个有详细信息的视图会从系统状态栏中下拉出现。   ---- (Star:1,993) (Fork:367) (Watch:92)  

#### 导航栏@

* [WRNavigationBar](https://github.com/wangrui460/WRNavigationBar) 超简单！！！ 一行代码设置状态栏、导航栏按钮、标题、颜色、透明度，移动等   ---- (Star:1,026) (Fork:216) (Watch:18)  
* [AMScrollingNavbar](https://github.com/andreamazz/AMScrollingNavbar) 一个可以上拉隐藏导航栏和下拉显示导航栏的框架   ---- (Star:4,993) (Fork:540) (Watch:132)  
* [JTNavigationController](https://github.com/JNTian/JTNavigationController) 一个拥有更平滑的navigationBar切换动画的NavigationController   ---- (Star:475) (Fork:97) (Watch:15)  
* [NavigationController](https://github.com/Roxasora/RxWebViewController) 实现类似微信的 webView 导航效果，包括进度条，左滑返回上个网页或者直接关闭，就像 UINavigationController   ---- (Star:1,097) (Fork:218) (Watch:28)  
* [LTNavigationBar](https://github.com/ltebean/LTNavigationBar) 叠。[实现教程](http://tech.glowing.com/cn/change-uinavigationbar-backgroundcolor-dynamically/)   ---- (Star:4,227) (Fork:688) (Watch:117)  

#### 设置@

* [InAppSettingsKit](https://github.com/futuretap/InAppSettingsKit) InAppSettingsKit 是一款功能强大的ios设置组件，可以满足各种各样的app设置需求。   ---- (Star:2,810) (Fork:523) (Watch:118)  
* [ViralSwitch](https://github.com/andreamazz/ViralSwitch) A UISwitch that infects its superview with its tint color.   ---- (Star:315) (Fork:27) (Watch:13)  


#### Switch@

* [JTMaterialSwitch](https://github.com/JunichiT/JTMaterialSwitch) A Customizable Switch UI for iOS, Inspired from Google's Material Design   ---- (Star:231) (Fork:40) (Watch:8)  
* [LLSwitch](https://github.com/lilei644/LLSwitch) 一个有趣的switch   ---- (Star:505) (Fork:60) (Watch:11)  

#### Label@

* [PPCounter](https://github.com/jkpang/PPCounter) - 一款简单实用的数字加减动画,支持UILabel、UIButton显示   ---- (Star:310) (Fork:49) (Watch:7)  

#### Search@

* [PYSearch](https://github.com/iphone5solo/PYSearch) 非常赞 An elegant search controller for iOS.   ---- (Star:2,494) (Fork:534) (Watch:65)  
* [search](https://github.com/mrhyh/search) 搜索历史标签   ---- (Star:0) (Fork:0) (Watch:1)  
* [CYLSearchViewController](https://github.com/ChenYilong/CYLSearchViewController) 模仿iPhone短信聊天里的搜索框样式，点击搜索后，搜索框平滑移动到导航栏上。   ---- (Star:158) (Fork:62) (Watch:4)  

#### 主题@

* [LEETheme](https://github.com/lixiang1994/LEETheme) 优雅的主题管理库- 一行代码完成多样式切换   ---- (Star:326) (Fork:60) (Watch:14)  
* [PYTheme](https://github.com/iphone5solo/PYTheme)  PYTheme通过NSObject的分类实现使用简单的主题更换。 An easy way to change theme through NSObject's category for iOS.   ---- (Star:368) (Fork:87) (Watch:10)  

#### 电影选座@

* [ZFSeatsSelection](https://github.com/ZFbaby/ZFSeatsSelection) 高仿猫眼电影选座（选票）模块（High imitation opal film seat selection (vote) module）   ---- (Star:359) (Fork:85) (Watch:9)  
* [FVSeatsPicker](https://github.com/Upliver/FVSeatsPicker) FVSeatsPicker是一个高性能的选座框架，可以直接pod引入，使用时可以直接当做View添加到任何视图控件内部！   ---- (Star:93) (Fork:28) (Watch:1)  

#### 瀑布流@

* [CHTCollectionViewWaterfallLayout](https://github.com/chiahsien/CHTCollectionViewWaterfallLayout) 赞 UICollectionViewLayout的一个子类，尽可能地模仿了UICollectionViewFlowLayout的用法，灵感来源于Pinterest，同时还兼容PSTCollectionView。   ---- (Star:3,444) (Fork:588) (Watch:138)  

#### 菜单@

* [JSDBanTangHomeDemo](https://github.com/JoySeeDog/JSDBanTangHomeDemo) 真正的仿半塘首页效果，半糖首页核心技术解析。   ---- (Star:364) (Fork:69) (Watch:9)  
* [HACursor](https://github.com/HAHAKea/HACursor) 帮助开发者方便集成导航指示器，用于管理视图页面   ---- (Star:565) (Fork:132) (Watch:29)  
* [ZTPageController](https://github.com/wuzhentao/ZTPageController) 模仿网易新闻和其他新闻样式做的一个菜单栏，栏中有各自的控制器。 不建议用VC做展示，具体可以参考我最近写的   ---- (Star:185) (Fork:36) (Watch:7)  
* [circle-menu](https://github.com/Ramotion/circle-menu) 赞 一个不错的旋转点击菜单，类似于遥控器的上下左右中点击样式   ---- (Star:2,371) (Fork:289) (Watch:74)  
* [KYGooeyMenu](https://github.com/KittenYang/KYGooeyMenu) - KYGooeyMenu 是一个具有 Gooey Effects 带粘性的扇形菜单控件(卫星菜单、path)。   ---- (Star:1,729) (Fork:262) (Watch:46)  
* [DCPathButton](https://github.com/Tangdixi/DCPathButton) - Path，4.0的弹出菜单，呼出或者关闭菜单时，多个小图标会分别按照逆时针和顺时针的方向进行滚动。   ---- (Star:858) (Fork:160) (Watch:35)  
* [类似美团的下拉选项](http://code4app.com/ios/%E7%B1%BB%E4%BC%BC%E7%BE%8E%E5%9B%A2%E7%9A%84%E4%B8%8B%E6%8B%89%E9%80%89%E9%A1%B9/538606d4933bf06e0a8b496e) -  类似于美团、大众点评的下拉菜单选项，code4app代码，评论代码有瑕疵。

#### TabBar@

* [DLSlideView](https://github.com/agdsdl/DLSlideView) DLSlideView对常见的顶部Tab页点击、滑动分页做了封装。 它使用基于ViewController的container特性（而不是scrollview）来管理各个子页面，保留原始的系统消息，没有隐患。 同时内存模型更优于使用scrollview的方式，理论上可以支持无限分页。   ---- (Star:525) (Fork:122) (Watch:23)  
* [](https://github.com/NoCodeNoWife/LLRiseTabBar-iOS) 仿淘宝闲鱼的 TabBar   ---- (Star:476) (Fork:132) (Watch:18)  

#### 小红点@

* [WZLBadge](https://github.com/weng1250/WZLBadge) - 小红点，Badge，支持横竖屏支持iOS5~iOS8允许高度定制化，包括“红点”的背景颜色，文字(字体大小、颜色)，位置等。[说明](http://code.cocoachina.com/detail/316890/%E4%B8%80%E8%A1%8C%E4%BB%A3%E7%A0%81%E5%AE%9E%E7%8E%B0%E5%A4%9A%E9%A3%8E%E6%A0%BC%E7%9A%84%E6%8E%A8%E9%80%81%E5%B0%8F%E7%BA%A2%E7%82%B9/).   ---- (Star:1,421) (Fork:292) (Watch:57)  
* [RKNotificationHub](https://github.com/cwRichardKim/RKNotificationHub) - 快速给 UIView 添加上炫酷的通知图标（Badge、红点、提示）。   ---- (Star:2,788) (Fork:309) (Watch:68)  
* [PPBadgeView](https://github.com/jkpang/PPBadgeView) - iOS自定义Badge组件, 支持UIView、UITabBarItem、UIBarButtonItem ,支持Objective-C/Swift双版本;   ---- (Star:341) (Fork:46) (Watch:5)  

#### page@

* [NinaPagerView](https://github.com/RamWire/NinaPagerView) 一行代码搞定顶部菜单栏。类似网易新闻、今日头条、虎扑看球等app做的一个顶部菜单栏，每栏中有独立的控制器，可自己定制。   ---- (Star:336) (Fork:47) (Watch:10)  
* [PageMenu](https://github.com/uacaps/PageMenu) A paging menu controller built from other view controllers placed inside a scroll view (like Spotify, Windows Phone, Instagram) [⚠️已失去维护]   ---- (Star:4,356) (Fork:694) (Watch:156)  
* [MXSegmentedPager](https://github.com/maxep/MXSegmentedPager) 分页滚动，多个分页的pageController效果   ---- (Star:812) (Fork:159) (Watch:31)  
* [XHTwitterPaggingViewer](https://github.com/xhzengAIB/XHTwitterPaggingViewer) A twitter like navigation bar, page viewer.   ---- (Star:219) (Fork:56) (Watch:14)  

#### 轮播@

* [iCarousel](https://github.com/nicklockwood/iCarousel) 非常赞 作者是英国 Charcoal Design 公司的创始人, 开源领域的贡献颇为卓著, 这个项目就是其中之一, 这是一款可以在 iOS 上实现旋转木马视图切换效果的第三方控件, 并提供多种切换效果。是一个使用简单、高度自定义的多类型视图切换的控件，支持iOS/Mac OS、ARC & Thread Safety; A simple, highly customisable, data-driven 3D carousel for iOS and Mac OS   ---- (Star:9,902) (Fork:2,321) (Watch:452)  
* [SDCycleScrollView](https://github.com/gsdios/SDCycleScrollView) - 无限循环自动图片轮播器(一步设置即可使用)。   ---- (Star:4,358) (Fork:1,177) (Watch:128)  
* [HYBLoopScrollView](https://github.com/CoderJackyHuang/HYBLoopScrollView) 一行代码接入轮播组件，自带图片下载、缓存相关功能，无任何第三方依赖、轻量级组件。   ---- (Star:589) (Fork:142) (Watch:19)  

#### 选择器@

* [ASDayPicker](http://code.cocoachina.com/detail/226543) - 适用于iOS (iPhone)的日期选择器(时间选择器)，类似于Calendar app的周视图。
* [HSDatePickerViewController](https://github.com/EmilYo/HSDatePickerViewController) - 带有Dropbox Mailbox感觉的时间日期选择器(时间选择器)。启动是背景被模糊化。界面也是主流的扁平化风格。   ---- (Star:312) (Fork:59) (Watch:14)  
* [HZQDatePickerView](https://github.com/huzhiqin/HZQDatePickerView) - 自定义时间选择器(日期选择器)，包括开始日期和结束日期两种类型。   ---- (Star:101) (Fork:13) (Watch:3)  
* [CFCityPickerVC](https://github.com/CharlinFeng/CFCityPickerVC) - 城市选取控制器。   ---- (Star:538) (Fork:136) (Watch:25)  
* [JFCitySelector](https://github.com/zhifenx/JFCitySelector) （仿美团）简单好用的城市选择器，三行代码搞定！   ---- (Star:106) (Fork:24) (Watch:1)  

#### 购物车@

* [ShoppingCartExample](https://github.com/gbaldera/ShoppingCartExample) - 购物车最多star demo。   ---- (Star:146) (Fork:61) (Watch:15)  
* [shoppingCart1](https://github.com/yhangeline/shoppingCart) - 仿美团购物车效果。   ---- (Star:13) (Fork:3) (Watch:1)  
* [ZFShoppingCart](https://github.com/WZF-Fei/ZFShoppingCart) - 仿照美团外卖加入购物车的动态效果。   ---- (Star:80) (Fork:37) (Watch:6)  
* [shoppingCart2](https://github.com/spxvszero/ShoppingCart) - 一个购物车demo，包含购物车动画效果、购物车多选、删除、编辑等功能。   ---- (Star:10) (Fork:2) (Watch:2)  
* [shoppingCart-demo](https://github.com/DrYrw/shoppingCart-demo) - 一个简单的购物车功能实现demo。   ---- (Star:1) (Fork:0) (Watch:1)  
* [iOS_oShoppingCart_Demo](https://github.com/ZyZwei/iOS_oShoppingCart_Demo) - 简单实现购物车常见的筛选功能。   ---- (Star:3) (Fork:0) (Watch:1)  
* [XNQShoppingTrolley](https://github.com/342261733/XNQShoppingTrolley) - 购物车功能 基本功能仿照淘宝的购物车。   ---- (Star:15) (Fork:2) (Watch:1)  
* [ShoppingDemo](https://github.com/Zhangjingwang1993/ShoppingDemo) - iOS仿美团外卖饿了吗App点餐动画,购物车。   ---- (Star:20) (Fork:5) (Watch:1)  
* [shopCarDemobyCX](http://code.cocoachina.com/view/129430) - shopCarDemobyCX一个简易购物车效果，最重要的是可以分单结算，分单个商品结算，代理是主要技术。
* [MVVM KVO购物车](http://code.cocoachina.com/view/128713) - MVVM KVO 购物车(一处计算总价钱)。
* [CartDemo](https://github.com/LQQZYY/CartDemo) - CartDemo比较完整的购物车界面及逻辑,商品展示,多选,单选,全选及滑动删除,价格计算。   ---- (Star:185) (Fork:53) (Watch:4)  

#### 引导@

* [Onboard](https://github.com/mamaral/Onboard) 一个iOS框架，轻松创建一个美丽和吸引人的使用引导，只需行代码，非常赞👍👍，同时支持Swift。   ---- (Star:5,820) (Fork:748) (Watch:183)  
* [JMHoledView](https://github.com/leverdeterre/JMHoledView) 一个不错的使用引导库，使用View实现.   ---- (Star:451) (Fork:91) (Watch:16)  
* [TNTutorialManager](https://github.com/Tawa/TNTutorialManager) 内嵌的App使用引导库.   ---- (Star:81) (Fork:6) (Watch:1)  

#### 进度@

* [LiquidFloatingActionButton](https://github.com/yoavlt/LiquidFloatingActionButton) - 卫星弹出菜单。   ---- (Star:3,134) (Fork:393) (Watch:73)  
* [NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView) -  loading 进度条动画，有20-30多种，非常👍👍👍 .   ---- (Star:5,935) (Fork:632) (Watch:161)  
* [DGActivityIndicatorView](https://github.com/gontovnik/DGActivityIndicatorView) DGActivityIndicatorView is a great way to make loading spinners in your application look nicer. It contains 32 different indicator view styles.   ---- (Star:1,565) (Fork:259) (Watch:42)  
* [YLProgressBar](https://github.com/yannickl/YLProgressBar) UIProgressView replacement with an highly and fully customizable animated progress bar in pure Core Graphics   ---- (Star:1,043) (Fork:169) (Watch:28)  
* [NJKWebViewProgress](https://github.com/ninjinkun/NJKWebViewProgress) - 很赞 一个 UIWebView 的进度条接口库,UIWebView 本身是不提供进度条的。   ---- (Star:3,750) (Fork:614) (Watch:101)  
* [UAProgressView](https://github.com/UrbanApps/UAProgressView) 很赞 的一个进度指示View   ---- (Star:973) (Fork:145) (Watch:33)  
* [AwesomeMenu](https://github.com/levey/AwesomeMenu) - 最多人用的Path菜单。   ---- (Star:5,119) (Fork:838) (Watch:211)  
* [ZFProgressView](https://github.com/WZF-Fei/ZFProgressView) A simple digit progress view.（version1.3 使用GCD定时器代替NSTimer,避免内存泄露问题)   ---- (Star:83) (Fork:33) (Watch:3)  
* [WaveLoadingView](https://github.com/liuzhiyi1992/WaveLoadingView) - iOS 唯一完美的波浪进度加载指示器，[实现说明](http://zyden.vicp.cc/waveloadingindicator/)。   ---- (Star:539) (Fork:76) (Watch:17)  
* [JZMultiChoicesCircleButton](https://github.com/JustinFincher/JZMultiChoicesCircleButton) - 三维多选按钮。   ---- (Star:355) (Fork:37) (Watch:14)  
* [ASProgressPopUpView](https://github.com/alskipp/ASProgressPopUpView) - 弹出的进度条显示进度。   ---- (Star:1,123) (Fork:176) (Watch:36)  
* [TwitterPaggingViewer](https://github.com/xhzengAIB/XHTwitterPaggingViewer)  - 多个Tableview，左右滑动。   ---- (Star:219) (Fork:56) (Watch:14)  
* [CircularProgressControl](https://github.com/carantes/CircularProgressControl) - Circular Progress Control using CAShapeLayer ，环形进度控制条。   ---- (Star:335) (Fork:44) (Watch:11)  
* [SDProgressView](https://github.com/gsdios/SDProgressView) - 简便美观的进度指示器，此系列共有六种样式的进度指示器。   ---- (Star:358) (Fork:124) (Watch:18)  
* [LoopProgressDemo](https://github.com/saitjr/STLoopProgressView) - 环形渐变进度条，[环形渐变进度条实现](http://www.superqq.com/blog/2015/08/12/realization-circular-gradient-progress/)。   ---- (Star:118) (Fork:35) (Watch:2)  
* [MDCSwipeToChoose](https://github.com/modocache/MDCSwipeToChoose) - MDCSwipeToChoose可简单地添加滑动手势来调用UIView，并使用该行为提供了一个组件以创建类似Tinder app的like或者dislike界面的轻扫。基于轻扫的方向，你可以决定执行什么样的行为，并且你可以自定义文本颜色和图片。该项目适用于教学用的抽认卡、图片查看器以及其他等。   ---- (Star:2,468) (Fork:464) (Watch:79)  
* [MediumScrollFullScreen](https://github.com/pixyzehn/MediumScrollFullScreen) - Medium的可扩展滚动页面，上下滚动时，全屏显示内容，并自然消隐上下菜单。由此项目感知，作者是一位很注重细节的开发者，他的另外[几个菜单类项目](https://github.com/pixyzehn)也都不错，值得参考，比如：PathMenu, MediumMenu 等。   ---- (Star:543) (Fork:44) (Watch:15)  
* [today extension](http://adad184.com/2014/10/29/2014-10-29-how-to-setup-today-extension-programmatically/) - 用纯代码构建一个Widget(today extension) 。
* [PDTSimpleCalendar](https://github.com/jivesoftware/PDTSimpleCalendar) - 是iOS最棒的日历组件了。你可以在各个方面对它进行定制，无论是运行逻辑还是外观方面。   ---- (Star:1,836) (Fork:344) (Watch:87)  
* [Form](https://github.com/hyperoslo/Form) - JSON 驱动的 Form表单系统，复杂的表单填写类 App 极其需要（比如淘宝呢！）。   ---- (Star:1,587) (Fork:135) (Watch:66)  
* [ImagePickerSheetController](https://github.com/larcus94/ImagePickerSheetController) - 图片或视频选择器（可多选）组件及其示例项目。   ---- (Star:1,356) (Fork:193) (Watch:38)  
* [ImagePickerSheet](https://github.com/larcus94/ImagePickerSheetController) - 图片或视频选择器（可多选）组件及其示例项目。   ---- (Star:1,356) (Fork:193) (Watch:38)  
* [BLEProgressView](https://github.com/blueeee/BLEProgressView)使用pop实现动画的进度条   ---- (Star:149) (Fork:51) (Watch:8)  
* [ZZCircleProgress](https://github.com/zhouxing5311/ZZCircleProgress) draw rect实现的圆形进度条。可以使用部分圆弧当做整个进度条，并可以随意设置起始角度及减少的圆弧角度大小。   ---- (Star:90) (Fork:29) (Watch:1)  
* [BubbleTransition](https://github.com/andreamazz/BubbleTransition) - 以气泡膨胀和缩小的动画效果来显示和移除 controller，Uber的就是这种取消操作的方式。   ---- (Star:2,572) (Fork:193) (Watch:50)  
* [KYFloatingBubble](https://github
  .com/KittenYang/KYFloatingBubble) - 类似iOS7中Game Center浮动气泡的效果。
* [DKNightVersion](https://github.com/Draveness/DKNightVersion) - DKNightVersion 是一个支持夜间模式切换的框架。   ---- (Star:2,831) (Fork:444) (Watch:82)  
* [EasyUIControl](https://github.com/sx1989827/EasyUIControl) - 一个可以简化界面ui的控件框架。   ---- (Star:40) (Fork:14) (Watch:1)  
* [QQBtn](https://github.com/ZhongTaoTian/QQBtn) - 仿QQ未读消息弹性按钮动画，达到和手机QQ未读信息一样的动画效果，效果基本实现。   ---- (Star:284) (Fork:55) (Watch:9)  
* [TZStackView](https://github.com/tomvanzummeren/TZStackView) - OS 9 UIStackView 功能模拟实现于 iOS 7/ iOS 8 内。   ---- (Star:1,137) (Fork:136) (Watch:23)  
* [Ruler](https://github.com/nixzhu/Ruler) - 尺子。   ---- (Star:147) (Fork:17) (Watch:4)  
* [HUMSlider](https://github.com/justhum/HUMSlider) - HUMSlider是一款能够自动显示刻度记号的滑竿，滑动到某处，该处的刻度会自动上升，两边还能配置图像。支持代码或storyboard中实现。   ---- (Star:241) (Fork:35) (Watch:9)  
* [3DTouchDemo](https://github.com/luzefeng/3DTouchDemo) - 详细介绍了每个参数的含义和3Dtouch的入口，保证包学包会。   ---- (Star:42) (Fork:14) (Watch:3)  
* [3DTouchSample](https://github.com/RichardLeung/3DTouchSample) - 3D-Touch的功能分为两个部分：Shortcut和Preview。   ---- (Star:70) (Fork:14) (Watch:3)  
* [SBShortcutMenuSimulator](https://github.com/DeskConnect/SBShortcutMenuSimulator) - 教你如何在模拟器上测试 3D Touch 功能!   ---- (Star:1,783) (Fork:181) (Watch:52)  
* [仿LOL滚动视图](http://code.cocoachina.com/view/128287) - 仿LOL滚动视图。
* [答题选择切换页](http://code.cocoachina.com/view/128281) - 将scrollview和tableview封装在一起，在初始化的时候简单的将数据带上，就可以一页一页的左右来回滑动。
* [SCTrelloNavigation](https://github.com/SergioChan/SCTrelloNavigation) - 类似trello的导航动效控件实现。   ---- (Star:780) (Fork:102) (Watch:21)  
* [RGCategoryView](https://github.com/refinemobi/RGCategoryView) - 仿了个苏宁易购的分类页面。
* [VBFPopFlatButton](https://github.com/victorBaro/VBFPopFlatButton) - 通过几条线段实现的非常Q萌的动画按钮效果。   ---- (Star:2,866) (Fork:304) (Watch:85)  
* [LNPopupController](https://github.com/LeoNatan/LNPopupController) - AppleMusic式pop up，弹出是页面，可以上下拉动。   ---- (Star:1,948) (Fork:227) (Watch:53)  
* [DGRunkeeperSwitch](https://github.com/gontovnik/DGRunkeeperSwitch/) - 动画segment，节选器。   ---- (Star:1,814) (Fork:153) (Watch:39)  
* [DynamicMaskSegmentSwitch](https://github.com/KittenYang/DynamicMaskSegmentSwitch) - 一个简单有趣的 SegmentedControl 节选器。   ---- (Star:291) (Fork:31) (Watch:7)  
* [YXFilmSelectView](https://github.com/yixiangboy/YXFilmSelectView) - 仿造时光网选择电影票的UI而开发的一个自定义View。   ---- (Star:96) (Fork:39) (Watch:3)  
* [FJTagCollectionView](http://code.cocoachina.com/view/129152) - 标签（适配宽度）。
* [DFTimelineView](https://github.com/anyunzhong/DFTimelineView) - DFTimelineView仿微信朋友圈 时间轴。   ---- (Star:390) (Fork:152) (Watch:21)  
* [HYBImageCliped](https://github.com/CoderJackyHuang/HYBImageCliped) - 可给任意继承UIView的控件添加任意多个圆角、可根据颜色生成图片且可带任意个圆角、给UIButton设置不同状态下的图片且可带任意圆角、给UIImageView设置任意图片，支持带圆角或者直接生成圆形。   ---- (Star:477) (Fork:95) (Watch:21)  
* [StackViewController](https://github.com/seedco/StackViewController) - 方便 iOS 开发者使用 UIStackView 构建表单或其它静态内容视图。   ---- (Star:615) (Fork:37) (Watch:23)  
* [LLBootstrapButton](https://github.com/lilei644/LLBootstrapButton) - Bootstrap 3.0扁平化风格按钮，自带图标，一句代码直接调用！   ---- (Star:186) (Fork:27) (Watch:10)  
* [JMRoundedCorner](https://github.com/raozhizhen/JMRoundedCorner) - UIView设置不触发离屏渲染的圆角！   ---- (Star:688) (Fork:110) (Watch:19)  
* [KNCirclePercentView](https://github.com/knn90/KNCirclePercentView) 一个自定义动画的圆形进度View   ---- (Star:77) (Fork:25) (Watch:9)  

#### 其他UI@

* [drawablebubble](https://github.com/KittenYang/KYCuteView)QQ中未读气泡拖拽消失的实现分析[分析文章](http://kittenyang.com/drawablebubble/)   ---- (Star:919) (Fork:199) (Watch:36)  
* [PPNumberButton](https://github.com/jkpang/PPNumberButton)高仿京东淘宝商品数量的加减按钮,可定制程度较高,使用简单!   ---- (Star:482) (Fork:88) (Watch:16)  
* [YJFavorEmitter](https://github.com/SplashZ/YJFavorEmitter) 一个非常好用的点赞粒子发射器   ---- (Star:48) (Fork:12) (Watch:2)  
* [BEMCheckBox](https://github.com/Boris-Em/BEMCheckBox) - BEMCheckBox 是一个用于 iOS 应用上构建漂亮, 高度可定制化动画效果的复选框类库, 最低支持到 iOS 7 系统, 有多种不同风格的动画效果可供选择。   ---- (Star:1,892) (Fork:191) (Watch:42)  
* [BFPaperCheckbox](https://github.com/bfeher/BFPaperCheckbox) iOS Checkboxes inspired by Google's Paper Material Design.   ---- (Star:432) (Fork:47) (Watch:16)  
* [GMenuController](https://github.com/GIKICoder/GMenuController) 具有和UIMenuController一致的UI 与交互行为. menuItem可指定target. 可定制化UI.对外API与原生UIMenuController 一致.   ---- (Star:16) (Fork:4) (Watch:3)  

#### 工具@
#### 综合@
* [sstoolkit](https://github.com/soffes/sstoolkit) 一个不错的工具包，提供各种比如编码、加密、字符串处理等等东西，还提供了一些不错的自定义控件，并且文档非常齐全   ---- (Star:3,393) (Fork:630) (Watch:201)  

#### 提醒用户评分@

* [iRate](https://github.com/nicklockwood/iRate) - 问卷调查。   ---- (Star:4,319) (Fork:748) (Watch:150)  
* [UAAppReviewManager](https://github.com/urbanapps/UAAppReviewManager) 一个轻量级的，易用的App评分提醒库.   ---- (Star:807) (Fork:115) (Watch:25)  
* [appirater](https://github.com/arashpayan/appirater) - 用于提醒用户给你的 APP 打分的工具。   ---- (Star:4,489) (Fork:913) (Watch:197)  

#### 压缩解压@

* [ZipArchive](https://github.com/ZipArchive/ZipArchive) - 适用iOS和OS X的解压库。   ---- (Star:3,134) (Fork:850) (Watch:127)  

#### Category@

* [FlatUIKit](https://github.com/Grouper/FlatUIKit) 针对Foundation的扩展,非常👍 A collection of awesome flat UI components for iOS.   ---- (Star:7,661) (Fork:1,017) (Watch:385)  
* [JKCategories](https://github.com/shaojiankui/JKCategories) 非常棒👍👍👍 的分类集合，包含Foundation,UIKit,CoreData,QuartzCore,CoreLocation,MapKit Etc等等.   ---- (Star:2,553) (Fork:835) (Watch:138)  
* [UIScrollView-InfiniteScroll](https://github.com/pronebird/UIScrollView-InfiniteScroll) 滚动视图无限滚动分类 UIScrollView infinite scroll category   ---- (Star:758) (Fork:102) (Watch:25)  
* [LTNavigationBar](https://github.com/ltebean/LTNavigationBar) 允许改变导航栏appearance dynamically的分类  UINavigationBar Category which allows you to change its appearance dynamically   ---- (Star:4,227) (Fork:688) (Watch:117)  
* [BlocksKit](https://github.com/zwaldowski/BlocksKit)  block框架，为 OC 常用类提供了强大的 Block 语法支持，使得编写 OC 代码变得舒适、快速、优雅。 The Objective-C block utilities you always wish you had.   ---- (Star:6,396) (Fork:1,051) (Watch:272)  
* [YYCategories](https://github.com/ibireme/YYCategories) - 功能丰富的 Category 类型工具库。   ---- (Star:604) (Fork:131) (Watch:19)  
* [BFKit](https://github.com/FabrizioBrancati/BFKit) 一个非常不错的分类集合工具库，大幅提高开发效率.同时包含Swift版本   ---- (Star:757) (Fork:125) (Watch:49)  
* [NullSafe](https://github.com/nicklockwood/NullSafe) NullSafe is a simple category on NSNull that returns nil for any unrecognised messages instead of throwing an exception pod 'NullSafe', '~> 1.2.2' 用于防止项目中数组为空时越界访问崩溃。   ---- (Star:1,068) (Fork:239) (Watch:39)  
* [iOS-Categories](https://github.com/shaojiankui/IOS-Categories) - 收集了许多有助于开发的iOS扩展,各种category分类。   ---- (Star:2,553) (Fork:835) (Watch:138)  
* [cocoacats](http://cocoacats.com/) - 【分类汇总】里面收集了 iOS 中常用的分类文件，一直在更新。
* [libextobjc](https://github.com/jspahrsummers/libextobjc Libextobjc是一个非常强大的Objective-C库的扩展,为Objective-C提供诸如Safe categories、Concrete protocols、简单和安全的key paths以及简单使用block中的弱变量等功能。libextobjc非常模块化，只需要一个或者两个依赖就能使用大部分类和模块。
* [SFJumpToLine](https://github.com/sferrini/SFJumpToLine) Xcode plugin that moves the instruction pointer to the selected line   ---- (Star:10) (Fork:0) (Watch:2)  
* [DTFoundation](https://github.com/Cocoanetics/DTFoundation) 标准工具类和分类 - Standard toolset classes and categories   ---- (Star:746) (Fork:207) (Watch:44)  

#### Color@

* [Chameleon](https://github.com/ViccAlexander/Chameleon) - Chameleon是一个非常棒👍👍👍iOS的色彩框架。它运用现代化flat color将UIColor扩展地非常美观。我们还可以通过它运用自定义颜色创建调色板。它还有很多功用，请浏览readme。同时支持Swift.   ---- (Star:10,139) (Fork:973) (Watch:309)  

#### Github相关@

* [http://shields.io/](http://shields.io/) - 开源项目的徽章
* [Classroom for GitHub](https://github.com/education/classroom) - Classroom for GitHub 可以自动创建代码仓库和访问控制，可以让老师很方便的在 GitHub 上发布代码任务和收集作业。   ---- (Star:683) (Fork:189) (Watch:59)  
* [Hexo](https://github.com/hexojs/hexo) - 通过Github Pages写博客的Node.js框架   ---- (Star:18,869) (Fork:2,776) (Watch:752)  
* [octicons](https://github.com/github/octicons) - GitHub的 图标字体   ---- (Star:4,093) (Fork:317) (Watch:157)  
* [markdown-editor](https://github.com/jbt/markdown-editor) - GitHub味道的markdown编辑器   ---- (Star:2,035) (Fork:484) (Watch:89)  
* [backup-utils](https://github.com/github/backup-utils) - backup-utils 是 Github 企业备份工具，它包括一些备份和恢复工具。这些备份工具实现了多项用于备份主机的高级功能，还原功能也已经包括在 GitHub Enterprise 中。   ---- (Star:404) (Fork:166) (Watch:121)  
* [gistblog](https://github.com/jazzychad/gistblog) -gistblog 是一个简单的 Node.js 应用，使用 Github 的认证系统和 gist 提供的后台存储来实现博客的功能。可使用 Markdown 编写博客。   ---- (Star:300) (Fork:14) (Watch:12)  
* [openspace](https://github.com/EverythingMe/openspace) -Openspace 是一个用来将你在 Github 上的项目汇总显示在一个网页里的应用。   ---- (Star:73) (Fork:12) (Watch:14)  
* [primer](https://github.com/primer/primer) -Primer 是 Github 工具包，用于 Github 前端设计。   ---- (Star:6,231) (Fork:452) (Watch:186)  
* [https://gitter.im](https://gitter.im) - 专门给GitHub开源项目或者开源作者提供的聊天软件
* [boennemann - badges](https://github.com/boennemann/badges) - 各种徽章   ---- (Star:668) (Fork:406) (Watch:23)  
* [GitTorrent](https://github.com/cjb/GitTorrent)   ---- (Star:3,750) (Fork:212) (Watch:237)  

#### 键盘@

* [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager) - 处理键盘事件强大的库，有OC和Swift版本，纯代码、Storyboard和Xib都适用。   ---- (Star:10,209) (Fork:1,722) (Watch:320)  

#### 文本@
#### 文本输入@

* [GrowingTextView](https://github.com/HansPinckaers/GrowingTextView)  一个非常棒的UITextView库   ---- (Star:2,034) (Fork:472) (Watch:95)  
* [JVFloatLabeledTextField](https://github.com/jverdi/JVFloatLabeledTextField)作者是 Thumb Labs 的联合创始人, JVFloatLabeledTextField 是 UITextField 的子类, 主要实现输入框标签浮动效果, 创作灵感来自 Dribbble, 已出现多个移植版本 UITextField subclass with floating labels - inspired by Matt D. Smith's design: http://dribbble.com/shots/1254439--GIF-Mobile-Form-Interaction?list=users   ---- (Star:6,493) (Fork:664) (Watch:195)  
* [GBigbang](https://github.com/GIKICoder/GBigbang) 一个分词功能组件/大爆炸/tagFlowView   ---- (Star:22) (Fork:6) (Watch:1)  

#### 富文本@   [返回目录](#目录)

* [YYText](https://github.com/ibireme/YYText) - 功能强大的 iOS 富文本框架。   ---- (Star:6,754) (Fork:1,129) (Watch:202)  
* [Shimmer](https://github.com/facebook/Shimmer) - BlingBling闪光效果，酷炫的Label的效果，可以用于加载等待提示。   ---- (Star:8,177) (Fork:1,017) (Watch:370)  
* [GRichLabel ](https://github.com/GIKICoder/GRichLabel) - 支持选择复制.支持自定义选择弹出menu的富文本Label.内部使用YYAsyncLayer提供异步绘制任务.   ---- (Star:64) (Fork:6) (Watch:4)  
* [TFHpple ](https://github.com/topfunky/hpple) - TFHpple解析html的轻量级框架   ---- (Star:2,432) (Fork:443) (Watch:104)  
* [RTLabel](https://github.com/honcheng/RTLabel) - RTLabel 基于UILabel类的拓展,能够支持Html标记的富文本显示，它是基于Core Text,因此也支持Core Text上的一些东西。32位，很久没有更新了。   ---- (Star:1,388) (Fork:407) (Watch:78)  
* [RTLabel](https://github.com/bingxue314159/RTLabel) - 富文本，RTLabel支持64位。   ---- (Star:39) (Fork:407) (Watch:3)  
* [TYAttributedLabel](https://github.com/12207480/TYAttributedLabel) -  TYAttributedLabel。 简单易用的属性文本控件(无需了解CoreText)，支持富文本，图文混排显示，支持添加链接，image和UIView控件，支持自定义排版显示。   ---- (Star:2,180) (Fork:501) (Watch:74)  
* [TTTAttributedLabel](https://github.com/TTTAttributedLabel/TTTAttributedLabel) - 一个文字视图开源组件，是UILabel的替代元件，可以以简单的方式展现渲染的属性字符串。另外，还支持链接植入，不管是手动还是使用UIDataDetectorTypes自动把电话号码、事件、地址以及其他信息变成链接。[用TTTAttributedLabel创建变化丰富的UILabel](http://blog.csdn.net/prevention/article/details/9998575) - 网易新闻iOS版使用。   ---- (Star:7,808) (Fork:1,510) (Watch:240)  
* [MLEmojiLabel](https://github.com/molon/MLEmojiLabel) - 自动识别网址、号码、邮箱、@、#话题#和表情的label。可以自定义自己的表情识别正则，和对应的表情图像。(默认是识别微信的表情符号)，继承自TTTAttributedLabel，所以可以像label一样使用。label的特性全都有，使用起来更友好更方便。   ---- (Star:750) (Fork:173) (Watch:26)  
* [FXLabel](https://github.com/nicklockwood/FXLabel) - FXLabel是一个功能强大使用简单的类库，通过提供一个子类改进了标准的UILabel组件，为字体增加了阴影、内阴影和渐变色等，可以被用在任何标准的UILabel中。FXLabel还提供了更多控件，可以对字体行距、字体间距等进行调整。   ---- (Star:828) (Fork:133) (Watch:47)  
* [WFReader](https://github.com/TigerWf/WFReader) - 一款简单的coretext阅读器，支持文本选择、高亮以及字体大小选择等。   ---- (Star:123) (Fork:46) (Watch:7)  
* [WPAttributedMarkup](https://github.com/nigelgrange/WPAttributedMarkup) - WPAttributedMarkup is a simple utility category that can be used to easily create an attributed string from text with markup tags and a style dictionary。   ---- (Star:180) (Fork:47) (Watch:9)  
* [UUColorSwitch](https://github.com/zhangyu9050/UUColorSwitch) - Switch 开关动画效果,当打开开关时，Switch可实现平滑渲染过渡到父视图的效果。   ---- (Star:17) (Fork:1) (Watch:2)  
* [UITextViewDIYEmojiExample](https://github.com/zekunyan/UITextViewDIYEmojiExample) - [UITextView编辑时插入自定义表情-简单的图文混编](http://tutuge.me/2015/03/07/UITextView%E7%BC%96%E8%BE%91%E6%97%B6%E6%8F%92%E5%85%A5%E8%87%AA%E5%AE%9A%E4%B9%89%E8%A1%A8%E6%83%85-%E7%AE%80%E5%8D%95%E7%9A%84%E5%9B%BE%E6%96%87%E6%B7%B7%E7%BC%96/)。   ---- (Star:135) (Fork:38) (Watch:7)  
* [ZSSRichTextEditor](https://github.com/nnhubbard/ZSSRichTextEditor) - 适用于iOS的富文本WYSIWYG编辑器，支持语法高亮和源码查看。ZSSRichTextEditor包含所有WYSIWYG标准的编辑器工具。   ---- (Star:2,615) (Fork:386) (Watch:89)  
* [DTCoreText](https://github.com/Cocoanetics/DTCoreText) - 可以解析HTML与CSS最终用CoreText绘制出来，通常用于在一些需要显示富文本的场景下代替低性能的UIWebView。[DTCoreText源码解析](http://blog.cnbang.net/tech/2630/)。   ---- (Star:5,150) (Fork:1,032) (Watch:201)  
* [CSGrowingTextView](https://github.com/cloverstudio/CSGrowingTextView) - 用作即时通讯文本框和评论文本框使用，可以显示多行输入。   ---- (Star:151) (Fork:40) (Watch:4)  
* [MarkdownTextView](https://github.com/indragiek/MarkdownTextView) - 显示Markdown的TextView。   ---- (Star:544) (Fork:54) (Watch:14)  
* [高仿微信限定行数文字内容](http://d.cocoachina.com/code/detail/300299) - 采用Autolayout高仿微信纯文字限定行数。
* [FuriganaTextView](https://github.com/lingochamp/FuriganaTextView) - 实现复杂的日文韩文排版。   ---- (Star:87) (Fork:8) (Watch:14)  
* [ParkedTextField](https://github.com/gmertk/ParkedTextField) - 带固定文本的输入组件。   ---- (Star:787) (Fork:48) (Watch:19)  
* [GJCFCoreText](https://github.com/zyprosoft/GJCFCoreText) - 图文混排。   ---- (Star:13) (Fork:5) (Watch:2)  
* [AttributedLabel](https://github.com/KyoheiG3/AttributedLabel) - 显示性能数量级 UILabel 的 AttributedLabel。无畏无惧、挑战权威。   ---- (Star:355) (Fork:31) (Watch:11)  
* [FFLabel](https://github.com/liufan321/FFLabel) - 自动检测 URLs, @username, #topic# 等关链词（提供响应扩展）。实用的标签文本小组件。   ---- (Star:341) (Fork:77) (Watch:16)  
* [TextFieldEffects](https://github.com/raulriera/TextFieldEffects) - 标准的UITextField有些枯燥么？来认识一下TextFieldEffects吧！废话不多说，只要看几个例子,是啊，都是些简单的dropin控制器。甚至可以在storyboard中使用IBDesignables。   ---- (Star:4,242) (Fork:452) (Watch:126)  
* [AutocompleteField](https://github.com/filipstefansson/AutocompleteField) - 可应用于 iOS 应用中文字输入框自动补全的场景, 兼容到 iOS 8。   ---- (Star:652) (Fork:40) (Watch:16)  
* [WordPress-Editor-iOS](https://github.com/wordpress-mobile/WordPress-Editor-iOS) - 一个文本编辑器 简书和新浪博客都在用。   ---- (Star:861) (Fork:183) (Watch:46)  
* [placeholder_TextView](http://code.cocoachina.com/view/129099) - 带有placeholder的TextView：带有提示信息的textview，使用懒加载的思想，支持扩展、自定义，类似许多APP内部的意见反馈页面 。
* [M80AttributedLabel](https://github.com/xiangwangfeng/M80AttributedLabel) - M80AttributedLabel实现文字与表情的混排。一般使用气泡作为背景。   ---- (Star:555) (Fork:153) (Watch:30)  


#### 字体@

* [FontAwesomeKit](https://github.com/PrideChung/FontAwesomeKit) 图片字体库，支持超级字体、基础Icon等，支持同时支持Swift.   ---- (Star:2,541) (Fork:311) (Watch:87)  

#### 多线程@

* [JX_GCDTimer](https://github.com/Joeyqiushi/JX_GCDTimer) 定时器，NSTimer和GCD哪个更好   ---- (Star:120) (Fork:21) (Watch:6)  
* [BLStopwatch](https://github.com/beiliao-mobile/BLStopwatch) 代码耗时打点计时器   ---- (Star:22) (Fork:2) (Watch:0)  
* [Thread](https://github.com/mrhyh/Thread) 多线程Demo集合   ---- (Star:1) (Fork:1) (Watch:1)  

#### 日历@

* [FSCalendar](https://github.com/WenchaoD/FSCalendar) 一款漂亮，强大的 iOS 日历组件 A fully customizable iOS calendar library, compatible with Objective-C and Swift   ---- (Star:5,348) (Fork:936) (Watch:171)  
* [MSSCalendar](https://github.com/MSS0306/MSSCalendar) A simple iOS Calendar 高性能日历控件（类似去哪网）   ---- (Star:244) (Fork:60) (Watch:10)  
* [Calendar](https://github.com/jumartin/Calendar) - 日历、行程安排类的View和控制器。A set of views and controllers for displaying and scheduling events on iOS   ---- (Star:518) (Fork:136) (Watch:51)  
* [HYYCalendar](https://github.com/kRadius/HYYCalendar) 一个简单易用的日期的选择的控件，支持日历选择和Picker选择两种方式。支持iOS 6+   ---- (Star:94) (Fork:13) (Watch:1)  
* [JTCalendar](https://github.com/jonathantribouharet/JTCalendar) - iOS下优美的 Calendar 组件，做 GTD 类 App 必备。   ---- (Star:2,422) (Fork:484) (Watch:95)  
* [MSCollectionViewCalendarLayout](https://github.com/erichoracek/MSCollectionViewCalendarLayout) 日历 UICollectionViewLayout for displaying cells chronologically. Similar to the iOS Calendar app.   ---- (Star:1,870) (Fork:288) (Watch:104)  

#### 游戏@

* [cocos2d-objc](https://github.com/cocos2d/cocos2d-objc) Cocos2d for iOS and OS X, built using Objective-C   ---- (Star:4,111) (Fork:1,244) (Watch:306)  

#### 侧滑与右滑返回手势@

* [ViewDeck](https://github.com/ViewDeck/ViewDeck) 项目需要用到左侧右侧各有一个抽屉视图，而这个类库可以极其简单的实现这个功能，不单单是左右各一个，它可以随意设置上下左右的抽屉视图，简直是360度想怎么抽怎么抽   ---- (Star:5,201) (Fork:1,007) (Watch:244)  
* [FDFullscreenPopGesture](https://github.com/forkingdog/FDFullscreenPopGesture) 非常棒的全屏手势侧滑，只需导入此库，就可以让你的App具备左滑返回功能，不用写一句代码。   ---- (Star:4,436) (Fork:934) (Watch:154)  
* [SloppySwiper](https://github.com/fastred/SloppySwiper) - iOS系统自带的UINavigationController要7.0才支持，但不过该手势只能从屏幕左侧边缘识别，如果要扩大到整个屏幕范围怎么办？配合一个SloppySwiper无需代码就可以轻松实现。此库支持iOS5.0以上版本（另外：Nav的title滑动不明显，本人写了2个类似的控件），[SloppySwiper-demo](https://github.com/Tim9Liu9/SloppySwiper-Example) ：代码方式与storyboard方式。   ---- (Star:721) (Fork:93) (Watch:31)  
* [SCNavigation](https://github.com/singro/SCNavigation) - UINavigation可以右滑返回，隐藏UINavigationBar。   ---- (Star:117) (Fork:28) (Watch:4)  
* [UINavigationController-YRBackGesture](https://github.com/YueRuo/UINavigationController-YRBackGesture) - 支持右滑返回手势，标题栏不动。   ---- (Star:49) (Fork:18) (Watch:6)  
* [GHSidebarNav](https://github.com/gresrun/GHSidebarNav) - 现在比较流行使用侧开(侧滑)菜单设计。试了不少控件，感觉GHSidebarNav最成熟，尤其对纯代码创建的界面兼容性最好。[在Storyboard中使用GHSidebarNav侧开菜单控件](http://www.cnblogs.com/zyl910/archive/2013/06/14/ios_storyboard_sidemenu.html)。   ---- (Star:633) (Fork:149) (Watch:86)  
* [iOS-Slide-Menu](https://github.com/aryaxt/iOS-Slide-Menu) - 能够类似Facebook和Path那样弹出左右边栏侧滑菜单,还支持手势。多种可以自定义的属性 (非常不错)。   ---- (Star:1,541) (Fork:381) (Watch:74)  
* [ECSlidingViewController](https://github.com/ECSlidingViewController/ECSlidingViewController) - 侧滑菜单。   ---- (Star:4,450) (Fork:902) (Watch:171)  
* [JASidePanels](https://github.com/gotosleep/JASidePanels) - 侧滑菜单,有左右菜单，有pop功能，支持手势侧滑,本人使用中：简单。   ---- (Star:3,147) (Fork:647) (Watch:201)  
* [animated-tab-bar](https://github.com/Ramotion/animated-tab-bar) - 让 Tabbar items能显示萌萌的动画。   ---- (Star:8,164) (Fork:1,068) (Watch:295)  
* [tabbar图标动画](http://code.cocoachina.com/detail/284346) - tabbar上图标的动画实现，[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。
* [JHMenuTableViewDemo](https://github.com/Jiahai/JHMenuTableViewDemo) - 仿网易邮箱列表侧滑菜单。   ---- (Star:36) (Fork:9) (Watch:3)  
* [SlideMenuView](https://github.com/xudafeng/SlideMenuView) - 炫酷侧滑菜单布局框架，[Android版本的一致实现](Android 版本的一致实现请见：https://github.com/xudafeng/SlidingMenu)。   ---- (Star:47) (Fork:13) (Watch:2)  
* [KGFloatingDrawer](https://github.com/KyleGoddard/KGFloatingDrawer) - 侧滑菜单，qq类似，KyleGoddard/KGFloatingDrawer：一款适合于大屏手机或平板的浮动抽屉式导航界面组件。效果很赞- 侧开菜单，qq类似（与RESideMenu类似）。   ---- (Star:478) (Fork:77) (Watch:22)  
* [AIFlatSwitch](https://github.com/cocoatoucher/AIFlatSwitch) - 一款带平滑过渡动画的 Switch 组件类，类相同风格的 Menu/Back[HamburgerButton](https://github.com/fastred/HamburgerButton),类似相同风格的 Menu/Close[hamburger-button](https://github.com/robb/hamburger-button).   ---- (Star:635) (Fork:41) (Watch:18)  
* [WXGSlideMenuDemo](https://github.com/WXGBridgeQ/WXGSlideMenuDemo) - 个简单实现侧拉（侧滑）菜单的小demo，供初学者共同学习、练习使用。   ---- (Star:94) (Fork:23) (Watch:3)  
* [PKRevealController](https://github.com/pkluz/PKRevealController) - PKRevealController是一个可以滑动的侧边栏菜单（可向左、向右或者同时向两侧），只需手指轻轻一点（或者按一下按钮，但是这样滑动时不够炫酷），这类控制的其他库，而PKRevealController是最棒的。安装简便，高度定制且对手势识别良好。可以当做一个标准控件用在iOS SDK中。   ---- (Star:3,957) (Fork:728) (Watch:196)  
* [FlipBoardNavigationController](https://github.com/michaelhenry/FlipBoardNavigationController) - FlipBoardNavigationController。   ---- (Star:876) (Fork:183) (Watch:59)  
* [MMDrawerController](https://github.com/mutualmobile/MMDrawerController) - 最多人用的一个有关侧边“抽屉”导航框架，里面还有很多你意想不到的交互效果，侧滑。   ---- (Star:6,436) (Fork:1,431) (Watch:320)  
* [UIWebView翻页返回效果](http://code.cocoachina.com/detail/316925/UIWebView%E7%BF%BB%E9%A1%B5%E8%BF%94%E5%9B%9E%E6%95%88%E6%9E%9C%EF%BC%88%E5%8F%98%E9%80%9A%E6%96%B9%E6%B3%95%EF%BC%89/) - UIWebView翻页返回效果（变通方法）。
* [LLSlideMenu](https://github.com/lilei644/LLSlideMenu) - 一个弹性侧滑菜单,弹性动画原理借鉴该项目中阻尼函数实现。   ---- (Star:548) (Fork:93) (Watch:11)  
* [ScreenShotBack](https://github.com/zhengwenming/ScreenShotBack) 全屏返回，截图手势返回，景深效果，类似斗鱼、天天快报、腾讯新闻等APP的手势返回。   ---- (Star:348) (Fork:80) (Watch:10)  
* [MLTransition](https://github.com/molon/MLTransition) iOS7+, pop ViewController with pan gesture from middle or edge of screen.   ---- (Star:435) (Fork:82) (Watch:26)  

#### ipad@

* [UISplitViewControllerDemo](https://github.com/NatashaTheRobot/UISplitViewControllerDemo) iOS8 UISplitViewController Demo   ---- (Star:74) (Fork:28) (Watch:7)  

#### 通讯@

* [peertalk](https://github.com/rsms/peertalk) peertalk 是一个支持 iOS 与 Mac 通过 USB 相互通讯的开源库。 Duet Display 基于此实现了将 Mac 界面呈现到 iOS 设备上。   ---- (Star:2,060) (Fork:290) (Watch:102)  

#### 通讯录@

* [快速查找联系人](http://code.cocoachina.com/view/128245) - 类似微信联系人搜索的界面,快速查找联系人,并支持点击查询结果 。
* [PPGetAddressBook](https://github.com/jkpang/PPGetAddressBook) -  对联系人姓名第二个字做排序处理,对AddressBook框架(iOS9之前)和Contacts框架(iOS9之后)做了对应的封装处理,一句代码搞定联系人的获取与排序。   ---- (Star:303) (Fork:67) (Watch:7)  

#### 三方分享、支付、登录等等@

* [openshare](https://github.com/100apps/openshare) - 不用官方SDK，利用社交软件移动客户端(微信/QQ/微博/人人/支付宝)分享/登录/支付。   ---- (Star:3,074) (Fork:637) (Watch:136)  
* [RongCloud-SDK-description](https://github.com/zhengwenming/RongCloud-SDK-description) 介绍融云SDK即时通讯机制和集成步骤，由于国内CSDN博客封杀带有广告性质的文章（其实不是打广告，纯粹的技术分享），所以只能在Github发表了。希望大家支持我，谢谢。Demo地址：https://github.com/zhengwenming/RCIM   ---- (Star:165) (Fork:39) (Watch:15)  
* [RCIM](https://github.com/zhengwenming/RCIM) 融云SDK集成即时通讯。单聊，群聊，讨论组，自定义cell,自定义消息等。文章配合代码一起看，效果更佳！文章地址：https://github.com/zhengwenming/RongCloud-SDK-description   ---- (Star:212) (Fork:84) (Watch:16)  


#### 其他库@

* [iOS源代码](http://opensource.apple.com/source/CF/) - iOS源代码。
* [Slidden](https://github.com/Brimizer/Slidden) - 一个老外开源的开发自定义键盘的库，利用这个开源库，可以方便的配置键位、颜色以及键位对应的图片。   ---- (Star:535) (Fork:87) (Watch:40)  
* [TPKeyboardAvoiding](https://github.com/michaeltyson/TPKeyboardAvoiding) - 用户键盘弹出自动计算高度，进行屏幕滚动操作。   ---- (Star:5,389) (Fork:926) (Watch:181)  
* [CDPMonitorKeyboard](http://d.cocoachina.com/code/detail/298267) - CDPMonitorKeyboard封装,可以解决输入视图(例如textField,textView等)被键盘覆盖问题，并可设置高于键盘多少。
* [自动监听键盘高度](http://code.cocoachina.com/detail/297973/%E8%87%AA%E5%8A%A8%E7%9B%91%E5%90%AC%E9%94%AE%E7%9B%98%E9%AB%98%E5%BA%A6/) - 自动监听键盘高度，初始界面，输入框在屏幕最下方，当键盘出现时，输入框随即移动到键盘上方。
* [ZYKeyboardUtil](https://github.com/liuzhiyi1992/ZYKeyboardUtil) - 全自动处理键盘遮挡事件，只需要一个Block，全自动处理任何多层嵌套复杂界面 因键盘升降 造成的输入控件遮挡问题。   ---- (Star:423) (Fork:94) (Watch:15)  
第三方键盘分次弹出问题 ,[说明](http://ios.jobbole.com/85135/)。
* [KeyboardToolBar](https://github.com/Jiar/KeyboardToolBar/) - 从此不再担心键盘遮住输入框，[文档](http://www.jianshu.com/p/48993ff982c1)。   ---- (Star:83) (Fork:14) (Watch:4)  
* [Review Monitor](https://launchkit.io/reviews/) -  第一时间自动推送 Apple Store 的用户评论到你的邮件箱或者 Slack，第一时间跟进用户反馈，打造优秀 App 必备工具！类似的有：App annie 的类似功能。
* [WBWebViewConsole](https://github.com/Naituw/WBWebViewConsole) - 类似微博iPhone客户端的 “调试选项” 吗？把其中的 “内置浏览器网页调试” 开源在 Github 上了。   ---- (Star:1,101) (Fork:99) (Watch:39)  
* [ios-good-practices](https://github.com/futurice/ios-good-practices) - ios-good-practices iOS 开发最佳实践。   ---- (Star:6,728) (Fork:817) (Watch:635)  
* [iOS开发最佳实践](http://ios.jobbole.com/81830/) - iOS 开发最佳实践 -- 中文。
* [TodayExtensionSharingDefaults](http://code.cocoachina.com/detail/232160) - TodayExtensionSharingDefaults是一个iOS 8 Today扩展示例，可以使用NSUserDefaults与其containing app分享数据。
* [Password-keyboard](https://github.com/liuchunlao/Password-keyboard) - 随机变换数字位置的密码键盘。 模仿银行类应用在付款时输入的随机密码键盘。   ---- (Star:97) (Fork:32) (Watch:1)  
* [SemverKit](https://github.com/nomothetis/SemverKit) - 针对符合『语义化版本规范 2.0.0』版本号的解析、比较运算类库。不仅支持 Major, Minor, Patch，还支持 Alpha 和 Beta 预发布版本，以及相应地递增运算扩展。   ---- (Star:131) (Fork:7) (Watch:3)  
* [Tesseract-OCR-iOS](https://github.com/gali8/Tesseract-OCR-iOS) - 有关OCR文字识别项目。   ---- (Star:3,156) (Fork:724) (Watch:184)  
* [Screenotate](https://github.com/osnr/Screenotate) - 支持 OCR 文字识别的载屏笔记 Mac 完整应用。   ---- (Star:227) (Fork:11) (Watch:12)  
* [Olla4iOS](https://github.com/nonstriater/Olla4iOS) - 过去积累的一些方便复用的类和方法，还在整理中。   ---- (Star:194) (Fork:21) (Watch:9)  
* [DKNightVersion](https://github.com/Draveness/DKNightVersion) - 用最快的方式给你的应用加上夜间和白天的切换效果。   ---- (Star:2,831) (Fork:444) (Watch:82)  
* [TouchVisualizer](https://github.com/morizotter/TouchVisualizer) - 实用的多点触摸可视化组件。扩展并作用于 UIWindows，结构上提供了简单地针对触摸显示定制，比如触摸点的颜色。   ---- (Star:548) (Fork:38) (Watch:19)  
* [RegexKitLite](https://github.com/wezm/RegexKitLite) - 用来处理正则表达式。   ---- (Star:574) (Fork:132) (Watch:14)  
* [XcodeServerSDK](https://github.com/czechboy0/XcodeServerSDK) - 非官方 Xcode Server SDK 封装库。 P.S. 该 SDK 分离自之前推荐的由该作者开发的自动测试框架 [Buildasaur](https://github.com/czechboy0/Buildasaur)。   ---- (Star:370) (Fork:35) (Watch:20)  
* [Seam](https://github.com/nofelmahmood/Seam) - 基于 CloudKit 服务器实现多终端数据同步。   ---- (Star:551) (Fork:51) (Watch:33)  
* [IDNFeedParser](https://github.com/photondragon/IDNFeedParser) - 一个简单易用的Rss解析库。   ---- (Star:26) (Fork:6) (Watch:1)  
* [CoreUmeng](https://github.com/CharlinFeng/CoreUmeng) - 简单：友盟分享封装。   ---- (Star:104) (Fork:49) (Watch:10)  
* [Mirror](https://github.com/kostiakoval/Mirror) - 通过反射（Refection）实现镜像对象封装库。从而可以更轻松获取（或输出）对象属性名、类型及值变量。   ---- (Star:454) (Fork:25) (Watch:13)  
* [Proposer](https://github.com/nixzhu/Proposer) - Proposer 用单个 API 处理 iOS 上的权限请求，以便使用前确认可访问“相册”、“相机”、“麦克风”、“通讯录”或“用户位置”。   ---- (Star:744) (Fork:42) (Watch:10)  
* [PermissionScope](https://github.com/nickoneill/PermissionScope) - 用这个库可以在询问用户前，就告知用户所需的系统权限，为用户带来更好的体验。接受度更高—>更多活跃用户->更高的留存率->数据更好->下载率更高。   ---- (Star:4,574) (Fork:444) (Watch:91)  
* [LocationManager](https://github.com/intuit/LocationManager) - 地理位置管理封装库， CoreLocation使用起来还是比较麻烦的，需要授权，判断系统版本等等，所以推荐使用第三方框架LocationManager，使用Block，十分简单！[iOS-CoreLocation：无论你在哪里，我都要找到你！](http://www.cocoachina.com/ios/20150721/12611.html) 。   ---- (Star:2,148) (Fork:317) (Watch:78)  
* [pangu.objective-c](https://github.com/Cee/pangu.objective-c) - 有多种语言实现版本～ Pangu.Objective-C：格式化中英文之间的空格（OC）。   ---- (Star:106) (Fork:9) (Watch:2)  
* [objection](https://github.com/atomicobject/objection) - 一个轻量级的依赖注入框架Objection。   ---- (Star:1,539) (Fork:186) (Watch:92)  
* [ControlOrientation](https://github.com/johnlui/Swift-On-iOS/tree/master/ControlOrientation/ControlOrientation) - 如何用代码控制以不同屏幕方向打开新页面【iOS】， [使用说明](https://lvwenhan.com/ios/458.html)。   ---- (Star:342) (Fork:181) (Watch:33)  
* [GameCenterManager](https://github.com/nihalahmed/GameCenterManager) - 在iOS上管理GameCenter vanilla并不算难，但是有了这个库会更简单也更快。好上加好不是更好么。   ---- (Star:700) (Fork:136) (Watch:54)  
* [SlackTextViewController](https://github.com/slackhq/SlackTextViewController) - 用作极佳、定制的文本输入控制时，自适应文本区域，手势识别、自动填充、多媒体合并，快速drop-in解决方案。   ---- (Star:8,040) (Fork:1,017) (Watch:249)  
* [IAPHelper](https://github.com/saturngod/IAPHelper) - 应用内付费给我们提供了很多样本代码，而这个库丢掉了那些代码，将金钱交易相关的大多通用任务做了简单的封装。   ---- (Star:1,096) (Fork:218) (Watch:57)  
* [IAPDemo](https://github.com/WildDylan/IAPDemo) - 应用内支付IAP全部流程, [教程](http://www.jianshu.com/p/e9ae4cece800)。   ---- (Star:69) (Fork:11) (Watch:2)  
* [TAPromotee](https://github.com/JanC/TAPromotee) - 交叉推广应用是你可以免费实现的最佳市场推广策略之一。使用这个库做起来非常简单，不用都不可能——将TAPromotee加入你的podfile中，免费配置与享受更多下载吧。   ---- (Star:565) (Fork:76) (Watch:16)  
* [DownloadFontOnline](https://github.com/cgwangding/DownloadFontOnline) - 实现了在线下载一些字体的功能，不用在工程中导入字体库，下载的字体也不会保存在你的应用中，所以可以放心使用。修复了一下崩溃的bug。   ---- (Star:31) (Fork:7) (Watch:1)  
* [STClock](https://github.com/zhenlintie/STClock) - 仿锤子时钟。   ---- (Star:164) (Fork:43) (Watch:9)  
* [GitUp](https://github.com/git-up/GitUp) - GitUp是一个可视化的Git客户端，能够实时的进行编辑、合并、回滚等多种操作，更多功能，请下载体验。   ---- (Star:6,942) (Fork:405) (Watch:153)  
* [获取联系人信息，通讯录](http://code.cocoachina.com/detail/320392/) - 获取联系人信息，通讯录。
* [Universal-Jump-ViewController](https://github.com/HHuiHao/Universal-Jump-ViewController) - 根据规则跳转到指定的界面(runtime实用篇一)。   ---- (Star:287) (Fork:91) (Watch:10)  
* [打开自带地图、百度地图、腾讯地图](http://code.cocoachina.com/view/128249) - 打开自带地图、百度地图、腾讯地图。
* [DateTools](https://github.com/MatthewYork/DateTools) - 用于提高Objective-C中日期和时间相关操作的效率。灵感来源于 DateTime和Time Period Library。   ---- (Star:5,809) (Fork:709) (Watch:157)  
* [DDSlackFeedback](https://github.com/deepdevelop/DDSlackFeedback) - 用这个接口实现的摇一摇上传文字或者截屏反馈到你的 Slack channel，特别适合测试 app 的时候用，集成也很简单。   ---- (Star:42) (Fork:2) (Watch:4)  
* [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - 是一个非常容易使用的蓝牙库, 适用于 iOS 和 Mac OS, 基于原生 CoreBluetooth 框架封装, 可以帮开发者们更简单地使用 CoreBluetooth API, 使用链式方法体, 使得代码更简洁、优雅。[iOS蓝牙开发（四）：BabyBluetooth蓝牙库介绍](http://www.cocoachina.com/ios/20160219/15301.html)   ---- (Star:3,193) (Fork:759) (Watch:152)  
* [YYDispatchQueuePool](https://github.com/ibireme/YYDispatchQueuePool) -  iOS 全局并发队列管理工具。   ---- (Star:281) (Fork:50) (Watch:17)  
* [YYKeyboardManager](https://github.com/ibireme/YYKeyboardManager) -   iOS 键盘监听管理工具。   ---- (Star:374) (Fork:69) (Watch:10)  
* [BHBDrawBoarderDemo车](https://github.com/bb-coder/BHBDrawBoarderDemo) - 仿写猿题库练题画板功能，没有用drawRect，而是用CAShapeLayer来做画板绘画，特别省内存，赞1个，[实现分析](http://bihongbo.com/2016/01/03/memoryGhostdrawRect/)。   ---- (Star:259) (Fork:64) (Watch:8)  
* [jrswizzle](https://github.com/rentzsch/jrswizzle) - runtime实现的Method Swizzling第三方框架。   ---- (Star:2,077) (Fork:306) (Watch:70)  
* [BGTaobao](https://github.com/huangzhibiao/-) - ios 高仿淘宝/京东详情页 - 集合各种测试框架。   ---- (Star:32) (Fork:31) (Watch:1)  
* [JLRoutes](https://github.com/joeldev/JLRoutes) - JLRoutes好用的URL map库，它的作用是让按钮的点击像网页里的链接一样，只是触发了某个URL，而没有像pushViewController这样的行为，实现解耦。   ---- (Star:3,822) (Fork:426) (Watch:102)  
* [PromiseKit](https://github.com/mxcl/PromiseKit) - 同时支持 Swift 及 Objective-C 的 Promise 类库，异步编程类库 提供了很多实用的异步函数 让异步编程更简单。   ---- (Star:8,379) (Fork:756) (Watch:201)  
* [HWChangeFont](https://github.com/Loveway/HWChangeFont) - 利用runtime一键改变字体。[教程](http://www.jianshu.com/p/b9fdd17c525e)。   ---- (Star:52) (Fork:6) (Watch:2)  
* [RuntimeSummary](https://github.com/Tuccuay/RuntimeSummary) - 一个集合了常用 Objective-C Runtime 使用方法的 Playground。   ---- (Star:210) (Fork:64) (Watch:9)  
* [GCDThrottle](https://github.com/cyanzhong/GCDThrottle) - 限制频率过高的调用GCD多线程。   ---- (Star:130) (Fork:14) (Watch:6)  
* [WHC_KeyboardManager](https://github.com/netyouli/WHC_KeyboardManager)iOS平台轻量级的键盘管理器，使用简单功能强大，键盘再也不会挡住输入控件   ---- (Star:241) (Fork:50) (Watch:7)  

#### 消息相关@
#### 消息推送客户端@

* [SmartPush](https://github.com/shaojiankui/SmartPush) SmartPush,一款iOS苹果远程推送测试程序,Mac OS下的APNS工具APP,iOS Push Notification Debug App   ---- (Star:555) (Fork:175) (Watch:22)  
* [Orbiter](https://github.com/mattt/Orbiter) - 消息推送客户端:Push Notification Registration for iOS.   ---- (Star:698) (Fork:44) (Watch:21)  
* [PushDemo](https://github.com/ios44first/PushDemo) - 客户端消息接收消息代码，[IOS开发之 ---- IOS8推送消息注册](http://blog.sina.com.cn/s/blog_71715bf80102uy2k.html) ， [分分钟搞定IOS远程消息推送](http://my.oschina.net/u/2340880/blog/413584)。   ---- (Star:42) (Fork:17) (Watch:3)  

#### 消息推送服务端@

* [javapns源代码](https://code.google.com/p/archive/downloads/list) - 消息推送的java服务端代码，注意：DeviceToken中间不能有空格。
* [pushMeBaby](https://github.com/stefanhafeneger/PushMeBaby) - Mac端消息推送端代码，注意：DeviceToken中间要有空格。   ---- (Star:836) (Fork:289) (Watch:66)  

#### 时间日期@

* [iso-8601-date-formatter](https://github.com/boredzo/iso-8601-date-formatter)   ---- (Star:598) (Fork:135) (Watch:24)  
cocoaNSFormatter子类日期转换为从ISO- 8601格式的字符串。支持日历，星期，和序格式。

#### 设计模式@

* [Design-Patterns-In-Swift](https://github.com/ochococo/Design-Patterns-In-Swift) 非常👍 Design Patterns implemented in Swift   ---- (Star:8,702) (Fork:931) (Watch:559)  
* [KVOController] (https://github.com/facebook/KVOController)  是一个简单安全的KVO（Key-value Observing，键-值观察）工具，用于iOS 和OS X 应用开发中，开源自facebook。 在项目中有使用 KVO ，那么 KVOController 绝对是个好选择。   ---- (Star:6,009) (Fork:720) (Watch:218)  
* [DecouplingKit] (https://github.com/coderyi/DecouplingKit)   iOS模块化过程中模块间解耦方案。   ---- (Star:111) (Fork:16) (Watch:4)  
* [Trip-to-iOS-Design-Patterns](https://github.com/skyming/Trip-to-iOS-Design-Patterns)   ---- (Star:566) (Fork:94) (Watch:26)  

#### 皮肤@语言国际化@

* [Hodor](https://github.com/Aufree/Hodor) Hodor 是一套可让你的应用快速支持本地化的解决方案, 允许你在应用内直接更改应用语言而无需退出应用, 类似微信.   ---- (Star:493) (Fork:56) (Watch:14)  

#### 版本新API的Demo@

* [appleSample](https://github.com/WildDylan/appleSample) - iOS 苹果官方Demo合集， [官方demo](https://developer.apple.com/library/ios/navigation/#section=Resource%20Types&topic=Sample%20Code).   ---- (Star:184) (Fork:912) (Watch:14)  
* [iOS7-Sampler](https://github.com/shu223/iOS7-Sampler) - 整合了iOS7.0的一些十分有用的特性，比如：Dynamic Behaviors、碰撞检测、语音合成、视图切换、图像滤镜、三维地图、Sprite Kit（动画精灵）、Motion Effect（Parallax）、附近蓝牙或者wifi搜索连接、AirDrop、运动物体追踪（iPhone 5S以上，需要M7处理器）等等。对于日常的应用开发十分实用。   ---- (Star:3,065) (Fork:550) (Watch:272)  
* [iOS8-Sampler](https://github.com/shu223/iOS8-Sampler) - 日本的shuさん制作的 iOS8 参考代码集。01.Audio Effects ；02.New Image Filters；03.Custom Filters；04.Metal Basic；05.Metal Uniform Streaming；06.SceneKit；07.HealthKit；08.TouchID；09.Visual Effects；10.WebKit；11.UIAlertController；12.User Notification；13.Pedometer；14.AVKit；15.Histogram；16.Code Generator；17.New Fonts；18.Popover；19.Accordion Fold Transition   ---- (Star:3,304) (Fork:431) (Watch:196)  
* [iOS-9-Sampler](https://github.com/shu223/iOS-9-Sampler) - 通过实例介绍了iOS 9 SDK中重要新特性的使用。   ---- (Star:3,597) (Fork:470) (Watch:203)  
* [iOS 9 分屏多任务](http://www.cocoachina.com/ios/20150714/12557.html) - iOS 9 分屏多任务：Slide Over & Split View快速入门（中文版）。
* [Search-APIs](https://github.com/fish-yan/Search-APIs) - iOS 9 学习系列: SearchAPIs。[教程](http://blog.csdn.net/fish_yan_/article/details/50635433)   ---- (Star:5) (Fork:1) (Watch:1)  

#### 代码安全与密码@

* [ios-class-guard](https://github.com/Polidea/ios-class-guard) - 一个用于混淆iOS的类名、方法名以及变量名的开源库--有人反映编译出来的app运行不了。   ---- (Star:1,004) (Fork:514) (Watch:50)  
* [《Protecting iOS Applications》](https://www.polidea.com/#!heartbeat/blog/Protecting_iOS_Applications)：文章系统地介绍了如何保护iOS程序的代码安全，防止反汇编分析。
* [fishhook](https://github.com/facebook/fishhook) - fishhook是Facebook开源的一个可以hook系统方法的工具。   ---- (Star:2,027) (Fork:312) (Watch:140)  
* [JMPasswordView](https://github.com/Juuman/JMPasswordView) - 简单实用的手势密码，效果可自行调控。   ---- (Star:25) (Fork:13) (Watch:1)  
* [仿密码锁-九宫格](http://code.cocoachina.com/detail/298556/%E4%BB%BF%E5%AF%86%E7%A0%81%E9%94%81-%E4%B9%9D%E5%AE%AB%E6%A0%BC/) - 仿密码锁-九宫格，主要是使用UIButton 手势事件  UIBezierPath画图，解锁失败弹出“密码错误”。
* [CoreLock](https://github.com/CharlinFeng/CoreLock) - 本框架是高仿支付宝，并集成了所有功能，并非一个简单的解锁界面展示。个人制作用时1周多，打造解锁终结者框架。   ---- (Star:935) (Fork:271) (Watch:45)  
* [LikeAlipayLockCodeView](https://github.com/crazypoo/LikeAlipayLockCodeView) - 高仿支付宝手势解锁（超级版）。   ---- (Star:18) (Fork:5) (Watch:1)  
* [Smile-Lock.swfit](https://github.com/liu044100/Smile-Lock) - 一个类似于iOS的解锁界面。   ---- (Star:465) (Fork:59) (Watch:11)  
* [PCGestureUnlock](https://github.com/iosdeveloperpanc/PCGestureUnlock) - 目前最全面最高仿支付宝的手势解锁，而且提供方法进行参数修改，能解决项目开发中所有手势解锁的开发。   ---- (Star:544) (Fork:144) (Watch:20)  
* [ICPayPassWordDemo](https://github.com/icoder20150719/ICPayPassWordDemo) - CPayPassWordDemo，一个模仿支付宝支付密码输入对话框小demo。   ---- (Star:7) (Fork:3) (Watch:1)  
* [RSAESCryptor](https://github.com/bigsan/RSAESCryptor) - 加密 RSA+AES Encryption/Decryption library for iOS. This library uses 2048-bit RSA and 256-bit key with 128-bit block size AES for encryption/decryption。   ---- (Star:85) (Fork:22) (Watch:12)  
* [TouchID](https://github.com/bringbird/TouchID) - 用法简单的TouchID验证框架：两行代码搞定。   ---- (Star:108) (Fork:39) (Watch:1)  
* [SFHFKeychainUtils] (https://github.com/ldandersen/scifihifi-iphone)iOS中使用SFHFKeychainUtils保存用户密码，比如项目中需要保存用户密码，以实现自动登录的功能可以使用。   ---- (Star:1,226) (Fork:370) (Watch:41)  
* [AESCipher-iOS](https://github.com/WelkinXie/AESCipher-iOS) - AESCipher-iOS:用 Objective-C 实现的 AES 加密。与 [AESCipher-Java](https://github.com/WelkinXie/AESCipher-Java) 一并使用能达到 在iOS、Android、Java后台产生相同密文、正确解密成明文的目的。[AES加密 - iOS与Java的同步实现](http://www.jianshu.com/p/df828a57cb8f)   ---- (Star:61) (Fork:20) (Watch:3)  

#### 版本适配@

* [iOS9AdaptationTips](https://github.com/ChenYilong/iOS9AdaptationTips) iOS9适配系列教程   ---- (Star:4,517) (Fork:1,090) (Watch:387)  

#### 测试调试@

* [FBSimulatorControl](https://github.com/facebook/FBSimulatorControl) 支持同时启动多个模拟器的库，FaceBook出品.   ---- (Star:2,098) (Fork:190) (Watch:101)  
* [calabash-ios](https://github.com/calabash/calabash-ios) 自动测试 Calabash is an automated testing technology for Android and iOS native and hybrid applications.   ---- (Star:1,635) (Fork:361) (Watch:132)  
* [iConsole](https://github.com/nicklockwood/iConsole) 调试利器 In-app console for viewing logs and typing debug commands in iPhone apps   ---- (Star:855) (Fork:159) (Watch:79)  

#### 调试优化@

* [IPAPatch](https://github.com/Naituw/IPAPatch) 免越狱调试、修改第三方App，很👍👍   ---- (Star:2,039) (Fork:285) (Watch:68)  
* [iOS-Performance-Optimization](https://github.com/skyming/iOS-Performance-Optimization) 关于iOS 性能优化梳理、内存泄露、卡顿、网络、GPU、电量、 App 包体积瘦身、启动速度优化等、Instruments 高级技巧、常见的优化技能- Get — Edit   ---- (Star:673) (Fork:127) (Watch:19)  
* [MSLeakHunter](https://github.com/mindsnacks/MSLeakHunter) - 自动检测 UIViewController 和 UIView 对象的内存泄露。Find memory leaks in your iOS app at develop time. [MLeaksFinder 的使用参照](https://github.com/Zepo/MLeaksFinder)   ---- (Star:314) (Fork:48) (Watch:35)  
* [iOS-private-api-checker](https://github.com/NetEaseGame/iOS-private-api-checker) iOS-private-api-checker 苹果iOS私有API检查工具   ---- (Star:265) (Fork:51) (Watch:17)  
* [gitbook](https://github.com/GitbookIO/gitbook) GitBook 是一个基于Node.js 的命令行工具，可使用Github/Git 和Markdown 来制作精美的电子书。 GitBook需要使用markdown格式编写，如果你不了解可以看看这里。   ---- (Star:16,611) (Fork:2,137) (Watch:630)  
* [crashlytics](https://www.fabric.io/onboard) Twitter出的一个崩溃分析软件
* [Knuff](https://github.com/KnuffApp/Knuff)调试iOS App远程推送(APNs)的工具   ---- (Star:3,904) (Fork:303) (Watch:103)  
* [PPAutoPackageScript](https://github.com/jkpang/PPAutoPackageScript) - Xcode8以后的iOS自动打包脚本,配置简单/方便   ---- (Star:206) (Fork:46) (Watch:6)  
* [CocoaDebugKit](https://github.com/Patrick-Kladek/CocoaDebugKit) Debugging made easy. Automatically create QuickLook images of custom objects   ---- (Star:461) (Fork:21) (Watch:5)  
* [AssetsExtractor](https://github.com/pcjbird/AssetsExtractor) 『Assets提取工具』是一款OSX平台上用于将Assets.car或xxx.app中打包的png图片、pdf等资源重新提取出来的开发者工具。Assets.car常见于iOS/Mac/Unity等开发中的资源打包。   ---- (Star:30) (Fork:6) (Watch:2)  

#### Xcode工具@

* [react-native-device-info](https://github.com/rebeccahughes/react-native-device-info) react-native获取设备信息组件,支持iOS、Android.   ---- (Star:1,679) (Fork:400) (Watch:54)  

#### crash@

* [Crashlytics](http://try.crashlytics.com/) - Crashlytics 崩溃报告 崩溃日志   [使用说明](http://www.infoq.com/cn/articles/crashlytics-crash-statistics-tools) 。
* [KSCrash](https://github.com/kstenerud/KSCrash) - iOS Crash 捕获上报工具， 可以自己配置服务器， 也可以与它推荐的服务器搭配使用   ---- (Star:1,761) (Fork:273) (Watch:104)  
* [AvoidCrash](https://github.com/chenfanfang/AvoidCrash) 利用runtime处理崩溃问题的一个框架   ---- (Star:509) (Fork:159) (Watch:23)  
* [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) - 是一个快速、简单，但很强大的日志框架，可以自定义打印日志的颜色。 A fast & simple, yet powerful & flexible logging framework for Mac and iOS   ---- (Star:9,542) (Fork:1,782) (Watch:390)  
* [fastlane](https://github.com/fastlane/fastlane) - 非常棒👍👍👍一套iOS开发和持续集成的命令行工具fastlane，可以用来快速搭建CI甚至自动提交的开发环境。这套工具中包括了上传ipa文件，自动截取多语言截屏，生成推送证书，管理产品证书等一系列实用工具。 The easiest way to automate building and releasing your iOS and Android apps https://fastlane.tools   ---- (Star:18,863) (Fork:2,885) (Watch:604)  
* [FLEX](https://github.com/Flipboard/FLEX) 非常赞的 一个Xcode界面调试工具，FLEX是一个需要注入式的一种框架，从描述来看，功能非常多。主要来讲的话能够对正在运行的应用进行样式的修改和控件的读取。FLEX会赐予你SuperPower！！！   ---- (Star:8,491) (Fork:907) (Watch:372)  
  1. 可以查看控件的坐标和属性
  2. 看任何一个对象的属性和成员变量
  3. 动态修改属性和成员变量
  4. 动态的调用实例和类方法
FLEX正因为是注入式的，所以不需要在链接LLDB或者Xocde，或者是远程的调试服务器，它可以在本地随时随地的进行自有的操作和调试
* [FBMemoryProfiler](https://github.com/facebook/FBMemoryProfiler) - Facebook出品,内存检测库。[FBMemoryProfiler 基础教程](http://ifujun.com/fbmemoryprofiler-shi-yong-ji-chu-jiao-cheng/)。(https://swiftcafe.io/2017/05/02/mem-profiler/?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)   ---- (Star:2,778) (Fork:303) (Watch:123)  
* [xctool](https://github.com/facebook/xctool) - Facebook出的自动化打包工具，它规范了输出的log日志，而且一些错误信息也更为清晰一些。   ---- (Star:6,501) (Fork:732) (Watch:291)  
* [chisel](https://github.com/facebook/chisel) Chisel扩展了一些列的lldb的命令来帮助iOS开发者调试iOS应用程序。   ---- (Star:6,318) (Fork:549) (Watch:286)  
* [PonyDebugger](https://github.com/square/PonyDebugger)由 Square 公司推出的一款优秀的 iOS 应用网络调试工具, 用户可以实时看到应用程序的网络请求, 也可以对 iOS 应用程序的核心数据栈进行远程调试   ---- (Star:5,470) (Fork:576) (Watch:320)  
* [KIF](https://github.com/kif-framework/KIF) - 是一个开源的用户界面UI测试框架. 使用 KIF, 并利用 iOS中的辅助功能 API, 你将能够编写模拟用户输入，诸如点击，触摸和文本输入，自动化的UI测试.   ---- (Star:5,084) (Fork:817) (Watch:187)  
* [pxctest](https://github.com/plu/pxctest) Execute tests in parallel on multiple iOS Simulators 在多个 iOS 模拟器上并行测试。   ---- (Star:767) (Fork:57) (Watch:26)  
* [dSYMTools](https://github.com/answer-huang/dSYMTools)友盟 dSYM analyze  备用地址[https://github.com/mrhyh/dSYMTools]   ---- (Star:1,686) (Fork:463) (Watch:67)  
* [HeapInspector](https://github.com/tapwork/HeapInspector-for-iOS) - HeapInspector是一个用于检测应用中的内存泄漏的开源调试工具。   ---- (Star:1,625) (Fork:130) (Watch:59)  
* [UIViewController-Swizzled](https://github.com/RuiAAPeres/UIViewController-Swizzled) - 把你进入的每一个controller的类名打出来,如果看一些特别复杂的项目的时候直接运行demo就可以知道执行次序了。   ---- (Star:860) (Fork:138) (Watch:30)  
* [snoop-it](https://code.google.com/archive/p/snoop-it/) - snoop-it比UIViewController-Swizzled好用，代码托管在google上。
* [Versions](https://github.com/zenangst/Versions) - 版本比较小工具。   ---- (Star:182) (Fork:11) (Watch:5)  
* [MobileWebPageTest](http://code4app.com/ios/MobileWebPerformanceTest/5465d3e9933bf00c658b4f43) - MobileWebPageTest是用来测试移动网页性能的软件，它可以对页面的加载和渲染过程进行截屏，协助开发者分析出页面性能瓶颈。
* [KKLog](https://github.com/Coneboy-k/KKLog) - 一个日志管理系统。   ---- (Star:127) (Fork:22) (Watch:4)  
* [Buildasaur](https://github.com/czechboy0/Buildasaur) - 自动测试框架 Buildasaur。   ---- (Star:718) (Fork:67) (Watch:24)  
* [使用Quick框架和Nimble来测试ViewControler](http://www.devtf.cn/?p=739) - Quick是一个用于创建BDD测试的框架。配合Nimbl，可以为你创建更符合预期目标的测试。
* [Quick](https://github.com/Quick/Quick) - 用于Swift中的单元测试（也可用于Objective-C），与Xcode整合在一起。如果你是Objective-C的粉丝，我建议用Specta代替这个，但是对Swift使用者来说，Quick是最佳选择。   ---- (Star:6,964) (Fork:670) (Watch:250)  
* [Bugtags-iOS](https://github.com/bugtags/Bugtags-iOS) 一个简单、有效的bug和崩溃报告工具.   ---- (Star:89) (Fork:16) (Watch:4)  

#### Runtime@

* [iOS私有API](https://github.com/nst/iOS-Runtime-Headers) - 这个仓库可以调取苹果的所有私有方法头文件，相当强大。私有API，绿色 == public，红色 == private，蓝色 == dylib。   ---- (Star:5,986) (Fork:1,311) (Watch:464)  

#### Xcode插件@

* [MonkeyDev](https://github.com/AloneMonkey/MonkeyDev) 原有iOSOpenDev的升级，非越狱插件开发集成神器！ CaptainHook Tweak、Logos Tweak and Command-line Tool、Patch iOS Apps, Without Jailbreak.   ---- (Star:952) (Fork:168) (Watch:33)  
* [xTextHandler](https://github.com/cyanzhong/xTextHandler) Xcode源码编辑扩展工具(Xcode8版) Xcode Source Editor Extension Tools (Xcode 8 Plugins)   ---- (Star:1,377) (Fork:73) (Watch:40)  
* [首先学习使用Xcode](http://www.cocoachina.com/special/xcode/) - 学习使用Xcode构建出色的应用程序！在Xcode启动的时候，Xcode将会寻找位于~/Library/Application Support/Developer/Shared/Xcode/Plug-ins文件夹中的后缀名为.xcplugin的bundle作为插件进行加载（运行其中的可执行文件）。
* [RPAXU](https://github.com/cikelengfeng/RPAXU) 每当 Xcode 升级之后，都会导致原有的 Xcode 插件不能使用，这是因为每个插件的 Info.plist 中记录了该插件兼容的 Xcode 版本的DVTPlugInCompatibilityUUID，而每个版本的 Xcode 的 DVTPlugInCompatibilityUUID 都是不同的。如果想让原来的插件继续工作，我们就得将新版 Xcode 的 DVTPlugInCompatibilityUUID 加入到每一个插件的 Info 文件中，手动添加的话比较费时间还可能出错，所以作者写了一个脚本来做这件事。   ---- (Star:237) (Fork:56) (Watch:8)  
* [Alcatraz](https://github.com/alcatraz/Alcatraz) -使用Alcatraz来管理Xcode插件   ---- (Star:10,075) (Fork:1,273) (Watch:440)  
* [Polychromatic](https://github.com/kolinkrewinkel/Polychromatic)  为不同的变量类型赋予不同的颜色   ---- (Star:1,100) (Fork:72) (Watch:37)  
* [ClangFormat-Xcode](https://github.com/travisjeffery/ClangFormat-Xcode) clang-format 代码格式化   ---- (Star:2,560) (Fork:288) (Watch:107)  
* [BBUncrustifyPlugin-Xcode](https://github.com/benoitsan/BBUncrustifyPlugin-Xcode) 代码格式化   ---- (Star:1,209) (Fork:176) (Watch:57)  
* [HOStringSense-for-Xcode](https://github.com/holtwick/HOStringSense-for-Xcode)有图，点进去一看就明白了，代码编辑器里的字符串编辑器，粘贴大段 HTML 字符串之类的很方便，自动转义。   ---- (Star:724) (Fork:508) (Watch:41)  
* [ZLGotoSandboxPlugin](https://github.com/MakeZL/ZLGotoSandboxPlugin) - 支持Xcode快捷键了跳转当前应用沙盒了！快捷键是 Shift+Common+w。   ---- (Star:568) (Fork:95) (Watch:23)  
* [cocoapods-xcode-plugin](https://github.com/kattrali/cocoapods-xcode-plugin) - 该CocoaPods的插件增加了一个CocoaPods菜单到Xcode的产品菜单。如果你不喜欢命令行，那么你一定会喜欢这个插件。     ---- (Star:2,386) (Fork:359) (Watch:127)  
* [Carthage](https://github.com/Carthage/Carthage)Carthage是一个新的第三方库管理工具，它轻耦合，使用很灵活，不会修改项目文件，使用xcodebuild工具来编译第三方库。跟cocoaPod有些类似。   ---- (Star:10,322) (Fork:928) (Watch:328)  
* [KSImageNamed](https://github.com/ksuther/KSImageNamed-Xcode) - 自动完成，特别是如果你正在写Objective-C，如果Xcode能自动完成文件名难道不会很伟大吗？比如图像文件的名称。   ---- (Star:4,292) (Fork:776) (Watch:202)  
* [KFCocoaPodsPlugin](https://github.com/ricobeck/KFCocoaPodsPlugin)	Xcode插件 cocoapod, 方便编辑Podfile，显示构建日志   ---- (Star:835) (Fork:64) (Watch:38)  
* [XCActionBar](https://github.com/pdcgomes/XCActionBar) 是一个用于 Xcoded 的通用生产工具。   ---- (Star:1,225) (Fork:44) (Watch:39)  
* [XcodeBoost](https://github.com/fortinmike/XcodeBoost) XcodeBoost 是一款可以让开发者轻而易举地检查和修改 Objective-C 代码的插件。XcodeBoost 能够自动进行一些繁琐的操作，比如方法的定义与声明、添加基于命令行的代码处理（剪切/复制/粘贴/重复/删除行）、持续高亮等。   ---- (Star:846) (Fork:95) (Watch:34)  
* [SCXcodeSwitchExpander](https://github.com/stefanceriu/SCXcodeSwitchExpander)在写switch时，自动补全所有选项 (只支持NS_ENUM)   ---- (Star:669) (Fork:105) (Watch:23)  
* [ColorSense-for-Xcode](https://github.com/omz/ColorSense-for-Xcode)ColorSense是一款Xcode颜色插件，可让UIColor和NSColor更加可视化。虽然已经有很多工具允许你从取色板插入UIColor/NSColor或者从屏幕上取色，但这些工具并不会记忆你此前你的常用选择。不过ColorSense可以解决这个问题，把插入符放在代码上即可展示实际颜色，并可以使用标准的Mac OS X颜色选择器进行调整。此外，该插件还在编辑菜单上添加了可插入颜色或者暂时禁用颜色高亮的项目，这些菜单项目没有默认的快捷键，但是你可以通过系统的键盘设置偏好进行设置。   ---- (Star:2,910) (Fork:508) (Watch:168)  
* [tween-o-matic](https://github.com/simonwhitaker/tween-o-matic) 编辑CAMediaTimingFunction动画曲线   ---- (Star:117) (Fork:14) (Watch:9)  
* [iOS-Universal-Framework] (https://github.com/kstenerud/iOS-Universal-Framework) 	iOS-Universal-Framework 是一个方便你将第三方 SDK 编译成 Framework 的开源工具。   ---- (Star:2,930) (Fork:518) (Watch:217)  
* [iOS-Framework](https://github.com/jverkoey/iOS-Framework) 编译iOS的Framework的通用模板   ---- (Star:2,463) (Fork:303) (Watch:158)  
[Xcode-Plugin-Template ](https://github.com/kattrali/Xcode-Plugin-Template） 插件开发
[XcodeEditor](https://github.com/appsquickly/XcodeEditor) 解析和操作Xcode工程文件
* [fui](https://github.com/dblock/fui) Fui 可以用来查找 Xcode 项目中无用的 import 并予以删除   ---- (Star:994) (Fork:69) (Watch:27)  
* [SCStringsUtility](https://github.com/stefanceriu/SCStringsUtility) 让你在一个清爽的界面编辑不同的语言，简单地输入/输出NSLocalizedString数据。   ---- (Star:540) (Fork:52) (Watch:39)  
* [Lin](https://github.com/questbeat/Lin) 一个开源的Mac基础工具，可以让你在一个清爽的界面编辑不同的语言，简单地输入/输出NSLocalizedString数据。提供了一个非常不错的操作界面，并且为不同的语言提供了不同的区域。   ---- (Star:1,237) (Fork:92) (Watch:49)  
* [Transformifier](https://github.com/erwinmaza/Transformifier) Transformifier是一款通用的交互式的3D转换调整工具，用于iOS开发。开发者可以通过它以可视化的方式变换各维度上的值，还可以把使用CATransform3D输出的代码导入自己的app中。   ---- (Star:436) (Fork:28) (Watch:33)  
* [UIEffectDesignerView](https://github.com/icanzilb/UIEffectDesignerView)   ---- (Star:625) (Fork:106) (Watch:33)  
iOS和OSX原生粒子系统效果图搭载QuartzCore
* [Xcode5 Plugins 开发简介](http://studentdeng.github.io/blog/2014/02/21/xcode-plugin-fun/)  [写个自己的Xcode4插件](http://joeyio.com/ios/2013/07/25/write_xcode4_plugin_of_your_own/)
* [RTImageAssets](https://github.com/rickytan/RTImageAssets) - 一个 Xcode 插件，用来生成 @3x 的图片资源对应的 @2x 和 @1x 版本。[Asset Catalog Creator](https://itunes.apple.com/app/asset-catalog-creator-free/id866571115?mt=12) 功能强大，能自动生成全部尺寸：包括App Icons、Image Sets、Launch Screens Generator。   ---- (Star:2,399) (Fork:354) (Watch:85)  
* [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode) - 一个Xcode插件，build后，随手打开一个你之前的项目，然后在任意一个方法上面连按三下"/"键盘，就ok了。   ---- (Star:8,443) (Fork:1,711) (Watch:401)  
* [java2Objective-c](https://github.com/google/j2objc) - Google公司出得java转Obje-C转换工具，转换逻辑，不转换UI。   ---- (Star:4,929) (Fork:669) (Watch:311)  
* [RegX](https://github.com/kzaher/RegX) - 专治代码强迫症的 Xcode 插件，使用 Swift 和 Objective-C 编写。其用竖向对齐特定源代码的元素，使得代码更易读和易理解。[说明](http://www.cocoachina.com/ios/20141224/10743.html) ； 菜单：xcode——》Edit-》Regx 。   ---- (Star:178) (Fork:26) (Watch:13)  
* [CodePilot](https://github.com/macoscope/CodePilot) Code Pilot是一款在项目中快速方便地查找文件、方法和符号，Xcode 5的扩充开源插件，开发者无需鼠标进行操作。   ---- (Star:1,352) (Fork:235) (Watch:92)  
* [XVim](https://github.com/XVimProject/XVim) 支持绑定VIM快捷键   ---- (Star:5,178) (Fork:713) (Watch:276)  
* [CATweaker](https://github.com/keefo/CATweaker) CATweaker – 一个用于创建漂亮的CAMediaTimingFunction 曲线的插件. XcodeWay – 便捷地导航到多个地方   ---- (Star:707) (Fork:58) (Watch:19)  
* [FuzzyAutocomplete](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin) - Xcode的实现自动完成还不完美，此插件能给出你所期望或想要的建议，设置：xcode-》Editor-》FuzzyAutocomplete-》plugin settings。   ---- (Star:3,391) (Fork:411) (Watch:113)  
* [GitDiff](https://github.com/johnno1962/GitDiff) - Xcode的代码编辑器的一个微妙的补强，加上了足够的可见信息以了解上次git提交以来发生了什么变化，设置：xcode-》Edit-》GitDiff。   ---- (Star:867) (Fork:57) (Watch:23)  
* [XToDo](https://github.com/trawor/XToDo) - 这个插件不仅凸显TODO，FIXME，???，以及！！！注释，也在便利列表呈现他们。 菜单：xcode-》view-》snippets;   调出列表显示: xcode-》view-》ToDo List ： ctrl + T 。   ---- (Star:1,594) (Fork:207) (Watch:57)  
* [Backlight](https://github.com/limejelly/Backlight-for-XCode) - 突出显示当前正在编辑的行。菜单：xcode-》view-》Backlight 。   ---- (Star:437) (Fork:78) (Watch:23)  
* [Peckham](https://github.com/markohlebar/Peckham) - 添加import语句比较麻烦，此插件 按Command-Control-P，给出的选项列表中选择要的头文件。先要安装   ---- (Star:732) (Fork:101) (Watch:37)  
* [Auto-Importer](https://github.com/citrusbyte/Auto-Importer-for-Xcode) - Auto-Importer是一个自动导入类对应的头文件的Xcode插件。   ---- (Star:580) (Fork:62) (Watch:23)  
* [KSHObjcUML](https://github.com/kimsungwhee/KSHObjcUML) -KSHObjcUML 是一个 Objective-C 类引用关系图的 Xcode 插件。   ---- (Star:937) (Fork:94) (Watch:32)  
* [Dash-Plugin-for-Xcode](https://github.com/omz/Dash-Plugin-for-Xcode)。   ---- (Star:1,554) (Fork:207) (Watch:98)  
* [ESJsonFormat-Xcode](https://github.com/EnjoySR/ESJsonFormat-Xcode) - 将Json格式化输出为模型的属性。   ---- (Star:1,875) (Fork:345) (Watch:70)  
* [SCXcodeMiniMap](https://github.com/stefanceriu/SCXcodeMiniMap) - Xcode迷你小地图-SCXcodeMiniMap。   ---- (Star:1,042) (Fork:109) (Watch:43)  
* [xTransCodelation](http://code.cocoachina.com/detail/316095/xTransCodelation/) - XCODE中英文翻译插件，提供API查询模式和网页模式，都是利用的百度翻译。另外集成了一个可以一键关闭其他所有APP的实用功能，方便开发者！目前只有30多颗星。
* [jazzy](https://github.com/realm/jazzy) 通过代码注释生成doc文档,支持ObjC/Swift,分析准确   ---- (Star:4,789) (Fork:257) (Watch:149)  
* [CoPilot](https://vimeo.com/128713880) - 通过此插件， Xcode 可以协同编程了（采用 WebSocket 通讯）。如此强大的“黑工具”，不爱它能行吗。
* [SuggestedColors](https://github.com/jwaitzel/SuggestedColors/) - Xcode 插件SuggestedColors，用于 IB颜色设置 辅助插件，非常好用。   ---- (Star:88) (Fork:11) (Watch:4)  
* [Crayons](https://github.com/Sephiroth87/Crayons) - Xcode调色板增强插件。   ---- (Star:490) (Fork:7) (Watch:17)  
* [injectionforxcode](https://github.com/johnno1962/injectionforxcode) - Injection for Xcode：成吨的提高开发效率,[使用说明](http://www.jianshu.com/p/27be46d5e5d4)。   ---- (Star:4,931) (Fork:443) (Watch:157)  
* [IconMaker](https://github.com/kaphacius/IconMaker) - 只需要一步，自动生成不同尺寸的App icon。超级方便。   ---- (Star:499) (Fork:34) (Watch:8)  
* [BuildTimeAnalyzer-for-Xcode](https://github.com/RobertGummesson/BuildTimeAnalyzer-for-Xcode) - 实用的编译时间分析 Xcode 插件。   ---- (Star:2,033) (Fork:94) (Watch:53)  
* [FastStub-Xcode](https://github.com/music4kid/FastStub-Xcode) - 一只快速生成代码的Xcode插件，[说明](http://mrpeak.cn/blog/faststub/)。   ---- (Star:493) (Fork:56) (Watch:12)  
* [ESTranslate-Xcode](https://github.com/EnjoySR/ESTranslate-Xcode) - 一个快速翻译Xcode代码里面单词(我主要用于翻译句子～)的插件，快捷键：Ctrl+Shift+T。   ---- (Star:245) (Fork:36) (Watch:5)  

#### 接口调试工具@

* [PostMan](https://www.getpostman.com/) google出品的接口调试工具

#### AppleWatch

* [Tesla汽车AppleWatch app demo演示](https://github.com/eleks/rnd-apple-watch-tesla) - 通过AppleWatch控制特斯拉汽车，同时可以看到汽车的相关信息，比如剩余电量、可续行里程等，以及解锁/上锁车门、调节司机和乘客的四区域空调温度、开启车辆大灯、定位汽车等。[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。   ---- (Star:362) (Fork:63) (Watch:43)  
* [WatchKit-Apps](https://github.com/kostiakoval/WatchKit-Apps) - WatchKit 开源小项目示例集锦。是不可多得地学习 WatchKit 的示例式教程（1.如何创建一个简单的交互式计数器；2.如何从手表上控制iOS app；3.如何在WatchKit app和iOS app之间共享数据；4.如何创建一个拥有不同背景色的数字时钟；5.展示不同的UI层；6.如何创建支持滑动手势的应用程序。）。   ---- (Star:1,069) (Fork:144) (Watch:77)  
* [kiwi-bdd](https://github.com/kiwi-bdd/Kiwi/wiki) - TDD或BDD，objective-c语言的测试框架，最流行的BDD测试框架了，Kiwi最受欢迎（根据github上的star数来推断，行为描述和期望写起来也比较易懂，至少我是这么认为的） [iOS开发中的测试框架](http://www.jianshu.com/p/7e3f197504c1#)。   ---- (Star:3,686) (Fork:486) (Watch:148)  
* [specta](https://github.com/specta/specta) -  TDD或BDD，objective-c语言的测试框架，用的人多。   ---- (Star:2,072) (Fork:210) (Watch:69)  
* [cedar](https://github.com/pivotal/cedar) -  TDD或BDD，objective-c语言的测试框架，用的人少。   ---- (Star:1,141) (Fork:158) (Watch:68)  
* [ViewMonitor](https://github.com/daisuke0131/ViewMonitor) - 能够帮助 iOS 开发者们精确的测量视图, 可直接在调试应用中查看具体某个视图的坐标, 宽高等参数。   ---- (Star:709) (Fork:53) (Watch:20)  
* [MMPlaceHolder](https://github.com/adad184/MMPlaceHolder) - 一行代码显示UIView的位置及相关参数。   ---- (Star:952) (Fork:144) (Watch:36)  
* [KMCGeigerCounter](https://github.com/kconner/KMCGeigerCounter) - KMCGeigerCounter通过复杂和简单的视图演示了类似盖革计数器的帧速计算功能。掉帧通常是可见的，但是很难区分55fps和60fps之间的不同，而KMCGeigerCounter可以让你观测到掉落5帧的情况。   ---- (Star:1,869) (Fork:234) (Watch:57)  
* [ipapy](https://github.com/hades0918/ipapy) - iOS项目自动打包脚本，并且上传到fir.im，然后发送邮件给测试人员。   ---- (Star:357) (Fork:117) (Watch:19)  
* [fbretaincycledetector](https://github.com/facebook/fbretaincycledetector) - Facebook出品,通过Runtime监测循环引用。   ---- (Star:2,660) (Fork:273) (Watch:91)  
* [FBAllocationTracker](https://github.com/facebook/FBAllocationTracker) - Facebook出品,跟踪oc对象的分配情况。   ---- (Star:802) (Fork:96) (Watch:48)  
* [JxbDebugTool](https://github.com/JxbSir/JxbDebugTool) 一个iOS调试工具，监控所有HTTP请求，自动捕获Crash分析。   ---- (Star:63) (Fork:31) (Watch:3)  
* [KSCrash](https://github.com/kstenerud/KSCrash) - iOS Crash 捕获上报工具， 可以自己配置服务器， 也可以与它推荐的服务器搭配使用   ---- (Star:1,761) (Fork:273) (Watch:104)  

#### App更新提示@

* [iVersion](https://github.com/nicklockwood/iVersion) 非常赞👍 的一个灵活动态监测App是否有更新的库，并可以通知用户升级.   ---- (Star:1,971) (Fork:306) (Watch:97)  

#### 动态更新@

* [waxPatch](https://github.com/mmin18/WaxPatch) - 大众点评的屠毅敏同学在基于[wax](https://github.com/probablycorey/wax)的基础上写了waxPatch，这个工具的主要原理是通过lua来针对objc的方法进行替换，由于lua本身是解释型语言，可以通过动态下载得到，因此具备了一定的动态部署能力。   ---- (Star:787) (Fork:191) (Watch:61)  
* [JSPatch](https://github.com/bang590/JSPatch) - JSPatch 是一个开源项目(Github链接)，只需要在项目里引入极小的引擎文件，就可以使用 JavaScript 调用任何 Objective-C 的原生接口，替换任意 Objective-C 原生方法。目前主要用于下发 JS 脚本替换原生 Objective-C 代码，实时修复线上 bug。[官网](https://github.com/bang590/JSPatch)。(JSPatchX)[https://github.com/bang590/JSPatchX] JSPatch的XCode 代码补全插件。   ---- (Star:10,095) (Fork:2,135) (Watch:512)  
* [CTJSBridge](https://github.com/casatwy/CTJSBridge) - JCTJSBridge：a javascript bridge for iOS app to interact with h5 web view。   ---- (Star:291) (Fork:67) (Watch:10)  

#### AppleWatch@

* [Tesla汽车AppleWatch app demo演示](https://github.com/eleks/rnd-apple-watch-tesla) - 通过AppleWatch控制特斯拉汽车，同时可以看到汽车的相关信息，比如剩余电量、可续行里程等，以及解锁/上锁车门、调节司机和乘客的四区域空调温度、开启车辆大灯、定位汽车等。[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。   ---- (Star:362) (Fork:63) (Watch:43)  
* [WatchKit-Apps](https://github.com/kostiakoval/WatchKit-Apps) - WatchKit 开源小项目示例集锦。是不可多得地学习 WatchKit 的示例式教程（1.如何创建一个简单的交互式计数器；2.如何从手表上控制iOS app；3.如何在WatchKit app和iOS app之间共享数据；4.如何创建一个拥有不同背景色的数字时钟；5.展示不同的UI层；6.如何创建支持滑动手势的应用程序。）。   ---- (Star:1,069) (Fork:144) (Watch:77)  
* [KYVoiceCurve](https://github.com/KittenYang/KYVoiceCurve) - 类似Apple Watch中语音的声音曲线动画。     ---- (Star:46) (Fork:4) (Watch:4)  
* [IGInterfaceDataTable](https://github.com/facebookarchive/IGInterfaceDataTable) - IGInterfaceDataTable是WKInterfaceTable对象的一个类别，可以让开发者更简单地配置多维数据。该项目使用类似UITableViewDataSource的数据源模式配置Apple Watch表格，而不是将数据结构扁平化成为数组。     ---- (Star:855) (Fork:61) (Watch:38)  
* [watchOS-2-Sampler](https://github.com/shu223/watchOS-2-Sampler) - 基于 watchOS 2 若干新特性，写了相应的示例代码供大家学习、参考。   ---- (Star:1,017) (Fork:140) (Watch:86)  
* [HMWatch](https://github.com/KhaosT/HMWatch) - HMWatch是个有待完善的watchOS 2.0 HomeKit 应用示例。   ---- (Star:14) (Fork:1) (Watch:1)  
* [CocoaMultipeer](https://github.com/manavgabhawala/CocoaMultipeer) - CocoaMultipeer这个开源框架支持OS X, iOS和watchOS设备间的点对点通信，解决watchOS和Mac之间通信的方案还是很有用的。   ---- (Star:85) (Fork:10) (Watch:10)  
* [HighstreetWatchApp](https://github.com/GetHighstreet/HighstreetWatchApp) - 是电商平台Highstreet针对App Watch的一款应用，该demo中加载的是虚拟数据。   ---- (Star:352) (Fork:32) (Watch:13)  
* [NKWatchChart](https://github.com/NilStack/NKWatchChart) - NKWatchChart是一个基于PNChart专门为Apple Watch 开发的图表库,目前支持 line, bar, pie, circle 和 radar 等 图表形式。   ---- (Star:248) (Fork:24) (Watch:14)  
* [BeijingAirWatch](https://github.com/diwu/BeijingAirWatch) - 国人的开源项目代码 ！WatchOS 2.0 Complication of Real-time Air Quality for Major Chinese Cities 苹果表盘实时刷新北上广沈蓉空气质量。   ---- (Star:55) (Fork:9) (Watch:4)  

#### VPN完整项目@

* [Hydro.network](https://github.com/CatchChat/Hydro.network) - [Hydro.network 的开发旅程](http://blog.zhowkev.in/2015/03/09/hydro-network-de-kai-fa-lu-cheng/), [gitcafe](https://gitcafe.com/Catch/Hydro.network)。   ---- (Star:393) (Fork:72) (Watch:13)  
* [Potatso](https://github.com/shadowsocks/Potatso) 基于iOS 9 的 NetworkExtension 框架实现 Shadowsocks 代理，由国人开发，虽然还有很多问题不过确实值得期待。   ---- (Star:3,327) (Fork:1,127) (Watch:146)  

#### 好的文章@

* [自定义转场动画](http://www.jianshu.com/p/38cd35968864) - 3 种方法～ 关于自定义转场动画。
* [用 JSON 构建 API 的标准指南](http://jsonapi.org.cn/) - 用 JSON 构建 API 的标准指南。
* [iOS创建半透明ViewController](http://miketech.it/ios-transparent-viewcontroller/) - iOS创建半透明ViewController。
* [iOS蓝牙开发（四）：BabyBluetooth蓝牙库介绍](http://www.cocoachina.com/ios/20160219/15301.html) - [iOS蓝牙开发（一）蓝牙相关基础知识](http://www.cocoachina.com/ios/20150915/13454.html),[iOS蓝牙开发（二）：iOS连接外设的代码实现](http://www.cocoachina.com/ios/20160217/15294.html),[iOS蓝牙开发（三）：App作为外设被连接的实现](http://www.cocoachina.com/ios/20160218/15299.html)。
* [统计项目中图片使用情况](http://blog.adorkabledean.cn/blog/20151027/tong-ji-xiang-mu-zhong-tu-pian-shi-yong-qing-kuang/) - 统计项目中图片使用情况;工具：[Unused](http://jeffhodnett.github.io/Unused/):找出项目中未使用的图片, Unused 的基础上改了一下的[LSUnusedResources](https://github.com/tinymind/LSUnusedResources);工具：[ImageOptim](https://imageoptim.com/) 图片保真压缩。【iOS图片压缩工具】效率最高的是[tiny-png](http://www.alfredforum.com/topic/1520-tiny-png-workflow-updated-to-v12/):在线压缩，前500张免费。   ---- (Star:874) (Fork:160) (Watch:36)  
* [iOS推送之远程推送](http://ios.jobbole.com/83952/) 、[iOS推送之本地推送](http://ios.jobbole.com/83949/)。
* [动态部署方案](http://www.cocoachina.com/ios/20151019/13761.html) - iOS应用架构谈动态部署方案。
* [ReactiveCocoa 4 文档翻译目录](http://www.jianshu.com/p/fccba7be1ca1) - ReactiveCocoa 4 文档翻译目录。    
* [每个Xcode开发者应该知道的七个使用技巧](http://www.cocoachina.com/ios/20160304/15558.html) - 每个Xcode开发者应该知道的七个使用技巧。
* [腾讯力作！超实用的iOS 9人机界面指南](http://blog.jobbole.com/94261/) - 腾讯力作！超实用的iOS 9人机界面指南。    
* [iOS开发-超链接富文本案](http://ios.jobbole.com/84956/) - iOS开发-超链接富文本。
* [UIView+RedPoint实现底部UITabBarItem和控件的右上角显示和隐藏红点/数字的需求](https://segmentfault.com/a/1190000005112043) -
* [使用GCD实现和封装分组并发网络请求](www.jianshu.com/p/54bbacfcc31b) - 使用GCD实现和封装分组并发网络请求。
* [微信语音连播的实现思路](http://www.jianshu.com/p/1d354feacf3c) - 微信语音连播的实现思路。
* [UITableView 手势延迟导致subview无法完成两次绘制](http://www.jianshu.com/p/b422d92738ac) - UITableView 手势延迟导致subview无法完成两次绘制。

#### 美工资源@

* [TWG_Retina_Icons](https://github.com/markohlebar/Peckham) - 一套支持 Retina 高清屏的 iPhone 免费图标集。   ---- (Star:732) (Fork:101) (Watch:37)  
* [ASCIImage](https://github.com/cparnot/ASCIImage) - 使用 NSString 创建 image，[说明](http://cocoamine.net/blog/2015/03/20/replacing-photoshop-with-nsstring/)。   ---- (Star:1,543) (Fork:81) (Watch:46)  
* [my-sketch-colors](https://github.com/RayPS/my-sketch-colors) - 配色。   ---- (Star:506) (Fork:30) (Watch:22)  
* [Font Awesome](http://www.imooc.com/wenda/detail/250367) - Font Awesome：一套绝佳的图标字体库和CSS框架，详细的安装方法请参考[官方网站](http://fortawesome.github.io/Font-Awesome/icons/)[中文网站](http://fontawesome.dashgame.com/),[GitHub地址](https://github.com/FortAwesome/Font-Awesome) 。   ---- (Star:53,022) (Fork:9,263) (Watch:1,324)  
* [DynamicColor](https://github.com/yannickl/DynamicColor) - 强大的颜色操作扩展类。通过该类，你可以通过扩展方法基于某个颜色得到不同深浅、饱和度、灰度、色相，以及反转后的新颜色。是不可多得的好类库。   ---- (Star:1,711) (Fork:78) (Watch:48)  
* [FontBlaster](https://github.com/ArtSabintsev/FontBlaster) - 载入定制字体时更简单。   ---- (Star:851) (Fork:61) (Watch:17)  

#### 其他资源@

* [githuber](http://githuber.info/#/index) - 最好用的GitHub人才搜索工具。   
* [codatlas](https://www.codatlas.com) - 源代码搜索利器。
* [searchcode](https://searchcode.com/) - 源代码搜索利器：来自悉尼的代码搜索引擎汇聚了 Github, Bitbucket, Sourceforge...等多家开源站点超20万个项目、180亿行源代码，能以特殊字符、语言、仓库和源方式从90多种语言找到函数、API的真实代码。
* [kitematic](https://github.com/docker/kitematic) - Mac 上使用 Docker 最简单的方案。   ---- (Star:7,913) (Fork:893) (Watch:308)  

#### 学习资料@

#### 播客@

* [The Ray Wenderlich Podcast](https://www.raywenderlich.com/rwpodcast)
* [Debug](http://www.imore.com/debug)
* [App Story](http://www.appstorypodcast.com)
* [Mobile Couch](http://mobilecouch.co/)
* [iOS Bytes](https://iosbytes.codeschool.com/)
* [iPhreaks](https://devchat.tv/iphreaks)
* [Under the Radar](https://www.relay.fm/radar)
* [Core Intuition](http://coreint.org/)
* [Release Notes](https://releasenotes.tv/)
* [More Than Just Code](http://mtjc.fm/)
* [Runtime](https://spec.fm/podcasts/runtime)
* [Consult](http://consultpodcast.com/)
* [Fireside Swift](https://itunes.apple.com/us/podcast/fireside-swift/id1269435221?mt=2)

#### 学习资料@

* [free-programming-books](https://github.com/EbookFoundation/free-programming-books)非常棒👍👍👍 经常更新的免费资源列表，包括书籍，播客，网站，开发工具等等。对于正在学习代码的人来说挺实用；  Whether you're learning to code or are already an experienced programmer, this GitHub repository is an incredible resource of free programming books. ... You'll find books on professional development, specific platforms like Android and Oracle Server, and about 80 programming languages.   ---- (Star:96,407) (Fork:24,280) (Watch:7,015)  
* [coding-interview-university](https://github.com/jwasham/coding-interview-university) 非常棒👍👍👍 A complete computer science study plan to become a software engineer.   ---- (Star:48,796) (Fork:12,776) (Watch:2,897)  
* [Analyze](https://github.com/Draveness/Analyze) 深入解析 iOS 开源项目   ---- (Star:5,200) (Fork:1,235) (Watch:395)  
* [articles](https://github.com/objccn/articles) Articles for objccn.io. objc.io的完整、准确、优雅的中文翻译版本   ---- (Star:1,795) (Fork:411) (Watch:186)  
* [RNStudyNotes](https://github.com/crazycodeboy/RNStudyNotes) React Native 研究与实践   ---- (Star:1,833) (Fork:413) (Watch:143)  
* [iOSInterviewQuestions](https://github.com/ChenYilong/iOSInterviewQuestions) iOS面试题集锦（附答案）   ---- (Star:5,943) (Fork:1,918) (Watch:358)  
* [growth-ebook](https://github.com/phodal/growth-ebook) Growth Engineering: The Definitive Guide。全栈增长工程师指南   ---- (Star:5,506) (Fork:1,042) (Watch:493)  
* [ideabook](https://github.com/phodal/ideabook)一个全栈增长工程师的练手项目集. A Growth Engineering Idea in Action.   ---- (Star:2,721) (Fork:761) (Watch:332)  
* [zen](https://github.com/100mango/zen) iOS, Swift, Objective-C 心得   ---- (Star:2,120) (Fork:407) (Watch:130)  
* [objc-zen-book-cn](https://github.com/oa414/objc-zen-book-cn) 禅与 Objective-C 编程艺术 （Zen and the Art of the Objective-C Craftsmanship 中文翻译）   ---- (Star:2,764) (Fork:681) (Watch:156)  
* [dev-blog](https://github.com/nixzhu/dev-blog) 翻译、开发心得或学习笔记   ---- (Star:3,395) (Fork:674) (Watch:274)  
* [Show](https://github.com/CharlinFeng/Show) 成都地区一个公司开源项目目录   ---- (Star:147) (Fork:37) (Watch:16)  
* A-[awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)  GitHub上所有Awesome Awesomeness 系列集合. 这个系列集合收集上GitHub上优秀的开源项目、框架、书籍、网站、类库等实用资源的集合。
* [豆瓣iOS开源库列表](https://www.douban.com/note/276160185/?type=like) - 豆瓣iOS开源库列表，很多开源项目。
* [iOS-Core-Animation-Advanced-Techniques](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques) - 中文版iOS 高级动画技术。   ---- (Star:3,537) (Fork:1,146) (Watch:274)  
* [iOS开发的一些奇巧淫技1](http://www.jianshu.com/p/50b63a221f09) - TableView不显示没内容的Cell怎么办;  app不流畅:[KMCGeigerCounter](https://github.com/kconner/KMCGeigerCounter);   ---- (Star:1,869) (Fork:234) (Watch:57)  
* [CSStickyHeaderFlowLayout](https://github.com/jamztang/CSStickyHeaderFlowLayout) CollectionView实现悬停的header   ---- (Star:4,789) (Fork:603) (Watch:146)  
* [iOS开发的一些奇巧淫技2](http://www.jianshu.com/p/08f194e9904c) -  用一个pan手势来代替UISwipegesture的各个方向、拉伸图片、播放GIF、上拉刷新、把tableview里cell的小对勾的颜色改变、navigationbar弄成透明的而不是带模糊的效果、改变uitextfield placeholder的颜色和位置。
* [cocoapods安装指南](http://code4app.com/article/cocoapods-install-usage) - cocoapods安装指南。
* [RemoteControl](https://github.com/johnno1962/Remote) - Control your iPhone from inside Xcode for end-to-end testing 。   ---- (Star:648) (Fork:28) (Watch:16)  
* [MVVM 介绍](http://objccn.io/issue-13-1/) - 替换MVC的开发模式。
* [第三方接口](http://apistore.baidu.com/astore/index) - 基本所有第三方接口都在这，再也不用那么麻烦去找了。
* [提高iOS开发效率的方法和工具](http://yyny.me/ios/%E6%8F%90%E9%AB%98iOS%E5%BC%80%E5%8F%91%E6%95%88%E7%8E%87%E7%9A%84%E6%96%B9%E6%B3%95%E5%92%8C%E5%B7%A5%E5%85%B7/) - 提高iOS开发效率的方法和工具。
* [禅与 Objective-C 编程艺术](https://github.com/oa414/objc-zen-book-cn) - 禅与 Objective-C 编程艺术 （Zen and the Art of the Objective-C Craftsmanship 中文翻译）。   ---- (Star:2,764) (Fork:681) (Watch:156)  
* [Objective-C编码规范：26个方面解决iOS开发问题](http://www.imooc.com/article/1216) - 【Objective-C编码规范：26个方面解决iOS开发问题：“我们制定Objective-C编码规范的原因是我们能够在我们的书，教程和初学者工具包的代码保持优雅和一致。”今天分享的规范来自raywenderlich.com团队成员共同完成的，希望对学习OC的朋友们有所指导和帮助。
* [demo](https://github.com/coolnameismy/demo) 刘彦玮的技术博客中文章对应的demo   ---- (Star:473) (Fork:233) (Watch:42)  
* [awesome-growth](https://github.com/phodal/awesome-growth) IT技能图谱   ---- (Star:232) (Fork:58) (Watch:25)  
* [ios_core_animation_advanced_techniques](https://github.com/ZsIsMe/ios_core_animation_advanced_techniques) 核心动画学习资料 [其中的核心动画电子书](https://zsisme.gitbooks.io/ios-/content/)   ---- (Star:454) (Fork:115) (Watch:22)  
* [Apple-OfficialTranslation-SourceAnnotation](https://github.com/CustomPBWaters/Apple-OfficialTranslation-SourceAnnotation) Apple官方译文框架源码注解，当你「了解权威 & 进阶原理」的时候，网搜的众多中 ~ ~（自行脑补）。一劳永逸，渐进式学习。 以简化初学者入门和老司机回顾的繁索过程，尽快切入主题，快速使用起来。   ---- (Star:447) (Fork:91) (Watch:28)  
* [RuntimeBrowser](https://github.com/nst/RuntimeBrowser) This is a class browser for the Objective-C runtime on iOS and OS X.   ---- (Star:2,395) (Fork:373) (Watch:149)  

#### 他人开源总结@

* [awesome-ios](https://github.com/vsouza/awesome-ios) 一个非常棒👍👍👍 的开源库集合.   ---- (Star:22,191) (Fork:3,749) (Watch:1,334)  
* [awesome-osx](https://github.com/iCHAIT/awesome-osx) - 一个非常棒👍👍👍的Mac OS X开源库集合。   ---- (Star:6,729) (Fork:515) (Watch:276)  
* [awesome-ios-ui](https://github.com/cjwirth/awesome-ios-ui) - 收集了不少 iOS UI/UX 库, 包含了很多酷炫的动画效果。   ---- (Star:9,798) (Fork:1,222) (Watch:660)  
* [awesome-mac](https://github.com/jaywcjlove/awesome-mac)  Mac软件、开发工具、设计工具集合   ---- (Star:15,100) (Fork:1,774) (Watch:724)  
* [ios-cosmos](http://www.ios-cosmos.com/) - The iOS Cosmos：收录了iOS绝大部分的开源框架和工具。
* [Awesome Haskell资料大全](https://haskell.zeef.com/konstantin.skipor#block_28362_basics) -    Awesome Haskell 资料大全：框架，库和软件。
* [Cosmos](http://ios-cosmos.com) - The iOS Cosmos：收录了IOS绝大部分的开源框架和工具。
* [cocoacontrols](https://www.cocoacontrols.com/) -  收集了很多UI控件效果代码，缺点是需要翻墙，而且代码分类不够好。
* [lexrus](https://github.com/lexrus) -  lexrus国内出名的iOS开源coder，非常酷的label动画、textfield动画。
* [适合iOS开发者的15大网站推荐](http://www.csdn.net/article/2015-03-04/2824108-ios-developers-sites) -  适合 iOS 开发者的 15 大网站推荐 --- 英文网站。
* [Objective-C GitHub 排名前 100 项目简介](https://github.com/Aufree/trip-to-iOS/blob/master/Top-100.md) -  主要对当前 GitHub 排名前 100 的项目做一个简单的简介, 方便初学者快速了解到当前 Objective-C 在 GitHub 的情况。   ---- (Star:7,213) (Fork:2,289) (Watch:800)  
* [Github-iOS备忘](http://github.ibireme.com/github/list/ios/) -整理了比较常用的iOS第三方组件，以及github上的统计。
* [超全！整理常用的iOS第三方资源](http://www.cocoachina.com/ios/20160121/14988.html) - 超全！整理常用的iOS第三方资源。
* [MyGithubMark](https://github.com/JanzTam/MyGithubMark) - Github上的iOS资料-个人记录（持续更新）。   ---- (Star:135) (Fork:44) (Watch:13)  
* [Github 上的 iOS 开源项目](http://ios.jobbole.com/84684/) - Github 上的 iOS 开源项目总结。
* [iOS资源大全中文版](https://github.com/jobbole/awesome-ios-cn) - iOS资源大全中文版。   ---- (Star:2,625) (Fork:765) (Watch:245)  
* [LearningIOS](https://github.com/zhouhuanqiang/LearningIOS) Learning materials of iOS   ---- (Star:1,182) (Fork:483) (Watch:102)  
* [Dev-Repo](https://github.com/DevDragonLi/Dev-Repo) 学习经验、面试题等集合.   ---- (Star:64) (Fork:20) (Watch:3)  
* [awesome-github](https://github.com/AntBranch/awesome-github) - awesome-github:收集这个列表，只是为了更好地使用亲爱的GitHub。   ---- (Star:1,332) (Fork:401) (Watch:126)  

#### 开发博客列表@

* [Halfrost-Field](https://github.com/halfrost/Halfrost-Field) iOS学习博客.   ---- (Star:659) (Fork:161) (Watch:40)  
* [唐巧整理](https://github.com/tangqiaoboy/iOSBlogCN) - 猿题库唐巧整理.   ---- (Star:4,428) (Fork:1,246) (Watch:481)  
* [11个超棒的iOS开发学习国外网站](http://www.cocoachina.com/ios/20150626/11348.html) - 11个超棒的iOS开发学习网站:[objc.io](https://www.objc.io) ;[subjc.com](http://subjc.com) ;[NSHipster](http://nshipster.com) ;[Peter Steinberger](http://petersteinberger.com) ;[Ole Begemann](http://oleb.net) ;[Florian Kugler](http://floriankugler.com) ;[NSBlog](https://www.mikeash.com/pyblog/) ;[Cocoa](http://cocoa.tumblr.com) ;[iOS Dev Weekly](http://iosdevweekly.com) ;[iOS Developer Tips](http://iosdevelopertips.com) ;[iOS Goodies](http://ios-goodies.com) ;[AppCoda](http://www.appcoda.com) 香港人创建;[Krzysztof Zab?ocki](http://merowing.info) ;[iOS Development tips](http://iosdevtips.co) ;

博客地址 | RSS地址
----- | -----
[南峰子的技术博客](http://southpeak.github.io/) | 南峰子的技术博客。
[唐巧的技术博客](http://blog.devtang.com) | <http://blog.devtang.com/atom.xml>
[OneV's Den](https://onevcat.com) | <https://onevcat.com/atom.xml>
[objc 中国](http://objccn.io/) | 为中国 Objective-C 社区带来最佳实践和先进技术。
[破船之家](http://beyondvincent.com) | <http://beyondvincent.com/atom.xml>
[NSHipster](http://nshipster.cn) | <http://nshipster.cn/feed.xml>
[Limboy 无网不剩](http://limboy.me/) | <http://feeds.feedburner.com/lzyy>
[Lex iOS notes](http://lextang.com) | <http://ios.lextang.com/rss>
[念茜的博客](http://nianxi.net) | <http://nianxi.net/feed.xml>
[Xcode Dev](http://blog.xcodev.com) | <http://blog.xcodev.com/atom.xml>
[Ted's Homepage](http://wufawei.com/)| <http://wufawei.com/feed>
[txx's blog](http://blog.t-xx.me) | <http://blog.t-xx.me/atom.xml>
[KEVIN BLOG](http://imkevin.me) | <http://imkevin.me/rss>
[阿毛的蛋疼地](http://xiangwangfeng.com/) | <http://xiangwangfeng.com/atom.xml>
[亚庆的 Blog](http://billwang1990.github.io) | <http://billwang1990.github.io/atom.xml>
[Nonomori](http://nonomori.farbox.com) | <http://nonomori.farbox.com/feed>
[言无不尽](http://tang3w.com) | <http://tang3w.com/atom.xml>
[Wonderffee's Blog](http://wonderffee.github.io) | <http://wonderffee.github.io/atom.xml>
[I'm TualatriX](http://imtx.me) | <http://imtx.me/feed/latest/>
[vclwei](http://www.vclwei.com/) | <http://www.vclwei.com/posts.rss>
[Cocoabit](http://blog.cocoabit.com) | <http://blog.cocoabit.com/atom.xml>
[nixzhu on scriptogr.am](http://nixzhu.me) | <http://nixzhu.me/feed>
[不会开机的男孩](http://studentdeng.github.io) | <http://studentdeng.github.io/atom.xml>
[Nico](http://www.taofengping.com) | <http://www.taofengping.com/rss.xml>
[阿峰的技术窝窝](http://hufeng825.github.io) | <http://hufeng825.github.io/atom.xml>
[answer_huang](http://answerhuang.duapp.com) | <http://answerhuang.duapp.com/index.php/feed/>
[webfrogs](http://webfrogs.me) | <http://webfrogs.me/feed/>
[代码手工艺人](http://joeyio.com) | <http://joeyio.com/atom.xml>
[Lancy's Blog](http://gracelancy.com) | <http://gracelancy.com/atom.xml>
[I'm Allen](http://imallen.com/) | <http://imallen.com/atom.xml>
[Travis' Blog](http://imi.im/)| <http://imi.im/feed>
[王中周的技术博客](http://wangzz.github.io/) |<http://wangzz.github.io/atom.xml>
[会写代码的猪](http://jiajun.org/)|<http://gaosboy.com/feed/atom/>
[克伟的博客](http://wangkewei.cnblogs.com/)|<http://feed.cnblogs.com/blog/u/23857/rss>
[摇滚诗人](http://www.cnblogs.com/biosli)|<http://feed.cnblogs.com/blog/u/35410/rss>
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
[ibireme伽蓝之堂](http://blog.ibireme.com/) | <http://blog.ibireme.com/feed/>

#### CodeLiararyWebSite@

* [pttrns](http://pttrns.com/) iOS各种源码

#### 学习笔记@

* [iOS-Note](https://github.com/seedante/iOS-Note)A@ 非常好的学习笔记，主要目录1.Core Data 笔记2.Photos 笔记3.转场动画详解4.自定义容器控制器转场5.交互式动画   ---- (Star:560) (Fork:101) (Watch:36)  

#### 设计@

* [design-resource](https://github.com/timmy3131/design-resource) 设计师资源列表   ---- (Star:1,376) (Fork:1,484) (Watch:269)  
* [Reveal：分析iOS UI的利器](http://revealapp.com/)
* [Reveal-Plugin-for-XCode](https://github.com/shjborage/Reveal-Plugin-for-XCode) - 一个Reveal插件，可以使工程不作任何修改的情况下使用Reveal，该插件已在Alcatraz上架。   ---- (Star:236) (Fork:35) (Watch:8)  

#### 物联网@

* [awesome-iot](https://github.com/phodal/awesome-iot) - 这份物联网学习参考大全太给力。从物联网协议、嵌入式系统、相关开源库、相关书籍、博客、学习笔记、标准应有尽有。   ---- (Star:1,243) (Fork:298) (Watch:152)  

#### mac@

* [radiant-player-mac](https://github.com/radiant-player/radiant-player-mac) 一个Google Play音乐转换成与Mac整合的独立，美观的mac音乐播放器。   ---- (Star:3,009) (Fork:292) (Watch:106)  
* [DevDataTool](https://github.com/MxABC/DevDataTool) OSX系统 转换、加解密工具   ---- (Star:147) (Fork:5) (Watch:2)  
* [LuLu](https://github.com/objective-see/LuLu) 防火墙 LuLu is the free open-source macOS firewall that aims to block unauthorized (outgoing) network traffic   ---- (Star:327) (Fork:20) (Watch:30)  
* [WeChatPlugin-MacOS](https://github.com/TKkk-iOSer/WeChatPlugin-MacOS) mac OS版微信小助手 功能: 自动回复、消息防撤回、远程控制、微信多开   ---- (Star:2,201) (Fork:263) (Watch:89)  
* [WeChatTweak-macOS](https://github.com/Sunnyyoung/WeChatTweak-macOS) A dynamic library tweak for WeChat macOS - 微信 macOS 客户端撤回拦截与多开   ---- (Star:1,277) (Fork:126) (Watch:47)  

#### 深度学习@

* [TrafficLights-DeepLearning-iOS](https://github.com/asavihay/TrafficLights-DeepLearning-iOS) 利用Caffe深度学习执着的一个交通灯信号检测App   ---- (Star:86) (Fork:25) (Watch:2)  

#### 未分类@

* [Form](https://github.com/hyperoslo/Form) Form 是一个方便开发者创建表单填写工作的 UI 库。   ---- (Star:1,587) (Fork:135) (Watch:66)  

#### 参考@

* [说明](说明) 此库是完全开源收集整理，服务于广大iOS开发工作者的开源集合资料库，欢迎大家踊跃贡献.
* [awesome-github](https://github.com/AntBranch/awesome-github) A curated list of awesome GitHub guides, articles, sites, tools, projects and resources. 收集这个列表，只是为了更好地使用亲爱的GitHub,欢迎提交pr和issue。   ---- (Star:1,332) (Fork:401) (Watch:126)  

#### 其他领域@

* [freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp) 非常棒👍👍👍  We’re a community that helps you learn to code, then get experience by contributing to open source projects used by nonprofits.   ---- (Star:291,303) (Fork:12,948) (Watch:8,471)  
* [You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS) A book series on JavaScript. @YDKJS on twitter.   ---- (Star:69,333) (Fork:12,083) (Watch:3,736)  
* [bootstrap](https://github.com/twbs/bootstrap) Bootstrap 的 Github 帐户，著名的响应式网页设计框架。主要提供技术信息，还提供其他有用站点的其他链接。如果你正在寻找有关框架的更详细的文档，可以访问. Bootstrap is a free front-end framework for faster and easier web development. Bootstrap includes HTML and CSS based design templates for typography, forms, buttons, tables, navigation, modals, image carousels and many other, as well as optional JavaScript plugins   ---- (Star:117,177) (Fork:55,063) (Watch:7,122)  
* [wiki](https://github.com/d3/d3/wiki) D3 (Data-Driven Documents or D3.js) is a JavaScript library for visualizing data using web standards.   ---- (Star:69,463) (Fork:18,033) (Watch:3,497)  
* [awesome-python](https://github.com/vinta/awesome-python) A curated list of awesome Python frameworks, libraries, software and resources   ---- (Star:40,211) (Fork:7,679) (Watch:3,512)  
* [You-Dont-Need-jQuery](https://github.com/oneuijs/You-Dont-Need-jQuery) 专注于使用 vanilla JavaScript 解决典型的编程问题，这个仓库的兴起与 React 的兴起密切相关； Examples of how to do query, style, dom, ajax, event etc like jQuery with plain javascript.   ---- (Star:12,327) (Fork:1,099) (Watch:463)  
* [public-apis](https://github.com/toddmotto/public-apis) 经常更新的web开发公共JSON API 列表。 A collective list of public JSON APIs for use in web development.   ---- (Star:28,957) (Fork:2,551) (Watch:1,000)  

#### 开发环境@

* [Homebrew](https://github.com/Homebrew/brew) Homebrew是一款Mac OS平台下的软件包管理工具，拥有安装、卸载、更新、查看、搜索等很多实用的功能。简单的一条指令，就可以实现包管理，而不用你关心各种依赖和文件路径的情况，十分方便快捷。   ---- (Star:9,409) (Fork:2,351) (Watch:415)  
