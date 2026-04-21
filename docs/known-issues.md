# Known Issues

Current player-facing issues and operational caveats.

---

## Launcher Runtime vs Game Runtime Tags

**Severity:** Low  
Launcher binary and mirrored game assets are versioned on separate lanes:

- `v1.x` -> launcher runtime (`ninja_dash_launcher.exe`)
- `v0.x` -> mirrored game runtime assets (`ninja-client-all.jar`, `ninja-server-all.jar`)

If latest `v0.x` release has no launcher exe, use the newest `v1.x` launcher runtime.

---

## Java Requirement For Current Game Runtime

**Severity:** Medium (setup blocker)  
Current game runtime assets are JAR-based and require Java 21+.

**Workaround:** Install Java 21 LTS (Temurin recommended) and relaunch.

---

## Internet Hosting Requires Manual Network Setup

**Severity:** Medium (connectivity)  
Friends outside your LAN cannot join unless host network rules are configured.

**Workaround:** Allow firewall prompts and forward TCP port `7777` to host PC.

---

## Long Report Bodies On Older Launcher Builds

**Severity:** Low  
Older launcher builds may fail to open prefilled feedback URLs when logs make the URL too long.

**Workaround:** Update launcher runtime (`v1.x`) or submit shorter report text.

---

## Reporting New Issues

Report at
[indie-ninja-feedback](https://github.com/VainAsher/indie-ninja-feedback/issues/new/choose)
with:

- version tag
- mode/context
- repro steps
- optional `user_data/logs` snippet
