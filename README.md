# Habagat Games privacy pages

Public, static privacy policies for Habagat Games. No custom domain and no paid service.

The site source is the `docs/` folder on `main`. GitHub Pages is not on yet: this agent's token can push the files, and `GET /pages` is 404, but `POST /pages` returns 403 (no Pages administration permission). A repository admin turns it on under **Settings → Pages**:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/docs**

The public URL is then https://mikalikan.github.io/habagat-privacy/ . The first build can take a few minutes. A GitHub Actions deploy was tried and removed; `actions/configure-pages` cannot create the site with the default `GITHUB_TOKEN` until Pages already exists.

## Lagoon Rings

Privacy policy (English): [https://mikalikan.github.io/habagat-privacy/](https://mikalikan.github.io/habagat-privacy/)

Source: [`docs/index.html`](docs/index.html)

That address is the in-app and Play Console link for the Lagoon Rings release. The game repository stays private. This repository contains only the public page.
