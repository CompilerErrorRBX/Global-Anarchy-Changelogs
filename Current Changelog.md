# 📑 Changelog 10/17/2026 - 10/22/2026

## 🟢 Status `Unreleased`

## 💬 Patch Notes
We've rolled back server-authoritative movement while we keep working on it behind the scenes. Most of last update's improvements are still here, plus a brand new Play page, smoother animations and a pile of bug fixes.
________

## 📢 Features and Improvements

### ❗ `Change` Server Authority Rolled Back
- Movement is back to the previous system while we iron out issues with server-authoritative movement.
- Improvements made alongside it, like better performance and the controller auto-sprint fix, have been kept.

### ✅ `Feature` New Play Page
- Choosing how your squad plays now uses a new card-based Play page.
- Casual is selected by default on public servers.
- 🎯 Training Mission is coming soon!

### 🔼 `Improvement` Character Animations
- Other players and bots no longer get stuck in the falling pose after landing on a slope.
- A player's held weapon pose now updates correctly when they swap to fists from the inventory.
- Climbing down a ladder no longer freezes the climbing animation.

### 🔼 `Improvement` Performance
- Characters on screen are now moved more efficiently, reducing physics work with many players nearby.

### 🔼 `Improvement` Controller
- Play page cards now show the standard controller highlight, like every other button.
- Auto-sprint now waits a moment after you fire before kicking back in, so it no longer fights semi-auto shots.

________

## 🐛 Bugfixes
- Fixed a bug where bullets could sometimes pass through glass instead of breaking it.
- Fixed a bug where you could keep firing "phantom" shots that did nothing while your magazine was empty during a reload.
