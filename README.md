# Dismas — Personal Site

This is a small 3-page static website (Home, Research, Skills & Hobbies) intended to be hosted with GitHub Pages.

Files:
- `index.html` — Home page
- `research.html` — Robotic WAAM research details
- `skills.html` — Skills and hobbies
- `css/style.css` — Site styles

How to publish on GitHub Pages

1. Initialize a git repo (if you haven't):

```powershell
git init ; git add . ; git commit -m "Initial site scaffold"
```

2. Create a GitHub repository (use GitHub website). Add it as `origin` and push:

```powershell
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```

3. On GitHub, go to **Settings → Pages** and set the source to the `main` branch and `/ (root)` folder, then save.

After a few minutes your site will be available at `https://<your-username>.github.io/<repo-name>/`.

Alternative (deploy to `gh-pages` branch) — if you prefer automated deploys using `gh-pages` npm package, I can add a simple `package.json` and deploy script.

If you'd like, I can also:
- Add your contact email and links
- Add images or a real avatar
- Add a `CNAME` for a custom domain
