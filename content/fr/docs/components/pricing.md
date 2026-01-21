---
title: Tableaux de tarification
weight: 2
---

# Tableaux de tarification

Affichez vos plans tarifaires avec de beaux tableaux optimisés pour la conversion.

## Tableau de tarification basique

Configurez vos plans tarifaires dans `data/pricing.yaml` :

```yaml
plans:
  - name: Starter
    price: 9
    period: month
    features:
      - "5 Projets"
      - "10Go Stockage"
      - "Support par email"
    cta:
      text: "Essai gratuit"
      url: "/signup?plan=starter"

  - name: Pro
    price: 29
    period: month
    featured: true
    features:
      - "Projets illimités"
      - "100Go Stockage"
      - "Support prioritaire"
      - "Analyses avancées"
    cta:
      text: "Essai gratuit"
      url: "/signup?plan=pro"

  - name: Enterprise
    price: 99
    period: month
    features:
      - "Tout dans Pro"
      - "Stockage illimité"
      - "Support téléphonique 24/7"
      - "Intégrations personnalisées"
      - "Garantie SLA"
    cta:
      text: "Contacter les ventes"
      url: "/contact"
```

## Bascule annuel vs mensuel

Activez la bascule de tarification pour afficher les prix annuels et mensuels :

```yaml
# Dans hugo.toml
[params.pricing]
  showToggle = true
  annualDiscount = 20
```

## Mise en avant d'un plan

Ajoutez `featured: true` pour mettre en avant votre plan recommandé avec un badge spécial et un style distinctif.
