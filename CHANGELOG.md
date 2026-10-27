# Vestara client patch history

Published player-client updates, newest version first. Dates are the UTC release-note dates.

<!-- vestara-client-history:v1; maintained by the publisher -->

<!-- vestara-client:0.6.2 -->
<!-- source-archive-sha256:e3144fc3dfff6a920886014d13ff9d94df8be636ae4fd1a9f453cff5a7872dbd -->
<!-- source-content-sha256-v1:95d2d3ef06b285068793a880852962c1a8780b8817e7addfd9643d10f8c8310e -->
## 0.6.2 — 2026-10-27

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.6.2)

### Changed

- The game map now also draws the ring of tiles just outside your screen, so the edges no longer show artefacts while you walk.
- The launcher's sound is now instant to mute, fades out when you minimise the launcher or press Play, and fades back in when you return to it, even while an update is downloading.
- The launcher no longer plays a sound when you press Play.
- Elite and Mythic monsters drop rare items more often: only items rarer than 1% are boosted, the rarest up to 3.5x from Elites and 8x from Mythics. Common loot is unchanged.
- Special backpacks drop more often: 10% from Mythic monsters (was 2%), and Elite monsters can now drop them too (1%).

### Fixed

- The chat cursor no longer jumps back to the start of the line after you type a space.
- Runes (and any other object) can be bound to a Multi-Action slot again, whatever the button already shows.
- Desktop and Start menu shortcuts now show the new Vestara icon after the launcher updates, without reinstalling.

<!-- /vestara-client:0.6.2 -->

<!-- vestara-client:0.6.1 -->
<!-- source-archive-sha256:b06ecca1eeae74db52aae0db74a20396aabc8d4ef194eaf95c6e33cb4748667e -->
<!-- source-content-sha256-v1:af7efc6ed34eb7a836122f56872e94d481f39e5dc34121cfdcadf9fc20e548a3 -->
## 0.6.1 — 2026-10-27

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.6.1)

### Added

- New Vestara logo: the pixel-art stone gate, now on the launcher, the game client and the installer.
- A redesigned Setup wizard for new players. Download it from https://github.com/Vick-Tibia/vestara-downloads/releases/latest/download/Vestara-Setup.exe
- Store: choose how many to buy. Item offers such as boost tokens and exercise weapons have an Amount box in the purchase confirmation (up to 100 at once).

### Changed

- New experience rates, as voted by players: 5x up to level 100, 4x up to level 250, 3x up to level 500 and 2x after that.
- All weapon skills (fist, club, sword, axe, distance and shielding) and magic level now train at 2x speed.
- Catch-up XP and the extra low-level XP bonus have been removed, so the rates above are what you get. Boosted creatures, prey and XP boosts still apply on top.
- The launcher now plays the quiet sounds of a campfire in the night forest, and the login screen plays Campfire Folk.
- Raid rewards reset at the daily server save instead of 10:00.
- The store's "Most Popular First" sort now lists the offers players buy most at the top.

### Fixed

- The launcher no longer fails to open with "Invalid launcher slot." after updating. If yours still won't open, download and run Vestara-Setup.exe from the link above: it installs over your launcher and keeps your game, settings and hotkeys.
- Shields, spellbooks and two-handed weapons (bows, crossbows, katars) now count towards their set bonus, for example the Crown shield in the Crown Oath set.
- Clicking "Weapons: All" in the Cyclopedia no longer freezes the client or disconnects you.
- Sorting the battle list by health no longer leaves dead creatures behind in the list.
- The store's sort order works, and "Newest First" is spelled correctly.
- The Quest Tracker no longer opens by itself on every login, and closed analyser windows stay closed, even after the client crashed.
- Hovering over the Reward Wall no longer leaves old text overlapping the new text.
- The stance highlight on your action bar keeps animating while the stance is active.

<!-- /vestara-client:0.6.1 -->

<!-- vestara-client:0.6.0 -->
<!-- source-archive-sha256:b5180756c87fd1980aa8c68a2a3d6bc7fe154b38cd34e26d7b0cbf24b2e1be1e -->
<!-- source-content-sha256-v1:56363fa2fe71686f12759af569b61fb867b89661faee369de7275a54b94bc899 -->
## 0.6.0 — 2026-10-27

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.6.0)

### Added

- A new look for the launcher: the campfire glade comes to life with drifting embers, fireflies and soft campfire music.
- Music controls in the launcher: click the speaker to mute, hover over it to set the volume.
- The login screen now shows your party gathered at the campfire, with new upbeat music, March of the Brave.

### Changed

- Music in the launcher and on the login screen now starts at 50% volume. If you never changed your music volume, it is lowered to 50% once.
- The launcher's What's new now shows the latest update, including server updates.

