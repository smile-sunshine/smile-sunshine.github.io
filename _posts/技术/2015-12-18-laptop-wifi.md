---
layout: post
title: 用能上网的笔记本开启免费WiFi
category: 技术
tags: 笔记本 Wifi
keywords: 
description: 
---


Windows+R，在弹出的运行对话框中输入`cmd`，确定，这时弹出`cmd`命令行。

在cmd命令行中依次输入以下几条命令：

* 设置WiFi

```
netsh wlan set hostednetwork ssid = King key = 12344321
```

* 开启Wifi
```
netsh start hostednetwork
```

* 关闭Wifi

```
netsh stop hostednetwork
```

>By Cacool
>
>2015.12.18