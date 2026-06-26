# jeremycaris.com

Personal landing page built with [Astro](https://astro.build), deployed to [Cloudflare Pages](https://pages.cloudflare.com).

## Dev

```bash
npm install
npm run dev
```

## Deploy

```bash
npm run build
npx wrangler pages deploy ./dist
```

Or connect the repo to Cloudflare Pages with:
- **Build command:** `npm run build`
- **Output directory:** `dist`

## Card images

Drop replacement images into `public/img/`:

| File | Card |
|---|---|
| `passgrinder.png` | PassGrinder |
| `interpretmydream.png` | Interpret My Dream |
| `fieldguideforlife.png` | Field Guide for Life |
