# Matt's Watchlist — Stremio Addon

Weekly movie recommendations based on my Letterboxd taste, served as a Stremio addon.

## Install

In Stremio, go to Addons → paste this URL:

```
https://mattloud.github.io/stremio-watchlist/manifest.json
```

## How it works

- `manifest.json` — the addon manifest
- `catalog/movie/watchlist-picks.json` — the current week's picks (IMDb IDs; Stremio resolves posters/metadata itself)
- The catalog is refreshed weekly.
