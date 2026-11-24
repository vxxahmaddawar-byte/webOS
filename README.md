# webOS

Browser desktop environment.

**Repo:** https://github.com/vxxahmaddawar-byte/webOS

## How games work

Games are **not** stored in this repo as 584 separate repos.

- **Catalog** (`games.json` in this repo) lists games
- Each game **HTML file** loads from one shared public GitHub repo:
  - https://github.com/BombedByXander/lib-backup
  - via `raw.githubusercontent.com/...`

So: **your repo** = webOS UI + catalog. **lib-backup** = game files.

## Run

1. Download the latest `webOS.html` from chat / artifacts (full app, ~1MB, all 584 games in catalog)
2. Or open this repo and use GitHub Pages once `index.html` is the full app

## Full app file

Use the `webOS.html` file from the project (not embedded games — loads from GitHub raw on click).

Internet required for games.
