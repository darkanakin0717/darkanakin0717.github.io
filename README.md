# Laser Vision — Static Site

A single-file static website. No build step needed.

## Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. `laser-vision`).
2. Upload all files from this folder (`index.html` and the `images/` folder) to the repo root.
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, choose `main` / `(root)`.
4. Save. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute.

## Local preview

Just open `index.html` in your browser — or run any static server:

```
python3 -m http.server
```

## Custom domain

In GitHub Pages settings, add your custom domain and create a CNAME DNS record pointing to `<your-username>.github.io`.
