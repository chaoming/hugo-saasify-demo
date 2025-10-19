---
title: Despliegue
weight: 4
---

# Despliegue

Despliega tu sitio Hugo Saasify en varias plataformas.

## Netlify

La forma más sencilla de desplegar:

1. Sube tu sitio a GitHub
2. Conecta tu repositorio a Netlify
3. Establece el comando de compilación: `hugo --minify`
4. Establece el directorio de publicación: `public`

## Vercel

Desplegar con Vercel:

```bash
vercel deploy
```

## GitHub Pages

Desplegar en GitHub Pages:

1. Configurar `baseURL` en tu configuración
2. Compilar con `hugo --minify`
3. Subir el directorio `public` a la rama gh-pages

## Auto-alojamiento

Compilar tu sitio:

```bash
hugo --minify
```

Subir el directorio `public` a tu servidor web.
