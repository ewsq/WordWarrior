﻿# WordWarrior
一个个性化的安卓英语单词本应用，配合mdict效果更好哦！

## 功能
- 从文章中分析单词词频
- 修改是否记住标记
- 查询单词意思（点击调用黏贴板，mdict响应）
- 可导出导入单词

## 使用
- Android Studio最新版
- Android phone  android:minSdkVersion="11"  android:targetSdkVersion="17"
- 除baoyz.swipemenulistview，不需要其他库
- 熟悉SQLite的增删改查、listview的使用即可。

## 数据库说明（wordwarrior.lib）
- 表MyWord没有放任何数据
- 表TmpWord放了柯林斯5星的680个单词，没有单词意思，单词意思靠mdict查
- 在程序中两个表的相关操作都在sqlhelper和WordDAO完成（com\talengu\wordwarrior\sql下）

## 其他说明
- 此项目包含一个第三方库baoyz.swipemenulistview(我将源代码放在了我的项目中)，在此表示感谢。
- 欢迎大家fork和给我建议！


## 应用运行图片
本项目debug-apk文件[下载地址](https://raw.githubusercontent.com/talengu/WordWarrior/master/apkandimg/app-debug.apk)  
mdict Android安装包[下载地址](http://www.mdict.cn/wp/?lang=zh)

<img src="./apkandimg/Screen1.png" width = "240" height = "400" alt="截图一" align=center />
<img src="./apkandimg/Screen2.png" width = "240" height = "400" alt="截图二" align=center />
<img src="./apkandimg/Screen3.png" width = "240" height = "400" alt="截图三" align=center />
