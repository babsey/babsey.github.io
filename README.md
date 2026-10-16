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

- `index.html` – home page (hero + featured projects + recent posts)
- `_pages/` – About, Projects, Posts, Tags, Categories, 404
- `_posts/` – blog posts, named `YYYY-MM-DD-title.md`
- `_data/navigation.yml` – top navigation
- `assets/css/main.scss` – skin selection and style overrides

## Deployment

`.github/workflows/pages.yml` builds the site with Jekyll 4 and deploys it to GitHub Pages on every
push to `master`. In the repository settings, set **Pages → Build and deployment → Source** to
**GitHub Actions**.
