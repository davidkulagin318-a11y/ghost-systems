# Ghost Systems website

Plain static site. No build step. Open `index.html` to preview.

- `index.html` is the home page (hero, lineup, approach, company, contact)
- `privacy.html` is the site privacy page
- `styles.css` holds all styling; colours are the variables at the top
- `assets/` holds the logo, favicon and fonts (Archivo and Martian Mono, both under the SIL Open Font License)

## Put it online (GitHub Pages, free)

1. On github.com, create a new **public** repo named `ghost-systems` (no README).
2. In Terminal:

```
cd ~/ghost-systems-site
git init -b main
git add .
git commit -m "Ghost Systems site"
git remote add origin https://github.com/davidkulagin318-a11y/ghost-systems.git
git push -u origin main
```

3. In the repo: Settings → Pages → Source "Deploy from a branch" → `main` / `/ (root)` → Save.

The site appears at https://davidkulagin318-a11y.github.io/ghost-systems/ after a minute or two.

## Google Search Console

Add the URL above as a "URL prefix" property, choose the "HTML tag" method, and paste the tag into `index.html` under the `Google Search Console` comment near the top. Commit, push, then click Verify.
