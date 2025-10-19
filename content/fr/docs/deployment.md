---
title: Déploiement
weight: 4
---

# Déploiement

Déployez votre site Hugo Saasify sur diverses plateformes.

## Netlify

Le moyen le plus simple de déployer :

1. Poussez votre site sur GitHub
2. Connectez votre dépôt à Netlify
3. Définir la commande de build : `hugo --minify`
4. Définir le répertoire de publication : `public`

## Vercel

Déployer avec Vercel :

```bash
vercel deploy
```

## GitHub Pages

Déployer sur GitHub Pages :

1. Configurer `baseURL` dans votre configuration
2. Compiler avec `hugo --minify`
3. Pousser le répertoire `public` vers la branche gh-pages

## Auto-hébergement

Compiler votre site :

```bash
hugo --minify
```

Télécharger le répertoire `public` sur votre serveur web.
