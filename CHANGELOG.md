# Vestara client patch history

Published player-client updates, newest version first. Dates are the UTC release-note dates.

<!-- vestara-client-history:v1; maintained by the publisher -->

<!-- vestara-client:0.21.0 -->
<!-- source-archive-sha256:c63f37d5e07b8edf0c92922032bcd4109cc6e4212cc0b299fe77d68f6569b672 -->
<!-- source-content-sha256-v1:62d99c6f7d2998e5e0a1fc20e064b999f7e2c2ac47dbddd62351bc3666d7e160 -->
## 0.21.0 — 2026-11-13

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.21.0)

### Added

- You can now salvage gear you don't need at the Exaltation Forge. It breaks down into essences, the forge's new upgrade material: the item's stars decide which essence you get and its rarity how much. Rare and better items can also give an affix stone.
- At forge tiers 3 and 6 you now choose a permanent upgrade for the item: Refine one of its affix lines, or Imprint a new attribute on it. At tier 6, every kind of forgeable item can instead take an upgrade of its own, such as a stronger Momentum, extra physical resistance or an extra ricochet target. Your choices appear in a new Forged section of the item's tooltip.
- Items with 9 or more stars can reach forge tier 9 and gain a unique effect, such as Last Stand (survive a killing blow once every 4 hours), Twin Cast, Volley or Fleetfoot. Only one forged unique effect works at a time.
- Anvils now let you salvage gear too. An anvil in your own house does everything the Exaltation Forge does, so you can enhance, upgrade and salvage at home.
- The anvil is now house furniture: buy it for 850 coins in the store, or for 25,000 hunting task points from the Task Board shop or Walter Jaeger, and unwrap it in your house.
- Mythic monsters now drop forge slivers.
- Gear now has gem sockets. Every weapon, armor, helmet, legs, boots, shield, spellbook, ring, amulet and quiver gets from 1 socket up to a maximum set by its stars and type (up to 6 on moonsilver gear). Items you already own get theirs the first time you look at, equip or carry them. Sockets are shown in a new Sockets section of the tooltip.
- Gems drop from monsters. Stronger monsters drop better grades, elite and mythic monsters drop gems more often, and many monsters drop gems that suit them: dragons drop Draconic Ward and Ember, undead drop Undead Bane and Last Rite. Corrupted False Halo gems drop only from moonsilver monsters.
- 13 gems to start: Hemorrhage, Deep Roots, Hexweaver, Ricochet Lens, Ember, Undead Bane and Marked for Death (red), Draconic Ward and Martyr's Ward (green), Last Rite, Predator and Pack Leader (blue), and the corrupted False Halo. Each comes in five grades, from chipped to radiant. Wearing the same gem more than once gives less from each extra copy, and only one Last Rite counts.
- Set, remove and combine gems in the new Sockets tab of the Exaltation Forge or an anvil in your house. Setting a gem is free; taking one out costs gold depending on its grade, and the gem comes back unharmed. Three gems of the same kind and grade combine into one of the next grade. Salvaging an item, or giving away its forge tier, returns its gems.
- Red sockets take red gems, green take green and blue take blue; rare prismatic sockets take any gem. Prism shards (recolour an empty socket) and jeweler's augers (one try per item, 50% chance, to add a socket) drop from elite and mythic monsters and raid bosses.
- The forge tier 3 upgrade has a new choice, Open: make one of the item's sockets prismatic.
- Token traders take part in gems: Yana now sells prism shards for 10 gold tokens and jeweler's augers for 25 gold tokens (her imbuement material bundles are gone), and Cledwyn finds you a random flawed gem of the colour you choose for 5 silver tokens.
- Imbuing shrines are now gem shrines. Use one to combine three gems into the next grade, or pay gold to reroll a gem into a random other gem of the same colour and grade. The store sells gem shrines for your house.
- Last Rite and the forged Last Stand share one save: after either one saves you, both wait for their cooldown.
- The journal's Places page is much bigger: besides cities and hunting grounds you can now discover villages, islands, landmarks, caves and dungeons, boss lairs and wild regions such as the Plains of Havoc, over 200 places in all, each group with its own count.
- In the Cyclopedia Houses tab, selecting a house now shows where it is: its town, how far it is from the temple and in which direction, and a "Show on map" button that opens the map at the house entrance.
- Selected houses now show a floor plan of their rooms with the walls, the doors and the entrance marked. You can switch between floors, and the size, beds, floors, rent and type are listed next to it.
- The login screen now shows how many adventurers are online, next to the green dot at the top. The dot dims when the game server cannot be reached.
- New option "Weapon swing animation" (Options \> Graphics \> Effects): switch off the weapon that appears beside an attacker and swings on every melee attack, if you prefer attacks without it. It is on by default.
- At the Oracle you now choose your vocation and your home town in a window: pick a vocation, pick a town (the ones recommended for that vocation are listed first) and confirm. The buttons act directly, nothing is typed into the chat. Talking to the Oracle still works as before.
- The vocation window now also tells you which titles each vocation's capstones lead to, such as Berserker, Blademaster or Guardian for a Knight.
- New achievement "A Wider World" for leaving Rookgaard and reaching the mainland.
- Adventure Guide: every milestone now shows what it pays as pictures (gold, potions, the weapons you can choose from), and a dot on the Adventure Guide button tells you when a reward is waiting to be claimed.
- When you complete an Adventure Guide milestone, a card now tells you which one, what it pays and to press Claim reward. Rewards still unclaimed are mentioned once when you log in.
- Adventure Guide: the troll caves near Thais, Edron, Venore and Ab'Dendriel and the Amazon Camp near Venore are now tagged "New player friendly" and listed first for characters below level 20.
- Nightblade: new spell Assassinate (exori max sica, level 200). One heavy strike on the enemy next to you that always counts as a backstab, every 18 seconds.

### Changed

- The Exaltation Forge has been reworked and has a new window. Instead of fusing two copies of an item, you now enhance a single item with essences, gold and, at higher tiers, exalted cores. Each tier is harder to reach than the last.
- From forge tier 4, a failed enhancement drops the item one tier, unless you protect it by paying double the gold or spending an extra exalted core. Below tier 4 a failure only costs the materials.
- Moving a forge tier to another item now costs gold and essences instead of dust, and the item's forge upgrades move along with it. The item giving its tier is still destroyed.
- Forge dust is no longer used and monsters no longer give it. The dust you have, including the dust you spent raising your dust limit, turns into gold in your bank the next time you log in.
- Imbuing has been replaced by gems. Imbuement scrolls no longer work and are no longer sold, and imbuements still on your items are removed, without a refund, the next time you log in or equip the item.
- Finding a hunting ground, village, island or landmark now shows a small notice coloured by the kind of place instead of the big city banner. Several finds close together share one notice, and boss lairs are only written into your journal so nothing pops up during a fight.
- The champion statues have been taken out of the Thais temple for now; they will return at a later date. Town criers still tell you who the champions are.
- The Rookgaard tutorial now follows one clear path: walking and talking, the village, then Huntsman Fargas's first task. Tips about using things, fighting and looting only appear once you have a task and something to fight.
- The tutorial arrow on the map is much larger, brighter and bounces more, so it is hard to miss.
- Huntsman Fargas's tasks: the route card now appears as soon as you accept a task, and its arrow leads you step by step: the stairs to Fargas, the sewer grate for the rats, the way back up, and the stairs again. Each of those spots is also marked on the map itself.
- Huntsman Fargas's bug task now leads to the loose stone pile north of the village, explains how to open it with a shovel and how to leave with a rope, and marks a safe square to fight from so the bugs cannot surround you.
- Arriving on the mainland, the tutorial now sends you straight to the Adventure Guide and then to the daily and weekly tasks, before it explains your vocation, your spells and the layout.
- Adventure Guide: the rotworm caves near Thais and Edron are now recommended from level 12 and listed after the troll caves, because rotworms hit too hard for a character fresh off Rookgaard.
- Druid beast forms hit much harder: Rend, Maul, Pounce and the Primal Avatar's Stampede deal about 2.4 times their old damage, so the beast moves are worth using next to your ordinary spells.
- Beast Hide is stronger. Wolf Form's hide now absorbs 80%, 90% or 100% of a Magic Shield by rank (was 35%, 45%, 55%), Bear Form's 115% or 130% (was 85%, 100%) and the Primal Avatar's 175% (was 150%).
- Shifting into a beast form can grant a fresh Beast Hide every 14 seconds, the same wait as Magic Shield (was 20 seconds).
- Druid: the Elemental Synthesis stance now also strengthens the beast moves (Rend, Maul, Pounce and Stampede), which got nothing from it before.
- Sorcerer: Tempest calls down more lightning on bigger groups. It now strikes two to four bolts every half second, depending on how many enemies are around you (up to 24 bolts, was always 12), still at most 3 per enemy.
- Monk: Tiger's Fury comes back sooner (10 seconds of rest instead of 15) and its extra claw on every basic attack hits for 75% of the attack (was 50%).
- Paladin: Oathbreaker now makes every basic attack strike a second time with death damage, for 20%, 28% or 35% of the attack by rank. Like your other death damage, it drains life.
- Nightblade: Cutthroat and Eviscerate deal 20% more damage, and Eviscerate is ready again after 6 seconds instead of 10.
- Nightblade: Ambush hits twice as hard and is ready again after 12 seconds instead of 14. Dagger Storm deals 20% more damage.

