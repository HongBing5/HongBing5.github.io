---
title: nvm介绍
excerpt: node版本管理工具的简介使用
date: 2023-06-17 16:53:46
tags: [笔记]
category: [编程]
banner: "https://w.wallhaven.cc/full/0j/wallhaven-0j5w15.jpg"
---

## nvm 介紹

[Node](https://so.csdn.net/so/search?q=node&spm=1001.2101.3001.7020) 的版本管理器，可以方便地安装&切换不同版本的 node

## 1.下载

下载地址：https://github.com/coreybutler/nvm-windows/releases

## 2.安装

安装需要注意：

把电脑上面的 node 环境先卸载干净（C:\Users\HB\AppData\Roaming\node 下面的文件也要解决干净）

## 3、检查安装是否成功

在命令行输入 nvm 能出现反应就行 OK 了

## 4、😎 使用 nvm

```cmd
安装node前配置一下镜像地址
node_mirror: https://npm.taobao.org/mirrors/node/
npm_mirror: https://npm.taobao.org/mirrors/npm/
```

### 1、安装指定的 node 版本

安装想要的 node 版本，可以通过 以下命令查看可以安装的 node 版本

```cmd
nvm ls available
```

### 2、安装方式

**nvm install 版本号**

CURRENT ：当前最新的版本

LTS ：稳定版本

OLD STABLE：旧的稳定

OLD UNSTABLE：旧的不稳定

```cmd
# 例如我要安装最新的 20.1.0 的版本（当前稳定的最新版）
nvm install 20.1.0

# 我安装了两个
nvm install 20.1.0
nvm install 16.14.1
```

### 3、显示 node 版本

```cmd
# 使用 nvm ls 或者 nvm list 可以查看安装的不同node版本，*指向的就是当前版本
nvm ls
```

### 4、切换 node 版本

```cmd
# 例如我要切换到 16.14.1 版本
nvm use 16.14.1
```

## 5.常用指令表

| 命令                            | 含义                                               |
| ------------------------------- | -------------------------------------------------- |
| nvm ls                          | 列出所有已安装的 node 版本                         |
| nvm ls-remote                   | 列出所有远程服务器的版本（官方 node version list） |
| nvm list available              | 显示所有可下载的版本                               |
| nvm install stable              | 安装最新版 node                                    |
| nvm install 20.1.0              | 安装 20.1.0 版本 node                              |
| nvm uninstall 20.1.0            | 删除 20.1.0 版本的 node                            |
| nvm use [node 版本号]           | 切换到指定版本 node                                |
| nvm current                     | 当前 node 版本                                     |
| nvm alias default [node 版本号] | 设置默认版本                                       |
