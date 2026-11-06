# MARVEL: Rift Arena

A small, fan-made 3D browser arena prototype. The site is static and uses Three.js from jsDelivr at runtime.

## Deploy to Render

The repository root contains `index.html`. Render reads `render.yaml` and publishes the repository root.

Render static sites receive a public `onrender.com` URL. Anyone with that URL can open the game.

The Render Static Site is connected to this Git repository. Each push to `main` triggers a new deploy.

## Run locally

Serve `index.html` over HTTP locally. Python 3 users can run `python -m http.server 8000` from this folder and open `http://localhost:8000`.
