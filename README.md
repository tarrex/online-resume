# Cesar Pereira Resume

This repository now publishes a plain static site for GitHub Pages. It does not require Jekyll, Ruby, or a build step on GitHub Pages.

## Structure

- `index.html`: Portuguese resume
- `en.html`: English resume
- `pv.html`: detailed professional version
- `assets/css/main.css`: committed static stylesheet
- `.github/workflows/static-pages.yml`: deploys the site to GitHub Pages
- `.nojekyll`: disables Jekyll processing on GitHub Pages

## Deployment

Push to `master` and the GitHub Actions workflow will publish the static files to GitHub Pages.

## Editing

Update the HTML pages directly when you want to change content.
