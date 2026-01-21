---
title: 定价表格
weight: 2
---

# 定价表格

使用精美的、转化率优化的表格展示您的定价方案。

## 基础定价表格

在`data/pricing.yaml`中配置您的定价方案：

```yaml
plans:
  - name: 入门版
    price: 9
    period: month
    features:
      - "5个项目"
      - "10GB存储"
      - "邮件支持"
    cta:
      text: "开始免费试用"
      url: "/signup?plan=starter"

  - name: 专业版
    price: 29
    period: month
    featured: true
    features:
      - "无限项目"
      - "100GB存储"
      - "优先支持"
      - "高级分析"
    cta:
      text: "开始免费试用"
      url: "/signup?plan=pro"

  - name: 企业版
    price: 99
    period: month
    features:
      - "专业版所有功能"
      - "无限存储"
      - "24/7电话支持"
      - "自定义集成"
      - "SLA保障"
    cta:
      text: "联系销售"
      url: "/contact"
```

## 年付/月付切换

启用定价切换以同时显示年付和月付价格：

```yaml
# 在hugo.toml中
[params.pricing]
  showToggle = true
  annualDiscount = 20
```

## 突出显示方案

添加`featured: true`以使用特殊徽章和样式突出显示您推荐的方案。
