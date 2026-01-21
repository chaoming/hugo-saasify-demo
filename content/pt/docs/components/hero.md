---
title: Seções Hero
weight: 1
---

# Seções Hero

A seção hero é a primeira coisa que os visitantes veem em sua página de destino. Hugo Saasify fornece várias variantes de hero para combinar com sua marca.

## Hero padrão

O hero padrão inclui um título, descrição e botões de chamada para ação:

```yaml
# No front matter da sua página
hero:
  title: "Construa algo incrível"
  description: "Comece seu projeto com nossa poderosa plataforma"
  buttons:
    - text: "Começar"
      url: "/signup"
      primary: true
    - text: "Saiba mais"
      url: "/docs"
```

## Hero com imagem

Adicione uma captura de tela do produto ou ilustração ao lado do seu texto:

```yaml
hero:
  title: "Nome do seu produto"
  description: "Uma breve descrição do que você oferece"
  image: "/images/hero-screenshot.png"
```

## Hero com vídeo

Incorpore um vídeo para demonstrar seu produto:

```yaml
hero:
  title: "Veja em ação"
  video_url: "https://youtube.com/watch?v=..."
```

## Personalização

Você pode personalizar cores, espaçamento e animações no seu `tailwind.config.js` ou sobrescrevendo o partial hero nos seus layouts.
