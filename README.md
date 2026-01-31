# fenglang918.github.io

[![Website](https://img.shields.io/badge/website-fenglang918.github.io-blue)](https://fenglang918.github.io/)
[![Last commit](https://img.shields.io/github/last-commit/fenglang918/fenglang918.github.io)](https://github.com/fenglang918/fenglang918.github.io)

Source for my personal website (GitHub Pages).

- Website: [https://fenglang918.github.io/](https://fenglang918.github.io/)
- Owner: Liang Feng (冯亮)
- Quick links: [English](https://fenglang918.github.io/index.html) · [中文](https://fenglang918.github.io/index_cn.html) · [Photography](https://fenglang918.github.io/photography.html)

## Pages

- Home: [`index.html`](./index.html) (English), [`index_cn.html`](./index_cn.html) (中文)
- Photography: [`photography.html`](./photography.html), [`photography_cn.html`](./photography_cn.html)
- Images: [`selfie.jpg`](./selfie.jpg), [`photograph/`](./photograph/)

## Local Preview

No build step — it’s plain static HTML/CSS. You can preview it locally:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

## Deploy

GitHub Pages deploys from the `main` branch. Push to update:

```bash
git add .
git commit -m "docs: update site"
git push origin main
```

It usually becomes visible within a few minutes (sometimes longer due to caching).

## Notes

- This is a personal site repo; issues/PRs for typos or broken links are welcome.
- Please don’t reuse photos or other personal content without permission.
