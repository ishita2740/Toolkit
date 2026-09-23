# Rhythma — Frontend & Design Toolkit

A single static page (`index.html`) documenting which tools to use at each
stage of building the Rhythma landing page. No build step, no dependencies.

## Deploy on GitHub Pages

1. Create a new repo (or use an existing one) and push these files:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Add design toolkit guide"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
2. On GitHub: **Settings → Pages → Source → Deploy from a branch**, pick
   `main` and `/ (root)`, then save.
3. Your page goes live at:
   `https://<your-username>.github.io/<repo-name>/`

## Deploy on Vercel / Netlify (alternative)

Drag and drop the folder onto vercel.com/new or app.netlify.com/drop —
no configuration needed, since it's just one static HTML file.
