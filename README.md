# HMSOP

Static landing page for **Help Me Sweep Original Punks**.

## Deploy

This is a static site. Drop into Vercel, Netlify, Cloudflare Pages, or any static host.

### Vercel

1. Push this repo to GitHub
2. Import at [vercel.com/new](https://vercel.com/new)
3. Framework Preset: **Other**
4. Output directory: leave blank (root)
5. Deploy

Or via CLI:

```bash
npm i -g vercel
vercel --prod
```

## Files

- `index.html` — landing page, self-contained
- `favicon.svg` — favicon (solid V1 lavender pixel)
- `og.png` — 1200×630 share card
- `kenny.png` — placeholder image of the first swept V1 (replace with on-chain V1 metadata in production)
- `vercel.json` — config

## Update before going live

In `index.html`, update these to match your domain:

```html
<meta property="og:url" content="https://hmsop.xyz" />
```

And the footer links to your real X account and contract page once those exist.
