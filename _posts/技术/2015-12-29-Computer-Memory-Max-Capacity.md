---
layout: post
title: 查看自己电脑可以支持的最大内存量
category: 技术
tags: 电脑
keywords: 
description: 
---


查看自己电脑的主板可以支持的最大内存存储量

1. Windows+R，打开【运行】对话框，输入cmd，确定

2. 在cmd中输入查询命令
在cmd中输入

```
wmic memphysical get maxcapacity
```  

接着在cmd中就会显示主板可以支持的最大内存量

此处的16777216就是16G=16*1024*1204KB=16777216GB。结果显示中的这个数字的单位是KB。

>By Cacool
>
>2015.12.29
