# drosaka.com

Single-page site: black screen, one centered image. `public/index.html` plus `public/stateless-machine.webp`.

- `public/` — the static site. This folder is what gets served.
- `wrangler.jsonc` — Cloudflare Workers static-assets config (used by Cloudflare's git import and by `npx wrangler deploy`).

## Deploying

Connected to Cloudflare via git import: every push to `main` redeploys.

Manual alternative from this folder: `npx wrangler login && npx wrangler deploy`.
