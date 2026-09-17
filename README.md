# neharpoddar.github.io

Personal site for Nehar Poddar — PhD researcher in humanoid robotics at IHMC / University of West Florida.

A single-page Jekyll site, hosted on GitHub Pages.

## Structure

- `_pages/about.md` — the one page (home), covers bio, publications, experience, education, skills.
- `_pages/404.md` — not-found page.
- `_layouts/page.html` — the only layout.
- `assets/css/style.css` — the only stylesheet.
- `images/`, `files/` — photos and downloadable files (CV, videos).

## Local development

```
docker run --rm -it -p 4000:4000 -v "$PWD":/srv/jekyll -w /srv/jekyll jekyll/jekyll:4 \
  sh -c "jekyll serve --host 0.0.0.0"
```

Then open `http://localhost:4000`.
