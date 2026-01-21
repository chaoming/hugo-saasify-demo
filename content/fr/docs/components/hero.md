---
title: Sections Hero
weight: 1
---

# Sections Hero

La section hero est la première chose que les visiteurs voient sur votre page d'atterrissage. Hugo Saasify fournit plusieurs variantes de hero pour correspondre à votre marque.

## Hero par défaut

Le hero par défaut inclut un titre, une description et des boutons d'appel à l'action :

```yaml
# Dans le front matter de votre page
hero:
  title: "Construisez quelque chose d'incroyable"
  description: "Démarrez votre projet avec notre puissante plateforme"
  buttons:
    - text: "Commencer"
      url: "/signup"
      primary: true
    - text: "En savoir plus"
      url: "/docs"
```

## Hero avec image

Ajoutez une capture d'écran de produit ou une illustration à côté de votre texte :

```yaml
hero:
  title: "Nom de votre produit"
  description: "Une brève description de ce que vous offrez"
  image: "/images/hero-screenshot.png"
```

## Hero avec vidéo

Intégrez une vidéo pour démontrer votre produit :

```yaml
hero:
  title: "Voyez-le en action"
  video_url: "https://youtube.com/watch?v=..."
```

## Personnalisation

Vous pouvez personnaliser les couleurs, l'espacement et les animations dans votre `tailwind.config.js` ou en surchargeant le partial hero dans vos mises en page.
