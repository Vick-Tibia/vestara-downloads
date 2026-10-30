# Vestara client patch history

Published player-client updates, newest version first. Dates are the UTC release-note dates.

<!-- vestara-client-history:v1; maintained by the publisher -->

<!-- vestara-client:0.8.1 -->
<!-- source-archive-sha256:ee32951966c10148933ce72429bb81c7cc4d29203e9d4a22bf111c8f6dc3bee4 -->
<!-- source-content-sha256-v1:590da2764ed3aec9410d054e901e4ea9ca0b2fba55fefca0ee933fe952f9dfbe -->
## 0.8.1 — 2026-10-30

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.8.1)

### Added

- Blood Frenzy: Hemorrhage. Your melee hits deal 3/4/5% more for every bleed stack you have on the target. While frenzied your outfit turns crimson, Bloodlust pulses as it fills, and Rupture is easier to see.
- Eldritch Knight: the Final Harvest now has its own icon while the Harbinger walks, so your Souls count no longer seems to reset.

### Changed

- Knight masteries have been rebalanced. All Knight mastery points are refunded once: open the Masteries window to spend them again.
- Battle arts (Blood Burst, Cleave, Soul Harvest): master one, and take a second at rank 1 if you like. You can no longer take all three.
- Mastery area damage is smaller across the board (Cleave, Blood Burst, Soul Nova, Bloodletter, Gathering Storm burst), so packs no longer melt instantly. Each capstone now makes its own path's area damage stronger: Blood Frenzy +10%, Windfury +25%, Eldritch Knight +40%.
- Capstones cost 4/7/10 points instead of 5/9/13, and each has a clear job: Blood Frenzy for bosses, Windfury for small groups, Eldritch Knight for big pulls.
- Twin Cut goes off more often with smaller cuts, and Gathering Storm stacks make cuts more likely. Twin Cut and Windfury never chain at the same time, and extra swings no longer sweep Cleave (mastery or gear) unless you have Windfury.
- Windfury: fewer but heavier swings (up to 120% damage), at most 6 per chain, with its own whirlwind animation and a bigger Eye of the Gale.
- Eldritch Knight: Reaper's Arc drains life and heals you for a quarter of it. Reaper's Toll and Withering Edge now poison, and Blight is poison on the ground. Soul Nova and Final Harvest stay death damage.
- Eldritch Knight: Soul Nova no longer spends your Souls, so only the Harbinger does. Reaping Sweep now hits harder for every Soul you hold instead of spending them.
- Gale Slash is now a whirlwind around you (every tile next to you, the ring beyond at half damage), and its vortex follows you and pulls monsters in towards you.

### Fixed

- Immersive layout: the top and bottom rows of the map are no longer cut off, so you see as much of the map vertically as in the classic layout (and more to the sides).
- Eldritch Knight: Reaping Sweep, Reaper's Arc and the Harbinger no longer leave slash animations on the floor that never go away and pile up the longer you fight.

<!-- /vestara-client:0.8.1 -->

<!-- vestara-client:0.8.0 -->
<!-- source-archive-sha256:51a69006284a866b0d75101a714dc78226e8b736c0152e520d07c6a7cf8ba1ab -->
<!-- source-content-sha256-v1:4922d7e6fbaca2ca962faa7b1d84b765740c015b9c525907b362ffc255245767 -->
## 0.8.0 — 2026-10-30

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.8.0)

### Added

- Store: floors, carpets, furniture, potions, runes, exercise weapons, casks, kegs and boost tokens now have quick 1 / 5 / 10 / 25 buttons next to the amount box under the price, so you can buy several at once (up to 100) and see the total before you buy.
- Players and monsters now show small icons when they are hasted, magic shielded, strengthened or in a combat stance like Blood Rage, Protector or Sharpshooter. You can turn them off with "Show buff icons over creatures" in Options \> Interface.

### Changed

