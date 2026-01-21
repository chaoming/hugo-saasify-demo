---
title: 分析集成
weight: 1
---

# 分析集成

使用流行的分析平台跟踪您的网站表现。

## Google Analytics 4

添加您的GA4测量ID以启用跟踪：

```toml
# hugo.toml
[params.analytics]
  googleAnalytics = "G-XXXXXXXXXX"
```

## Plausible Analytics

对于注重隐私的分析，使用Plausible：

```toml
[params.analytics]
  plausible = "yourdomain.com"
```

## 自定义事件

跟踪自定义事件，如按钮点击和表单提交：

```javascript
// 跟踪注册按钮点击
plausible('Signup', { props: { plan: 'pro' } });

// 或使用Google Analytics
gtag('event', 'signup', { plan: 'pro' });
```

## 隐私考虑

Hugo Saasify尊重用户隐私：

- 分析脚本仅在cookie同意后加载（如果启用）
- 主题本身不收集任何个人数据
- 您控制发送给第三方服务的数据
