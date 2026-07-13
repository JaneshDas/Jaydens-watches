# Meridian Timepieces

A single-page site for a watch and strap storefront concept, featuring:

- A hero section with a live SVG clock face
- A watches section showcasing two models with specs and pricing
- A strap library with filters for color, leather type, and size

## Running locally

This is a static site — no build step, no dependencies. Just open `index.html`
in a browser, or serve the folder with any static file server, e.g.:

```
npx serve .
```

## Deploying

Any static host works. A few easy options:

- **GitHub Pages** — Settings → Pages → set source to this branch, root folder
- **Netlify** — drag this folder into [app.netlify.com/drop](https://app.netlify.com/drop)
- **Vercel** — `vercel deploy` from this folder (with the Vercel CLI installed)
- **Cloudflare Pages** — connect this repo in the Cloudflare dashboard

## Structure

```
.
├── index.html   # the entire site (HTML, CSS, and JS inline)
└── README.md
```