- Affix stones (rerolls and the other modification stones) can now be used on backpacks, necklaces and rings.
- Equipment you clean with a rust remover now rolls rarity and affixes, like equipment dropped by monsters.
- Equipment bought from the gold token and silver token traders now rolls rarity and affixes, like equipment dropped by monsters.
- On elemental weapons, a +attack affix now adds to the weapon's elemental damage instead of its physical attack (for example 5 attack + 48 fire with +12 attack becomes 5 attack + 60 fire).
- Elite and mythic monsters now always give forge dust when killed, like influenced and fiendish monsters: elite as much as an influenced monster, mythic as much as a fiendish one.
- Storm arrows (shatterstorm, firestorm, terrastorm, froststorm, thunderstorm) no longer hit an area around the target. Instead each shot ricochets to 2 more enemies, and their attack is raised: 45 for the elemental arrows, 40 for shatterstorm.
- Crystalline arrows: attack lowered from 65 to 55.
- Sorcerer fire masteries toned down: Kindle burns for 15/20/25% of the hit (was 20/30/40%), Pyromancy rank 2 stacks burns to 4 (was 5) and keeps cinders to 1 tile, and Combust adds 25% to detonated burns (was 50%).
- Knight masteries reworked. Your Knight mastery points have been refunded, so open the Masteries window to spend them again. The tree now has three paths (Blood, Tempest, Eldritch), each with its own way to hit groups of monsters, plus the Iron support column.
- Knight Blood path: bleeds burst onto nearby monsters when a bleeding monster dies (Blood Burst), Spinning Assault leaves a pool of blood, and Blood Frenzy now clearly shows when it starts and ends, heals you while it runs and ends in a bigger explosion.
- Knight Tempest path: Battle Rhythm gives Momentum, attack speed that stacks with every kill and lasts 12 seconds after your last one. New Gathering Storm builds up to a wind burst, new Gale Slash (Exori Min) leaves a whirlwind that drags monsters in, and Windfury's extra swings now also cut the monsters beside you.
- Knight Eldritch path: kills give you Souls. Soul Harvest turns them into a Soul Nova of death damage that leaves blighted ground (purple smoke) hurting monsters on it for 3 seconds, new Reaping Sweep (Exori) hooks monsters towards you, and Withering Edge adds death damage.
- Knight Eldritch capstone: the new Eldritch Knight replaces Oathkeeper: your swings reap a crescent of death damage, further with a two-handed weapon, and at 10 Souls you become the Harbinger, taking the form of a void-violet Grim Reaper that moves 10% faster and has 5% more health until it ends. Type !harbinger to switch its automatic start on or off. Eldritch Knights show their own title and icon when inspected and in party frames.
- Knight Iron column: Hold the Line makes you take less damage for every monster next to you, Retaliation strikes back at everything around you, Seismic Wave adds an Aftershock where it pulls monsters, and Shield Bounce now works without a shield and makes you tougher for every monster it hits.
- Knight weapon specialisations work with one- and two-handed weapons alike (one-handed a bit weaker) and each has its own way to hit groups. Swords: Twin Cut can chain and slashes nearby monsters. Axes: two-handed axes swing slower but harder, and Devastate can finish off weakened monsters. Clubs: every few hits a shockwave staggers the monsters around your target.
- Knight: Lacerate, Battle Rhythm and Cleave are a little weaker. Martial Focus, Berserker, Shield Wall, Rampage, Unbroken, Hemorrhage, Guarded Stance and Thorned Bulwark are gone, and the Knight's mastery spells now cost 15% less mana.
- Boss loot: the rare items from bosses with a reward chest drop much more often. A boss's rarest pieces (1% or less) now drop up to 10 times as often, so a solo kill gives one in roughly 1 of 10 kills instead of 1 in several hundred. Common boss loot is unchanged.
- The Bestiary creature page now shows two separate bars: Bestiary progress (stages and charm points) and XP Rewards (your next experience reward and your current XP bonus for that creature), each with a tooltip explaining it.
- Side panels now only change width while you hold Ctrl+Alt and drag their edge (Ctrl+Alt+double-click for the standard width), so they aren't resized by accident while you move bags and windows around. Hold Shift as well for any width.

### Fixed

