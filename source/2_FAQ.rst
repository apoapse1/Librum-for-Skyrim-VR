Frequently Asked Questions
==========================

Support and Community
---------------------

**Can you offer support in other languages?**
 - Unfortunately, since so many mods are English-only, Librum itself can't be offered in other languages. However, I can offer support auf Deutsch, en français, en español, или по-русски.

**I have a suggestion!**
 - If you believe your suggestion would be a good fit for Librum, and you don't see it on our `Trello <https://trello.com/b/dYUOOuIv/librum-modpack>`_ or in our #suggestions channel in our `Discord <https://discord.com/invite/BnUHUswABG>`_\ , please fill out this Google Form: https://forms.gle/4nBCPopDgrh1HpxX9.
 
**I found a bug!**
 - If you're certain it's a bug, **and you can reproduce it**_, please fill out this Google Form: https://forms.gle/kFw7c3kHHoULue4k7.
 
**I found an error in the readme!**
 - I opened a channel for these comments specifically.
 
Setup and Installation
----------------------

**What are all the unchecked mods in MO2?**
 - These are all intentional. I recommend ignoring everything except the "Optional Plugins" at the bottom of the left pane, which are described in the readme.

**How do I improve my framerate?**
 - Try turning down the in-game settings. In particular, supersampling and view distance (especially for actors and grass) are major culprits, and you can see if you prefer turning Dynamic Resolution off. If you are on SSE, you can also use the *(se)Librum ENB selector* in the ``Optional - Graphics`` section of your MO2 profile. There are options for other ENBs and a few have a choice for performance over graphics. If none of that is good enough, the last resort is to disable the ENB.

**When I level up, I still get a perk!**
 - Check your "Librum/overwrite" folder for a "SKSE/plugins/SkyrimUncapper.ini**, and delete it. You may also want to check your ``Apoapse Advancement`` MCM settings in game. There are settings you can adjust that will determine how many levels it takes to get a perk, and how many perks you get at those levels and it might have been changed on accident. Just set *Perks per Payout* to zero.
 
**What difficulty setting is recommended?**
 - The difficulty recommended is certainly Adept. If you find fights are taking longer than you would really like them to, don't feel bad about ticking the difficulty down.

**Some of the voice acting is too loud/not great.**
 - You probably have Death Consumes All active. If so, I did warn you =). If not, please let me know.

**I don't want survival features.**
 - This is possible. See the ``Customizing the MCM`` section of our install instructions. 

**The Bashed Patch is disabled/several mods in the left pane are disabled/LOOT says to reorder the mods.**
 - This is all intentional, and messing with it will break your game.


Gameplay
--------

**Why are people in town attacking me after I killed a deer?**
 - This would be a result of SVmods. Specifically the *Hunting Requires Permit* setting. If you do not pay the Steward of a city for a hunting permit, you are illegally poaching. If you get caught doing this by someone who can report the crime, the guards might turn hostile to you. It can be toggled off in the MCM under ``SV Mods Menu``_.

**Why am I crashing while going into a new city with Auri?**
 - You most likely have her mounted. This is a known bug due Auri and Convenient Horses that we are working on fixing. In the meantime please try to enter a new cell (not just a city) with no followers currently mounted.

**Why does my character pick up books without reading them?**
 - This is intentional and only happens if you activate the book while your hands/weapons are raised. It is meant to allow players to save skillbooks to read later or to quickly loot books while clearing out a dungeon. If you want to simply read the books you just need to lower your hands.

**How am I supposed to clear Bleakfalls Barrow, the draugr won't stay dead?**
 - The bandits in the opening room might have left a reminder for latecomers in their gang to bring lots more salt with them. We suggest you do the same.

**Why am I being arrested/fined? All I did was smith an iron sword!**
 - This is again SVmods. You need to pay the owner of that forge to use their crafting station. Alternatively, there are unowned or bandit owned forges/potion stations/enchanting tables for you to use for free if you don't mind a treck.

**Why are the guards mad at me, all I did was wait for Belethor to open his shop!?**
 - This is once again SVmods. Vagrancy, simply standing about town is illegal. It is one of the more questionable changes simply because of the way it is implemented. if it is causing you a hassle, you can toggle it off in the MCM.

**Why do I have to keep paying my followers more money?**
 - Many followers are hired to do a dangerous job, but they now require you to keep up payments if you expect them to keep risking their life protecting you. Each follower will want 500 copper coins a week.

**Why am I drowning after spawning from the starting area?**
 - If you equip heavy armor you cannot swim.

**If I can't swim in heavy armor, why is it a choice in the starting area!?**
 - Should you ever choose to begin your journey at the Falkreath cart, you will be very glad to have that metal armor as you flee through the forest. But in seriousness, it is possible to drop the armor after spawning, then drag it to the shore and re-equip it.

**What are the weird enemies below [insert city name]?**
 - You've encountered Skyrim Underground. I've patched away the worst offenders, but I recognize that I've got some more work to do in this department.

**Why do my items dissapear from my inventory after using an enchanting table?**
 - Enchanting Awakened changes the way that you can disenchant items until you get further along in the perk tree. This removing of itens is how it makes it impossible to disenchant certain enchantments for a while. Don't worry, your items will return shortly after leaving the menu.