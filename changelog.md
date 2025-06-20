WIP

Nothing in here is guaranteed; all is subject to change. Not save safe. Release date unknown.

Version 8.1.0

**PATCH NOTES**

- Moved or removed 40 trees.
- Fixed Miraak's vanilla skin being flagged as Playable when it shouldn't be.
- Edited Gaulur Amulet (and all three fragments) to use Awesome Artifacts enchantments instead of TAS enchantments - this should fix the issue of the amulet aggroing some NPCs (TAS had unconditioned magic effects to drain health, stamina, and magicka).
- Patched Peryite Shrine for Wintersun, Only Cure Quest Expansion, and Daedric Shrines AIO.

---

**REMOVED**

- Andromeda - Unique Standing Stones of Skyrim.
- Bruiser - Hand to Hand Skill Tree.
- Blood and Silver - Cidhna Mine Expanded.
- CC Myrwatch - Tweaks and Enhancements.
- Celestine.
- Custom Skills Merged.
- Dialogue History.
- Enhanced Blood Textures.
- Imperious - Races of Skyrim.
- Indigo.
- Morthal Barrow.
- Northern Raven Rock.
- Orpheus.
- Practical Necromancy.
- Redbag's Rorikstead.
- Savvy's Tel Mithryn.
- Scoped Bows.
- Water For ENB.

---

**UPDATED**

- Community Shaders.
- Dragons Use Thu'um.
- Nature of the Wild Lands.
- Occlusion for Quest Mods.
- Stronger Potema - Wolf Queen Boss.
- The Taste of Death - Quest Addon.

---

**ADDED**

- A Horse's Life.
- Aljo's Vigilant Tweaks.
- Alt-Tab Stuck Key Fix NG.
- Animation Ledge Block NG.
- Apocalypse - Silmane's Spell Sentinel Auto Dispel and Fixes.
- Attack Animation Fling Fix NG.
- Auri VIGILANT commentary patch tweaks.
- Azurite Weathers III - Enhanced.
- Better Watercolor and Transparency for Realistic Water Two.
- Bleeding Damage Fixes.
- Blended Skills - Class Perks.
- Bow Charge Plus.
- Bow Charge Plus and Bow Rapid Combo V3 Dodge Shot Animation Patch.
- Bow Charge Plus Velocity fix.
- Bow Rapid Combo V3.
- Bow Rapid Combo Bow Charge Shot Custom Skill Tree.
- CAM - Companions at Mirmulnir.
- Cancel Attack SKSE - Balanced Settings.
- Combat Pathing Revolution AE.
- Considerate Followers - Followers are Silent During Dialogue.
- COTN Falkreath - RW2 5.0 Patch.
- Custom Skills - GLENMORIL.
- Custom Skills - HandToHand.
- Custom Skills - Unarmoured Defense.
- Daedric Shrines - All in One.
- Daedric Shrines - Wintersun Patch.
- Dawnguard Perk Tree.
- Death Drop Overhaul.
- Death Idle Fix.
- Denji - Custom Skills Menu for CSF v3.
- Draw Fix - Move Equip Animation Fix.
- Expanded Mastery Perks for Ordinator.
- Freyr - Integrated Standing Stones of Skyrim.
- HAG - Occult Cradle Stone Tower.
- Hammering Animation and Sound Fixes.
- Hot Key Skill.
- Hammering Animation and Sound Fixes.
- Inertia (Floating Gear Fix).
- Invisible Rune Explosion Fix.
- Logical Rope Bridges - Suspension of Spans.
- Mannaz - Integrated Races of Skyrim.
- Mannaz - Useful Races Descriptions.
- Media Keys Fix SKSE.
- Nature of the Wild Lands - Animations Addon.
- Ordinator - Combat Styles.
- Orc Stronghold - Dushnikh Yal Occlusion Addon.
- Orc Strongholds - All In One.
- Orc Strongholds - All In One High Poly Head patch.
- PAN - Nameless Vampires SE.
- Persistent Favorites.
- Quest Journal Limit Bug Fixer - Recover Disappeared Quests.
- Realistic Water Two.
- Realistic Water Two Forge Water for Elysium Estate - Patch.
- Remove Orphaned Hazards.
- Sabre Cat Attack Animations.
- Sanguine Symphony.
- SD's Enairim Tweaks.
- Seagulls- Mihail Monsters and Animals (SE-AE version).
- SilverDeckel's Common Stuff.
- Stealth Detection Fixes.
- The Gildergreen Grows.
- The Royal Seat - A Noble and Upperclass Bench Chair and Throne Replacer.
- Water Not Metal.
- Wintersun - Faiths of Skyrim.

---

2025/04/26

Version 8.0.6

**Please note: You will once again have a Missing Master warning when you load up your save. This is expected and perfectly fine. The plugin was 100% overrides and has been fully replaced. This will not harm your game in any way.**

- Moved or removed 22 trees. (`Liv_NOTWL_Treetrim`)
- Removed one hanging moss. (`Liv_NOTWL_Treetrim`)
- Removed one beehive. (`Liv_NOTWL_Treetrim`)
- Added patch for RS Children and Beyond Reach. (`RS Children- Beyond Reach Patch SE`)
- Added patch for RS Children and ETAC - Darkwater Crossing. (`RS Children Patch Compendium FOMOD`)
- Added Avanchnzel Dwemer Piston Sound Hotfix.
- Created new patch for Armory of the Dragon Cult (recent SPID update broke distribution; patch created to manually create and distribute leveled lists to Dragon Priests).
  - This fix is not retroactive. You'll need to use the console to obtain missed gear from priests you've defeated previously. Sorry.
  - Also I haven't really tested this, so let me know.
  - (`Liv_DragonPriestArmory_INAMinsteadofSPID`; patch added to `LivPatches` Loot group).
