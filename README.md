# lead-ing.github.io (Project Site)

This repository is set up to publish a **GitHub Pages _project_ site** at:

**https://jamesafful.github.io/lead-ing/**

## Enable GitHub Pages
1. Go to **Settings → Pages**.
2. **Source:** `Deploy from branch`
3. **Branch:** `main` (or default branch)
4. **Folder:** `docs/`
5. Click **Save**.

GitHub will build and deploy automatically. Your site will be at the URL above.

## Local preview (optional)
If you use Codespaces, this repo includes a minimal setup to run Jekyll:
- Open in Codespaces
- Run: `bundle install` then `bundle exec jekyll serve --source docs --baseurl "/lead-ing" --livereload`
- Open the forwarded port it suggests.

> The site content lives entirely in the `docs/` folder and uses the official **minima** theme.
