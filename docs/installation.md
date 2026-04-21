# Installation Guide

## Download

1. Go to [Releases](https://github.com/VainAsher/indie-ninja-launcher/releases)
2. Download `ninja_dash_launcher.exe` from the latest launcher-runtime tag (`v1.x`)
3. Run it (no installer required)

The launcher will then install/update current game runtime assets.

---

## Windows SmartScreen Warning

Windows may show a warning when you first run the launcher:

> "Windows protected your PC"

This is normal for unsigned executables. To proceed:

1. Click **More info**
2. Click **Run anyway**

This is expected for unsigned binaries.

---

## Java Requirement (Current Runtime)

Current game-content releases are JAR-based (`ninja-client-all.jar`, `ninja-server-all.jar`).
Install Java 21+ before launching if prompted by the launcher.

Recommended: Eclipse Temurin 21 LTS.

---

## Firewall / Antivirus

For multiplayer hosting:

- Allow Java / launcher network access through Windows Firewall when prompted
- If playing over the internet (not LAN), the host needs to forward port **7777 TCP** on their router

---

## System Requirements

| Component | Minimum |
|-----------|---------|
| OS | Windows 10 (64-bit) |
| CPU | Intel i3 / AMD equivalent |
| RAM | 4 GB |
| Storage | 300 MB+ |
| Java | 21+ (for current JAR runtime) |
| Network | Required for release checks and multiplayer |

---

## Updating

The launcher checks for updates automatically on startup.
Click **Install/Update** when prompted.

Update lanes are split:

- `v1.x` tags: launcher runtime (`ninja_dash_launcher.exe`)
- `v0.x` tags: mirrored game runtime assets (client/server JARs + docs archive)

If your launcher binary is old, download the newest `v1.x` launcher runtime manually.

---

## File Locations

| File | Location |
|------|----------|
| Game saves | `user_data\saves\` under your configured game directory |
| Logs | `user_data\logs\` |
| Replays | `user_data\replays\` |
| Settings | `user_data\settings\settings.json` |
