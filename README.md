# babsey.github.io

Personal website of Sebastian Spreizer, built with [Jekyll](https://jekyllrb.com/) and the
[Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme (vendored in `_layouts`,
`_includes` and `_sass`).

## Local development

```bash
bundle install
bundle exec jekyll serve --livereload
```

Then open <http://localhost:4000>.

## Content

- `index.html` – home page (hero + featured projects)
- `_pages/` – About, CV (English `/cv/`, German `/de/cv/`), Projects, 404
- `_includes/cv.html` – CV template shared by both languages; labels in `_data/cv_i18n.yml`,
  German titles in the `title_de` / `location_de` fields of `_data/work.yml` and `_data/education.yml`
- `_data/` – CV data (`work.yml`, `education.yml`, `publications.yml`, `skills.yml`)
- `_data/navigation.yml` – top navigation
- `assets/css/main.scss` – skin selection and style overrides

## Deployment

`.github/workflows/pages.yml` builds the site with Jekyll 4 and deploys it to GitHub Pages on every
push to `main`. In the repository settings, set **Pages → Build and deployment → Source** to
**GitHub Actions**.
