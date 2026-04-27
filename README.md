# DeadlineGhost

**A ghost that haunts your deadlines.**

ADHD-friendly visual timer with white noise for macOS. A menu bar ghost that follows your cursor and grows more agitated as your deadline approaches.

[![Download on the Mac App Store](https://img.shields.io/badge/Download-Mac%20App%20Store-blue?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com/app/deadlineghost)
[![Platform](https://img.shields.io/badge/platform-macOS%2026+-333?style=for-the-badge&logo=apple)](https://apps.apple.com/app/deadlineghost)
[![Website](https://img.shields.io/badge/website-live-green?style=for-the-badge)](https://develku.github.io/deadlineghost-website/)

## How It Works

1. **Add a deadline** — Create a task from the menu bar. Pick a quick time (5m, 15m, 1h) or set any date.
2. **Watch it approach** — The ghost tracks your cursor. As time runs out, colors shift and animations intensify.
3. **Feel the pressure** — The ghost turns red, shakes violently, and the bar disappears. You feel the urgency without clock-checking.

## Features

- **Visual urgency system** — Four ghost states (Calm → Approaching → Hovering → Enraged) that you feel, not read
- **Pomodoro timer** — Configurable focus sessions with break cycles
- **White noise** — Auto-toggles macOS Background Sounds during focus sessions via a one-tap Apple Shortcut (App Sandbox–safe). Rain, stream, ocean, and more. [Setup details](https://develku.github.io/deadlineghost-website/shortcut-setup.html).
- **Ghost skins** — Multiple ghost personalities with unique animations and weather effects
- **Customizable** — 7 accent colors, ghost size, bar opacity, keyboard shortcuts, launch at login
- **Liquid Glass UI** — Built for macOS 26 with native Liquid Glass design
- **Privacy-first** — All data stays local on your Mac

## Background sounds (Shortcut-based)

DeadlineGhost controls macOS Background Sounds (Accessibility → Audio → Background Sounds) through a user-installed Apple Shortcut named `DeadlineGhost Background Sounds`, not by writing system preferences directly. This is what makes the app App Sandbox–safe and App Store distributable.

**Install in one tap:** [iCloud share link](https://www.icloud.com/shortcuts/c176d5d37a464a648045743023c9a6d1)

**Build it yourself:** [shortcut-setup.html](https://develku.github.io/deadlineghost-website/shortcut-setup.html)

The shortcut accepts a single text input:

| Input    | Effect                              |
|----------|-------------------------------------|
| `on`     | Turn background sounds ON           |
| `off`    | Turn background sounds OFF          |
| `vol:50` | Turn ON at 50% volume (any 0–100)   |

Picking which sound plays (rain, stream, ocean, …) lives in **System Settings → Accessibility → Audio → Background Sounds** — the Shortcuts `Change Background Sound` action only takes a fixed picker value, not a magic variable.

## Roadmap

- [x] macOS app (launching soon)
- [ ] iPhone app with iCloud sync
- [ ] iPad app with multitasking support
- [ ] Desktop & Lock Screen widgets

## Links

- [Website](https://develku.github.io/deadlineghost-website/)
- [Mac App Store](https://apps.apple.com/app/deadlineghost)
- [X / Twitter](https://x.com/deadlinehaunt)
- [Contact / Feedback](https://github.com/develku/deadlineghost-website/issues)

## License

Copyright 2026 kud lee. All rights reserved.
