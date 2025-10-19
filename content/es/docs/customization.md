---
title: Personalización
weight: 3
---

# Personalización

Aprende a personalizar tu tema Hugo Saasify para que coincida con tu marca.

## Colores

Puedes personalizar los colores en `tailwind.config.js`:

```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        primary: '#6366f1',
        secondary: '#8b5cf6',
      }
    }
  }
}
```

## Tipografía

Personaliza las fuentes y la tipografía en tu configuración de sitio o la configuración de TailwindCSS.

## Diseños

Anula cualquier diseño creando un archivo con la misma ruta en tu directorio `layouts`.

## Componentes

Todos los componentes están construidos con TailwindCSS, lo que los hace fáciles de personalizar.
