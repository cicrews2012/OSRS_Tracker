# OSRS_Tracker










# ⛏ MLM Haul Tracker

A live-price Old School RuneScape Motherload Mine haul tracker hosted on GitHub Pages.

## Features

- **Live GE prices** — pulls from the OSRS Wiki Real-time Prices API every 5 minutes, no setup needed
- **Ore tracking** — Gold, Mithril, Adamantite, Runite, Coal with correct GP calculations per your strategy
- **Gem jewellery calculator** — all 20 combinations (4 types × 5 gems), raw vs enchanted profit with rune costs deducted, best option auto-selected
- **Coal analysis** — calculates surplus/deficit against Addy bar needs, shows buy cost or sell value
- **Grand total** — live GP breakdown by ore, gems, and coal

## How to host on GitHub Pages

1. Create a new GitHub repository (can be private or public)
2. Upload `index.html` to the root of the repo
3. Go to **Settings → Pages → Source → Deploy from branch → main / root**
4. GitHub will give you a URL like `https://yourusername.github.io/mlm-tracker/`
5. Bookmark it — prices refresh automatically every 5 minutes when you have the page open

## Notes

- Prices come from the [OSRS Wiki Real-time Prices API](https://prices.runescape.wiki/api/v1/osrs/latest) — the same data RuneLite uses
- If the direct API call is blocked by your browser, the app falls back to an allorigins proxy
- No server, no Python, no installs — pure static HTML/JS
