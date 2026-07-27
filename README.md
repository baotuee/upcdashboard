# UPC Livestream Dashboard

Standalone HTML dashboard for UPC livestream performance.

## Data Source

The dashboard loads live data from this Google Sheet on refresh:

- `raw_centralized`
- `raw_smg`
- `Data_plan`

If Google Sheet loading fails, the dashboard falls back to the embedded data inside `index.html`.

## GitHub Pages

Upload this folder to GitHub, then enable GitHub Pages for the repository.

Because the main file is named `index.html`, GitHub Pages can serve it directly from the repository root.