- Added `No Respawn` flag to Thieves Guild Storage Cabinet door in the Ragged Flagon (will prevent door from re-locking itself if player is gone for 30+ days) (`Liv_NLIThieves_Patchwork`).
- Added lock levels to five training chests in Thieves Guild Cistern (`Liv_NLIThieves_Patchwork`).
- Capitalized location name for Salt Marsh Watch from The Marshlands (Fix merged into `WT Final Marshlands Tweaks`).
- Added Practical Necromancy to FLM file to allow for perk points to be refunded from this Custom Skill tree when using a Scroll of Legends (added to `Perk Refunds Affects Custom Skills - Ordinator`).
- Fixed issue where Aetherium Ingots could not be smelted (classic Lively move - there's two mods that add Aetherium ore & ingots, and I disabled both, probably with the intention of choosing which one to use later, edited all the cobjs to use the same ore & ingots for consistency, then never re-enabled a way to craft the appropriate ingots).
- Fixed a number of cell overrides not forwarding Lux changes (new patch: `Liv_LuxOverrides`; added to `LuxPatches` Loot group). (Note: not all cell changes made to this plugin, only cells that didn't previously have a custom patch by us).
- Moved a number of LotD displays out of locations which you can never return to after clearing.
  - Orc Head in a Jar moved from Skuldafn to Narzulbur Mauhulakh's Longhouse.
  - Jade Priest Statue moved from Skuldafn to Shroud Hearth Barrow.
  - Jade Lady Statue moved from Japhet's Folly to Markarth's Shrine of Talos.
- Moved two collectible items in Darklight Tower to more accessible areas (new patch: `Liv_DarklightFixes`; added to `LivPatches` Loot group).
- Edited the Change Looks spell that I can't remember the name of from Odin to not have a green glow on the character, made by request. Merged into `Lively's Tweaks.esp`.
- Fixed translation issues in `RimImpactOfMod.esp`. Includes direct edits to plugin file. Should hopefully fix invisible diseases and debuffs.
- New patch: `Liv_RimImpact_AutomatonGlow`; added to `LivPatches` Loot group.
- Fixed landscape issue at Varlais Cavern (cell `16, -26`).
- Added `uInterior Cell Buffer=0` to `Skyrim.ini` under the `[General]` section.
  - Ra2Phoenix suggests this may help with the occasional crash-on-load deal, and he is smarter than me, so let's try it out!
- New Synthesis outputs.
- New step in MCM Recording (to add default Hotkey for Inquisitor-Warlock, `N`). Adjusted Hotkey Reminder (`F11`) accordingly.
- Updated Patreon credits. (*so many cancellations lately*).

Known issues I didn't feel like fixing yet:

- Black face bugs on children NPCs in Karthwasten.
- Black face bug on a few select NPCs (`19970`, `1996C`, `3300E`, `020176FB`).

Known issues that won't be fixed until next save-breaking update:

- Cidhna Mine guards can be permanently hostile. Will remove Cidhna Mine Expanded in the future.
- Dovahzul words involving Fire, Frost, and Ice can say `Fiik` instead of the actual word. No other issues seem to arise from this. Most likely culprit is Dragons Use Thu'um. Cannot update this mod mid-save.
- Myrwatch quest objectives don't appropriately forward changes (purchase from Tolfdir instead of casting the fire spell on the rune). This is confusing and, frankly, unnecessary for Tempus. Will remove CC Myrwatch Tweaks & Enhancements in the future.
- Morthal Barrow will be removed due to use of AI voice. I originally thought this was voice splicing, which is more of a gray area; I was mistaken.

---

2025/04/14

Version 8.0.5

Changed version of curios from Steam to Creation Club. That's it.

---

2025/04/14

Version 8.0.4

- Moved two new patches mentioned in 8.0.3 from `Overwrite` to `Lively's Patches`. Classic dumbass Lively.
- Removed CK dependency, again, hopefully, god I hate this thing. Did you know that if I set WJ to ignore every individual CK-related file in Stock Game, it still tries to pull all that stuff into the compile anyway? Did you? I have to delete all the CK stuff from `steam/steamapps/` in order to get WJ to stop trying to include the CK stuff. IT'S GREAT. DO YOU KNOW HOW OFTEN I HAVE TO REMOVE AND REINSTALL THE CK
- The rest of 8.0.3's changelog still applies, please read it.

---

2025/04/14

Version 8.0.3

- Deleted 7 trees, a juniper bush, and a tree stump.
- Deleted a tankard.
- Fixed markdown errors in Blue Dartwing and Bleeding Crown bestiary entries.
- Added Vlindrel Hall - Mystic Condensor Patch (710). Patch added to Loot Group `WTPatches`.
- Added Vlindrel Hall - Distinct Interiors Patch (710). Patch added to Loot Group `WTPatches`.
- Fixed floating fire in MarkarthExterior01 (`Liv_MarkarthEntrance_Fixes`).
  - Added `Liv_MarkarthEntrance_Fixes` to LivPatches Loot Group.
- Fixed two misaligned objects in MarkarthExterior01 (`Liv_MarkarthEntrance_Fixes`).
- Fixed a small gap in a wall in SalvisFarmExterior01 (`Liv_MarkarthEntrance_Fixes`).
- Moved Aleksey's Key to be more easily obtainable and hopefully prevent people from saying it's sunken into a chest (fix merged into `Lively's Tweaks`).
- Fixed landscape gap near Rorikstead (New Loot rule: `Redbeg's Rorikstead` - Load After `Landscape and Water Fixes - Patch - Farming`).
  - This leaves some floating grass where the gap was. Will have to rerun Grass Cache later. Honestly I probably won't do this for a while, since it's one pretty small area, and it takes a long time to rerun this output. Maybe next time I break saves, since I plan to change the water anyway.
- Fixed `RockCliff08.nif` having a darker blue texture than all other snow-covered terrain pieces.
- Deleted a floating lantern trap in The Rift from Lux Via. Why was it there in the first place? Nobody knows.
- Fixed hair and eyebrow meshes on Xander and Muiri.
- New EasyNPC Output.
- New Synthesis Outputs (all).
- Added No Respawn flag to Dark Ship jar at Solitude Docks (fix merged into `Lively's Tweaks.esp`).
- Removed Standing Stone Amulets from Madesi's vendor inventory.(New patch: `Liv_AmuletsofSkyrim_DontSellStandingStoneAmulets.esp` - added to Loot group `LivPatches`).
- Edited Elberon (Forgotten Seasons DLC) base NPC record to remove Dwarven Crown from Default Outfit, and added Dwarven Crown to Death Item via new LVLI record. Untested; hopefully will fix the issue of Elberon not having the Dwarven Crown on his corpse (New patch: `Liv_ElberonCrownFix.esp` - added to Loot group `LivPatches`).
- Removed a Mammoth Skull STAT that was clipped into a bridge in cell 4,2 (`mihailmammothbaby.esp`).
- Added MHIYH Custom Follower Exclusion FLM Patch.
  - *This was already in the list, but I put it on Nexus. Yay.*
- Added Edge UI - Centered Tween Menu.
  - *This was already in the list, but I put it on Nexus. Yay.*
- Added Melana the War Maiden's "Helgen, What Helgen" patch. Thank you for the suggestion, TobiDoes.
- Added Melana the War Maiden's "Heal Player" patch.
- Removed an old patch from when I was trying out Placed Lights instead of Lux.
- Updated Supporters list on the Main Menu. Thank you for your support! [Feel free to get your name in the credits as well.](https://www.patreon.com/c/nicholasjae)

**Please note:** You will get a missing masters warning on this update. This plugin did NOTHING. It was a dummy. Your game is fine. I promise.

---

2025/04/07

Version 8.0.2

- Deleted 18 trees.
- Fixed Better Bridges/Lux/CFTO dock in Cell -5, -14.
- Fixed Better Bridges/Lux Via area in Cell 21,-2.
- Fixed Old Hroldan Inn interior.
- New Synthesis-NPCs plugin to remove effect shader overrides from Imperious.
- New patches for Headhunter and Missives.
  - *Note: Made the Headhunter-LeveledRewards plugin full ITMs to prevent unwanted changes and to also prevent people from having missing plugins when loading saves. This will be removed on the next save-breaking update, whenever that may be.*
- New Synthesis-Fixes plugin.
- Edited perk description for Denting Blows to specify blunt weapon types (maces and whips).
- Edit spear animation moveset priorities to address spears using 1H sword animations.
- Added Celestine to NFF Exclusion Formlist INI.
- Updated Celestine to v2.6 (with Vigilant commentary).
  - *Note: you won't get the full experience of this if you've already done Vigilant.*
- Added LotD Window Fix.
- Fixed messed up textures on specific dwemer walls (hid file DweHallLg2Way01.nif from LotD Patches mod).
  - *Note to self & rule-11 people: when reinstalling LotD Patches Official, do not select Missives, Artificer, or Dwemer Pipeworks Reworked. They're all handled in our own way, and we do not need the LotD patch versions.*
- Fixed two floating trees in the Marshlands (Wartortle).
- Fixed single pass snow shader on Folgunthur (Wartortle).
- Fixed burnt down shack from Lux Via in cell -14, 27 (rotated and moved chest, four lanterns, bag, two safes, and a note to align with the floorboards properly; moved note on top of safe).
- Edited Hotkey Reminder to show the correct binding for RDO's Stop Combat hotkey (Numpad+).

---

2025/04/03

Version 8.0.1

Minor bug fixes found on stream.

- Fixed 11 tree placements (some moved, some disabled).
- Fixed horse stables in Whiterun outskirts (moved down -60 units on z axis).
- Fixed vanilla iron helmet (12e4d) model (bad file path due to old patch from smp stuff).
- Downgraded Dwemer Pipework Reworked from v5 to v4 (helps alleviate crash issues in Dumzbthar).
- Flagged original Tempus Main Menu replacer as Always Enabled (disabled by default due to people thinking it's a virus but it's amazing so you should turn it on).
- Hid statsmenu.swf from EdgeUI (perk chart text will now be in the style of Untarnished). 
- Disabled Immersive Weapon Switch (weird UI stuff I don't feel like dealing with).

---

2025/04/03

Version 8.0.0

Welcome to the new Tempus Maledictum. There are so many changes that a full changelog would probably be a thousand lines long, if not more. So let's just cover the hits.

**ADDED**

- BFCO
- Hundreds of new combat animations
- Community Shaders
- Reshade
- SCAR
- Lux
- Lux Via
- Lux Orbis
- Missives
- Nature of the Wildlands
- Fortified Morthal
- Wait Your Turn - Enemy Circling Behavior
- Celestine
- Melana the War Maiden - An Evolving Custom Voiced Follower
- No Loading in the Thieves Guild
- The Ratway Passages
- Fortified Whiterun
- JK's Whiterun Outskirts
- Archery Locational Damage

**REMOVED**

- ENB, and all related ENB files
- Traverse the Ulvenwald
- Redbag's Solitude
- NPCs React To Necromancy
- Darkend
- The Great Village of Kynesgrove

Honestly I can't remember most of what I removed. Focus on the new stuff!

Enjoy the list, and remember: this is literally my full-time gig now, so if you like what you see, please [consider supporting me on Patreon](https://www.patreon.com/c/nicholasjae). Thanks!

---

2025/01/06

Version 7.4.1

All that work and I forgot to include the new spellforge library in wj's settings.

You can use the same save, just use the Import Spells function from the Spellforge Manual to update the list if you started on 7.4.0 already.

---

2025/01/06

Version 7.4.0

**UPDATED**
- eeekie's Orpheus - visual overhaul.
- Marked Treasure SSE (NG).
- Legacy of the Dragonborn - Follower Room Patches.
- PhotoMode.
- Legacy of the Dragonborn SSE.
- Legacy of the Dragonborn Patches (Official).
- Val Serano.
- Legacy of the Dragonborn SSE - The Curators Companion.

**ADDED**
- Simply Order Summons - No Dialogue Menu Patch.
- Ultimate Animated Potions NG - ElSopa - Potions Redone patch.
- No Furniture Camera.
- Xelzaz Sirenroot Patch.
- Val Serano - Velehk Sain Patch.
- HDT-SMP Spell Knight Armor Patch.

**REMOVED**
- Next-Gen Decapitations.
- Mihail's CC Zombies Overhaul.
- College of Winterhold - Quest Expansion.

**NOTES**
- New Synthesis Outputs.
- New EasyNPC Output.
- Should fix crash on load issues (again). I tested this for quite a bit myself. Next-Gen Decapitations won't be making a comeback, sadly.
- Removed some older/outdated patches that were doing precisely nothing.
- Fixed four trees. Wow.
- Spellforge lists should now be perfect. This took me roughly six hours. It was miserable.
- Re-enabled a few Spell Tomes, such as Frostbite & Flames for the focusing crystal quest that I forgot the name of.
- Some new Loot rules.
- Fixed some armor equip displays (most notably Dragon Priest Masks).
- Added Xelzaz to NFF Default Exclusion List.
- Added fix for Clavicus Vile. If you are pursuing both There Is No Umbra alongside Barbas' quest, you need to finish the deal with Daumbra before Clavicus will have the dialogue to complete Barbas' quest. Such is life.
- Removed Soul Harvest from Odin, to prevent confusion with Soul Harvest from Practical Necromancy.

---

2025/01/01

Version 7.3.6

Disabled optional SSE Display Tweaks INI.

---

2025/01/01

Version 7.3.5

Reverted ENB changes from 7.3.4.

---

2024/12/31

Version 7.3.4

Happy New Year!

**UPDATED**
- HCaS Fish Anywhere Patch.

**ADDED**
- Majestic Mountains - Bloodchill Manor Patch AE.
- Valhalla Combat - Backstab Bug Fix.
- Widescreen Scale Removed for 1-6-1130 and higher.
- Edge UI C.O.C.K.S 21-9 fix


**REMOVED**
- Grab and Throw.

**NOTES**
- Fixed an issue where Deep Elf characters weren't given a starting Smithing perk. If you are playing a Deep Elf character, you will be prompted to choose which perk you'd like when you load into your save.
- Hid a file from Edge UI (statsmenu.swf) that was causing the text on Perk descriptions to be too small for people's liking.
- Several people are working very hard on Ultrawide compatibility. To that end, I have added two Ultrawide-related mods, but have NOT removed any others, as I am currently unsure of which files actually need to be here. If you require assistance with this, please check in with the Discord.
- Edited some ENB settings for rain.

Special thanks to ChurchofKenny, Dace, StonyMason, and a few others for all their help with the Ultrawide section.

I also want to add a note that I've noticed an influx of people reporting and troubleshooting issues, most notably Delth. I just want you all to know that this is very much appreciated. These are largely small things, but the small things are what make a list - and a community - truly great. While these issues are not fixed in this version, I do plan to do some testing on my end so I can address these things properly. It can be hard for me to fix stuff that I haven't seen first-hand, that's all. Just don't want you to think I'm ignoring you all. This may not be the most popular list, but it is the best, and that's all that matters.

Thanks. Enjoy.

---

2024/12/27

Version 7.3.3

**UPDATED**
- Handy Crafting and Spells.
- Handy Crafting Patches.
- Next Gen Decapitations.
- The Dragonborn's Bestiary - Lively's Alchemy Addon.
- Skyrim Script Extender.

Inlined a preset from Avi that I kept forgetting to move into the Presets folder. My bad.  

Inlined a SkyHUD INI to fix the crosshair placement for Ultrawide users. This section will receive more updates as I am spoonfed more information from Ultrawide users.  

This update should resolve issues with bonus carry weight being stuck when exiting the DBM museum/player homes.  
SKSE isn't exactly "updated" but the download source has been changed from the SKSE website to Nexus. This will allow Ian to get more DP (which he deserves for his years and years of support for the community).

Special thanks to ItsAlways710 for putting up with my bullshit, optimizing Alchemy Addon's scripting functionality, and for making the HCaS optional File for disabling auto learn during store.

---

2024/12/24

Version 7.3.2

Disabled CK Source Scripts.

Please note: you do NOT want this. It overwrites all other scripts in your game, and is only for me to use when working in the Creation Kit.  
If you installed this on an existing 7.3.0 save, **revert back to a save prior to updating to 7.3.1.** This version (7.3.2) is fully compatible with saves from 7.3.0.

Apologies for the inconvenience.

---

2024/12/24

Version 7.3.1

**ADDED**
- RS Children - Stonehills.
- Cloth Mannequins.
- Cloth Mannequins for Legacy of the Dragonborn.
- Lush Lavender.
- Rally's Barsets.
- The Great Cities of Winterhold - RS Children Patch.

**NOTES**
- Various fixes and script optimizations (thanks to ItsAlways710).
- Disabled two vines in Ivarstead that were blocking Gwilin on the bridge (aesthetic only).
- Fixed issue with Greybeard Mantle reducing shout cooldown by 20 instead of 0.2.

On a slightly more personal note, I just wanted to say thanks to ItsAlways710. For the unaware, he is responsible for overhauling Tempus' visuals, as well as creating [Handy Crafting & Storage](https://www.nexusmods.com/skyrimspecialedition/mods/59258), and providing various script fixes for things like Xelzaz and our Bestiary Alchemy Add-on. Please give him a little thank you, because god knows I don't do it enough.

---

2024/12/22

Version 7.3.0

- Included Synthesis outputs in the Wabbajack compile because I forgot.

Let's just pretend like 7.2.x never happened because I'm so fucking tired and depressed that I can barely handle this.

Just start a new save, it's been like 15 minutes, I'm sorry I suck at this.

---

2024/12/22

Version 7.2.1

Removed Auri AI Dismount Fix.  
Removed Auri - Thistlefoot Should Stay Outdoors.

---

2024/12/22

Version 7.2.0

New save required.☺

**UPDATED**
- Song of the Green - Auri Follower.
- Dragons Use Thu'um.  
- Landscapes - Cathedral Concept.
- Sacrosanct - Vampires of Skyrim.
- DynDOLOD DLL NG.
- DynDOLOD 3 Alpha.
- DynDOLOD Resources SE 3.
- Skyrim Landscape and Water Fixes.
- VIGILANT SE.
- VIGILANT Voiced - English Addon.
- No Grass In Objects.
- The Great Village of Kynesgrove Patch Collection.
- Summermyst - Enchantments of Skyrim.

**ADDED**
- Armory of the Dragon Cult.  
- TUDM Script Fixes.  
- Dragon Priests Retexture SE.
- Armory of the Dragon Cult - Unofficial LOTD Patch.
- Grass Cache Helper NG.

**REMOVED**
- Konahriik's Accoutrements, and all associated patches.

**FIXED**
- Disappearing crosshair after sneaking.  
- Doubled doors in Dawnstar's Jarl's palace.  
- Breezehome Aids can no longer acquire homes other than Breezehome (you shouldn't be using this book anyway, really).
- Black screens/freezes on specific cell transitions.
- Black face bugs on Kynesgrove children.
- Deeja's immortality.
- Remi's dialogue for her intro quest.
- Missing wall in High Gate Ruins.
- Orpheus intro not progressing if choosing vampire start in ASLAL.

**NOTES**
- New Dyndolod, Texgen, Lodgen outputs.  
- New Grass cache.  
- This version will be more performance heavy. The cost of stability, I guess.

---

2024/12/18

Version 7.1.2

**UPDATED**
- More Informative Console.
- Spell Perk Item Distributor.
- Summermyst - Enchantments of Skyrim.
- Splashes of Storms.
- Object Categorization Framework.
- B.O.O.B.I.E.S (aka Immersive Icons).
- Crash Logger SSE VR.

**ADDED**
- Keyword Patch Collection.

**REMOVED**
- Skyrim Priority.

Disabled SSE Display Tweaks INI in Overrides.

Kinda caught me mid-work so you get like...a half of an update. Sorry. That Priority thing just gotta go, I thought I deleted it a long time ago anyway.

---

2024/12/17

Version 7.1.1

**UPDATED**
- Updated Better Grabbing.
- Updated The Dragonborn's Fishiary - Bestiary Addon.
- Updated Considerate Followers - Followers are Silent During Dialogue.
- Updated Local Map Upgrade.
- Updated Local Map Upgrade - Edge UI Patch.

**ADDED**
- Added Oblivion Artifact Pack - Misc Fixes.

**NOTES**
- Reinstalled SkyHUD to add the iHud Compatibility Patch.
- New Synthesis and EasyNPC outputs. No more naked ladies.
- Patched Orpheus for ASLAL (thanks Tortle).
- Patched a missing mesh in High Gate Ruins (thanks Tortle).
- Updated Main, FAQ, and Post Installation sections of the ReadMe.
- Renamed Display Tweaks INI in Overrides to have the `_Custom` suffix.
- Moved `Survival Mode INI - Enabled` mod to the Optionals section. I think people are more likely to see it here.
- Inlined a preset from Rose upon request.
- Enabled achievements.

---

2024/12/15

Version 7.1.0

- Updated Legacy of the Dragonborn.
- Updated Legacy of the Dragonborn Official Patches.
- Updated Legacy of the Dragonborn - Creation Club Patches.
- Updated Bow of Shadows - Thane Required.
- Updated Next-Gen Decapitations.


- Removed edits to spell injection quests (primarily on Enai's spell mods). To account for this change, increased spell tome value by 800%. I think this will ultimately make things more interesting so you aren't *required* to rely on Spellforge, but still heavily encouraged to do so.
- Fixed Brawler's Iron Gauntlets model causing a meshsplosion.
- Fixed Proventus not giving Steward's Note for the Bow of Shadows CC quest.
- Fixed bird perches in Morthal and Ivarstead (thank you, Wartortle).
- Fixed landscape gaps outside Whiterun (thank you, Wartortle).
- Made some edits to Dragonborn's Fishiary because I didn't like the way some of it was done (namely, the easter egg entry / no easter egg patch).

This update should fix issues people are having in regards to crashing on save/load sometimes.

---

2024/12/14

Version 7.0.2

- Updated Relic Hunter- Guildmaster Start (Legacy and ASLAL addon).  
- Updated The Dark Arts (which got renamed to Practical Necromancy, so if you're searching for this in the future, here you go).  
- Removed Auto Audio Switch.  
- Flagged experimental Ultrawide files to be included in the compile.  
- Changed some MCM settings.  

---

2024/12/13

Version 7.0.1

- Updated SKSE Menu Framework.  
- Changed SKSE Menu Framework to no longer open the mod control panel when pressing F1 (you can still open it via holding F1).  
- Fixed Auri's body textures. Unfortunately, this does involve rebuilding EasyNPC so WJ will probably have to reassemble that for you as well.    
- Updated scripts for The Dragonborn's Bestiary - Lively's Alchemy Addon.  

---

2024/12/13

Version 7.0.0

**UPDATED**
<details>
 
- Another Race Menu Rotation Mod  
- Auto Input Switch  
- Base Object Swapper  
- Better AltTab  
- Bring Meeko To Lod  
- CBBE  
- Cities of the North - Morthal  
- Cities of the North - Falkreath  
- Cities of the North - Falkreath Patch Collection  
- CoMAP  
- ConsolePlusPlus  
- Constructible Object Custom Keyword System  
- COTN Dawnstar Patch Collection  
- Crash Logger SSE VR  
- Creation Club Farming - Tweaks Enhancements and Quest Expansion  
- Creation Club Open Helmets  
- Custom Skills Framework  
- Decorating Madness  
- Dragons Use Thu'um  
- Dual Wield Parrying SKSE  
- Dwemer Pipework Reworked  
- Dynamic Dodge Animation  
- DynDOLOD 3.00  
- DynDOLOD DLL NG  
- DynDOLOD Resources  
- DynDOLOD TexGen Fixes  
- ENB Input Disabler  
- Enhanced Death Cam  
- EVG Conditional Idles  
- Experience  
- Experience - MCM  
- Extra Skeleton Nodes - Physics for IED  
- Face Sculptor Expanded  
- Formlist Manipulator  
- Handy Crafting and Spells - Crafting Storage and Travel Enhancements  
- Harvest Your Blood for Septimus  
- Headhunter - Bounties Redone  
- Hearthfires Extended and Creation Club Fishing Patch  
- Heavy Armory  
- Heimskr only preaches on weekends  
- House of Horrors - Quest Expansion  
- I'm Talkin' Here  
- Improved Camera SE  
- Infiltration - Quest Expansion  
- Innocence Lost - Quest Expansion  
- Instantly Skip Dialogue NG  
- Intuitive Dragon Ride Control (SE)  
- JS Essence Extractor SE  
- Keyword Item Distributor (KID)  
- Lawless - A Bandit Overhaul  
- Leaps of Faith - A Misc Quest  
- Legacy of the Dragonborn  
- Legacy of the Dragonborn - The Curator's Companion  
- Legacy of the Dragonborn - Follower Room Patches  
- Legacy of the Dragonborn Club Patches  
- Legacy of the Dragonborn Patches (Official)  
- Legacy Storage Extension Util  
- MCM Helper  
- MFG Fix NG  
- moreHUD Inventory Edition  
- Nilheim - Quest Expansion  
- Nordic Stonewalls  
- Open Animation Replacer  
- Papyrus Ini Manipulator  
- PapyrusUtil SE - Modders Scripting Utility Functions  
- Particle Patch for ENB  
- PhotoMode  
- po3's Papyrus Extender 
- po3's Tweaks  
- Rain Extinguishes Fires  
- Rally's Weapon Racks  
- Read Or Take SKSE  
- Redbag's Solitude  
- RedBag's Solitude Patch Collection  
- Remiel-Custom Voiced Dwemer Specialist and Companion  
- RemoveAllItems Freeze Fix  
- Riften Docks Overhaul  
- Security Overhaul SKSE - Lock Variations  
- Sharpen Other Swords II - AnimObject Swapper  
- Simple Blood Potion  
- SIRENROOT - Deluge of Deceit  
- Smoking Torches and Candles SSE  
- Spell Perk Item Distributor (SPID)  
- Song of the Green (Auri Follower) - Vigilant Commentary Patch  
- Sun Affects NPC Vampires  
- Sure of Stealing  
- Survival Mode Improved - SKSE  
- Take a Seat - New DAR Sitting Animations  
- The Great Cities Resources  
- The Great City of Winterhold  
- The Heart of Dibella - Quest Expansion  
- The Heart of Dibella - Quest Expansion  
- The Only Cure - Quest Expansion  
- The Whispering Door - Quest Expansion  
- Trade and Barter  
- Traverse the Ulvenwald - No Enhanced Landscapes  
- True Directional Movement - Modernized Third Person Gameplay  
- Unaggressive Dragon Priests Fix  
- Unique Map Weather  
- Unofficial Skyrim Creation Club Content Patch  
- Unofficial Skyrim Modders Patch - USMP - Patch Emporium  
- Valvalis Combat - Visceral Tactics  
- Various Immersive Tanning Racks  
- Various Mystic Condenser Patches  
- Vlindrell Hall Remade  
- Water for ENB  
- Wyrmstooth  
- Xelzaz - Custom Fully Voiced Argonian Telvanni Follower  

</details>

**ADDED**
<details>

- A Shrine of Azura at the Shrine of Azura  
- Acolyte - Divine Covenants  
- Alchemy Plus  
- Als Ritual Quest Markers SE  
- Andrealphus Scene Tweaks  
- Animals Swim (Sort of)  
- Animated Ice Bergs  
- Animated Ships  
- Animated Ships Patches  
- Animated Ships - Finer Sails  
- Archery Rebalance  
- Ascend - Hidden Peaks of Skyrim  
- Ash Guardian Expansion- Mihail Monsters and Animals (SE-AE version) (''golem'')  
- Auri - Meridia Order Patch  
- Auri Buys Bone Arrows Fix  
- Auri's Mount Thistlefoot Texture Fix  
- Auto Audio Switch  
- Auto Grab Amulets of Skyrim From Standing Stones  
- Auto Resolution  
- Azurite Weathers  
- Baby Mammoths - Mihail Monsters and Animals (SE-AE version)  
- Backported Extended ESL Support  
- Bandit Lines Expansion  
- Better AltTab  
- Better Atronach Forge Offering Box - No More Dwemer Dresser - High Polygon Summoning Circle  
- Better Dragon Breath - AOE ground walls and FX  
- Better Forgotten Vale Portal Textures - Cubemaps - Environment maps  
- Better Grabbing  
- Birds of Prey and Felsaad Terns- Mihail Monsters and Animals (SE-AE version)  
- Bonemold Armor Replacer (SMP)  
- Bound Weapon Fix  
- Bounty Quests Redone - NG  
- Bow Of Shadows - Whiterun Thane  
- Bow of Shadows Invisibility Patch  
- Brawl Lines Expansion and Fixes  
- Bridges of Skyrim - Better Navmesh   
- Bruiser - Hand to Hand CSF Skill Tree  
- Burnt Corpses 4k Retexture- Mihail's Shards of Immersion (SE-AE version)  
- Buyable Home Patch for Elysium Estate SSE  
- Carriage and Ferry Travel Overhaul Patch  
- Carriages and Stables Dialogue Bundle  
- Cathedral 3D Sword Ferns  
- Carriage Ferry Travel Overhaul useless dock removal - Base Object Swapper - CFTO - BOS  
- Chickens and Chicks- Mihail Monsters and Animals (SE-AE version)  
- Chitin Armor Replacer (SMP)  
- Civil War Lines Expansion  
- Classic Paralysis  
- ClickLight - Colour Picker FOMOD  
- Cliff Racers Fly So High- Mihail Monsters and Animals (SE-AE version)  
- College of Winterhold - Quest Expansion  
- Conditional Expressions - Subtle Face Animations  
- Conditional Expressions Extended  
- Conditional Expressions for NPCs  
- Conditional Expressions Sound Loop Bugfix  
- Considerate Followers - Followers are Silent During Dialogue  
- Console Commands Extender  
- COTN Falkreath Center Tree Replacer  
- Cow Replacer - My optimized textures and SkyTEST patch SE by Xtudo  
- Crimson Nirnroot Bosses - Return to Your Roots Alternative  
- Crouch Sliding  
- Crouch Sliding - Pandora fix  
- Crouch Sliding - Remove Ragdolling for Good  
- Crouch Sliding TUDM Patch - Slide with Your Weapon Drawn  
- Crows and Ravens- Mihail Monsters and Animals (SE-AE version)  
- CS' Fishing Nets  
- Daggermouth - Mihail Monsters and Animals (SE-AE version)  
- Damaged Skeletons- Mihail Monsters and Animals (SE-AE version) (''undead'')  
- Dark Elf Voices For Bandits  
- Darkend - Enemy Rebalance  
- Defeat the Dragon Cult  
- Demon of Dream  
- Depths of the Reach  
- Destroy The Dark Brotherhood - Quest Expansion  
- Detect Life and Detect Dead Rework - No longer concentration  
- Dialogue History  
- Dismembering Framework  
- Diverse and Lootable Firewood  
- Diverse Tanning Racks - Base Object Swapper  
- Doomsday of Blades- Mihail Monsters and Animals (SE-AE version) (''mythic dawn'')  
- Dragon Breath VFX Edit  
- Dragon Come Back  
- Dryads - Mihail Monsters and Animals (SE-AE version) (''spriggan'')  
- DVA - Dynamic Vampire Appearance  
- Dynamic Activation Key  
- Dynamic Animation Casting - NG  
- Dynamic Interface Patcher - DIP  
- Dynamic Mercenary Fees  
- Dynamic Things Alternative  
- Easy Console Commands  
- Edge UI  
- eeekie's Illia  
- eeekie's Regular Remiel  
- Elemental Dash  
- Elemental Golems- Mihail Monsters and Animals (SE-AE version)  
- Elysium Estate SSE - Caretaker NPC Removal  
- Elysium Estate - Guards Armor Replacer SSE Compatibility Patch  
- EVG CLAMBER - Slope Animations  
- Face Sculptor Expanded  
- Fancy Fishing  
- Faster HDT-SMP  
- First Person Animation Teleport Bug Fix  
- Fishermen Fish  
- Flame VFX Edit  
- Flute Animation Fix  
- Follower Trap Safety - SPID  
- Forceless Dawnbreaker Explosion - AE  
- Forsworn and Thalmor Lines Expansion  
- Fortune's Tradehouse  
- Frogs- Mihail Monsters and Animals (SE-AE version)  
- Frost VFX Edit  
- G.I.R.T.H. - Gildergreen Is Really Thicc HD  
- Giant Club Variety- Mihail Weapons and Shields (SE-AE version)  
- Giants Overhaul- Mihail Monsters and Animals (SE-AE version)  
- Gildergreen Regrown  
- Glorious Doors of Skyrim - Missing Door Sounds  
- Grab And Throw  
- Grindable Mammoth Tusks  
- Hanging Dead Animals Replacer- Mihail's Shards of Immersion (SE-AE)  
- Hanging Dead Pheasants Replacer- Mihail's Shards of Immersion (SE-AE)  
- Harkon Sword Rework  
- Harthstone Isles  
- Havocrels- Mihail Monsters and Animals (SE-AE version) (''eso'')  
- Hayd's Warpaints  
- HCaS Fish Anywhere with Simple Fishing Overhaul  
- HCaS Ordinator Bone Collector Patch  
- HCaS Silent Spells  
- HDT-SMP for Cloaks and Capes  
- Headhunter - Bounties Redone  
- Healing VFX Edit  
- Hearthfire Multiple Adoptions  
- Heavy Armory - New Weapons  
- Heavy Chitin Armor Replacer (SMP)  
- Hide Backpacks  
- Hive Guardians- Mihail Monsters and Animals (SE-AE version) (''falmer'')  
- Horse Save Load Fix  
- Hotkey Reminder  
- I4 Armor Icons Overhaul  
- IA Merged - Multiple Adoptions version  
- IDRC - Diverse Dragons Collection Patch  
- Imaginarium ENB  
- Immersive Equipment Displays - Extra Skeleton Nodes  
- Immersive Rejections  
- INDIGO  
- Infiltration - Quest Expansion  
- Insightful Shalidor's Insights (esl)  
- Iron Armor Replacer (SMP)  
- Items Stolen Bug Fix  
- JS Badges of Office  
- JS Unique Utopia SE - Rings  
- JS Vanilla Circlets SE  
- Jump Slide Fix OAR  
- Just Reject Boethiah  
- Khajiit Has Tents  
- Less Block Without Shield  
- Lesser Ice Golem- Mihail Monsters and Animals (SE-AE version)  
- Leveled List Crash Fix  
- Lightning VFX Edit  
- Local Map Color  
- Local Map Upgrade  
- Marked Treasure SSE (NG)  
- MergeMapper   
- MfgFix NG  
- Mihail's CC Goblins Overhaul (SE's Creation Club- AE)  
- Mihail's CC Zombies Overhaul (SE's Creation Club- AE)  
- Missing in Action Delayed - Level and Quest Requirement  
- Modular SMP Hairstyles  
- More Ancient Frost Atronachs- Mihail Monsters and Animals (SE-AE version)  
- More Cow Variants- Mihail Monsters and Animals (SE-AE)  
- More Hircinic Aspects of Hircine- Mihail's Shards of Immersion (SE-AE version)  
- Morthal Barrow  
- Multiple Adoptions Improved  
- My Home is Your Home (MHiYH 2plus) - SSE
- MYrwatch - House Fix  
- Naked Dead NPC Fix  
- Native EditorID Fix  
- New Madness 2.0  
- New Moon Cottage  
- Next-Gen Decapitations  
- Nightgate Inn Revived  
- Nirn Necessities - SMP Accessories  
- Nirn Necessities - Generic Distribution Add-on  
- No Grass In Objects  
- No Mask Unturned  
- NPCs Learn to Aim  
- NPCs React To Frenzy  
- NPCs React To Invisibility  
- NPCs Take Cover - Smarter Anti-Cheese AI  
- NPCs Wear Amulets of Mara PLUS  
- Obscure's College of Winterhold Loot Rebalancing  
- Ogres and Ettins- Mihail Monsters and Animals (SE-AE version)  
- Orc Addon for Vampire Lines Expansion  
- Opheus  
- Oxygen Meter 2  
- Paired Animation Improvements  
- Parkour in Skyrim - EVG Animated Traversal Addon  
- Patch for Lawless and Infiltration Quest Expansion  
- Perks of Valhalla - Block Skill Tree  
- Perks of Valhalla - Block Skill Tree SPID Distribution  
- Possessed Daedric Armours- Mihail Monsters and Animals (SE-AE version)  
- Precision magic trails  
- Press E to Heal Followers  
- Project AHO - Saving The Oryses Tweaks  
- Rainbows Remade  
- Rally's Banners of Skyrim  
- RedBag's Rorikstead FOMOD  
- Redcap CC Goblins Commentary and Gogh Interactions  
- Redcap EVG Animated Traversal Addon (ESL flagged)  
- Redcap the Riekling - A Fully Voice-Acted Immersive Follower and Quest  
- Reimperialized Darklight Tower - Location Overhaul and New Tileset  
- Reindeer Herds- Mihail Monsters and Animals (SE-AE version)  
- Remote Interactions  
- Request Break from Bards  
- Restoring the Aretino Residence SE  
- Return Aegisbane  
- Revealing Rune  
- Riekling Ice-Carved Steed - Mihail Monsters and Animals (SE-AE version)  
- Ring-necked Pheasants - Mihail Monsters and Animals (SE-AE version)  
- Rise in the East - Immersive Start - Don't Miss Japhet's Folly  
- Rogue's Gallery  
- Run For Your Lives  
- Safehouse Spellforge  
- Sanctified Stolen Goods  
- Sandbox When Idle  
- Savage Serana  
- Sea Giants and Ice Titans- Mihail Monsters and Animals (SE-AE version)  
- Sea Turtles- Mihail Monsters and Animals (SE-AE version)  
- Sense Death - It reeks (Detect Dead)  
- Sensible Bribes - Based on Speechcraft Not Level  
- Sensible Dawnguard Prerequisite  
- Sensible Oculory Solution - Logical Mzark Puzzle - Discerning The Transmundane - Main Quest  
- Sensible Undeath Prerequisite - No Level  
- Sensible Wyrmstooth Prerequisite  
- Simple Fishing Overhaul - Animations and Improved Quest Dialogue  
- Skill Based Dynamic Animations  
- Skip Time Wound Scene (optional and initially disabled, just in case the scene bugs out)  
- Skyrim on Skooma  
- Skyrim SE Skill Interface Re-Texture  
- SkyTactics - Dynamic Combat Styles  
- Sky Reflection Fix  
- Sleeping Expanded - Animations and NPC reactions  
- Small Nordic Tent- Animated  
- Smart NPC Potions - Enemies Use Potions and Poisons  
- SMP Wind  
- Snazzy - Skyrims Unique Treasures (Plus Legacy of the Dragonborn Patch)  
- Soldier of Stendarr  
- Sound Record Distributor  
- Spellbreaker Reforged  
- Spellforge  
- SPID-ified - HDT-SMP for Cloaks and Capes  
- Stamina of Shooting - Drawing Bow Costs Stamina  
- Stealing Not Browsing - A Pickpocket Mod  
- Stonefire Weaponry- Mihail Weapons and Shields (SE-AE version)  
- Stronger Potema - Wolf Queen Boss  
- Stuff of Shadows  
- Summoning Portals VFX Edit  
- Talkative Falmers - Mihail Monsters and Animals (SE-AE version)  
- Talkative Flame Atronachs - Mihail Monsters and Animals (SE-AE version)  
- Talkative Hagravens - 2023 Halloween Special (SE-AE version)  
- Talkative Spriggans- Mihail Monsters and Animals (SE-AE version)  
- Talkative Storm Atronachs - Mihail Monsters and Animals (SE-AE version)  
- Talkative Wispmothers - Mihail Monsters and Animals (SE-AE version)  
- Taunt Your Enemies - Taunting Matters  
- Thane's Privilege - Guards Forgive You Multiple Times  
- The Cursed Mercenaries  
- The Dark Arts  
- The Dragonborn's Bestiary  
- The Dragonborn's Bestiary - Lively's Alchemy Addon  
- The Dragonborn's Fishiary  
- The Emperor's Bodyguard - Dark Brotherhood Questline Final Boss  
- The Sunken City  
- The Taste of Death - Quest Addon  
- There Is No Umbra - Chapter III  
- There Is No (CC) Umbra  
- Thugs Not Assassins Extended  
- Troll Cubs- Mihail Monsters and Animals (SE-AE version)  
- Trolls SE  
- TUDM Pandora Animation Patch  
- Tundra Homestead - LotD Storage  
- Ultimate Animated Potions NG  
- Unmasking Sybille  
- Val Serano  
- Val Serano - Salt and Wind Retextures  
- Vampire Animations  
- Vampire Feeding Tweaks  
- Vampire Lines Expansion  
- Vanilla Eating Animation Fixes  
- Vigil Enforcer Retexture SE  
- VIGILANT - No Early Daedric Weapons  
- VIGILANT - No Thalmor Weapons  
- VIGILANT - Smaller Dragon knight Tower Shield 25  
- Vipir Pickpocket Training Fix  
- Werebeasts Don't Talk  
- Werewolf Power Attack Fix  
- Werewolf Power Attack Fix - Violens Patch  
- Whiterun Exterior Patch Collection  
- Wild Horses - Voiced Addon (CC)  
- Wounds Overlays For RaceMenu  
- ZeusCam - A Next Gen Cinematic SmoothCam Preset  
- zxlice's ultimate potion animation - ZUPA  

</details>

**REMOVED**
<details>
 
- 8k 4k Nordic Mountains - Just Textures  
- Ancient Dwemer Metal - My patches - Clockwork  
- Animated Small Nordic Tent Replacer  
- Apocalypse - Waterstride Spell Addon  
- Apophysis Dragon Priest Masks  
- Archery Gameplay Overhaul  
- Better Ferns  
- Blackthorn (and all associated mods and patches)  
- Cathedral Weathers and Seasons  
- Cathedral Weathers and Seasons Unofficial Update  
- Cathedral Weathers MCM  
- Clockwork (SSE)  
- Clockwork shadow redone  
- Clockwork - No Lockpick Activate (SKSE) Patch  
- Clockwork - Particle Lights for ENB Addon  
- CoMAP  
- Culminated ENB  
- Dear Diary  
- Dynamic Firewood Stacks  
- Elevated NPCs  
- ERM - Enhanced Rocks and Mountains  
- EVGATLOTD Patch  
- Faction - Pit Fighter  
- Faction - Pit Fighter - Revamped  
- Faction - Pit Figher Travels Add-on  
- Favor Quests Separated  
- Fluffy Beds and Bedrolls  
- Fossil Mining  
- Hoth  
- Improved Daedric Artifacts SE  
- Inigo (and all associated mods and patches)  
- Intuitive Dragon Ride Control (SE)  
- Kaidan 2 (and all associated mods and patches)  
- Legacy of The Dragonborn - Cube Maps Fixed  
- Legacy of The Dragonborn - Museum Exterior Fixes  
- Legacy of the Dragonborn - Serana's Safehouse Room (Unofficial)  
- Legacy of the Dragonborn - Serana's Safehouse Room (Unofficial) - Alternate Painting  
- Legacy Safehouse Plus  
- Lively's Second Great War Patches  
- New Treasure Hunt SSE  
- Odin Spells for NPCs  
- Oxygen Meter  
- Polar Peaks  
- Race Compatibility Dialogue for Inigo  
- Rainbows SE  
- Real Mountains Rebuilt - FoMod  
- RedBag's Rorikstead - Second Great War Patch  
- RedBag's Rorikstead - New Treasure Hunt Patch  
- RedBag's Rorikstead - ASLAL Patch  
- RedBag's Rorikstead - CC Pets Patch  
- RedBag's Rorikstead - Embers XD Patch  
- RedBag's Rorikstead - SUT Patch  
- RedBag's Rorikstead - Ulvenwald Patch  
- Riften Docks Overhaul - Clockwork  
- Serana Safehouse Room TCC Patch  
- Sets of Skills (and all associated mods and patches)  
- Stats of Stealing  
- Supreme Rainstorms SE  
- Survival Mode Vampires - Health Regen Fix  
- The Falkreath Hauntings  
- The Gray Cowl of Nocturnal SE - Retexture  
- The Gray Cowl of Nocturnal SSE - HD pack  
- The Gray Cowl of Nocturnal SE  
- The Gray Cowl of Nocturnal - Alternative Start  
- The Second Great War  
- The Second Great War - Relationship Dialogue Overhaul  
- The Second Great War - USSEP  
- TrueHUD - HUD Additions - Gray Cowl of Nocturnal Boss Ini Tweaks  
- Treasure Hunter for SSE  
- Untarnished UI  
- Use Or Take SKSE  
- Vanargand Animations - Archery  
- Vanargand Animations - Sneak Archery  
- Wintersun (and all associated mods and patches)  
- Zim's Immersive Artifacts  

</details>

---

2024/04/08

Version 6.3.4

Fixed Deep Elf starter perk stuff.  

---

2024/04/08

Version 6.3.3

Added Better Rkund Navmesh for Legacy of the Dragonborn.  
Added Harrald Horse Crash Fix.  
Added CatHub.  

Updated Kaputt - Melee Killmove Manager.  
Updated Console Commands Extender - Anniversary Edition Update.  
Updated The Timelost Dwemer - A Deep Elf Race SE.  
Updated Unofficial Skyrim Modder's Patch Hotfix 2.6.2b.  

Slightly edited Synthesis patch to remove outdated Timelost Dwemer addon.  

---

2024/01/20

Version 6.3.2

Replaced Curios creation with the other Curios creation.  
Minor mod order adjustment because filming an episode of One Minute Modding seems to be the worst thing I've ever done in my life.  

---

2024/01/19

Version 6.3.1

**REMOVED**

Ancient Dwemer Metal - My patches - JS Attunement Sphere and Lexicons SE  
Ancient Dwemer Metal - My patches - JS Dwarven Oil SE  
Ancient Dwemer Metal - My patches - JS Dwemer Artifacts SE  
Ancient Dwemer Metal - My patches - JS Dwemer Control Cube  
Ancient Dwemer Metal - My patches - JS Dwemer Ichor Barrels SE  
Ancient Dwemer Metal - My patches - JS Dwemer Kitchenware SE  
Ancient Dwemer Metal - My patches - JS Dwemer Puzzle Cube SE  
Ancient Dwemer Metal - My patches - JS Essence Extractor SE  

---

2024/01/19

Version 6.3.0

Recompiled to make the list installable again. Thank you to the Wabbajack devs for the app update that made this possible.

---

2023/12/07

Version 6.2.0

Recompiled to make the list installable again.

---

2023/10/11

Version 6.1.5

Made Glenmoril ammo only craftable after starting the Glenmoril quest.

---

2023/10/06

Version 6.1.4

Fixed Ordinator Recycling Handy Crafting interaction.  
Fixed invisible werewolves again. For the last time. 
 - I only tested on Sinding because he's the fastest one to test werewolf stuff on, so let me know if someone else doesn't have the fix applied. But it should be universal.

---

2023/08/30

Version 6.1.3

*This isn't getting old at all, right guys?*  

Removed Owl's Font Config Tweaks.  

---

2023/08/30

Version 6.1.2

Fixed KaidanMod download (removed extra file in my downloads folder so the compile for WJ won't pick it up anymore).  
Fixed Synthesis/EasyNPC interaction rendering some player character presets with an invisible head part.  

---

2023/08/30

Version 6.1.1

Fixed some Loot/load order stuff.  
Updated Tempus version header in MO2.  

Yes, that's it.  

---

2023/08/30

Version 6.1.0  

**New save required.**  

 <details>

**ADDED**

Polar Peaks - 16K - Parallax  
Guards and Stormcloaks Armors Retexture SE  
KG's Vanilla-esque Farmhouse Walls with Parallax  
KG's Farmhouse Walls - Dave's Polar Peaks Recolor  
tanningrack001  
Various Immersive Tanning Racks  
Sepolcri - A Complete Burial Sites Overhaul  
Less Shiny Bloody Bones - Skeleton Replacer HD  
Hendraheim - Creation Club Patches - SMIM  
Drengin's Blue Palace - Mesh Only Replacer  
Solitude and Temple Frescoes 2019  
Solitude Temple Frescoes 2019 - eye cubemap patch  
HD Textures for Solitude and Temple Frescoes  
Thieves Guild Armors Retexture SE  
Animated Armoury - Precision Whips Patch  
Darkend - CoMAP  
Madmen - A Forsworn Overhaul  
Gozer's Patch for Delayed Missing in Action  

**UPDATED**  

Clockwork - Particle Lights for ENB Addon  
Kaidan - Extended Edition  
Beyond Skyrim - Bruma - Growable Plants Patch  
Unslaad SE  
UNSLAAD Voiced - English Addon  
Object Categorization Framework  
B.O.O.B.I.E.S (aka Immersive Icons)  
Aura's Inventory Tweaks  
Font Overhaul  
Lawless - A Bandit Overhaul  
FormList Manipulator - FLM  
RaceCompatibility with fixes for SSE  
The Timelost Dwemer - A Deep Elf Race SE  

**REMOVED**  

Difficulty Balance  
Stone Wall 4k retexture  
Solitude and Temple Frescoes - Cleaned and Upscaled  
Show Player In Menus  

Changed Scrambled Bugs' ini settings to account for the removal of Difficulty Balance.  
Fixed QuickLoot icons.  
Removed DA02Champion from Dunmeri Outfits for Skyim Dunmers (SPID).  
New EasyNPC output.  
New Synthesis output.  
  - No longer using Weapon Speed Fix or that Landscape Vertex patcher thingy.  

 </details>

---

2023/07/29

Version 6.0.0

**New save required.**

<details>  
 
 **ADDED**  
 
 Ulvenweld - No Berries on Wigfrid09's Reach trees  
 Venerable Nordic Temples (2K - 4K)  
 Skyland Blacksmith Texture Overhaul  
 Leather Armors Retexture SE  
 Unreal 4K-8K Mammoth Skeleton ReTexture  
 4K Tusks  
 Spriggans SE  
 Iconic's Spiders of Skyrim  
 Giant Hanging Bones Retexture  
 Temple of Kynareth Mosaic Retexture - 4K - 2K  
 Skyland Alchemy and Enchanting Tables  
 Skyland Animated Mead and Ale Bottles  
 Skyrim Objects SMIMed - Noble Furniture  
 ElSopa - Potions Redone - My Patches SE by Xtudo- LotD, CC Adventurer's Backpack, Praedy's Soul Husk Extract  
 Sleeping Tree Sap - My Version by Xtudo - ENB  
 Blood Potion - My Version by Xtudo - ENB  
 Ancient Nord Armors and Weapons Retexture  
 SMIM Raddits Shell Textured - Real Rabbiits HD Version  
 No Grassias  
 Falmer Armors and Weapons Retexture  
 Better Ropes SSE  
 Nordic Stonewalls  
 A Canticle Tree  
 Skyland Animated Mead and Ale Bottles  
 Skyland Alchemy and Enchanting Tables  
 Temple of Kynareth Mosaic Retexture  
 Vaermina's Torpor - My Version by Xtudo - Purple Version, Deadly Fear Poison  
 Sound Fix for Large Sector Drives  
 Dwemer Armors and Weapons Retexture SE  
 Iconic's Gargoyle and Death Hound Retexture  
 Dark Brotherhood Sanctuary Decor - Remastered Vanilla Door  
 The Gray Cowl of Nocturnal SSE - HD pack  
 The Gray Cowl of Nocturnal SE - Retexture  
 Praedy's repository - SE  
 Hot Lava - Heat Distortion - PraedythXVI  
 Alchemy Station Variants - Base Object Swapper  
 Higher Quality Shadowmarks  
 Desaturated HD Unique Hand Made Signs Overhaul By ShibePatrol  
 WiZkiD Signs  
 WiZkiD Specific Signs  
 Upgraded Silverware for Distinct Interiors  
 Rudy HQ - Miscellaneous SE  
 Peltapalooza - Complex Parallax Occlusion  
 Fluffy Beds and Bedrolls  
 Dark Brotherhood Armors Retexture SE  
 JS Purses and Septims SE  
 Basic Dining Set Replacer  
 Chitin Armors Retexture SE  
 JS Knapsacks SE  
 Diverse Candles STAC - Base Object Swapper  
 Creation Club Basket Distribution  
 Bruma Outfits for Skyrim Imperials (SPID)  
 Beyond Skyrim - Bruma Upscaled Textures (BSBUT)  
 Immersive Vampire Clutter - LITE  
 Myrwatch Clutter for College of Winterhold (BOS)  
 Dwarven Mail Outfits for Dwemer Enthusiasts (LOTD)  
 Vigil Enforcer Armors for Vigilants of Stendarr (SPID)  
 Civil War Champions Outfits for Officers (SPID)  
 Dead Man's Dread Outfits for Pirates and Sailors (SPID)  
 Dunmeri Outfits for Skyrim Dunmers (SPID)  
 Strongholds - Narzulbur  
 Strongholds - Largashbur  
 Juniper's Dawnstar Sanctuary  
 Sure of Stealing  
 Lawless - A Bandit Overhaul  
 Notification Log SSE NG  
 RemoveAllItems Freeze Fix  
 Instantly Skip Dialogue NG  
 Hide Those Futile Quests SE  
 GLENMORIL SE  
 Glenmoril Boss TDM patch  
 Animated Armoury Glenmoril Patch  
 Glenmoril - Delayed Start  
 Glenmoril Armors and Weapons Retexture SE  
 High Poly NPCs  
 Dual Casting Fix   
 Vigilant - Shadowfoot Sanctum Patch  
 Vigilant - NPC Overhaul  
 Xelzaz - Custom Fully Voiced Argonian Telvanni Follower  
 Simplicity of Seeding - Better Hearthfires and Farming CC Planter Scripts  
 Casting Bar  
 Object Categorization Framework  
 Dear Diary Dark Mode (white text)  
 Camera Persistence Fixes  
 Stats of Stealing  
 I'm Talkin' Here  
 A Dog's Life  
 Favor Jobs Overhaul  
 Dear Diary Dark Mode  
 Object Categorization Framework  
 Casting Bar  
 Untarnished UI  
 The Handy Icon Collection Collective  
 Extended UI  
 B.O.O.B.I.E.S (aka Immersive Icons)  
 I4 - SkyUI Weapons Pack  
 SkyUI AIO Survival (SAS)  
 Jug of Milk HD by iimlenny - My version SE  
 Windhelm Brazier - Vanilla Plus (High-ish Poly) Replacer  
 Bonemold Armors and Weapons Retexture SE  
 Precision Creatures  
 Smooth Moveset - Animated armoury Grip position fix  
 Smooth Moveset - Skyrim Spear Mechanic Grip position fix  
 Optimised Scripts for Enhanced Blood Textures - SPID version  
 Optimised Scripts for Ordinator  
 Optimised Scripts for Apocalypse-Ordinator Patch  
 Optimised Scripts for Summermyst  
 Smooth Random Jump Animation - Rework  
 Smooth Weapon Jump Animation  
 Stagger Direction Fix - SSE  
 Stagger Direction Fix - NG  
 Stoppage of Staggerlock  
 Conditional Dog Barking (DAR)  
 Conditional tavern cheering (DAR)  
 Gesture Animation Remix (DAR)  
 Gesture Animation Remix (DAR) - shield patch  
 Immersive folded hands (DAR)  
 Immersive folded hands (DAR) - Vanilla shield position patch  
 Lively cart driver animation replacer - SE or AE  
 NPC Animation Remix (DAR)  
 NPC Animation Remix (DAR) - Vanilla shield position patch  
 Animated Mounted Casting - Cast Spells On Horseback And Dismiss Horse  
 Axarien's Animations - The Companions - Vilkas Farkas Aela  
 VioLens Compatibility Extension  
 Open Animation Replacer  
 Nemesis Creature Behaivour - WereWolf Addon  
 Look Around - Searching Animations For NPCs  
 Pristine Vanilla Movement  
 Pristine Vanilla Movement - No Camera Shake  
 Unique Animations Reworked  
 Photo Mode  
 Survival Control Panel  
 Font Overhaul - Books and Notes Only  
 My Road Signs are Beautiful - English  
 Strongholds - Dushnikh Yal  
 Strongholds - Mor Khazgur  
 CC's Camping Expansion  
 Survival Mode Patch Collection - Cloaks of Skyrim  
 Realms of Oblivion  
 Inigo AE Survival Mode Food Overhaul  
 Wintersun - Survival Mode Patch  
 hakaspi's Survival Mode Patch - LotD  
 Ancient Falmer Armors and Weapons Retexture SE  
 Mythic Dawn armor SE  
 Mythic Dawn Armor SE - My patches and fixes  
 Mythic Dawn Armor - SPID  
 Skyland Bits and Bobs - A Clutter Overhaul  
 Cities of the North Optimized Meshes  
 Overlooked Dungeon Objects Retextures  
 Stalhrim Armors and Weapons Retexture SE  
 Owls Patching Nest - Valhalla Combat - More Race Compatibility Patches  
 Kaputt - Melee Killmove Manager  
 Valhalla Combat - Race Addons  
 The Heart of Dibella - Quest Expansion  
 House of Horrors Quest Expansion - Wintersun Patch  
 Caught Red Handed - Quest Expansion  
 The Only Cure - Quest Expansion  
 The Only Cure Quest Expansion - Wintersun Patch  
 The Whispering Door - Quest Expansion  
 The Innocence Lost - Quest Expansion  
 Search and Seizure - Quest Expansion  
 Improved Camera SE  
 4K Atronach Forge  
 DPI Scaling Fix  
 Lively's Patches for Remiel and her Add-Ons  
 Lively's Patches for Blackthorn and Tree Mods  
 Lively's Moved Carriage for Beyond Reach and Markarth Entrance Overhauls  
 Lively's Patch for CotN Dawnstar and Thunderchild  
 Lively's Patch for Icy Windhelm and City Entrance Overhaul Windhelm  
 Lively's Synergy Patch for Tools of Kagrenac and Aetherium Armor and Weapons  
 Lively's Formlist Manipulator INI for Transcribe Spells  
 Lively's Formlist Manipulator INI for Shadow of Skyrim  
 Lively's Patches for Cheesemod for EVERYONE  
 Vampire Armors and Weapons Retexture  
  
 **REMOVED**  
 
 ElSopa - HD Grindstone Redone SE  
 ElSopa - HD Grindstone Redone - Improved Sparks 10x  
 Jebbalon's Lava Column Correction - Aetherium Forge  
 Dwarven Set - Resurgence  
 Skyrim Remastered - Glaciers and Ice  
 Realistic HD Baskets Remastered  
 Survival Mode Improved - Wyrmstooth Region Patch  
 Motionless Rocks Killing People Fix  
 CritterSpawn Congestion Fix  
 High Gate Ruins Puzzle Reset Fix  
 Tavern AI fix  
 No BS AI Projectile Dodge (Magic and Arrows) - Immersive Projectiles Nondetection of Enemies  
 Completionist - Skyrim Completion Tracker (SE-AE)  
 CC Gray Cowl Returns - Thief Delay  
 Rudy HQ - More Lights for ENB SE - Bthardamz  
 Rudy HQ - More Lights for ENB SE - Deathbell  
 Rudy HQ - More Lights for ENB SE - Soul Gems  
 Iconic's Ysgramor Shield Retexture  
 SMIM Upper Furniture And Other Fixes  
 Shadow of Skyrim - Nemesis and Alternative Death System  
 No More Laser-Printed Book  
 Better MessageBox Controls  
 Convenient Dialogue UI - SE  
 Remove QuickSave Button from SkyUI System Menu  
 Wider MCM Menu for SkyUI  
 Smaller Vanilla Cursors  
 Attack Speed Framework  
 Smooth Magic Casting Animation  
 SpellSword Moveset  
 (SGC) Scriptfree Behavior Staggerlock - SBS  
 Ultimate Spinning Arrows SE  
 DART - Dynamic Animation Replacer Tool (beta)  
 Dynamic Animation Replacer   
 Map Flip For Beyond Reach  
 Phenderix Elements  
 Diversity - A Character Overhaul  
 The Streets of Whiterun in HD  
 Controller-mapping Unbound  
 Weapons of the Third Era SSE  
 Simplicity of Snow - Cities of The North  
 Cities of the North - Dawnstar - Partitioned Meshes for Lighting  
 Cities of the North - Morthal - Partitioned Meshes for Lighting  
 
 **UPDATED**  
 
 Better Chests  
 Owlessa's Custom Control Map Config  
 Custom Skills - Vigilant  
 Icy Mesh Remaster  
 Iconic Statues  
 Wolf Armor and Weapons Retexture SE  
 Glass Armors and Weapons Retexture SE  
 Blades Armors and Weapons Retexture SE  
 Elven Armors and Weapons Retexture SE  
 Imperial Armors and Weapons Retexture SE  
 Steel Armors and Weapons Retexture SE  
 Iron Armors and Weapons Retexture SE  
 Orcish Armors and Weapons Retexture SE  
 Daedric Armors and Weapons Retexture SE  
 Ebony Armors and Weapons Retexture SE  
 PAPER  
 Keyword Item Distributor (KID)  
 FormList Manipulator - FLM  
 Behavior Data Injector Universal Support  
 Unofficial Skyrim Creation Club Content Patch  
 Survival Mode Improved - SKSE  
 Unofficial Skyrim Modder's Patch - USMP SE  
 DynDOLOD Resources SE  
 Dyndolod 3 Alpha  
 Dual Wield Parrying SKSE  
 Skyrim Landscape and Water Fixes  
 Legacy of The Dragonborn Perk Menus  
 Immersive Armors Retexture and Mesh Fixes SE  
 Remiel-Custom Voiced Dwemer Specialist and Companion  
 Vigilant SE  
 Vigilant Voiced English Addon  
 Aura's Inventory Tweaks  
 Nemesis Creatures BEHAVIOUR compatibility  
 Sprint Sneak Movement Speed Fix  
 Keyword Compatibility Framework  
 Smooth Moveset  
 Dynamic Dodge Animation  
 Swor's Valhalla Combat KillCam Patches  
 Valhalla Combat Execution Compatibility patches  
 Animation in blizzard  
 Animation in Ashstorm  
 Payload Interpreter  
 Valvalis Combat - Visceral Tactics  
 Dynamic Random Spell Idle - Player and teammate  
 Conditional Armor Type Animations  
 CATA Addon - Goetia female idle Walk Run  
 CATA Addon - Goetia male idle Walk Run  
 CATA Addon - Goetia Animations Sprint  
 CATA Addon - Leviathan II Female Idle Walk Run  
 CATA Addon - Leviathan II Male Idle Walk Run  
 CATA Addon - Leviathan Animations II Sprint  
 CATA Addon - Vanargand Female idle Walk Run  
 CATA Addon - Vanargand male idle walk run  
 CATA Addon - Vanargand Animations Sprint  
 Embers XD  
 Creation Club Open Helmets  
 Custom Skills Merged  
 Custom Skills Menu - A Custom Skills Framework Unified Menu  
 Higher Poly Vanilla Cave Lamps  
 Water for ENB  
 Spell Perk Item Distributor (SPID)  
 Papyrus Ini Manipulator  
 ConsolePlusPlus  
 Rain Extinguishes Fires  
 Unofficial Skyrim Special Edition Patch  
 Particle Patch for ENB  
 Creation Club Open Helmets  
 Curated Bosses for True HUD  
 Wintersun - Zim's Immersive Artifacts Patch  
 Paarthurnax - Quest Expansion  
 Harvest Your Blood for Septimus  
 Creation Club Farming - Tweaks Enhancements and Quest Expansion  
 Song of the Green (Auri Follower)  
 Song of the Green (Auri Follower) - Kaiden Banter Patch  
 Janquel's Arguably Needed Quixotically Unifying ESP Library  
 Simply Order Summons  
 Expressive Remiel  
 
Added Optional INI Override section for users to easily find commonly edited ini files from mods.  
Downgraded Intuitive Dragon Ride Control (SE) from v3.0.0 to v2.0.0.  
Adjusted Aetherial Dwemervamidium temper recipe to require 25 dwarven ingots instead of 1.  
Removed bow & arrows from Daenlit (Wyrmstooth).  
Made some patches for CRAFT.  
Fixed floating staffs in Shalidor's Maze.  
Fixed unobtainable cheese and misaligned wall in some random Miner's Hut and I don't remember where. Somewhere in Old Hroldan or something.  
Really just a whole bunch of fixes with out-of-bounds and clipping collectibles and displays. I did a lot of them on stream, you can look it up ~~because I don't remember all of them.~~  
Probably a bunch of other fixes. It's been a while. I'm old. My memory sucks.  

 </details>

---
 
---

2023/04/25

Version 5.0.8

Fixed QuickLoot stuff. Enjoy your icon resurgence or whatever.

---

2023/04/24

Version 5.0.7

<details>
 
  **ADDED**  
  
  - Clockwork - No Lockpick Activate (SKSE) Patch  
  - Wynter's Breezehome - Wintersun - Legacy of the Dragonborn Patch
  
  **UPDATED**
  
  - Unofficial Skyrim Special Edition Patch  
  - Completionist - Skyrim Completion Tracker  
  - Simply Order Summons  
  - Swiftly Order Squad  
  - Spell Perk Item Distributor (SPID)  
  - Simplicity of Snow  
  - Icy Windhelm  
   
  **FIXED**
  
  - Deep Elf item values were ridiculous. Most are now 10% of what they were; some are even lower.  
  - Deep Elf item crafting was a bit ridiculous. No more clearing one dungeon and coming out with 900+ dwarven ingots.  
  - Grand champion helm was invisible on equip.  
  - Butterflies in Shivering Isles were upside down, just like vanilla.  
  - Missing controller config files.  
  - Disabled Strange Runes shadow casting. Should fix lighting crashes.  
  
  **DISMISS ANY SUMMONS YOU HAVE ACTIVE PRIOR TO UPDATING.**  
</details>

---  

2023/04/16

Version 5.0.6

Recompile in an attempt to fix hash mismatch errors because nobody truly knows why this happens so this is the only thing i can really even attempt to do to fix it plz ty  
MO2 version number probably still says 5.0.5. This is fine. plz.

---

2023/04/16

Version 5.0.5

Recompile to include two patches I accidentally left out of the compile. My bad.

---

2023/04/15

Version 5.0.4

<details>
  
  <b>ADDED</b>
  
  - Controller-mapping Unbound  
  - Silver Armor and Weapons Retexture SE  
  - Septentrional Landscapes 2K  
  - Northern Shores 2K  
  - Snow - HD Texture Replacer with Parallax  
  - Rudy - More dramatic Red Mountain Plume  
  
  <b>REMOVED</b>
  
  - The Omnibus - Terrain Complex Parallax AiO  
  - Tundra - HD Texture Replacer with Parallax  
  
  <b>UPDATED</b>
  
  - Skyland AIO
  
  <b>FIXED</b>
  
  - Refinalized navmeshes to successfully complete the door link from the Soul Cairn to Apocrypha. Valerica will no longer get stuck during the Beyond Death quest in Dawnguard.  
  - The "Return to Breezehome" spell has several issues. First, there was a typo in the description. That's fixed. Second, it teleported you into the Armory room, which is a purchasable upgrade. Now it will teleport you into the main area instead of the Armory, so you should no longer be stuck inside.  
  - Breezehome Exterior purchasable upgrade was revamped instead of removed. Now the landscape pieces will be enabled by default, and the upgrade you purchase will be for the furniture, rugs, lights, and things like that.  
  - Snowy treasure chests had weird textures.  
  - Iron gauntlets had a broken mesh that could cause a crash.  
  - Changed Miraak's gloves from Clothing to Light Armor.  
  - Changed some settings for Show Player in Menu. Please stop reporting that your inventory models are broken. They aren't broken. They just aren't vanilla. This is a modded setup. Sometimes things aren't vanilla.  
  
  </details>

---

2023/04/10

Version 5.0.3

<details>
  <b>ADDED</b>

  2K Raven Rock  
  Ancient Pottery  
  Auri Dismount AI Fix  
  Better Mammoth Tusks  
  Dovahnique's Diverse Dark Elf Lanters  
  FYX - RavenRock Docks and Fences Round Posts  
  Higher Poly Vanilla Cave Lamps  
  Remiros' Dragonborn Alcohol  
  Weathered Dark Elf Furniture Redux - Brown - 2K  
  
  <b>UPDATED</b>
  
  Cathedral Armory for CC - Patches  
  Cathedral Armory - Misc Patches  
  
  <b>BUG FIXES</b>
  
  Fixed Daedric Helmet being invisible.  
  Fixed werewolves turning invisible.  
  Fixed Ragged Flagon lighting issues (I think).  
  Removed one piece of floating hanging moss in the Reach.  
  Lowered an idle marker on Solitude Docks.  
  Moved LotD Shipping Boxes outside of Breezehome.  

  </details>
  
---

2023/04/08

Version 5.0.2

Removed CK stuff from the compiler. Again. Maybe. This is frustrating.

---

2023/04/08

Version 5.0.1

Removed CK stuff from the compiler. Thought I did that already. Guess I missed a few files.

---

2023/04/08

Version 5.0.0

New Save Required.

<details>
  
  <b>ADDED</b>
  
  4K Bedroll   
  Small Nordic Tent Replacer  
  Animated Small Nordic Tent Replacer  
  Salmon Retex - Realistic Salmon  
  Cathedral - 3D Dragons Tongue - White Violet  
  Cathedral - 3D Dragons Tongue - Glow Map and ENB Light  
  Bijin - Use CBBE Meshes and Textures  
  The Omnibus - Terrain Complex Parallax AIO  
  Tundra - HD Texture Replacer with Parallax  
  Tundra Texture Transplant  
  CoMAP - Common Marker Addon Project  
  DynDOLOD TexGen Fixes  
  Forgotten City - Softlock Protection  
  Valhalla Combat Execution Compatibility patches  
  Ice skating fixed for real - No more attack sliding movement (NEMESIS compatible)  
  CATA Addon - Goetia Animations Sprint  
  CATA Addon - Goetia female idle Walk Run  
  CATA Addon - Goetia male idle Walk Run  
  CATA Addon - Leviathan Animations II Sprint  
  CATA Addon - Leviathan II Female Idle Walk Run  
  CATA Addon - Leviathan II Male Idle Walk Run  
  CATA Addon - Vanargand Animations Sprint  
  CATA Addon - Vanargand Female idle Walk Run  
  CATA Addon - Vanargand male idle walk run  
  First Person Combat Animations Overhaul 2.0 -SIZE MATTERS  
  First Person Combat Animations Overhaul - Bugfix and Compatibilty Patch for Animated Armoury  
  Dynamic Random Spell Idle - Player and teammate  
  Dual Wield Parrying SKSE  
  Survival Mode Improved - SKSE  
  Map Flip For Beyond Reach  
  Dragons Fall Down - Immersive Airborne Death  
  Vine Maple Redone (didnt i just remove this, 710..?)  
  Blades Armors and Weapons Retexture SE  
  Locational Encounter Zones  
  Dragon Ragdoll Sounds  
  Name Your Pet  
  Wynter's Breezehome Redux  
  Custom Skills Framework  
  Companions Perk Tree  
  Custom Skills - VIGILANT  
  Legacy of The Dragonborn Perk Menus  
  Prelude to Purgatory - A Lich Custom Skill Tree  
  Custom Skills Merged  
  The Great City Of Winterhold SSE Edition  
  Ulvenwald - The Great City of Winterhold Patch  
  The Great City of Winterhold Patch Collection  
  Sprint Sneak Movement Speed Fix  
  Vanargand Animations - Dual Wield Normal and Power Attacks  
  Vanargand Animations - Archery  
  Vanargand Animations - One Handed Mid Stance  
  Vanargand Animations - One Handed Normal Attacks  
  Vanargand Animations - One Handed Power Attacks  
  Goetia Animations - Enchanted Staves  
  Goetia Animations - Magic Spell Casting  
  Goetia Animations - Sneak Magic  
  Cheesemod for EVERYONE  
  Unofficial LotD and BSB Synergy Patch - Standalone Displays  
  Recipe Auto-Learn  
  AnimObject Swapper  
  Sharpen Other Swords II - AnimObject Swapper  
  Sharpen Other Swords - Better-Shaped Weapons  
  Leviathan Animations - Two-Handed High Stance  
  Leviathan Animations - Two-Handed Normal Attacks  
  Leviathan Animations - Two-Handed Power Attacks  
  Better Chests  
  Whiterun Bench - Replacer  
  The Streets of Whiterun in HD  
  Iconic Statues  
  Serio's Enhanced Dragons Redone  
  Dragons Use Thu'um  
  Opulent Thieves Guild - Tweaks  
  Diverse Dragons Collection SE (DDCS) Soul Absorb Animation Fixed  
  Custom Skills Menu - A Custom Skills Framework Unified Menu  
  Additional Hearthfire Dolls  
  Ryn's Standing Stones  
  SmoothCam Vanilla Enhanced 2  
  Elven Armors and Weapons Retexture SE  
  WoW Dragon Mounds CTD Fix  
  Experience  
  Alternate Start - Experience Patch  
  Vampire Feed Improved  
  Sun Affects NPC Vampires  
  Cover Your Head - Sacrosanct  
  Sacrosanct Survival Mode - Vampirism Grants Warmth Bonus  
  Sacrosanct - No Sneak Feed On Followers  
  Strange Runes - Sacrosanct Patch  
  Vampires Have Claws  
  3rd Person Camera Stagger Remover  
  Disable screen shake effect  
  Obscure's College of Winterhold - Creation Club Patches (and a couple others too)  
  Catching Clockwork - Wheels of Lull Fishing Addon  
  Glass Armors and Weapons Retexture SE  
  Wolf Armor and Weapons Retexture SE  
  Vampire Lord Retexture  
  Supreme Vampire Lords  
  Legacy of the Dragonborn - Improved Dig Sites SE  
  JS Dwemer Kitchenware SE  
  Legacy of The Dragonborn - Dwemer Compass Replacer  
  Pets of Skyrim (CC) Collision Patch  
  ElSopa - HD Iron Tools Redone SE  
  Fixed Nordic Metal Grate  
  Nordic Carved Armors and Weapons Retexture SE  
  8k 4k Nordic Mountains - Just Textures  
  Enhanced Volumetric Lighting and Shadows (EVLaS)  
  Just Ice  
  Praedy's Soul Cairn - SE  
  Lod Model Library for DynDOLOD  
  Rudy HQ - More Lights for ENB SE - Moths and Fireflys  
  Butterfly Improved by zzjay - SE  
  Blackthorn Textures - 2K  
  Clockwork - Particle Lights for ENB Addon  
  Cow Replacer- Mihail Monsters and Animals (SE-AE version)  
  JS Torture Tools SE  
  Thrones of Skyrim  
  Serio Redone Exclusion Inclusion Patches  
  Swor's Valhalla Combat KillCam Patches  
  Experience - MCM  
  Experience Quests Tweak  
  Leveling Freedom - Configure your XP Curve - Gentler Smoother Steeper or Flat  
  
  <b>UPDATED</b>
  
  Skyrim (1.6.353 > 1.6.640)  
  ENB Binaries  
  Address Library for SKSE  
  PrivateProfileRedirector SE  
  Actor Limit Fix  
  Bug Fixes SSE  
  ConsolePlusPlus  
  ConsoleUtilSSE  
  Crash Logger SSE VR  
  JContainers SE  
  Encounter Zones Unlocked SE  
  Enhanced Invisibility  
  Enhanced Reanimation  
  Equip Enchantment Fix  
  Essential Favorites  
  Favorite Misc Items  
  Fuz Ro D-oh - Silent Voice  
  HelpExtender  
  Infinity UI  
  Mfg Fix  
  monster race crash fix  
  More Informative Console  
  No Lockpick Activate (SKSE) - Updated  
  Papyrus Tweaks NG  
  PapyrusUtil SE - Modders Scripting Utility Functions  
  Read Or Take SKSE  
  Remember Lockpick Angle - Updated  
  Scrambled Bugs  
  Simple Activate SKSE  
  Skyrim Priority SE AE - skse plugin  
  Spell Perk Item Distributor (SPID)  
  To Your Face SE - AE - VR  
  Yes Im Sure  
  powerofthree's Tweaks  
  powerofthree's Papyrus Extender  
  Base Object Swapper  
  Scaleform Translation Plus Plus  
  ENB Helper SE  
  Better Jumping SE  
  Use Or Take SKSE  
  I'm Walkin' Here  
  Enhanced Death Cam  
  Magic Leveling Fix  
  DynDOLOD Resources SE  
  DynDOLOD DLL SE - SKSE64 Plugin  
  Creation Club Open Helmets  
  A Clear Map of Skyrim and Other Worlds  
  Compass Navigation Overhaul  
  moreHUD Inventory Edition  
  moreHUD SE  
  Oxygen Meter  
  QuickLootRE - With Icons and TCC support  
  Completionist - Skyrim Completion Tracker (SE-AE)  
  Aura's Inventory Tweaks  
  Odin - Skyrim Magic Overhaul  
  Set of Skills  
  Legacy of the Dragonborn SSE  
  Legacy of the Dragonborn - Hall of Forgotten - TCC Patches  
  The Timelost Dwemer - A Deep Elf Race SE  
  Cathedral - Armory  
  Legacy of the Dragonborn Patches (Official)  
  Animated Armoury - Updated Legacy of Dragonborn Displays  
  Legacy of the Dragonborn Animated Armoury The Curator's Companion updated display patch  
  XP32 Maximum Skeleton Special Extended  
  Simple Dual Sheath  
  Immersive Equipment Displays - unequip when nude  
  (SGC) Scriptfree Behavior Staggerlock - SBS  
  Valravn - Integrated Combat of Skyrim  
  Valravn SPID Uncloak  
  Valvalis Combat - Visceral Tactics  
  Reduce Attack Skating Movement  
  Smooth Moveset  
  Unofficial LotD and BSB Synergy Patch - Main  
  Intuitive Dragon Ride Control (SE)  
  Landscapes - Cathedral Concept  
  Embers XD  
  
  <b>REMOVED</b>
  
  Better SkyUI Config - Reading Fix  
  Alternate Alchemy  
  Various DynDOLOD Error Fixes - Gray Cowl of Nocturnal  
  Various DynDOLOD Error Fixes - LotD  
  Animated Armoury - Legacy of Dragonborn Displays  
  XPMSSE Left Hand Sheath Rotation Fix  
  Valravn Uncloaked  
  No Spinning Death Animation SE  
  Skyrim Battle Aftermath SE  
  LotD Extension - Breezehome  
  Eli's Breezehome  
  Whose Quest Is It Anyway  
  (SGC) SkySA - Combat Behavior Compulsion  
  (SGC) SkySA - Intense Combat  
  Vanargand Animations - Mace Moveset MCO - SkySA  
  Alik'r Swordsmanship for SkySA  
  Elden Power Attack  
  COTN Winterhold Patch Collection  
  Cities of the North - Winterhold - ASLAL Patch  
  Cities of the North - Winterhold - Partitioned Meshes for Lighting  
  Winterhold - Expanded Ruins  
  Elden Power Attack  
  Attack Animations and Movesets  
  Smooth Random Equip Animation(Unarmed)  
  Smooth Random Equip Animation(Dagger)  
  Smooth Random Equip Animation(2H)  
  Smooth Random Equip Animation(1H)  
  Dynamic Animation Replacer Multiple Power Attacks Animations  
  Diverse Random Normal Attack  
  Archery Gameplay Overhaul SE - Nemesis Patch  
  Immersive World Encounters SE  
  Legacy of the Dragonborn - Hall of Forgotten  
  Legacy of the Dragonborn - Hall of Forgotten - TCC Patches  
  Dynamic Collision Adjustment  
  Learn Ingredients  
  Sharpen Other Swords  
  Holds the City Overhaul - Modular Edition  
  Holds Special Edition Compatibility Patches  
  Holds - Root Block Fix  
  Skyrim Reborn - Whiterun Hold  
  Skyrim Reborn - Hjaalmarch Hold  
  Antiquary - Enhanced Artifacts  
  Dragons Shout With Voice  
  Deadly Dragons  
  World Eater Beater  
  Simple Follower Extension  
  Auri - Convenient Horses Patch  
  Convenient Horses  
  Convenient Horses Anniversary Edition Patch  
  Lively's Convenient Horses Patches  
  The Brotherhood of Old  
  Animated Embers  
  Daedric Set - Resurgence  
  Ebony Set - Resurgence  
  Elven Set - Resurgence  
  Glass Set - Resurgence  
  Iron Set - Resurgence  
  Nord Set - Resurgence  
  Orcish Set - Resurgence  
  Steel Set - Resurgence  
  Nordic Carved Set - Resurgence  
  Soul Cairn HD  
  Bleak Falls Barrow - Animated Traversal  
  EVG Animated Traversal Skyrim Integration Patch  
  EVG Traversal Animations - Dungeons addons  
  
  
  Integrated Controller Support. Please see the readme.  
  Integrated Widescreen Support. Please see the readme.  
  
  </details>

---  

2023/03/08

Version 4.1.2

<details>
  
  <b>ADDED</b>
  
  Gemstones Remade  
  Vanilla Warpaints Absolution  
  Cathedral Armory CBBE Patch  
  SC - KS Hairdos Retextured  
  SPID for Footprints - Player Footprints Fix  
  Legacy of the Dragonborn - Cube Maps Fixed  
  Rally's Weapon Racks  
  Mari's Flora  
  Rally's Mead Barrels  
  Rally's Crates  
  Random Barrel Roll  
  Rally's Barrels  
  Enhanced Rocks and Mountains  
  Daedric Armors and Weapons Retexture SE  
  Dragon Armors and Weapons Retexture SE  
  Ebony Armors and Weapons Retexture SE  
  Orcish Armors and Weapons Retexture SE  
  Steel Armors and Weapons Retexture SE  
  Iron Armors and Weapons Retexture SE  
  Imperial Armors and Weapons Retexture SE  
  Immersive Armors Retexture for CBBE  
  Immersive Armors Retexture and Mesh Fixes SE  
  Unslaad Armors and Weapons Retexture SE  
  Vigilant Armors and Weapons Retexture SE  
  The Wheels of Lull Retexture SE  
  Vigilant's Molag Bal Dragon Retexture SE  
  Night Mother  
  
  <b>UPDATED</b>
  
  SPID for Footprints Fix  
  
  <b>REMOVED</b>
  
  Cathedral 3D Thistle  
  Cathedral 3D Nightshade  
  Vine Maple Redone  
  Deathbell by Mari  
  Charming Nirnroots  
  Thistle by Mari  
  
  Mod order adjustments.  
  Engine Fixes toml updated.  
  Lots of various bug fixes courtesy of Wartortle, ItsAlways710, and Owlessa.  
  New Dyndolod, Synthesis, EasyNPC outputs.  
  
  To do for the future (whenever we break saves again, anyway):  
  
  Combat updates/replacements  
  Slow down leveling    
  </details>
  
---
  
2023/03/02

Version 4.1.1

<details>
  
  <b>ADDED</b>
  
  Papyrus ini Manipulator.  
  dTry's Key Utils AE.  
  Elden Power Attack.  
  Erikur's House Rework for LotD.  
  Orc Settlements Enhanced.  
  Rally's Display Cases.  
  Whiterun Mesh Fixes.  
  Weathered Stockades Retexture.  
  Stone Wall 4K Retexture.  
  Meridia's Better Beacon.  
  Skyland Common and Upper Furniture.  
  The Great City of Dragon Bridge Navmesh Fix.  
  Minedoors Redone.  
  
  <b>REMOVED</b>
  
  Whiterun Stockade.  
  2K Stockade.  
  Fluffy Snow.  
  Better Power Attack Directional Control SSE.  
  Matching Mine Door.  

  <b>FIXED</b>
  
  First person attacks don't chain together.  
  First person power attacks don't work.  
  Landscape glitches due to removal of Build Your Noble House.  
  Blue Palace stairs use wrong textures.  
  Snapleg Cave soul gem can cause CTD.  
  Knight of Chorrol helmet renders head invisible.  
  Ravenscorn Spire Tower clipping.  
  Fort Amol tree clipping.  
  Inn of Lost Souls trees clipping.  
  Stone Hills clutter and clipping trees.  
  Dragons and other enemies "fade out" when you get too close to them.  
  Riverwood floating ivy and lantern placements.  
  Beards clip through helmets and masks.  
  Abandoned Shack floating tree.  
  Trees clipping in cell 21,-1.  
  Solitude museum ext floating lantern.  
  Honnigmead texture/mesh issue.  
  Wintersun functionality for LotD restored.  
  Phenderix summoning spells don't cost what is displayed in the UI.  
  Tempus Maledictum Guide Book no longer tells users to manually run MCM Recording.  
  Tempus Maledictum Guide Book now has a section for Alternate Alchemy.  
  Tempus Maledictum Guide Book now has a section for Combat behaviors.  
  Extra alchemy table in Breezehome.  
  New Lodgen, Texgen, Dyndolod outputs. As usual...  
  Some minor ini adjustments.  
  
  <b>KNOWN ISSUES</b>
  
  Crossbows can break contextual crosshair and sneak indicator.  
  Game saves sometimes list as corrupted. Restarting the game fixes this, and your saves are fine. I have no clue why this happens to a few of you.  
  Phenderix summoning spells occasionally fail to work. Unknown reason or cause.
  
  
  </details>

A vast majority of these fixes are thanks to the hard, ceaseless work by Wartortle. 

---

2023/02/17

Version 4.1.0

New save required.

<details>
  
  Added Skyland Common and Upper Furniture.  
  Added Animated Armoury - Legacy of the Dragonborn Displays.  
  
  Updated Sets of Skills - Improved UI.  
  Updated Standardization of Spelling of Sets of Skills.  
  
  Removed ELIF - ENB Light Inventory Fix.  
  Removed Creation Club Armors Integration.  
  
  New custom Improve Camera ini.  
  New/updated MCM Recordings.  
  Removed double statue outside of Whiterun.  
  Removed snow texture Lod issue at Windhelm entrance.  
  Quicklight works as expected now, even in first person with nothing equipped.  
  Potions and ingredients are no longer insanely out of scale in the inventory menus.  
  Navmesh fix for Solitude by Wartortle.  
  
  I'm not 100% sure if the VioLens recording will "work" in a sense, since the new one just unbinds that hotkey. It's possible this may have to be done manually, but if nothing else, it shouldn't be an issue for newcomers to the list. Sorry if this is annoying for you guys.  
  
  </details>

---

2023/02/12

Version 4.0.0

<details>
  
  **ADDITIONS**  
  
  Archery Gameplay Overhaul.  
  Dynamic Animation Replacer.  
  My Home is Your Home.  
  Beard Mask Fix.  
  Redbag's Solitude.  
  Convenient Horses.  
  Craftable Circlets.  
  Simple Blood Potion.  
  Lightfoot for Followers SPID.  
  Happy Little Shrubs.  
  Intuitive Dragon Ride Control.  
  Cult of the World Eater.  
  Wards Functionality Extended.  
  Magic Sneak Attacks.  
  Improved Camera.  
  Runic Dawnguard.  
  Immersive Equipment Displays.  
  Simple Dual Sheath.  
  ABT AE - Arrows and Bolts Tweaks.  
  Papyrus Tweaks NG.  
  LotD Hall of Forgotten TCC Patches.  
  Sets of Skills UI.  
  SkySA - Combat Behavior Compulsion.  
  SkySA - First Person View SSE.  
  SkySA - Intense Combat.  
  Animation Queue Fix.  
  Weapon Keyword Unification Project.  
  Diverse Random Normal Attack.  
  Reduce Attack Skating Movement.  
  Dynamic Animation Replacer Multiple Power Attacks Animations.  
  Don't Sheathe Bound Weapons DAR Animations.  
  Dynamic Dodge Animation.  
  Disable Turn Animation.  
  Payload Interpreter.  
  Dynamic Fus Ro Dah.  
  Smooth Moveset.  
  SpellSword Moveset.  
  Dynamic Whirlwind Sprint.  
  Enemy Magelock - NPC Magic Casting Commitment.  
  EVG Conditional Idles.  
  EVG Animation Variance.  
  Goetia Animations - Conditional Shouts.  
  Conditional Werewolf Howl.  
  Artifact Animation Replacer - Wabbajack.  
  Axarien's Animations - Inigo.  
  Axarien's Animations - Kaidan.  
  Axarien's Animations - Lucien.  
  Axarien's Animations - Teldryn Sero.  
  Loki's Wade in Water.  
  Underdog Animations.  
  Underdog Falling Animations - Leaps of Faith Patch.  
  Tools Not Weapons.  
  Take a Seat.  
  Smooth Random Equip Animations (2H).  
  Smooth Random Equip Animations (Dagger).  
  Smooth Random Equip Animations (Unarmed).  
  Smooth Magic Casting Animation.  
  Vanargand Animations - Crossbows.  
  Vanargand Animations - Dual Wield Sneak Strikes.  
  Vanargand Animations - Dual Wield Sneak Thrusts.  
  Vanargand Animations - Sneak Archery.  
  Vanargand Animations - Sneak Idle Walk and Run.  
  Vanargand Animations - Sneak Strike Attacks.  
  Vanargand Animations - Sneak Thrust Attacks.  
  Vanguard - Bash Behaviors Overhaul.  
  DAR - Animated Fear.  
  DAR - Dynamic Swimming.  
  DAR - Dynamic Swimming - Argonian Mastery.  
  Dragon Animation Replacer.  
  Vanargand Animations - Mace Moveset.  
  Alik'r Swordsmanship for SkySA.  
  Attack Animations and Movesets.  
  Imperial Saddle Retexture.  
  Yee Haaaa Horse Saddle Retexture.  
  Rustic Clothing.  
  Common Furniture Retexture.  
  Rustic Furniture.  
  Better Bookcase.  
  Room Markers for Dumzbthar.  
  Lively's Convenient Horses Patches.  
  Lively's Deep Elf Race Patches.  
  Lively's Dwemer Gates No Respawn Patches.  
  Lively's Second Great War Patches.  
  ElSopa - Potions Redone Update - Patches.  
  Skyland Noble Furniture.  
  ENB Light Inventory Fix.  
  Aura's Inventory Tweaks.  
  Rudy Fix for Smoke.  
  Archery Rebalance.  
  Animation in Ashstorm.  
  Animation in Blizzard.  
  Animated Static Reload Fix NG.  
  Skyrim Spear Mechanic.  
  Animated Armoury.  
  Animated Heavy Armoury.  
  Difficulty Balance.  
  Empty Spell Sprint Hand Fix.  
  Better Power Attack Control.  
  Barter Limit Fix.  
  Fire Hurts NG.  
  Enhanced Death Cam.  
  Dynamic Collision Adjustment.  
  Don't Stay in Water.  
  Magic Leveling Fix.  
  Transcribe Spells - Convert Known Spells to Tomes.  
  Show Player in Menus.  
  Rain Extinguishes Fires.  
  Dual Wield Parrying Reimplementation for SSE.  
  Praedy's Chantry of Auriel AIO - SE.  
  Sets of Skills - Improved UI.  
  Misc Effects ENB Light.  
  Fluffy Snow.  
  Flame Atronach SE.  
  Flame Atronach SE - Optimized Textures.  
  Glowy Storm Atronach.  
  DART - Dynamic Animation Replacer Tool.  
  EVG Animated Traversal.  
  IED Preset for Simple Dual Sheath and EVG Conditional Idles.  
      
  **REMOVALS**  
  
  Dynamic Dungeon Loot.  
  Dev Aveza.  
  Ars Metallica.  
  Pumping Iron.  
  Dreughs of Skyrim.  
  All Geared Up Derivative.  
  Holds - Solitude.  
  New Beginnings - Live Another Life Extension.  
  Elemental Arrows.  
  Sneak Tools.  
  Jump Attack.  
  Immersive Fort Dawnguard.  
  Realistic Nord Ships.  
  Screenshot Helper.  
  Build Your Noble House.  

  **UPDATES**  
  
  Dwemer Gates Don't Reset.  
  CRAFT.  
  CoverKhajiits.  
  Armor Variants Expansion - Patch Collection.  
  Precision.  
  USMP Patch Emporium.  
  Second Great War.  
  Particle Patch for ENB.  
  Valhalla Combat.  
  Read or Take.  
  Infinity UI.  
  QuickLootEE.  
  Shadow of Skyrim.  
  Rainbows.  
  SPID For Footprints Fix.  
  Shooting Stars.  
  xLodgen.  
  ENB.  
  
  **FIXES**  
  
  Auri's bow and arrows are now craftable at the smithing forge instead of the tanning rack.  
  Lost Souls Inn no longer has a tree growing through it.  
  White Hall in Dawnstar should have functional navmeshing now.  
  
</details>

---

2023/01/21

Version 3.1.4

<details>
  
  Added Mrf's Markarth.  
  Added ElSopa - Noble Furniture.  
  Added More Lights for ENB - Blood Splatter Fix.  
  Added Auri - Thistlefoot Should Stay Outside.  
  Added Auri Dismount AI Fix.  
  Added Ancient Dwemer Metal - Mrf's Markarth Patch.  
  Added Legacy of the Dragonborn - Museum Exterior Fixes.  
  Added Salt and Wind - Vanilla Hair.  
  Added Bed Head - Vanilla Hair Replacer.  
  Added Standardization of Spelling of Sets of Skills.  
  
  Updated Dyndolod.  
  Updated powerofthree Tweaks.  
  Updated Lively's Patches.  
  Updated Better Third Person Selection.  
  
  Removed Unblended - Really Blended Roads.  
  Removed Snowy AF Markarth and Dwemer Ruins.  
  
  New Lodgen, Texgen, Dyndolod outputs. As usual.  
  
  Issues addressed:
   - Forgotten Vale has a map now.
   - Forgotten Vale doesn't crash anymore near the spiders on the hill.
   - Skuldafn doesn't crash anymore.
   - Karliah doesn't have missing eye textures anymore.
   - Companions no longer turn invisible when transforming into werewolves.
   - Lund's Hut looks nice again.
   - Riverwood doesn't have random floating ivy hanging about.
   - Akaviri Outpost doesn't have a visible black plane or a tree growing through it.
   - Winterhold Ruins Expanded doesn't have missing walls anymore.
   - Blood splatter decals aren't big weird 3D objects anymore.
   - Fixed sewer overlap in Solitude.
   - Navmesh/pathing in Whiterun market and around Elysium Estate won't be a problem anymore.
  
  </details>

---

2023/01/04

Version 3.1.3

Removed Creation Kit from compilation.

---

2023/01/04

Version 3.1.2

<details>
  
  Added Better Occlusion - COTN Falkreath.  
  Added Attack Speed Fix.  
  Added Mrf's Solitude.  
  Added Illustrious Whiterun.  
  Added Stony AF Markarth and Dwemer Ruins.  
  Added Some Braziers.  
  Added BURP - Spell Tomes.  
  Added ElSopa - Potions Redone.  
  Added SMIM Upper Furniture and Other Fixes.  
  
  Updated Lively's Patches.  
  Updated Treasure Hunter for SSE.  
  Updated 710's Patches.  
  
  New Lodgen, Texgen, Dyndolod outputs. As usual.  
  
  Dreugh enemy types should be easier now with Auto Calc Stats and PC Level Mult flags.  
  Rogue Class probably works just fine now.  
  LotD Navmesh stuff should be fixed up.  
  Divine Crusader quest should complete properly.  
  No more kid with black face bug in Solitude.  
  Water seams should all be fixed. If not all, then certainly a vast majority.  

  </details>

---

2022/12/25

Version 3.1.1

Merry Christmas!

<details>
  
Updated Lively's Patches.  
Updated Auto Elemental Cloaks.  
Updated Aspens Ablaze - Dyndolod 3 Addon.  
Updated Dyndolod.  
Updated Dyndolod Resources.  

Removed Pause Menu After Loading. This was primarily added because of Forgotten Dungeons, which we no longer use.  

Fixed issue with Candlestick missing textures via moving ENB Light above Particle Patch in the mod order.  
Fixed Kaidan black face bug.  
Reinstalled Skyland AIO to remove an extraneous plugin because I don't know how to read. Fixes floating Point the Way signs.  
New Lodgen, Texgen, Dyndolod, Synthesis outputs.  

</details>
  
---

2022/12/21

Version 3.1.0

New save not required, but I mean, you should start a new game.

<details>
  
Removed Time-Based Enemy Scaling (until I can test it further, then we shall see).  

Fixed some EasyNPC patches so people don't look stupid.  

Added a Tempus Maledictum Beginner's Guide to the ASLAL prison cell.

</details>

---

2022/12/20

Version 3.0.0

**New save required.**

<details>

Added Undeath - Classical Lichdom.  
Added Beast Skeletons Revised (Bitter Edition).  
Added Skeleton Replacer HD.  
Added Dragon Priest Fix - Behaviour Overhaul.  
Added Phenderix Elements.  
Added Creation Club Backpacks - Crafting Overhaul.  
Added Vlindrel Hall Remade.  
Added Auto Elemental Cloaks.  
Added ConsolePlusPlus.  
Added Skyrim Extended Cut - Saints and Seducers.  
Added Swiftly Order Squad - Simply Order Summons integration.  
Added Alternate Alchemy.  
Added Legacy of the Dragonborn SSE - Settings Loader.  
Added Precision.  
Added Valvalis Combat - Visceral Tactics.  
Added Animation Motion Revolution.  
Added Valhalla Combat.  
Added Kanjs Chaurus Egg and Staff.  
Added Learn Ingredients.  
Added C. Culminated ENB for Cathedral Weathers.  
Added Ice Lake Dragon Retexture.  
Added Ancient Dwemer Metal - My patches - FINAL SE VERSION Update v6.  
Added Dreughs of Skyrim - Fathom's Creature Series.  
Added Sets of Skills - a Skyrim Class Mod - Settings Loader.  
Added Set of Skills.  
Added Time-Based Enemy Scaling.  
Added Time-Based Set of Skills - Time-Based Enemy Scaling Sets of Skills Patch.  
Added Immersive DragonFire - Apocrypha.  
Added Another Race Menu Rotation Mod.  
Added Dovah Den.  
Added Skyland AIO.  
Added Skyland - Ships and Shacks.  
Added Water in Wells - mesh-only animated wells.  
Added Rudy HQ - More Lights for ENB SE - Soul Gems.  
Added CC's Enhanced Ore Veins SSE - 2K - 9.0.1.  
Added Modest Mines 4K.  
Added FYX - 3D Stockades.  
Added FYX - 3D Stockades - Walls and Gate.  
Added Stockades of Skyrim 3D.  
Added 2K SMIM Whiterun Stockade.  
Added 2K Stockade.  
Added 2K Whiterun Stockade.  
Added Matching Mine Door.  
Added Riften Canals rounded - by Pfuscher.  
Added Praedy's Castle Volkihar - SE.  
Added FYX - Riften Canal and Round Posts.  
Added Northfire's Dungeons (nordic ruins and caves).  
Added RUSTIC RELIEFS.  
Added Northfire's Rustic Clever Underground Nordic Ruins.  
Added Skyrim Remastered - Caves 2K Parallax.  
Added ElSopa HD - The Smelter SE.  
Added ElSopa - HD Medieval Anvil SE.  
Added Renthal's workbench.  
Added Renthals's tanning rack.  
Added ElSopa - HD Grindstone Redone SE.  
Added ElSopa HD - Strider And Netches SE.  
Added Mrf's Carts.  
Added Epic Doors of Whiterun SE.  
Added Skyland Whiterun-AIO - Epic Doors of Whiterun patch SE.  
Added Smaller Potion of Blood.  
Added SD's Farmhouse Fences SE.  
Added Less Distracting Blowing Snow Effects for ENB Particle Patch.  
Added Interior Floating Fog Remover.  
Added real life snowflakes SSE.  
Added EasyNPC.  
Added Marvelous Mage Followers.  
Added Not Quite Vanilla NPC Overhaul - Argonians.  
Added Pandorable's Initiates.  
Added eeekie's High-Poly Teldryn Sero.  
Added eeekie's Enhanced NPCs.  
Added eeekie's Kaidan Long Hair.  
Added Elevated NPCs.  
Added NVICO - Townies.  
Added Northbourne NPCs.  
Added eeekie's High-Poly Real Delphine.  
Added Pandorable's NPCs.  
Added The Devil drinks Black Briar - High Poly Maven.  
Added Bijin Warmaidens SE.  
Added Beards of Power - Sons of Skyrim.  

Updated Enhanced Reanimation.  
Updated Embers XD.  
Updated CRAFT Smarter LotD Forge.  
Updated The Timelost Dwemer.  
Updated Simply Order Summons.  
Updated The Great Town of Ivarstead Patch Collection.  
Updated TrueHUD - HUD Additions.  
Updated Wintersun - Faiths of Skyrim - Legacy Settings Loader.  
Updated Particle Patch for ENB.  
Updated Water for ENB.  
Updated COTN Morthal Patch Collection.  
Updated Spell Perk Item Distributor (SPID).  
Updated Unofficial Skyrim Modders Patch - USMP - Patch Emporium.  
Updated COTN Dawnstar Patch Collection.  
Updated Forgotten Argonian Roots.  
Updated Legacy of the Dragonborn Creation Club Patches.  
Updated Legacy of the Dragonborn SSE - The Curators Companion.  
Updated DynDOLOD.  
Updated DynDOLOD Resources.  
Updated Legacy of the Dragonborn SSE.  
Updated Moons And Stars.  
Updated Auto Input Switch.  
Updated Keyword Item Distributor (KID).  
Updated Contextual Crosshair.  
Updated ENB Input Disabler.  
Updated NPC AI Process Position Fix - NG.  
Updated Use Or Take SKSE.  
Updated Stay at the System Page - AE.  
Updated True Directional Movement.  
Updated Unique Map Weather.  
Updated Wash That Blood Off 2.  
Updated Better Third Person Selection - BTPS.  
Updated Completionist - Skyrim Completion Tracker (SE-AE).  
Updated Frozen Electrocuted Combustion.  
Updated Storm Lightning for SSE and VR (Minty Lightning 2019).  
Updated MCM Helper.  
Updated Crash Logger SSE VR.  
Updated powerofthree's Tweaks.  
Updated powerofthree's Papyrus Extender.  
Updated The Ultimate Dodge Mod - SPID Patch.  
Updated The Ultimate Dodge Mod - SPID Patch - Settings Loader.  

Removed Wait Your Turn - Enemy Circling Behaviour.  
Removed Undeath Immersive Lichdom SSE.  
Removed Undeath - The Ascension.  
Removed Undeath ZIA Patch.  
Removed Shield Of Stamina - Blocking Redux.  
Removed Counter Damage.  
Removed Elden Parry.  
Removed Block Enchantments.  
Removed Smart NPC Potions.  
Removed Action Based Projectiles.  
Removed Alternate Start - The Last Dwemer.  
Removed Copy and Paste in Console.  
Removed Player Rotation in ShowRaceMenu.  
Removed Classic Paralysis.  
Removed Blubbos PineTreeReplacer 2022.  
Removed Blubbos Snow Pine Tree Replacer.  
Removed Serio's ENB.  
Removed Tempus Maledictum - Super Duper Facegen.  

Reinstalled Animated Forge Water.  

Removed the Scripts folder from Tortle's Patches.  
Changed Curator Storage Token COBJ to require 200 Gold instead of 1.  
Changed Curator Storage Token Breakdown COBJ to yield 100 gold instead of 1.  
New Lodgen, Texgen, Dyndolod, Synthesis outputs.  

Look, I'll be honest, we've been working really hard and pretty much nonstop, so I undoubtedly forgot to write some things down in this here changelog. Apologies.  

  </details>

---

2022/11/20

Version 2.3.0

**New save required.**

<details>
  
  <summary>Click to expand</summary>
  
  Added The Distinct Great Ivarstead Interiors.  
  Added The Great Town of Ivarstead Patch Collection.  
  Added Dev Aveza Hotfix.  
  Added Oxygen Meter.  
  
  Removed Forgotten Dungeons SSE.  
  Removed CoMAP.  
  
  New Texgen, Dyndolod, Synthesis outputs.  
  
  Added Tortle's Patches and Itslways710's Patches.
  
  To elaborate on these added patches, here's a list of known issues that were fixed:
  
   - Brotherhood of Old tent clips Elysium Estate.
   - Fur Vested Clothes and Linwe's Armor have floating hands.
   - Markarth stables door is inaccessible.
   - Morthal Inn navmesh is broken.
   - Restoring Order can't be done.
   - Various clipping/floating issues with the Redguard CC mod.
   - Dev Aveza hopefully fixed.
   - Floating trees outside of Treva's watch.
   - Glitchy landscape in Solitude Walkway
   - Some firewood piles are not lootable
   - Door out of Solitude to the Solitude walkway was broken
   - Door to Riften Noble's Quarters was broken
   - Doors sometimes say where you are, not where you are going.
   - Raven Rock has some clipping boats and bad navmesh.
   - Floating lantern in Salvius Farm.
   - Floating beehive outside of Helgen.
   - Water seam at Riften Docks.
   - Water seam outside of Solitude.
   - Old Hroldan Inn was broken.
   - Floating firewood in Fort Dawnguard.
   - Floating candles in Blue Palace.
   - Tree lod is purple in places.
  
</details>

---

2022/10/19

Version 2.2.2

Solitude looked like shit. I fixed it.

I can do this all night.

---

2022/10/19

Version 2.2.1

Forgot to actually install the Unslaad English Voiced Add-on after downloading it.  Go team.

---

2022/10/19

Version 2.2.0

New save required.

<details>
  
  <summary>Click to expand</summary>

Added Distinct Interiors - Fixes.  
Added Forgotten Magic Redone - Ordinator Compatibility Patch.  
Added Apophysis Dragon Priests Masks SE - Kohnarik Accoutrements Patch.  
Added Cathedral Weathers Unofficial Update.  
Added The Holds - Solitude.  
Added CRAFT - Smarter LotD Forge.  

Removed Weather for ENB.  
Removed Unslaad SE Patches. These are now contained in the main mod.  
Removed Enhanced Solitude.  
Removed Misc Tweaks - Decluttered Crafting Menus.  
Removed Solitude Skyway.  

Updated USMP Patch Emporium.  
Updated Dyndolod Resources.  
Updated Acquisitive Soul Gems Multithreaded.  
Updated More Plantable Plants for Creation Club.  
Updated Unslaad SE.  
Updated The Timelost Dwemer.  
Updated Timelost Dwemer Essentials Patcher.  
Updated Sneak Tools SE.  
Updated Regional Features -- Riverwood Oaks.  
Updated Unblended - Really Blended Roads.  
Updated Palaces and Castles Enhanced Patch Collection.  
Updated Glorious Doors of Skyrim.  
Updated Jumping Attack.  
Updated Vigilant.  
Updated Unslaad.  
Updated ODIN spells for NPCS.  
Updated Legacy of the Dragonborn Patches (Official).  
Updated Rob's Bug Fixes - COTN Morthal.  
Updated Rob's Bug Fixes - COTN Falkreath.  
Updated Rob's Bug Fixes - COTN Dawnstar.  
Updated Lively's Patches for Tempus Maledictum.  
Updated Shadow of Skyrim.  
Updated Dyndolod SE.  

New outputs (Lodgen, Road Generator, Texgen, Dyndolod, Occlusion, Nemesis, Synthesis).  

  </details>

---

2022/09/22

Version 2.1.2

No changes, just a compile to make the list installable again. Sorry for the extended delay, sincerely. I hate when my lists are down.

2022/09/09

Version 2.1.1

<details>
  
  <summary>Click to expand</summary>

Added Tempus Maledictum Main Menu Replacer.  

Updated Beyond Reach.  
Updated Synthesis Output.  

Messed around with compass markers. Still not great but it's better for now.

   </details>  

---

2022/09/07

Version 2.1.0

New save required.  

<details>
  
  <summary>Click to expand</summary>
  
Added Wartortle's Shadow of Skyrim Autostart.  
Added Wartortle's Marshlands Fixes.  
Added Keyboard Shortcuts Fix.  
Added Acquisitive Soul Gems Multithreaded - Settings Loader.  
Added The White Phial - Tweaks and Enhancements.  
Added Handy Crafting and Spells.  
Added Help Extender.  
Added Ice Wraith Teeth Collision Fixes.  
Added Infinity UI.  
Added Compass Navigation Overhaul.  
Added Elemental Arrows (yeah I totally forgot to do that, shut up).  
Added Rainbows SE.  
Added Wonders of Weather.  
Added Wonders of Weather - Settings Loader.  
Added MiscFix.  
Added Favor Quests Separated.  
Added Legacy Safehouse Plus.  
Added Simplicity of Snow.  
Added Better SkyUI Config - Reading Fix.  
Added Fixed Mesh Lighting.  
Added Simplicity of Snow - Cities of The North.  
Added CoMAP - Common Marker Addon Project.  
Added Forgotten Vale Map Markers.  
Added NPCs React to Necromancy.  
Added Legacy of the Dragonborn - Serana's Safehouse Room.  
Added Jumping Attack.  
Added Better SkyUI Config - Reading Fix.  

Removed Pickpocket Reset.  
Removed Skyrim Reputation.  
Removed R.A.S.S. - Rain and Snow Shaders.  
Removed Better Dynamic Snow.  

Updated Audio Overhaul Skyrim.  
Updated Cities of the North - Falkreath Patch Collection.  
Updated Palaces and Castles Enhanced Patch Collection.  
Updated Assorted Mesh Fixes.  
Updated Shadow of Skyrim.  
Updated Glowing Mushroom Collision Fixes.  
Updated The Wheels of Lull.  
Updated Lively's Patches for Tempus Maledictum.  
Updated The Brotherhood of Old.  
Updated UnBlended - Really Blended Roads.  
Updated Legacy of the Dragonborn - Follower Room Patches.  
Updated Hall of Forgotten Patches.  
Updated A Clear Map of Skyrim and Other Worlds.  

New Lodgen, Texgen, Dyndolod, Nemesis outputs.  

   </details>
   
---

2022/08/20

Version 2.0.2

<details>
  
  <summary>Click to expand</summary>

- Removed Cold Region Behavior - Beta Test.  
- Removed Wet and Cold - Fur Hoods Fix.  

 </details>
 
---

2022/08/20

Version 2.0.1

<details>
  
  <summary>Click to expand</summary>

- Added R.A.S.S. - Rain Ash And Snow Shaders.  
- Added Cold Region Behavior - Beta Test.  
- Added Wet and Cold - Fur Hoods Fix.  
- Added Cold Region Behavior - Fur Hoods Fix.  

- Updated Lively's Patches for Tempus Maledictum.

- Removed Glow Be Gone.  
- Removed Glow Be Gone GhostFX Workaround.  
- Removed Wet and Cold.  

- Fixed an issue with Uncapper.ini.  
- Fixed a lot of areas with grass growing over roads and structures.  
- Fixed Evette Sans' shop marker to make her actually lean on the damn counter.  
- Fixed Ivarstead and Realistic Nord Ships to play more nicely together.  
- Fixed a bunch of stupid trees and stupid plants growing in stupid places.  
- New dyndolod output.  

</details>

---

2022/08/18

Version 2.0.0

Also it's my birthday. Yay.  

<details>
  
  <summary>Click to expand</summary>

- Added Splashes of Storms.  
- Added Shadow of Skyrim.  
- Added Quick Inventory.  
- Added Player Rotation in ShowRaceMenu.  
- Added NPC Dialogue Audio Enhancer.  
- Added Blackreach Tentacle Mesh Fix.  
- Added Better Dirt Cliffs and Alphas.  
- Added Skyrim Remastered - Glaciers and Ice.  
- Added Tamrielic Grass.  
- Added Footprints Sand Patch.  
- Added Realistic HD Food Remastered.  
- Added Realistic HD Baskets Remastered.  
- Added Charming Nirnroots.  
- Added Regional Features - Riverwood Oaks.  
- Added Caves - More Accurate Collision.  
- Added Bruma Misc Fixes.  
- Added Sahrotaar Must Die.  
- Added High Poly Dragonborn Ingredients Retextured.  
- Added CoverKhajiits.  
- Added GhostFX Workaround.  
- Added ENB Light for Apocrypha.  
- Added JS Dwemer Puzzle Cube SE - Glowmapped.  
- Added Sprites or Spectres - ENB Light.  
- Added JS Dwemer Control Cube SE - Glowmapped.  
- Added JS Dwemer Artifacts SE - Glowmapped.  
- Added Cathedral - 3D Lavender.  
- Added Cathedral - 3D Tundra Cotton.  
- Added Thistle by Mari.  
- Added ElSopa - Azura's Star Redone.  
- Added ElSopa - Azura's Star Redone - ENB Light.  
- Added Light Horses of Skyrim (Realistic Body and Fur).  
- Added Ulvenwald - Forest Overhaul.  
- Added Blubbo's Pine Tree Replacer 2022.  
- Added Blubbo's Snow Pines Replacer.  
- Added Skyrim Landscape and Water Fixes.  
- Added Deathbell by Mari.  
- Added ENB Light for Deathbell by Mari.  
- Added Blackthorn Manor - Fallen Trees Patch.  
- Added Blackthorn Manor - CFTO Patch.  
- Added Blackthorn Manor - Cathedral Landscapes Patch.  
- Added Blackthorn Manor - Anniversary Edition Autosorting Patch.  
- Added Kaiden 2 Shackles Fix.  
- Added Moons and Stars.  
- Added Aspens Ablaze Autumnal Variety.  
- Added Webs SE.  
- Added JK's Markarth.  
- Added The Great Village of Mixwater Mill.  
- Added The Great City of Dragon Bridge.  
- Added The Great Town of Ivarstead.  
- Added The Great Village of Kynesgrove.  
- Added The Great Cities - Resources.  
- Added Holds the City Overhaul - Modular.  
- Added Winter is Coming - Cloaks (no plugin).  
- Added Holds Patching Center.  
- Added Holds - Root Block Fix.  
- Added Anga's Mill - Cities of the North Addon.  
- Added The Great Settlement of Kolskeggr Mine.  
- Added Elysium Estate - Lanterns of Skyrim II Patch.  
- Added Lanterns of Wyrmstooth.  
- Added Cities of the North - Assorted Mesh Fixes Patch.  
- Added Unique Doors for CotN Dawnstar.  
- Added The Distinct Interiors.  
- Added The Distinct Cities of the North Interiors.  
- Added Cities of the North - Winterhold - Partitioned Meshes for Lighting.  
- Added Cities of the North - Morthal - Partitioned Meshes for Lighting.  
- Added Cities of the North - Dawnstar - Partitioned Meshes for Lighting.  
- Added Skyrim Skill Uncapper - Simplified Ordinator Preset.  
- Added Shooting Stars SE.  
- Added Enhanced Solitude Terrain Patch.  
- Added Beyond Skyrim - Bruma - Milk Thistle patch for Thistle by Mari SE.  

- Updated UnBlended - Really Blended Roads.  
- Updated Creation Club Open Helmets.  
- Updated Audio Overhaul Skyrim.  
- Updated moreHUD SE - Legacy Settings Loader.  
- Updated Zim's Immersive Artifacts.  
- Updated More Plantable Plants for Creation Club.  
- Updated SSE Display Tweaks.  
- Updated Unofficial Skyrim Creation Club Content Patch.  
- Updated USMP Patch Emporium.  
- Updated A Clear Map of Skyrim and Other Worlds FOMOD - PART 1.  
- Updated Beyond Skyrim - Assets.  
- Updated Beyond Skyrim - Bruma.  
- Updated The Wheels of Lull.  
- Updated Legacy of the Dragonborn Patches (Official).  
- Updated Rob's Bug Fixes - COTN Winterhold.  
- Updated COTN Dawnstar Patch Collection.  
- Updated Rob's Bug Fixes - COTN Morthal.  
- Updated Palaces and Castles Enhanced Patch Collection.  

- Removed Cathedral Landscape - Fixed Bridge Meshes - REALly Blended Roads for SMIM.  
- Removed Skyrim 3D Trees and Plants.  
- Removed Skyrim3DTrees and Plants 3dLOD Resources.  
- Removed Leaps of Faith 3D Trees and Plants Compatibility Patch.  
- Removed Rudy's More Lights Deathbell and Nirnroot For 3D Trees and Plants.  
- Removed JK's Skyrim.  
- Removed Rob's Bug Fixes - JK's Skyrim.  
- Removed JK's Skyrim - Clockwork Patch.  
- Removed JK's Skyrim - Fishing (CC) Patch.  
- Removed JK's Skyrim - Gray Cowl (CC) Patch.  
- Removed JK's Skyrim - Thunderchild Patch.  
- Removed Enhanced Solitude SSE - JK's AIO.  
- Removed Patch Between JK's Skyrim and Winterhold Ruins.  
- Removed Icy Windhelm - JK's Skyrim Patch.  
- Removed Thanedom Assets.  
- Removed Kingdom of Eastmarch.  
- Removed CFTO - JK's Skyrim Patch.  
- Removed Pets of Skyrim - JK's Skyrim Compatibility Patch.  
- Removed JK's Skyrim and The Marshlands Patch.  
- Removed Astral Magic 2.  

- New custom patches for various things.  
- Removed a few custom patches for obvious reasons.  
- New Texgen, Lodgen, Dyndolod, Allgud outputs.  

</details>

---

2022/08/07

Version 1.1.1

<details>
  
  <summary>Click to expand</summary>
- Fixed a bad meta for High Poly Project.

</details>
---

2022/08/06

Version 1.1.0

<details>
  
  <summary>Click to expand</summary>
- Added elwap's Hidden Map Markers for Mod Locations.  
- Added Auri - Deluxe.  
- Added Serana Replacer.  
- Added Horses Simply Turn Better.  
- Added Horses For Followers.  
- Added Simply Order Summons.  
- Added Simple Follower Extension.  
- Added No Crime Teleport.  
- Added Project AHO - Unique Smelter Patch.  
- Added Project AHO - Security Locks Overhaul Patch.  
- Added Race Compatibility Dialogue - Project AHO Patch.  
- Added CrashLogger VR.  
- Added Hearthfire Extended Aquarium Patch.  
- Added Bring Meeko to Lod.  
- Added Bijin Skin.  
- Added Project AHO - Start When You Want.  
- Added High Poly Head.  
- Added Courageous Women of Skyrim.  
- Added Pride of Skyrim.  
- Added Expressive Facial Animation - Male Edition.  
- Added Expressive Facial Animation - Female Edition.  
- Added Expressive Facegen Morphs.  
- Added Hvergelmir's Aesthetics - Brows.  
- Added Brows for High Poly Head.  
- Added Northborn Scars.  
- Added Northborn Scars for High Poly Head.  
- Added Hvergelmir's Aesthetics - Beards.  
- Added Beards for High Poly Head.  
- Added Wider MCM Menu for SkyUI.  
- Added Remove QuickSave Button from SkyUI System Menu.  
- Added Dragons Shout With Voice.  

- Removed Diversity - A Character Overhaul.  
- Removed Diverse Skyrim.  
- Removed Diversity - Valindor missing Facegen Data.  
- Removed Guards Armor Replacer - Diversity Patch.  
- Removed Project AHO Delay Slavery.  
- Removed Reverie Skin.  
- Removed Crash Logger.  
- Removed Butterflies Land True.  
- Removed Nether's Follower Framework.  
- Removed Travellers of Skyrim - Vanilla Version.  
- Removed Travellers of Skyrim - Dragonborn and Bags and Pouches Addon.  
- Removed Maximum Carnage.  
- Removed Diverse Skyrim - Battle of Whiterun Fix.  

- Updated Cities of the North - Falkreath Patch Collection.  
- Updated Dragonborn Aptitude.  

</details>

---

2022/07/29

Version 1.0.1

<details>
  
  <summary>Click to expand</summary>
- Redownloaded Haugbui - Legacy of the Dragonborn Patch. Archive was corrupt on my end or something.  

</details>
  
---

2022/07/29

Version 1.0.0

<details>
  
  <summary>Click to expand</summary>
- Added Stay At The System Page - AE.  
- Added I'm Walkin Here.  
- Added Haugbui - A Draugr Overhaul.  
- Added Draugr Upgrades and Improvements.  
- Added Cathedral Weathers MCM.  
- Added Animated Forge Water.  

- Removed The Great Cities - Minor Cities and Towns.  
- Removed The Great Village of Mixwater Mill.  
- Removed Rob's Bug Fixes - TGC Mixwater Mill.  
- Removed The Great Town of Ivarstead.  
- Removed Rob's Bug Fixes - TGC Ivarstead.  
- Removed The Great Village of Kynesgrove.  
- Removed Great City of Dragon Bridge - CFTO Ferry Integration.  
- Removed Centered Blue Palace Throne.  
- Removed The Great Cities of JK's North.  
- Removed Skaal Village Overhaul.  
- Removed AAE Ultimate Edition.  
- Removed Maximum Carnage.  
- Removed Thanedom Darkwater Crossing.  

- Removed Skyrim - Patch.bsa from Stock Game folder.  
- Added a lot of new custom patches and removed some others that ended up getting replaced/outdated.  
- Fixed like 40 known issues.  

</details>

---

2022/07/20

BETA 5

Consider this primarily a bug fix + combat update.

<details>
  
  <summary>Click to expand</summary>
- Added Markarth Outskirts.  
- Added Pause After Loading - Auto Unpause.  
- Added Shield of Stamina - Blocking Redux.  
- Added Wait Your Turn - Enemy Circling Behavior.  
- Added Counter Damage.  
- Added Inigo - Bloodchill Manor Patch.  
- Added QuickLoot EE - Settings Loader.  
- Added Block Enchantments.  
- Added Apocalypse Spells for Spellcasters.  
- Added Action Based Projectiles.  
- Added Odin Spells for Spellcasters.  
- Added Maximum Carnage.  
- Added Smart NPC Potions.  
- Added Dragonborn Aptitude.  
- Added UnBlended - Really Blended Roads.  
- Added Silver Objects SMIMed.  
- Added VIGILANT - Elite Vigilant Hood Fix.  
- Added VIGILANT - Immersive Text Edit.  
- Added Astral Magic 2.  
- Added Master Spell Runes.  
- Added Use or Take SKSE.  
- Added Elden Parry.  
- Added SPID For Footprints.  
- Added SPID For Footprints Fix.  
- Added Phendrix Magic Evolved SPID - Spells for NPCs.  
- Added Markarth Entrance Overhaul Fixed.  
- Added Valravn - Integrated Combat of Skyrim.  
- Added Valravn Uncloaked.  
- Added The Ultimate Dodge Mod Reborn.  
- Added Immersive World Encounters - Settings Loader.  
- Added Cathedral Weathers MCM - Settings Loader.  
- Added The Ultimate Dodge Mod - SPID Patch.  
- Added The Ultimate Dodge Mod - SPID Patch - Settings Loader.  
- Added VioLens - A Killmove Mod - Settings Loader.  
- Added Wyrmstooth - Settings Loader.  
- Added XP32 Maximum Skeleton - Settings Loader.  
- Added moreHUD SE - Settings Loader.  
- Added Unread Books Glow SSE - Settings Loader.  
- Added Imperious - Races of Skyrim - Settings Loader.  
- Added Ordinator - Perks of Skyrim - Settings Loader.  
- Added Apocalypse - Magic of Skyrim - Settings Loader.  
- Added Wintersun - Settings Loader.  
- Added Growl - Werebeasts of Skyrim - Settings Loader.  
- Added Symmermyst - Enchantments of Skyrim - Settings Loader.  
- Added Sacrosanct - Vampires of Skyrim - Settings Loader.  
- Added Better Third Person Selection.  

- Updated A Matter of Time - Settings Loader.  
- Updated Creation Club Open Helmets.  
- Updated Dyndolod Output.  

- Made a bunch of new custom patches.  
- Disabled/moved a bunch of trees and lanterns.  
- Turned on profile specific saves cuz I forgot.  

</details>

---

2022/07/15

BETA 4

<details>
  
  <summary>Click to expand</summary>
- Updated Read or Take SKSE.  

- Added Skyrim Skill Uncapper Fixed.  
- Added Skyrim Skill Uncapper INI for Ordinator.  
- Added Pets of Skyrim - JK's Skyrim Patch.  
- Added Rob's Bug Fixes - COTN Winterhold.  
- Added JK's Skyrim and The Marshlands Patch.  
- Added CC Horse Armor No Blacksmith Dialogue.  
- Added Creation Club Open Helmets.  
- Added Pause Menu After Loading.  

- Removed Equus - Horse Sounds Redesigned.  
- Removed Eviscerate.  
- Removed Settlements Expanded.  
- Removed Landscape Fixes for Grass Mods. Possibly only temporary.  
- Removed Maids 2: Deception.  
- Removed Legendary Armors - DeserterX Collection.  
- Removed The Great Village of Kynesgrove.  
- Removed Enhanced Solitude Docks and all related patches.  

- New lodgen, texgen, dyndolod outputs.  
- Bunch of new custom patches.  
- Various mod/load order adjustments.  

</details>

---

2022/07/09

BETA 3

<details>
  
  <summary>Click to expand</summary>
- Disabled various bushes, rocks, plants, and trees that were otherwise interfering with doors and landscape edits.  
- Reinstalled and added various patches for Embers XD.  
- Added Screenshot Helper.  
- Removed Disable Snow Grass - For Vanilla and Cathedral Landscapes.  
- Removed Dynamic Things.  
- Added JS Shrines of the Divines.  
- Added Double Bright Quick Light.  
- Changed ENB screenshot key to Insert because it was pissing me off when I used Print Screen to take a screenshot and I would end up with two copies of every image.  
- Updated Dyndolod Output.  

Known issues that were fixed:  
 - Markarth, Morthal, Falkreath, Solitude Skyway, Blue Palace Courtyard, and many other locations should have greatly reduced jank and clipping and whatnot. This does NOT mean I cleared every location or got every instance of any object that's placed incorrectly, but I definitely got a lot of them. This is the sort of thing that will take a long time.  
 - Fire pits should no longer have missing textures.  
 - Blackthorn's initial note should no longer be riddled with typos and grammatical errors.  
 - Screenshots SHOULD save properly now, in your `Stock Game\[NoDelete]Screenshots` path.  

If any of the items listed above are NOT fixed, please notify me immediately. It's a lot for one person to check...

</details>

---

2022/07/06

BETA 2

<details>
  
  <summary>Click to expand</summary>
- Hotfix to add patch for LotD and Enhanced Solitude.

</details>

---

2022/07/05

BETA 1

Initial public release.
