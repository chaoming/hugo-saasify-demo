---
title: Personnalisation
weight: 3
---

# Personnalisation

Apprenez à personnaliser votre thème Hugo Saasify pour qu'il corresponde à votre marque.

## Couleurs

Vous pouvez personnaliser les couleurs dans `tailwind.config.js` :

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

## Typographie

Personnalisez les polices et la typographie dans votre configuration de site ou la configuration TailwindCSS.

## Mises en page

Remplacez n'importe quelle mise en page en créant un fichier avec le même chemin dans votre répertoire `layouts`.

## Composants

Tous les composants sont construits avec TailwindCSS, ce qui les rend faciles à personnaliser.
