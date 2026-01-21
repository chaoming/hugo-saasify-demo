---
title: Feature Grids
weight: 3
---

# Feature Grids

Showcase your product features with visually appealing grid layouts.

## Icon Feature Grid

Display features with icons in a responsive grid:

```yaml
# In data/features.yaml
features:
  - title: "Lightning Fast"
    description: "Built for speed with optimized performance"
    icon: "zap"

  - title: "Secure by Default"
    description: "Enterprise-grade security built in"
    icon: "shield"

  - title: "Easy Integration"
    description: "Connect with your favorite tools"
    icon: "plug"

  - title: "24/7 Support"
    description: "We're here when you need us"
    icon: "headphones"
```

## Feature with Screenshots

Alternate between text and images for detailed features:

```yaml
sections:
  - title: "Powerful Dashboard"
    description: "Get insights at a glance with our intuitive dashboard"
    image: "/images/dashboard.png"
    imagePosition: "right"

  - title: "Team Collaboration"
    description: "Work together seamlessly with real-time updates"
    image: "/images/collaboration.png"
    imagePosition: "left"
```

## Grid Columns

Control the number of columns in your feature grid:

```html
{{</* features columns="3" */>}}
```

Options: `2`, `3`, or `4` columns. The grid automatically adjusts for mobile devices.
