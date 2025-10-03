---
title: Customization
weight: 3
---

# Customization

Learn how to customize your Hugo Saasify theme to match your brand.

## Colors

You can customize colors in `tailwind.config.js`:

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

## Typography

Customize fonts and typography in your site configuration or TailwindCSS config.

## Layouts

Override any layout by creating a file with the same path in your `layouts` directory.

## Components

All components are built with TailwindCSS, making them easy to customize.
