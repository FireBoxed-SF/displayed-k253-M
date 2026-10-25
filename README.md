# displayed-k253-M
unbeared-Z-J283
a# Loom

Loom is a browser-based workspace with a gaming catalog, embedded web tools, music, settings, accessibility options, and a customizable interface. It is designed to run as a static website and does not require an application framework or build step.

## Features

- Curated game catalogs and embedded games
- Watchables and browser-style workspace views
- Music powered remotely by `moon.html` from jsDelivr
- Themes, accent colors, text readability, motion, and accessibility settings
- Custom wallpapers and session-based preferences

## Files

- `workspace.html` - Main Loom application
- `moon.html` - Hosted remotely from `https://cdn.jsdelivr.net/gh/FireBoxed-SF/luna@main/moon.html`; the local copy is not required

## Test Loom Locally

No dependencies or build tools are required.

From the workspace directory, start a local static server:

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173/workspace.html in a browser.

To use another port:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/workspace.html.

Keep the terminal running while testing. Stop the server with `Ctrl+C`.

## Music CDN

The Music page loads the remote HTML module from:

```text
https://cdn.jsdelivr.net/gh/FireBoxed-SF/luna@main/moon.html
```

An internet connection is required to load the remote module. If the Music page does not appear, check the browser developer console and confirm that the CDN URL is reachable.

Este es El readme.md
