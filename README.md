# personal-web

Personal portfolio site for **Barbara Demczyszak** — QA Software Engineer.

Static site, no build step. Pure HTML / CSS / vanilla JS.

## Local preview

Just open `index.html` in a browser, or serve the folder:

```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

Then visit http://localhost:8000

## Deploy to GitHub Pages

1. Push this folder to a GitHub repo (e.g. `basia-dem/basia-dem.github.io` for a user site, or any repo for a project site).
2. In the repo, go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch** → branch `main`, folder `/ (root)`.
4. Save. Your site will be live at:
   - User site: `https://basia-dem.github.io/`
   - Project site: `https://basia-dem.github.io/<repo-name>/`

The `.nojekyll` file disables Jekyll processing so files/folders starting with `_` are served as-is.

## Files

- `index.html` — markup
- `styles.css` — styling (dark IT/terminal theme)
- `script.js` — typed role, matrix background, scroll reveal, stat counters
- `.nojekyll` — GitHub Pages config
