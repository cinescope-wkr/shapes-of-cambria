# Shapes of Artificial Cambrian Explosion

Official submission page for **CVPR Art Gallery 2026**, plus the accompanying model/code in the same repository.

## Repository layout

- Website (GitHub Pages)
  - `docs/index.html` (single-page project site)
  - `docs/css/` (styling)
  - `docs/assets/` (paper + images)
  - `docs/favicon.svg`, `docs/favicon.png`
- Code (model + reproduction)
  - `model/` (put training/inference code here)
  - `scripts/` (helper scripts)
  - `configs/` (YAML/JSON configs)

## Website: edit + preview

- Replace assets:
  - Paper PDF: `docs/assets/paper.pdf`
  - Teaser: `docs/assets/img/teaser.*`
  - Figures/photos: `docs/assets/img/fig-01.*`, `docs/assets/img/fig-02.*`
- Update links/IDs in `docs/index.html` (GitHub URL and YouTube video ID).

Local preview:

- `cd docs && python3 -m http.server 8000`
- Open `http://localhost:8000/`

## Publish on GitHub Pages

In GitHub (repo: `cinescope-wkr/shapes-of-cambria`):

- `Settings → Pages`
- Source: “Deploy from a branch”
- Branch: `main`
- Folder: `/docs`

## Code: notes

- Large binaries (checkpoints, datasets, renders) should go in Releases or external storage; don’t commit them to git.
