# viciens.com — workspace notes

This is the **deploy repo** for viciens.com. NOT the source of truth — it's a derived artifact.

## Source of truth lives elsewhere

The Viciens brand kit, voice docs, legal artifacts, and research all live in:
`/Users/jasoncumbers/active/viciens-brand/`

The canonical stub source is `viciens-brand/viciens/site/index.html`. When that changes, mirror the changes here with relative-path fixes (`../brand/...` → `brand/...`).

## What's in this repo

- `index.html` — the stub (single file, ~200 lines)
- `brand/` — only the 3 SVG assets the stub uses (favicon.svg, favicon-dark.svg, wordmark-dark.svg)
- Standard support files (.gitignore, README.md, this file)

Nothing else. **Do not add legal docs, research, voice.md, or any other content from viciens-brand here** — this repo is publicly served at viciens.com.

## Brand rules still apply

The locked v1.9 brand kit governs the visual layer: Boska / Synonym / JetBrains Mono fonts, vellum / ink / lapis color tokens, wordmark on dark surface only in vellum. See [viciens-brand/viciens/brand/README.md](file:///Users/jasoncumbers/active/viciens-brand/viciens/brand/README.md).
