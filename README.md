# Aya Ali — Portfolio

Personal portfolio website (single static page, no build step).

## Publish on GitHub Pages

1. On GitHub, create a **public** repository named exactly `AyaAli72.github.io`.
2. Upload `index.html` and this `README.md` to the repository root (or use git):
   ```bash
   git init
   git add .
   git commit -m "Add portfolio"
   git branch -M main
   git remote add origin https://github.com/AyaAli72/AyaAli72.github.io.git
   git push -u origin main
   ```
3. Go to **Settings → Pages**, set **Source: Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. After a minute your site is live at **https://AyaAli72.github.io**.

## Customize

Everything is in `index.html`. Add links to your project repos by editing the cards under the `#projects` section.
