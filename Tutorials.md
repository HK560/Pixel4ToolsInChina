
## <span id="tutorials">教程搜集</span>
### <span id="unlockbl">	解锁Bootloader(BL锁)</span>
> BL锁就是锁住手机的Recovery和Fastboot,防止刷入非官方签名的系统而损坏手机的一个保护机制(同时也为用户资料提供了一定的保护)。——[【科普向】Android手机的BL锁到底是什么东东](https://www.bilibili.com/read/cv307758)

通过解锁BL锁我们能够自由刷入系统镜像,进行root处理,以便我们更方便使用手机,也就能够安装Magisk,进而安装模块解锁motion sense雷达电信

一些教程链接:
* [小胡子的干货铺——Pixel 4 XL解锁Bootloader](https://sspai.com/post/57922)
* [【推荐】Google Pixel&Nexus 官方工厂镜像下载](https://developers.google.com/android/images#instructions)的线刷步骤中有指导如何解锁BL

[这里](resources/Resources.md#adbUSB)提供了一些可能用得到的资源

-----


### <span id="whatmagisk">	通过Magisk 解锁使用root,Motion Sense ,电信网络</span>
> - Magisk是一套开放源代码的Android(5.0以上版本)自定义工具套组,内置了Magisk Manager(图形化管理界面)、Root、启动脚本、SElinux补丁和启动时认证/dm-verity/强制加密移除功能。Magisk同时提供了在无需修改系统文件的情况下更改/system或/vendor分区内容的接口,利用与Xposed类似的模块系统,开发者可以对系统进行修改或对所安装的软件功能进行修改等。——引用自Magisk维基百科

简单来说安装Magisk可以让你的手机使用root超级用户权限,能够安装一些magisk模块修改系统,实现一些额外的功能。
**为Pixel4解锁motion sense(雷达)和使用电信网络,使用magisk模块基本上是最方便快捷的方式。**


#### <span id="installmagisk"> 1. 安装Magisk</span>
相关安装教程链接:
* [【推荐】(最后更新2021-07-31)[Pixel]OTA系统更新后重新安装Magisk](https://www.bilibili.com/video/BV1Eq4y1975h)
* [(最后更新2019年12月18日)小胡子的干货铺——Pixel 4 XL刷入Magisk、Root](https://sspai.com/post/57923)

##### 可能会用到的资源网站:
* [MagiskManager官网下载](https://magiskmanager.com/)
* [Google Pixel&Nexus 官方工厂镜像下载](https://developers.google.com/android/images),搜索该网页"flame" for Pixel 4即可找到Pixel4各个系统版本的工厂镜像下载链接,按需下载


#### <span id="installmagiskmodules"> 2. 安装并启用Magisk模块</span>

为了使用雷达和电信VoLTE网络,我们需要安装能够解锁对应的Magisk模块

你可以在[这里](resources/Resources.md#MagiskModules)下载解锁雷达和电信VoLTE的Magisk模块

Magisk安装本地模块教程:
- [Magisk怎样安装本地模块?](https://jingyan.baidu.com/article/4b07be3c628c3109b380f3db.html) 

当然你还可以在Magisk Manager的在线仓库搜索模块下载安装

安装模块成功之后,模块会在Magisk Manager中显示,请确保勾选启用模块,然后重启手机,模块即可生效。

-------

### <span id="OTA-magisk">	OTA升级后恢复Magisk,ROOT,模块</span>
待更新完善....

------
### <span id="factoryImages">使用工厂镜像线刷系统(重装系统,救砖)</span>
待更新完善....

-------	
### <span id="fullOTAImages">使用Full OTA镜像升级系统(保留数据升级系统)</span>
待更新完善....

-----------