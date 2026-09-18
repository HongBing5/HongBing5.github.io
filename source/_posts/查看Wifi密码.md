---
title: 查看Wifi密码
excerpt: 查看已连接过WiFi密码，再也不用担心忘记密码了
date: 2023-03-28 21:10:13
tags: 技巧
category: 编程
thumbnail: "https://w.wallhaven.cc/full/zy/wallhaven-zy8q6w.jpg"
---

# WIFI 密码查看

{% notel yellow 查看已连接过WiFi密码，再也不用担心忘记密码了 %}

相信各位朋友肯定遇到过，我们在路由器中设置的 WIFI 密码，由于时间太过久远，忘记了设置的密码是什么。或者是连接了朋友/邻居家的 WIFI，我们却不知道密码是什么。这篇笔记简单分享一下如何查看已经连接过的 WIFI 的密码

{% endnotel %}

{% note warning  %}
Windows 方法
{% endnote %}

按下键盘上 WIN+R 键，打开运行窗口；运行窗口中输入 CMD，回车，打开命令行窗口；

在 CMD 窗口中输入：

```cmd
netsh wlan show profiles
```

执行后，会列出已连接过的 WiFi 名称；

接着输入命令：

```cmd
netsh wlan show profiles name="这里填WIFI名称" key=clear
```

执行后就会显示密码。

{% note warning  %}
Android 方法
{% endnote %}

依次打开手机设置 →WLAN→ 长按想要知道 WiFi 密码的名称 → 截图二维码。

打开微信并打开扫一扫，扫描本地二维码图片，扫描完成后中间部分就是我们的 WIFI 密码。
