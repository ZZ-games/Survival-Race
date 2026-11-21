# Survival Race

Runs straight from GitHub Pages — no CDNs, ads, trackers or Poki SDK.

- **`index.html`** — the game page. Loads the Unity build from `game/survival-race-us/Build/` in this repo.
  Live: https://zz-games.github.io/Survival-Race/
- **`survival-race.html`** — the whole game packed into one self-contained HTML file (~18 MB).
  Works offline, opened from disk, or dropped into any host. No other files needed.

The Poki SDK and loader were replaced with a small built-in stub, so ad breaks are skipped
and rewarded-ad bonuses are granted instantly.
