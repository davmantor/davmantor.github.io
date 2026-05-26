# David M. Torres-Mendoza

This repository contains the static source for `davidmtorres.com`.

## Structure

- `public/` contains the published HTML, CSS, and assets.
- `docs/` contains the previous MkDocs source and planning notes.
- `.github/workflows/deploy.yml` deploys `public/` directly to GitHub Pages.

## Preview

Open `public/index.html` in a browser, or serve the directory locally:

```powershell
python -m http.server 8000 -d public
```
