---
title: NexT主题安装及配置
categories:
  - 网站设计
  - Hexo
  - NexT主题
tags:
  - 网站设计
  - Hexo
  - NexT主题
date: 2023-04-14 10:33:46
---

## 安装

方法一、

```bash
npm install hexo-theme-next
```

方法二、

```bash
git clone https://github.com/next-theme/hexo-theme-next themes/next
```

## 复制配置文件

复制主题配置文件到站点根目录，命名为：`_config.主题名称.yml`

安装方法一、

```bash
cp node_modules/_config.yml _config.next.yml
```

安装方法二、

```bash
cp themes/next/_config.yml _config.next.yml
```

<!--more-->

## 配置站点

### 设置缓存

```yaml
# Allow to cache content generation.
cache:
  enable: true
```

### 移除非必要文件

```yaml
# Remove unnecessary files after hexo generate.
minify: true
```

### 选择scheme

```yaml
# ---------------------------------------------------------------
# Scheme Settings
# ---------------------------------------------------------------

# Schemes
#scheme: Muse
#scheme: Mist
#scheme: Pisces
scheme: Gemini
```

![Muse Scheme](image-20230414104834967.jpg)

### 边栏控制

> 边栏位置可以在左边，也可以在右边。

```yaml
sidebar:
  # Sidebar Position.
  # position: left
  position: right
```

### 颜色

### 页眉面板颜色

选择深蓝色（默认值："#222"）

```yaml
# Browser header panel color.
theme_color:
  light: "#226"
  dark: "#226"
```

