# Gabriel H. Righi — Academic Portfolio

Jekyll-based academic and professional portfolio hosted at [gabrielhr77.github.io](https://gabrielhr77.github.io).

## Pages

- **About** — introduction, featured projects, background and contact
- **Research** — FAPESP-supported work on gravitational dynamics and neural networks
- **Projects** — research, WordPress development and SemComp VII case studies
- **CV** — professional overview and a downloadable PDF

## Run locally

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve --livereload
```

Open http://localhost:4000. For Windows builds, the Gemfile includes `tzinfo-data`.

## Add or update a project

Create or edit a Markdown file in `_portfolio/` with the `permalink`, `order`, `category`, `image`, `technologies` and optional `github` / `demo` fields in its YAML front matter. Both the home page and the Projects page use `_includes/project-cards.html`.

## Deployment

The included GitHub Actions workflow targets the `master` branch. If the repository default branch is `main`, update the workflow branch setting accordingly. Configure GitHub Pages to deploy with **GitHub Actions**.

## Credits

Based on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and the Minimal Mistakes theme. Licensing and template attribution are retained in `LICENSE` and the site footer.
