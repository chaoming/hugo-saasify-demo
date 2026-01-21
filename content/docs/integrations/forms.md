---
title: Forms
weight: 2
---

# Form Integrations

Collect user data with various form backend services.

## Formspree

The easiest way to handle form submissions:

```toml
# hugo.toml
[params.forms]
  provider = "formspree"
  formspreeId = "xyzabcde"
```

Then use the contact form shortcode:

```markdown
{{</* contact-form */>}}
```

## Netlify Forms

If hosting on Netlify, forms work automatically:

```toml
[params.forms]
  provider = "netlify"
```

Add the `netlify` attribute to your forms:

```html
<form name="contact" method="POST" data-netlify="true">
  <!-- form fields -->
</form>
```

## Custom Webhook

Send form data to your own backend:

```toml
[params.forms]
  provider = "webhook"
  webhookUrl = "https://api.yoursite.com/forms"
```

## Spam Protection

Enable reCAPTCHA or honeypot fields:

```toml
[params.forms]
  honeypot = true
  recaptchaSiteKey = "your-site-key"
```
