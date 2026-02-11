# Personal Homepage (GitHub Pages)

This repository contains the static homepage for **Yihang Qiu**.

## Local preview

Open `index.html` directly in browser, or run a local static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages

For a personal homepage with URL `https://yihangqiu.github.io/`, use a repository named:

- `yihangqiu.github.io`

Steps:

1. Create a new public repo: `yihangqiu.github.io`
2. Copy these files into that repo root (`index.html`, `styles.css`, and optional assets).
3. Commit and push to branch `main`.
4. In GitHub repo settings:
   - `Settings` -> `Pages`
   - `Build and deployment` -> `Source: Deploy from a branch`
   - Branch: `main` and folder `/ (root)`
5. Wait 1-3 minutes for deployment.

## Notes

- Replace the avatar URL in `index.html` with your own image path.
- If you use a custom domain, configure `CNAME` in GitHub Pages settings.