### Fixed

- Upper, Middle and Lower Spike can now each be discovered separately.
- The Launcher now shows how many players are online next to "Server online" more reliably, and no longer drops the number when the server is briefly too busy to answer.
- Rain now falls at a steady pace. It no longer races, stalls or seems to rise when you walk north or south, and it no longer streams sideways while the weather changes.
- The "World First" banner is now easy to read: its caption is now dark lettering on an ivory plate instead of pale gold on gold, and banners without a picture no longer have a glow washing out their text.
- Adventure Guide: "Coming up" is no longer empty for high-level characters. It now lists the things you haven't done yet that didn't fit in the short list above, followed by what opens at later levels.
- The Oracle's vocation window can now be reopened after you close it: say hi to the Oracle again, or ask for the vocations. Before, you had to walk away and come back.
- Vocation window: the Sorcerer and Druid now face the wave they cast and stand right behind it, the Monk wears the Monk outfit, and the Monk, Reaver and Nightblade show spells they really have (Flurry of Blows, Eldritch Sweep, Blade Fan).
- Adventure Guide: it no longer says "1 done" right after you arrive on the mainland. Only milestones you have completed are counted.

<!-- /vestara-client:0.21.0 -->

<!-- vestara-client:0.20.0 -->
<!-- source-archive-sha256:526b607a7da9c5544dae22dd78312a34d2823b33fb7cc4d89e841adb194f4a5f -->
<!-- source-content-sha256-v1:8873922d9602ce5e08ffc2dcd91fecb812e8282f34c6292f7e63d32f6e932126 -->
## 0.20.0 — 2026-11-13

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.20.0)

### Added

- The Launcher now shows whether the game server is online and how many players are playing.
- The Launcher has a Discord button, and keeps a log you can copy from the Activity panel when you need help from the team.
- At the Oracle, a new overview shows what every vocation does before you choose: how it fights, its first spells, how masteries shape it later, and a small scene of the vocation casting one of its spells.
- The Adventure Guide now pays rewards. When you finish a goal in "What to do next", such as your first hunt or reaching level 10, 20 or 30, press Claim reward for gold and useful items. At level 20 you pick one weapon for your vocation.
- On Rookgaard, the guide now leads you through Huntsman Fargas's tasks one step at a time: to Fargas, to the monsters (rats first, down the sewer grate in the village), and back for your reward and the next task. A counter shows your kills.
- You can read tutorial tips again: use "Read earlier tips" on any tip, or the Earlier tips button in Options \> Interface \> Tutorial.
- New tutorial tips: pushing creatures and players, rope and shovel, potions, and the bank and depot. On Rookgaard, a tip after your first kill shows the two spells you already know, Practise Fire Wave and Practise Healing; another shows your vocation's first spells once you choose one.
- When you pick an early hunt in the Adventure Guide and have few potions, the route stops at your town's potion seller first.

### Changed

- Launcher downloads continue where they stopped when your connection drops, and no longer give up after 30 minutes on a slow connection. Progress shows the size, speed and time left.
- Installing the game for the first time is faster, and updates need much less free disk space.
- The Launcher rests while you play: its animated background stops while the game is running, and it checks for new updates by itself when you come back to it.
- Launcher error messages are clearer, for example when you are offline or your disk is full.

### Fixed

- The Bestiary pop-up no longer has a see-through strip along its top.
- Bows and crossbows no longer show a melee swing when you attack; staves and fist weapons show the right one.
- The Launcher window now fits on small or zoomed-in laptop screens.
- The Launcher tells you when the game could not start, instead of saying it started.

<!-- /vestara-client:0.20.0 -->

<!-- vestara-client:0.19.0 -->
<!-- source-archive-sha256:15905f4e18c79c5cac924e4c5a4fa0b09da61aa7616ad858011064a2ca4ce77c -->
<!-- source-content-sha256-v1:ebd3ed0eff28f1734e1404075eb38e720c3a4d9cf721c4289f617dbbe348e578 -->
## 0.19.0 — 2026-11-13

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.19.0)

### Added

- New Auction House in the market window: sell an item from your depot for gold or Tibia Coins. Choose whether players can bid, set an optional minimum bid and buyout price, and pick 1, 3, 7 or 14 days. A small listing tax is paid when you list, growing with the price and the duration.
- Auction House bidding: your bid is held from your bank or your transferable Tibia Coins, and comes straight back if someone outbids you or buys the item out. The highest bid wins when the time is up and the item arrives in your inbox. Items that get no bids return to the seller's inbox.
- Hovering an item listed in the Market or the Auction House now shows its full tooltip, with its exact rarity, affixes and tier, just like in your backpack.
- Houses are now auctioned in the Cyclopedia (Houses tab). Pick a town, see which houses are free, rented or on auction, and bid with the gold in your bank. The auction runs 7 days from the first bid and is settled at the daily server save; the highest bidder wins and pays about the second-best bid (only the rent if nobody else bid).
- House owners can move out, keep their house, or transfer it to another character for a price from the Cyclopedia. The new owner accepts or rejects the transfer there, and the gold is held safely until the transfer day.
- New characters who reach level 8 on Rookgaard without a vocation are now brought straight to the Oracle (once they are out of a fight), with a tip explaining how to choose a home town and a vocation.
- The Oracle now gives advice on which home town suits each vocation best for a first trip to the mainland: ask the Oracle for "advice". Every town is still on offer.
- Tutorial tips can now point things out on the screen: a gold box and a gently bouncing arrow show the people and places a tip talks about, and a small arrow points at the buttons it mentions. A new Rookgaard tip shows you around the village.
- New tutorial tips explain Spell Echo the first time one of your spells echoes, and equipment sets the first time you pick up a set item.
- The Cyclopedia Items tab now shows which creatures drop an item and how often, right under the item's details.
- Campfires: buy a campfire kit in the Task Board shop and light it on a free street square of a major city (not in houses, depots or temples). It burns for 10 minutes. Stand close for a minute (a small countdown shows next to the global boosts) and you get +3% experience from monsters for 30 minutes.
- Rested experience: log out in a house or a protection zone and you slowly become rested, up to 30% of a level over about 20 hours. While rested, monsters give +10% experience until it is used up. Rested and campfire together never give more than +10%.
- Sounds from Tibia: spells, weapon hits, creature noises and death cries now play, quieter the farther away they are, along with the sea, birds, wind and caves of the place you are in, all the official Tibia sounds. Each kind of creature has its own voice. Change or turn them off under Options \> Sound (Sound effects, Ambient sounds).
- Music from Tibia: each city plays its own Tibia theme a few seconds after you arrive, then stays quiet for a while, like on Tibia. Feyrist, Marapur, Gray Beach, Rookgaard, Dawnport and the countryside around Thais have their own themes too, and the royal throne rooms and boss lairs play their music as soon as you walk in. Turn it on or off under Options \> Sound (Music).
- Weapon swings: auto-attacks now show the weapon swinging at the target, like on Tibia: swords, clubs, axes, bows, crossbows and bare fists each have their own animation, seen by everyone nearby. Fist weapons now make a sound too, and rods sound different from wands.
- Hunt summary: back in a city after ten minutes or more away, a small card shows how long you hunted, the experience gained, your balance, your best drop and what you slew most. Click it to open the Hunt analyser. You can turn it off under Options \> Interface.
- Friend moments: when a friend (on your VIP list, with you on theirs) reaches every 10th level, finds a mythic item, beats a boss or raid for the first time, or comes back after a week away, you get a quiet line in the Server Log and their name glows in your VIP list. Never during a fight. You can stop sharing yours under Options \> Interface.
- After-raid card: when your party wins a raid, a card shows who dealt the most damage to the boss, who healed the most, whether nobody fell, and who cleared it for the first time. The raid window's Last run button shows it again.
- Journal chapters: your journal is now split into chapters by level, each with a short summary of the cities reached, bosses beaten and more. Very old minor lines (hunting grounds, repeat raid clears, lesser drops) are folded into their chapter's summary, so the journal never grows too large.
- Character list: the hero card now shows a small picture of the city each character was last in, behind the hero, with the name kept easy to read.
- Spend points: after a milestone level, or when five or more attribute points are waiting, a small card offers a Spend points button that opens your skills.

