# Indie Ninja Adventures - Launcher Distribution

Public distribution and player-facing docs for Shadow Ascent.

---

## Download

Use [Releases](https://github.com/VainAsher/indie-ninja-launcher/releases) and pick assets based on what you need:

- `ninja_dash_launcher.exe` from launcher-runtime tags (`v1.x`, currently `v1.1.1`)
- mirrored game runtime assets from game-content tags (`v0.x`), including:
  - `ninja-client-all.jar`
  - `ninja-server-all.jar`
  - docs archive zip

If the latest release is a `v0.x` game-content mirror and does not include the launcher exe,
download `ninja_dash_launcher.exe` from the latest `v1.x` launcher-runtime release.

---

## What The Launcher Does

- Checks for new game releases and installs updates
- Supports both EXE-era assets and current JAR-based runtime assets
- Launches solo, host, and join flows
- Opens prefilled bug/feedback reports to the feedback repo
- Includes Dev Tools for logs, replays, and diagnostics

---

## Current Requirements

- Windows 10 or 11 (64-bit)
- Java 21+ for current JAR-based game runtime (`v0.12+`)
- Internet connection for release checks and downloads

---

## Quick Start

1. Download `ninja_dash_launcher.exe` from the latest launcher-runtime release (`v1.x`)
2. Run it (SmartScreen may require `More info -> Run anyway`)
3. Click Install/Update to pull the latest game runtime assets
4. Launch solo or multiplayer from the Play tab

See [Installation Guide](docs/installation.md) for full setup.

---

## Player Guides

- [Installation Guide](docs/installation.md)
- [Controls Reference](docs/controls.md)
- [Gameplay Guide](docs/gameplay-guide.md)
- [Multiplayer Guide](docs/multiplayer.md)
- [FAQ](docs/faq.md)
- [Known Issues](docs/known-issues.md)
- [Changelog](docs/changelog.md)

---

## Reporting Issues

Use the launcher's Report tab, or file directly at
[indie-ninja-feedback](https://github.com/VainAsher/indie-ninja-feedback/issues/new/choose).

---

## For Developers

Launcher source is maintained in the private game repo:
`VainAsher/indie-ninja-adventures/launcher/launcher.py`.

This public repo is distribution + player documentation.

See [SETUP.md](SETUP.md) for repo setup.
