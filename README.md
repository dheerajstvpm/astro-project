# Astro Project

A simple Astro site using Tailwind CSS via the Vite plugin.

## 🚀 Overview

This project was created with Astro and includes:
- Astro pages, layouts, and components
- Tailwind CSS support via `@tailwindcss/vite`
- A modern Vite-based build pipeline

## 📁 Project structure

```text
/
├── public/             Static assets served at root
├── src/
│   ├── assets/         Images and media
│   ├── components/     Reusable UI components
│   ├── layouts/        Page layout wrappers
│   └── pages/          Astro route pages
├── astro.config.mjs    Astro configuration
└── package.json        Project metadata and scripts
```

## 🧞 Scripts

Run these commands from the project root.

| Command | Action |
| :------ | :----- |
| `pnpm install` | Install dependencies |
| `pnpm dev` | Start the local development server |
| `pnpm build` | Build the production site |
| `pnpm preview` | Preview the production build locally |
| `pnpm astro -- --help` | Show Astro CLI help |

## 🔧 Development

1. Install dependencies:
   ```sh
   pnpm install
   ```
2. Start the dev server:
   ```sh
   pnpm dev
   ```
3. Open the local site in your browser at `http://localhost:4321`

## 📚 Useful links

- Astro docs: https://docs.astro.build
- Tailwind CSS plugin: https://github.com/tailwindlabs/tailwindcss/tree/main/packages/vite
