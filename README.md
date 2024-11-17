# Hugo Saasify Demo

This repository serves as the demo site for the [Hugo Saasify Theme](https://github.com/yourusername/hugo-saasify-theme), showcasing its features and capabilities in a real-world context. It's designed to help users understand how to implement and customize the theme for their own SaaS websites.

## Overview

This demo site demonstrates:
- Basic theme setup and configuration
- Common use cases for SaaS websites
- Theme customization examples
- Content organization patterns

## Quick Start

1. Clone this repository:
   ```bash
   git clone --recursive https://github.com/yourusername/hugo-saasify-demo
   ```

2. Navigate to the project directory:
   ```bash
   cd hugo-saasify-demo
   ```

3. Start the Hugo server:
   ```bash
   hugo server -D
   ```

4. Open your browser and visit: http://localhost:1313

## Structure

```
.
├── content/          # Site content
├── hugo.toml         # Site configuration
└── themes/
    └── hugo-saasify-theme/  # Theme submodule
```

## Content Management

- Content is organized in the `content/` directory
- The homepage is configured through `content/_index.md`
- Site settings can be customized in `hugo.toml`

## Theme

This demo site uses the Hugo Saasify Theme as a Git submodule. The theme is located in `themes/hugo-saasify-theme/` and can be updated using standard Git submodule commands.

## License

MIT
