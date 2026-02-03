# surprise-gf-site

This is a tiny, single-file romantic page you can host with GitHub Pages or preview using raw.githack/htmlpreview. The page includes the requested phrase: **gudo applogie**.

Files:

- `index.html` — the single-page site (small confetti effect, signature, and the phrase "gudo applogie").

How to publish (quick):

1. Create a new public repository on GitHub named `surprise-gf-site` (or any name you prefer).
2. From this project folder, push to GitHub:

```bash
cd surprise-gf-site
git init
git add index.html README.md
git commit -m "Initial romantic page"
git remote add origin https://github.com/<your-username>/surprise-gf-site.git
git branch -M main
git push -u origin main
```

3. (Recommended) Enable GitHub Pages:

- Go to the repo on GitHub → Settings → Pages
- Under "Build and deployment" choose "Deploy from a branch"
- Select branch `main` and folder `/ (root)`, Save
- The published URL will be `https://<your-username>.github.io/surprise-gf-site/` (it may take ~1 minute to appear)

4. Quick preview without enabling Pages (instant):

- HTMLPreview:
  `https://htmlpreview.github.io/?https://github.com/<your-username>/surprise-gf-site/blob/main/index.html`
- Raw.githack:
  `https://raw.githack.com/<your-username>/surprise-gf-site/main/index.html`

Privacy note: A public repo means anyone can view the page and source. If you want the page private, consider sharing a password-protected service or using a private deployment on Netlify/Vercel with access control.

— includes: gudo applogie
