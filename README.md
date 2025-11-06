# Lead-ing — World‑class Project Site

This repo publishes a **GitHub Pages _project_ site** at:
**https://jamesafful.github.io/lead-ing/**

## Enable GitHub Pages
1. Repo → **Settings → Pages**
2. **Source:** Deploy from branch
3. **Branch:** `main`
4. **Folder:** `/docs`
5. Save

## Local preview (Codespaces or local Ruby)
```bash
bundle install
bundle exec jekyll serve --source docs --baseurl "/lead-ing" --host 0.0.0.0 --livereload
```

## Structure
- `docs/_layouts/` — custom layouts (`home.html`, `article.html`)
- `docs/_includes/` — SEO head, newsletter CTA
- `docs/collections/` — `/_essays`, `/_playbooks`, `/_toolkit`, `/_scenarios`
- `docs/assets/` — css, img (logo, social card, favicon)
