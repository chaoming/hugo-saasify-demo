---
title: Pricing Tables
weight: 2
---

# Pricing Tables

Display your pricing plans with beautiful, conversion-optimized tables.

## Basic Pricing Table

Configure your pricing plans in `data/pricing.yaml`:

```yaml
plans:
  - name: Starter
    price: 9
    period: month
    features:
      - "5 Projects"
      - "10GB Storage"
      - "Email Support"
    cta:
      text: "Start Free Trial"
      url: "/signup?plan=starter"

  - name: Pro
    price: 29
    period: month
    featured: true
    features:
      - "Unlimited Projects"
      - "100GB Storage"
      - "Priority Support"
      - "Advanced Analytics"
    cta:
      text: "Start Free Trial"
      url: "/signup?plan=pro"

  - name: Enterprise
    price: 99
    period: month
    features:
      - "Everything in Pro"
      - "Unlimited Storage"
      - "24/7 Phone Support"
      - "Custom Integrations"
      - "SLA Guarantee"
    cta:
      text: "Contact Sales"
      url: "/contact"
```

## Annual vs Monthly Toggle

Enable the pricing toggle to show both annual and monthly prices:

```yaml
# In hugo.toml
[params.pricing]
  showToggle = true
  annualDiscount = 20
```

## Highlighting a Plan

Add `featured: true` to highlight your recommended plan with a special badge and styling.