- Prey bonuses now run out after their hunting time again, instead of lasting forever.
- You can no longer get stuck unable to move any items until you relog. Only the item open in the imbuement window (and the bag holding it) is locked while it is open.
- The stash now works whenever you stand at a depot, including right after logging in there or arriving by teleport.
- Paladin Sanctified Ground no longer stops you from looting bodies lying in it. The holy (or unholy) ground now shows as a pulsing effect instead.
- Sell All at an NPC now sells everything in one click instead of only the first item.
- An item's tooltip now shows a new or removed imbuement straight away, instead of only after relogging.
- Pressing Enter or Escape on the death window no longer risks freezing the client.
- Opening big item categories in the Cyclopedia (such as all weapons) no longer freezes the game.
- Client settings such as smart walk and your control scheme are now kept if the client crashes or you x-log.
- Moved or resized windows (skills, battle list and others) now keep their place after a client crash or x-log.
- Locking a window works again: locked windows and bags can no longer be moved or resized by accident, and stay locked after you log in again.
- Creatures you track in the bestiary or bosstiary tracker no longer disappear from the list at random.
- The global skill boost now shows its time left next to the other global boosts.
- Global XP, loot, skill and elite boosts are no longer lost when the server restarts.
- Party frames show each member's vocation icon again (a druid shows the leaf); their capstone still appears as the title under their name.
- Elemental weapons show their elemental damage in the item tooltip again (for example ATTACK 5 and FIRE 48).
- Item tooltips no longer call food, tools, potions and other ordinary items a "Weapon".
- Items linked in chat now show the same new-style tooltip as items in your backpack.
- Items you link in a private message now show their name in your own copy of the message, instead of "\[Item\]".
- Legendary items in the loot channel are shown in legendary gold, the same colour as their tooltip.
- The battle list no longer keeps showing monsters that are already gone while sorted by distance.
- Quest access announced in 0.6.3 now really works: quest-gated hunting grounds and boss routes open for your character the next time you log in. Quest rewards still have to be earned.
- Token traders show your token balance as tokens instead of gold.
- Pyromancy cinders no longer fly through walls or chain from kill to kill across a whole pack. They reach at most 4 nearby enemies in sight.
- Spinning Assault's bleeds no longer stop after the first tick when you don't have Lacerate.
- The classic layout shows the wider game view again (17 by 13 squares) instead of shrinking back to the old Tibia view after logging in. Monsters, spells and throws still use the classic range.
- The minimap no longer snaps back to your character during combat after you've moved it. It only recentres when you walk to another square.
- Runes can now really be put in a Multi-Action slot: the rune is added and the button keeps working. Before, adding a rune broke the whole Multi-Action button, and buttons broken this way work again after the update.
- The vocation icon at the end of the health bar (immersive layout) no longer turns into the last item you looked at.
- The rest of the interface no longer greys out while the supply stash is open, and the stash no longer pops back up after you close it right after withdrawing.
- The walking outfit at the top left of the character inspect window is a little smaller, so large outfits no longer stick out of their frame.
- The imbuement window now tells you why an imbuement couldn't be applied (for example missing items), instead of seemingly doing nothing.
- Bags that open again when you log in now come back in the same column, order and size you left them in, instead of wherever there was room.
- Windows you leave next to a side panel now move aside when you make the panel wider, instead of the panel and its windows ending up underneath them.
- Switching between your saved layouts (1-3) now also moves your windows (Skills, Battle List, bags...) to where you had them in that layout, and no longer stops half-way when the layouts have a different number of action bars.
- Monsters no longer respawn inside walls or rocks in hunting grounds whose spawn points were placed on them.
- If the game freezes and you close it, the launcher no longer refuses to start it again until you restart your PC: it offers to close the stuck game and start a new one.
- Dying and getting reconnected right away is safer: the death window no longer races the automatic reconnect, and the client is protected against the kind of endless loop that could freeze it after death.

<!-- /vestara-client:0.8.0 -->

<!-- vestara-client:0.7.0 -->
<!-- source-archive-sha256:5b4d27e2c91d37b64f360fc638927b1166eaac668c62c835e0296cd4b1a5f2c3 -->
<!-- source-content-sha256-v1:b7ab2bbdf7413b8835f6d56ac96b9bbd3c2feb20e3479816089da33199039383 -->
## 0.7.0 — 2026-10-29

Client 0.7.0

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.7.0)

### Added

- A new immersive layout: the game fills the whole window and shows more of the world, with health, mana and experience in a bar at the bottom and the chat and action bars over the game. Switch between it and the classic layout with Ctrl+. or the layout button next to Options.
- Edit layout (Ctrl+Shift+L): move and resize the health bar, chat, minimap, equipment, action bars and windows such as Skills or Battle List. Pieces snap neatly into place and never overlap. Save up to three layouts and set the size of the whole interface (handy on 4K screens).
- More action bars: up to three on each side of the screen and three rows at the bottom. The immersive layout keeps its own bars, so your classic hotkeys never change.
- Wider side panels in the classic layout: drag a panel's inner edge to make it up to twice as wide.
- Party frames: every member's health and mana in one block, even when they are off screen, with right-click options to message, follow or pass leadership. Party invitations now pop up with Accept and Decline buttons.
- Compact vitals: an optional portrait frame with your vocation icon, name, health, mana and experience.
- Lock windows so they can't be dragged by accident.
- A new login and character select by a quiet forest campfire. Your characters sit in one window beside a card for the one you choose, and characters with a capstone show its title (for example Crusader).
- Soft interface sounds on the login and character screens. Turn them off with "Interface sounds" under the speaker in the top bar.

### Changed

