---
title: Intégrations de formulaires
weight: 2
---

# Intégrations de formulaires

Collectez les données utilisateurs avec divers services backend de formulaires.

## Formspree

Le moyen le plus simple de gérer les soumissions de formulaires :

```toml
# hugo.toml
[params.forms]
  provider = "formspree"
  formspreeId = "xyzabcde"
```

Puis utilisez le shortcode du formulaire de contact :

```markdown
{{</* contact-form */>}}
```

## Netlify Forms

Si hébergé sur Netlify, les formulaires fonctionnent automatiquement :

```toml
[params.forms]
  provider = "netlify"
```

Ajoutez l'attribut `netlify` à vos formulaires :

```html
<form name="contact" method="POST" data-netlify="true">
  <!-- champs du formulaire -->
</form>
```

## Webhook personnalisé

Envoyez les données de formulaire à votre propre backend :

```toml
[params.forms]
  provider = "webhook"
  webhookUrl = "https://api.yoursite.com/forms"
```

## Protection anti-spam

Activez reCAPTCHA ou les champs honeypot :

```toml
[params.forms]
  honeypot = true
  recaptchaSiteKey = "your-site-key"
```
