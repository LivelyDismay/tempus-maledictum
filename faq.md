## Tempus Maledictum Frequently Asked Questions

### Table of Contents
- [Tempus Maledictum Frequently Asked Questions](#tempus-maledictum-frequently-asked-questions)
  - [Table of Contents](#table-of-contents)
  - [Hotkeys?](#hotkeys)
  - [Can I change some bindings?](#can-i-change-some-bindings)
  - [My game crashes when I launch from MO2. Help!](#my-game-crashes-when-i-launch-from-mo2-help)
  - [When I start Tempus Maledictum, the game is zoomed in!](#when-i-start-tempus-maledictum-the-game-is-zoomed-in)
  - [When I close my game, I get strange behavior with my mouse. I can't click on other windows. What's up with that?](#when-i-close-my-game-i-get-strange-behavior-with-my-mouse-i-cant-click-on-other-windows-whats-up-with-that)
  - [How do I change my FOV?](#how-do-i-change-my-fov)
  - [Can I add/remove/edit/change/clean x mod?](#can-i-addremoveeditchangeclean-x-mod)
  - [What are the minimum requirements / recommended specs for this list?](#what-are-the-minimum-requirements--recommended-specs-for-this-list)
  - [I'm having low FPS / I am not happy with my performance. What can I do?](#im-having-low-fps--i-am-not-happy-with-my-performance-what-can-i-do)
  - [What are these icons in my inventory / how do I keep track of LotD displays?](#what-are-these-icons-in-my-inventory--how-do-i-keep-track-of-lotd-displays)
  - [There's a bunch of NPC Replacer mods in MO2 that are disabled. Can I turn them on?](#theres-a-bunch-of-npc-replacer-mods-in-mo2-that-are-disabled-can-i-turn-them-on)
  - [I don't like the way certain NPCs look. Can I change it?](#i-dont-like-the-way-certain-npcs-look-can-i-change-it)
  - [I chose a Race other than Deep Elf but I still get the Deep Elf stuff added to my inventory. Why?](#i-chose-a-race-other-than-deep-elf-but-i-still-get-the-deep-elf-stuff-added-to-my-inventory-why)
  - [Can I disable/edit killmoves?](#can-i-disableedit-killmoves)
  - [Claw weapons are really bad and I'm having trouble hitting enemies with them. What gives?](#claw-weapons-are-really-bad-and-im-having-trouble-hitting-enemies-with-them-what-gives)
  - [I am experiencing crashes. What do I do?](#i-am-experiencing-crashes-what-do-i-do)
  - [Sometimes I notice a faint white glow around my character, usually around grass. Is there a fix?](#sometimes-i-notice-a-faint-white-glow-around-my-character-usually-around-grass-is-there-a-fix)
  - [My armor / shield / cape / helmet / beard / etc is clipping! Can you fix it?](#my-armor--shield--cape--helmet--beard--etc-is-clipping-can-you-fix-it)
  - [Can I hide my backpack?](#can-i-hide-my-backpack)
  - [Everything is too bright, can you make it have some sort of realistic immersive darkness?](#everything-is-too-bright-can-you-make-it-have-some-sort-of-realistic-immersive-darkness)
  - [Everything is too dark, can I brighten it up somehow?](#everything-is-too-dark-can-i-brighten-it-up-somehow)
  - [I'm having a hard time finding Spell Tomes. Where are they?](#im-having-a-hard-time-finding-spell-tomes-where-are-they)
  - [I found an exploit / this armor is way too good / this weapon is too strong. Will you fix it?](#i-found-an-exploit--this-armor-is-way-too-good--this-weapon-is-too-strong-will-you-fix-it)
  - [I went to Elysium Estate but the ghost isn't there. How do I get the house?](#i-went-to-elysium-estate-but-the-ghost-isnt-there-how-do-i-get-the-house)
  - [Sprint swimming and getting out of the water makes me swim on land!](#sprint-swimming-and-getting-out-of-the-water-makes-me-swim-on-land)
  - [Is the world unleveled?](#is-the-world-unleveled)
  - [Where is Inigo?](#where-is-inigo)
  - [How do I start the Goldenhills Plantation CC stuff?](#how-do-i-start-the-goldenhills-plantation-cc-stuff)
  - [Can I buy you a drink?](#can-i-buy-you-a-drink)

---

### Hotkeys?

All default keyboard, mouse, and gamepad bindings are listed in Hotkey Reminder (F11). You can click the buttons to see if there are "combos" as well (for example, click the left trigger on the controller, and it shows you what happens if you were to press Trigger+D-pad buttons in-game). Pretty fancy.

[[Top]](#table-of-contents)

---

### Can I change some bindings?

Sure. Most are handled by the default settings in the game menu. Dual wield block is handled by an INI which must be changed manually, in the Dual Wield Block INI. Do note that INIs cannot be changed in-game; you have to exit the game to edit this binding.

Combat is a little more complex. The current set-up is as follows:
- Left Click: Attack
- Right Click: Block
- Mouse4 (side button): Power Attack
- Left Alt: Dodge

You can block/timed block/dodge in the middle of regular attacks. You can use dozens of different combos based on your pattern of regular attacks and power attacks. Some weapons even allow for charged attacks (holding S while holding Power Attack). Play around, see what you like.

Some animation movesets are only available for specific NPCs, factions, or unlocked with specific perks. The mod names in MO2 help explain when certain movesets are used, and by whom. Or just discover things naturally - probably more fun that way anyway, in my opinion.

If you want to also change what's listed in the Hotkey Reminder (F11) menu, open the MCM for Hotkey Reminder and disable the lock so you can edit the layout manually.

[[Top]](#table-of-contents)

---

### My game crashes when I launch from MO2. Help!

Make sure you disable any overlays - most notably, Medal.TV seems to cause this crash frequently for those with that program.

The other most common cause is an Antivirus (not Windows Defender; a third party antivirus like Webroot or Kaspersky or [Bitdefender](https://www.bitdefender.com/consumer/support/answer/28557/), etc). Disable those or exclude MO2/scriptextender/etc.

[[Top]](#table-of-contents)

---

### When I start Tempus Maledictum, the game is zoomed in!

Windows Scaling is messing with the game. To fix this:

- Go the folder you installed Tempus into
- Then go into the Stock Game folder
- Right click on the SkyrimSE.exe item
- Choose Properties
- Select the Compatibility tab at the top of that window
- Click the Change high DPI settings button
- Put a checkmark in the Override high DPI scaling behavior box
- Choose Application in the dropdown list just below the previous checkbox

Note: Wording may not be exact, but should be similar enough.

If this doesn't fix it, you can try editing the SSE Display Tweaks INI under the `Optionals & INI Overrides` section in MO2. It's at the bottom.

[[Top]](#table-of-contents)

---

### When I close my game, I get strange behavior with my mouse. I can't click on other windows. What's up with that?

I have no idea. Apparently it's something to do with MO2, since this isnt list-specific. Good news, though: there's an easy fix. `Ctrl`+`Alt`+`Delete` and then just cancel out of it. Fixes it right away.

[[Top]](#table-of-contents)

---

### How do I change my FOV?

`Left Shift + Home` opens the Improved Camera GUI. Navigate through the menus and adjust things to your liking. I would recommend saving your changes to a new profile. Easier that way.

[[Top]](#table-of-contents)

---

### Can I add/remove/edit/change/clean [x] mod?

You can do whatever you want. However, I am under no obligation to help you. This will be considered a violation of Rule 11 of the Discord server, and you will be removed from the official support channel.

Having said that, if you find and report a bug in the list, and you're trying to help fix it - of course I'm happy to listen. Trying to help me fix a bug native to the list does not violate Rule 11. That is a very important distinction to me.

### So you won't help me at all?

Man, I'd be glad to teach you some stuff about modding. [I thoroughly enjoy doing so.](https://github.com/LivelyDismay/Learn-To-Mod/wiki) What I don't like is when people demand I add or remove mods *for* them. I want to make MY list, not YOUR list. But if you *actually* want to learn, yeah, I'll help down in the general/social channels, for sure. Unfortunately, a vast majority of people aren't interested in learning, and I've grown rather jaded. Such is life.

[[Top]](#table-of-contents)

---

### What are the minimum requirements / recommended specs for this list?

I don't know, and I'll explain why:

Consider it a decision made for our collective sanity. For example, let's say we advised 6 gigs of vram. Then someone plays with 8 gigs of vram, but complains about only getting 85 fps instead of 200. Their specs aren't good enough...for them. This may sound like a gross exaggeration, but we've literally had people complain about dropping from 60 to 55 fps, so I promise you, that is a realistic scenario.

You'll just have to decide if it runs good enough for you - and if it doesn't, you'll have to make your own tweaks and figure out your own hardware. Sorry, but that's just one of the costs of owning your own PC.

[[Top]](#table-of-contents)

---

### I'm having low FPS / I am not happy with my performance. What can I do?

- Riverwood and Whiterun are pretty heavy areas. Some dips are to be expected. Try exploring a bit further to see if your issues are only in those areas.  
- Press Numpad* to disable Community Shaders.

This likely won't help much, as performance is drained more by draw calls than lighting. For the unaware: draw calls are the number of objects rendered on screen at any given time. So, things like city overhauls are far more performance-intensive than lighting and shadows. These mods are NOT easily removed, and will invalide official support.

If you are on a laptop:

Open your Nvidia Control Panel. In the Manage 3D Settings section, if you have multiple GPUs, the Global Settings for Preferred Graphics Processor should be, by default, set to auto-select. You should leave this as it is.

Instead, switch tabs the Program Settings, and add the Skyrimse.exe or fallout4.exe that is located in the folder named Stock Game inside the folder where you installed Tempus/Opus. Then, as the Preferred Graphics Processor for that program, choose the High-performance Nvidia Card.

If all of this is still unsatisfactory, then you'll just have to either deal with it or come up with a solution for your own hardware. Sorry, but that's just the way it is. The game is going on 15 years old, there's only so much you can do before the engine just gives up on you.

[[Top]](#table-of-contents)

---

### What are these icons in my inventory / how do I keep track of LotD displays?

![alt text](https://github.com/LivelyDismay/tempus-maledictum/blob/dd8e06f23d0654a81809df1938bb248b87bb5339/curators%20companion%20icons.png)  
These icons are very helpful.

[[Top]](#table-of-contents)

---

### There's a bunch of NPC Replacer mods in MO2 that are disabled. Can I turn them on?

No. They're all part of the EasyNPC output. They're already active in your game. Enabling these individual mods will break your game.

[[Top]](#table-of-contents)

---

### I don't like the way certain NPCs look. Can I change it?

Not without rerunning EasyNPC and choosing different replacers. This will invalidate official support, so please do not break that rule, or keep it in the rule-11 channels on discord.

[[Top]](#table-of-contents)

---

### I chose a Race other than Deep Elf but I still get the Deep Elf stuff added to my inventory. Why?

Because this mod is really meant to be used by regular mod users. People install it with the intent to use it. Having it in the modlist has adverse effects such as this. You can freely ignore these things, or take advantage of them. Either way, not really a bug, and something you'll have to figure out for yourself in regards to whether or not you want to use it.

[[Top]](#table-of-contents)

---

### Can I disable/edit killmoves?

Press F6 to open the CatHub/Kaputt GUI. Change to your liking.

[[Top]](#table-of-contents)

---

### Claw weapons are really bad and I'm having trouble hitting enemies with them. What gives?

I know. They're really bad. They have incredibly short range - especially in first person. This is an issue with Precision. Honestly, I'd strongly urge you to juse use a different weapon type. Grab some claws for the museum and that's about it. Sorry.

[[Top]](#table-of-contents)

---

### I am experiencing crashes. What do I do?

There is one known crash in the list, which is during the House of Horrors quest. If you choose the vanilla route (siding with Molag Bal), the game crashes if you skip or tab out of the final dialogue. Simply let this dialogue play out on its own, and you won't crash.

Other than that, we would need more details. Problems can often arise from using third-party Antivirus programs, or using OneDrive (both of these can interfere with MO2's ability to save, so if you're crashing on save/load, it's likely Antivirus/OneDrive issues).

For any other crashes, we'd have to see a crashlog. You can find us over on [Discord](https://discord.gg/livelymods).

Please remember that this was a very large update that was recently put out, and we are a very small team. The thousands of you will see more of the game in a day than the half dozen of us saw in three months. **I genuinely want to provide the best possible experience for you,** so please feel free to report bugs, and have some patience. We will address any issues when we can.

[[Top]](#table-of-contents)

---

### Sometimes I notice a faint white glow around my character, usually around grass. Is there a fix?

Yes and no. This is caused by Ambient Occlusion. You can turn it off if you want, but this will also make your game look a lot worse. Your call.

[[Top]](#table-of-contents)

---

### My armor / shield / cape / helmet / beard / etc is clipping! Can you fix it?

No. Unequip/unfavorite one of the items that's clipping, or simply deal with it.

[[Top]](#table-of-contents)

---

### Can I hide my backpack?

No. The `Hide Backpacks` mod only applies to 3 of the Creation Club backpack variants, not all of them. Like above, unequip it or learn to accept it.

[[Top]](#table-of-contents)

---

### Everything is too bright, can you make it have some sort of *realistic immersive darkness?*

No. It's a video game. I want to see.

[[Top]](#table-of-contents)

---

### Everything is too dark, can I brighten it up somehow?

'End' opens up the Community Shaders GUI. Adjust things as you like.

[[Top]](#table-of-contents)

---

### I'm having a hard time finding Spell Tomes. Where are they?

Spells are primarily now acquired through Spellforge. There's one in the starting prison cell along with enough materials for you to create 5 novice spells. You can also read the Spellforge Manual to teach yourself how to conjure your own Spellforge anywhere - please note that spells crafted at a custom Spellforge are more "expensive" than at placed Spellforges, such as the one in the Dragonborn Museum safehouse.

There are a few other Spellforges in the world as well. Go find them.

You can also still buy Spell Tomes, but the prices for them have been increased by 800%.

[[Top]](#table-of-contents)

---

### I found an exploit / this armor is way too good / this weapon is too strong. Will you fix it?

Probably not. It's a single player game. If you think something is too strong, don't use it. If you find an exploit, use self control. At the end of the day, you're not hurting anyone but yourself. If that's how you enjoy playing, then more power to you. I don't care at all.

Besides, this is an LotD list. There's going to be a lot of overpowered stuff. Get used to it.

[[Top]](#table-of-contents)

---

### I went to Elysium Estate but the ghost isn't there. How do I get the house?

You have to buy it now. Read the note attached to the front door of the estate.

[[Top]](#table-of-contents)

---

### Sprint swimming and getting out of the water makes me swim on land!

Jump. Or stop the sprint-swimming prior to exiting the water.

[[Top]](#table-of-contents)

---

### Is the world unleveled?

No.

[[Top]](#table-of-contents)

---

### Where is Inigo?

Dead.

[[Top]](#table-of-contents)

---

### How do I start the Goldenhills Plantation CC stuff?

You need to be level 15, then speak with an innkeeper in either Whiterun or Rorikstead. They will have a line of dialogue about work in the area.

[[Top]](#table-of-contents)

---

### Can I buy you a drink?

Sure can. I have a [Patreon](https://www.patreon.com/c/nicholasjae) or you can tip me through Venmo (@Nicholas-Jae).

[[Top]](#table-of-contents)
