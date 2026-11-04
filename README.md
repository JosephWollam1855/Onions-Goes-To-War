# Onions Goes To War — Playable Prototype v1

An original tavern-themed version of the classic card game War featuring the supplied Onions mascot.

## Play locally

Download or extract all files in this folder, then double-click `index.html` in Windows. Keep `onions.png` in the same folder.

## Modes

- **Play vs Onions (Computer):** one person against a computer pile.
- **Two Players · Local:** both people share the device, one on each side. Press **Flip Cards** to reveal both cards simultaneously.
- **Auto Play:** advances battles automatically with an on/off button. You may mute the short synthesized sound effects.

Traditional 52-card War rules. Ties trigger War (up to three face-down cards then a face-up card). See **How to Play** in the game for short-deck edge cases.

## Upload to GitHub

1. Open your new `Onions-Goes-To-War` repository.
2. Select **Add file → Upload files**.
3. Upload `index.html`, `onions.png` and `README.md` from the extracted folder.
4. Commit the changes.

## Put the site online

This is a **static website**. It does not need a Node server, npm or a database. If you choose to make the repository public, you may use GitHub Pages (Repository **Settings → Pages → Deploy from branch → main → /(root) → Save**). GitHub Pages availability for private repositories depends on plan, so alternatively create a **Static Site** on Render with this repository; publish directory `.` and leave build command blank.

Your Bug Brigade repository stays separate.

## Notes

The mascot artwork is displayed as a static image; its portrait bounces after wins. Detailed eye/ear animations would require additional animation artwork. This is an early playable prototype, not production-ready. No online multiplayer in v1.
