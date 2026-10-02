# Site-Management — releases

Built releases of **site-manager** (ניהול מסמכי אתר). This repository holds
release files only: no source code, no history, no configuration or secrets.

Each release carries one asset, `site-manager-web-<version>.zip` — the built
web app with `index.html` at its top — and its SHA-256 in the release notes.
Releases are published automatically when a version is merged in the private
source repository.
