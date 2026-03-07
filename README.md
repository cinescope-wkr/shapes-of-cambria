# Shapes of Artificial Cambrian Explosion

Official submission page for **CVPR Art Gallery 2026**, plus the accompanying model/code in the same repository.

## Repository layout

- Website (GitHub Pages)
  - `index.html` (single-page project site)
  - `css/` (styling)
  - `assets/` (paper + images)
  - `favicon.svg`, `favicon.png`
- Code (model + reproduction)
  - `model/` (put training/inference code here)
  - `scripts/` (helper scripts)
  - `configs/` (YAML/JSON configs)

## Website: edit + preview

- Replace assets:
  - Paper PDF: `assets/paper.pdf`
  - Teaser: `assets/img/teaser.*`
  - Figures/photos: `assets/img/fig-01.*`, `assets/img/fig-02.*`
- Update links/IDs in `index.html` (GitHub URL and YouTube video ID).

Local preview:

- `python3 -m http.server 8000`
- Open `http://localhost:8000/`

## Publish on GitHub Pages

In GitHub (repo: `cinescope-wkr/shapes-of-cambria`):

- `Settings → Pages`
- Source: “Deploy from a branch”
- Branch: `main`
- Folder: `/(root)`

## Code: notes

- Large binaries (checkpoints, datasets, renders) should go in Releases or external storage; don’t commit them to git.
