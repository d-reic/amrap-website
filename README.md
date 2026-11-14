# AMRAP website

Static marketing site for the AMRAP iOS app at https://amrap-app.com.

Hosted on Firebase Hosting (project `amrap-bd332`). Every push to `main` deploys automatically via `.github/workflows/firebase-hosting-merge.yml`; pull requests get a preview channel. amrap.danielreichenpfader.com redirects to amrap-app.com (set up in the Firebase console).

Styles follow the Amrap design system v3:
- `assets/tokens.css`: colour, type, spacing and radius tokens (light and dark)
- `assets/components.css`: the design system's `amrap-` components (StatCard, CategoryTile, PhaseScreen, TimerDial)
- `assets/site.css`: page layout

Preview locally:

```bash
python3 -m http.server 4173
```
