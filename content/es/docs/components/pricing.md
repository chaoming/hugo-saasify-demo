---
title: Tablas de precios
weight: 2
---

# Tablas de precios

Muestra tus planes de precios con hermosas tablas optimizadas para conversión.

## Tabla de precios básica

Configura tus planes de precios en `data/pricing.yaml`:

```yaml
plans:
  - name: Starter
    price: 9
    period: month
    features:
      - "5 Proyectos"
      - "10GB Almacenamiento"
      - "Soporte por email"
    cta:
      text: "Prueba gratis"
      url: "/signup?plan=starter"

  - name: Pro
    price: 29
    period: month
    featured: true
    features:
      - "Proyectos ilimitados"
      - "100GB Almacenamiento"
      - "Soporte prioritario"
      - "Análisis avanzado"
    cta:
      text: "Prueba gratis"
      url: "/signup?plan=pro"

  - name: Enterprise
    price: 99
    period: month
    features:
      - "Todo en Pro"
      - "Almacenamiento ilimitado"
      - "Soporte telefónico 24/7"
      - "Integraciones personalizadas"
      - "Garantía SLA"
    cta:
      text: "Contactar ventas"
      url: "/contact"
```

## Alternador anual vs mensual

Habilita el alternador de precios para mostrar precios anuales y mensuales:

```yaml
# En hugo.toml
[params.pricing]
  showToggle = true
  annualDiscount = 20
```

## Destacar un plan

Agrega `featured: true` para destacar tu plan recomendado con una insignia especial y estilo distintivo.
