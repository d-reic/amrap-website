# AMRAP website

Static marketing site for the AMRAP iOS app at https://amrap-app.com.

Hosted on GitHub Pages from the root of `main`; every push deploys automatically. The custom domain is set in `CNAME`.

Styles follow the Amrap design system v3:
- `assets/tokens.css`: colour, type, spacing and radius tokens (light and dark)
- `assets/components.css`: the design system's `amrap-` components (StatCard, CategoryTile, PhaseScreen, TimerDial)
- `assets/site.css`: page layout

Preview locally:

```bash
python3 -m http.server 4173
```
