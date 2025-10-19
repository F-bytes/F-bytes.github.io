---
title: "Hello World - 我的第一篇博客"
date: 2025-10-19T10:00:00+08:00
draft: false
tags: ["随笔", "博客搭建"]
categories: ["生活"]
author: "ZHU"
showToc: true
TocOpen: false
description: "博客搭建成功的第一篇文章"
cover:
    image: ""
    alt: ""
    caption: ""
---

## 前言

欢迎来到我的博客！这是使用 Hugo + PaperMod 主题搭建的第一篇文章。

经过一番折腾，终于把博客搭建起来了。这里记录一下搭建过程和感想。

## Hugo 简介

Hugo 是一个用 Go 语言编写的静态网站生成器，具有以下特点：

- ⚡ **速度快** - 毫秒级生成速度
- 🎨 **主题丰富** - 大量优秀主题可选
- 🌐 **多语言支持** - 原生 i18n 支持
- 📝 **Markdown** - 使用 Markdown 编写内容
- 🚀 **易部署** - 可部署到 GitHub Pages、Vercel 等

## 为什么选择 Hugo

在众多静态博客框架中，我选择 Hugo 的原因：

1. **性能卓越** - 生成速度是 Hexo 的 10-30 倍
2. **原生多语言** - 内置完善的 i18n 支持
3. **无需依赖** - 单文件运行，不需要 Node.js
4. **活跃社区** - GitHub 84k+ stars
5. **技术前瞻** - Go 语言生态，符合技术方向

## 技术栈

本博客采用的技术栈：

- **框架：** Hugo (Extended)
- **主题：** PaperMod
- **评论系统：** Giscus（计划中）
- **部署平台：** GitHub Pages
- **版本控制：** Git + GitHub

## 搭建过程

### 1. 安装 Hugo

```bash
# 使用 Scoop 安装
scoop install hugo-extended
```

### 2. 创建站点

```bash
hugo new site ZHUs-Tech-Blog
cd ZHUs-Tech-Blog
```

### 3. 安装主题

```bash
git submodule add https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
```

### 4. 配置站点

编辑 `config.yml` 文件，配置站点信息和主题参数。

### 5. 创建文章

```bash
hugo new posts/hello-world.md
```

### 6. 本地预览

```bash
hugo server -D
```

## 未来计划

- ✅ 完成博客基础搭建
- ⬜ 集成 Giscus 评论系统
- ⬜ 部署到 GitHub Pages
- ⬜ 配置自定义域名
- ⬜ 添加 Google Analytics
- ⬜ 优化 SEO
- ⬜ 启用多语言支持

## 写作计划

接下来计划分享以下内容：

1. **技术教程** - 开发过程中的实践经验
2. **读书笔记** - 技术书籍阅读心得
3. **项目分享** - 个人项目和开源贡献
4. **工具推荐** - 提高效率的工具和方法

## 结语

终于有了自己的技术博客，可以记录和分享技术心得了。

希望能坚持更新，让这个博客成为我技术成长的见证。

如果你也想搭建自己的博客，Hugo 是一个不错的选择！

---

**欢迎留言交流！** 📝
