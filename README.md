# Pharaoh Road

Marketing site for the home at 5113 Farrow Road, Columbia, SC.

Whole-home and private-room furnished rentals — designed for travel nurses,
healthcare professionals, faculty, and people staying in Columbia for 30+ days.

## Stack
- Single-page static HTML (no build step)
- Hosted on Netlify
- Form submissions handled by Netlify Forms (see the `inquiry` form in `index.html`)

## Local preview
Just open `index.html` in a browser, or run any static server:
```bash
python3 -m http.server 8000
```

## Photos
Drop room photos into `photos/` with the filenames referenced in `index.html`
(e.g. `master-wide.jpg`, `loft1.jpg`, etc.). Missing photos automatically fall
back to a styled placeholder, so the site never breaks.

## Deploy
Any push to `main` triggers a Netlify production deploy.
