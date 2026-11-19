# Built site for GitHub Pages

Expected URL: https://cwenqi0608-spec.github.io/phd-funding/

This folder is the static export only. It is not the application source. The private Origin project remains the source of truth.

To publish an update, rebuild there with `npm test` and `npm run build`, then replace this repository’s files with the new `out/` folder. Do not commit the Origin source here.

The site path is `/phd-funding/`. `index.html` belongs at the repository root. `.nojekyll` must stay, or GitHub Pages will hide `_next`.