- New login music, Fireside Ballad, played much more quietly. The speaker in the top bar now controls only the music, with a volume slider when you hover it.
- Inspecting a player has a new look: their outfit, vocation or capstone icon, guild, equipment framed in each item's rarity colour and bars showing their skills at a glance. Hover any item for its full tooltip.
- The launcher plays a calm piece of Vestara music instead of the campfire sounds.
- New players start in the immersive layout. If you already play on Vestara, you stay in the classic layout until you switch.
- Account creation now opens in the middle of the screen, and the login screen no longer shows a YouTube panel.
- The server sends a wider area of the map, so you can see creatures further away. Monsters still notice and chase you from the same distance as before.

### Fixed

- Hotkeys and action bars: keys on slots 10 to 50 no longer clear other slots, Chat On and Chat Off use their own keys straight away, bars are no longer lost if the client closes while saving, and characters no longer share each other's bars.
- Windows such as the Battle List no longer go missing at login, and opening a window in a full column no longer closes others.
- Looking at a player shows their capstone title (for example "He is a Crusader.").
- Attributes no longer get stuck on "Loading...".
- Attacking a creature that is too far away now says "Too far away."
- The chat tabs always open in the same order, and the game window no longer flashes white when you switch back to it.

<!-- /vestara-client:0.7.0 -->

<!-- vestara-client:0.6.3 -->
<!-- source-archive-sha256:0177ef8cbae68ad9098cb5433569dbd057264ed256e5b63ba70baa3f06eb1f11 -->
<!-- source-content-sha256-v1:1cd85fea335e54dcd480d3fb6e219b68c871b398ee4a1aa857ce79771271243d -->
## 0.6.3 — 2026-10-28

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.6.3)

### Added

- Exaltation Forge rework, built around Vestara's rarity and star system:
- Items fuse with others from the same family (melee weapons, fist weapons, distance weapons, wands, armour, helmets, legs, boots), not only identical copies.
- An item's maximum tier equals its stars, so any forgeable item can now hold a tier, including custom Vestara gear.
- The success chance shows its full breakdown. Rarity, tier, stars, a matching item and cores all count, between 5% and 90%.
- Tier transfer works again and has a Full transfer option (higher cost, uses cores).
- New forge window with Fuse, Transfer, Convert and History tabs, cost preview including your bank gold, a confirm step and a result panel. If something can't be done, the forge tells you why.
- Onslaught, Ruse and Transcendence are 50% stronger. Convergence fusion has been removed.
- New item tooltips: a cleaner layout with rarity-coloured outlines, stat tiles, colour-coded roll bars and turquoise MAX rolls. Legendary, Mythic and Divine items each get their own animated effect.
- Hold Shift over a weapon or piece of armour to compare it with what you're wearing: per-stat arrows plus an "If you equip this" list of every gain and loss.
- Spellbook rework: categories, search, and spells split into ready to cast, unlocks later and other vocations. A details panel shows words, cost, cooldowns and requirements. Drag a spell onto your action bar to bind it, or double-click to cast.
- The spellbook shows only your own vocation's spells, plus a Mastery category with the spells your mastery tree has taught you (they disappear again if you reset the mastery).
- Inspecting a player with a mastery capstone shows their specialisation title (for example Crusader or Fire Sorceress) instead of their vocation.

### Changed

- Knight mastery Twin Cut: every sword swing now has a 20% chance to strike twice, instead of every 4th swing on the same target. Procs can happen back to back.
- Ricochet and Cleave no longer roll as item affixes. Existing ones are replaced with a fresh roll of the same quality. The mastery and set-bonus versions are unchanged.
- Quest access: almost every quest-gated hunting ground and boss route is now open to everyone, including boss chains such as the Falcon and Cobra Bastions, Goshnar's Megalomania, Bakragore, the Pale Worm and the Asura Mirror. Quest rewards (outfits, addons, items, mounts, achievements, experience) still have to be earned.
- Gnome city teleports, Feyrist shrines, the Elemental Spheres and the astral carvings no longer use up crystals, gems or pearls.
- Every character has postman privileges (mailbox doors and the postman travel discount).
- Several sidebar, chat and minimap buttons have a new look.

### Fixed

- Loot containers: swapping or re-equipping your main backpack no longer clears your loot and obtain container assignments for bags you still carry.
- Loot filter: your skipped and accepted loot lists are saved right away, so a crash no longer loses them.
- Item tooltips no longer get stuck on screen.
- Hirelings: saved immediately (a crash can no longer lose one), recalling with a full store inbox no longer leaves an unrecallable hireling, and outfit and Cook fixes.
- Hirelings can be bought from the store again; hireling renames and sex changes work.
- Hero of Rathleton pipes and teleports, the Formorgar Mines hoist and the Farmine/Zao carpets let players through again.
- Seeing a scorcher, chiller or simple jo staff no longer makes your map drift out of sync with the server.

<!-- /vestara-client:0.6.3 -->

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
