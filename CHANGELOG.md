# Vestara client patch history

Published player-client updates, newest version first. Dates are the UTC release-note dates.

<!-- vestara-client-history:v1; maintained by the publisher -->

<!-- vestara-client:0.2.1 -->
<!-- source-archive-sha256:1448096cdbdf05e23077ac9ed28b813b11552ae6088966d1bdd27856a058680d -->
<!-- source-content-sha256-v1:093c3a2a749d347c94ce9804569c701cda700e0bd833d934487439386fbf086c -->
## 0.2.1 — 2026-10-24

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.2.1)

### Added

- The Vestara look: restyled windows, tabs, buttons and fonts across the client, and a new window icon.
- A new login screen with background art, campfire music, embers and falling leaves.
- The full world map is now on your minimap from your first login. Everything you have explored yourself and your map marks are kept.

### Changed

- Hotkeys are now per character. Each character keeps its own hotkeys, action bars and Ctrl+K hotkeys, loaded automatically when it logs in. A new character starts from its vocation's preset. You can turn this off in Options, Controls, under Per-Character Hotkeys.

### Fixed

- Hotkeys no longer reset after logging out and closing the client.
- Action bar changes are saved right away, so they survive a crash or a forced close.
- Closing the client no longer runs into an error in the market window.

<!-- /vestara-client:0.2.1 -->

<!-- vestara-client:0.2.0 -->
<!-- source-archive-sha256:a6dd89830d774f8d7a560d25cd575e7d5ab20bcc4559a19ce6c38049f47454dd -->
<!-- source-content-sha256-v1:97bf983623162f06240b487acb87a39adaff539eff56ceec9099b1e0fdf5f5a3 -->
## 0.2.0 — 2026-10-24

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.2.0)

### Added

- Masteries window, opened from its own toolbar button: talent trees for Knights, Sorcerers, Paladins and Druids, with attunements, spell changes and capstones.
- Stack display: mastery stacks and effects show as small icons above creatures and players. Choose Mine, Everyone or Off for each kind in its settings.
- New mastery spells in the spell list: Arrow Volley, Wolf Form, Bear Form, Beast Strike, Beast Cry, Blizzard, Overgrowth and Primal Avatar.
- New looks: the Druid's spirit wolf, grove bear and primal avatar shapes, the corrupted Avatar of Light, and sanctified and unholy ground.

### Changed

- Item tooltips show the affix tier in the item title.
- Spell icons in round talent-tree slots are drawn round.

### Fixed

- Hotkeys are saved reliably when you edit them, go offline or close the client.
- Item tooltips no longer show a forge tier as affix tier 1.

<!-- /vestara-client:0.2.0 -->

<!-- vestara-client:0.1.5 -->
<!-- source-archive-sha256:552092e8662f0e01d901bedefda24cfbbdad18fb244fb2c22ef7abf2833947e7 -->
<!-- source-content-sha256-v1:b2562b69ba20655471fbfc4973553e8e9f7f89853eba70fbb61967c406d2f745 -->
## 0.1.5 — 2026-10-22

Client 0.1.5 - Client version in the window title

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.1.5)

### Fixed

- Restored the published client version in the window title, for example Vestara Client 0.1.5.
- Future Publisher releases automatically display the version entered during publishing.

### Preserved

- The title is set by the generated startup wrapper; the supplied original startup and all other retained source files remain unchanged.
- Uses the same supplied build as 0.1.4, with the same minimal privacy and launcher-compatibility exclusions. No gameplay modules, bot features, connection settings or developer controls are changed.
- Launcher-managed settings, hotkeys and maps remain separate from client release files.

<!-- /vestara-client:0.1.5 -->

<!-- vestara-client:0.1.4 -->
<!-- source-archive-sha256:552092e8662f0e01d901bedefda24cfbbdad18fb244fb2c22ef7abf2833947e7 -->
<!-- source-content-sha256-v1:b2562b69ba20655471fbfc4973553e8e9f7f89853eba70fbb61967c406d2f745 -->
## 0.1.4 — 2026-10-22

Client 0.1.4 - Preserve the supplied client

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.1.4)

### Fixed

- Replaced broad client pruning with minimal exclusions to prevent packaging from removing supplied client features and supporting files.
- Preserved the original startup script, module loading order, bot/mod files, connection settings, complete assets, DLLs and runtime extras such as bin contents.
- Kept launcher-managed player settings and logs separate through a small startup bootstrap, while retaining the original startup script unchanged.

### Changed

- Only explicit privacy exclusions and compatibility constraints of existing launchers are applied. Every excluded or generated file is recorded during preparation.
- This release repackages the same supplied source build as 0.1.3 with the new preservation rules; it does not claim a new executable build or additional server fixes.
- The more complete client package increases the first-install download size. Existing compatible launchers continue to use changed-file downloads where possible.
- Players can open Vestara Launcher, check for updates and choose Update client. Their launcher-managed settings, hotkeys and maps remain separate from client release files.

<!-- /vestara-client:0.1.4 -->

<!-- vestara-client:0.1.3 -->
<!-- source-archive-sha256:552092e8662f0e01d901bedefda24cfbbdad18fb244fb2c22ef7abf2833947e7 -->
<!-- source-content-sha256-v1:b2562b69ba20655471fbfc4973553e8e9f7f89853eba70fbb61967c406d2f745 -->
## 0.1.3 — 2026-10-22

