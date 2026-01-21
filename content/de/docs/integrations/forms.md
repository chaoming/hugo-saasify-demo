---
title: Formular-Integrationen
weight: 2
---

# Formular-Integrationen

Sammeln Sie Benutzerdaten mit verschiedenen Formular-Backend-Diensten.

## Formspree

Der einfachste Weg, Formular-Einreichungen zu verarbeiten:

```toml
# hugo.toml
[params.forms]
  provider = "formspree"
  formspreeId = "xyzabcde"
```

Dann verwenden Sie den Kontaktformular-Shortcode:

```markdown
{{</* contact-form */>}}
```

## Netlify Forms

Beim Hosting auf Netlify funktionieren Formulare automatisch:

```toml
[params.forms]
  provider = "netlify"
```

Fügen Sie das `netlify`-Attribut zu Ihren Formularen hinzu:

```html
<form name="contact" method="POST" data-netlify="true">
  <!-- Formularfelder -->
</form>
```

## Benutzerdefinierter Webhook

Senden Sie Formulardaten an Ihr eigenes Backend:

```toml
[params.forms]
  provider = "webhook"
  webhookUrl = "https://api.yoursite.com/forms"
```

## Spam-Schutz

Aktivieren Sie reCAPTCHA oder Honeypot-Felder:

```toml
[params.forms]
  honeypot = true
  recaptchaSiteKey = "your-site-key"
```
