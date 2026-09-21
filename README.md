# Cortex Live Workout Prototype

Mobile-first UX prototype for Cortex Scout's live workout logger.

## Prototype scope
- Static web app; no backend, auth, database, external APIs or production Cortex integration.
- Full **FULL-BODY-TITAN HYBRID v5.6** three-pass demo program.
- Cortex near-black / orange / zinc visual system.
- Live set logging, exercise navigation, workout timer, rest timer, notes and local summary.
- Draft workout state persists in the browser with `localStorage`, so a refresh should resume the session.
- Historical values are shown only where known demo/reference data exists; unknown history is explicitly shown as unknown.

The repository is deliberately separate from the production Cortex Scout Android repository. Do not place secrets or private production data here.

GitHub Pages deployment is handled by `.github/workflows/pages.yml`.
