---
title: Integración de Analytics
weight: 1
---

# Integración de Analytics

Rastrea el rendimiento de tu sitio web con plataformas de analytics populares.

## Google Analytics 4

Agrega tu ID de medición de GA4 para habilitar el rastreo:

```toml
# hugo.toml
[params.analytics]
  googleAnalytics = "G-XXXXXXXXXX"
```

## Plausible Analytics

Para analytics enfocados en privacidad, usa Plausible:

```toml
[params.analytics]
  plausible = "yourdomain.com"
```

## Eventos personalizados

Rastrea eventos personalizados como clics de botones y envíos de formularios:

```javascript
// Rastrear un clic en el botón de registro
plausible('Signup', { props: { plan: 'pro' } });

// O con Google Analytics
gtag('event', 'signup', { plan: 'pro' });
```

## Consideraciones de privacidad

Hugo Saasify respeta la privacidad del usuario:

- Los scripts de analytics solo se cargan después del consentimiento de cookies (si está habilitado)
- El tema en sí no recopila datos personales
- Tú controlas qué datos se envían a servicios de terceros
