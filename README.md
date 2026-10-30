# 90scards.net

Static site for 90scards.net: 1990s basketball, football and baseball card sets, inserts, odds and scans.

- `public/index.html`: the whole site (HTML, CSS and JS in one file)
- `public/img/boxes/`: box photos
- `public/img/cards/`: card scans, named `{set}-{player}-{insert}-{version}-{f|b}.webp`

No build step. Deployed as a Cloudflare Worker with static assets (`wrangler.jsonc` serves `public/`).
