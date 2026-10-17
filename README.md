# Mega Booster (kRO Mega Booster promotion) for Ragnarok Offline

A mod for [Ragnarok Offline](https://github.com/Flux159/ragnarokoffline.app)
(renewal) that adds kRO's Mega Booster promotion (메가 부스터 프로모션): a
Booster Guide in Izlude (Lasagna for Doram) gives a new character the Booster
Box, and the Booster Call summons Lime Evenor for the booster shops, Lv 1–80
hunts, Booster Missions, enchants, Level Up Tickets, milestone rewards and the
upgrade to the Premium Booster Call. The Job Agent, Reset Service and Exchanger
stand in Prontera's Adventurer Convenience Center, with the two Booster
Enchanters in the Illusion and Automatic towns. No server rebuild or rAthena
change is needed.

What each file does, the settings, where it differs from kRO and what to check
in game are in the mod's own [README](mega-booster/README.md).

## Installing

Download `mega-booster-<version>.zip` from the latest
[release](../../releases/latest), then in the app: Settings → Mods → Install
from a folder…, and pick the zip. Restart the server for the NPCs and tables,
and the app for the item, quest and sign text.

## Unverified values

NPC positions, quest IDs, pack contents and item text come from the kRO client
(Dec 2025). Prices, rewards and rules come from gnjoy's 2026 Mega Booster guide
and hazyforest.com. English item and sign text is ROenglishRE's; quest text is
translated from the kRO client. Anything not confirmed by two sources is marked
`[unverified]` where it's used:

```sh
grep -rn unverified mega-booster/
```

Corrections with a source are welcome, Korean sources and kRO client data first.

## Repository layout

| Path | |
|---|---|
| `mega-booster/` | The mod, exactly as it goes in a player's mods folder. |
| `CHANGELOG.md` | One `## <version>` section per release; it becomes the release notes. |
| `scripts/build-release.py` | Checks the mod against the app's limits and builds the release zip. |
| `.github/workflows/` | `check.yml` runs the check on every push; `release.yml` publishes a release when `mod.json` has a new version; `delete-release.yml` (run by hand) removes one. |

## Making a release

1. Change the mod, raise `version` in `mega-booster/mod.json`, and add a
   `## <version>` section to `CHANGELOG.md`.
2. `python3 scripts/build-release.py --check`, commit, and push to `main`.

When `main` carries a version that has no release yet, the release workflow
builds `mega-booster-<version>.zip` from that commit, tags it `v<version>`, and
publishes it as a full release with that version's changelog section.

## License

GPL-3.0, the same as rAthena. See [LICENSE](LICENSE).
