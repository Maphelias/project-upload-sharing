# Spellforge (line-frame)

Top-down wireframe co-op spell-crafting game: design your own spells from five elements, clear three zones with up to
four players and beat the Hollow Warden.

## Download

**Current version: 0.1.13** (2026-11-27) - [SpellforgeAlt-0.1.13-Win64.zip](https://github.com/Maphelias/project-upload-sharing/releases/download/SpellforgeAlt-0.1.13/SpellforgeAlt-0.1.13-Win64.zip) (Windows 10/11, 64-bit)

Unzip anywhere and start `SpellforgeAlt.exe`. Nothing to install. Profiles are saved in `Documents\SpellforgeAlt`.

The game checks this folder at start and offers new versions in-game (Esc > Updates): it downloads the new exe
(and README.txt), checks their SHA-256 and restarts. Everyone in a lobby needs the same version.

## Files here

| File | What |
|---|---|
| `latest.json` | The newest version and where its files are (read by the game's updater) |
| `latest.json.sig` | Ed25519 signature of `latest.json` with the release key; the game installs nothing without a valid one |
| `versions.json` | Every published version with its notes |

The files themselves are on the [releases page](https://github.com/Maphelias/project-upload-sharing/releases?q=SpellforgeAlt) (tags `SpellforgeAlt-<version>`).