### Changed

- The launcher and the login screen play the usual Vestara music again.
- The launcher and the login screen are back to the Vestara campfire.
- The login screen's "Did you know?" tips now come from a much larger set covering Vestara's own systems and classic Tibia basics.
- !buyhouse, !leavehouse and !sellhouse now point you to the Cyclopedia Houses tab. Your bid limit and first rent are taken from your bank when you bid and returned right away if you are outbid. Each character can own one house and bid on one house at a time.
- Catch-up is back, gently: characters below 70% of the highest level gain up to 50% more experience, less the closer they get, and none from 70% of the top up. Skills and magic level work the same way against the best in that skill. It doesn't add to the low-level bonus; the larger of the two counts.
- The action bars have a new Vestara look in both the classic and immersive layouts: green slot frames that brighten when you hover, a gold frame on equipped items, and clearer hotkey labels and cooldown numbers.
- The page buttons at the bottom of backpacks now match the Vestara style.
- The Cyclopedia Items tab is easier to read: a taller category list, a clear highlight on the selected category and item, and new filter buttons.
- The Cyclopedia Houses tab has a cleaner look, and the house you select is outlined in gold.
- The Prey window's slot titles are now gold, and the time left on a prey bonus is easier to read.
- NPCs who mention your recent great deeds now do so once per town instead of once per NPC, remember it after a server restart, and also notice world firsts and mythic kills.
- The Adventure Guide's route tracker now leads you step by step, like a levelling guide: each step says which way to go, how far and what to look for ("Go north-east for about 80 steps to a ladder and climb up it"), and the next step appears once you have taken it. A steady arrow points straight at the next stairs, ladder, hole or boat captain, and a second line says where the hunting ground lies. Routes are walked on the real map for almost every hunting ground, including journeys by ship.
- Route tracker: the next spot and the hunting ground are now marked on the minimap. When they are too far away to be on it, the marks sit on the minimap's edge in the direction to walk.
- Adventure Guide: "Mark on map" is now "Show on map" and opens a route map instead of the full-screen world map: the area around the place, a flag on the hunting ground, your own position, and for a tracked route a dotted trail, a numbered pin for every step and the list of steps beside it. Click a step to see it on the map. The route card has a Show on map button too.

### Fixed

- House rent is now charged when it is due; until now a server restart reset it.
- The right-click menu no longer offers "Use" on things that can't be used, such as plain chairs, walls and decorations. Anything a quest or script lets you use, doors, beds, levers, books and the like still show it.
- The login screen now shows today's boosted creature and boss and the event calendar (the coming weekend events and any special events). They update each time you log in, so the first login of a day fills them in.
- Travelling by boat or carpet with the Travel window works again: pressing Travel on a destination now takes you there straight away, without typing the destination and "yes" in the chat. You can still type them if you prefer. The window now counts the gold you carry and have in the bank, opens again when you say hi, and closing it no longer stops your character from walking with the arrow keys.
- The Bank window now does what you ask straight away: Deposit, Withdraw, Transfer and Change no longer type the words in the chat over and over. The banker answers in the chat, the window shows the answer and your new balance. You can still type to the banker if you prefer.
- Using the NPC conversation buttons, including the More list, no longer stops your character from walking with the arrow keys.
- The Bestiary pop-up works again: it shows the creature's picture, whether it is a new entry, an update or a completed entry, and how many kills the next stage needs.
- The Store window has a close button again, at the top right.
- Highscores: hovering over or clicking a category no longer leaves it highlighted, categories no longer get stuck while loading (an empty one now says no one is ranked yet), and the "All vocations" filter is back.
- Fixed the game client crashing after you died, or when you equipped several pieces of gear in a row, such as putting on a full set.
- Route tracker steps no longer get cut off at the edge of the card (for example the town to say to a boat captain).

<!-- /vestara-client:0.19.0 -->

<!-- vestara-client:0.18.0 -->
<!-- source-archive-sha256:cf6620cd9cdd5d18047433e43fe1598bb6e3317eda75a9c04560143d5743b943 -->
<!-- source-content-sha256-v1:561d687fa697399dbce6543a20a419f6b0942ece73c0d764fb3f6cfb6fcff0cd -->
## 0.18.0 — 2026-11-12

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.18.0)

### Added

