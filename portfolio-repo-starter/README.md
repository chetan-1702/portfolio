# Chetan Bissessur — Portfolio

Personal portfolio site and dissertation archive.

- **`index.html`** — the portfolio itself (cybersecurity background, experience, skills, education). Hosted via GitHub Pages once enabled on this repo.
- **`dissertations/`** — MSc and BSc dissertation reports. See [`dissertations/README.md`](./dissertations/README.md) for details on each.

## Hosting this with GitHub Pages

1. Push this repo to GitHub (see commands below).
2. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `root`**.
3. The site will be live at `https://chetan-1702.github.io/portfolio/` within a minute or two.

## Pushing this repo for the first time

```bash
cd portfolio-repo-starter
git init
git add .
git commit -m "Initial commit: portfolio site + dissertation archive"
git branch -M main
git remote add origin https://github.com/chetan-1702/portfolio.git
git push -u origin main
```

(Create the empty `portfolio` repo on GitHub first — no README/license/gitignore selected — then run the commands above from inside this folder.)
