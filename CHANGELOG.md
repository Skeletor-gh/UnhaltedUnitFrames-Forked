## V12.1.02-alpha
- Fixed LibSharedMedia "Attempt to register an invalid file" error on load (removed registration of a missing `Dragonflight_BG.tga` background).
- Updated TOC for retail 12.1.5 (`120105`).

## V12.1.0
- Add Party / Raid Frames.
- Add Dedicated Augmentation Raid Frames.
  - Define rendered frames by Unit Name.
  - All Settings from Raid Frames are supported yet separated.
- Indicators:
  - Added: Ready Check.
  - Added: Resurrect.
  - Added: Threat.
  - Added: Phase.
  - Added: Role.
  - Added: Summon.
  - Fixed: Highlight / Target Overlays breaking when making changes.
- Tags
  - Healer Mana & Healer Mana with Sign.
  - `perhp` tag has been redefined to support statuses.
  - Move to localised `DEAD`.
- Power Bar has `Only Show Healer Mana` option.
- Test Environment Rework.
- Dead & Offline Backdrop Colour.
- Heal Absorbs will reverse grow when selecting `Attach to Missing Health`.
- Added `Unhalted Unit Frames` to Main Menu.
- Added `Interrupt on Cooldown` Colour for Cast Bars.