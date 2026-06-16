# BM Revision · June 2026

**🔗 Live site: https://bm-j26.vercel.app/**

A single-file, offline-capable IB Business Management revision site (Units 1 to 5,
tools and frameworks, a Data Booklet formula sheet, and a definitions sheet).

## What it is
- Pure static site. The whole thing is `index.html`.
- No build step, no dependencies to install. GSAP and Google Fonts load from a CDN.

## Deploy to Vercel
1. Create an empty GitHub repo (do not add a README from GitHub).
2. From this folder:
   ```
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git branch -M main
   git push -u origin main
   ```
3. On vercel.com choose New Project, import the repo, leave Framework Preset as
   "Other", and click Deploy. Vercel serves `index.html` at the root.

## Local preview
Just open `index.html` in any browser, or run:
```
python3 -m http.server 8000
```
then visit http://localhost:8000
