Android笔记
==

## Android Widgets

- [Android控件](https://github.com/xieyangxuejun/AndroidNote/blob/master/android_widgets.md)

技术框架
--

### 图片加载
* [Glide](https://github.com/bumptech/glide)
* [Fresco](http://fresco-cn.org/)
* [Volley](https://android.googlesource.com/platform/frameworks/volley)
* [Picasso](http://square.github.io/picasso/)
* [Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader)

### 网络请求
* [okhttp](http://square.github.io/okhttp/)
* [retrofit](http://square.github.io/retrofit/)
* [Volley](http://developer.android.com/intl/zh-cn/training/volley/index.html)
* [android-async-http](http://loopj.com/android-async-http/)

### 数据库ORM
* [OrmLite](http://ormlite.com/)
* [greenDAO](http://greenrobot.org/greendao/)
* [sugar](http://satyan.github.io/sugar/)
* [realm](https://github.com/realm/realm-java)
* [sqlbrite](https://github.com/square/sqlbrite)

### Json解析
* [gson](https://github.com/google/gson)
* [fastjson](https://github.com/alibaba/fastjson)
* [jackson](https://github.com/FasterXML/jackson)

### 常用工具
* [AndroidCommon](https://github.com/xieyangxuejun/AndroidCommon)
* [android-common](https://github.com/Trinea/android-common)
* [android-common](https://github.com/litesuits/android-common)

### 依赖注入
* [Dagger 2](http://google.github.io/dagger/)
* [Butter Knife](http://jakewharton.github.io/butterknife/)
* [RoboGuice](https://github.com/roboguice/roboguice)
* [AndroidAnnotations](http://androidannotations.org/)

### 快速开发
* [afinal](https://github.com/yangfuhai/afinal)
* [xUtils3](https://github.com/wyouflf/xUtils3)
* [ThinkAndroid](https://github.com/white-cat/ThinkAndroid)
* [LoonAndroid3](https://github.com/gdpancheng/LoonAndroid3)
* [KJFrameForAndroid](https://github.com/kymjs/KJFrameForAndroid)

### 动态加载
* [dynamic-load-apk](https://github.com/singwhatiwanna/dynamic-load-apk)
* [DynamicAPK](https://github.com/CtripMobile/DynamicAPK)
* [DroidPlugin](https://github.com/Qihoo360/DroidPlugin)
* [AndroidDynamicLoader](https://github.com/mmin18/AndroidDynamicLoader)
* [android-pluginmgr](https://github.com/houkx/android-pluginmgr)
* [DroidPlugin](https://github.com/DroidPluginTeam/DroidPlugin)
* [ACDD](https://github.com/bunnyblue/ACDD)

### 热修复
* [AndFix](https://github.com/alibaba/AndFix)
* [Xposed](https://github.com/rovo89/Xposed)
* [dexposed](https://github.com/alibaba/dexposed)
* [HotFix](https://github.com/dodola/HotFix)
* [Nuwa](https://github.com/jasonross/Nuwa)
* [DroidFix](https://github.com/bunnyblue/DroidFix)
* [RocooFix](https://github.com/dodola/RocooFix)
* [Legend](https://github.com/asLody/legend)
* [Tinker](https://github.com/Tencent/tinker)
* [Robust](https://github.com/Meituan-Dianping/Robust)

### 事件总线
* [EventBus](http://greenrobot.org/eventbus/)
* [Otto](http://square.github.io/otto/)

### 性能工具
* [LeakCanary](https://github.com/square/leakcanary)
* [ACRA](https://github.com/ACRA/acra)

### 图表
* [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)
* [WilliamChart](https://github.com/diogobernardino/WilliamChart)
* [HelloCharts](https://github.com/lecho/hellocharts-android)

### 响应式编程
* [RxJava](https://github.com/ReactiveX/RxJava)
* [RxAndroid](https://github.com/ReactiveX/RxAndroid)
* [Agera](https://github.com/google/agera)
* [RxBinding](https://github.com/JakeWharton/RxBinding)

### 日志框架
* [Logger](https://github.com/orhanobut/logger)
* [Timber](https://github.com/JakeWharton/timber)

## Android架构

### MVVM&&MVP&&MVC

- [android-boilerplate](https://github.com/ribot/android-boilerplate)(基于MVP的完整架构，Dagger2+Retrofit+RxJava ,参考链接[Android Application Architecture](https://medium.com/ribot-labs/android-application-architecture-8b6e34acda65),对应中文翻译[Android Application Architecture中文翻译](http://www.jianshu.com/p/8ca27934c6e6))

-  [Archi](https://github.com/ivacf/archi)（同一个app，分别利用MVP，MVVM，以及标准模式实现。）


-  [ANDROID DATABINDING: GOODBYE PRESENTER, HELLO VIEWMODEL](http://tech.vg.no/2015/07/17/android-databinding-goodbye-presenter-hello-viewmodel/)

（viewmodel，安卓中的databinding）

-  [MVVM-in-Android](http://www.codeproject.com/Articles/166952/MVVM-in-Android)（android中的mvvm）


-  [ ZhiHuMVP github 地址](https://github.com/CameloeAnthony/ZhiHuMVP)（MVP架构思想，Retrofit RESTful API 框架的配合，RxJava 响应式编程）


-  [ androidmvp github地址](https://github.com/antoniolg/androidmvp)（star2000+的MVP实例）


-  [MVP for Android: how to organize the presentation layer](http://antonioleiva.com/mvp-android/)（上面这个github对应的文章）


-  [ Introduction-to-Model-View-Presenter-on-Android](https://github.com/konmik/konmik.github.io/wiki/Introduction-to-Model-View-Presenter-on-Android)（MVP的介绍，MVP必读经典）


-  [Introduction-to-Model-View-Presenter-on-Android 中文翻译版](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2015/0425/2782.html)


-  [ActivityFragmentMVP github地址](https://github.com/spengilley/ActivityFragmentMVP)（MVP处理Activity和Fragment，使用了Dagger 注入）


-  [ EffectiveAndroidUI github地址](https://github.com/pedrovgs/EffectiveAndroidUI)（star 3000+的mvp，mvvm实例）


-  [ MvpCleanArchitecture github地址](https://github.com/glomadrian/MvpCleanArchitecture)（使用clean architecture 和mvp的实例）


-  [ Material-Movies github地址](https://github.com/saulmm/Material-Movies)（ 使用material design +MVP实现的Material-Movies）


-  [EffectiveAndroid github地址](https://github.com/rallat/EffectiveAndroid)（MVP+clean Architecture 项目）


-  [AndroidMVPDemo github地址](https://github.com/CameloeAnthony/AndroidMVPDemo)（本文作者MVP demo github地址）


-  [MVVM on Android: What You Need to Know](http://willowtreeapps.com/blog/mvvm-on-android-what-you-need-to-know/)(MVVM介绍，这个博客很不错)


-  [data-bingding guide](https://developer.android.com/tools/data-binding/guide.html)（data-binding guide官网）


-  [Android应用开发架构概述](http://www.liuguangli.win/archives/299)


-  [MVVM介绍](http://objccn.io/issue-13-1/)（iOS中MVVM的一种实现，对概念的理解有帮助）


-  [Android Architecture](https://medium.com/android-news/android-architecture-2f12e1c7d4db#.ta695te6a)（区分andrtoid项目中的MVVM，MVP，MVC）


-  [Web开发的MVVM模式](http://www.cnblogs.com/dxy1982/p/3793895.html)（web开发中的MVC VS. MVP VS. MVVM）


-  [M — Model in MVC, MVP, MVVC in Android](https://medium.com/@artem_zin/m-model-from-mvc-mvp-in-android-flow-and-mortar-bd1e50c45395#.5kbw4q5psd)（android工程MVC，MVVC，MVVM中的Model角色讲解）


-  [Android MVP架构中的Presentation层应该怎么设计](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=402868193&idx=1&sn=790e12f84dfcea171528e6d3789c69ed#rd)（如果你面临部分代码不知道放到Presentation层还是UI层的问题，甚至你不知道某段代码是否属于业务代码。不知道如何分清MVP中的代码职责，参考这篇文章）
-  [MVVM_Android-CleanArchitecture](http://rocko.xyz/2015/11/07/MVVM_Android-CleanArchitecture/)(MVVM+CleanArchitecture实现，)

###官方架构

- [googlesamples/android-architecture](https://github.com/googlesamples/android-architecture)（google官方android架构项目）

###国内平台

- [App工程结构搭建：几种常见Android代码架构分析](http://www.uml.org.cn/mobiledev/201310211.asp)
-  [携程Mobile架构演化(视频)](http://www.infoq.com/cn/presentations/ctrip-mobile-architecture-evolution)
- [携程Android App插件化和动态加载实践](http://www.infoq.com/cn/articles/ctrip-android-dynamic-loading)
- [携程移动端架构演进与优化之路](http://geek.csdn.net/news/detail/108167)
-  [陶钧谈淘宝客户端应用框架实践](http://www.infoq.com/cn/interviews/tj-taobao-client-arch)
- [QCon旧金山演讲总结：阿里无线技术架构演进](http://www.infoq.com/cn/articles/alibaba-mobile-infrastructure)
- [手机淘宝构架演化实践](http://www.infoq.com/cn/news/2014/12/taobao-app-evolution)
- [手机淘宝Android客户端架构](http://www.open-open.com/lib/view/open1436316754208.html)
- [漫谈移动应用架构设计](http://club.alibabatech.org/resource_detail.htm?topicId=124)
- [大规模团队的Android开发](http://club.alibabatech.org/resource_detail.htm?topicId=130)

-  [支付宝钱包客户端技术架构](http://club.alibabatech.org/resource_detail.htm?topicId=155)


-  [手机百度Android平台平台化解决方案](http://www.infoq.com/cn/presentations/mobile-baidu-android-platform-solutions)


-  [涅盘新生—Android QQ音乐架构演进](http://www.infoq.com/cn/presentations/evolution-of-android-qq-music-architecture)


-  [微信Android客户端架构演进之路](http://www.infoq.com/cn/articles/wechat-android-app-architecture)


-  [饿了么移动APP的架构演进](https://mp.weixin.qq.com/s?__biz=MzAxNDUwMzU3Mw==&mid=401044540&idx=1&sn=24b7d8fb655ae6dd5d989d0cb3c08e90&scene=2&srcid=0106EtxRjD2jHxzomxVPTwY3&from=timeline&isappinstalled=0&uin=NzgwODIwNDgw&key=&devicetype=webwx&version=70000001&lang=zh_CN&pass_ticket=46hW44w3Hxd7VY9rutz7mgLu1JGe2T1AAKNQpxNoYOSGi8NpmNYr%2BAZj%2BiXtRX2F)
-  [糯米移动组件架构演进之路](https://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112195&idx=1&sn=27fa638e90b09a107057e4a5e8d01ab1&scene=0&key=b28b03434249256bfa802f640871a1d36fcc58d62fbdae43d4cf0bb232988312ebd980373392cdb72dff355da09201bf&ascene=0&uin=Mjc3OTU3Nzk1&devicetype=iMac+MacBookPro10%2C1+OSX+OSX+10.10.5+build%2814F1713%29&version=11020201&pass_ticket=fVNELMIhboNqtKbXT0UAQtJy1MNge%2F0s6VqFTdnuSJvfHsNGCxh1X%2FVk7UdXna7W)
-  [英语流利说 Android 架构演进](http://mp.weixin.qq.com/s?__biz=MzI0NjIzNDkwOA==&mid=2247483673&idx=1&sn=ba9cf498ab78646f1a9c9e711f65c360&scene=2&srcid=0527JyTxU6ucKtlLVyl7REaB&from=timeline&isappinstalled=0#wechat_redirect)
-  [七牛云存储-千万级用户的 ANDROID 客户端是如何养成的](http://blog.qiniu.com/archives/6017) 
-  [微信Android客户端后台保活经验分享](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403254393&idx=1&sn=8dc0e3a03031177777b5a5876cb210cc&scene=1&srcid=0402fANUWIotbVLECw4Ytz4K#wechat_redirect)
-  [微信Android客户端架构演进之路](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=401921778&idx=1&sn=f05433ff53199999f9dc2acb3b249ac3&scene=21#wechat_redirect) 
-  [QQ空间直播秒开优化实践](https://mp.weixin.qq.com/s?__biz=MzI1MTA1MzM2Nw==&mid=2649796799&idx=1&sn=42061b7d021b8d8fba00202286cd9372&scene=1&srcid=06229jXN0bm1drO2Eckf9iAG&key=77421cf58af4a653d7ef81b351f58a7ebbe2903e873c2c7904d6a74bac0fb11b65ef1dd3a278cc35a3563229c548766b&ascene=0&uin=MTYzMjY2MTE1&devicetype=iMac+MacBookPro10%2C1+OSX+OSX+10.11.5+build(15F34)&version=11020201&pass_ticket=3vGrz7MTtJUi6HBVB4E0etQLjdXe6h6iiZ0lDZpD27c%3D) 

###设计模式

-  [Software design pattern on android](http://www.slideshare.net/PedroVicenteGmezSnch/software-design-patterns-on-android)（安卓中的设计模式，英文ppt）


-  强烈推荐书籍《Android 源码设计模式解析与实战》

###其他

-  [AndroidTDDBootStrap Github地址](https://github.com/Piasy/AndroidTDDBootStrap)（AndroidTDDBootStrap 是一个Android TDD 引导项目，使用一些新技术，灵感来自于一些最流行的框架，有许多方便的开发工具，遵循最佳实践。）
-  [Design for Offline: Android App Architecture Best Practices](https://plus.google.com/+AndroidDevelopers/posts/3C4GPowmWLb)


-  [Robust and readable architecture for an Android App](http://blog.joanzapata.com/robust-architecture-for-an-android-app/)


-  [知乎：Android 开发有什么好的架构么?](https://www.zhihu.com/question/21406685)
-  [知乎：如果从0创建一个Android APP，设计思路是什么？（架构、activity、layout等复用性的考虑），感觉无从下手](https://www.zhihu.com/question/28564947)

-  Clean Architecture

  -  [The Clean Architecture](https://blog.8thlight.com/uncle-bob/2012/08/13/the-clean-architecture.html)(clean architecture出处)


  -  [Architecting Android…The evolution](http://fernandocejas.com/2015/07/18/architecting-android-the-evolution/)


  -  [Architecting Android…The evolution中文翻译](http://www.devtf.cn/?p=1083)


  -  [MvpCleanArchitecture github地址](https://github.com/glomadrian/MvpCleanArchitecture)（使用clean architecture 和mvp的实例）


  -  [EffectiveAndroid github地址](https://github.com/rallat/EffectiveAndroid)（MVP+clean Architecture 项目）


  -  [Rosie](https://github.com/Karumi/Rosie)（利用Clean Architecture搭建的安卓框架）


  -  [A detailed guide on developing Android apps using the Clean Architecture pattern](https://medium.com/@dmilicic/a-detailed-guide-on-developing-android-apps-using-the-clean-architecture-pattern-d38d71e94029)(使用Clean Architecture的基础性文章，对应翻译 [在Android应用中使用Clean架构 ](http://blog.chengdazhi.com/index.php/101))

- Flux

  -  [flux](https://github.com/facebook/flux)(flux 官方github地址)
  - [flux and android](https://armueller.github.io/android/2015/03/29/flux-and-android.html)
  - [rxflux android architecture](https://medium.com/swlh/rxflux-android-architecture-94f77c857aa2#.sfjwchwok)
  - [why rxflux](https://medium.com/swlh/why-rxflux-5b687f062709#.ltlnlr4cl)
  - [android flux todo app](https://github.com/lgvalle/android-flux-todo-app)([中文翻译](http://www.devtf.cn/?p=1028))
  - [RxFlux](https://github.com/skimarxall/RxFlux)（RxFlux是一个遵从Flux设计规范，并添加RxJava支持的架构项目）
  - [android-flux-todo-app](https://github.com/lgvalle/android-flux-todo-app)(示例代码，利用Facebook的Flux实现TODO项目)
  - [flux-comparison](https://github.com/voronianski/flux-comparison)(各种flux实现对比)

- 架构心得体会系列：

  - [Android APP架构心得](http://www.jianshu.com/p/2d5c1d855c31)
  - [Android App的设计架构：MVC,MVP,MVVM与架构经验谈](http://android.jobbole.com/82578/)

##博客社区

### 个人博客
* [老罗的Android之旅](http://blog.csdn.net/luoshengyang)
* [泡在网上的日子](http://www.jcodecraeer.com/)
* [Trinea](http://www.trinea.cn/)
* [郭霖](http://blog.csdn.net/guolin_blog)
* [夏安明](http://blog.csdn.net/xiaanming)
* [鸿阳](http://blog.csdn.net/lmj623565791)
* [任玉刚](http://blog.csdn.net/singwhatiwanna)
* [云在千峰](http://blog.chengyunfeng.com/)
* [胡凯](http://hukai.me/)
* [stormzhang](http://stormzhang.com/)
* [马天宇](https://github.com/litesuits)
* [江清清的技术专栏](http://www.lcode.org/)
* [阮一峰的网络日志](http://www.ruanyifeng.com/blog/)
* [张涛-开源实验室](http://blog.kymjs.com/)
* [谢权SELF](https://xiequan.info/)
* [Mr.Simple](http://blog.csdn.net/bboyfeiyu)
* [技术小黑屋](http://droidyue.com/)
* [Drakeet的个人博客](https://drakeet.me/)
* [eclipse_xu](http://blog.csdn.net/eclipsexys)
* [子墨博客](http://blog.csdn.net/ElinaVampire)
* [巫山老妖](http://blog.csdn.net/wwj_748)
* [AigeStudio](http://blog.csdn.net/aigestudio)
* [雨松MOMO程序研究院](http://www.xuanyusong.com/)
* [包建强](http://blog.csdn.net/jspandasp)
* [邓凡平](http://blog.csdn.net/innost)
* [hujiaweibujidao](http://hujiaweibujidao.github.io/)
* [何红辉](http://blog.csdn.net/bboyfeiyu)
* [Piasy](http://blog.piasy.com/)
* [元斌](http://blog.csdn.net/qibin0506)
* [赵四](http://blog.csdn.net/jiangwei0910410003)
* [weishu](http://weishu.me/)
* [严振杰](http://blog.csdn.net/yanzhenjie1003)
* [切问录](http://www.fuzihao.org/blog/)
* [猴子搬来的救兵](http://blog.csdn.net/mynameishuangshuai)
* [markzhai](http://blog.zhaiyifan.cn/)
* [兰亭风雨](http://blog.csdn.net/ns_code)
* [谦虚的天下](http://www.cnblogs.com/qianxudetianxia/)
* [工匠若水](http://blog.csdn.net/yanbober)
* [diygreen](http://www.jianshu.com/u/0ad0a0afc409)
* [VERYYOUNG](http://veryyoung.me/)
* [左飞](http://blog.csdn.net/baimafujinji)
* [Frodo](http://frodoking.github.io/)
* [青峰](http://www.fqxyi.com/)
* [拉丁吴](http://www.jianshu.com/u/1d8042233f67)
* [Carson_Ho](http://blog.csdn.net/carson_ho)
* [Gityuan](http://gityuan.com/)
* [GcsSloop](http://www.gcssloop.com/)
* [吴小龙同学](http://wuxiaolong.me/)

### 团队博客
* [Android官方技术博客](http://android-developers.blogspot.com/)
* [美团点评技术团队](http://tech.meituan.com/)
* [腾讯全端 AlloyTeam 团队](http://www.alloyteam.com/)
* [腾讯大讲堂](http://djt.qq.com/)
* [奇迹空间技术学习小组](http://blog.qiji.tech/)
* [Square](https://corner.squareup.com/)
* [Facebook](https://code.facebook.com/)
* [腾讯游戏安全实验室](http://gslab.qq.com/)
* [腾讯Bugly社区](http://bugly.qq.com/bbs/portal.php)
* [DEV CLUB](http://dev.qq.com/)
* [腾讯Gad](http://gad.qq.com/program)

### 技术社区
* [CSDN](http://www.csdn.net/)
* [博客园](http://www.cnblogs.com/)
* [ITEYE](http://www.iteye.com/)
* [51CTO](http://www.51cto.com/)
* [开源中国](http://www.oschina.net/)
* [Linux公社](http://www.linuxidc.com/)
* [EOE](http://www.eoeandroid.com/)
* [CocoaChina](http://www.cocoachina.com/)
* [深度开源](http://www.open-open.com/)
* [伯乐在线](http://blog.jobbole.com/)
* [ImportNew](http://www.importnew.com/)
* [稀土掘金](http://gold.xitu.io/)
* [IMB developerWorks](http://www.ibm.com/developerworks/cn/)
* [segmentfault](https://segmentfault.com/)
* [InfoQ](http://www.infoq.com/cn/)
* [ChinaUnix](http://blog.chinaunix.net/)
* [ITPUB](http://blog.itpub.net/)
* [开发者头条](http://toutiao.io/)
* [Android安全中文站](http://www.droidsec.cn/)
* [菜鸟教程](http://www.runoob.com/)
* [V2EX](https://www.v2ex.com/)
* [FreeBuf](http://www.freebuf.com/)
* [Google开发者官方频道](http://i.youku.com/i/UMjczOTc0NDkzNg==)
* [GDG中国社区论坛](http://www.chinagdg.com/)
* [谷歌中国博客](http://developers.googleblog.cn)

### 技术周报
* [编程狂人](http://www.tuicool.com/mags/)
* [Android开发技术周报](http://androidweekly.cn/)
* [APP开发日报](http://app.memect.com/)
* [码农周刊](http://weekly.manong.io/issues/)
* [干货集中营](http://gank.io/history)
* [平安金融科技移动技术周报](http://www.jianshu.com/notebooks/2983917/latest)
* [Android博客周刊](http://androidblog.cn/)
* [Android Weekly](http://androidweekly.net/)

技术书籍
--

### 计算机基础
* [《计算机科学导论》](https://book.douban.com/subject/1142213/)  
  本书是大学计算机相关专业的基础课教材，涉及到计算机科学的各个方面。本书着重讲解基本概念而不是数学模型和技术细节，通过大量的图表和演示范例讲解计算机科学的基础知识。

* [《深入理解计算机系统》](https://book.douban.com/subject/5333562/)  
  本书从程序员的视角详细阐述计算机系统的本质概念，并展示这些概念如何实实在在地影响应用程序的正确性、性能和实用性。

### 操作系统
* [《现代操作系统》](https://book.douban.com/subject/3852290/)  
  本书是操作系统领域的经典之作，书中集中讨论了操作系统的基本原理，包括进程、线程、存储管理、文件系统、输入/输出、死锁等，同时还包含了有关计算机安全、多媒体操作系统、掌上计算机操作系统、微内核、多核处理机上的虚拟机以及操作系统设计等方面的内容。

* [《操作系统：精髓与设计原理》](https://book.douban.com/subject/5064311/)   
  本书不仅全面地讲述了操作系统的基本概念、原理和方法，还清楚地展现了当代操作系统的本质和特点。作者针对近几年操作系统领域的最新变化，对操作系统的设计原理进行深入的阐述，同时将其对操作系统整个领域全面而深入的理解呈现给读者。

### 体系结构
* [《计算机体系结构：量化研究方法》](https://book.douban.com/subject/20452387/)   
  本书是最权威的计算机体系结构著作，是久负盛名的经典作品。书中系统地介绍了计算机系统的设计基础、指令集系统结构、流水线和指令集并行技术、层次化存储系统与存储设备、互连网络以及多处理器系统等重要内容。

* [《计算机组成与设计：硬件/软件接口》](https://book.douban.com/subject/2110638/)  
  本书是计算机组成的经典教材。全书着眼于当前计算机设计中最基本的概念，展示了软硬件间的关系，并全面介绍当代计算机系统发展的主流技术和最新成就。

* [《计算机组成与体系结构：性能设计》](https://book.douban.com/subject/6398113/)  
  本书是介绍当代计算机体系主流技术和最新技术的优秀教材，以Intel x86和ARM两个处理器系列为例，深入讨论了计算机组成与体系结构的基本原理和概念，并将它们运用到当代计算机系统设计的问题中。

* [《计算机组成与体系结构》](https://book.douban.com/subject/1881545/)  
  本书系统介绍计算机组成与体系结构，主要内容包括：数字逻辑和数字系统、机器层次的数据表示方法、汇编层次的机器组织和结构、存储器的组成和结构、接口和通信、功能组织、多处理器和可供选择的其他结构、性能增强、网络结构和分布式计算机系统等。

* [《计算机组织与体系结构》](https://book.douban.com/subject/1737686/)  
  本书是介绍当代计算机体系主流技术的最新技术的优秀教材。作者以Intel Pentium 4和IBM/Motorola PowerPC作为考察实例，将当代计算机系统性能问题和计算机组织与体系结构的基本概念及原理紧密联系起来。

### 计算机网络
* [《计算机网络》](https://book.douban.com/subject/10510747/)  
  本书是国内外使用最广泛、最权威的计算机网络经典教材。全书按照网络协议模型自下而上（物理层、数据链路层、介质访问控制层、网络层、传输层和应用层）有系统地介绍了计算机网络的基本原理，并结合Internet给出了大量的协议实例。在讲述网络各层次内容的同时，还与时俱进地引入了最新的网络技术，包括无线网络、3G蜂窝网络、RFID与传感器网络、内容分发与P2P网络、流媒体传输与IP语音，以及延迟容忍网络等。

* [《计算机网络：自顶向下方法》](https://book.douban.com/subject/26176870/)  
  本书首创采用自顶向下的方法讲解计算机网络的原理和协议，出版以来已被几百所大学和学院选用，是业界最经典的计算机网络教材之一。

* [《深入理解计算机网络》](https://book.douban.com/subject/20560942/)  
  本书结合最新计算机网络技术，全面、系统、深入地阐述了计算机网络的体系结构、工作原理，以及各种通信协议实现原理，能满足读者系统和深入地学习和研究计算机网络技术的需求。

* [《TCP/IP详解 卷1：协议》](https://book.douban.com/subject/1088054/)  
  《TCP/IP详解·卷1：协议》是一本完整而详细的TCP/IP协议指南，描述了属于每一层的各个协议以及它们如何在不同操作系统中运行。

* [《TCP/IP详解 卷2：实现》](https://book.douban.com/subject/1087767/)  
  《TCP/IP详解·卷2：实现》完整而详细地介绍了TCP/IP协议是如何实现的。

* [《TCP/IP详解 卷3：TCP事务协议、HTTP、NNTP和UNIX域协议》](https://book.douban.com/subject/1058634/)  
  《TCP/IP详解·卷3：TCP事务协议、HTTP、NNTP和UNIX域协议》是“TCP/IP详解系列”的延续。主要内容包括：TCP事务协议，即T/TCP，这是对TCP的扩展，使客户-服务器事务更快、更高效和更可靠。

* [《TCP/IP协议族》](https://book.douban.com/subject/5386194/)  
  《世界著名计算机教材精选·TCP/IP协议族(第4版)》是介绍TCP/IP协议族的经典图书的最新版本。

* [《HTTP权威指南》](https://book.douban.com/subject/10746113/)  
  本书详细解释了HTTP协议，包括HTTP是如何工作的，如何用HTTP来开发基于Web的应用程序，核心的因特网协议如何与架构构建块交互，如何正确实现因特网客户和服务器等。

### 数据库
* [《数据库系统概念》](https://book.douban.com/subject/10548379/)  
  本书是数据库领域的殿堂级作品，是夯实数据库理论基础，增强数据库技术内功的必备之选，对深入理解数据库，深入研究数据库，深入操作数据库都具有极强的指导作用。

* [《数据库系统实现》](https://book.douban.com/subject/4838430/)  
  本书是关于数据库系统实现方面内容最为全面的著作之一，是美国斯坦福大学计算机科学专业数据库系列课程第二门课程的指定教材。

* [《高性能MySQL》](https://book.douban.com/subject/23008813/)  
  本书是MySQL 领域的经典之作，拥有广泛的影响力。

* [《MySQL 5 权威指南》](https://book.douban.com/subject/1909003/)  
  本书是MySQL数据库管理员和开发人员的必备参考书。

* [《MongoDB权威指南》](https://book.douban.com/subject/25798102/)  
  本书是一本广受好评的MongoDB权威著作。书中介绍了面向文档的存储方式及利用MongoDB的无模式数据模型处理文档、集合和多个数据库，讲述了如何执行基本的写操作以及各种复杂的条件查询，还介绍了索引、聚合工具以及其他高级查询技术，另外对监控、安全性和身份验证、备份和修复、水平扩展MongoDB数据库等内容也有所涉及。

* [《Redis设计与实现》](https://book.douban.com/subject/25900156/)  
  本书系统而全面地描述了Redis内部运行机制，是NoSQL数据库开发人员案头必备。

* [《NoSQL精粹》](https://book.douban.com/subject/25662138/)  
  《NoSQL精粹》为考虑是否可以使用和如何使用NoSQL数据库的企业提供了可靠的决策依据。书中全方位比较了关系型数据库与NoSQL数据库的异同；分别以Riak、MongoDB、Cassandra和Neo4J为代表，详细讲解了键值数据库、文档数据库、列族数据库和图数据库这4大类NoSQL数据库的优劣势、用法和适用场合；深入探讨了实现NoSQL数据库系统的各种细节，以及与关系型数据库的混用。

### 编译原理
* [《编译原理》](https://book.douban.com/subject/3296317/)  
  本书是编译领域无可替代的经典著作，被广大计算机专业人士誉为“龙书”。本书全面、深入地探讨了编译器设计方面的重要主题，包括词法分析、语法分析、语法制导定义和语法制导翻译、运行时刻环境、目标代码生成、代码优化技术、并行性检测以及过程间分析技术，并在相关章节中给出大量的实例。

### 数据结构&算法
* [《数据结构与算法分析：C语言描述》](https://book.douban.com/subject/1139426/)  
  本书是《Data Structures and Algorithm Analysis in C》一书第2版的简体中译本，原书曾被评为20世纪顶尖的30部计算机著作之一。在本书中，作者更加精炼并强化了他对算法和数据结构方面创新的处理方法。通过C程序的实现，着重阐述了抽象数据类型的概念，并对算法的效率、性能和运行时间进行了分析。

* [《数据结构与算法分析：Java语言描述》](https://book.douban.com/subject/3351237/)  
  本书是国外数据结构与算法分析方面的经典教材，使用卓越的Java编程语言作为实现工具讨论了数据结构（组织大量数据的方法）和算法分析（对算法运行时间的估计）。 随着计算机速度的不断增加和功能的日益强大，人们对有效编程和算法分析的要求也不断增长。本书把算法分析与最有效率的Java程序的开发有机地结合起来，深入分析每种算法，内容全面、缜密严格，并细致讲解精心构造程序的方法。

* [《数据结构（C语言版）》](https://book.douban.com/subject/1886174/)  
  《数据结构》(C语言版)针对采用ANSI C实现数据结构进行了全面的描述和深入的讨论。书中详细讨论了栈、队列、链表以及查找结构、高级树结构等功能，对裴波那契堆、伸展树、红黑树、2-3树、2-3-4树、二项堆、最小-最大堆、双端堆等新的数据结构进行了有效分析。

* [《数据结构（C语言版） 严蔚敏》](https://book.douban.com/subject/2024655/)  
  本书是为“数据结构”课程编写的教材，也可作为学习数据结构及其算法的C程序设计的参数教材。
  本书的前半部分从抽象数据类型的角度讨论各种基本类型的数据结构及其应用；后半部分主要讨论查找和排序的各种实现方法及其综合分析比较。

* [《算法导论》](https://book.douban.com/subject/20432061/)  
  本书将严谨性和全面性融为一体，深入讨论各类算法，并着力使这些算法的设计和分析能为各个层次的读者接受。

* [《算法》](https://book.douban.com/subject/19952400/)  
  本书是算法领域经典的参考书，涵盖所有程序员必须掌握的50种算法，全面介绍了关于算法和数据结构的必备知识，并特别针对排序、搜索、图处理和字符串处理进行了论述。

### 设计模式
* [《设计模式：可复用面向对象软件的基础》](https://book.douban.com/subject/1052241/)  
  本书是引导读者走出软件设计迷宫的指路明灯，凝聚了软件开发界几十年设计经验的结晶。四位顶尖的面向对象领域专家精心选取了具有价值的设计实践，加以分类整理和命名，并用简洁而易于重用的形式表达出来。本书已经成为面向对象技术人员的圣经和词典，书中定义的23个模式逐渐成为开发界技术交流所必备的基础知识和语汇。

* [《Head First 设计模式》](https://book.douban.com/subject/2243615/)  
  《O'Reilly：Head First设计模式（中文版）》趋近完美，因为它在提供专业知识的同时，仍然具有相当高的可读性。

* [《大话设计模式》](https://book.douban.com/subject/2334288/)  
  本书是准备攀登面向对象编程高峰朋友们的引路人和提携者，是学习、体会和领悟了众多大师智慧结晶后的图书作品，是你深入理解和感受GoF的《设计模式》及其它大师作品的必备书籍。本书通篇都是以情景对话的形式，用多个小故事或编程示例来组织讲解GoF总结的23个设计模式。

### 软件工程
* [《软件工程：实践者的研究方法》](https://book.douban.com/subject/6047742/)  
  《软件工程:实践者的研究方法(原书第7版)》自1982年发行第1版以来，一直受到软件工程界的高度重视，成为高等院校计算机相关专业软件工程课程的重要教学参考书。近30年来，它的各个后继版本一直都是软件专业人土熟悉的读物，在国际软件工程一界享有无可置疑的权威地位。它在全面而系统地介绍软件工程的有关概念、原则、方法和工具方面获得了广大读者的好评。

* [《软件工程》](https://book.douban.com/subject/6109617/)  
  本书是系统介绍软件工程理论的经典教材，自1982年初版以来，随着软件工程学科的发展不断更新版本，影响了一代又一代软件工程人才，对学科的发展建设也产生了积极影响。全书分四部分完整讨论了软件工程的各级段内容，是软件工程和系统工程专业本科和研究生的优秀教材，也是软件工程师必备的参考书籍。

* [《面向对象分析与设计》](https://book.douban.com/subject/3892590/)  
  本书是一本注重实效的书，面向架构师和软件开发者等软件工程实践者的实际需要，通过大量例子说明了基本概念，解释了方法，并展示了在不同领域的成功应用。

* [《深入浅出面向对象分析与设计》](https://book.douban.com/subject/3530721/)  
  本书将告诉你如何分析、设计以及撰写真正面向对象的软件；容易重用、好维护、可扩展的软件；不再使你心碎的软件；让你增添新功能而不会破坏旧机制的软件。

### 数字图像处理
* [《数字图像处理》](https://book.douban.com/subject/6434627/)  
  本书是数字图像处理领域的杰作。

* [《图像处理、分析与机器视觉》](https://book.douban.com/subject/5921462/)  
  本书是为计算机专业图像处理、图像分析和机器视觉课程编写的教材。书中针对图像处理、图像分析和机器视觉领域的有关原理与技术展开了广泛而深入的讨论，包括图像预处理、图像分割、形状表示与描述、物体识别与图像理解、三维视觉、数学形态学图像处理技术、离散图像变换、图像压缩、纹理描述、运动分析等。

* [《数字图像处理：MATLAB》](https://book.douban.com/subject/26344083/)  
  本书是图像处理基础理论论述同以MATLAB为主要工具的软件实践方法相对照的第一本书，书中集成了冈萨雷斯和伍兹所著的《数字图像处理》一书中重要的原文材料和MathWorks公司的图像处理工具箱。本书的特色在于重点强调怎样通过开发新代码来加强这些软件工具。本书在介绍MATLAB编程基础知识之后，讲述了图像处理的主干内容，包括灰度变换、线性和非线性空间滤波、频率域滤波、图像复原与重建、彩色图像处理、图像压缩、图像分割、区域和边界表示与描述。

### 计算机图形学
* [《计算机图形学》](https://book.douban.com/subject/26403265/)  
  本书是一本经典著作，全面系统地讲解了计算机图形学的基本概念和相关技术。

* [《计算机图形学》](https://book.douban.com/subject/3129340/)  
  本书与大多数传统的计算机图形学教材不同，它仅简要介绍交互式计算机图形学方面的基本知识，主要侧重于介绍计算机图形学在数学及其他科学领域的应用，解决实际问题。

* [《计算机图形学》](https://book.douban.com/subject/3561816/)  
  本书通过最能代表技术发展状况的示例综合介绍了计算机图形学方面的原则和技巧，书中对每个概念都进行了详细介绍，阐述了其背后的数学原理，并给出了用OpenGL实现的代码以及实现结果展示。

* [《OpenGL编程指南》](https://book.douban.com/subject/26220248/)  
  本书清晰地讲解了OpenGL的相关功能与技术，包括几何对象顶点的传递、细分，几何着色器中的几何变换，通过片元着色器来操作像素和纹理贴图，以及基于帧缓存对象和计算着色器的先进数据操作技术。

* [《OpenGL超级宝典》](https://book.douban.com/subject/10774590/)  
  本书是OpenGL及3D图形编程最好的入门指南，涵盖了使用最新版本的OpenGL进行编程所需要的主要知识。

### Linux
* [《深入理解LINUX内核》](https://book.douban.com/subject/2287506/)  
  本书指导你对内核中使用的最重要的数据结构、算法和程序设计诀窍进行一次遍历。通过对表面特性的探究，作者给那些想知道自己机器工作原理的人提供了颇有价值的见解。

* [《深入Linux内核架构》](https://book.douban.com/subject/4843567/)  
  本书讨论了Linux内核的概念、结构和实现。

* [《Linux程序设计》](https://book.douban.com/subject/4831448/)  
  本书是Linux程序设计领域的经典名著，以简单易懂、内容全面和示例丰富而受到广泛好评。

* [《Linux内核设计与实现》](https://book.douban.com/subject/6097773/)  
  本书详细描述了Linux内核的主要子系统和特点，包括Linux内核的设计、实现和接口。

* [《Linux/Unix设计思想》](https://book.douban.com/subject/7564417/)    
  本书将Linux的开发方式与Unix的原理有效地结合起来，总结出Linux与Unix软件开发中的设计原则。

* [《鸟哥的Linux私房菜：基础学习篇(第3版)》](https://book.douban.com/subject/4889838/)  
  本书是最具知名度的Linux入门书《鸟哥的Linux私房菜基础学习篇》的最新版，全面而详细地介绍了Linux操作系统。本书内容丰富全面，基本概念的讲解非常细致，深入浅出。各种功能和命令的介绍，都配以大量的实例操作和详尽的解析。本书是初学者学习Linux不可多得的一本入门好书。

* [《鸟哥的Linux私房菜：服务器架设篇(第3版)》](https://book.douban.com/subject/10794788/)     
  您已有Linux基础，想要进一步学习服务器架设？还想了解如何维护与管理您的服务器？本书是您绝佳的选择。

* [《UNIX环境高级编程》](https://book.douban.com/subject/1788421/)  
  本书是被誉为UNIX编程“圣经”的Advanced Programming in the UNIX Environment一书的更新版。本书内容权威，概念清晰，阐述精辟，对于所有层次UNIX程序员都是一本不可或缺的参考书。

### Android
* [《Android开发权威指南》](https://book.douban.com/subject/25741542/)  
  本书是一本全面介绍Android应用开发的专著。

* [《第一行代码》](https://book.douban.com/subject/26915433/)
  本书被广大Android 开发者誉为“Android 学习第一书”。全书系统全面、循序渐进地介绍了Android软件开发的必备知识、经验和技巧。

* [《Android内核剖析》](https://book.douban.com/subject/6811238/)  
  本书详细分析了Android内核的内部机制，包括窗口管理系统、Activity管理系统、输入法框架、编译系统等，为Android内核定制及高级应用程序开发提供技术参考。  
* [《Android开发艺术探索》](https://book.douban.com/subject/26599538/)  
  本书是一本Android进阶类书籍，采用理论、源码和实践相结合的方式来阐述高水准的Android应用开发要点。

* [《Android源码设计模式解析与实战》](https://book.douban.com/subject/26644935/)    
  本书从Android源码的角度由浅入深地剖析设计模式的运用，让工程师们把设计与模式重视起来，提升自己的设计能力与代码质量。

* [《深入解析Android 5.0系统》](https://book.douban.com/subject/26377840/)    
  本书详细剖析了最新Android 5.0 系统主要框架的原理和具体实现。

* [《深入理解Android内核设计思想》](https://book.douban.com/subject/25921329/)   
  本书从操作系统的基础知识入手，全面剖析进程/线程、内存管理、Binder机制、GUI显示系统、多媒体管理、输入系统等核心技术在Android中的实现原理。

* [《Android软件安全与逆向分析》](https://book.douban.com/subject/20556210/)    
  本书由浅入深、循序渐进地讲解了Android 系统的软件安全、逆向分析与加密解密技术。包括Android软件逆向分析和系统安全方面的必备知识及概念、如何静态分析Android 软件、如何动态调试Android 软件、Android 软件的破解与反破解技术的探讨，以及对典型Android 病毒的全面剖析。

