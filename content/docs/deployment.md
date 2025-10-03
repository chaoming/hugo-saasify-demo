---
title: Deployment
weight: 4
---

# Deployment

Deploy your Hugo Saasify site to various platforms.

## Netlify

The easiest way to deploy:

1. Push your site to GitHub
2. Connect your repo to Netlify
3. Set build command: `hugo --minify`
4. Set publish directory: `public`

## Vercel

Deploy with Vercel:

```bash
vercel deploy
```

## GitHub Pages

Deploy to GitHub Pages:

1. Configure `baseURL` in your config
2. Build with `hugo --minify`
3. Push `public` directory to gh-pages branch

## Self-Hosting

Build your site:

```bash
hugo --minify
```

Upload the `public` directory to your web server.
