# viciens.com — deploy repo

Institutional stub for viciens.com. Single-file static HTML, no build step.

This repo is the **deploy artifact only** — what gets served at viciens.com. The brand kit, voice docs, legal artifacts, and research live in `~/active/viciens-brand/` (private master).

## Local preview

```
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

Cloudflare Pages, auto-deploy on push to `main`.
