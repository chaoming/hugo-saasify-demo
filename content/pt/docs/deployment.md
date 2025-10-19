---
title: Implantação
weight: 4
---

# Implantação

Implante seu site Hugo Saasify em várias plataformas.

## Netlify

A maneira mais fácil de implantar:

1. Envie seu site para o GitHub
2. Conecte seu repositório ao Netlify
3. Defina o comando de build: `hugo --minify`
4. Defina o diretório de publicação: `public`

## Vercel

Implantar com Vercel:

```bash
vercel deploy
```

## GitHub Pages

Implantar no GitHub Pages:

1. Configure `baseURL` em sua configuração
2. Compile com `hugo --minify`
3. Envie o diretório `public` para o branch gh-pages

## Auto-hospedagem

Compile seu site:

```bash
hugo --minify
```

Envie o diretório `public` para seu servidor web.
