# Maxime Belotti — Personal Website

Minimal personal website built with [Astro](https://astro.build). A single static page for now, meant to grow.

Live at: https://maximebelotti.com

## Tech stack

- [Astro](https://astro.build) (static output)
- [TypeScript](https://www.typescriptlang.org)
- [`@astrojs/sitemap`](https://docs.astro.build/en/guides/integrations-guide/sitemap/) for automatic sitemap generation

## Project structure

```text
/
├── public/
│   ├── favicon.ico
│   ├── favicon.svg
│   └── robots.txt
├── src/
│   └── pages/
│       └── index.astro
├── astro.config.mts
├── tsconfig.json
└── package.json
```

## Commands

All commands are run from the root of the project:

| Command           | Action                                       |
| :----------------- | :-------------------------------------------- |
| `npm install`       | Installs dependencies                         |
| `npm run dev`       | Starts the local dev server at `localhost:4321` |
| `npm run build`     | Builds the production site to `./dist/`       |
| `npm run preview`   | Previews the production build locally         |
| `npm run check`     | Runs TypeScript type-checking                 |

## SEO

- Canonical URL, meta description, Open Graph and Twitter Card metadata
- `schema.org/Person` JSON-LD structured data
- Auto-generated sitemap (`/sitemap-index.xml`) and `robots.txt`
