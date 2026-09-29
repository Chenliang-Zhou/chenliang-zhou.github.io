# Chenliang Zhou — Personal Website

Site: <https://chenliang-zhou.github.io>  
Theme: Academic Pages / Minimal Mistakes (Jekyll + GitHub Pages)

## Recommended mental model

| Folder | What it is |
|--------|------------|
| **`pages/`** | **Your content** — About, Publications, Teaching, 404 |
| **`images/`** | Photos / figures used by the site |
| **`trash/`** | Recycle bin (not built / not published) |
| `_config.yml`, `_data/` | Site config & navigation |
| `_includes/`, `_layouts/`, `_sass/`, `assets/` | Theme engine (usually leave alone) |

Jekyll/GitHub Pages **requires** `_config.yml` and theme folders (`_includes`, `_layouts`, `_sass`, `_data`) at the **repo root**. They cannot all be moved into a single `config/` folder without a custom build pipeline. So the clean split is: **edit `pages/` for content; treat `_config*` / `_data` / theme as engine**.

## Content files

- `pages/about.md` → `/`
- `pages/publications.md` → `/publications/` (selected)
- `pages/publications-full.md` → `/publications/full/`
- `pages/teaching.md` → `/teaching/`
- `pages/404.md` → `/404.html`

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

## Notes

- `trash/` is excluded from the Jekyll build (see `_config.yml` `exclude`).
- Legacy `_publications/` collection was moved to `trash/_publications/`.
