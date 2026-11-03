# alliekreitman.github.io

My personal website, hosted on GitHub Pages at
[allieskreitman.com](https://allieskreitman.com) (also reachable at
alliekreitman.github.io).

## Pages

Each page is a Markdown file in the repo root. The `permalink` in its front
matter is its URL, and it must match the entry in `navbar-links` in
`_config.yml`.

| File | URL |
| --- | --- |
| `index.md` | `/` |
| `Publications.md` | `/Publications/` |
| `Research.md` | `/Research/` |

To edit the site, edit those files — everything else is theme machinery.

## Everything else

- `_config.yml` — site title, navbar links, social links, colours.
- `_layouts/`, `_includes/` — page templates.
- `assets/` — images, PDFs, CSS, JS.
- `404.html` — the not-found page.

## Running it locally

```sh
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

---

Built with [Beautiful Jekyll](https://beautifuljekyll.com) by
[Dean Attali](https://deanattali.com).
