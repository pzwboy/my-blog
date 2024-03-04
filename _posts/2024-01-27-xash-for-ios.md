---
layout: post
title:  "Xash 3D（半衰期1代）iOS版本安装指南"
---
已更新文章，因为报错、卡控制台等原因，已删除自签及AppSync Unified（部分iOS版本可能能用）安装方式

## 准备工作
* iOS设备已进行越狱（可选）

* 已安装Trollstore

#### 二选一
* 拥有Mac或Windows设备并安装好[爱思助手](https://www.i4.cn/)（越狱后）

* iOS设备中已安装Filza

#### Filza安装方式

##### 越狱
打开Sileo或Cydia，搜索并安装`Filza File Manager`即可

##### 仅安装了Trollstore
[Pzwboy 资源站](http://pzwboy.ysepan.com)

iOS游戏-->Filza_3.9.5-文件管理器.ipa

安装即可

## 1.安装xash引擎启动器

### ipa安装包下载
[天翼云盘](https://cloud.189.cn/web/share?code=RBFjquraM73i)（访问码：kw7a）

[123云盘](https://www.123pan.com/s/9s7uVv-tlfiH.html)

### 安装
未越狱的设备根据iOS版本自行在网上找安装方式（如`Trollstar`等安装器）

越狱后通过Sileo或Cydia搜索`TrollStore Helper`，根据提示安装TrollStore（由于TrollStore Helper是通过Github的官方仓库来下载最新版本，所以部分地区的网络需全程打开V啥啥，不然会报错），再在软件中导入安装ipa即可

## 2.《半衰期》数据包导入

### 数据包下载
提取自零售年度版，已更改访问权限。

[天翼云盘](https://cloud.189.cn/web/share?code=YnuuemZvi2qe)（访问码：tax5）

[123云盘](https://www.123pan.com/s/9s7uVv-zlfiH.html)

### 导入

#### iOS设备通过Filza
打开Filza，找到`/var/mobile/Containers/Data/Application/xash3d-ios/Documents`，复制iOS专用数据包到此处即可

#### 爱思助手（即PC）
在Sileo或Cydia中添加搬运工源🇨🇳`https://byg.iosios.net/`后，搜索并安装`AFC2电脑访问手机文件`，在爱思助手中的“文件管理”-->“文件系统（越狱）”中找到`/var/mobile/Containers/Data/Application/xash3d-ios/Documents`，复制iOS专用数据包到此处即可

## Hud过小解决方案
在启动器输入框中加入`+hud_scale 2`即可

## Gearbox Software 高清模型补丁
[蓝奏云](https://www.lanzv.com/igkJ21mfmkab)

复制到valve文件夹内使用

## 《半衰期：蓝色行动》及《半衰期：针锋相对》包
[123云盘](https://www.123pan.com/s/9s7uVv-L6fiH.html)

### 启动项
蓝色行动：`-game bshift`

针锋相对：`-game gearbox`

## 最后，玩得愉快！