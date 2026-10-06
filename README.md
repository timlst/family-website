# family-website

Minimal Hugo website intended for use as a family blog and deployment on GitHub Pages.

## Local development

```bash
hugo server -D
```

## Build

```bash
hugo --minify
```

## GitHub Pages

This repository includes a GitHub Actions workflow at:

- `/home/runner/work/family-website/family-website/.github/workflows/hugo-gh-pages.yml`

It builds the Hugo site and deploys the generated `public/` output to GitHub Pages.
