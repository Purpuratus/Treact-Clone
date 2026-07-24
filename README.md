# Treact — Landing Page Clone

A static clone of the [Module 2 Final Project example website](https://module-2-fp-example-website.vercel.app) (the "Treact" SaaS landing page template), rebuilt with plain **HTML + CSS** — no build step, no framework.

## Contents

```
treact-clone/
├── index.html    # page markup
├── style.css     # all styling (responsive)
└── README.md
```

Open `index.html` in any browser to view it locally. Everything loads over the internet (fonts, illustrations), so no server is required.

---

## Put it on GitHub

### Option A — Upload through the GitHub website (no command line)

1. Go to <https://github.com/new> and create a repository, e.g. `treact-clone`. Leave it **public** and don't add a README (this folder already has one).
2. On the new repo page, click **uploading an existing file**.
3. Drag `index.html`, `style.css`, and `README.md` into the box.
4. Click **Commit changes**.

### Option B — Push with git (command line)

```bash
cd treact-clone
git init
git add .
git commit -m "Initial commit: Treact landing page clone"
git branch -M main
git remote add origin https://github.com/<your-username>/treact-clone.git
git push -u origin main
```

Replace `<your-username>` with your GitHub username.

---

## Host it live with GitHub Pages

Once the files are on GitHub:

1. In the repository, go to **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Set the branch to **main** and the folder to **/ (root)**, then **Save**.
4. Wait ~1 minute. Your site will be live at:
   `https://<your-username>.github.io/treact-clone/`

That gives you a public URL just like the Vercel original.

---

## Notes

- The illustrations, icons, and logos are loaded from the original project's public asset URLs. If you'd rather host them yourself, download each asset into an `assets/` folder and update the `src` paths in `index.html`.
- Fonts come from Google Fonts (Inter).
- Text is placeholder Lorem ipsum, matching the original template.
- Treact is an open-source template; this clone is for learning purposes.
