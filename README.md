# VISION-LINK AI HUB (J-FEWS)

## Overview
VISION-LINK AI HUB houses the static landing page for the J-FEWS Flood Early-Warning System. It provides the initial web user interface for the system presentation.

## CI/CD Workflow & Automated Guardrails
This repository uses GitHub Actions (`.github/workflows/ci.yml`) to perform basic baseline integrity checks on every push and pull request:
- **Baseline File Check:** Verifies that `BASELINE.md` exists in the repository.
- **Dependency Check:** Verifies that `index.html` includes the Tailwind CSS CDN reference (`cdn.tailwindcss.com`).

## How to Contribute Safely
1. Create a feature branch off `main`.
2. Make your updates and commit changes.
3. Open a Pull Request against `main`.
4. Ensure all automated CI workflow checks pass before requesting review and merging.
5. 
