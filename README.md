# The Blooming Flour (Static)

This is a **static** version of the site (no PHP required).

## Run locally

### Option A: VS Code Live Server
1. Install the **Live Server** extension
2. Open the project folder
3. Right‑click `index.html` → **Open with Live Server**

### Option B: Python simple server
```bash
python -m http.server 8000
```
Then open: http://localhost:8000

## Contact form note
The contact page is static and uses a `mailto:` action. If you want a real form submission, swap it to a service like Formspree / Netlify Forms and remove the `mailto:`.

## Pages
- `index.html`
- `pages/about.html`
- `pages/portfolio.html`
- `pages/contact.html`