- The Outfits window has a new look: preview, addons and colours on the left, your outfit, mount, wings, aura, effect and shader in the middle, and every look you own on the right, with a search. Star favourites to list them first, and save presets that keep your whole look.
- The Store has been redesigned: a home page with featured, popular and sale offers, offer cards with clear badges, a large preview, pack sizes and quantities that show exactly what you get and the total, and purchases completed inside the Store. Search works as you type, and offers can be sorted.
- The Battle List has a new look: buttons to show monsters, players and NPCs with their counts, filters and sorting (closest first by default), distance and health in each row, vocations, party stripes, gold elite and violet mythic frames, and red and green rows for your target and followed creature. Party members under 50% health gently pulse while sorting by health.
- NPC trade and player trade have a new look. NPC trade lists one item per row, says why a row can't be traded, shows the total, weight and gold after the trade, and lets you type or step the amount. Player trade shows both offers with counts and tells you what to do next.
- Item rarity marker: in Options, choose how rare items are marked: an outline, a coloured slot frame, a soft glow, coloured corners, or off. Each style is shown on a sample item.
- New: the Adventure Guide (sidebar button). It lists hunting grounds for your level and vocation with what each is best at, their monsters, weaknesses, what to bring and the loot worth taking. Track route shows the way step by step, with an arrow and a minimap mark.
- Adventure Guide: What to do next shows one clear next step, more things worth doing now and what opens later, including the basics many guides start with, such as a rope and shovel, the bank, Rashid and the djinns.
- Task window: NPCs that give tasks (Grizzly Adams, the Spike gnomes, Bigfoot's Burden and more) open a window with your tasks, progress, rewards and buttons to start, cancel and turn in. Grizzly Adams also shows your Paw and Fur rank and bosses. Typing still works.
- NPC conversations: buttons under the NPC chat show what you can say, such as Trade, Mission or the places a captain sails to. Captains and other travel NPCs open a travel window with every destination and price, and bankers open a bank window to deposit, withdraw, transfer or change coins.
- Minimap: a label shows which floor you are looking at, and the coordinates of the spot you point at.
- New: the Task Board (sidebar button Task Hunt). Three daily tasks are picked for your level and vocation; finish one for experience, gold, Hunting Task Points and bonus bestiary kills. Reroll with tokens (one free each day), abandon a task for free, and get new tasks for free once you outlevel them.
- Task Board: weekly kill and delivery tasks with a points multiplier up to x8, and a Task Shop with the Falconer outfit, the Antelope mount, trophies and a falcon pet. A Task Tracker window shows your progress, and the Task Hunt button shows a dot when a reward waits.
- Cyclopedia map: search for towns, NPCs and your map marks, and the map moves to the spot on the right floor.
- Entering a major city shows its name with a short animation; the first visit reads City discovered with a count of the 15 cities. Your first visit to each Adventure Guide hunting ground shows its name too. Logging in inside a city does not show it.
- Bestiary: a card slides in when you first kill a creature, unlock more details or complete an entry. Vestara's own creatures now have entries, a For your level button lists the creatures that suit you, a creature's page lists its hunting grounds, and the search finds any part of a name.
- Attribute perks: 100 bought ranks of Nature Magic make food last 25% longer, and 100 of Luck give 5% more gold from monsters. Ranks from gear do not count. A banner celebrates each perk you unlock.
- Banners for the big moments: level 20 and every 50th level, a raid starting, won or failed, your first kill of any boss, a finished task (with the creature you hunted), a completed quest, a set step or complete set (with rings rippling from the pieces), an affix stone result and a new best hit.
- Rare drops: a Legendary or better item shows a banner with its picture in its rarity's colour, for you and party members nearby. Several drops at once share one banner, and the corpse keeps flaring until the item is taken.
- More banners: when you earn a mastery point (the Masteries button shows the points waiting), when you kill an elite or mythic creature (each with its own death effect), when your Market offers sell, and for world firsts, which everyone online sees: the first to reach level 100, 200 and so on, or to beat a raid boss.
- Combat feedback: Spell Echo, Heal Echo, Ricochet and the mastery Cleave show a short word over the target when they trigger. Critical hit numbers are larger and brighter, and the edges of the game view turn softly red below a quarter of your health.
- Upgrades: gear in your bags and corpses shows a small green arrow when it is better than what you wear on every stat they share. A higher rarity alone does not count. A switch in Options turns the arrows and gear comparison on or off.
- Forge and affix stones: the item glows in its rarity's colour when a fusion, transfer or stone succeeds, and fades grey on a failure. Banners play short, quiet sounds that follow the interface sounds option.
- New: the Journal (sidebar button). The Timeline lists what your character has done, from cities and hunting grounds to milestone levels, boss kills, raid clears, quests, achievements, the best drops and the first time you wore a great item. Places and Lore fill as you explore.
- Towns: criers greet you by your latest deed, call out the weekend event and raid victories, and show the board of recent deeds or the champions. Each crier town has a notice board by the temple, statues of each vocation's highest character stand in Thais, and other NPCs may mention your deeds.
- Guilds: online guild members are told when a member defeats a boss for the first time, clears a raid or finishes a quest.
- Session summary: logging out shows what the session came to: time, experience, levels, best drop, tasks, quests, places, hardest hit and deaths. The exit window has a Session button for it.
- Death window: it shows the last hit you took, the damage of your final 12 seconds and where it came from, with clear text and Respawn and Log out buttons.
- Cyclopedia: the Character tab opens on your character sheet: title, level progress, attributes, strongest masteries, combat stats, gear rarity, sets and last deaths.
- Highscores has a new look: categories, one-click vocation filters, a podium with the top three in their outfits, your own row marked and Jump to me.
- Items of Uncommon rarity or better remember where they were found, for example "Found on a dragon lord, 12 Nov 2026, by Sir Galahad", even after a trade or a Market sale.
- Fame: give another player fame from their inspect window, once a day from level 50. Everyone sees a character's fame when inspecting them.
- After an update, a What's new card shows its notes the first time you log in, and a short note tells you what happened since you were last here: a new task week, a weekend event and your guildmates' deeds.
- Notifications share one column at the top of the game view, in both layouts. Banners, achievement pop-ups, Bestiary updates and the login note line up and wait their turn instead of covering each other.
- Immersive layout: share your layout as a code with Copy layout code, and load someone else's with Use a layout code. New players pick a starting layout (Minimal, Standard or Everything) from small previews, and the layout menu shows the presets again any time.
- Tutorial tips: new cards introduce the Adventure Guide, the Task Board, your promotion at level 20, the Journal, elite creatures, fame, dying, and Lock windows with Ctrl+Alt.

### Changed

- Immersive layout: windows snap more gently and not over a side panel, moving the minimap no longer drags the panels below it, and with Lock windows on you can still move a window by holding Ctrl+Alt as you drag.
- Achievements: the unlock pop-up stays about 25 seconds (shorter when other notifications wait). Click its x to close it, or click it to open your achievements.
- Attributes: ranks cost more the higher an attribute goes (1 point each up to 200 ranks, 2 up to 300, and so on), and each rank does more: 0.08% damage or healing, up from 0.05%. All your points are returned on your first login to spend again.
- Attributes: Vitality and Intelligence raise maximum health and mana by a share of your own (0.04% health and 0.03% mana per rank), so they are worth the same to every vocation.
- Monsters have more health the higher the level they are meant for (about 13% more at level 100, 23% at 300, 32% at 600), with that much more experience and a matching chance of a second loot roll, so experience and loot per hour stay the same. Bosses and Vestara's own monsters are unchanged.
- Gear: Strength, Dexterity, Arcane Magic and Nature Magic lines go up to 100, down from 150, as each rank is worth more; owned items keep their roll quality. Early sets that gave Vitality or Intelligence now give health or mana directly.
- Reaver: Soul Rend gains 4% damage per Soul instead of 8%, and your abomination hits harder to make up for it.
- Nightblade: distance fighting on Paladin gear counts as sword fighting for you, and tooltips show it that way.
- Quest Log: a progress bar, ticked quests and missions, and pinned or hidden quests that are remembered.
- VIP list: online count, add and show-offline buttons, online players first, offline players in grey and notes on hover.
- Hotkeys window (Ctrl+K): every hotkey says in plain words what it does and can be searched, changes save as you make them, and Reset all asks first.
- Blessings window and Supply Stash: blessing names on hover, a count of active blessings, a Get blessings button, and number boxes with - and + and quick amounts instead of sliders.
- Pop-up boxes and choice windows: the confirming button is on the left, labels fit, errors have a red title, the selected option is clearly highlighted, and typing boxes take the cursor straight away. The chat's channel list highlights your choice too.
- Prey: the tracker shows each creature, bonus and time left with a time bar, and the Prey window explains every button and shows an active prey's bonus and time left.
- Books and letters show who wrote them and when, with a character counter.
- Cyclopedia: tab names on hover, an empty houses message, and placeholder texts replaced.
- Smaller windows tidied up: Bug report, Unjustified Points, the Imbuement tracker, the Loot splitter, Weapon Proficiency and the Daily Reward wall read more plainly.
- Options window redesigned: every page in one list, clear headings, a search for any setting, arrow buttons with values instead of long sliders, and hover help. Reset and restart and clearing an action bar ask first. Interface scale and text sizes go in 10% steps.
- Market: a clearer layout, with full item names, a taller category list, For sale and Wanted lists, labelled gold and coins, and no cut-off buttons.
- Quick loot window: clearer buttons, tooltips on every slot and plain help text.
- Skills window: Ricochet Targets shows (cap) in gold at your limit. Analyser charts use the Vestara greens.
- Task Board: easier to read, with clearer buttons, tabs, banners, counts and rewards.
- Sidebar buttons have plain names on hover. The Journal button shows a dot for new entries, and the Skills button while attribute points wait. Leaf ornaments are gone from the Dungeons & Raids and Achievements windows.

### Fixed

- Immersive layout: a panel placed under a side panel's windows stays under them instead of pushing them below it.
- Outfits: changing your outfit keeps your wings, aura, effect and shader; unticking Ride mount really makes you walk; locked wings, auras and effects can't be worn; and a crash when wings came off a preview is fixed.
- Outfits window: the search always filters, the window opens with what you wear, and Enter in the search no longer applies and closes.
- Store: mount pictures show on the home page, the coin check matches the server, Get Coins explains how to get coins, and categories with sub-categories no longer open empty.
- Quest Log: the second quest no longer always shows unfinished, symbols in the search work, and filters stay applied.
- VIP list: login and logout notifications work again.
- Blessings window: the History view works, the promotion text is right and penalty percentages show correctly.
- Prey tracker: the third slot is no longer cut off, and unlocked slots show again.
- Unjustified Points and the Imbuement tracker no longer cause errors or pile up hidden items.
- Options: Control Buttons names are readable, clearing right bar 3 no longer clears right bar 1, and drop-down lists open again.
- Market: categories keep working after an error.
- Map marks: the Description label no longer overlaps the text box.
- Quick loot: the search filters your loot list, and clearing a list asks first.

<!-- /vestara-client:0.18.0 -->

<!-- vestara-client:0.17.0 -->
<!-- source-archive-sha256:003aa0191e432f9d01fe5d742c0b71dcf428ec580f6311d4aff3d6ead2ec94e2 -->
<!-- source-content-sha256-v1:4e0d7f6a0a8fece38cb06bea433b2f33932d28ae3f5655d3c91957f6a02d39d4 -->
## 0.17.0 — 2026-11-09

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.17.0)

### Added

- New raid: The False Ascension, the moonsilver dungeon beyond Albion (level 800+, a party of six, weekly). Take six of the plates around the fountain and pull the lever to face the Envoy of the Heavens, then what wears his halo: Lucifer, the False Light.
- Moonsilver bag: the raid's reward bag. Open it for a piece of moonsilver equipment for your vocation.
- Auric moon sigil: use it on a moonsilver weapon for a 5% chance to turn it stellar. A stellar weapon is always Divine with the most affix lines it can hold. Your first clear of The False Ascension always gives one.

### Changed

- Nightblade: new animations for Cutthroat and Eviscerate (crimson slashes), Feint (a steel arc), Ambush (a shadow streak along the dash) and Phantom Rush (a speed blur at every dash and a crimson double slash on each hit). Dodging with Evasion now shows a speed blur too.

<!-- /vestara-client:0.17.0 -->

