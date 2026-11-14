# Code Valley 0.1.0-beta.2

Early, free, non-commercial friends preview for Apple Silicon. Public binary download; application source stays private. No automatic updater. No Codex, Windows, Intel, mobile or multiplayer integration.

## Try

- Independent farms per repository and cat farmers for Claude Code sessions.
- Crop growth, visible harvest collection, per-farm inventory and mixed-crop trades for three fixed-slot decorations.
- Five cat colors, a wooden farmhouse, perimeter fence and connected terrain.
- Farm tabs, attention indicators, pin, internal menu, settings and reviewed diagnostic reports.
- Hook preview, backup, install and uninstall that preserve unrelated Claude settings.

Compared with the earlier review candidate, beta.2 loads the farm scene on first opening, skips hidden-window live view transfers and reuses native tray images. These optimizations do not establish a final CPU/memory budget pass.

## Compatibility and installation

- Apple Silicon / arm64. Native checks used macOS **26.5.1**; the package's 15.0 build floor does not establish support for all older systems.
- Claude Code terminal and Claude Desktop's **Code** environment are the intended integrations. Full current real-Desktop acceptance remains pending; ordinary Claude chat is not supported.
- **Ad-hoc signed, not notarized.** Local Gatekeeper assessment rejected the app. First launch may require an explicit per-app exception; see [INSTALL.md](INSTALL.md). Actual browser-download/quarantine installation is a remaining pilot test.
- No developer tools or Code Valley account are required.

## Known limits

Final CPU/memory measurements, real-Claude and longer real-use checks are pending. Native accessibility, permissions/notifications, crowded menu-bar and system behavior are still being checked. Report high resource use or missing alerts. The first friend journey has not been recorded.

Current full-suite testing is incomplete under extreme host load: one unchanged hook timing guard exceeded its 500 ms limit and four frontend workers failed to initialize. The missed frontend cases and model tests passed separately; this is not a fresh uninterrupted full-suite pass. Local bundle/signature/resource/checksum checks and isolated beta.1→beta.2 update/reinstall/compatible-backup checks passed.

Transcript fallback is optional, off by default and cannot identify permission requests. Farm saves are batched for up to two seconds. Historical harvest totals do not retroactively fill inventory. Forget removes current farm progress but retains recovery copies; it is not a purge.

## Exact package

- File: `Code-Valley_0.1.0-beta.2_macOS_arm64.zip`
- Size: **3,596,412 bytes**
- SHA-256: `63d7e2a033ee6b0e11ea17c88d3c97fcc2c19eae82986b2f103fdf75c080d815`
- Frozen source revision: `d799669ffe51dbc5b5ffb786ed0cadd57d0b21a6`

The original ZIP is unchanged. Credits and asset/dependency notices are bundled. Updates use a new beta version; do not replace these bytes silently. Follow [installation and recovery instructions](INSTALL.md) and the [public/private feedback guidance](README.md#feedback).
