# fenglang918.github.io

Source for my personal website (GitHub Pages).

- Website: `https://fenglang918.github.io/`
- Owner: Liang Feng (冯亮)

## Pages

- `index.html` (English)
- `index_cn.html` (中文)
- `photography.html` / `photography_cn.html`
- Images: `selfie.jpg`, `photograph/`

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

- This is a personal site repo; please open an issue/PR for typos or broken links.
- Please don’t reuse photos or other personal content without permission.