<!-- vestara-client:0.16.0 -->
<!-- source-archive-sha256:fd225142cbbb312a0d43bd9f8bde4f888a35134800ff45b235e4786e6a034cdd -->
<!-- source-content-sha256-v1:fdce2f8235977a3316f38c5d06d2b68638fdecca4ae96f1faaaed893d178436b -->
## 0.16.0 — 2026-11-07

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.16.0)

### Added

- A new vocation: the \*\*Nightblade\*\*, chosen at the Oracle and promoted to \*\*Phantom\*\*. Nightblades fight up close with daggers, and an offhand dagger in the shield hand adds a second strike to every basic attack. A hit on a monster from behind, or on one you have Exposed, is a backstab: a sure critical hit that also leaves a Mark on it.
- Nightblade spells: builders leave Marks (Cutthroat, Throwing Stars, Blade Fan, Star Volley, and Thousand Cuts at level 90), spenders pop up to 3 Marks per monster for big damage (Eviscerate from level 12, Dagger Storm on a group, and Phantom Rush at 100, five dashes from back to back). Feint, Ambush and Smoke Bomb expose monsters, Smoke Bomb's vanish hides you from every monster but bosses, and Evasion dodges hits.
- Nightblade stances, once promoted: Lightning Reflexes (your basic attacks come 25% faster, but you take 10% more damage) or Substitution (every hit has a 12% chance to miss you, but you deal 5% less damage).
- From level 51 the Nightblade has its own mastery tree with three paths, Shadow (exposing and vanishing), Storm (lightning that your spenders discharge) and Edge (bleeds and fighting face to face), crowned by the Shadowdancer, Stormblade and Duelist capstones.
- Nightblade gear: daggers and offhand daggers drop from monsters from the early levels up to Ferumbras, and the endgame swords (soul, sanguine, moonsilver and more) come as Nightblade daggers when a Nightblade gets them. Nightblades wear the Paladin's lighter armour; its most important pieces have shadowed versions with sword fighting instead of distance. Five Nightblade sets add bonuses to backstabs, Exposed and Phantom Rush.
- The Nightblade has its own Wheel of Destiny, with its own spells and two revelations, Death Blossom and Avatar of Shadows. Nightblades heal with the Knight's healing spells, drink the same potions as Reavers and summon the Paladin's familiars for now.
- Reaver masteries: two new nodes for your abomination. Rotting Aura makes it damage every monster next to it every 2 seconds while you fight. Flesh Cleaver turns every third hit of your abomination into a cleave that hits harder and also hits the monsters in a cone behind and beside its target.

### Changed

- The Cyclopedia badge for having every vocation on your account now also needs a Nightblade: accounts that had it lose it until a Nightblade on the account reaches the required level.
- New music plays in the launcher and on the login screen: Fireside ballad nightblade.
- The launcher and the login screen show new artwork: Nightblade launch.
- Gear that comes in a Knight and a Reaver version now drops in the version for whoever gets it: a Knight always gets the Knight piece and a Reaver the harrowed one. Monster loot follows the corpse's owner, boss rewards and reward bags the player who gets them. Gear you carry also switches to your vocation's version when you log in, in both directions, keeping all its bonuses and upgrades.
- Reaver weapons now gain weapon proficiency as fast as Knight weapons.
- Reaver, Blight Stance: the poison is stronger and faster, a quarter of each hit over 4 seconds (was 15% over 6 seconds), so it pays off before monsters die. When a poisoned monster dies, every stack of its poison now jumps to the 2 nearest monsters, instead of one stack to one monster.
- Reaver, Bone Ward: the ward now soaks 40% of every hit for 10 seconds until it has absorbed its full amount, instead of eating whole hits at once, so it lasts through a fight instead of one or two hits.
- Reaver: players and monsters can now walk through the Raise Abomination undead; it no longer blocks corridors.
- Reaver, Raise Abomination: your abomination can no longer be hurt or killed and no longer runs out of time. It stays with you until you die or log out (or leave it far behind). Monsters ignore it, so it cannot tank for you. Feeding it Souls still makes it stronger up to 20 growth; each growth adds a little less damage than before because it no longer resets.
- Reaver, Withering Wave: the wave now starts on all 3 squares in front of you, so it hits the whole front of a group of monsters instead of just the one straight ahead. It is a little stronger, deals 10% more for every other monster it hits (up to 40% more), and every monster it hits deals 10% less damage for 5 seconds (5% for bosses).
- Reaver masteries: Grave Pact (a longer-lasting, tougher abomination) is gone now that the abomination never dies, and Flesh Cleaver takes its place. All Reaver mastery points are refunded once when you log in, for a free respec.
- Small client updates through the Launcher are now much faster. Game files that did not change are no longer copied and checked twice, so a minor patch takes a few minutes or less instead of up to 20. The Launcher updates itself to this version first.

### Fixed

- Reaver, Blight Stance: a monster dying with several poison stacks now spreads all of them, not just one.

<!-- /vestara-client:0.16.0 -->

<!-- vestara-client:0.15.0 -->
<!-- source-archive-sha256:c14eed90032a7fbae9e5b286039d1633bee8babe9840a8366762dc6cf4445769 -->
<!-- source-content-sha256-v1:5934d9202818e0a29a4c3557302dba2bdf527c8a9016ba8d55ed29ba905a55e0 -->
## 0.15.0 — 2026-11-06

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.15.0)

### Added

- Immersive layout: a new "Immersive panel opacity" slider in Options \> HUD makes the windows, minimap, equipment, panel buttons and chat see-through (30% to 100%), so they block less of your view. The action bars and the health and mana bars stay solid, and the classic layout isn't affected.
- New raid: \*\*Ashes of Ferumbras\*\* (level 400+, up to 5 players, weekly reset). Join it from Dungeons & Raids. Ferumbras walks in to greet you before the fight begins. Bring a Knight or Reaver to hold him, keep moving out of his marked attacks, and when he chants EXEVO GRAN MAS OPUS, only the tiles right behind the pillars are safe. Rewards include level 300-500 gear for your vocation and a very rare Ferumbras' hat.
- Ferumbras achievements: beat him fast, with a small party, without a tank, or without being hit by a single marked attack; survive his ultimate again and again, outrun his seeking orb, and win his hat. Two more are secret.

### Fixed

- Immersive layout: a window you open on the right (or left) no longer appears hidden under the side action bars. The side bars now move beside the windows as soon as a window opens in an empty side panel, and back when the last one closes.
- Gale Slash's second slash now deals your weapon's element too (for example fire with a fire sword), just like the first slash, and your gear and Wheel bonuses for Front Sweep now count for it as well. Before, it was always plain physical.
- Quivers and a few starter items no longer list "Nones" among the vocations that can use them; quivers now just say paladins.

<!-- /vestara-client:0.15.0 -->

<!-- vestara-client:0.14.0 -->
<!-- source-archive-sha256:d867acfb69ae750d4448a0af99da4fd33a8f8dbe7720e3714e0690a67cec0945 -->
<!-- source-content-sha256-v1:5bd9506e66a61f07275b011ae9f717676a3569e29bf3088358d78d7603834c20 -->
## 0.14.0 — 2026-11-05

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.14.0)

### Added

- 11 new outfits in the store, each with both addons and for 750 coins: Northland Raider, Orbweaver, Snowmane Champion, Lizard Masquerader, Hooded Sellsword, Bone Shaman, Nightwing Knight, Pelt Hunter, Emberwing Ascendant, Gloomwing Duelist and Nightveil Assassin.

### Changed

- Reaver masteries no longer tie you to one stance. Lingering Chill and Frostwarden now also slow monsters outside Rime Stance, Virulence and Blightbringer also poison outside Blight Stance, Frostwarden's and Blightbringer's other effects, Permafrost (on monsters you slowed) and Contagion work in every stance, and Soulreaper starts at 10 Souls in any stance, with its life leech (changing stance no longer ends the Reaper form). Each path is still strongest in its own stance.
- All Reaver mastery points have been refunded once, so you can rebuild your tree for free with the new rules. You get a message about it at your next login.
- The Reaver's Soulreaper form now turns you into the Duskwing, with Shadow Smoke Wings, instead of the violet Grim Reaper.
- The Duskwing outfit has been removed from the store. It is now reserved for the Soulreaper form, so characters who owned it no longer have it as an outfit.

### Fixed

