---
title: Secciones Hero
weight: 1
---

# Secciones Hero

La sección hero es lo primero que los visitantes ven en tu página de aterrizaje. Hugo Saasify proporciona varias variantes de hero para que coincidan con tu marca.

## Hero predeterminado

El hero predeterminado incluye un título, descripción y botones de llamada a la acción:

```yaml
# En el front matter de tu página
hero:
  title: "Construye algo increíble"
  description: "Comienza tu proyecto con nuestra poderosa plataforma"
  buttons:
    - text: "Comenzar"
      url: "/signup"
      primary: true
    - text: "Saber más"
      url: "/docs"
```

## Hero con imagen

Agrega una captura de pantalla del producto o ilustración junto a tu texto:

```yaml
hero:
  title: "Nombre de tu producto"
  description: "Una breve descripción de lo que ofreces"
  image: "/images/hero-screenshot.png"
```

## Hero con video

Incrusta un video para demostrar tu producto:

```yaml
hero:
  title: "Míralo en acción"
  video_url: "https://youtube.com/watch?v=..."
```

## Personalización

Puedes personalizar colores, espaciado y animaciones en tu `tailwind.config.js` o anulando el partial hero en tus layouts.
