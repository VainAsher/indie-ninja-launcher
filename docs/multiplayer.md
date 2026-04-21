# Multiplayer Guide

Shadow Ascent supports 1-4 player sessions.

One player hosts, others connect to that host.

---

## How To Host

1. Open the launcher
2. Click **Host Game**
3. Set the port (default: `7777`)
4. Click **Host + Play**
5. Share your IP with other players

For LAN games, share local IP (example: `192.168.1.5`).
For internet games, share public IP and forward TCP `7777`.

---

## How To Join

1. Open the launcher
2. Click **Join Game**
3. Enter `host:port` (example: `192.168.1.5:7777`)
4. Click **Launch**

---

## Port Forwarding (Internet Play)

To accept internet players, the host must forward TCP `7777` from router to host PC.
Router steps vary by model.

---

## Replay System

Replays are available in launcher Dev Tools and stored in `user_data/replays/`.

To replay a session:

1. Open launcher
2. Go to **Dev Tools**
3. Click **Launch Replay**
4. Select a replay file

Replays are deterministic input playback, not video captures.

---

## Current Notes

- LAN is the best baseline for low-latency playtesting.
- All players must run the same game version.
- Host firewall and router setup is required for internet sessions.

---

## Troubleshooting

**Cannot connect**

- Confirm host IP and port
- Confirm firewall access on host
- Test LAN first

**Lag/desync symptoms**

- Confirm same build across all players
- Prefer LAN when diagnosing

**Crash on connect**

- Check logs in `user_data/logs/`
- Report with build tag and repro steps at:
  [indie-ninja-feedback](https://github.com/VainAsher/indie-ninja-feedback/issues/new/choose)
