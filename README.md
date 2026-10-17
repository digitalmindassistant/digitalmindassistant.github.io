# Digital Mind public website

This repository contains only the static public informational website for **Digital Mind**. It provides a product overview, privacy policy, and terms of use for the privately operated Digital Mind personal productivity application.

It does **not** contain the Digital Mind application, server code, SQLite database, user entries, Google messages, OAuth client credentials, authorization tokens, backups, logs, or other private application data.

## Files

- `index.html` — public product homepage
- `privacy.html` — privacy and Google user-data disclosures
- `terms.html` — terms for the current private-development project
- `styles.css` — shared responsive presentation styles

## Local preview

No build process or dependencies are required. Open `index.html` directly, or serve the directory with any local static HTTP server.

For example, with Python installed:

```powershell
python -m http.server 4173 --bind 127.0.0.1
```

Then open `http://127.0.0.1:4173/`.

## GitHub Pages

This repository is intended for GitHub Pages at:

`https://digitalmindassistant.github.io/`

To publish, commit these public files to the repository's default branch, push the branch to GitHub, and configure **Settings → Pages** to deploy from that branch's root directory if Pages is not enabled automatically.

## Privacy boundary

Keep this repository public-safe. Never copy files from the private Digital Mind application into this repository. In particular, do not add:

- `.env` files or secrets;
- OAuth client credential or token files;
- SQLite databases, WAL/SHM files, or backups;
- private notes, SMS messages, research findings, logs, or exports; or
- the private application's server or client source code.
