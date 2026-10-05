# sadharan-site

The public website for the Sadharan app family, served by GitHub Pages. Plain HTML and one stylesheet; no build step.

| Page | Source of truth |
|---|---|
| `index.html` | here |
| `launcher/privacy/index.html` | `docs/privacy-policy.md` in the (private) launcher repo. Change the policy there first, then copy the change here and update the effective date in both. |

A new app gets its own folder (`<app>/privacy/index.html`) and a line on the home page.

`.nojekyll` tells GitHub Pages to serve the files as they are.
