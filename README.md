# RST Payout Calculator

Contributor-accessible web calculator for weekly payout calculations, saved scenarios, and side-by-side what-if comparisons.

## Features

- Weekly payout calculation
- Adjustable USD to PHP exchange rate
- Automatic hit-rate and pay-tier calculation
- Save, load, rename, duplicate, and delete scenarios
- Compare multiple scenarios side-by-side
- Export/import scenarios as JSON
- Responsive desktop/mobile UI
- No login required

## Scenario storage

Saved scenarios use browser local storage, so each contributor has their own scenarios on their device/browser. Export and Import allow scenarios to be moved between browsers or devices.

## Publish as a contributor web

This is a static site and can be published with GitHub Pages:

1. Open repository Settings.
2. Open Pages.
3. Under Build and deployment, choose Deploy from a branch.
4. Select branch main and folder / (root).
5. Save.

GitHub will provide the public Pages URL after deployment.

## Shared contributor scenarios

The current version keeps scenarios private to each browser. If contributors need shared scenarios across devices, the next version should add authentication and a hosted database.
