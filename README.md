# Dismas — Personal Site

This is a small 3-page static website (Home, Research, Skills & Hobbies) intended to be hosted with GitHub Pages.

Files:
- `index.html` — Home page
- `research.html` — Robotic WAAM research details
- `skills.html` — Skills and hobbies
- `css/style.css` — Site styles


How to publish on GitHub Pages

Option A — GitHub Actions (recommended):

1. The repository contains a workflow at `.github/workflows/pages.yml` that will automatically publish the repository root to GitHub Pages whenever you push to `main`.

2. Commit and push your changes to `main`. GitHub will run the workflow and publish the site. The `CNAME` file (if present) will be used for custom domains.

Example (this repository):

```powershell
git remote add origin https://github.com/Guru5290/My_portfolio.git
git branch -M main
git push -u origin main
```

After a few minutes the site will be available at `https://Guru5290.github.io/My_portfolio/` unless you set a custom domain.

Option B — npm + `gh-pages` (manual deploy):

1. Install dependencies:

```powershell
npm install
```

2. Deploy using the `deploy` script in `package.json`:

```powershell
npm run deploy
```

This will publish the repository root to a `gh-pages` branch. You can use either option — GitHub Actions will keep Pages updated automatically on pushes to `main`.

Contact links & avatar

- Replace `youremail@example.com`, `https://github.com/<your-username>` and LinkedIn URL in the HTML files with your real contact details.
- Replace `assets/avatar.svg` with a real photo or avatar named `avatar.svg` (or update the `src` to a PNG/JPG in `assets/`).

Custom domain (optional)

- Replace the placeholder `CNAME` file with your domain (for example `www.yourdomain.com`). GitHub Pages will use that CNAME when deploying.

If you want, I can:
- Add your real email, GitHub and LinkedIn links now and replace the placeholder avatar with an uploaded photo if you provide one.
- Or use the `gh-pages` npm flow instead of Actions — tell me which you prefer.
