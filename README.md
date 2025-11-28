# Archaeological Sample Metadata Profile

This repository contains the source files for the **Archaeological Sample Metadata Profile** documentation site, built using [MkDocs](https://www.mkdocs.org/) and the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.

## 📁 Repository structure

- `docs/` — Markdown content, images, custom stylesheets, and scripts.
- `overrides/` — Custom HTML overrides and partial templates for the site theme.
- `mkdocs.yml` — MkDocs configuration file.
- `.gitignore` — Excludes build artifacts (e.g., the `site/` folder).

## 🚀 Building the site locally

Access to build or serve the documentation locally may be limited.  
If you have permission and the required environment to build the documentation:

1. Install MkDocs and dependencies:
   ```bash
   pip install mkdocs-material
2. Serve locally:
   ```bash
   mkdocs serve
3. The site will be available at http://127.0.0.1:8000/.

🔄 Manual site updates

1. The live site is published manually from this repository. To update it:
   Build the site locally using `mkdocs build`.
   This generates the `site/ folder` containing the HTML and assets.
2. Switch to the `gh-pages` branch:
   ```git checkout gh-pages
3. Copy the contents of `site/` into the root of `gh-pages` (replacing existing files).
4. Commit and push the changes to the `gh-pages` branch:
   ```git add --all
   ```git commit -m "Update site"
   ```git push origin gh-pages
5. The changes will be live immediately at the published URL.

⚠️ Note: The `gh-pages` branch is public so the site can be viewed, but other branches may remain private.

## 🌐 Public site

This repository contains source materials only.  
The published version of this documentation is available at:  
👉 [https://igsn.github.io/archcop-metadata-profile/]

*This repository is maintained by the IGSN–DataCite Archaeology and Cultural Heritage Community of Practice.*
