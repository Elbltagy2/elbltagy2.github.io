# Ahmed Elbltagy — Portfolio Site

A single-file, dependency-free portfolio site (`index.html`). No build step — just open it or host it.

## Preview locally
Open the file directly in a browser:
```bash
open index.html        # macOS
```
Or run a tiny local server (nicer for testing):
```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Before you publish — one edit
Open `index.html` and replace the placeholder email in the contact section:
```html
<!-- TODO: replace with your real freelance email -->
<a class="btn btn-light" href="mailto:your.email@example.com">Email me ...
```
Swap `your.email@example.com` for the email you want clients to use.
(GitHub links are already set to github.com/Elbltagy2.)

## Deploy — free options

### Option A — GitHub Pages
1. Create a repo (or reuse your existing `portfolio` repo).
2. Put `index.html` at the repo root and push.
3. On GitHub: **Settings → Pages → Source: Deploy from a branch → `main` / root**.
4. Your site goes live at `https://elbltagy2.github.io/<repo-name>/`.

For a clean URL, name the repo `elbltagy2.github.io` → it serves at `https://elbltagy2.github.io/`.

### Option B — Vercel (drag & drop)
1. Go to vercel.com → **Add New → Project**.
2. Import the repo (or drag the folder into the dashboard).
3. No framework, no build command needed — Vercel serves the static file.
4. You get a `*.vercel.app` URL instantly; add a custom domain later if you want.

### Option C — Netlify
Drag the `portfolio-site` folder onto app.netlify.com/drop — live in seconds.

## Updating content
All content lives in `index.html`:
- **Featured builds** → the `<article class="build">` blocks.
- **More work** → the `<a class="mini">` blocks.
- **Stack** → the `<ul class="stack-list">` lists.
- **About / Contact** → near the bottom.

Add a project by copying one existing block and editing the name, description, tech chips, and GitHub link.
