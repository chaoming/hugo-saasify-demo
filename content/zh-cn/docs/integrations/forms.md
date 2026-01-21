---
title: 表单集成
weight: 2
---

# 表单集成

使用各种表单后端服务收集用户数据。

## Formspree

处理表单提交最简单的方式：

```toml
# hugo.toml
[params.forms]
  provider = "formspree"
  formspreeId = "xyzabcde"
```

然后使用联系表单短代码：

```markdown
{{</* contact-form */>}}
```

## Netlify Forms

如果托管在Netlify上，表单会自动工作：

```toml
[params.forms]
  provider = "netlify"
```

在表单中添加`netlify`属性：

```html
<form name="contact" method="POST" data-netlify="true">
  <!-- 表单字段 -->
</form>
```

## 自定义Webhook

将表单数据发送到您自己的后端：

```toml
[params.forms]
  provider = "webhook"
  webhookUrl = "https://api.yoursite.com/forms"
```

## 垃圾邮件防护

启用reCAPTCHA或蜜罐字段：

```toml
[params.forms]
  honeypot = true
  recaptchaSiteKey = "your-site-key"
```
