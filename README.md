# Why hire me? — Jie Chen's portfolio

A single-page portfolio: plain HTML, CSS and JavaScript, no build step. All images are in `assets/`.

## Deploy (Cloudflare Workers, static assets)
1. In Cloudflare: Workers & Pages → Create → Import a repository → pick `why-hire-me`.
2. Leave the build command empty. Cloudflare reads `wrangler.jsonc` and serves the folder as a static site.
3. Add a custom domain (e.g. `new.jiechen.design`) under the worker's Settings → Domains & Routes.

Every push to `main` deploys automatically.

## Case studies
Each case opens in an in-page reader and has its own link, e.g. `/#pocket-gem`, `/#coop`, `/#transparent-ai`.
