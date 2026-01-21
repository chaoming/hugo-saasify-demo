---
title: Intégration Analytics
weight: 1
---

# Intégration Analytics

Suivez les performances de votre site web avec les plateformes d'analytics populaires.

## Google Analytics 4

Ajoutez votre ID de mesure GA4 pour activer le suivi :

```toml
# hugo.toml
[params.analytics]
  googleAnalytics = "G-XXXXXXXXXX"
```

## Plausible Analytics

Pour des analytics respectueuses de la vie privée, utilisez Plausible :

```toml
[params.analytics]
  plausible = "yourdomain.com"
```

## Événements personnalisés

Suivez les événements personnalisés comme les clics de boutons et les soumissions de formulaires :

```javascript
// Suivre un clic sur le bouton d'inscription
plausible('Signup', { props: { plan: 'pro' } });

// Ou avec Google Analytics
gtag('event', 'signup', { plan: 'pro' });
```

## Considérations de confidentialité

Hugo Saasify respecte la vie privée des utilisateurs :

- Les scripts d'analytics ne se chargent qu'après le consentement aux cookies (si activé)
- Aucune donnée personnelle n'est collectée par le thème lui-même
- Vous contrôlez quelles données sont envoyées aux services tiers
