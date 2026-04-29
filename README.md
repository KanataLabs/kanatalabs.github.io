# Kanata Labs — Corporate Site

Source for **kanatalabs.com**, the corporate website for Kanata Labs LLC, an
independent software and games studio.

Built with [Astro](https://astro.build/) and deployed to GitHub Pages via the
workflow in `.github/workflows/`.

## Pages

- `/` — landing page (Hero + capabilities + company snapshot + CTA)
- `/about` — about the company
- `/services` — software development, game development, game operations, consulting
- `/contact` — contact form (mailto)
- `/privacy` — Privacy Policy
- `/terms` — Terms of Use

## Project structure

```text
src/
├── components/   reusable UI (Header, Hero, Footer, ...)
├── layouts/      base HTML layout, global styles, GA4 tag
├── pages/        routed pages (one .astro per route)
└── scripts/      client-side TS
public/           static assets served as-is
```

## Commands

| Command         | Action                                   |
| :-------------- | :--------------------------------------- |
| `pnpm install`  | Install dependencies                     |
| `pnpm dev`      | Local dev server on `localhost:4321`     |
| `pnpm build`    | Build to `./dist/`                       |
| `pnpm preview`  | Preview the production build locally     |
