# Productivity Pack — Releases

A lightweight macOS menu-bar app to boost productivity:

- **Focus** — set your goal, arm it, and get a gentle full-screen nudge when you drift
  to a distracting app or website (Chrome, Safari, Edge, Brave, Arc supported).
- **To-Do** — fast day-based task list: Today / Yesterday / Tomorrow or any date,
  colored categories, drag to reprioritize, one-click "move ahead" for yesterday's
  unfinished tasks.

Everything stays on your Mac — no accounts, no cloud, no tracking.

> This repository hosts downloads only. The source code is private.

## Download

Grab the latest `ProductivityPack-vX.Y.Z.zip` from
[**Releases**](../../releases/latest), unzip it, and drag **ProductivityPack.app**
into your **Applications** folder.

**Requirements:** macOS 14 (Sonoma) or newer · Apple Silicon & Intel

## First launch (important!)

This is a test build that isn't notarized by Apple, so macOS will block the first
launch. This is expected — you only have to do this once:

1. Double-click **ProductivityPack.app** → a dialog says it *"can't be opened"* —
   click **Done** (not "Move to Trash"!)
2. Open **System Settings → Privacy & Security**, scroll down to the message
   *"ProductivityPack was blocked…"* → click **Open Anyway**
3. Confirm, enter your password if asked — done. It opens normally from now on.

<details>
<summary>Terminal alternative (one command, skips the dance)</summary>

```bash
xattr -dr com.apple.quarantine /Applications/ProductivityPack.app
```
</details>

After launching, look for the **eye icon** in your menu bar (top-right of the screen).

## Permissions the app asks for

- **Automation** (System Settings → Privacy & Security → Automation): lets the app see
  your active browser tab's address so it can nudge you on distracting sites. The URL
  never leaves your machine.

## Feedback

Found a bug or have an idea? Message me directly, or open an issue here.
