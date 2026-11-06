# MARVEL: Rift Arena

A small, fan-made 3D browser arena prototype. The site is static and uses Three.js from jsDelivr at runtime.

## Deploy to Render

This folder is arranged as the repository root for Render. Push the folder to a GitHub or GitLab repository, then create a Render Static Site from that repository. Render reads `render.yaml` and publishes `public/`.

Render static sites receive a public `onrender.com` URL. Anyone with that URL can open the game.

Render's Static Site flow requires a linked Git repository. The dashboard sign-in and repository connection still need to be completed before the first deploy.

## Run locally

Run `run-game.ps1` in PowerShell. Python 3 is required to serve the ES module page over HTTP.
