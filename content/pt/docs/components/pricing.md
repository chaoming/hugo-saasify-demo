---
title: Tabelas de preços
weight: 2
---

# Tabelas de preços

Exiba seus planos de preços com tabelas bonitas e otimizadas para conversão.

## Tabela de preços básica

Configure seus planos de preços em `data/pricing.yaml`:

```yaml
plans:
  - name: Starter
    price: 9
    period: month
    features:
      - "5 Projetos"
      - "10GB Armazenamento"
      - "Suporte por email"
    cta:
      text: "Teste grátis"
      url: "/signup?plan=starter"

  - name: Pro
    price: 29
    period: month
    featured: true
    features:
      - "Projetos ilimitados"
      - "100GB Armazenamento"
      - "Suporte prioritário"
      - "Análises avançadas"
    cta:
      text: "Teste grátis"
      url: "/signup?plan=pro"

  - name: Enterprise
    price: 99
    period: month
    features:
      - "Tudo no Pro"
      - "Armazenamento ilimitado"
      - "Suporte telefônico 24/7"
      - "Integrações personalizadas"
      - "Garantia SLA"
    cta:
      text: "Contatar vendas"
      url: "/contact"
```

## Alternador anual vs mensal

Habilite o alternador de preços para mostrar preços anuais e mensais:

```yaml
# Em hugo.toml
[params.pricing]
  showToggle = true
  annualDiscount = 20
```

## Destacar um plano

Adicione `featured: true` para destacar seu plano recomendado com um selo especial e estilo distinto.
