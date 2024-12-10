## Tempus Maledictum Frequently Asked Questions



---

#### Hotkeys?

All default keyboard, mouse, and gamepad bindings are listed in Hotkey Reminder (F11). You can click the buttons to see if there are "combos" as well (for example, click the left trigger on the controller, and it shows you what happens if you were to press Trigger+D-pad buttons in-game). Pretty fancy.

---

#### Can I change some bindings?

Sure. Most are handled by the default settings in the game menu. Dodge is handled by The Ultimate Dodge Mod MCM, where the dodge key is the vanilla Sneak key (in the vanilla game menu key bindings) while the Sneak key is set in the MCM. Dual wield block is handled by an INI which must be changed manually, in the Dual Wield Block INI. Do note that INIs cannot be changed in-game; you have to exit the game to edit this binding.

If you want to also change what's listed in the Hotkey Reminder (F11) menu, open the MCM for Hotkey Reminder and disable the lock so you can edit the layout manually.

---

#### My game crashes when I launch from MO2. Help!

Make sure you disable any overlays - most notably, Medal.TV seems to cause this crash frequently for those with that program.

The other most common cause is an Antivirus (not Windows Defender; a third party antivirus like Webroot or Kaspersky or [Bitdefender](https://www.bitdefender.com/consumer/support/answer/28557/), etc). Disable those or exclude MO2/scriptextender/etc.

---

When I start Tempus Maledictum, the game is zoomed in!

Windows Scaling is messing with the game. To fix this:

- Go the folder you installed Magnum Opus into
- Then go into the Stock Game folder
- Right click on the SkyrimSE.exe item
- Choose Properties
- Select the Compatibility tab at the top of that window
- Click the Change high DPI settings button
- Put a checkmark in the Override high DPI scaling behavior box
- Choose Application in the dropdown list just below the previous checkbox

Note: Wording may not be exact, but should be similar enough.

If this doesn't fix it, you can try editing the SSE Display Tweaks INI under the `Optionals & INI Overrides` section in MO2. It's at the bottom.

---

#### How do I change my FOV?

`Left Shift + Home` opens the Improved Camera GUI. Navigate through the menus and adjust things to your liking. I would recommend saving your changes to a new profile. Easier that way.

---

#### Can I add/remove/edit/change/clean [x] mod?

You can do whatever you want. However, I am under no obligation to help you. This will be considered a violation of Rule 11 of the Discord server, and you will be removed from the official support channel.

Having said that, if you find and report a bug in the list, and you're trying to help fix it - of course I'm happy to listen. Trying to help me fix a bug native to the list does not violate Rule 11. That is a very important distinction to me.

---

#### So you won't help me at all?

Man, I'd be glad to teach you some stuff about modding. [I thoroughly enjoy doing so.](https://github.com/LivelyDismay/Learn-To-Mod/wiki) What I don't like is when people demand I add or remove mods *for* them. I want to make MY list, not YOUR list. But if you *actually* want to learn, yeah, I'll help down in the general/social channels, for sure. Unfortunately, a vast majority of people aren't interested in learning, and I've grown rather jaded. Such is life.

---

#### What are the minimum requirements / recommended specs for this list?

I don't know, and I'll explain why:

Consider it a decision made for our collective sanity. For example, let's say we advised 6 gigs of vram. Then someone plays with 8 gigs of vram, but complains about only getting 85 fps instead of 200. Their specs aren't good enough...for them. This may sound like a gross exaggeration, but we've literally had people complain about dropping from 60 to 55 fps, so I promise you, that is a realistic scenario.

You'll just have to decide if it runs good enough for you - and if it doesn't, you'll have to make your own tweaks and figure out your own hardware. Sorry, but that's just one of the costs of owning your own PC.

---

### I'm having low FPS / I am not happy with my performance. What can I do?

For starters, most of these reports are from people that JUST booted up the game. Here are a few tips:

- Riverwood and Whiterun are pretty heavy areas. Some dips are to be expected. Try exploring a bit further to see if your issues are only in those areas.  
- Increase your pagefile size.  
- Press `Shift+Enter` to open the ENB GUI, and disable the Ambient Occlusion option (it's under the Global settings).  
- If that is still unsatisfactory, disable the ENB entirely (Shift+f12, or uncheck the Use Effect box in the ENB GUI).  

If you are on a laptop:

Open your Nvidia Control Panel. In the Manage 3D Settings section, if you have multiple GPUs, the Global Settings for Preferred Graphics Processor should be, by default, set to auto-select. You should leave this as it is.

Instead, switch tabs the Program Settings, and add the Skyrimse.exe or fallout4.exe that is located in the folder named Stock Game inside the folder where you installed Tempus/Opus. Then, as the Preferred Graphics Processor for that program, choose the High-performance Nvidia Card.

If all of this is still unsatisfactory, then you'll just have to either deal with it or come up with a solution for your own hardware. Sorry, but that's just the way it is. The game is going on 15 years old, there's only so much you can do before the engine just gives up on you.

---

#### There's a bunch of NPC Replacer mods in MO2 that are disabled. Can I turn them on?

No. They're all part of the EasyNPC output. They're already active in your game. Enabling these individual mods will break your game.

---

#### I chose a Race other than Deep Elf but I still get the Deep Elf stuff added to my inventory. Why?

Because this mod is really meant to be used by regular mod users. People install it with the intent to use it. Having it in the modlist has adverse effects such as this. You can freely ignore these things, or take advantage of them. Either way, not really a bug, and something you'll have to figure out for yourself in regards to whether or not you want to use it.

---

#### Can I disable/edit killmoves?

Press F6 to open the CatHub/Kaputt GUI. Change to your liking.

---

#### Everything is too bright, can you make it have some sort of *realistic immersive darkness?*

No. It's a video game. I want to see shit.

---

#### Everything is too dark, can I brighten it up somehow?

Shift+Enter to open the ENB GUI. Adjust as you see fit. When you're done, click Save Configuration. Shift+Enter again to close the ENB GUI.

---

#### My night eye/vampire sight/etc powers don't work.

Yeah, ENBs tend to do that. Press `Shift+Enter`, navigate to the righthand column of the ENB GUI, expand the `ENBEFFECT.FX` section, and enable the option that states `Use Nigheye Fix`. Then, in the lefthand column, click `Save Configuration`, then click `Apply Configuration`. Press `Shift+Enter` again to close the ENB GUI.

---

#### There is a white flash when I shout/use powers/etc.

This means you turned on the Nighteye Fix above. Turn it back off using the same instructions above, except now you're disabling it instead of enabling it. Don't forget to Save+Apply.

---

#### I'm having a hard time finding Spell Tomes. Where are they?

Spells are primarily now acquired through Spellforge. There's one in the starting prison cell along with enough materials for you to create 5 novice spells. You can also read the Spellforge Manual to teach yourself how to conjure your own Spellforge anywhere - please note that spells crafted at a custom Spellforge are more "expensive" than at placed Spellforges, such as the one in the Dragonborn Museum safehouse.

There are a few other Spellforges in the world as well. Go find them.

---

#### What about the Spell Tomes I need for the Museum displays?

You can craft a spell, then use the Transcribe power to create a Spell Tome from the spell you have equipped in your right hand.

---

#### I found an exploit / this armor is way too good / this weapon is too strong. Will you fix it?

Probably not. It's a single player game. If you think something is too strong, don't use it. If you find an exploit, use self control. At the end of the day, you're not hurting anyone but yourself. If that's how you enjoy playing, then more power to you. I don't care at all.

Besides, this is an LotD list. There's going to be a lot of overpowered stuff. Get used to it.

---

#### I went to Elysium Estate but the ghost isn't there. How do I get the house?

You have to buy it now. Read the note attached to the front door of the estate.

---

#### Sprint swimming and getting out of the water makes me swim on land!

Jump. Or stop the sprint-swimming prior to exiting the water.

---

#### Is the world unleveled?

No.

---

#### What ENB is in this list?

Imaginarium ENB.

---

#### How do I start the Goldenhills Plantation CC stuff?

You need to be level 15, then speak with an innkeeper in either Whiterun or Rorikstead. They will have a line of dialogue about work in the area.

---

#### Can I buy you a drink?

Sure can. I have a [Patreon](https://www.patreon.com/c/nicholasjae) or you can tip me through Venmo (@Nicholas-Jae).
