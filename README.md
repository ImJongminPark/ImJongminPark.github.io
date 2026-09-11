# jongmin-park homepage

Single-file static site. No build step.

## Publish on GitHub Pages

1. Create a repo named `ImJongminPark.github.io` (must match your GitHub username exactly).
2. Copy everything in this folder into the repo root and push.
3. Repo → Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Site appears at https://imjongminpark.github.io within a minute or two.

## Files to add before publishing

| Path | What |
|---|---|
| `images/profile.jpg` | Portrait, square, ≥ 400×400 |
| `assets/Jongmin_Park_CV.pdf` | Your CV PDF |
| `images/webspline.png`, `ecosplat.png`, `mobgs.png`, `splinegs.png`, `moblurf.png`, `compass.png` | Paper teaser images, 4:3, ≥ 600×450. Any missing one falls back to a text placeholder automatically. |

## Editing

Everything is in `index.html`. Each publication is one `<article class="pub" data-type="...">` block;
copy one and change the fields. `data-type` is `conference`, `journal`, or `preprint` and drives the filter buttons.

Colors and fonts are CSS variables at the top of the `<style>` block.

## Also update

- Point the LinkedIn / Google Scholar homepage fields to the new URL.
- Add the new URL to the CV header and retire the Google Sites page (or add a redirect notice there).
