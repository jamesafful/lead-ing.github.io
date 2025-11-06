# Lead‑ing — Youth Leadership Playbooks

This is a GitHub Pages site (Jekyll + minima) focused on **practical leadership for young people**.

## Structure
- Site code lives in `docs/`.
- Collections:
  - `collections/_playbooks` — step‑by‑step guides
  - `collections/_scenarios` — tricky peer situations with scripts
  - `collections/_toolkit` — templates & checklists
  - `collections/_essays` — big ideas, no jargon

## Local dev
```bash
bundle install
bundle exec jekyll serve --source docs --livereload
```

## Deploy
Enable **Pages** → build from GitHub Actions or `main / docs`.

## Options
- Set `site.plausible_domain` in `_config.yml` to enable Plausible.
- Add a custom domain under Settings → Pages.

## License
Content © You. Feel free to keep the structure and replace the words.