- Rain, snow and the other weather now also show on house roofs and on the ground right around houses when you're outside. Before, the roofs and a strip of one or two squares around many houses stayed clear.
- A new character no longer starts with another character's action bar. With per-character hotkeys, its first bar now comes from its vocation's default (or starts empty).
- Four of the new store outfits (Pelt Hunter, Emberwing Ascendant, Gloomwing Duelist and Nightveil Assassin) can now actually be bought and worn. Before, the server didn't know them.
- Fixed a game crash that could happen when an elite or mythic monster with its glowing outline came into view, for example after changing floors.

<!-- /vestara-client:0.14.0 -->

<!-- vestara-client:0.13.1 -->
<!-- source-archive-sha256:9b6c0aabc1a7ea359c8ebf78fcdb5fb4f4471aa82df7e9e17c32ad304edee529 -->
<!-- source-content-sha256-v1:448308e7412e56ee06ad4a6716cb9d047464eb76cb9d6f32a639065ea4588b3c -->
## 0.13.1 — 2026-11-05

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.13.1)

### Changed

- For the Reaver's launch week, the launcher plays a Reaver version of the Fireside Ballad too.

### Fixed

- The launcher's animated wallpaper no longer flashes black for a moment when its animation starts over.
- Every bag you covet can be opened now. Some bags looked and were named the same as the normal one but were a different item, and nothing happened when you used them.

<!-- /vestara-client:0.13.1 -->

<!-- vestara-client:0.13.0 -->
<!-- source-archive-sha256:fac31ae079fe659a0700ac1d8bf8f7815be7f76b135913a0f9d3396a0713b57f -->
<!-- source-content-sha256-v1:cccd24c98d5cbcd35a35a7b3d4f895ee5f567177018a440715fe883616b5480c -->
## 0.13.0 — 2026-11-05

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.13.0)

### Added

- A new vocation: the \*\*Reaver\*\*, chosen at the Oracle and promoted to \*\*Harbinger\*\*. Reavers fight up close with a sword (one-handed with a shield, or two-handed), mixing steel with dark magic: every swing and kill gathers Souls to spend on heavy strikes, and Souls can raise a stitched abomination that fights beside you.
- Once promoted, a Reaver picks one of three stances that changes its element: Grave (death and life leech), Rime (ice that slows monsters) or Blight (earth poison that spreads); picking a stance locks the other two for 15 seconds. From level 51 the Reaver has its own mastery tree, with the Soulreaper, Frostwarden and Blightbringer capstones.
- Reavers use Knight swords, shields, armour and jewellery and the gear Knights and Paladins share, and can roll their death, ice, earth and magic bonuses on swords. They have their own spell icons, their own Wheel of Destiny (the Knight's layout with Reaver spells, the Reaper's Toll and Avatar of Souls revelations, and the Knight's guardian gems), a "Hide reavers" button in the battle list and a familiar wrapped in soul wisps. The Knight spell trainers teach Reaver spells.
- Reavers get their own endgame gear: "harrowed" versions of the soulcutter, soulshredder, soulwalkers and soulbastion, the sanguine blade, razor (both also grand) and legs, and the moonsilver battle visor, epee and claymore (also stellar). They're black and grey with a green glow, only Reavers can wear them, and their spell bonuses name Reaver spells (Soul Harvest, Soul Rend, Avatar of Souls).
- The Knight versions of these pieces are Knight-only from now on; any a Reaver already owns turns into the Reaver version on login, keeping its bonuses and upgrades. Wherever the Knight piece drops, the Reaver version takes half of its chance.
- The harrowed pieces have their own set bonuses: \*\*Harrowed Soulbound\*\* (2 pieces: dropping below 35% health spends all your Souls on a ward worth 4% of your maximum health plus 1.5% per Soul), \*\*Harrowed Sanguine\*\* (2 pieces: sword hits can rend, giving an extra Soul and a wound in your stance's element) and \*\*Harrowed Moonsilver\*\* (2 pieces: your abomination deals 25% more damage, its hits can crack a line through the ground in your stance's element, and kills near it make it grow).
- Weather now changes across the world: sunny days, drizzle, rain and the occasional thunderstorm in the cities, heat haze and sandstorms in the deserts, snow and blizzards where snow lies on the ground, and lasting fog over the Plains of Havoc, the Ghostlands and the swamps. Rain and snow stay outside, never inside buildings. You can switch weather off completely, turn the effects down, switch off lightning flashes and set the weather volume under Options \> Graphics \> Effects.
- A new coin: the \*\*crystal ingot\*\*, worth 100 crystal coins (1,000,000 gold). It weighs only 1.00 oz, far less than the 10.00 oz of 100 crystal coins, so carrying and trading large amounts of gold is much easier. Use a stack of 100 crystal coins to turn it into an ingot, or use an ingot to change it back. Your gold pouch turns 100 crystal coins into an ingot by itself, bankers and shops pay out large sums in ingots, and you can pay with ingots anywhere you can pay with coins.

### Changed

- For the Reaver's launch week, the login screen plays a Reaver version of the Fireside Ballad.
- To celebrate the Reaver's arrival, the launcher and the login screen show new animated Reaver artwork for the launch week.
- Kinetic Armor now builds up against weak monsters too: every monster hit that lands stores at least 4/5/6% of your shield power (by rank), so a few weak hits are enough for a full wave. The wave's limit is unchanged, so it hits bosses no harder.
- If the game crashes, it now always writes a crash report and tells you which two files to send to the team, so crashes can be found and fixed.
- The Master Class badges now need a character of every vocation on the account, Monk and Reaver included.

### Fixed

- The sanguine legs' Fierce Berserk critical damage bonus now works. A spelling mistake meant it never applied.
- Reward bags (Bag You Covet, Bag You Desire, Primal Bag) always open now. If the reward can't get a rarity, you still receive the item instead of an "unavailable" message.
- Elite and mythic monsters no longer lose their outline and \[ELITE\]/\[MYTHIC\] tag after you change floors or walk out of view and back.
- The basket with puppies from Tom Govern's quest can now be moved and carried. If you finished the quest but never got to keep the basket, Tom gives you one the next time you talk to him. The Zaoan chess box that couldn't be picked up can now be carried too.
- The character list now always names Monks, Exalted Monks, Reavers and Harbingers correctly.
- Monks can now use lightest magic missile runes, like every other vocation.
- Animated wings and other back cosmetics no longer stand still when you face certain directions.
- Monks can now do the Elemental Spheres quest: Arkulius gives them the energy sphere mission and the gem machine accepts their amethysts, like for Knights.
- The Wheel of Destiny's default preset and preset sharing, and the weapon proficiency window's vocation check, no longer break after the Market has been loaded.

<!-- /vestara-client:0.13.0 -->

<!-- vestara-client:0.12.0 -->
<!-- source-archive-sha256:1ce67149058bf73c6774f2e9621da1569ca1c97a1d77af423612fae9a9a84b3c -->
<!-- source-content-sha256-v1:a6171c35599c31a5717a869fe16bfc7a2c629bedb7485b866696c87640ec8e23 -->
## 0.12.0 — 2026-11-04

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.12.0)

### Added

- Quick loot can now loot items from your skipped list anyway when they drop at a rarity you choose, and an 'Always loot rarity' setting loots anything at or above that rarity, whatever your loot list says.
- Hovering an item or spell on the action bar now shows its tooltip: item details, or the spell's words, level, mana, cooldown and what it does.
- Spells can now be dragged from the spellbook onto multi-action buttons and onto hotkeys in the Hotkeys window.
- The character list now shows the level a character logged out with, plus how many levels it gained since you logged in.

### Changed

- Monks can now take the Knight's place in old quests built for one player of each of the four classic vocations: the Desert Dungeon, the Elemental Spheres, the Pits of Inferno fire paths and the Kilmaresh vocation teleports.
- The server now saves and restarts every day at 10:00 (Central European time), with a warning every minute from five minutes before.
- Rare drops that have no rarity of their own, like the Bag You Desire, Bag You Covet, boss dolls and figurines and mount items, now show in the mythic loot colour so they stand out.
- Dragging an action bar slot onto another slot now swaps the two (also between bars, and multi-action buttons as a whole) instead of overwriting it. Hotkeys stay on their slots.

### Fixed

- Some boss and monster attacks used to skip Monks entirely. The special attacks of Gaz'haragoth, Tenebris, Eruption of Destruction and Prince Drazzak now hit Monks too, and the skill-draining attacks of Lisa and Walkers now lower a Monk's fist fighting and shielding.
- Mawhawk's last-stand explosion ("Better flee now.") now actually hurts the players who stay close, as it should. Before, it never damaged anyone.
- The dead bureaucrats in the Pits of Inferno no longer stop talking when a Monk tells them their vocation.
- Opening the Achievements window no longer crashes the game.

