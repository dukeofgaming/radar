# David Vega's Tech Radar

Personal technology radar. Blips are Markdown files under `radar/<edition>/`, in the [AOE Technology Radar](https://github.com/AOEpeople/aoe_technology_radar) format (rings: adopt, trial, assess, hold). A later file with the same name revises that blip.

GitHub Pages publishes the site from `.github/workflows/tech-radar.yml` at [dukeofgaming.github.io/radar](https://dukeofgaming.github.io/radar/).

```bash
npm ci
PUBLIC_URL=/radar REACT_APP_RADAR_NAME="David Vega's Tech Radar" npm run build:static
```
