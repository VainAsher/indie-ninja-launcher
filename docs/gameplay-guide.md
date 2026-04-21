# Gameplay Guide

This guide tracks player-facing expectations for the current Shadow Ascent builds.

---

## Current Modes

| Mode | Purpose |
|------|---------|
| **Campaign** | Primary progression path and story-driven flow |
| **Developer** | Expanded debug/testing path for internal playtest coverage |
| **Arcade** | In active development; availability may vary by build |

Use launcher **Play** to enter mode selection.

---

## Core Loop

1. Launch from the launcher Play tab.
2. Select a mode and enter a run.
3. Complete objectives, fights, and traversal challenges.
4. Return to hub/menu and continue progression.

Progression, mission tuning, and content pacing are still being actively iterated.

---

## Progression And Saves

- Save data is stored under `user_data/saves/`.
- Replays are stored under `user_data/replays/`.
- Logs are stored under `user_data/logs/`.
- Launcher Save/Replay tools can inspect and manage these files.

---

## Multiplayer

- Host or join from launcher controls.
- Default host port is `7777`.
- All players should run the same game version.
- LAN is the best baseline when testing connection stability.

See [Multiplayer Guide](multiplayer.md).

---

## Controls And Readability

- Press `F1` in-game for the live controls overlay.
- Use pause/settings to inspect bindings and options.
- Report unclear or misleading inputs via launcher Report tab.

---

## Reporting Gameplay Issues

When reporting, include:

- game version tag
- mode (Campaign/Developer/Arcade)
- single-player or multiplayer context
- reproducible steps
- optional log snippet from `user_data/logs/`

Submit via launcher Report tab or
[indie-ninja-feedback](https://github.com/VainAsher/indie-ninja-feedback/issues/new/choose).
