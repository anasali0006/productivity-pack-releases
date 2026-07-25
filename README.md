# Productivity Pack — Releases

A simple, native macOS app that lives in your top menu bar and boosts your productivity:

- **Focus** — set your goal, arm it, and get a gentle full-screen nudge when you drift
  to a distracting app or website (Chrome, Safari, Edge, Brave, Arc supported).
- **Manage your tasks** — fast day-based task list, easy to use, simple: Today /
  Yesterday / Tomorrow or any date, colored categories, drag to reprioritize.

Everything stays on your Mac — no accounts, no cloud, no tracking.

## Download

Grab the latest `ProductivityPack-vX.Y.Z.zip` from
[**Releases**](../../releases/latest), unzip it, and drag **ProductivityPack.app**
into your **Applications** folder.

**Requirements:** macOS 14 (Sonoma) or newer · Apple Silicon & Intel

## First launch (important!)

This is a test build that isn't notarized by Apple, so macOS quarantines it on
download. One command clears it:

```bash
xattr -dr com.apple.quarantine /Applications/ProductivityPack.app
```

(If you get *Operation not permitted*, prepend `sudo`.)

<details>
<summary>Prefer clicking through instead?</summary>

1. Double-click **ProductivityPack.app** → a dialog says it *"can't be opened"* —
   click **Done** (not "Move to Trash"!)
2. Open **System Settings → Privacy & Security**, scroll down to the message
   *"ProductivityPack was blocked…"* → click **Open Anyway**
3. Confirm, enter your password if asked — done. It opens normally from now on.
</details>

After launching, look for the **eye icon** in your menu bar (top-right of the screen).

## Permissions the app asks for

- **Automation** (System Settings → Privacy & Security → Automation): lets the app see
  your active browser tab's address so it can nudge you on distracting sites. The URL
  never leaves your machine.

## Feedback

Found a bug or have an idea? Message me directly, or open an issue here.
