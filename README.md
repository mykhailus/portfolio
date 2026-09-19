# mykhailus.netlify.app

Personal portfolio of **Mykhailo Yatsenko** — AI creator, 15+ years in video production.

**Live:** https://mykhailus.netlify.app

## What this is

A single self-contained page, hand-written, no build step and no framework — one `index.html` plus image assets. Dark/light sections alternate, everything is JetBrains Mono, the accent is a single red.

Built with Claude Code as a working session, not generated from a template.

## Details worth a look

- **Interactive dot cloud** — a page-wide canvas field where points drift, link into constellations, scatter away from the cursor and spring back.
- **Scramble headings** — section titles decode themselves from noise as they enter the viewport.
- **Custom cursor** in the research section — a crosshair with a full-height hairline and a soft red glow, replacing the pointer entirely.
- **Lite YouTube embeds** — thumbnails load first, the player is injected only on click, so the page stays light.
- **Blurred toolbox rows** that sharpen under the cursor.
- **Live X embeds**, a scroll-progress hairline and a seamless marquee.

## Structure

```
index.html          the whole page — markup, styles and scripts
photo.jpg           portrait
art-*.jpg           article covers
cert-*.jpg          certificates
moonwalkers.jpg     NFT collection
nft-singularity.jpg NFT collection
favicon.png         circular favicon
```

## Deploy

```bash
netlify deploy --prod --dir .
```

Hosted on Netlify. No pipeline, no CI — the folder is the artifact.
