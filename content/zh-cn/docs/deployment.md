---
title: 部署
weight: 4
---

# 部署

将您的Hugo Saasify网站部署到各种平台。

## Netlify

最简单的部署方式：

1. 将您的网站推送到GitHub
2. 将您的仓库连接到Netlify
3. 设置构建命令：`hugo --minify`
4. 设置发布目录：`public`

## Vercel

使用Vercel部署：

```bash
vercel deploy
```

## GitHub Pages

部署到GitHub Pages：

1. 在配置中配置`baseURL`
2. 使用`hugo --minify`构建
3. 将`public`目录推送到gh-pages分支

## 自托管

构建您的网站：

```bash
hugo --minify
```

将`public`目录上传到您的Web服务器。
