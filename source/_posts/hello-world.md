---
title: 个人博客搭建
date: 2023-03-15 14:00:02
tags: [笔记, 技巧]
category: 编程
excerpt: "搭建属于自己的个人博客"
banner: "https://w.wallhaven.cc/full/x6/wallhaven-x6zzql.jpg"
---

快速、简洁且高效的博客框架: [Hexo ](https://hexo.io/zh-cn/) 的基本使用，在这之前首先你需要有 [Git](https://git-scm.com/) 没有的话可以点击链接自行下载

## 和我一起开始搭建属于自己的 [个人博客](https://iyfhongbing.gitee.io/) 吧 o(_^▽^_)┛

### 第一步：下载

首先你需要在 [npm](https://www.npmjs.com/) 下载 [Hexo]() 所需要的模块

```bash
npm install hexo-cli -g
```

或者使用 yarn 命令也是可以的

```bash
yarn add hexo-cli -g
```

### 第二步：初始化

在你要创建博客的目录文件夹下，初始化 **blog** 文件资源，创建 **blog** 文件夹（以后的资源文件全部在这个里面）

```bash
hexo init blog
```

### 第三步：在 blog 下 初始化

以后的大部分命令，要在这个文件为目录下操作

```bash
cd blog
```

### 第四步：安装 第三方包

```bash
npm install
```

### 第五步：运行

需要在 **blog** 目录下运行命令符，

**blog** 的运行地址一般在：http://localhost:4000/

```bash
hexo server
```

该命令可以简化为：

```bash
hexo s
```

如果你看到下面这样的页面，那么恭喜你已经成功创建了属于自己的博客了 (只不过这样页面有点小漂亮)

![Hexo_default](https://hexo.io/themes/screenshots/landscape.png)
