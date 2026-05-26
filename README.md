# Hilton Chakar

Marketing website for **Hilton Chakar** — serviced apartments in Tangier.

> Status: concept / preview. Currently served as a no-index preview on
> `hilton.knapgemaakt.nl`. Not for public indexing until it moves to the
> client's production domain.

## Tech stack

- **Framework:** Astro 6 (static site generation)
- **Styling:** Tailwind CSS 4 (via `@tailwindcss/vite`)
- **Hosting:** Cloudflare Pages
- **Releases:** Release Please (`release-type: simple`)

## Deploy model

- `main` → production deployment
- `test/*` → preview deployments (no other branch triggers a deploy)

## Local development

```bash
npm install
npm run dev      # local dev server
npm run build    # production build → dist/
```

---

Built by [KNAP GEMAAKT.](https://knapgemaakt.nl)
