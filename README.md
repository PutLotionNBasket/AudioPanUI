AudioPanUI — Alpha Version

**AudioPanUI** is a lightweight Windows utility that automatically pans application audio left or right based on the position of the active window on your screen.

Move a window to the left → audio shifts left.
Move it right → audio shifts right.
Center the window → audio recenters smoothly.

The goal is subtle, natural spatial awareness across single or multiple monitors without manual mixing.

---

## Status

**Version:** v0.2.0 Alpha

**Stability:** Core engine stable, GPU-safe rendering enabled

**Scope:** Early public preview for feedback

This build is intended for real-world testing, not final release.  As to being stable, this version has not had any noticeable bugs while running 3 days straight.

---

## Features

* Note: 'Headphones' & 'Speakers' on the Output selection are for preferable presets - not actually changing audio sources
* Real-time stereo panning driven by active window position
* Smooth, equal-power panning, with motion smoothing
* Independent handling of multiple windows playing audio
* System tray mode
* Single global hotkey:
	* Ctrl + Alt + P → Toggle panning
* Turning OFF automatically recenters audio
* GPU-safe software rendering for maximum stability on external monitors
* Single-file executable (no install required, but larger file size)

---

## What’s intentionally NOT in alpha

To keep behavior clean and predictable:

* No dead-zone snapping
* No complex configuration UI
* No custom hotkey editor

These may arrive in later versions based on feedback.

---

## Running the app

1. Launch **AudioPanUI.exe** (fully extracted from ZIP file)
2. The app can minimize to the system tray
3. Use Ctrl + Alt + P anytime to toggle panning on/off

No installation or administrator rights required.

---

## Known limitations

* Early alpha UI polish is minimal
* Some background/system audio sessions may appear in logs
* Multi-monitor edge behavior may evolve with feedback

No hardware risk — the app only adjusts **software audio balance**.

---

## Feedback

If you have thoughts, bugs, or ideas, share them where you found this build.

Even short feedback helps shape the next version.

---

## License / distribution

This alpha is shared free for testing.
No guarantees, no warranty — just an experimental utility being explored.
