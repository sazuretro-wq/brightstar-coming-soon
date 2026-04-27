# BrightStar — Coming Soon

Static under-construction page for **BrightStar Cleaning & Maintenance** (Twin Cities, MN), used while the main site is being rebuilt.

## Stack

Plain HTML + CSS + one SVG logo. No build step, no dependencies.

## Files

```
index.html          — markup + meta
styles.css          — brand tokens, layout, responsive breakpoints
favicon.svg         — BrightStar mark
assets/
  logo.svg          — dark-background variant (white BRIGHT + bright green STAR)
  logo-brand.svg    — original logo on transparent (for light backgrounds)
  hero-bg.svg       — lightweight placeholder background; swap for a photo
```

## Local preview

```bash
python3 -m http.server 4173
# open http://localhost:4173
```

Or just open `index.html` directly in a browser.

## Deploy

Drop-in for any static host — GitHub Pages, Netlify, Vercel, Cloudflare Pages.

### GitHub Pages

Settings → Pages → *Deploy from a branch* → `main` / root.

## Contact

- **Phone**: (651) 592-3468
- **Email**: brightstarmn228@gmail.com
