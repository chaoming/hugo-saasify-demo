---
title: Preistabellen
weight: 2
---

# Preistabellen

Zeigen Sie Ihre Preispläne mit schönen, konversionsoptimierten Tabellen an.

## Einfache Preistabelle

Konfigurieren Sie Ihre Preispläne in `data/pricing.yaml`:

```yaml
plans:
  - name: Starter
    price: 9
    period: month
    features:
      - "5 Projekte"
      - "10GB Speicher"
      - "E-Mail-Support"
    cta:
      text: "Kostenlos testen"
      url: "/signup?plan=starter"

  - name: Pro
    price: 29
    period: month
    featured: true
    features:
      - "Unbegrenzte Projekte"
      - "100GB Speicher"
      - "Prioritäts-Support"
      - "Erweiterte Analysen"
    cta:
      text: "Kostenlos testen"
      url: "/signup?plan=pro"

  - name: Enterprise
    price: 99
    period: month
    features:
      - "Alles in Pro"
      - "Unbegrenzter Speicher"
      - "24/7 Telefon-Support"
      - "Benutzerdefinierte Integrationen"
      - "SLA-Garantie"
    cta:
      text: "Vertrieb kontaktieren"
      url: "/contact"
```

## Jährlich vs. Monatlich Umschalter

Aktivieren Sie den Preisumschalter, um sowohl jährliche als auch monatliche Preise anzuzeigen:

```yaml
# In hugo.toml
[params.pricing]
  showToggle = true
  annualDiscount = 20
```

## Plan hervorheben

Fügen Sie `featured: true` hinzu, um Ihren empfohlenen Plan mit einem speziellen Badge und Styling hervorzuheben.
