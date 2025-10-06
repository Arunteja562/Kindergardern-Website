# Kindergarten Website

This repository contains a static website for a kindergarten. The site is built with plain HTML, CSS and images located in the `images/` folder. No build tools are required — the site can be served directly as static files.

Important: this change only adds this `README.md`. No other files in the project were modified.

## Files of interest

- `home.html`, `Main.html`, `Main.html` - main pages (check the root for other HTML pages like `home1.html`, `dashboard.html`, `login.html`, `register.html`).
- `Style.css`, `Main.css`, `login.css` - stylesheets.
- `images/` - image and media assets used by the site.
- `Script.js` - client-side JavaScript.

If you need to find a particular page, look for files with the `.html` extension at the project root.

## Run locally

Option A — Open an HTML file directly

1. Open the project folder in File Explorer.
2. Double-click `home.html` (or any other `.html` file) to open it in your browser.

Option B — Serve over a local HTTP server (recommended for testing JS/CSS that expects an HTTP context)

If you have Python 3 installed, run this from the project root in a terminal:

```powershell
python -m http.server 8000
```

Then open http://localhost:8000/home.html in your browser.

Alternatively, use any static server you prefer (Node `http-server`, VS Code Live Server extension, etc.).

## Deploy to GitHub Pages

This repository is a static site and can be hosted with GitHub Pages. Two simple deployment options:

Option 1 — Serve from the repository root (recommended)

1. If this project is not yet in a GitHub repository, create one and push the project:

```powershell
git init
git add .
git commit -m "Initial commit"
git remote add origin <your-git-repo-url>
git push -u origin main
```

2. On GitHub: go to your repository -> Settings -> Pages (or Settings -> Pages & GitHub Pages).
3. Under "Source", select the branch (e.g. `main`) and set the folder to `/ (root)`.
4. Save. GitHub will publish the site to `https://<your-username>.github.io/<repo-name>/` (or to your user/organization site if using the `main` branch of a repo named `<username>.github.io`).

Option 2 — Use `gh-pages` branch

1. Install and use a deploy tool (optional), or push your built/static files to a `gh-pages` branch.
2. In the repository Settings -> Pages choose the `gh-pages` branch as the source.

Notes and tips

- If you prefer the site under a custom subpath, or want a user/organization site, consult GitHub Pages docs: https://docs.github.com/en/pages
- If the site doesn't appear immediately, wait a minute and clear your browser cache.
- Ensure your homepage filename matches your chosen GitHub Pages setup; `index.html` at the repo root will be served at the root path. If you don't have `index.html`, link directly to `home.html` like `https://<user>.github.io/<repo>/home.html`.

## Credits

Project files and images included in this repository.

---

If you'd like, I can also:
- Add a small `index.html` that redirects to `home.html` so the site root opens automatically.
- Add a GitHub Actions workflow to automatically build/deploy (not necessary for pure static files).

If you want either of those, tell me which option and I will add it without modifying other project files unless requested.

## Live demo / Deployment link

If you've deployed this site to GitHub Pages, add your live URL here so others can visit it directly. Replace the placeholder below with your published site URL:

Live site URL:

`https://kindergartenwebsites.netlify.app`

If you'd like I can also add an `index.html` redirect or update other README text to point to this live URL.
