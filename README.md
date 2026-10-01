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

## Adding a project

1. Copy one of the `docs/projects/*_draft.md` templates into `docs/projects/<name>/index.md` (with `img/` and `files/` folders next to it) and add it to `nav` in `mkdocs.yml`.
2. Make a 16:10 thumbnail (about 960×600 JPG) at `docs/assets/thumbs/<name>.jpg`.
3. Copy an existing `<a class="project-card">` block in `docs/projects/index.md` (and on `docs/index.md` to feature it on the home page), then update the link, image, text, and tags.

Card, chip, and layout styles live in `docs/stylesheets/extra.css`.
