---
title: Hero区块
weight: 1
---

# Hero区块

Hero区块是访客在着陆页上看到的第一个内容。Hugo Saasify提供多种Hero变体以匹配您的品牌。

## 默认Hero

默认Hero包含标题、描述和行动按钮：

```yaml
# 在页面front matter中
hero:
  title: "构建令人惊叹的产品"
  description: "使用我们强大的平台开始您的项目"
  buttons:
    - text: "开始使用"
      url: "/signup"
      primary: true
    - text: "了解更多"
      url: "/docs"
```

## 带图片的Hero

在文案旁边添加产品截图或插图：

```yaml
hero:
  title: "您的产品名称"
  description: "关于您提供的服务的简要描述"
  image: "/images/hero-screenshot.png"
```

## 带视频的Hero

嵌入视频来演示您的产品：

```yaml
hero:
  title: "观看实际效果"
  video_url: "https://youtube.com/watch?v=..."
```

## 自定义

您可以在`tailwind.config.js`中自定义颜色、间距和动画，或通过在布局中覆盖hero部分来实现。
