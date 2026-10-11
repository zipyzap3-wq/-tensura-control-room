# Tensura Control Room

A standalone, anime-inspired dashboard for managing the Gobta's Tensura fanfiction workflow.

## Open the dashboard

Once GitHub Pages finishes deploying, open:

https://zipyzap3-wq.github.io/-tensura-control-room/

## What it includes

- Chapter/checkpoint notes
- Character board and story-thread tracker
- Continuity checklist
- Search, local notes, and activity feed
- Exportable JSON and copy-ready writing prompts

## Important notes

- This is a static website. It does not automatically read or edit your story files on GitHub.
- Dashboard changes are saved in the browser's local storage on the device/browser you use.
- The character entries are examples/placeholders until you replace them with verified story information.
- This repository contains the dashboard only; it does not copy your private story drafts.

## Deployment

GitHub Actions is configured to publish this site when a commit is pushed to `main`.

The workflow in `.github/workflows/pages.yml` publishes the root `index.html` through GitHub Pages when changes are pushed to `main`.
