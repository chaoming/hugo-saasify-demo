---
title: 功能网格
weight: 3
---

# 功能网格

使用视觉吸引力强的网格布局展示您的产品功能。

## 图标功能网格

在响应式网格中展示带图标的功能：

```yaml
# 在data/features.yaml中
features:
  - title: "闪电般快速"
    description: "为速度而生，性能优化"
    icon: "zap"

  - title: "默认安全"
    description: "内置企业级安全性"
    icon: "shield"

  - title: "轻松集成"
    description: "与您喜爱的工具连接"
    icon: "plug"

  - title: "全天候支持"
    description: "我们随时为您服务"
    icon: "headphones"
```

## 带截图的功能展示

交替使用文字和图片来详细介绍功能：

```yaml
sections:
  - title: "强大的仪表板"
    description: "通过直观的仪表板一目了然地获取洞察"
    image: "/images/dashboard.png"
    imagePosition: "right"

  - title: "团队协作"
    description: "通过实时更新无缝协作"
    image: "/images/collaboration.png"
    imagePosition: "left"
```

## 网格列数

控制功能网格的列数：

```html
{{</* features columns="3" */>}}
```

选项：`2`、`3`或`4`列。网格会自动适应移动设备。
