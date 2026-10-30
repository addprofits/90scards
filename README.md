# 90scards.net

Static site for 90scards.net: 1990s basketball, football and baseball card sets, inserts, odds and scans.

- `index.html`: the whole site (HTML, CSS and JS in one file)
- `img/boxes/`: box photos
- `img/cards/`: card scans, named `{set}-{player}-{insert}-{version}-{f|b}.webp`

No build step. Serve the folder as-is (Cloudflare Pages: framework preset "None", build command empty, output directory `/`).
