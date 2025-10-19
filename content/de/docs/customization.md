---
title: Anpassung
weight: 3
---

# Anpassung

Erfahren Sie, wie Sie Ihr Hugo Saasify Theme an Ihre Marke anpassen können.

## Farben

Sie können Farben in `tailwind.config.js` anpassen:

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

## Typografie

Passen Sie Schriften und Typografie in Ihrer Site-Konfiguration oder TailwindCSS-Konfiguration an.

## Layouts

Überschreiben Sie jedes Layout, indem Sie eine Datei mit demselben Pfad in Ihrem `layouts`-Verzeichnis erstellen.

## Komponenten

Alle Komponenten sind mit TailwindCSS erstellt, was sie einfach anzupassen macht.
