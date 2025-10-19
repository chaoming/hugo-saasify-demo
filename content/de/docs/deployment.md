---
title: Bereitstellung
weight: 4
---

# Bereitstellung

Stellen Sie Ihre Hugo Saasify Site auf verschiedenen Plattformen bereit.

## Netlify

Der einfachste Weg zur Bereitstellung:

1. Pushen Sie Ihre Site zu GitHub
2. Verbinden Sie Ihr Repo mit Netlify
3. Setzen Sie Build-Befehl: `hugo --minify`
4. Setzen Sie Publish-Verzeichnis: `public`

## Vercel

Bereitstellen mit Vercel:

```bash
vercel deploy
```

## GitHub Pages

Bereitstellen auf GitHub Pages:

1. Konfigurieren Sie `baseURL` in Ihrer Konfiguration
2. Builden Sie mit `hugo --minify`
3. Pushen Sie das `public`-Verzeichnis zum gh-pages Branch

## Self-Hosting

Builden Sie Ihre Site:

```bash
hugo --minify
```

Laden Sie das `public`-Verzeichnis auf Ihren Webserver hoch.
