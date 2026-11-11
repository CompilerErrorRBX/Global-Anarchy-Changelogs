# 📑 Changelog 11/08/2026 - 11/xx/2026

## 🟢 Status `Unreleased`

## 💬 Patch Notes
Patch notes.
________

## 📢 Features and Improvements

### ✅ `Feature` Take control of bots
- While spectating a bot on your team in Headquarters or Ranked, press E (X on controller) to take control of it.
- You become the bot: its name, look, class, weapons, ammo, health and scorestreaks.
- Your kills, deaths, score and medals count for the bot on the killfeed and scoreboard.
- Your own XP and challenge progress still count.

### ✅ `Feature` Final Kill Cam
- When a match ends, everyone watches a replay of the last kill from the killer's view, with slow motion on the kill.
- In Ranked, every round also ends with a replay of the round winning kill.

### ✅ `Feature` Search and Destroy
- Attackers pick up the bomb and plant it at site A or B. Defenders stop them or defuse it.
- One life per round, sides swap every round, first to 6 rounds wins.

### ✅ `Feature` Team pings
- Press Left Alt (D-pad Down on controller) to ping the spot you are aiming at.
- Your team sees a marker there with its distance, and on the minimap, for a few seconds.
- You can have one ping at a time. Left Alt no longer does free look.

### 🔼 `Improvement` Add announcer sounds to Hardpoint

### 🔼 `Improvement` Add announcer sounds to 1v1s and 2v2s

### 🔼 `Improvement` New team health display in 1v1s and 2v2s
- Every player's headshot now shows at the top of the screen, greyed out with an X once they are dead.
- Each team has one health bar under its headshots, replacing the health bars on the sides of the screen.

### 🔼 `Improvement` Map models and sounds now load during the loading screen
- Maps and sounds are ready when you join, so there is less pop in and fewer sounds missing the first time they play.
- The loading screen may take a little longer. You can still skip it.

________

## ⚖️ Changes

### ❗ `Change` Nerfed AA12
- Reduced hipfire accuracy
- Slightly increased dropoff

### ❗ `Change` Rebalanced MP7
- Damage reduced from 30 to 28
- Max range reduced from 700 to 650

### ❗ `Change` Pressing sprint or crouch to cancel a slide now applies an immediate velocity nerf
________

## 🐛 Bugfixes
- Fixed a bug where releasing the hold crouch key (Ctrl) during a slide ended the slide early and left you stuck crouched. The slide now continues until it ends or you cancel it, and you stand back up afterwards unless you are still holding the key
- Fixed a bug where spectating someone using a knife, grenade, claymore, throwing knife or scorestreak radio did not show their swing, throw or call-in animation in first person
- Fixed a bug where teammates and teammate bots could still block and push each other. You now pass through your team and only collide with enemies
