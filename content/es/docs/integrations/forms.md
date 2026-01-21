---
title: Integraciones de formularios
weight: 2
---

# Integraciones de formularios

Recopila datos de usuarios con varios servicios backend de formularios.

## Formspree

La forma más fácil de manejar envíos de formularios:

```toml
# hugo.toml
[params.forms]
  provider = "formspree"
  formspreeId = "xyzabcde"
```

Luego usa el shortcode del formulario de contacto:

```markdown
{{</* contact-form */>}}
```

## Netlify Forms

Si hospedas en Netlify, los formularios funcionan automáticamente:

```toml
[params.forms]
  provider = "netlify"
```

Agrega el atributo `netlify` a tus formularios:

```html
<form name="contact" method="POST" data-netlify="true">
  <!-- campos del formulario -->
</form>
```

## Webhook personalizado

Envía datos del formulario a tu propio backend:

```toml
[params.forms]
  provider = "webhook"
  webhookUrl = "https://api.yoursite.com/forms"
```

## Protección anti-spam

Habilita reCAPTCHA o campos honeypot:

```toml
[params.forms]
  honeypot = true
  recaptchaSiteKey = "your-site-key"
```
