# Meyad Guard — Home header ads

Live ad image for the Meyad Guard app's home header.

- `ads/current.jpg` — the ad image shown in the header (1080x920 px).
- `ads/manifest.json` — the file the app fetches. `version` must go up by 1 every time the image changes, so phones drop the old cached image.

## How to change the ad (from your phone)

1. Open this repo on github.com and upload a new `current.jpg` into the `ads` folder (it replaces the old one).
2. Edit `ads/manifest.json` and raise `version` by 1.
3. Done — the app picks it up live, no app update needed.
