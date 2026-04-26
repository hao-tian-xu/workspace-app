# Cosm

**A curated window sidebar for every task. Group windows by what you're doing. Switch in one click.**

Cosm is a macOS productivity app that replaces Cmd-Tab roulette and Mission Control walls with something simpler: a hand-picked sidebar per task. Create a Space for each project, pick exactly which windows belong in it, and switch to that Space with one click — only those windows appear, everything else hides.

No automatic lists of every app you have open. No tiling you didn't ask for. Just the three to five windows you actually need for the thing you're doing right now.

## Why "Cosm"?

Cosm is short for *microcosm* — a small, self-contained world. Each Space in Cosm is its own microcosm: just the windows you chose for one task, nothing else in sight.

## Features

- **Spaces** — Named workspaces you build by hand, each holding any combination of windows from any apps
- **Curated sidebar** — Every Space shows only its windows in the sidebar. No Cmd-Tab through every app, no Mission Control wall of thumbnails
- **One-click switching** — Click a Space and only its windows appear; everything else hides instantly. Click back and windows return to their exact positions
- **Per-window granularity** — The same app can live in multiple Spaces with different windows. Chrome for "Project A" ≠ Chrome for "Code Review"
- **Menu bar app** — Runs from the menu bar; no Dock icon

## Demo

![Image](https://github.com/user-attachments/assets/bba874e1-eb02-479a-a605-994da0086073)

## Download

**[Download Cosm v0.1.0](https://github.com/ianhxu/cosm-app/releases/latest)**

## Requirements

- macOS 14 (Sonoma) or later
- Accessibility permission (required for window management)

## Installation

1. Download the `.dmg` file from the [latest release](https://github.com/ianhxu/cosm-app/releases/latest)
2. Open the `.dmg` and drag **Cosm** to your Applications folder
3. Launch Cosm — on first launch, grant **Accessibility** permission when prompted
   - If you missed the prompt: System Settings → Privacy & Security → Accessibility → enable Cosm

## Known Issues

This is an early beta. Some things to be aware of:

- Uses SkyLight private framework for single-window activation — stable for 10+ years, but not compatible with the Mac App Store
- Window hiding works by moving windows off-screen (macOS limitation); a thin sliver may occasionally be visible at the screen edge
- Sidebar is fixed to the left edge
- Accessibility permission is required — the app cannot function without it

## Feedback

Found a bug or have a feature request? [Open an issue](https://github.com/ianhxu/cosm-app/issues/new/choose).

## License

Cosm is proprietary software. All rights reserved.
