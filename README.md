# The Silent War — silentwar.community

A brotherhood for the men still fighting in silence.

Built with [Astro](https://astro.build).

## Quick edits

The whole site lives in three files:

- `src/pages/index.astro` — page content (copy, sections, links)
- `src/styles/global.css` — colors, type, layout
- `src/layouts/Layout.astro` — `<head>`, meta tags, fonts

### Things to update before launch

In `src/pages/index.astro`:

```astro
const DISCORD_URL = '#join';   // <-- replace with real Discord invite link
const INSTAGRAM_URL = 'https://instagram.com/silentwar.community';
const EMAIL = 'silentwarcommunity@gmail.com';
```

## Local dev (optional)

If you ever want to run it locally:

```bash
npm install
npm run dev
```

## Deploy

Pushed to `main` auto-deploys on Vercel.
