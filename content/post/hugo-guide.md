---
title: "Hugo快速入门指南"
description: "学习如何使用Hugo创建静态网站"
date: 2025-01-21T14:30:00+08:00
categories:
    - "教程"
tags:
    - "Hugo"
    - "静态网站"
    - "教程"
# image: "images/hugo-logo.png"
---

## Hugo简介

Hugo是用Go语言编写的静态网站生成器，以其极快的构建速度而闻名。

### 主要特性

- **极速构建**: 毫秒级的页面生成
- **零依赖**: 单个二进制文件，无需额外依赖
- **灵活配置**: 支持多种配置格式
- **丰富主题**: 大量现成主题可选

### 基本命令

```bash
# 创建新站点
hugo new site mysite

# 创建新文章
hugo new posts/my-first-post.md

# 本地预览
hugo server

# 构建站点
hugo
```

### 目录结构

```
mysite/
├── archetypes/
├── content/
├── data/
├── layouts/
├── static/
├── themes/
└── config.yaml
```

这就是Hugo的基本使用方法，希望对你有帮助！