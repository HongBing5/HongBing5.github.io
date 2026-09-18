---
title: Stable Diffusion
date: 2023-03-24 08:48:38
tags: '笔记'
category: 'AI绘画'
excerpt: "开源软件AI绘图的基本使用和笔记"
banner: "https://w.wallhaven.cc/full/9d/wallhaven-9dzko8.png"
---

## AI 绘图的基本使用

目前 AI 绘图来说, **Stable Diffusion** 感觉应该是最好用的了，下文我会用 **SD** 来代称 Stable Diffusion 。

只要你电脑配置可以，画一些你能想象到的不错的图片，还是希望蛮大的 <(￣︶￣)↗[GO!]

### 前期需要软件有三个：

1. Python3.10.6 版本(版本过低的话是不行的)

   ```txt
   # 选上这个就不用配置环境了
   Add Python 3.10 to PATH 
   # 其他基本点下一步就好，最好不要安装在C盘
   ```

2. VSCode

   正常安装就行，不要安装在 C盘

3. Git 

   ``` txt
   # 遇到这个选项时候
   Which editor would you like Git to use ？ 
   # 选择
   Use Visual Studio Code as Git's default editor 
   # 其他基本都是点 下一步
   # 最后 Finish 时候 取消View Release Notes 的勾选
   ```

   

### 下载与安装：

1. 打开链接下载(以下三个是必须文件)：

   [SD软件本体](https://pan.baidu.com/s/1BkNY8A0h2eOVIQr0jQMLow?pwd=dq7e )  	💾10GB

   [启动器运行依赖]( https://pan.baidu.com/s/1kXpZy90zrDwZW3SYLqnfTA?pwd=xnxc  )  	💾54.6MB

   [启动器]( https://pan.baidu.com/s/1Hrgp0o7Aro_Z3pVDwKr7UA?pwd=ngf6)  	💾9.7MB

2. 把SD本体那个压缩包解压到指定目录，不要解压到C盘

3. 运行启动器依赖，点击下一步，然后就安装完成了

4. 解压启动器 到SD目录下

5. 去 SD 的根目录点启动器,就会打开启动界面了

   ```cmd
   # 在一键启动后会弹出 txt文本需要我们输入
   我已阅读并同意用户协议
   # 千万不要写错，或者多打空格，然后保存再关闭，可以按↓建查看
   # 然后重新启动再打开
   ```

6. 然后就可以进入 SD 的 UI 界面了

### 附加：

在附加功能页面，有一个图片放大的功能，可以单张放大也可以多张批量放大。

**单张图像放大**：只需要注意下面两项参数：

1. 缩放比例(默认4，基本就够用了)
2. Upscaler1(算法，基本: **R-ESRGAN 4X+** 其他自己可以随便尝试)

### 其他:

所需要的模型和Lora可以自己去 Civitai 看看

推荐B站 UP主 (也是这个UI界面的创作者) ：https://space.bilibili.com/12566101




