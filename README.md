# CIBAI Studio v4 — Cyberpunk Brutal

Sitio web corporativo de CIBAI Studio con estética **Cyberpunk Brutal**: naranja + teal sobre negro, tipografía monospace, efectos de scan line, glow y animaciones HUD.

## Stack

- **Astro 6** — Static Site Generator
- **Tailwind CSS v4** — Utility-first CSS via Vite plugin
- **TypeScript** — Strict mode
- **@astrojs/sitemap** — SEO sitemap generation

## Estructura

```
src/
  layouts/Layout.astro    — Layout base con head, OG tags, JSON-LD
  pages/
    index.astro           — Single-page principal (todas las secciones)
    privacidad.astro      — Política de privacidad
    aviso-legal.astro     — Aviso legal
    cookies.astro         — Política de cookies
  styles/global.css       — Theme cyberpunk, animaciones, componentes
public/
  favicon.svg             — Favicon SVG
  robots.txt              — Directrices para crawlers
```

## Setup local

```bash
npm install
npm run dev       # Dev server en localhost:4321
npm run build     # Build estático en ./dist/
npm run preview   # Preview local del build
```

## Deploy

Build estático compatible con Vercel, Netlify o cualquier hosting de archivos estáticos.

## Contacto

- Web: [cibai.studio](https://cibai.studio)
- Email: hola@cibai.studio
- Ubicación: Barcelona, España
