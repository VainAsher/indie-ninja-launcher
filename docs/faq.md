# FAQ

## Installation

**The launcher will not run. Windows says it is unsafe.**

This is SmartScreen for unsigned binaries. Click `More info`, then `Run anyway`.

**Install/Update does not download game files.**

Check the following:

1. Internet connection is stable
2. Java 21+ is installed
3. Firewall/proxy is not blocking GitHub downloads
4. You are using a current launcher runtime (`v1.x`)

**My antivirus flags the launcher exe.**

Unsigned PyInstaller builds can trigger false positives.
Verify the source repo and allowlist if needed.

**Report submission says the URL is too long.**

Older launcher builds may hit browser URL limits when long log tails are attached.
Update to latest launcher runtime (`v1.x`), or submit shorter text.

---

## Gameplay

**How do I save progress?**

Progress is auto-saved at game-defined checkpoints and transitions.

**Where are saves stored?**

`user_data/saves/` under your configured game directory.

**How do I leave a mission?**

Press `Esc` and use `Quit to Menu`.

---

## Multiplayer

**How do I play with friends?**

Use launcher `Host + Play` or `Join Game`.
See [Multiplayer Guide](multiplayer.md).

**Friends cannot join my hosted game.**

For LAN, confirm local IP and same network.
For internet, forward TCP `7777` and allow firewall access.

**We get lag or desync symptoms.**

Use LAN as baseline, confirm same game version across players, then report logs if issue persists.

---

## Performance

**Performance feels unstable.**

Attach logs from `user_data/logs/` in your feedback report and include:

- version tag
- mode (solo/host/join)
- area or mission context
- reproducible steps

---

## Replays

**Where are replays saved?**

`user_data/replays/` in your configured game directory.

**How do I replay a session?**

Launcher `Dev Tools` -> `Launch Replay`.

---

## Community

**How can I help while the game is still in development?**

The quickest way:

1. Play a short session
2. Report one bug, confusion point, or positive highlight
3. Include version, mode, and repro steps

See [Community Guide](community.md) for the full loop.
