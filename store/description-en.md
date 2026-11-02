# Bubble Aim — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Aim, bounce and pop! Match 3+ same-colored bubbles in the hex grid, drop
loose clusters for bonus points, and clear the board before it crosses the
line. (153 chars)

## Details

- Genre: Puzzle / Casual / Shooter (bubble shooter)
- Controls: Mouse / Touch (drag to aim, release or tap to shoot). Keyboard:
  ←/→ aim, Space/↑ shoot, S swap, M mute.
- Features: Wall-bounce aim prediction with landing ghost, pop scoring
  (+10 per bubble), falling-cluster bonus (+20 each), push-down pressure
  every few shots, endless levels with more colors and faster pressure,
  swap current/next bubble, best score & best level saving, procedural
  graphics & sounds, single-file HTML5 (no external assets), works
  offline once loaded.
- Tech: Vanilla JavaScript, Canvas, WebAudio. No frameworks, no tracking.

## Tags
bubble shooter, bubble, puzzle, casual, arcade, hex, match-3, shooter, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales, portrait-friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover 16:9 (1280x720) — to capture
- [ ] Screenshots — to capture

## GameDistribution
- Upload bubble-aim-gd.zip (contains index.html only), 100% width/height,
  leave SDK integration as-is (loader is domain-guarded).

## itch.io
- Upload bubble-aim-itch.zip, mark "This file is playable in browser",
  entry file: index.html, viewport 420x760, kind: html
- Pricing: $0 (donations optional)
