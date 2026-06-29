# Min-Max Coach

**A free, lightweight League of Legends coach that runs alongside your game — and can't get you banned.**

Real-time draft help, lane-matchup coaching, build paths, objective timers, and a post-game "climb plan" — in a ~3 MB app with **no account, no ads, no API key, and nothing that ever leaves your PC.**

### [⬇ Download the latest version](../../releases/latest)

---

## Why I built this

I love this game, but I got tired of the tools around it. The best coaching info is locked behind monthly subscriptions. The popular overlays are heavy, ad-stuffed, and want you to create an account so they can harvest your data. And a few of them quietly put your account at risk by reading things they shouldn't.

I also believe climbing isn't a secret. I was able to get to Diamond from just basic fundamentals and decisions. A Challenger player isn't seeing hidden information — they're reading the **same public information you already have**, and making the right call a half-second sooner. *Recall on this wave. Group for this drake. Build this item into their comp.* That's learnable.

So I built the coach I always wanted: one that reads the public game state alongside you and tells you the next right move, in the moment — and gives it away **free, forever**, with nothing sketchy under the hood. No account. No ads. No data leaving your PC. Nothing that can get you banned.

If it helps even a few people climb, it was worth building.

## What makes it different

| | **Min-Max Coach** | Typical overlays |
|---|---|---|
| **Price** | Free — *every* feature | Best features behind a subscription |
| **Account** | None — just run it | Sign-up + login required |
| **Your data** | Stays on your PC | Often uploaded / harvested |
| **Footprint** | ~3 MB, zero ads | Heavy, ad-stuffed |
| **Safety** | Public data only — can't get you banned | Some risk your account |
| **What it gives** | Real-time **decisions**, not just stats | Mostly stat dashboards |

## What it does

- **Champ select** — team-comp read, counter picks, ban suggestions, and a rune/summoner tip for your pick.
- **In game (overlay)** — your next macro move, lane matchup + who has priority, the exact next item to buy, and dragon/baron/herald/grub timers, all on a movable overlay.
- **Between games** — performance trends, a focused **climb plan**, and progress toward your rank goal.

## Why it's safe — it can't get you banned

Min-Max Coach uses **only official, public Riot interfaces** (the in-game Live Client Data API and the local League Client API) plus public Data Dragon data. It does **not**:

- read game memory or inject code,
- automate your client (it only ever *recommends* — never auto-accepts, picks, or dodges),
- surface any hidden opponent information (no enemy cooldowns, positions, or summoner timers),
- require a Riot API key, an account, or any login.

Everything runs locally on your machine. See **[PRIVACY.md](PRIVACY.md)**.

## Install

1. Download the `.exe` from the **[latest release](../../releases/latest)**.
2. Run it. Windows may show a SmartScreen warning (the app isn't code-signed yet) — click **More info → Run anyway**.
3. Launch League of Legends. Min-Max Coach connects automatically.

**Requirements:** Windows 10/11.

## Free, forever

This is and always will be free — every feature, no paywall. If it helps you climb and you'd like to support development, donations are welcome (link coming soon), but they're never required.

## Feedback

Found a bug or have an idea? **[Open an issue](../../issues)** — feedback shapes what gets built next.

---

<sub>Min-Max Coach is not endorsed by or affiliated with Riot Games. "League of Legends" and "Riot Games" are trademarks of Riot Games, Inc. © 2026. Licensed under [EULA.txt](EULA.txt).</sub>
