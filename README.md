# PROTEGO Detailing — Landing Page

Landing page for PROTEGO DETAILING (Nano Ceramic Coating, PPF & Rust Protection in Cipondoh, Tangerang). Designed in Claude Design, served as a static site with [Astro](https://astro.build).

## Commands

| Command           | Action                                     |
| :---------------- | :----------------------------------------- |
| `npm install`     | Install dependencies                       |
| `npm run dev`     | Start the dev server at `localhost:4321`   |
| `npm run build`   | Build the static site to `./dist/`         |
| `npm run preview` | Preview the production build locally       |

## Project structure

```text
/
├── docs/
│   └── DESIGN.md               Design brief given to Claude Design
├── originals/                  Full-size source photos (git-ignored)
├── public/
│   ├── favicon.ico
│   ├── apple-touch-icon.png
│   └── images/                 Web-optimized WebP images
│       ├── brand/              Logo
│       ├── hero/               Hero photo
│       ├── reviews/            Influencer reel covers
│       └── studio/             Studio Experience photos
└── src/
    ├── design/
    │   ├── protego.html        Page markup + all display text  ← edit this
    │   └── protego.assets.json Embedded fonts + runtime scripts (generated)
    └── pages/
        └── index.astro         Inlines the two design files at build time
```

## Editing text

All copy lives in `src/design/protego.html`. Search for these names:

| What                                          | Where                                                          |
| :-------------------------------------------- | :------------------------------------------------------------- |
| Page title and meta description (SEO)         | `<title>` and `<meta name="description">` at the top           |
| Bilingual copy (most sentences)               | `T = { ID: {…}, EN: {…} }` — keep the same keys in both        |
| Packages and pricing                          | `PKGS`                                                         |
| Google review quotes                          | `REVIEWS`                                                      |
| Influencer reels (captions and cover images)  | `REELS`                                                        |
| WhatsApp number and Google Maps links         | `WA`, `MAPS`, `ROUTE`                                          |
| Fixed labels (e.g. "INFLUENCER SPOTLIGHT", ©) | Directly in the HTML markup                                    |

Strings in the script block use single quotes, so write `\'` for an apostrophe inside one. `{{ … }}` in the markup are template bindings — leave them in place.

## Images

The page references images as `/images/<folder>/<name>.webp`. To add or replace a photo, keep the full-size file in `originals/`, export a resized WebP (900–1920 px wide, quality ~80) into `public/images/`, and update the path in `protego.html` (for reels, the `img` field in `REELS`).

## Deploy

Static output, so it deploys to Vercel with no adapter: import the GitHub repo and keep the detected Astro defaults (build `npm run build`, output `dist`).
