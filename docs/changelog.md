# Changelog

Player-facing release notes for launcher distribution lanes.

For full technical details, see the game repo changelog:
[indie-ninja-adventures/docs/CHANGELOG.md](https://github.com/VainAsher/indie-ninja-adventures/blob/main/docs/CHANGELOG.md)

---

## v0.12.00 - April 2026 (game-content mirror)

- Distribution lane now mirrors Java runtime assets from game releases:
  - `ninja-client-all.jar`
  - `ninja-server-all.jar`
  - docs archive zip
- Focus: repo cleanup, workflow adoption, release-lane hardening.
- No major feature drop in this tag; primarily operational and documentation work.

---

## v1.1.0 - April 2026 (launcher runtime)

- Public launcher runtime release (`ninja_dash_launcher.exe`)
- Launcher includes:
  - update/install flow
  - report submission tab
  - dev tools (logs, replays, diagnostics)
  - multiplayer host/join controls

---

## Notes On Versioning

- `v1.x` tags are launcher-runtime builds.
- `v0.x` tags are mirrored game runtime/content assets.

If you need the launcher executable itself, use the latest `v1.x` release.