Client 0.1.3 - Restore packaged client features

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.1.3)

### Fixed

- Restored the Bot button, cave bot and full vBot scripts that were incorrectly excluded during player-client packaging.
- Restored the supplied mod profiles, text editor, buttons, item selector and task module files.
- Restored the final startup loading stage for higher-priority game modules, including attributes, proficiency, item lock, health circle and wheel.
- Kept the bundled minimap initialization and separate player settings location without enabling bot restrictions.

### Changed

- Publishing now stops for unreviewed runtime modules or missing module dependencies/scripts instead of silently dropping them.
- This release corrects packaging of the existing 0.1.2 source build. It preserves its executable and game content; no new server build is required.

<!-- /vestara-client:0.1.3 -->

<!-- vestara-client:0.1.2 -->
<!-- source-archive-sha256:552092e8662f0e01d901bedefda24cfbbdad18fb244fb2c22ef7abf2833947e7 -->
<!-- source-content-sha256-v1:b2562b69ba20655471fbfc4973553e8e9f7f89853eba70fbb61967c406d2f745 -->
## 0.1.2 — 2026-10-22

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.1.2)

### Changed

- Item Progression and Affix Balance
- Added a full Item Power Tier system (T1-T10) to spread affix power across gear progression.
- Affix roll strength now scales primarily with item power tier, so low-tier/common gear no longer rolls endgame-level values as often.
- Added per-tier limits for how many affix lines can roll on an item.
- Added item-power gating for high-impact affixes (such as cleave/ricochet/spell-echo/attack-speed), so they unlock later in progression.
- Added tier overrides for key endgame brackets:
- Moonsilver weapons: Tier 9
- Stellar Moonsilver weapons: Tier 10
- Item look text now shows tier in the name line (example: Leather Armor T1).
- Cleave can now roll on weapons and shields above a certain tier.
- Cleave cap increased by 2 so players can now cleave in a U shape around their character with maximized cleave. (Knight and Monk)
- Existing Item Migration (Non-Destructive)
- Ran a full item sweep across player-owned inventories (including offline data paths) to apply new affix metadata.
- Legacy high-roll lines from earlier balancing eras were preserved (not deleted but nerfed), and marked as legacy where above new caps.
- Equipment Requirements and UX
- Removed level-based equip/use gating for items.
- Level requirement text was removed from item descriptions and market detail UI fields to avoid confusion.
- Combat and System Hardening
- Cleave behavior was unified to prevent overlapping/duplicate processing paths.
- Affix-derived movement speed and capacity bonuses now use cache refreshes for better runtime performance.
- Catch-up XP was implemented. Players will receive scaling XP bonuses depending on how far away they are from the highest level on the server up to 70% of their level.
- Catch-up XP refresh logic was moved away from repeated DB querying in hot XP flow.
- Stamina was disabled. To compensate for the removal of happy hour experience we've implemented catch-up bonuses. Additionally, global XP tokens are increased by 10% overall.
- Elite/Mythic Currency Changes
- Rebalanced elite/mythic bonus token drops:
- Gold Tokens: now drop at 50% chance, with 1-2 count.
- Silver Tokens: added at 50% chance, with 1-2 count.
- Gold and silver token drops are non-exclusive (both can drop on the same kill).
- Gold coins, platinum coins and crystal coins dropped by elite and mythic monsters were reduced significantly -- currently monitoring whether additional reduction is required.
- Rechargeable Ring/Amulet Affix Preservation
- Fixed recharge paths that could wipe affixes when converting between uncharged/charged item IDs.
- Recharging now transforms the same item instance for supported silver-token recharge gear, preserving rolled affixes/custom item state.
- Applies to rechargeable sets handled via:
- Cledwyn enchant flow
- !refill talkaction
- Final Notes:
- You will find your gear significantly weaker than before. This is intended. In the current meta there was far too little difference between having low level items VS high level items. To compensate for this fact level requirements are no longer, it now pays to take risks and hunt strong monsters for high level items.

<!-- /vestara-client:0.1.2 -->

<!-- vestara-client:0.1.1 -->
<!-- source-archive-sha256:0af0279089c2f2ad95e961848a3d489e03c66adb5aaf793564303ca2129b7ac2 -->
<!-- source-content-sha256-v1:2cbd5726ce118479e4ed4a0e3d89805f86c870b1ac187a60e41edb650f013fc5 -->
## 0.1.1 — 2026-10-22

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.1.1)

### Changed

- Updated player client with loot rarity
- Some minor fixes and gold change fixes

<!-- /vestara-client:0.1.1 -->

<!-- vestara-client:0.1.0 -->
<!-- source-archive-sha256:0af0279089c2f2ad95e961848a3d489e03c66adb5aaf793564303ca2129b7ac2 -->
<!-- source-content-sha256-v1:2cbd5726ce118479e4ed4a0e3d89805f86c870b1ac187a60e41edb650f013fc5 -->
## 0.1.0 — 2026-10-21

First launcher player release

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.1.0)

### Added

- Install, update and repair the Vestara client through the launcher.
- Includes the current server connection settings, game assets and sounds.

### Changed

- Player settings are stored separately from the development client.

<!-- /vestara-client:0.1.0 -->
