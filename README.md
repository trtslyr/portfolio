# Student Portfolio (Quarto + GitHub Pages)

This repo is a **template** for the STRAT 490R portfolio. Students edit Markdown files only.

## How to publish (instructor: do once)
1. Ensure this repo contains:
   - `_quarto.yml`
   - `.github/workflows/quarto-publish.yml`
2. In GitHub: **Settings → Pages → Build and deployment → Source = GitHub Actions**.

## Student workflow
1. Open a page (e.g., `assignments/assignment-1.md`). Click the ✏️ pencil.
2. Edit Markdown. Use links, images, or iframes (YouTube).
3. Scroll down → **Commit changes**. Wait ~1 minute.
4. Refresh your site: `https://<username>.github.io/<repo>/`

## Images
Put screenshots in `assets/images/` then reference as:
```
![Caption](assets/images/my-screenshot.png)
```

No local installs required. Quarto runs in GitHub Actions.
