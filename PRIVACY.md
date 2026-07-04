# Privacy Policy — Min-Max Coach

_Last updated: 2026_

Min-Max Coach is built privacy-first. **Nothing leaves your computer.**

## What we collect
**Nothing.** Min-Max Coach has no account, no login, and no telemetry. We do not
operate a server, and the app does not send your data anywhere.

## What stays on your PC
The app stores a few files locally, under `%APPDATA%\gg.minmax.coach\`:

- `history.jsonl` — a per-game record of your own public stats (CS/min, vision,
  KDA, etc.) used for the Trends and Climb Plan views.
- `settings.json` — your preferences (hotkeys, champion pool, climb goal).
- `overlay-layout.json` — where you positioned the overlay widgets.

These never leave your machine. You can delete them at any time (the in-app
"Clear history" button removes `history.jsonl`).

## What data sources it reads
Public, read-only interfaces:

- **Live Client Data API** (`127.0.0.1:2999`) — your own visible game state, the
  same information shown on your screen.
- **League Client (LCU) API** — local, for game-phase and champ-select events.
- **Data Dragon** (Riot's public CDN) — static champion/item data.
- **Build data** (`meta.json`): a single file of build, rune, and summoner
  recommendations, downloaded from the project's own public repository. It is a
  one-way download of recommendations; none of your data is sent to fetch it.

It does **not** read game memory, inject code, automate the client, require a
Riot API key, or access any hidden opponent information.

## Contact
Questions? Open an issue on this repository.
