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

### ✅ `Feature` Gamemode: Search and Destroy
- Attackers pick up the bomb and plant it at site A or B. Defenders stop them or defuse it.
- One life per round, sides swap every round, first to 6 rounds wins.

### ✅ `Feature` Team pings
- Press Left Alt (D-pad Down on controller) to ping the spot you are aiming at.
- Your team sees a marker there with its distance, and on the minimap, for a few seconds.

### ✅ `Feature` 1v1s and 2v2s in private servers
- Private servers have a new Duels section in the game mode list with 1v1 and 2v2.
- Duels play on Shipment, first to 6 rounds wins.

### ✅ `Feature` Unlocks & XP page at intermission
- Intermission now has two pages: Map Vote and Unlocks & XP. Switch with Q and E (LB and RB on controller).
- See the XP and gold you earned, your medals, your level progress and your stats from the match.
- See what you unlock next and the goals you are closest to finishing.
- Press Z or X (R3 on controller) to switch between your level and your best weapon of the match.
- The match stats popup no longer opens at intermission. Its stats are on the new page.

### 🔼 `Improvement` Private servers can turn off health regen
- New Health Regen option in the private server rules.

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

### ❗ `Change` Buffed PKM
- Recoil reduced by 16.7%

### ❗ `Change` Pressing sprint or crouch to cancel a slide now applies an immediate velocity nerf

### ❗ `Change` Ranked matches no longer send you back when they end
- When a Ranked match ends you stay on the results page.
- Press Play Again to vote for a rematch. If every player agrees, the same players play a new match.
- Or press Menu to go to the title screen and pick something else to play.
________

## 🐛 Bugfixes
- Fixed a bug where releasing the hold crouch key (Ctrl) during a slide ended the slide early and left you stuck crouched. The slide now continues until it ends or you cancel it, and you stand back up afterwards unless you are still holding the key
- Fixed a bug where spectating someone using a knife, grenade, claymore, throwing knife or scorestreak radio did not show their swing, throw or call-in animation in first person
- Fixed a bug where teammates and teammate bots could still block and push each other. You now pass through your team and only collide with enemies
- Fixed a bug where you could start throwing a grenade during the countdown before a round, while you are frozen in place
- Fixed a bug where Halloween bundles kept showing in the shop and on the map vote screen after the Halloween event ended, one of them with the wrong picture
