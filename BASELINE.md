# VISION-LINK AI HUB - Baseline Architecture

## Overview
VISION-LINK AI Hub (J-FEWS) is hosted directly on GitHub Pages from the `main` branch as a static landing page.

## Hosting & Deployment
- **Hosting Platform:** GitHub Pages.
- **Publishing Source:** Deployed directly from the repository's `main` branch.
- **Behavior:** Any change merged into `main` immediately goes live to visitors without a separate staging or gate deployment pipeline.

## Risk Assessment & Breaking Changes
Since GitHub Pages serves updates instantly upon merge:
- Unverified HTML changes, broken Tailwind CSS CDN links, or invalid syntax can directly impact live visitors.
- Automated checks on pushes/PRs serve as a lightweight warning layer, though final caution must be exercised before merging into `main`.
- 
