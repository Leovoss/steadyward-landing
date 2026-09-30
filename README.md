# Steadyward website

Static marketing site for Steadyward, a read-only behavioural retention layer for MT4/MT5 brokers.

- `index.html` - landing page (Tailwind, self-hosted fonts, ROI calculator, cookieless Cloudflare Web Analytics)
- `privacy.html`, `cookies.html`, `terms.html` - legal pages
- `images/` - source imagery

## CSS

`assets/styles.css` is compiled from `src/input.css`. Rebuild after changing Tailwind classes:

```
npm run build:css
```

## Hosting

Static files, served as-is from any static host (Cloudflare Pages, GitHub Pages, Netlify).