<!-- /vestara-client:0.12.0 -->

<!-- vestara-client:0.11.0 -->
<!-- source-archive-sha256:021cbdcfefef94a05820ab9382fc07b395292f15cd003bf1b6276677069f18af -->
<!-- source-content-sha256-v1:5caf3bead7dffc50bcfd6213de073921b4713cc0798a229fd9243d36022a95b3 -->
## 0.11.0 — 2026-11-03

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.11.0)

### Added

- Right-click a monster on the map or in the battle list to add it to, or remove it from, your Bestiary Tracker.
- Weekend events: every weekend, from Friday's server save until Monday's, one bonus is active: +50% experience, double bestiary kills, +50% loot or 50% faster monster respawns. It is never the same bonus two weekends in a row.
- The spellbook now explains what each spell does when you select it or hover over it.
- Tutorial tips: new characters get short tips as they play, first the Tibia basics in Rookgaard, then Vestara's own systems on the mainland, including a card about your vocation's mastery paths. Tips point at the button they talk about, never block play and can be skipped.
- Options \> Interface \> Tutorial turns tips on or off for each character and replays them. Characters made before this update start with tips off, and a one-time card shows how to turn them on.
- Achievements: a new Achievements window (Progression buttons) with 130 achievements from Easy to Grandmaster, covering hunting, bosses, raids, levels and skills, treasure, item modification, fishing and a few secret ones. Each one gives achievement points, and unlocking one plays a pixel-art pop-up with a medal and a Tibia firework (Grandmaster, milestones and server firsts get a little extra).
- Achievement reward track: reaching point milestones unlocks small permanent bonuses (up to +5% hunting experience, +15 movement speed and +3% skill training), five new wings for the outfit window and six badges, from Bronze Leaf to Grandmaster Sigil.
- Kills you made before achievements existed count toward kill achievements for creatures with a bestiary entry, and your level, skills and bank balance count straight away.
- Feats of Strength: Beta Pioneer for everyone playing during the beta, and server-first feats for the first character to reach level 200 and 500, the first party to beat Ironjaw, and the first mythic and divine finds.
- Inspecting another player now shows their achievement points and badge.

### Changed

- Soul War "Bag You Desire" now drops more often, with improved rates across regular monsters and bosses.
- Bag You Desire and Bag You Covet now use stronger endgame rarity weighting (8% Legendary, 3% Mythic).
- Stellar Moonsilver weapons now have a base +12% critical hit chance.
- Stellar Moonsilver weapons now include light vocation spell bonuses (for example Brutal Strike, Ethereal Spear, Greater Tiger Clash, Ultimate Energy Strike and Ultimate Terra Strike).
- Stellar Moonsilver caster weapons gained extra elemental magic levels to strengthen their spell scaling.
- Moonsilver helmets now grant 7% resistance to all major damage types (physical, fire, energy, earth, ice, holy and death).
- Moonsilver helmets also received stronger vocation-focused flat stats.
- Critical hits now deal at most 1.8x damage (was 2.5x). Critical chance is still capped at 70%.
- Kinetic Armor now stores the damage of each hit as it comes in, before your armour and Guardian reductions lower it, so its waves hit harder. Each wave now clearly shows the whole star it hits: a ground shake on every tile, including the tips two tiles out north, east, south and west.
- Elite monsters now count as 2 kills towards the Bestiary, and Mythic monsters as 5.
- Empty potion flasks now vanish after drinking instead of filling your backpack. Type !flask off if you want to keep them (and !flask on to stop again).
- NPC shops now let you buy stackable items in large amounts at once (for example a full stack of 1,000), instead of at most 100 per purchase.
- Bag You Covet drops as often as Bag You Desire: 0.5% from Murcion, Chagorz, Vemiath and Ichgahal (the first three didn't drop it before) and 0.9% from Bakragore.

### Fixed

- Bag You Covet now keeps rerolling until it can apply a valid rarity-affix result, instead of failing the reward.
- Paladin Smites no longer land a second critical hit on top of an attack that already crit, so they stop hitting far harder than intended.
- Huntmaster's Arrow Volley now follows your target: every wave lands where the target is at that moment, instead of on the spot where it stood when you cast.
- Sets with a shield piece now count it as worn while you use a two-handed weapon from that set, so two-handed players can complete them.
- The Arcanist and Duskcloak store outfits now show the right look for male and female characters (they were swapped). If you own one, pick it again in the Outfit window.
- Spells, mastery effects and spell echoes no longer hit creatures on other floors or behind walls. Scorched Earth and Firewalker embers now only burn enemies standing on the burning ground.
- Backpacks and other windows in the side columns stay where you put them after logging out and back in, or restarting the game, in both the classic and immersive layouts.
- Moving back and forth in the Bestiary keeps you on the right page: going back from a creature returns to the list page you came from, and late or empty replies no longer replace what you are looking at.
- Charm point totals and charm prices now update straight away after unlocking, upgrading or clearing a charm, and the confirmation shows the real cost.
- Locked doors in Cobra Bastion, the Falcon Bastion castle, Bounac and the true asura area are now unlocked for everyone.
- Holding Shift over a backpack now compares it with the backpack you wear, like other gear. Necklaces and rings already compare.
- Looking at an item on the ground (Shift+click) now also shows its tooltip, like items in your backpack.
- Affix gems and other items without stats now show what they do in their tooltip.
- Fixed the interface sometimes staying greyed out until you restarted the client.

<!-- /vestara-client:0.11.0 -->

<!-- vestara-client:0.10.0 -->
<!-- source-archive-sha256:a0a80be10f395beffd2d944d865b3914cd2c449832c77f6ff78c695d1d907c52 -->
<!-- source-content-sha256-v1:c1c98c1e963e6d52b270c002ffd36031333c9fa1d85c2c960eb6b9c83479c084 -->
## 0.10.0 — 2026-10-31

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.10.0)

### Added

