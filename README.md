# Book Companions

A small static hub page linking to my book-summary study companions. Pure HTML/CSS
(plus a few lines of JS for the light/dark toggle) — no build step, no framework.

## The companions

- [Designing Data-Intensive Applications](https://arunav-bhattacharya.github.io/ddia-companion/) — Martin Kleppmann & Chris Riccomini
- [AI Engineering](https://arunav-bhattacharya.github.io/ai-engineering-notes/) — Chip Huyen
- [Build a Large Language Model (From Scratch)](https://arunav-bhattacharya.github.io/build-llm-from-scratch/index.html) — Sebastian Raschka
- [Designing Machine Learning Systems](https://arunav-bhattacharya.github.io/building-ml-systems/index.html) — Chip Huyen

## Files

```
index.html    # the hub page
styles.css    # design tokens + components (house style)
favicon.svg   # stacked-books tile on the pink gradient
fonts/        # self-hosted Google Sans Flex (OFL-1.1)
```

## Run locally

Open `index.html` directly, or serve the folder:

```sh
python3 -m http.server
```

## Deploy

Designed for GitHub Pages. To serve it at the root domain
`https://arunav-bhattacharya.github.io/`, create a repo named
**`arunav-bhattacharya.github.io`**, push these files, and enable Pages
(source: branch `main`). All asset paths are relative, so it also works from a
project subpath or directly off the filesystem.
