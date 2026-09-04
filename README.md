# Prashant Kasula — Portfolio

A single-page portfolio site built with plain HTML, CSS, and vanilla JS (no build step required).

## Structure

- `index.html` — page markup
- `styles.css` — all styling (dark theme, purple accent, Plus Jakarta Sans font)
- `script.js` — mobile nav toggle + active-section highlighting on scroll

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. `portfolio`).
2. Push this project to it:
   ```bash
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source → Deploy from a branch → `main` / `(root)`** → Save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`
   (or `https://<your-username>.github.io/` if the repo is named `<your-username>.github.io`).

## To update

Edit the HTML/CSS/JS, commit, and push — GitHub Pages redeploys automatically within a minute or two.
