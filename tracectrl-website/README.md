# TraceCtrl by CloudsineAI — Marketing Strategy Site

A fully static site. No build step, no dependencies.

## Contents

- `index.html` — the strategy hub (Thesis / Brand awareness / Lead gen / Market loop / TraceCtrl kit tabs)
- `artefact-1-tracectrl-landing-page.html` — TraceCtrl product landing page
- `artefact-2-battlecard.html` — competitive battlecard
- `artefact-3-ciso-onepager.html` — CISO one-pager
- `package.json` — optional, only for `npm start` local preview
- `vercel.json` — optional Vercel config

## Run locally

Open `index.html` directly in a browser, or:

```bash
npm start        # serves the folder at http://localhost:3000
```

## Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "TraceCtrl marketing site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Then in the repo: Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save.
Site appears at `https://<your-username>.github.io/<repo-name>/`.

## Deploy to Vercel

Either import the GitHub repo at vercel.com (Framework preset: **Other**, no build command, output directory: root), or:

```bash
npx vercel --prod
```
