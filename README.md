# Quarterly Earnings — RevealJS Deck

This is a ready-to-publish Reveal.js presentation showcasing:
- Markdown slides
- Animated fragments
- Syntax-highlighted code
- Mathematical equations (KaTeX)
- Speaker notes
- Student email: **24f2005754@ds.study.iitm.ac.in**

## Quick Start
1. **Create a new GitHub repository** named `quarterly-earnings` (or any name you like).
2. Upload these files to the repo root.
3. In **Settings → Pages**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (root `/`), then **Save**.
4. Your deck will be live at:
   ```
   https://YOUR-USERNAME.github.io/REPO-NAME/
   ```
   If you use `quarterly-earnings` as the repo name:
   ```
   https://YOUR-USERNAME.github.io/quarterly-earnings/
   ```
5. To force-refresh cached content, append a version query:
   - `?v=1`, `?v=2`, etc., e.g. `https://YOUR-USERNAME.github.io/quarterly-earnings/?v=2`

## Local Preview
Just open `index.html` in a browser. (Some browsers block local module imports; if so, serve with a tiny HTTP server: `python -m http.server 8000` and visit `http://localhost:8000/`).

## Editing
- Edit `slides.md` for Markdown-based slides.
- Add new HTML slides inside `<div class="slides">` in `index.html`.
- Speaker notes use `<aside class="notes">…</aside>` or `Note:` in Markdown slides.
