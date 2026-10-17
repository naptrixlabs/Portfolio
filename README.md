# Prakash Eppala — Portfolio

Personal portfolio site for **Prakash Eppala**, iOS Technical Lead & Mobile Architect (11+ years, Hyderabad, India).

Hand-built static site — no framework, no template, no build step. One `index.html` with inline CSS and vanilla JS.

## Design

- **Direction:** a clinical instrument panel, drawn from the BLE / continuous-glucose-monitoring work the site describes — hairline rules, mono readout labels, and a live telemetry trace rendered on canvas behind the hero.
- **Type:** Archivo (expanded display) with IBM Plex Sans for body and IBM Plex Mono for data labels.
- **Themes:** dark by default, light under `prefers-color-scheme: light`, all colors driven by tokens on `:root`.
- **Motion:** staggered hero reveal, scroll-reveal sections, count-up metrics, animated signal trace. Everything respects `prefers-reduced-motion`.
- **Accessibility:** semantic landmarks, visible focus rings, keyboard-reachable controls, content fully readable with JavaScript disabled.

## Structure

```
index.html                        the entire site
assets/prakash-eppala.jpg         portrait
assets/Prakash-Eppala-Resume.pdf  résumé
.github/workflows/pages.yml       deploys to GitHub Pages on push to main
```

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Pushing to `main` publishes to GitHub Pages via the included workflow.
Enable it once under **Settings → Pages → Build and deployment → Source: GitHub Actions**.

## Contact

- Email: prakash.eppala@gmail.com
- LinkedIn: https://www.linkedin.com/in/prakash-eppala
- GitHub: https://github.com/prakash-eppala
