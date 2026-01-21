---
title: Integrações de formulários
weight: 2
---

# Integrações de formulários

Colete dados de usuários com vários serviços backend de formulários.

## Formspree

A maneira mais fácil de lidar com envios de formulários:

```toml
# hugo.toml
[params.forms]
  provider = "formspree"
  formspreeId = "xyzabcde"
```

Então use o shortcode do formulário de contato:

```markdown
{{</* contact-form */>}}
```

## Netlify Forms

Se hospedado no Netlify, os formulários funcionam automaticamente:

```toml
[params.forms]
  provider = "netlify"
```

Adicione o atributo `netlify` aos seus formulários:

```html
<form name="contact" method="POST" data-netlify="true">
  <!-- campos do formulário -->
</form>
```

## Webhook personalizado

Envie dados do formulário para seu próprio backend:

```toml
[params.forms]
  provider = "webhook"
  webhookUrl = "https://api.yoursite.com/forms"
```

## Proteção anti-spam

Habilite reCAPTCHA ou campos honeypot:

```toml
[params.forms]
  honeypot = true
  recaptchaSiteKey = "your-site-key"
```
