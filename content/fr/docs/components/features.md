---
title: Grilles de fonctionnalités
weight: 3
---

# Grilles de fonctionnalités

Présentez les fonctionnalités de votre produit avec des mises en page en grille visuellement attrayantes.

## Grille de fonctionnalités avec icônes

Affichez les fonctionnalités avec des icônes dans une grille réactive :

```yaml
# Dans data/features.yaml
features:
  - title: "Ultra-rapide"
    description: "Conçu pour la vitesse avec des performances optimisées"
    icon: "zap"

  - title: "Sécurisé par défaut"
    description: "Sécurité de niveau entreprise intégrée"
    icon: "shield"

  - title: "Intégration facile"
    description: "Connectez-vous avec vos outils préférés"
    icon: "plug"

  - title: "Support 24/7"
    description: "Nous sommes là quand vous avez besoin de nous"
    icon: "headphones"
```

## Fonctionnalité avec captures d'écran

Alternez entre texte et images pour des fonctionnalités détaillées :

```yaml
sections:
  - title: "Tableau de bord puissant"
    description: "Obtenez des insights en un coup d'œil avec notre tableau de bord intuitif"
    image: "/images/dashboard.png"
    imagePosition: "right"

  - title: "Collaboration d'équipe"
    description: "Travaillez ensemble de manière transparente avec des mises à jour en temps réel"
    image: "/images/collaboration.png"
    imagePosition: "left"
```

## Colonnes de grille

Contrôlez le nombre de colonnes dans votre grille de fonctionnalités :

```html
{{</* features columns="3" */>}}
```

Options : `2`, `3` ou `4` colonnes. La grille s'ajuste automatiquement pour les appareils mobiles.
