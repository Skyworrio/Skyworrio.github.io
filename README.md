# Skyworrio.github.io

Personal engineering portfolio, built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

## Local preview

```bash
pip install -r requirements.txt
mkdocs serve
```

Then open http://127.0.0.1:8000. Pages named `*_draft.md` show locally but are excluded from the deployed site.

## Deploy

Push to `main`. The GitHub Action builds the site and publishes it to the `gh-pages` branch.
In the repo settings, Pages → Source must be set to **Deploy from a branch → `gh-pages` / (root)**.
