# Portfolio Hub

A lightweight portfolio landing page for Anna Andersson's deployed software projects.

## Live site

The production URL will be:

```text
https://anna-projects.duckdns.org
```

## Projects

- [Launch Window](https://github.com/Demonetic/launch-window)
- [Monster Hunter Board](https://github.com/Demonetic/monster-hunting-board)

## Technology

The portfolio hub deliberately uses a small static stack:

- HTML
- CSS
- Vanilla JavaScript
- Caddy
- GitHub Actions

No frontend framework is needed for the current scope.

## Local preview

From the repository root:

```powershell
python -m http.server 8000
```

Open:

```text
http://localhost:8000
```

## Deployment

The production server uses Caddy to serve the static files. Deployment automation will be added after the initial server setup.