---
title: Grades de recursos
weight: 3
---

# Grades de recursos

Mostre os recursos do seu produto com layouts de grade visualmente atraentes.

## Grade de recursos com ícones

Exiba recursos com ícones em uma grade responsiva:

```yaml
# Em data/features.yaml
features:
  - title: "Ultrarrápido"
    description: "Construído para velocidade com desempenho otimizado"
    icon: "zap"

  - title: "Seguro por padrão"
    description: "Segurança de nível empresarial integrada"
    icon: "shield"

  - title: "Integração fácil"
    description: "Conecte-se com suas ferramentas favoritas"
    icon: "plug"

  - title: "Suporte 24/7"
    description: "Estamos aqui quando você precisar"
    icon: "headphones"
```

## Recurso com capturas de tela

Alterne entre texto e imagens para recursos detalhados:

```yaml
sections:
  - title: "Painel poderoso"
    description: "Obtenha insights rapidamente com nosso painel intuitivo"
    image: "/images/dashboard.png"
    imagePosition: "right"

  - title: "Colaboração em equipe"
    description: "Trabalhe junto perfeitamente com atualizações em tempo real"
    image: "/images/collaboration.png"
    imagePosition: "left"
```

## Colunas da grade

Controle o número de colunas na sua grade de recursos:

```html
{{</* features columns="3" */>}}
```

Opções: `2`, `3` ou `4` colunas. A grade se ajusta automaticamente para dispositivos móveis.
