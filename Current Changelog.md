# 📑 Changelog 11/13/2026 - 11/xx/2026

## 🟢 Status `Unreleased`

## 💬 Patch Notes
Patch notes.
________

## 📢 Features and Improvements

### ✅ `Feature` Feature

### ✅ `Feature` Directional death animations
- Players now fall away from where the killing shot came from: front, back, left or right.
- Headshots keep their own death animations.
- Explosions have their own death animations.

### ✅ `Feature` Soldier Shadows setting
- New Graphics setting that lets soldiers cast shadows. Off by default.

### ✅ `Feature` Private Server Time Limit and Score Limit
- Private Servers can now set their own Time Limit and Score Limit.
- Set either to Unlimited, or set both for a match that never ends.
- Available in Team Deathmatch, Free For All, Domination, Headquarters, Hardpoint, Kill Confirmed and One in the Chamber. Gun Game and Infection have Time Limit only.
- Matches with custom limits pay match rewards for the time actually played.

### 🔼 `Improvement` Skip the loading screen on controller
- Press B to skip the loading screen once the Skip button shows up.

### 🔼 `Improvement` Kill cam shows flashes and stuns
- If the killer was flashed or stunned, the kill cam now shows the white flash and screen sway they saw.

### ✅ `Feature` AFK players are removed from matches
- Players who stop playing for 90 seconds in a casual match are sent back to the title screen, and a bot takes their place.
- In Competitive, AFK players are disconnected from the match and can reconnect from the Play menu.

### ✅ `Feature` Key bindings
- Keyboard and mouse players can now rebind their keys in Settings, under Controls.
- Controller players can rebind their buttons there too.
- Bindings are saved to your account, and any binding can be reset to its default.

### ✅ `Feature` Custom mobile HUD layout
- Mobile players can now move and resize their on-screen buttons and HUD from Settings, under Controls.
- Controls snap into line with each other while you drag them.
- Your layout is saved to your account.

### 💄 `Cosmetic` New Settings menu
- The Settings menu has a new look that matches the Armory, Shop and Profile.
- Settings are grouped into sections, sliders show their value, and every setting can be reset to its default.

________

## ⚖️ Changes

### ❗ `Change` Change

### ❗ `Change` Bots switch weapons like players
- Bots now put their gun away before taking out another one.
- Bots now wait as long as players do before firing a weapon they just took out.

### ❗ `Change` PKM recoil reduced by 20%

### ❗ `Change` Shorter Search and Destroy pregame
- Outside Ranked, the pregame now ends as soon as everyone who has deployed has picked a class. Players still on the menu no longer hold the match back.
________

## 🐛 Bugfixes
- Fixed a bug where the class select screen closed when the kill cam played between rounds in Ranked and Search and Destroy.
- Fixed a bug where the "Your class will change next time you spawn" message could get stuck on screen.
- Fixed a bug where claymore kills did not show a kill cam.
- Fixed a bug where the camera snapped when you started or stopped sprinting with a pistol or fists, most noticeably when aiming down sights right after a sprint.
- Fixed a bug where your own gunshots could sound like they came from the wrong side in first person, most noticeable on headsets with directional audio.
- Fixed a bug where players could spend the pregame stuck in the spawn box instead of on the map.
