# 仓库说明
- 本仓库搜集整理 2019年发布的Google Pixel 4 手机相关的工具组件模块教程等资源。便于在中国大陆更方便合理地使用Pixel4。
- 本文大部分资源教程为O版服务。请各位机主了解清楚自己的Pixel4是什么版本! 若不理解本项内容请阅读[【关于Pixel4你可能想知道的】](#know)
- **注意仓库收录的资源适用于Pixel4,但不完全保证Pixel4XL也能够使用(虽然大体都可以互用的,有时候Pixel4XL的教程资源也能给Pixel4用)**
- **++大部分资源和教程来源于网络共享,本仓库仅作为指路导航++**
- ++**仓库仍在逐步完善中**++


-----


# 目录
- [我想要拥有/拥有了一台 Pixel 4,我应该做些什么?](#whatshouldido)
- [关于Pixel4你可能想知道的](#know)
- - [查询我的 Pixel 4 是什么版本(查询IMEI)](#imei)
- [我是非运营商版本的O版(即能解锁BL)Pixel4,我想要获得更好的体验](#iamready)

-----


- [教程搜集(解锁BL,刷入Magisk,MotionSense模块电信模块)](Tutorials.md#tutorials)

- - [解锁Bootloader(BL锁](Tutorials.md#unlockbl)
- - [通过Magisk 解锁使用root,Motion Sense ,电信网络](Tutorials.md#whatmagisk)
- - - [安装Magisk](Tutorials.md#installmagisk)



-----




## <span id="whatshouldido">【序】我想要拥有/拥有了一台 Pixel 4,我应该做些什么?</span>
#### 如果你还没有拥有Pixel4
* 如果你还没有拥有Pixel4,但想要了解这台手机或者准备购入,可以阅读下面的栏目[【关于Pixel4你可能想知道的】](#know)来了解Pixel4的基本信息。
#### 如果你已经拥有了Pixel4
* 如果你不知道你的手机是什么版本,你可以阅读[【我的 Pixel 4 是什么版本】](#IMIE)来了解
* 如果你已经知道**你的手机是O版**(即能解BL锁)那么恭喜你,你可以继续阅读本文内容来获得Pixel4的完整体验。
* 如果**你的手机是M版**(即无法解锁BL锁的运营商版本)那么很可惜,本文后半部分的介绍的内容无法用在你的手机上,但Pixel4的原生系统应该还是能给你带来不错的体验。




-----


## <span id="know">关于Pixel4你可能想知道的</span>
* **【必读】** Pixel4 大体上可以分为两个版本,这里为方便分别称为O版和M版。O版能解锁Bootloader锁,进而可以自由刷入镜像解锁root等;M版为运营商特供的版本,不能解锁bootloader,也就无法root等,本文大部分资源教程为O版服务。其他的可能还有工程机(不能使用面部解锁),日版(不能关闭拍照快门声音) **购机前一定要了解清楚机子是什么版本。若已入手也请各位机主一定要了解清楚自己手里的Pixel4是什么版本!**

* 如果没有代理服务(梯子)的话体验会严重打折扣,个人极度推荐使用开启代理服务来使用手机

* [Google Pixel 官方商店页面](https://store.google.com/tw/category/phones)
* [Pixel4 中文维基介绍](https://zh.wikipedia.org/wiki/Pixel_4)
* [Pixel4 配置数据信息_ZOL](https://detail.zol.com.cn/cell_phone/index1274867.shtml) 
* [[2021]《Pixel捡垃圾指南 (二) : Pixel 4 的故事》](https://www.bilibili.com/video/BV1Bq4y1o7mq)(了解Pixel4的特性和Pixel4独有的MotionSense雷达等)

### <span id="imei">查询我的 Pixel 4 是什么版本(查询IMEI)</span>
* [查询GooglePixel保修信息以及判断是否为Verizon运营商版](https://ericclose.github.io/Pixel-repairs-and-carriers.html)
* [【第三方平台查询IMEI】GOOGLE IMEI Check](https://www.imei.info/zh/phonedatabase/phones-google/)


-----


## <span id="iamready">我是非运营商版本的O版(即能解锁BL)Pixel4,我想要获得更好的体验</span>

* 为了获得Pixel4最好的体验,大家玩机选择的路线一般是:

1.  **解锁BL->刷入最新的原生系统镜像->安装Magisk获得root->安装Magisk模块解锁MotionSense和电信卡网络(按需是否继续刷入LspXposed框架->安装Xposed模块)** 
你可以阅读[教程](#tutorials)来学习如何操作

2.	**开启开发者模式,勾选强制屏幕高刷新率**
3.	**使用代理(梯子)登入谷歌账号,享受原生系统**



-----


## <span id="tutorials">教程搜集</span>
### <span id="unlockbl">一 解锁Bootloader(BL锁)</span>
> BL锁就是锁住手机的Recovery和Fastboot,防止刷入非官方签名的系统而损坏手机的一个保护机制(同时也为用户资料提供了一定的保护)。——[【科普向】Android手机的BL锁到底是什么东东](https://www.bilibili.com/read/cv307758)

通过解锁BL锁我们能够自由刷入系统镜像,进行root处理,以便我们更方便使用手机,也就能够安装Magisk,进而安装模块解锁motion sense雷达电信

一些教程链接:
* [小胡子的干货铺——Pixel 4 XL解锁Bootloader](https://sspai.com/post/57922)
* [Google Pixel&Nexus 官方工厂镜像下载](https://developers.google.com/android/images#instructions)的线刷步骤中有指导如何解锁BL



-----


### <span id="whatmagisk">二 通过Magisk 解锁使用root,Motion Sense ,电信网络</span>
> - Magisk是一套开放源代码的Android(5.0以上版本)自定义工具套组,内置了Magisk Manager(图形化管理界面)、Root、启动脚本、SElinux补丁和启动时认证/dm-verity/强制加密移除功能。Magisk同时提供了在无需修改系统文件的情况下更改/system或/vendor分区内容的接口,利用与Xposed类似的模块系统,开发者可以对系统进行修改或对所安装的软件功能进行修改等。——引用自Magisk维基百科

简单来说安装Magisk可以让你的手机使用root超级用户权限,能够安装一些magisk模块修改系统,实现一些额外的功能。
**为Pixel4解锁motion sense(雷达)和使用电信网络,使用magisk模块基本上是最方便快捷的方式。**


#### <span id="installmagisk"> 1. 安装Magisk</span>
相关Pixel4安装教程链接:
* [【推荐】(最后更新2021-07-31)[Pixel]OTA系统更新后重新安装Magisk](https://www.bilibili.com/video/BV1Eq4y1975h)
* [(最后更新2019年12月18日)小胡子的干货铺——Pixel 4 XL刷入Magisk、Root](https://sspai.com/post/57923)

##### 可能会用到的资源网站:
* [MagiskManager官网下载](https://magiskmanager.com/)
* [Google Pixel&Nexus 官方工厂镜像下载](https://developers.google.com/android/images),搜索该网页"flame" for Pixel 4即可找到Pixel4各个系统版本的工厂镜像下载链接,按需下载