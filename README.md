# Romania Relocation Guide

Complete multilingual guide for relocating to Romania - immigration, taxes, and daily life.

## 🌐 Live Site

**Access the document online:**
- 🇺🇦 [Ukrainian version](https://pokalchukkk.github.io/romania-relocation-guide/ua/)
- 🇷🇺 [Russian version](https://pokalchukkk.github.io/romania-relocation-guide/ru/)

## Languages

- 🇺🇦 [Ukrainian](ua/) - Основна мова
- 🇷🇺 [Russian](ru/) - Русская версия

## Features

- **Multilingual support** with Jekyll and Liquid templates
- **Language switcher** component
- **Responsive design** for mobile and desktop
- **SEO optimized** with meta tags and sitemap
- **GitHub Pages ready** with proper configuration

## Structure

```
PersonalAgent/
├── _includes/common/          # Common components
│   ├── gtm-body.html         # Google Tag Manager
│   ├── common.css            # Common styles
│   └── language-switcher.html # Language switcher
├── _layouts/
│   └── default.html          # Main layout
├── ua/                       # Ukrainian content
├── ru/                       # Russian content
├── _config.yml               # Jekyll configuration
├── Gemfile                   # Ruby dependencies
└── index.md                  # English homepage
```

## Local Development

1. Install Ruby and Bundler
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Start Jekyll server:
   ```bash
   bundle exec jekyll serve
   ```
4. Open http://localhost:4000

## Deployment

This site is configured for GitHub Pages deployment. Simply push to the `main` branch and GitHub Pages will automatically build and deploy the site.

## Content Management

- Update content in respective language folders (`ua/`, `ru/`)
- Use the language switcher component for navigation
- Maintain consistency across all language versions
- Update `last_modified` dates when making changes
- **Primary source**: `ua/index.md` (Ukrainian version)
- **Auto-sync**: When updating `ua/index.md`, automatically update `ru/index.md` with Russian translation

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `bundle exec jekyll serve`
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

---
*Last updated: 2025-01-02*
