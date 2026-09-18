# Hexo 简单说明书

## 1. 安装 Hexo

确保已安装 [Node.js](https://nodejs.org/) 和 [Git](https://git-scm.com/)。

```bash
npm install -g hexo-cli
```

## 2. 初始化博客

在你想创建博客的目录下运行：

```bash
hexo init blog
cd blog
npm install
```

## 3. 常用命令

- 新建文章：

  ```bash
  hexo new "文章标题"
  ```

- 启动本地服务器预览：

  ```bash
  hexo server
  ```

  访问 http://localhost:4000 查看博客。

- 生成静态文件：

  ```bash
  hexo generate
  ```

- 部署到远程（需配置 _config.yml）：

  ```bash
  hexo deploy
  ```

## 4. 目录结构简介

- `source/_posts/`：存放博客文章的 Markdown 文件
- `themes/`：主题文件夹
- `public/`：生成的静态网页文件
- `_config.yml`：全局配置文件

## 5. 常见问题

- 修改主题：将主题放入 `themes/` 文件夹，并在 `_config.yml` 中设置 `theme: 主题名`
- 安装插件：使用 `npm install 插件名 --save` 安装

## 6. 参考链接

- [Hexo 官方文档](https://hexo.io/zh-cn/docs/)
