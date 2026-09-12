# VISION-LINK AI HUB (J-FEWS)

## Overview
VISION-LINK AI HUB houses the frontend dashboard for the J-FEWS Flood Early-Warning System and Edge-AI solutions. It serves real-time telemetry data, early warnings, and critical safety parameters.

## CI/CD Workflow & Automated Guardrails
This repository uses GitHub Actions (`.github/workflows/ci.yml`) to ensure zero-downtime deployments and prevent broken releases:
- **Automated Guardrails:** Every push or Pull Request runs content assertion checks verifying essential UI components, site name, section IDs (`#solutions`, `#contact`), and script dependencies (Tailwind Play CDN).
- **Failure Prevention:** Failed check runs block broken code from reaching live visitors on GitHub Pages.

## How to Contribute Safely
1. Create a feature branch off `main`.
2. Make your updates and commit changes.
3. Open a Pull Request against `main`.
4. Ensure all automated CI workflow checks pass before requesting review and merging.
5. <!-- update -->).
