# Lucas Lima's website

A small Jekyll site with pages for the homepage, research, teaching, and CV. The paper PDFs are in `papers/`.

## Run locally

With Ruby and Bundler installed, run:

```sh
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000/>. Stop the server with Ctrl+C.

## Edit the site

- `index.md`, `research.md`, `teaching.md`, and `cv.md` contain the page content.
- `_config.yml` contains the site title, profile, URL, and permalink settings.
- `_layouts/page.html` contains the shared HTML and navigation.
- `assets/css/main.css` contains the styles.

Jekyll builds the site into `_site/`. The existing page paths (`/`, `/research/`, `/teaching/`, and `/cv/`) come from the page files and the permalink setting.
