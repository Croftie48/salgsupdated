# Seaford Allotment Society — Jekyll / GitHub Pages

This repository is configured to run exclusively from GitHub Pages at:

`https://croftie48.github.io/salgsupdated/`

## Publish

Upload the contents of this repository to the `salgsupdated` GitHub repository. In **Settings → Pages**, configure the site to deploy with GitHub Pages (GitHub Actions or the main branch, depending on the repository settings). No custom domain is required.

All internal pages, stylesheets, images and documents use Jekyll `relative_url` paths so they work correctly under the `/salgsupdated/` project path.

## Required media files

The following original media files were referenced by the source site but were not present in the supplied backup. Add them to these folders before publishing if you have them:

### `assets/img/`
- `jorg-hofmeier-wfqsRJZjXP0-unsplash.jpg`
- `Carrot.JPG`
- `wilderness1.jpeg`
- `wilderness2.jpg`
- `wilderness3.jpg`
- `loo1.jpeg`
- `loo2.jpeg`

### `assets/pdf/`
- `General Information for Plot Holders Nov 23.PDF`
- `Seaford Allotment Rules 2024.PDF`

The directories are included in this package so the required repository structure is ready.

## Local

```bash
bundle install
bundle exec jekyll serve
```
