# chandureddy-sec.github.io

Portfolio of E Chandu Reddy, SOC analyst and VAPT practitioner in Hyderabad.

Live site: https://chandureddy-sec.github.io

## What is on the page

- A short walkthrough of how I triage an endpoint alert, written as a practice scenario (the host, user and domain are invented).
- Lab and project write-ups: Active Directory attack lab, web application pentest lab, Android pentest lab, recon framework, network intrusion detection prototypes.
- Experience, skills, credentials and contact details.

## How it is built

One static HTML file with inline CSS and about 80 lines of JavaScript. There is no build step, no framework, no analytics and no third-party requests.

| Path | Purpose |
|---|---|
| `index.html` | The whole site |
| `fonts/` | Self-hosted Archivo, Source Serif 4 and IBM Plex Mono (SIL Open Font License, see `fonts/README.md`) |
| `favicon.svg`, `og.png` | Tab icon and social-preview image |
| `resume.pdf` | Downloadable résumé |

Features: light and dark themes (follows the system, with a toggle that remembers the choice), keyboard-operable walkthrough, visible focus states, reduced-motion support, responsive down to 360 px.

## Run it locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

GitHub Pages serves the `main` branch root. Push to `main` and the site updates.
