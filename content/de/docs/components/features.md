---
title: Feature-Grids
weight: 3
---

# Feature-Grids

Präsentieren Sie Ihre Produktfunktionen mit visuell ansprechenden Grid-Layouts.

## Icon-Feature-Grid

Zeigen Sie Features mit Icons in einem responsiven Grid an:

```yaml
# In data/features.yaml
features:
  - title: "Blitzschnell"
    description: "Für Geschwindigkeit gebaut mit optimierter Leistung"
    icon: "zap"

  - title: "Sicher by Default"
    description: "Enterprise-Grade Sicherheit integriert"
    icon: "shield"

  - title: "Einfache Integration"
    description: "Verbinden Sie sich mit Ihren Lieblings-Tools"
    icon: "plug"

  - title: "24/7 Support"
    description: "Wir sind da, wenn Sie uns brauchen"
    icon: "headphones"
```

## Feature mit Screenshots

Wechseln Sie zwischen Text und Bildern für detaillierte Features:

```yaml
sections:
  - title: "Leistungsstarkes Dashboard"
    description: "Erhalten Sie Einblicke auf einen Blick mit unserem intuitiven Dashboard"
    image: "/images/dashboard.png"
    imagePosition: "right"

  - title: "Team-Zusammenarbeit"
    description: "Arbeiten Sie nahtlos zusammen mit Echtzeit-Updates"
    image: "/images/collaboration.png"
    imagePosition: "left"
```

## Grid-Spalten

Steuern Sie die Anzahl der Spalten in Ihrem Feature-Grid:

```html
{{</* features columns="3" */>}}
```

Optionen: `2`, `3` oder `4` Spalten. Das Grid passt sich automatisch für mobile Geräte an.
