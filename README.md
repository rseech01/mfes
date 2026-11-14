# Miami Flat Earth Society

A satirical, single-page site for the (fictional) Miami chapter of the Flat Earth Society.

**This is satire.** The Earth is round. Miami is, however, very flat.

## What's here

- `index.html` contains the whole site: markup, CSS and JavaScript in one file, with no build step.
- Fonts (Monoton, Limelight and Bricolage Grotesque) load from Google Fonts. Everything else is inline.

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

It's a static site, so any static host works:

- **GitHub Pages:** Settings → Pages → deploy from the `main` branch, root folder.
- **Netlify / Vercel / Cloudflare Pages:** point the project at the repo root. There's no build command, and the publish directory is `/`.

## Notes

- The join form only builds a member card in the browser. It doesn't collect or send any data.
- The Flat-o-Meter readings are hard-coded in the `readings` object near the bottom of `index.html`.