- Knight masteries: a new Guardian path. Kinetic Armor stores part of the damage you take while you guard with Protector and a shield, then releases it in a wave around you. The Unbreakable capstone makes you much harder to kill for a few seconds and lets your swings taunt.
- Monks now have a mastery tree with three paths built on the Virtues: Tiger (Justice) for fast clawing attacks that make enemies bleed, Water (Sustain) for healing and shielding your party, and Dragon (Harmony) for strong spenders and area bursts. A Balance column adds dodging, a more forgiving Serene and stronger heals.
- Monk capstones: Tiger Spirit (Tiger's Fury: faster attacks, and claws that hit every enemy next to you), Spirit of Water (stronger party heals and shields; Sustain counts as Serene in a party) and Dragon Ascendant (a spirit dragon strikes your target and every enemy around you). Each gives an inspect title: White Tiger, Tidecaller or Grandmaster.
- Monk spell arts: Double Jab becomes Tiger Rake (the target bleeds), Mystic Repulse becomes Tidal Palm (shields you and allies next to you) and Devastating Knockout becomes Dragon Fist (roots the target at 5 Harmony, not bosses). Spell arts cost 15% less mana.
- The stack display now shows Monk Rend and Tiger Spirit's Ferocity.

### Changed

- Knight masteries have been reworked into Blood, Tempest and Guardian paths plus the Iron column. Eldritch Knight and the weapon-specific specialisations are gone. All Knight mastery points have been refunded.
- Knight masteries: Row II is now a choice of one technique (Blood Burst, Cleave or Kinetic Armor), and Row III a choice of one fighting style (Relentless, Precise or Steadfast).
- Cleave now hits a U shape in front of you: harder beside your target, lighter beside you, and never behind you.
- Gale Slash is now a double slash: in front of you, then behind you a second later.
- Spinning Assault is now a single spin that makes everything it hits bleed.
- Gathering Storm no longer releases a burst. A full Storm starts Windfury instead.
- Retaliation now strikes back at your target only.
- Blood Burst now goes off every 2nd hit on a bleeding target and hits harder.
- The Protector stance now lowers your damage by 5% instead of 15%.
- The old Monk masteries (Attack Speed, Life Leech, Reflection, Heal Echo) are replaced by the new Monk tree. All Monk mastery points have been refunded.
- Monk weapons now roll the stronger two-handed weapon bonuses (attack and critical), since Monks can't use a shield. This applies to newly rolled bonuses.

### Fixed

- Monk: Spiritual Outburst's second hit at 5 Harmony now keeps the Harmony bonus.
- Monk: a Spell Echo of a Harmony spender now keeps the Harmony of the original cast.
- Monk: basic attacks now trigger set effects meant for every vocation (for example the Pirate set's Cutlass Trick).
- The Ethereal Monk set now gives +4% healing received, and the Orange Plasma Resonance set +2% basic fist damage, as described.

<!-- /vestara-client:0.10.0 -->

<!-- vestara-client:0.9.0 -->
<!-- source-archive-sha256:835dac7f40919c9372de3ac16aef0f66c6da4048a997972b645e22faffd871e7 -->
<!-- source-content-sha256-v1:66daa3917fd46022d1fcfc44f890edad7989ea50abaf7d27e41baa00719f01c9 -->
## 0.9.0 — 2026-10-31

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.9.0)

### Added

- Discord now shows "Playing Vestara" on your profile while the game is open, with your character's name and level once you log in, and what you're hunting or which town you're in. This needs the Discord desktop app, with activity sharing turned on in Discord's settings.
- The UI size setting (Edit layout and Options) can now make the interface smaller, down to 0.8x, for 1080p screens.
- New Sorcerer spell Meteor Storm (exori mas flam) for the Firewalker capstone: meteors rain down on your target for 3 seconds and set enemies burning.
- Oskayaat and the Murky Caverns beneath it are now full of monsters: werepanthers, weretigers, werecrocodiles and more.

### Changed

- The affix stones now each have their own colour so you can tell them apart at a glance: Resonance Gems are teal, the Affine Exchange Gem is pink, the Alloy Reforge Gem glows orange and the Rarity Ascension Sigil is gold.
- Divine items roll their bonuses a little higher, so a divine roll is never below a mythic one. Divine items you already own are raised to match, keeping how good each roll was.
- Knight masteries reworked to match the other vocations: Row II is now Open Wounds (more damage to bleeding enemies), Cleave, Withering Edge and Retaliation, and you can take all of them. Blood Burst and Soul Harvest moved down next to their capstones, and Bloodletter is gone. The capstones are unchanged. Your Knight mastery points have been refunded, so open the Masteries window to spend them again.
- Small interface text has a little more space between letters and numbers, so it is easier to read.
- Sorcerer burns now stack up to 6 times (8 with Pyromancy) instead of replacing each other; stronger fire spells add more stacks, and every new stack keeps the burn going.
- Firewalker makes your burns stronger, so standing in your embers hurts more.
- Tempest now crashes two bigger lightning bolts down every half second, with a heavier storm around you.
- Grimvale's full moon werecreatures now roam there every day.
- Deeper Banuta is open to everyone: the Blind Prophet takes you to Banuta and the deepest catacomb no longer needs the amphoras broken.
- Buddel always sails where you ask, so Tyrsung and the other Svargrond islands are always reachable.
- The Asura Mirror to the true asuras only needs level 250.
- Hairycles no longer gives the Shaman outfit.

### Fixed

- Moonsilver set effects such as Moonfall's starfall and Falling Star now actually damage the monsters they land on.
- Very long item tooltips, such as divine items with 7 bonuses, now fit on screen by spreading into two columns.
- Eldritch Knight: dying as the Harbinger no longer carries the form or your Souls over into your next login.
- Boss reward chest equipment now rolls a rarity (uncommon to mythic) like gear from normal monsters, with the boss bonus to rare odds.
- Fixed a server crash that could happen while monsters picked targets during busy fights.
- Fixed some quest chests (In Service of Yalahar, Royal Rescue and others) giving an error instead of their reward.
- Buff icons over characters no longer cover the skull, guild and summon icons.
- Large numbers in the Skills window (experience, hit points and the like) are no longer cut off.
- The Skills window can now be stretched to the full height of a side panel.
- Sealed doors that blocked hunting grounds now open: the Kilmaresh ogre cave and the catacombs below it, the Vengoth castle rooms, and several Yalahar side rooms.

<!-- /vestara-client:0.9.0 -->

<!-- vestara-client:0.8.3 -->
<!-- source-archive-sha256:1b93348be514774c567ba15d682110f62c332cb6bd7ef3d36798e1c1565c255d -->
<!-- source-content-sha256-v1:8376ba9a17fffe872e385099418c0ddce7287233aae5bd561834b53e317cf260 -->
## 0.8.3 — 2026-10-31

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.8.3)

### Changed

- Eldritch Knight: every melee swing and every kill gives a Soul. At 10 Souls you become the Harbinger, a Grim Reaper whose swings reap every enemy around you. The form also gives more damage, health, movement speed and life leech for 8/10/12 seconds. Kills during the form keep it going and summon the spinning Reaper on each victim.
- Soul Harvest: every 4th melee swing now releases a Soul Nova of death damage on every enemy next to you. You no longer need kills or Souls to trigger it.
- Cleave: hits the 2, then 4 tiles beside your target, then every tile around you at rank 3, all for 15% of your swing. The Masteries window shows the tiles again, and Cleave no longer hits in an L shape.
- Bloodletter: your attack spells now make every enemy they hit bleed, as the description says.
- Blood Frenzy is simpler: bleeds +20/30/40%, and the crimson Frenzy now gives +10/15/20% attack speed while it lasts, then ends in Rupture. Hemorrhage and the other small bonuses are gone.
- Blood Burst: every 3rd hit on a target bleeding from you bursts its blood onto the enemies around it. It no longer needs a bleeding enemy to die.
- Twin Cut: each sword swing has a 25% chance (33% at rank 2) to strike your target again, at 60% with a two-handed sword or 45% one-handed. It no longer chains.
- Earthshatter: Concussion now builds on you with every club hit, whatever you hit, so it isn't lost when a monster dies before the Shatter.
- Executioner: one-handed axes now execute and splash at 60% of the two-handed values, instead of higher than rank 1 two-handed.
- Withering Edge: your hits Wither the target, so it deals less damage and takes more damage from you. No more poison.
- Reaping Sweep: Exori's dark crescent hits 10% harder and heals you for part of the damage.
- All Knight mastery points have been refunded so you can try the new builds.

### Fixed

- Knight: fixed a bug where Knight area effects could set each other off over and over in a big pack and stall or crash the server.

<!-- /vestara-client:0.8.3 -->

<!-- vestara-client:0.8.2 -->
<!-- source-archive-sha256:a85c3dc5fce150b89eaadcc9af037f098b99c6b0fb489f5f6065a68178a57dcc -->
<!-- source-content-sha256-v1:6c7759e97e0b9e212e4da075de084ee1576d6ebf80729fccc55551bc06926562 -->
## 0.8.2 — 2026-10-30

Client update

[Release and downloads](https://github.com/Vick-Tibia/vestara-downloads/releases/tag/client-0.8.2)

### Changed

- Unfortunately Vince, definitely not Dave, massively broke the Knight masteries, so I have had to undo the damage he did to save you all from One Punch Knights one-shotting the very universe as we know it.
- Knight masteries: a big power pass that brings Knights in line with the other vocations. The masteries now add to the Elite Knight's own spells and swings instead of burying them. There are fewer and smaller area effects, and extra swings no longer set off area effects. Your Knight mastery points have been refunded.
- Knight capstones (Blood Frenzy, Windfury, Eldritch Knight) now cost 5/9/13 points, the same as the other vocations' capstones.
- Twin Cut: at most two cuts (60%, then 45% with a two-handed sword), and only on your target. Crossing Cuts, Flourish and the Gathering Storm link are gone.
- Windfury: shorter chains (up to 4 swings) on your target, plus +4/7/10% attack speed. Every chain now ends in a Gale Burst that hits the enemies around you, and it grows with every swing in the chain. At rank 3, a full chain becomes the Eye of the Gale for an even bigger burst. Gale Edge and Cyclone are gone.
- Gale Slash is now a single whirlwind around you with no vortex or pull. Reaping Sweep no longer hooks enemies. Exori Mas (Seismic Wave) is the Knight's gathering spell.
- Eldritch Knight: smaller Reaper's Arc and Toll. Kills give 1 Soul, plus 1 for every 5th hit. The Harbinger lasts 5/6/7 s and reaps at 40%.
- Blood Frenzy, Blood Burst, Cleave, Soul Harvest, Gathering Storm, Retaliation, Executioner, Earthshatter, Bloodletter, Lacerate and Spinning Assault have lower values. Soul Nova and the Storm burst now hit only the tiles around you. Open the Masteries window to see each node's new numbers.

### Fixed

- Knight: Gathering Storm, Windfury and Twin Cut no longer pile area hits and animations on top of each other in packs.
- Mastery tooltips now wrap long text instead of running off the screen.
- Immersive layout: no more black bars at the sides of a maximised widescreen window. The map now fills the window edge to edge and still shows all 13 rows.

<!-- /vestara-client:0.8.2 -->

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
