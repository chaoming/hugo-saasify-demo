---
title: Hero Sections
weight: 1
---

# Hero Sections

The hero section is the first thing visitors see on your landing page. Hugo Saasify provides several hero variants to match your brand.

## Default Hero

The default hero includes a headline, description, and call-to-action buttons:

```yaml
# In your page front matter
hero:
  title: "Build Something Amazing"
  description: "Start your project with our powerful platform"
  buttons:
    - text: "Get Started"
      url: "/signup"
      primary: true
    - text: "Learn More"
      url: "/docs"
```

## Hero with Image

Add a product screenshot or illustration alongside your copy:

```yaml
hero:
  title: "Your Product Name"
  description: "A brief description of what you offer"
  image: "/images/hero-screenshot.png"
```

## Hero with Video

Embed a video to demonstrate your product:

```yaml
hero:
  title: "See It In Action"
  video_url: "https://youtube.com/watch?v=..."
```

## Customization

You can customize colors, spacing, and animations in your `tailwind.config.js` or by overriding the hero partial in your layouts.
