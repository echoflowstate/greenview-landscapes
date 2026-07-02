# Greenview Landscapes — Website

A single self-contained `index.html` (all CSS, JS, fonts, and the logo are embedded — no build step, no dependencies). Just host the file.

**Contact wired in:** phone `+1 (774) 510-0557`, email `greenviewlawncare07@gmail.com`, Instagram.

---

## Option A — GitHub Pages (simplest, free, no local setup)

1. Go to https://github.com/new and create a repo, e.g. `greenview-landscapes` (Public).
2. On the new repo page click **uploading an existing file**, then drag in `index.html` (and `README.md`). Commit.
3. Go to **Settings → Pages**.
4. Under **Source**, choose **Deploy from a branch** → Branch: `main` → Folder: `/ (root)` → **Save**.
5. Wait ~1 minute. Your site is live at:
   `https://<your-username>.github.io/greenview-landscapes/`

## Option B — GitHub → Netlify (best for a custom domain like greenviewlandscapes.com)

1. Push this folder to a GitHub repo (Option A steps 1–2, or the Git CLI method below).
2. At https://app.netlify.com → **Add new site → Import an existing project → GitHub** → pick the repo.
3. **Build command:** leave empty. **Publish directory:** `.` (the included `netlify.toml` already sets this.)
4. **Deploy.** You'll get a `something.netlify.app` URL instantly.
5. To use your own domain: **Site configuration → Domain management → Add a domain**, then point your domain's DNS at Netlify (they walk you through it).

## Git CLI method (if you prefer the terminal)

```bash
cd greenview-site
git init
git add .
git commit -m "Greenview Landscapes site"
git branch -M main
git remote add origin https://github.com/<your-username>/greenview-landscapes.git
git push -u origin main
```

---

## Before you go live — swap the placeholders

Everything labeled as a placeholder is clearly marked in the page. Replace with real content when ready:
- Project photos and the before/after images (look for "Illustration — replace with your photo")
- Team photos of Aidan & Brice ("Add photo")
- Reviews (currently clearly-labeled placeholders — paste real Google reviews)
- Business hours and service-area towns
- Optional: confirm the New England / coastal-MA framing matches your actual area

To edit, open `index.html` in any text editor (or VS Code) and search for the label text.
