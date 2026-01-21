---
title: Analytics-Integration
weight: 1
---

# Analytics-Integration

Verfolgen Sie die Leistung Ihrer Website mit beliebten Analytics-Plattformen.

## Google Analytics 4

Fügen Sie Ihre GA4-Mess-ID hinzu, um das Tracking zu aktivieren:

```toml
# hugo.toml
[params.analytics]
  googleAnalytics = "G-XXXXXXXXXX"
```

## Plausible Analytics

Für datenschutzorientierte Analytics verwenden Sie Plausible:

```toml
[params.analytics]
  plausible = "yourdomain.com"
```

## Benutzerdefinierte Events

Verfolgen Sie benutzerdefinierte Events wie Button-Klicks und Formular-Einreichungen:

```javascript
// Einen Signup-Button-Klick verfolgen
plausible('Signup', { props: { plan: 'pro' } });

// Oder mit Google Analytics
gtag('event', 'signup', { plan: 'pro' });
```

## Datenschutzhinweise

Hugo Saasify respektiert die Privatsphäre der Benutzer:

- Analytics-Skripte werden erst nach Cookie-Zustimmung geladen (falls aktiviert)
- Das Theme selbst sammelt keine persönlichen Daten
- Sie kontrollieren, welche Daten an Drittanbieter-Dienste gesendet werden
