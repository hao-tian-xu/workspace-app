# Workspace

**Group your apps and windows by task. Switch context in one click.**

Workspace is a macOS productivity app that lets you organize open windows into named workspaces. Switch between workspaces instantly — the right windows appear, everything else gets out of the way.

## Features

- **Spaces** — Create named workspaces and group any combination of app windows into each one
- **Instant switching** — Switch between spaces and only the active window is visible; all others are hidden automatically
- **Sidebar** — A persistent sidebar shows all tabs in the current space; click to switch
- **Window management** — Active windows auto-fill the screen area next to the sidebar
- **Multi-window apps** — Add individual windows from the same app to different spaces
- **Add apps easily** — Browse or search installed apps; pick specific windows for multi-window apps

## Screenshots

<!-- TODO: Add screenshots/GIF demo -->

## Download

**[Download Workspace v0.1.0-beta](https://github.com/hao-tian-xu/workspace-app/releases/latest)**

## Requirements

- macOS 14 (Sonoma) or later
- Accessibility permission (required for window management)

## Installation

1. Download the `.dmg` file from the [latest release](https://github.com/hao-tian-xu/workspace-app/releases/latest)
2. Open the `.dmg` and drag **Workspace** to your Applications folder
3. Launch Workspace — on first launch, grant **Accessibility** permission when prompted
   - If you missed the prompt: System Settings → Privacy & Security → Accessibility → enable Workspace

## Known Issues

This is an early beta. Some things to be aware of:

- Uses SkyLight private framework for window activation — not available on the Mac App Store
- Window hiding works by moving windows off-screen (macOS limitation); a thin sliver may occasionally be visible at the screen edge
- Accessibility permission is required — the app cannot function without it

## Feedback

Found a bug or have a feature request? [Open an issue](https://github.com/hao-tian-xu/workspace-app/issues/new/choose).

## License

Workspace is proprietary software. All rights reserved.
