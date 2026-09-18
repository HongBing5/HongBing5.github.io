---
title: Hexo博客搭建之修改主题
date: 2023-03-17 20:16:29
tags: [笔记, 技巧]
excerpt: "博客主题的样式修改"
category: 编程
banner: "https://w.wallhaven.cc/full/yx/wallhaven-yx52xd.jpg"
---

## 修改博客主题

相信各位同学也看到了，我们由 Hexo 原生生成的博客样式有点丑，那么我们可以参考官方的主题来美化它 点击 👉 [更多主题](https://hexo.io/themes/) 查看官方提供给我们的主题，这里有 378 个主题可以选择，

那么我拿本站使用的主题来做一个简单的演示：

**我使用的是**：

- [Theme Redefine](https://redefine.ohevan.com/) 主题(_点击可查看官方文档非常详细_)，

- 作者: [Evan Luo](https://ohevan.com/about) 是一位加拿大的留学生 感谢 (●'◡'●)

![](https://user-images.githubusercontent.com/68590232/224550645-07d6b624-fa7c-40aa-90f8-873c958afa30.png)

### 1.安装

​ 在你的博客根目录下运行 以下命令

```cmd
npm install hexo-theme-redefine@latest
```

### 2.使用

安装完成后，在 Hexo 配置文件`_config.yml ` 中将 `theme` 设置为 `Redefine`。

```yml
theme: redefine # 👈主题名称
```

### 3.配置

为了日后实现平滑升级，在 **Hexo 根目录中**创建 `_config.redefine.yml` 并将[这里的代码](https://github.com/EvanNotFound/hexo-theme-redefine/blob/main/_config.yml)全部复制进去保存，以后要更改主题设置就在 `_config.redefine.yml` 里面更改。

{% note red  %}
`config.redefine.yml` 永远都会覆盖主题目录下的 `_config.yml` 设置
{% endnote %}

### 4.主题背景图

**图库连接地址:[Dynamic Wallpaper Gallery](https://dynamicwallpaper.club/gallery)**

在这个网站如果直接下载资源的话，图片是`HEIC`格式，这样的格式一般不好打开，也不好转换出我们对应所需要的昼夜图片，

{% notel blue Tips %}

1. 对想要下载的图片点击 `分享`，会弹出对话框，再从对话框点击 `复制链接`

2. 在新的浏览器标签页打开，然后打开开发人员工具(F12)，审查元素，获取当前图片源地址并复制它，

3. 在浏览器 URL 地址，每次修改最后目录的索引值，一般都是数字类型，从 1 开始

### **然后你就会获取到对应时间段，不同风格的该主题图片了 🎉**

{% endnotel %}

### 5.更多: [官方文档](https://redefine-docs.ohevan.com/getting-started)

{% notel yellow 提醒 %}

推荐阅读的 `nodejieba` 这里配置有点小复杂

```
npm install nodejieba
```

**注意**： Windows 直接安装报错，因为缺少依赖。
由于 nodejieba 的底层算法实现是 C++，所以需要安装 node-gyp 来编译原生 C++扩展模块。

安装方法 http://www.notedeep.com/page/798
配置环境 https://www.jianshu.com/p/2b831714bbff

{% endnotel %}