### Fixed

- The launcher shows your client straight away after an update instead of appearing empty while old versions are cleaned up.

<!-- /vestara-client:0.6.0 -->

<!-- vestara-client:0.4.2 -->
<!-- source-archive-sha256:2c4395cac0ec7a876d79386c9860ee64e6413072723201f13988c207fc70a8a1 -->
<!-- source-content-sha256-v1:465ca0e9fe142ac67fed2f7ac6dbf86d6d87c92ad329ac3f61a7350911b1da00 -->
## 0.4.2 — 2026-10-26

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.4.2)

### Fixed

- The game no longer opens a black console window next to the client when it starts.

<!-- /vestara-client:0.4.2 -->

<!-- vestara-client:0.4.0 -->
<!-- source-archive-sha256:ecdd68c49998da151cf11aa921dba53774242bdcb384476665d7562a515d549a -->
<!-- source-content-sha256-v1:c4464c8a5b9940e0ab3778e811fdcd7c38f9b89c70128838b920be22e3d1125f -->
## 0.4.0 — 2026-10-26

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.4.0)

### Added

- 40 new outfits and the winged Duskwing outfit, available in the store.
- The store now also sells mounts, prey packs and multitools.
- Yasir buys the radiant and moonspawn creature drops that no other merchant takes, including moonspawn tentacles and headpieces.

### Changed

- Store offers show the real item pictures, and buying is faster.
- Imported outfits are now store outfits instead of being unlocked for every player.

### Fixed

- Opening item offers in the store (such as Consumables and Boosts) no longer crashes the client, the store no longer locks up after opening, and the XP boost opens the right page.
- The Goblin King is visible again.
- The Goblin King doll and the pocket portal can no longer be worn as legs, and other custom items now use the right equipment slot, stacking and container behaviour.
- Radiant and moonspawn creatures drop loot again.
- NPC replies that span several lines are no longer lost, and Cledwyn's dialogue works again.
- NPC token shops show prices and your balance in tokens instead of gold.
- Item tooltip stars no longer appear in other tooltips.
- Front Sweep's Wheel of Destiny augment now deals damage in its larger area.

<!-- /vestara-client:0.4.0 -->

<!-- vestara-client:0.3.0 -->
<!-- source-archive-sha256:99b8fea7fbc7c90340cf112828b2ac2416c47223845b011a633a71d1f892e7bb -->
<!-- source-content-sha256-v1:96a2870500357ddf8dfe7286031ceff49783629fd792eab512aee7cdd585b326 -->
## 0.3.0 — 2026-10-25

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.3.0)

### Changed

- Dungeons & Raids: a new window to queue with your party, a ready check before entering, and a reworked Ironjaw raid with new rewards.
- Item modification window for affix stones, with a preview of what the stone can roll before you confirm.
- Chat item links: Alt+click an item in your inventory, a backpack or the trade window to link it in chat. Hover the link to see the item's tooltip.
- Inspect other players to see their equipment and skills.
- Item star ratings from 1 to 10, shown with the item's rarity.
- Adventurer's menu: the compass button next to Options lists every window by category. Use the star to choose which shortcuts stay on your sidebar.
- The sidebar shortcut buttons are now grouped by category.
- Active stances are highlighted on your action bars.
- The new retail spells, with their own icons, learned automatically or from spell trainers.
- Superior and distilled mana potions and five storm arrows, sold by the usual potion and arrow merchants.
- NPC shops show item stats when you hover an item.
- Vocation rebalance following retail 15.25 and 15.30: Wheel of Destiny perks, spell values and augments for every vocation. Masteries were adjusted to match.
- Weapon proficiencies use the retail 15.33 values.
- Affixes only roll stats the wearer can use, wands and rods get caster lines, and percent health/mana, attack speed and spell echo have caps. Existing items are re-rated automatically.
- The skills window shows the maximum health and mana from your gear and your spell echo. Affix amounts are shown in their real units.
- The built-in bot now offers healing and potion support only. Cave, target and attack automation are no longer available.

### Fixed

- Your attack square stays on the target after the first hit.
- Prey, bestiary, kill tracker and analyser windows reopen when you log in.
- Bag windows keep their size when the server refreshes them.
- The minimap no longer snaps back after you drag it.
- Toggling a stance repeatedly no longer crashes the client.
- Classic controls: left+right click to look works reliably.
- Ranged weapon tooltips colour only the attack number.
- Daily reward item weight is shown in oz.
- Global boost icons are centred on the game view.
- Quick loot finds the corpse more reliably, and exercise weapons find the dummy on the tile you click.
- The djinn fortress entrance doors open for everyone.

<!-- /vestara-client:0.3.0 -->

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
