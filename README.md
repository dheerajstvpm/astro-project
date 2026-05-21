# Astro Project

A starter Astro site built with Astro v5 and Tailwind CSS using the official Vite plugin.

## 🚀 Project overview

This repository includes a lightweight Astro-based website with:
- Astro page routing and layouts
- Reusable components in `src/components`
- Global styles in `src/styles`
- Tailwind CSS integration through `@tailwindcss/vite`
- A Vite-powered dev and build workflow

## 🧩 Project structure

```text
astro.config.mjs        Astro configuration
package.json            Project metadata and scripts
pnpm-lock.yaml          Lockfile for pnpm dependencies
public/                 Static files served at the site root
src/
  assets/               Images and media assets
  components/           Reusable UI components
  layouts/              Layout wrappers for pages
  pages/                Astro route pages
  styles/               Global and component CSS
```

## ⚙️ Requirements

- Node.js 18 or later
- `pnpm` package manager

## 🚀 Getting started

Install dependencies:

```sh
pnpm install
```

Start the local development server:

```sh
pnpm dev
```

Open `http://localhost:4321` in your browser to view the site.

## 🛠️ Available scripts

| Command | Description |
| --- | --- |
| `pnpm dev` | Run Astro in development mode |
| `pnpm build` | Build the production website |
| `pnpm preview` | Preview the built site locally |
| `pnpm astro -- --help` | Show Astro CLI help |

## 📦 Dependencies

- `astro` — framework for building the site
- `tailwindcss` — utility-first CSS framework
- `@tailwindcss/vite` — Tailwind integration for Vite

## 📚 Resources

- Astro docs: https://docs.astro.build
- Tailwind CSS: https://tailwindcss.com
- Astro + Tailwind guide: https://docs.astro.build/en/guides/integrations-guide/tailwind/
