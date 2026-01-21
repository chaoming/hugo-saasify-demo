---
title: Hero-Bereiche
weight: 1
---

# Hero-Bereiche

Der Hero-Bereich ist das Erste, was Besucher auf Ihrer Landing Page sehen. Hugo Saasify bietet mehrere Hero-Varianten, die zu Ihrer Marke passen.

## Standard-Hero

Der Standard-Hero enthält eine Überschrift, Beschreibung und Call-to-Action-Buttons:

```yaml
# In Ihrem Seiten-Front-Matter
hero:
  title: "Bauen Sie etwas Erstaunliches"
  description: "Starten Sie Ihr Projekt mit unserer leistungsstarken Plattform"
  buttons:
    - text: "Loslegen"
      url: "/signup"
      primary: true
    - text: "Mehr erfahren"
      url: "/docs"
```

## Hero mit Bild

Fügen Sie einen Produkt-Screenshot oder eine Illustration neben Ihrem Text hinzu:

```yaml
hero:
  title: "Ihr Produktname"
  description: "Eine kurze Beschreibung Ihres Angebots"
  image: "/images/hero-screenshot.png"
```

## Hero mit Video

Betten Sie ein Video ein, um Ihr Produkt zu demonstrieren:

```yaml
hero:
  title: "Sehen Sie es in Aktion"
  video_url: "https://youtube.com/watch?v=..."
```

## Anpassung

Sie können Farben, Abstände und Animationen in Ihrer `tailwind.config.js` anpassen oder das Hero-Partial in Ihren Layouts überschreiben.
