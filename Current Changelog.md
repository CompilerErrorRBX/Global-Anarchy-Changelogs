# 📑 Changelog 08/14/2026 - 08/xx/2026

## 🟢 Status `Unreleased`

## 💬 Patch Notes
________

## 📢 Features and Improvements

### ✅ `Feature` Add "Animation Quality" setting
- This controls the map amount of player animation updates per frame.
- Default is Low.
  
### ✅ `Feature` Add Fly Swatter medal
- When you destroy an Attack Helicopter, you are awarded 500 xp.

### 🔼 `Improvement` Added weapon inspect animations

### 🔼 `Improvement` Added knife sheath/unsheath sounds

### 🔼 `Improvement` Double-clicking menu items in the armory now equips them

### 🔼 `Improvement` Updated Domination spawn logic

### 🔼 `Improvement` When using a predator missile dead players will no longer display as a target

### 🔼 `Improvement` Players now properly display as teammates when spectating them

### 🔼 `Improvement` Minimap now properly displays when spectating

### 🔼 `Improvement` Flashbang and concussion effects are now removed upon death

### 🔼 `Improvement` Settings UI and Private Match UI
- Improved inconsistent button alignment.
- Improved inconsistent description text sizes.
- The correct font is now used.
  
### 🔼 `Improvement` Settings UI can now be opened while in game
- Added the settings button to the loadout selection UI.

### 🔼 `Improvement` Player nameplates now follow your visual character
- Before they followed your server-sided character, which causes some odd visual desyncs.

### 🔼 `Improvement` "Back" button in the menu now acts as a back button
- Previously it would take you back to a hardcoded page
- Now there is an actual "menu stack" so you can open multiple menus and properly navigate them backwards

### 💄 `Cosmetic` Cosmetic

________

## ⚖️ Changes

### ❗ `Change` Buffed Ninja perk
- Entities that can "see" you now have an increased delay.
- Right now this affects Claymores and Attack Helicopters.

### ❗ `Change` Buffed all daily challenge rewards

### ❗ `Change` Nerfed Extra Pin perk
- Now only gives an extra grenade, excluding Claymores and Throwing Knives.

### ❗ `Change` Reduced the volume of weapon aim sounds by 20%
  
________

## 🐛 Bugfixes
- Fixed a bug where recoil would not reset properly after shooting.
- Fixed a bug where you cannot click the "Purchase" button on a booster in the Inventory UI.
- Fixed a bug where if you take out the same weapon twice, it breaks weapon rendering.
- Fixed a bug where selecting scorestreaks in Armory Selection UI would not visually update upon equipping.
- Fixed a bug where the knife sound was audible from too far away.
- Fixed a bug where clicking "back" in the weapon configuration UI would cause the armory selection UI to malfunction.
- Fixed a bug where the Attack Helicopter would not give radio notifications.
- (Hopefully) Fixed a bug where you would respawn with a sprinting animation but be moving at your walk-speed.
- (Hopefully) Fixed a bug where you would respawn holding a secondary weapon.
