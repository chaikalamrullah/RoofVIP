# RoofVIP website

This repository hosts the public website for **RoofVIP (Roof Vector Image Pair)**, a living, versioned dataset and benchmark platform for building-roof geometry research.

Website: https://chaikalamrullah.github.io/RoofVIP/

## Site structure

- `index.md` — project landing page and news
- `dataset/` — release overview and permanent release pages
- `benchmark/` — benchmark, evaluation, and leaderboard placeholders
- `team/` — project and dataset contributor attribution
- `docs/` — stable documentation independent of individual releases
- `_data/` — structured release, news, team, and leaderboard data
- `_includes/` — reusable Jekyll components
- `_layouts/` — shared page layouts
- `assets/css/main.scss` — project-specific visual style

## Updating a release

The release overview is driven primarily by `_data/releases.yml`. Change release status, modalities, links, and summaries there; keep detailed release-specific scientific documentation in the corresponding page under `dataset/`.

## Updating news

Add entries to `_data/news.yml`.

## Updating contributors

Add or edit entries in `_data/team.yml`. Contribution and release attribution can then be reused by the Team page and future components.

## Updating the leaderboard

When the benchmark protocol is ready, populate `_data/leaderboard.yml` and document the corresponding dataset and protocol versions.

## GitHub Pages

The site uses Jekyll and the GitHub Pages-compatible `minima` theme as a base, with custom layouts and styling. Links use Jekyll's `relative_url` filter so the site works under the `/RoofVIP` project path.
