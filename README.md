# Thiranix.ai website

## Tech stack
Plain **HTML, CSS and JavaScript** in a single file (`index.html`).
No React, no Vite, no Next.js, no npm packages, no build step.

## Files
- `index.html` – the whole website (HTML + inline CSS + inline JavaScript)
- `favicon.svg` – the browser tab icon (the hexagon "T" logo)
- `README.md` – this file

## Run it
Double-click `index.html`, or drag it into any browser. Nothing to install.

## Dependencies
The only external resource is **Google Fonts** (Bricolage Grotesque and Instrument Sans),
loaded by a `<link>` tag in `<head>`. It needs internet access. Offline, the page falls back
to system fonts and still works. All images and icons are inline SVG.

## Put it online
Upload this folder to any static host: Netlify (drag and drop), Cloudflare Pages,
GitHub Pages or Vercel. Then connect your domain and add the site to Google Search Console
so Google can index it.

## Things you may want to edit (search in index.html)
- Contact email: `thiranix.ai.company.pvt@gmail.com` (appears twice)
- Footer year and founder name: `© 2035 Thiranix.ai. Founded by Krishna Moorthy Abishek.`
- Colours: the `:root{...}` block at the top of the `<style>`
- Product text: the `id="products"` section
