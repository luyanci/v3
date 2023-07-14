---
title: LSPosed安装
date: 2023-07-01 16:17:20
tags: 软件
#cover: /image/lsposed/top.webp
---
![](/image/lsposed/top.webp)
# 简单介绍
LSPosed是目前主流的XPosed框架，支持安卓8.1-13
# [视频教程](https://www.bilibili.com/video/BV13B4y1x7rh)
<iframe src="//player.bilibili.com/player.html?aid=685579245&bvid=BV1dU4y1S7AY&cid=763587977&page=1" scrolling="yes" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

# 文字教程（以最新稳定为例）
## 下载
打开[LSPosed的Github页面](https://github.com/LSPosed/LSPosed/)，直接找到releases，下载**magisk模块**包
**这里下载的是模块包，不是管理器！**
## 安装
### Zygisk版本安装（Magisk>v24.1）
下载文件名带zygisk的包,打开面具直接刷入模块重启即可
**注意：面具设置必须打开zygisk,否则重启之后出现模块未启用**
![](/image/lsposed/1.jpg)

### Riru版本安装（magisk<24.1）
**推荐先去升级面具，没有办法再去换riru版**
首先以同样的方式下载[必要模块Riru](https://github.com/RikkaApps/Riru/)，然后再下载文件名带Riru的包，然后**按顺序刷入**（先Riru后LSPosed）

## 安装报错&解决方法

|报错提示|原因|解决方法|
|:---|:---:|:---:|
|Unzip error!|下载文件有问题|重新下载|
|Riru not installed!|Riru未安装|安装Riru|
|Please disable or uninstall incompatible frameworks！|模块冲突|卸载或禁用提示出来的模块即可（如edxp、太极阳、Dreamland等xp框架）|
|Please install Magisk v24.1+!|面具版本低|升级面具|

