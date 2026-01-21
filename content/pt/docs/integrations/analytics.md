---
title: Integração de Analytics
weight: 1
---

# Integração de Analytics

Rastreie o desempenho do seu site com plataformas de analytics populares.

## Google Analytics 4

Adicione seu ID de medição do GA4 para habilitar o rastreamento:

```toml
# hugo.toml
[params.analytics]
  googleAnalytics = "G-XXXXXXXXXX"
```

## Plausible Analytics

Para analytics focados em privacidade, use Plausible:

```toml
[params.analytics]
  plausible = "yourdomain.com"
```

## Eventos personalizados

Rastreie eventos personalizados como cliques de botões e envios de formulários:

```javascript
// Rastrear um clique no botão de cadastro
plausible('Signup', { props: { plan: 'pro' } });

// Ou com Google Analytics
gtag('event', 'signup', { plan: 'pro' });
```

## Considerações de privacidade

Hugo Saasify respeita a privacidade do usuário:

- Os scripts de analytics só carregam após o consentimento de cookies (se habilitado)
- O tema em si não coleta dados pessoais
- Você controla quais dados são enviados para serviços de terceiros
