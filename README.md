# Poké Pack Party

Free, unofficial, noncommercial Pokémon card-opening simulator for family use. One real card per pack, spinning rarity roulette, rare-pull particles, 3D foil tilt, separate browser-local profiles, binders, and JSON backup/export.

## GitHub Pages installation

1. Create a new GitHub repository, for example `pokemon-pack-party`.
2. Upload **index.html** to the repository root and commit it. (README.md is optional.)
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**. Select `main` and `/ (root)`, then **Save**.
5. After GitHub finishes deployment, open `https://YOUR-USERNAME.github.io/pokemon-pack-party/` in Safari.

No build tools, server, npm, or API key required. GitHub Pages serves the HTML over HTTPS, which avoids local `file://` restrictions.

## Notes

- Card images are fetched from `images.pokemontcg.io` and need an internet connection. The game displays a fallback if a card image cannot be loaded.
- Profiles are local to each browser/device, **not cloud accounts**. Use **Export backup** in the binder to save collections, and **Import backup** to restore them on another device.
- The rarity color tiers and odds are **game-defined**, not official Pokémon TCG pack odds. The initial curated pool includes Base Set and Scarlet & Violet—151 cards.
- No ads, purchases, accounts, tracking, or user data collection.
- Unofficial fan project. Not affiliated with or endorsed by Nintendo, The Pokémon Company, or Creatures Inc. Respect artwork and brand rights if publishing or distributing widely.
