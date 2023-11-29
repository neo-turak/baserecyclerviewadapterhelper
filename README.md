![](https://user-images.githubusercontent.com/7698209/33198075-ef8f2230-d123-11e7-85a3-4cb9b22f877d.png)
[![](https://jitpack.io/v/CymChad/BaseRecyclerViewAdapterHelper.svg)](https://jitpack.io/#CymChad/BaseRecyclerViewAdapterHelper)![](https://travis-ci.org/CymChad/BaseRecyclerViewAdapterHelper.svg?branch=master)[![API](https://img.shields.io/badge/API-14%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=14)[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-BaseRecyclerViewAdapterHelper-green.svg?style=true)](https://android-arsenal.com/details/1/3644)[![CircleCI](https://circleci.com/gh/CymChad/BaseRecyclerViewAdapterHelper/tree/master.svg?style=svg)](https://circleci.com/gh/CymChad/BaseRecyclerViewAdapterHelper/tree/master)[![Codacy Badge](https://api.codacy.com/project/badge/Grade/2302d0084d0048eaa0f9bac4350837a0)](https://www.codacy.com/app/CymChad/BaseRecyclerViewAdapterHelper?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=CymChad/BaseRecyclerViewAdapterHelper&amp;utm_campaign=Badge_Grade)[![](https://img.shields.io/badge/%E4%BD%9C%E8%80%85-%E9%99%88%E5%AE%87%E6%98%8E-7AD6FD.svg)](https://mp.weixin.qq.com/s/5UlMx9HDgEcvxJb4w5-gBA)  
# BRVAH
http://www.recyclerview.org/

Powerful and flexible RecyclerView Adapter,
Please feel free to use this. (Welcome to **Star** and **Fork**)  

强大而灵活的RecyclerView Adapter（欢迎 **Star** 和 **Fork**）
# 说明：
这个是基于BaseRecyclerViewHelper的3.x版本做出的改动，我认为一个库的更新应该支持向下兼容的。  
1.全部类转化成Kotlin，项目结构移动到Kotlin目录下(避免新版本AS展示Kotlin+android)。  
2.重命名data对象到items. 因为data是在Kotlin内是预保留字段，不应该作为对象。  
3.持续更新文档，保证文档更全面（主库找不到很多类的使用说明）。  
4.对于内部方法的改进，补充低版本不兼容方法。  
5.提交到Jitpack.io,下载快。

# Document
- English Writing ...
- [3.0版本 中文](https://github.com/CymChad/BaseRecyclerViewAdapterHelper/blob/3.x/readme/0-BaseRecyclerViewAdapterHelper.md)

## Demo
[wiki](https://github.com/CymChad/BaseRecyclerViewAdapterHelper/wiki)

# proguard-rules.pro
> 此资源库自带混淆规则，并且会自动导入，正常情况下无需手动导入。

> The library comes with `proguard-rules.pro` rules and is automatically imported. Normally no manual import is required.
> You can also go here to view [proguard-rules](https://github.com/CymChad/BaseRecyclerViewAdapterHelper/blob/master/library/proguard-rules.pro)


# Thanks  
[CymChad/BaseRecyclerViewAdapterHelper](https://jitpack.io/#CymChad/BaseRecyclerViewAdapterHelper)
[JoanZapata / base-adapter-helper](https://github.com/JoanZapata/base-adapter-helper)
# [License](https://github.com/CymChad/BaseRecyclerViewAdapterHelper/blob/master/LICENSE)
