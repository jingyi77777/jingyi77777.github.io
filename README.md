# Jin Huang — Personal Website

A clean, single-page personal website for career purposes, built with plain HTML, CSS, and JavaScript — no build step, no dependencies.

## Structure

- `index.html` — all content (hero, about, experience, projects, skills, education, contact)
- `styles.css` — light-theme styling, responsive down to 375px
- `script.js` — scroll-reveal animations and mobile nav toggle

## Run locally

Open `index.html` directly in a browser, or serve it:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy

This site is fully static, so it can be hosted for free on:

- **GitHub Pages** — push to a repo named `<username>.github.io`, or enable Pages in repo settings
- **Netlify / Vercel / Cloudflare Pages** — drag-and-drop or connect the repo

## Updating content

All content lives in `index.html`. Edit the relevant section (each is marked with an HTML comment) and refresh.
