---
title: 自定义
weight: 3
---

# 自定义

了解如何自定义您的Hugo Saasify主题以匹配您的品牌。

## 颜色

您可以在`tailwind.config.js`中自定义颜色：

```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        primary: '#6366f1',
        secondary: '#8b5cf6',
      }
    }
  }
}
```

## 排版

在您的网站配置或TailwindCSS配置中自定义字体和排版。

## 布局

通过在您的`layouts`目录中创建具有相同路径的文件来覆盖任何布局。

## 组件

所有组件都使用TailwindCSS构建，使其易于自定义。
