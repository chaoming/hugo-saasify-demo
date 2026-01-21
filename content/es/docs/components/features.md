---
title: Grillas de características
weight: 3
---

# Grillas de características

Muestra las características de tu producto con diseños de grilla visualmente atractivos.

## Grilla de características con iconos

Muestra características con iconos en una grilla responsiva:

```yaml
# En data/features.yaml
features:
  - title: "Ultrarrápido"
    description: "Construido para velocidad con rendimiento optimizado"
    icon: "zap"

  - title: "Seguro por defecto"
    description: "Seguridad de nivel empresarial integrada"
    icon: "shield"

  - title: "Integración fácil"
    description: "Conéctate con tus herramientas favoritas"
    icon: "plug"

  - title: "Soporte 24/7"
    description: "Estamos aquí cuando nos necesitas"
    icon: "headphones"
```

## Características con capturas de pantalla

Alterna entre texto e imágenes para características detalladas:

```yaml
sections:
  - title: "Panel de control potente"
    description: "Obtén insights de un vistazo con nuestro panel intuitivo"
    image: "/images/dashboard.png"
    imagePosition: "right"

  - title: "Colaboración en equipo"
    description: "Trabaja junto de manera fluida con actualizaciones en tiempo real"
    image: "/images/collaboration.png"
    imagePosition: "left"
```

## Columnas de grilla

Controla el número de columnas en tu grilla de características:

```html
{{</* features columns="3" */>}}
```

Opciones: `2`, `3` o `4` columnas. La grilla se ajusta automáticamente para dispositivos móviles.
