# Librum (for Skyrim SE/VR)
Wabbajack modlist installer for _Librum_.

***A small request: if you enjoy my work, please consider contributing to my Patreon page at the link below. Although I certainly don't expect any donations from users, these sorts of contributions allow me to continue improving and supporting Librum.***

[<img src="Resources/patreon.png" width="150" height="50">](https://www.patreon.com/apoapse)

- [Librum](#librum-for-skyrim-sevr)
  - [Preamble](#preamble)
  - [Technical Requirements](#technical-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
        - [Set the Game language to English](#set-the-game-language-to-english)
        - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-up-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
    - [Post-Installation](#post-installation)
      - [Copy "Game Folder Files"](#copy-game-folder-files)
      - [Starting Librum and Choosing Optional Plugins](#starting-librum-and-choosing-optional-plugins)
      - [Start up Skyrim... again](#start-up-skyrim-again)
      - [MCM Settings](#configure-the-mcm)
    - [Natural Locomotion](#natural-locomotion)
  - [Updating](#updating)
  - [Features of Librum](#features-of-librum)
    - [General Philosophy](#general-philosophy)
    - [Leveling and Skills](#leveling-and-skills)
    - [User Interface and Controls](#user-interface-and-controls)
    - [Dynamic World](#dynamic-world)
    - [Survival and Realism](#survival-and-realism)
    - [Combat and Enemies](#combat-and-enemies)
    - [Magic](#magic)
    - [Quests and Adventures](#quests-and-adventures)
    - [Graphics and Ambience](#graphics-and-ambience)
  - [Getting Started in Librum](#getting-started-in-librum)
  - [Frequently Asked Questions](#frequently-asked-questions)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

 
## Preamble
![Alt text](Resources/DoubleBanner.png?raw=tue "I made this image myself, and I am proud of it.")

_You're lost in the woods, having narrowly escaped after scaring off a pack of wolves with a summoned flame atronach. Your torch finally fades out, and it's getting cold. You can conjure basic foods, and your summoned atronach provides enough heat for the time being, but you'll need to gather wood in order to sustain a fire and survive the night. With little time to spare, you can't search far for materials -- luckily, you've fashioned a basic hatchet the night before, and you can chop down a nearby tree for lumber. You fall asleep next to your fire, having placed several runes nearby to dispatch would-be predators. Despite a few interruptions in the night, the morning comes at last, and the sun finally breaks over the horizon._

Skyrim VR is a wonderful experience, but it's a very familiar one. Even in stunning 3D, we visit the same locales and repeat the same adventures we have since the end of 2011.

_Librum_ is a comprehensive gameplay, graphics, and content overhaul that attempts to change all of this. Combining together some of the best and most popular mods for Skyrim SE, a suite of new quests and adventures that outnumber Skyrim's own, the tradition of great "hardcore" gameplay overhauls that have come before -- like Skyrim's _Requiem_ and _YASH_ or Oblivion's _Oscuro's Oblivion Overhaul_ -- and a host of unique-to-VR immersion improvements, Librum brings new life (and new challenge!) to Skyrim in a way that has never been experienced before.

***User Comments:***

<div align="center">"This is definitely the most different playthrough I've ever done."</div>

<div align="center">"I'm not used to the difficulty, but it was probably the most fun I had on Skyrim."</div>

<div align="center">"It's refreshing. At this point I would have all novice spells that I wanted in a normal playthrough
."</div>


## Technical Requirements
Librum is fairly technically intensive, but in line with standard Skyrim VR graphics enhancements. Your mileage will certainly vary -- I can only provide my own specs, but I imagine you will find good performance on a weaker system.

***Space Requirements.*** Librum requires 38 GB of space for its downloads, and 70 GB of space for the installation. In total, you will need 118 GB free on your computer.

***Recommended Specs.*** This was the machine I compiled Librum on. I have gotten very smooth gameplay, with an occasional stutter in a new area before the included [VR FPS Stabilizer](https://www.nexusmods.com/skyrimspecialedition/mods/31392) kicked into gear.
 - **CPU**: Intel Core i7-7700HQ, 4 cores at 2.80 GHz.
 - **GPU**: NVIDIA GeForce GTX 1060, 6 GB of VRAM
 - **RAM**: 16 GB DDR4

## Installation

Librum makes use of the excellent [Wabbajack](https://www.wabbajack.org/#/) program to make its installation as fast and painless as possible. That said, there are a few, very easy steps involved in setting up Librum. We will go over each in detail, but they are summarized as follows:

1. Clean your Skyrim folder and disable the Steam overlay.
2. Install the Wabbajack desktop client from [here](https://github.com/wabbajack-tools/wabbajack/releases).
3. (VR) Navigate to Librum under the _Browse for Modlists_ tab.
3. (SE) Download the Librum.wabbajack file from the "Releases" tab on this GitHub.
4. Install Librum to a new folder, outside of `Program Files`.
5. Copy the `Game Data Files` folder to your Skyrim VR directory.
6. Start a new game, and wait until mod installation notes finish appearing.
7. Configure the Mod Configuration Menu according to the [instructions that follow](#mcm).

### Pre-Installation

These steps are only needed if you are installing Librum for the first time. If you only want to update Librum, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

##### Set the Game language to English

Librum is entirely in English, as many excellent mods are English-exclusive. This may change in the future, but for now, I highly recommend playing the game in English.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

##### Clean Skyrim

If your Skyrim VR installation is not newly installed, I recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim VR` folder in `Documents/My Games/` by deleting the contents in it.

#### Start up Skyrim

After you have done everything above and have a clean Skyrim VR installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about the graphics settings at this point, as the Librum installation will replace them. 
Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads, or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

The download and installation process can take a very long time, depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack.
2. (VR) Browse for the modlist in the Wabbajack client, and click to download it.
2. (SE) Download the Librum_SE.wabbajack file from the "Releases" tab on this GitHub, and open it up in the "Install From Disk" option in the Wabbajack client.
3. Once the download is complete, set the installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, or Desktop. Put it somewhere easy like `C:/Modlists/Librum`). The downloads path should automatically fill in the installation path.
4. Click the Go/Begin button.
5. Wait for Wabbajack to finish.
6. If you run into any issues, see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off, so you lose no progress.

***Could not download X.*** If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update Librum.

***X is not a whitelisted download.*** This can happen when I update the modlist. Check if a new update is available and wait if there is none.

***Wabbajack could not find my game folder.*** Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

***Windows is reporting that a virus has been detected.*** Windows 10 has started to auto-quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2, saying a threat has been detected. This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for Windows Defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

### Post-Installation
Now that Librum is installed, it is time to start the game up for real and create your character. The character creation process has changed with Librum, so we will give details below. Moreover, it is highly recommended that you **configure the MCM after race selection** as described below.

#### Copy "Game Folder Files"
Navigate to the installed Librum folder, where you will find a folder titled `Game Folder Files`. Copy the contents of this folder to the Skyrim root folder.

There are two options available in the copied files: the "ENB - LCD" folder and the "ENB - OLED" folder. Depending on your headset, copy the contents of the appropriate folder to the Skyrim root folder; they should overwrite a few ENB-related files. If you do not know, the Valve Index and the Oculus Rift S are _LCD_ headsets, while the HTC Vive and Rift CV1 are _OLED_ headsets. 

#### Starting Librum and Choosing Optional Plugins
Navigate back to the installed Librum folder, and launch the program `ModOrganizer2.exe`. Before launching the game itself, take a look at the _Optional_ category at the bottom of the Mod Organizer 2 mod list. I will go over each below.

***End Times*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/39201)]. This plugin adds a sense of urgency to the Main Quest, and it ties in nicely with Librum's re-centering of Skyrim around being the Dragonborn. Specifically, if you do not defeat Alduin within a certain amount of time (365 days by default, but configurable in the MCM), he will swallow the world (accompanied by a nice visual), and you will have to reload and try again. You will have a _Doomsday Clock_ spell available, as well as configurable regular updates, to tell you how much time you have left.

If you do not want this plugin, disable it in MO2.

***Dragons from the Start*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/41453)]. This plugin enables dragon encounters from the very beginning of the game. This is highly recommended for Librum's Dragonborn-centric play, and it is especially important if you use the next optional plugin. 

If you do not want this plugin, disable it in MO2.

***No Perks on Level-Up***. This is a core feature of Librum, so it is highly recommended. With this plugin, you will no longer earn perks when you level up; rather, you will have to spend dragon souls in order to earn perk points. This accomplishes two things. First, along with other mods from the core modlist, this re-centers the Skyrim experience on you _actually being the Dragonborn_. You will not progress without hunting dragons and progressing the main quest. Secondly, this reframes the role of perks in the Librum experience. Because (especially at the beginning) they are much harder to obtain, they will form a much smaller part of your character's identity, and your character will spend a longer time being a "normal person".

If you do not want this plugin, disable it in MO2.

***The Adventurer Theme Mod*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/35568)]. The Adventurer Theme adds Oblivion-like elements to Skyrim's UI, changing (among other things) the inventory, magic menu, and crafting menus to look like parchment. See the [UI section below](#user-interface-and-controls) for more details.

If you do not want this plugin, disable it in MO2.

***Adventure Theme Lite***. If you don't want the full effect of _The Adventure Theme_, but you want the nicer cursor and Oblivion-style inventory icons, this is the plugin for you.

If you want this plugin, enable it in MO2. You don't need this if you have the full _Adventure Theme Mod_ option.

***Bullet Time Power*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/16690)]. This mod adds a toggleable "bullet time" power, which acts a little differently from standard _Slow Time_ effects and drains stamina as it goes. I recommend using this, to add a level of tactical movement to combat that is not easily achievable with real-time VR. If you use this, I recommend choosing a higher difficulty setting to compensate.

If you do not want this plugin, disable it in MO2.

***VRIK Controller Bindings*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/23416)]. These are recommended controller bindings to go along with VRIK. If you are using an Index, you will need the latest community bindings. Unfortunately, some in-game button prompts will not align with these bindings.

If you do not want this plugin, disable it in MO2.

***Magic Cards Font*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/14356)]. This is the font from Morrowind. It looks more "medieval" than the standard font, but is generally a nice (and nostalgic) change of pace.

If you do not want this plugin, disable it in MO2.

***Darker Night Sky***. This is SGS's night sky texture, to go alongside the [High Fidelity ENB](https://www.nexusmods.com/skyrimspecialedition/mods/27308) we're using. It is a darker texture with reddish auroras, and it fits in very nicely with Librum's theme. If you do not use this, you will have the brighter and arguably prettier textures from [Ethereal Cosmos](https://www.nexusmods.com/skyrimspecialedition/mods/5728).

If you want Ethereal Cosmos textures instead, disable this in MO2.

***New Voice Commands***. This adds several new voice commands, to automate many of the features you'll be using frequently: _Open Map_ and _Close Map_, _Call Horse_, _Spell Research_, _Drink Water_ and _Fill Waterskin_, _Continuance_ or _Get Status_ (for general health and hunger/thirst/fatigue status), and _Sense Direction_.

If you do not want this plugin, disable it in MO2.

***Left-handed Settings***. Self-explanatory. Make sure to also enable "Left-Handed Mode" in the in-game settings.

If you are left-handed, enable this in MO2.

#### Start up Skyrim... again
To start the game for real, start SKSE through Mod Organizer 2. This will be necessary every time you start the game; if you try to launch Skyrim through its default folder or through Steam, the game will be entirely vanilla.

Start a new game once you get to the main menu. The "yes/no" dialogue in the _New Game_ menu does not always indicate which you are selecting, but the buttons will work as expected. You will start in the character creation area from [Realm of Lorkhan](https://www.nexusmods.com/skyrimspecialedition/mods/18223). Here are some things to know as you create your character:

1. Race differences are changed in accordance with [Imperious](https://www.nexusmods.com/skyrimspecialedition/mods/1315), but with the modifications made by [Elemental Destruction Magic](https://www.nexusmods.com/skyrimspecialedition/mods/440). Namely, Orcs are 50% resistant to earth magic, and Argonians are 50% resistant to water magic.
2. Standing stones are changed in accordance with [Andromeda](https://www.nexusmods.com/skyrimspecialedition/mods/14910). However, **the standing stone you choose in the Realm of Lorkhan is final**. That is, you will not be able to change it without first returning to the Realm of Lorkhan.
3. Be particular with the items, spells, and powers you bring back from the Realm of Lorkhan. Much moreso than in vanilla Skyrim, having additional weapons, armors, spell tomes, gold, or even food items can start you out with a significant advantage. If you do not want this advantage, do not take anything with you.

Note that Wabbajack will reset some of the in-game Skyrim settings, which you will want to fix before continuing.
Open main menu -> settings -> VR performance, and apply the following settings:

 - Untick dynamic resolution
 - Untick the two "disable lod" options
 - Other options can be configured according to your hardware. In particular, note the "actor distance" slider -- keep this low or you will lag in towns and cities, even with the best CPU.


#### Configure the MCM
Once you have created your character, open up the in-game settings and navigate to the _Mod Configuration Menu_ (MCM). You will need to make several changes here to adhere to the suggested Librum setup. Unfortunately, very few of the mods used in Librum support FISS, so you will need to do this each time you create a new character.

The suggested MCM options are as follows:
1. **Cobb Encumbrance.** In the _Presets_ tab, apply the preset "Classic (SEM)".
2. **Frostfall**. Activate the mod, and turn off fast travel and waiting outdoors in the _General_ tab. If desired, choose one of the presets in the _Meters_ tab (I use "bottom left").
3. **Hunterborn**. Start the mod, and disable the Hunterborn config power in the _Enable_ tab.
4. **Lock Overhaul.** Activate the mod.
5. (VR) **MageVR.** Spawn MageVR backpack, and "Archery Mode" -> "Hardcore". Either set the first weapon slots (both left and right) to _empty quickslots_ or to _quivers_, to prevent MageVR holsters interfering with VRIK holsters.
6. **Nemesis.** Activate both options.
7. **Simple Horse.** Confirm that Follower horses are disabled.
8. **SkyUI.** If desired, disable the Active Effects HUD under _General_.
9. **Spell Research.** Import spells.
10. **SunHelm.** Activate the mod. If desired, change "Widget Display Type" in _Display and Notifications_ tab (I use "Alpha/Color Based").
11. **Tentapalooza.** I am working on a script to apply these settings automatically. For now, when you use a Tentapalooza tent, change its corresponding setting in this menu.
12. **Trade & Barter.** Under _Barter Rates_, set "Barter Presets" -> "Hardcore".
13. **Vigor.** Start the mod.

Further, there are a few settings to change using mod configuration spells:
1. (VR) **VRIK.** This configuration spell is available in the _Powers_ tab. Calibrate to headset height, and then to VR scale.

(VR) ***If you want to use the optional voice commands, apply the following settings:***
1. **Hunterborn.** Set the "Sense Direction" hotkey to "x".
2. **Spell Research.** Set the "Spell Research" hotkey to "alt".
3. **SunHelm.** Set the "Continuance" hotkey to "y", and the "Drink Water/Fill Waterskin" hotkey to "l".


Congratulations! You've completed the Librum setup, and you are ready to play. The next several sections will explain what Librum is and does, as well as provide support.

### Natural Locomotion
***Only applies to VR.***

This step is ***not mandatory***, but it will significantly improve your VR experience. Download [Natural Locomotion](https://store.steampowered.com/app/798810/Natural_Locomotion/) through Steam. It is an independent app, which allows you to walk around in VR games by swinging your arms (and possibly holding a hotkey). Although this sounds intrusive and unnatural, it quickly becomes a _very_ natural way to move around Skyrim. As a bonus, it works for everything from Skyrim and Fallout 4 VR to _No Man's Sky_.

In terms of configuring NaLo, I recommend the following settings (although it is up to taste):
***Common Settings:***
 - _Allow jumping while crouched_ - off.
 - _Enable strafing by tilting head_ - on.
 - _Sticky buttons_ - off.
***Edit Profile/Configure Buttons:***
 - Enable walking with one of the following two options:
   - _Hands down the hip (buttonless)_. This is newer, and may interrupt other actions, but feels more natural.
   - _Joystick touch_ on right or left hand only, and _enable both hands with this button_. You will only move around when your thumb is on the joystick, but you do not need to hold any buttons down.
 - _Enable jumping in place_ - on, with button set to _right joystick up_. The "natural jumping" doesn't always trigger when you want it to.
***Edit Profile/Configure Speed and Trackpad Emulation:***
 - _Original trackpad/joystick_ - set to _combine with movement_.
 - _Desired trackpad/joystick orientation_ - set to _head relative_.

When you want to play, first load up NaLo and click "Start selected profile" on Skyrim VR, and then launch Skyrim normally (SKSE through MO2).

## Updating
If Librum receives an update, please check the Changelog before doing anything. Always back up your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the updated modlist when updating!**

This means that any additional mods you have installed on top of Librum will be deleted. However, your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _Overwrite existing modlist_ button.
Note that some in-game settings will get reset when updating. Check them all again! Particularly, "dynamic resolution" and "disable lod" in the "VR Performance" settings menu. 

## Features of Librum
Librum significantly affects nearly every aspect of gameplay; in this section, I explain all of the significant changes that have been made, and how they change the Skyrim experience. I will separate it here into various "modules" for ease of explanation -- however, this does not reflect any clean-cut separations of Librum mechanics. Changes from the various modules overlap, affect one another, and work together to create a consistent Librum experience. For instance, _Spell Research_ forces mages to interact with the survival elements of Librum, and these survival elements turn a quest like _Clockwork_ into a precarious and time-sensitive escape mission.

With this in mind, here is a rough breakdown of what Librum accomplishes.

### General Philosophy
With every change, Librum attempts to adhere to the points of its _core philosophy_:

1. Librum is a game about _being Dragonborn_. Your dragon soul is a fundamental part of your character's development, and there is no way to indefinitely avoid this destiny.
2. The world is static in ways that make sense, but dynamic in all others. The world is not centered around you, but it reacts realistically to the actions you take and the choices you make. In particular, the ways in which you interact with the world change as you become more powerful.
3. Magic in all forms is a dangerous, arcane, and powerful force. Magic can solve most any problem you have, but -- as an example -- acquiring a single Master-level spell might take a whole playthrough.

### Leveling and Skills
Librum makes several major changes to character progression, described by the following comparison table:

 | Vanilla Skyrim | Librum
 | -------------- | ------
 | Character progression happens primarily as you level, and primarily through the allocation of perk points.	  | Character progression occurs through three unrelated aspects of your character: spell/equipment progression, character level, and collected dragon souls.
 | Available equipment and enemies depend exclusively on your level.	| Librum's loot distribution is based on [Morrowloot Ultimate](https://www.nexusmods.com/skyrimspecialedition/mods/3058), so equipment and enemies (with the exception of dragons) are entirely unleveled.
 | Higher level equipment can be made and improved at any time, mitigating any effect of leveled weapons and armor	| Smithing now requires more knowledge than just a perk point; for instance, you need to acquire the _[Ancient Knowledge](http://en.uesp.net/wiki/Skyrim:Powers#Ancient_Knowledge)_ effect to make any Dwarven equipment, and Daedric smithing requires uncovering the secret of its construction. Improving equipment is no longer as effective.
 | Available spell tomes depend exclusively on your skill level, but are readily available at spell merchants.	| Spell tomes do not exist, by and large, with the exception of select hand-placed tomes. Rather, all spell progression is done through [Spell Research](https://www.nexusmods.com/skyrimspecialedition/mods/20983).
 | Perk points are gained when you level up.	| You do not gain perk points through leveling. Using [Souls Do Things 2](https://www.nexusmods.com/skyrimspecialedition/mods/33518), you will have a power to convert one dragon soul to one perk point. Leveling will continue to grant you 10 Health, Magicka, or Stamina.
 | Dragon souls are exclusively used to unlock dragon shouts.	| Dragon souls have three purposes. They can be used to unlock shouts, they can be used to unlock perk points (as mentioned above), and finally, you will have passive buffs applied depending on the number of unspent souls in your collection.
 | You can level up at any time by opening the Skills menu.	| You must sleep for 8 hours in order to level up, in order to prevent level-ups in dangerous locations.
 | Perks are typically straight buffs to your existing skills, and form the core part of your character's identity.	| Librum uses [Vokrii](https://www.nexusmods.com/skyrimspecialedition/mods/26176) to mix up perk benefits and to help balance around having only a small handful of perks; a single perk investment in any tree replaces vanilla's "20/40/60/80/100%" improvement perks or "Novice/Apprentice/Adept/Expert/Master" perks.
 | Standing Stones provide moderate benefits to an existing character build, and can be changed at any time.	| Standing Stones entirely change your character's make-up, thanks to [Andromeda](https://www.nexusmods.com/skyrimspecialedition/mods/14910), but they can only be chosen during character creation.
 | Your race typically gives you a once-a-day power, as well as some moderate resistances. 	| Through [Imperious](https://www.nexusmods.com/skyrimspecialedition/mods/1315), your race confers significant passive abilities. These typically change gameplay drastically.

### User Interface and Controls
Librum makes a few changes to the default user interface, to (a) create a unique visual experience and (b) to improve the VR experience. For the first point, Librum uses [SkyUI](https://www.nexusmods.com/skyrimspecialedition/mods/12604) along with the excellent [Dear Diary UI](https://www.nexusmods.com/skyrimspecialedition/mods/23010) and pieces of the [Adventurer Theme Mod](https://www.nexusmods.com/skyrimspecialedition/mods/35568) in order to blend a Skyrim-style modern UI with touches of a more Oblivion-style classic visual theme:

![Alt text](Resources/UI.jpeg?raw=true "Adventurer Theme Mod, Rendered in Skyrim SE")

Librum makes larger changes in terms of controls. For one, it includes [Dual Wield Block VR](https://www.nexusmods.com/skyrimspecialedition/mods/28456), [Weapon Throw VR](https://www.nexusmods.com/skyrimspecialedition/mods/31374), [Sprint Jump VR](https://www.nexusmods.com/skyrimspecialedition/mods/28354), [VR Power Attack Fix](https://www.nexusmods.com/skyrimspecialedition/mods/28004), [Haptic Skyrim VR](https://www.nexusmods.com/skyrimspecialedition/mods/20364), and [Realistic Mining VR](https://www.nexusmods.com/skyrimspecialedition/mods/16692) in order to better match player motions to character actions. With this suite of mods, VR combat is a much more natural experience, and you have all the options -- such as blocking with an off-hand weapon or throwing your weapon -- that you would expect. In particular, as we will further discuss in the next section, you can swing your pickaxe at _any_ in-game rock (including, but not limited to standard ore veins) and swing your woodcutter's axe at (most) any in-game tree or wooden object to get the resources you expect.

A big change in this direction is [HIGGS VR](https://www.nexusmods.com/skyrimspecialedition/mods/43930), which allows you to use your hands to truly interact with the world. You can pick up items naturally and turn them in your hand, throw them at NPCs, or put them over your shoulder to put them in your inventory. You can drag bodies around (finally) to hide your crimes from the law, or grab armor pieces directly off of corpses without entering a menu. Finally, you have gravity-glove-like abilities, as in _Half-Life: Alyx_.

![Alt Text](Resources/hands.jpg?raw=true "Holding a coin with HIGGS") 

In a similar vein, Librum includes [Dragonborn Speaks Naturally](https://www.nexusmods.com/skyrimspecialedition/mods/16514) and [SkyVoice](https://www.nexusmods.com/skyrimspecialedition/mods/17840) to have the world respond naturally to your voice. Namely, when you begin reciting a dialogue option, the game will select it for you, and when you say the words of a learned dragon shout, you will use that shout in game. Not to worry, of course -- thanks to [Shout Pronunciations](https://www.nexusmods.com/skyrimspecialedition/mods/18572), the dragon language words of each shout will be shown in your shout menu.

Librum also includes [MageVR](https://www.nexusmods.com/skyrimspecialedition/mods/21297), which generally overhauls the way you interact with spells and equipment. I recommend thoroughly reading its mod page for more information, but in short, it adds the following features:
1. Spells can be slotted to drawn "glyphs". You can re-draw the glyph later to either equip or auto-cast the slotted spell, all without entering your menu.
3. Archery is realistic. You will need to manually retrieve an arrow from your quiver in order to fire another shot.
4. You can quickslot shouts and powers, usable through a gesture and hotkey press.
5. You are able to "immersively" loot a container, in which you manually drag loot from the container to your backpack.
6. You are able to "immersively" lockpick, in a way resembling the real procedure for a tumbler lock.

Last but not least, Librum includes the fan-favorite [VRIK Player Avatar](https://www.nexusmods.com/skyrimspecialedition/mods/23416), which allows you to see your character in-game. Not only that, but VRIK provides several visible weapon holsters around your body -- your calves, thighs, hips, forearms, upper arms, chest, stomach, and shoulders. To use these, hold your weapon over the appropriate holster (you should feel a haptic signal) and press "grip". Hold "grip" and pull away to unsheathe. VRIK also allows you to go into "selfie mode", by lifting your right hand above your head and rotating; you can finally see your VR character in his/her full glory!

![Alt Text](Resources/hands.png?raw=true "VRIK-enabled body, with visible holsters.")

### Dynamic World
Continuing on with the theme of the last section, Librum includes a suite of mods designed to make static objects react to your actions. Along with the mods mentioned before, the key players here are [Dynamic Things](https://www.nexusmods.com/skyrimspecialedition/mods/19520), [Dynamic Things Enhanced](https://www.nexusmods.com/skyrimspecialedition/mods/19521?tab=posts), [Destructible Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/28291), and [Sneak Tools](https://www.nexusmods.com/skyrimspecialedition/mods/1863) (which will come up again later).

The combined effects of these mods are as follows:
1. Any haypile or stack of wood you find in the game can be looted, and will decrease in size as you loot them.
2. Almost all "static" containers in Skyrim -- crates, barrels, and others -- can now be looted. They can also be destroyed with a woodcutter's axe, which will drop all of their contents and firewood.
3. Most rocks can be mined with a pickaxe, giving you Hearthfire resources.
4. Most trees can be cut down with any axe, giving you firewood and other resources.
5. You can drink or bottle liquids from mead barrels and similar containers.
6. Using your weapons or Destruction magic on training dummies and archery targets will yield experience.
7. You can harvest mammoth tusks from mammoth skulls you find.
8. Most "standard" objects, like barrels, urns, and small furniture, will be destroyed if you hit them.
9. Light sources around Skyrim can be ignited and put out, either by standard fire/frost effects or by the fire/water arrows included in Sneak Tools.

### Survival and Realism
On the flip side, _you_ have to appropriately react to Skyrim's environment. The core of this, of course, is [Campfire](https://www.nexusmods.com/skyrimspecialedition/mods/667) and [Frostfall](https://www.nexusmods.com/skyrimspecialedition/mods/671). Along with some more resource-adding mods (notably, [Tentapalooza](https://www.nexusmods.com/skyrimspecialedition/mods/652)), these mods add a complete cold-weather survival system to Skyrim. Your character will be subject to Skyrim's harsh climate, and you will need to bundle up, set up camp frequently, and avoid frigid water and inclement weather in order to survive. Mages will have various options to escape the cold (all compatible with Librum's [Spell Research](https://www.nexusmods.com/skyrimspecialedition/mods/20983) mechanics!): summoning cloaks or various tents and shelters, transmuting or summoning materials, summoning a Fire Atronach for heat, or teleporting to safety, among others. Finally, your character's survival skills will improve over time, unlocking various survival-themed perks available at a campfire.

![Alt text](Resources/Campfire.jpg?raw=true "This is a generic picture of a dude at a campfire.")

You will also need to keep track of your hunger, thirst, and fatigue, thanks to [iNeed (Continued)](https://www.nexusmods.com/skyrimspecialedition/mods/19390). Although you will eat and drink automatically (to avoid more menu-searching than is necessary), you will need to maintain a supply of water (or alcohol!) and fresh or salted food in order to survive. Thankfully, these resources can be obtained from many sources. You can get water from snowbanks, wells, rivers, or the ocean -- although it may have to be boiled for hygiene's sake -- and many NPCs are happy to share or sell water, if you ask nicely. 

Getting food is a more involved process, thanks to [Hunterborn](https://www.nexusmods.com/skyrimspecialedition/mods/7900). When you hunt an animal, you now need to properly dress and skin the carcass, using a hunting knife. On the other hand, you will have access to many more resources when you harvest from an animal carcass: more kinds of meats and animal products, pelts from each animal, and animal bones. Your hunting, foraging, bone-carving, and cooking skills will improve with each use, improving your harvests and giving access to new recipes over time.

_Sleep_ is also more complicated than it may seem. Although it is necessary both for general survival and to [level up](https://www.nexusmods.com/skyrimspecialedition/mods/32357), it is fairly dangerous to fall asleep in Skyrim's wilderness or in its dungeons. Thanks to [Sands of Time Sleeping Encounters](https://www.nexusmods.com/skyrimspecialedition/mods/8257), any time you fall asleep, you will have a location-dependent chance of being attacked during the night. This is particularly true in dungeons, making it imperative to either (a) quickly get to safety or (b) bring along a follower or lay traps.
Finally, through _Sunhelm_, diseases have become much more dangerous. Instead of applying a minor debuff to your stats, each disease will now progress through various stages, with many becoming deadly if left untreated. To avoid this all-new danger, you will need to take care to apply _Resist Disease_ effects, properly prepare your foods and water, and try not to get bitten or scratched in fights with wild animals. If you _do_ contract a disease, and it doesn't go away on its own, you will have to rest up, find an alchemical cure (unique to each disease), or pay through the nose for a priest to dispel your illness.

### Combat and Enemies
Librum uses a slew of mods to improve the combat experience overall, with a strong focus on making each fight (within reason) a dangerous and harrowing experience.

For general combat, Librum combines its many [new VR options](#user-interface-and-controls) with [Wildcat](https://www.nexusmods.com/skyrimspecialedition/mods/1368), [Mortal Enemies](#https://www.nexusmods.com/skyrimspecialedition/mods/4881), [Advanced Adversary Encounters](https://www.nexusmods.com/skyrimspecialedition/mods/6843?tab=description), [Know Your Enemy](https://www.nexusmods.com/skyrimspecialedition/mods/13807), and [Morrowloot Ultimate](https://www.nexusmods.com/skyrimspecialedition/mods/3058). The former two mods add an element of dynamism to combat -- instead of standing and swinging your Touch controllers wildly, you will need to duck, weave, and carefully time both your attacks and your blocks. If you interrupt an opponent's power attack pullback or bow draw, or if you hit them from behind or while staggered, you will gain massive "attack of opportunity" damage bonuses. Similarly, if you properly time your block, you can negate most damage and stagger your opponent (thus allowing for an attack of opportunity). Of course, the same effects apply to your opponents, so you will need to keep your guard up as you fight.

On the flip side, you (and your opponents) will have to be much more careful in order to avoid Wildcat's all-new injuries, which can quickly turn the tide of combat. Any time someone sustains a major attack (30% or more of their total health), they have a chance of injuring your head, chest, arms, legs, or back, and thus facing major body-part-specific penalties to their combat abilities.

The latter two mods, AAE and MLU, step in before you've even started a fight. The latter delevels all enemies, so you'll have to make sure you're properly prepared to be wherever you're going. The former drastically changes enemies' resistances, weaknesses, and abilities, forcing you to plan in advance before a difficult fight. You will now _need_ to pack a silver, Daedric, or magical weapon in order to fight ghosts, for instance, and you'll need to clobber skeletons instead of shooting at them. Furthermore, opponents will use all of the tools at their disposal. From the mod page, "witches will now summon spriggans and use poison spells to their advantage, Thalmor will try to subdue their foes by way of paralysis, while vampires can use hand to hand combat, as well as summon gargoyles, and even morph into a swarm of bats while in combat". Combined with AI tweaks from Wildcat and more minor mods (like [Multiple Floors Sandboxing](https://www.nexusmods.com/skyrimspecialedition/mods/4524)), these improvements will make any fight a life-or-death experience.

![Alt Text](Resources/Trident.png?raw=true "Glass trident, from Heavy Armory")

Combining nicely with these AI and combat tweaks, Librum adds several new classes of weapons through [Heavy Armory](https://www.nexusmods.com/skyrimspecialedition/mods/6308) and other, smaller weapon mods. You can now wield anything from spears and tridents to staves and clubs, and all of the new weapons control smoothly under VR. In particular, a spear will "feel" like a spear, instead of the slightly-more-awkward-sword it was consigned to being in 2D Skyrim. You can also throw any of these weapons, allowing you to finally play the javelineer you've dreamed of.

Special attention has been given to wild animals, combining [SkyTEST - Realistic Animals and Predators](https://www.nexusmods.com/skyrimspecialedition/mods/1104) with [Savage Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/37768). Animals will go about normal animal behaviors: hunting prey, running from predators or competing with other predators, raising cubs, and finding mates. Bears will hibernate in the winter, animals will search for food and water, and, importantly, they will not report your crimes. There will also be significantly more variety in different animals, with many animals now sporting different colorations:

![Alt Text](Resources/Wolves.jpeg?raw=true "New wolf colorations from Savage Skyrim")

Savage Skyrim goes one step further, however, combining the several graphical mods from Rougeshot over the years. Many enemies now have more unique, more characteristic, and (often) more terrifying body structures. Dragons and vampire lords have gotten larger wings; Dwemer constructs, spriggans, and spiders have become more imposing; and _many_ other animals and creatures have undergone similar changes.

Of course, dragon combat still forms the foundation of Librum, and dragons are not excluded from our tweaks here. Firstly, there is now a _much_ wider variety of dragon types available, thanks to [Splendor](https://www.nexusmods.com/skyrimspecialedition/mods/9670) and [Diverse Dragons Collection](https://www.nexusmods.com/skyrimspecialedition/mods/695). They have all each been given unique names through [Zim's Dragon Improvements](https://www.nexusmods.com/skyrimspecialedition/mods/38693), and they all [talk to you](https://www.nexusmods.com/skyrimspecialedition/mods/26955) during your fights. Along with changes to make dragon combat more difficult and dynamic, this combination turns each dragon fight into a unique boss fight, rather than another generic Skyrim opponent.

![Alt Text](Resources/Dragon.jpeg?raw=true "Named dragon from Zim's Dragon Improvements")

Finally, Librum turns Skyrim's half-baked sneaking mechanic into a stealth experience worthy of the _Thief_ franchise. With the many thoroughly researched changes from [Realistic AI Detection](https://www.nexusmods.com/skyrimspecialedition/mods/2345), you will now need to use darkness and silence to your advantage. Many dungeons have undergone [significant lighting improvements](https://www.nexusmods.com/skyrimspecialedition/mods/8586), which you need to make use of as you sneak around enemies' now-more-realistic detection skills. Speaking of the _Thief_ franchise, Librum adds many new tools of the trade to aspiring rogues, courtesy of [Sneak Tools](https://www.nexusmods.com/skyrimspecialedition/mods/1863). You can now knock unsuspecting opponents out with your bare hands or a blackjack, ignite and extinguish light sources with fire/frost magic or fire/water arrows, and better navigate your environment with rope arrows. You can also set things ablaze after hitting them with oil arrows, fool opponents with noisemaker arrows, and conceal your identity with various masks and hoods (a la Grey Cowl of Nocturnal). 

### Magic
If anything, Librum makes _more_ significant changes to the mage experience than the warrior or thief experiences mentioned in the last section. First and foremost, the process for obtaining new spells adheres to the [Spell Research](https://www.nexusmods.com/skyrimspecialedition/mods/20983) format. In short, ***spell tomes no longer exist***, by and large, with the exception of certain hand-placed tomes. This means that you will need to _research_ to discover each new spell, in one of three general fashions:
1. _Researching existing spells_. Using your research journal, you can spend time studying any spell already in your possession, in order to increase your knowledge of the spell's various archetypes. For instance, studying _Lesser Ward_ would improve your knowledge of Restoration magic, of shielding spells, of "magical force" inducing spells, of self-targeting spells, and of concentration spells. This is slow, but a very straightforward method of progression for existing mages.
2. _Distilling and studying alchemical ingredients_. Using an alembic or a cauldron, you can distill alchemy ingredients into concentrated serums, which you can then (a) use for interesting crafting recipes or (b) study to improve your knowledge of their effects. This is relatively fast, but expensive and terribly confusing.
3. _Beating the shit out of valuable artifacts_. Along your adventures, you will come across all manner of new magical artifacts, ranging from the relatively commonplace enchanted weapon fragments to the dangerous and rare _Grimoires_. By studying magical items, translating old tomes, or destroying all of these artifacts, you can learn a huge amount about various spell archetypes, or even gain new spells automatically. However, these methods can be finnicky and dangerous, and they may harm you more than they help.

Once you've learned enough about the spell archetypes you're interested in, you can attempt to write "magical theses" and apply them towards gaining a new spell. If you are skillful, lucky, and not mentally drained, you may discover a new spell that fits the archetypes of the theses you wrote.

Now, there are several important gameplay consequences of this system. Existing mages will have an easier time learning new spells than new apprentices -- if you don't have any spells to start with (which may well be the case), you must study alchemical ingredients or artifacts in order to improve. Furthermore, as spell tomes are largely unavailable, you will have to make do with lower level magic than is otherwise the case; learning your first _Adept_ or _Expert_ spell, for instance, is a very difficult process.

On the other hand, Librum adds many new spells and classes of magic, organized loosely around the [Mysticism](https://www.nexusmods.com/skyrimspecialedition/mods/27839) framework. Mysticism itself rebalances all of the vanilla spells, and it adds a wide swath of new spells corresponding to those of "legacy" Elder Scrolls games. The list below gives some examples, but is _noncomprehensive_:

 - ***Open X Lock.*** Instantly open any lock of the corresponding level.
 - ***Mark and Recall.*** Set a location with _Mark_, and instantly teleport there with _Recall_.
 - ***Absorb Health.*** Drain a target's health pool, and restore your own the same amount.
 - ***Weakness to X.*** Inflict a target with weakness to a given spell type.
 - ***Reflect Damage.*** For X seconds, a percentage of received melee damage is reflected back at your attacker.
 - ***Command.*** For X seconds, targets up to a given level are placed under your control.
 - ***Slow Time.*** For X seconds, the caster's perception of time is slowed by a given percentage.

Mysticism makes these effects -- and many more -- available in a number of different formats. This pairs particularly nicely with Spell Research, because each spell type is available in a variety of archetypes, and so the spells you discover are truly unique to your character. For instance, each elemental effect is now available in cloak, bolt, "stream", on-touch, wall, and rune formats, each at several different magic levels. This means that, where vanilla only had the novice "Flames" spell in the stream format, Mysticism gives the novice "Flames", the adept "Greater Flames", and the (very well-animated) master "Flames of Oblivion" spells.

In addition, unique spells from previous games make a comeback. These range from Destruction spells like "Finger of the Mountain" and the fan-favorite "Enemies Explode" to unique Conjuration spells, allowing you to summon any type of weapon as well as various types of Dremora, Skeletons, and other creatures. Notably, through [Magistrate Levitate](https://www.nexusmods.com/skyrimspecialedition/mods/24695), Morrowind-style levitation has also been reintroduced to the game.

![Alt Text](Resources/Shield.jpeg?raw=true "Shield of Awe, from Triumvirate's Cleric school")

This is just the core of Librum's magic offerings, however. Through the addition of several curated spell packs, Librum opens up many more-specific branches of magic:

 - ***Earth, Wind, and ~Fire~ Water Magic.*** Cast the same Mysticism-style destruction spells for the elements of earth, wind, water, and poison, thanks to [Elemental Destruction Magic](https://www.nexusmods.com/skyrimspecialedition/mods/440). Certain enemies will resist or be weak to these elements, and Vokrii perks have been changed to reflect these new additions. You can also summon earth, wind, and water atronachs, in the same style as the vanilla elements, and you can apply enchantments that make use of these new elements.
 - ***Shadow Magic.*** Teleport through shadows, cloak areas in darkness or reveal important items in existing darkness, and draw power from the shadows around you, with [Triumvirate's](https://www.nexusmods.com/skyrimspecialedition/mods/39170) expansive Shadow magic options. You can also deal all-new "shadow damage", petrify opponents, and apply shadow-based curses, combining Triumvirate's more aggressive options with [Shadow Spell Package](https://www.nexusmods.com/skyrimspecialedition/mods/13299).
 - ***Blood Magic.*** Use your health in place of your Magicka to cast spells, with [Ace Blood Magic](https://www.nexusmods.com/skyrimspecialedition/mods/16995). You can also manipulate blood in the environment, with bleeding effects, blood-mists that can infect opponents, and defensive orbs or pools of blood. Vampires have their own sort of blood magic, through [Sacrosanct's](https://www.nexusmods.com/skyrimspecialedition/mods/3928) "Hemomancy" mechanic. The more you feed, the more hemomancy spells you unlock.
 - ***Nature Magic.*** Follow the path of the druid, using nature-themed spell schools from Triumvirate and [Forgotten Magic Redone](https://www.nexusmods.com/skyrimspecialedition/mods/12711). Draw power or healing from the environment, infect your target with damaging spores or poisons, or grow various damaging brambles, vines, or mushrooms around your opponent. You can also call unique animals to aid you in combat, or take the form of these animals to gain unique abilities.
 - ***Expanded Fire/Frost/Shock Magic.*** Use Forgotten Magic Redone's heavily expanded elemental options to add new combat mechanics to your Destruction mage. Teleport around the battlefield through shock gates, surround yourself with a glacial fortress or freeze would-be attackers solid, or drop meteors on distant opponents. 
 - ***Holy Magic.*** Call upon the Divines to aid you in your quest, using spells from [Dawnguard Arsenal](https://www.nexusmods.com/skyrimspecialedition/mods/25094) as well as Triumvirate and Forgotten Magic Redone. Sun spells have been expanded to match the other elements, but you can also bless your weapons in combat, protect and buff nearby allies, or summon divine weapons or guardians to fight on your behalf.
 - ***Shaman Magic.*** Triumvirate offers something for the follower of the ancient Nordic pantheon, as well. Summon Nordic totems to heal you or damage your opponents, consecrate your surroundings to gain an easily-accessible sanctuary, or look upon the land from the eye of a bird. 
 - ***Celestial Magic.*** Applying the two spell schools from _Cosmic Spells_, you can unlock the powers of the Magna-Ge. Teleport targets through wormholes or draw them with gravitational force toward a summoned body, place "Umbral Orbs" or "Luminous Crescents" around the battlefield to extend your cosmic powers, or deal _lunar_ or _void_ damage to your opponents. 
 - ***Daedric Magic.*** Through Triumvirate, Forgotten Magic Redone, and [Zim's Dremora Improvements](https://www.nexusmods.com/skyrimspecialedition/mods/12128), unlock the magic of the Daedra. Cast the same (now heavily-expanded) fire-based protection and Destruction spells as Dremora, summon all manner of new Daedra, or banish targets to Oblivion. You can also apply a whole selection of new curses, or bind enemy spirits into your summons for stronger effects. 

In addition to the above list, Librum includes a ton of new "miscellaneous" spells -- for instance, from [Tentapalooza](https://www.nexusmods.com/skyrimspecialedition/mods/652), [Caranthir Tower Reborn](https://www.nexusmods.com/skyrimspecialedition/mods/4269) or [Immersive College of Winterhold](https://www.nexusmods.com/skyrimspecialedition/mods/17004), or from any of Librum's many quest mods -- that do not fit neatly into these categories. It also includes mods like [Thunderchild](https://www.nexusmods.com/skyrimspecialedition/mods/1460), [Summermyst](https://www.nexusmods.com/skyrimspecialedition/mods/6285), and [Complete Alchemy and Crafting Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/19924), which, along with some of the mods from Librum's other "modules", allow for mage-tangent playstyles utilizing enchantments, alchemy, or shouts primarily.

Note that almost all of the above spells must be discovered on your own, through Spell Research. Because of this, you will naturally tend toward a specific magical niche (which may not align at all with the spell "classes" listed above), dependent on your experience in the different magic archetypes. In this fashion, Librum turns Skyrim's vanilla "eat a book" magic system into a truly immersive research experience; you will be able to discover nearly any sort of magic you can imagine, but you need to dedicate yourself to studying the secrets of magic.

Finally, Librum adds a new element of challenge in the form of [FIZZLE](https://www.nexusmods.com/skyrimspecialedition/mods/18180). If your magic skill isn't high enough to comfortably cast a certain spell, there is a chance that it will fail on the spot (but still drain your Magicka!). This is affected by other environmental factors, forcing mages to adapt appropriately to Skyrim's harsh climate; for instance, if you are suffering from frostbite, your magic skills will be significantly reduced, and most of your spells will fail.

### Quests and Adventures
For all its strengths, Skyrim never got the questing aspect quite right. The game's many questlines are fairly straightforward and predictable, and most of its dungeons are as well. Librum only touches the worst offenders among Skyrim's vanilla quests, but it adds a great deal of new content to experience. Putting together dozens of curated quest and adventure mods, Librum's new content totals to hundreds of new quests and new areas to explore, including more questlines than are in the vanilla game, and several extensive dungeon systems and expansive new lands. In compiling these mods, there were a few specific requirements I upheld (excluding many otherwise fantastic mods, unfortunately):
1. Every line of dialogue is voiced, and always of high quality.
2. Every addition is lore-friendly, at least within the limits of artistic license.
3. Every addition is balanced (within reason), interesting, and natural within the existing game world.

![Alt Text](Resources/molag.jpg?raw=true "Welcome to Coldharbour.")

With that in mind, here are the major new quest mods included in Librum:

1. ***[Legacy of the Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/11802).*** Legacy of the Dragonborn is, without a doubt, the largest museum curator simulator available for Skyrim.  Legacy adds a large museum -- the _Dragonborn Gallery_ -- to Solitude, in which you can store and display nearly any artifact from your collection (including those from the following mods). Not only that, Legacy adds a ton of new artifacts hidden around Skyrim, and it comes complete with a new _archaeology guild_ and an expansive questline. Though it is hard to explain here, Legacy typically becomes the center of any playthrough that involves it.
2. ***[Beyond Skyrim: Bruma](https://www.nexusmods.com/skyrimspecialedition/mods/10917).*** The first release of the ambitious and far-reaching _Beyond Skyrim_ project, Bruma allows you to explore the titular region in the north of Cyrodiil, which you may remember from _The Elder Scrolls IV: Oblivion_. Bruma is feature-complete, with a collection of excellent quests, locations, and characters; top-notch voice-acting; and a level of polish matching Bethesda's own.
3. ***[Vigilant](https://www.nexusmods.com/skyrimspecialedition/mods/11849).*** Join forces with the Vigilant of Stendarr, to face a growing threat from the _Harvester of Souls_ himself, Molag Bal. Vigilant features a huge, branching main quest, steeped in the darker sides of Elder Scrolls lore, with many secrets to uncover and difficult choices to make.
4. ***[Project AHO](https://www.nexusmods.com/skyrimspecialedition/mods/15996).*** Working with (or against!) the hidden Telvanni outpost of Sadrith Kegran, discover one of the best-kept secrets of Dwarven invention. Project AHO offers a beautifully-rendered DLC-sized area to explore, as well as a branching main quest and many Dwemeri secrets to unlock.
5. ***[Carved Brink](https://www.nexusmods.com/skyrimspecialedition/mods/24351).*** From the makers of Project AHO, Carved Brink offers a look at two new planes of Oblivion: Peryite's _Pits_ and the all-new _Faceted Stones_. Explore the excellent world design of the _Haem Projects_ team through two main questlines, using puzzle-solving and new forms of transportation to traverse these otherwise un-transversable alien landscapes.
6. ***[Clockwork](https://www.nexusmods.com/skyrimspecialedition/mods/4155).*** Clockwork offers a fully-featured player home -- the Chlodovech family's _Clockwork Castle_, high in the Velothi mountains. Though it has not been touched in two centuries, you may lay claim to it as soon as you arrive. However, once in, the castle's inhabitants may not let you leave. Uncover the secrets of the castle's founding, and of its mysterious inhabitants, through a fleshed-out and horror-themed questline.
7. ***[Moon and Star](https://www.nexusmods.com/skyrimspecialedition/mods/4301).*** Explore the quaint Dunmeri village of _Little Vivec_, floating in the center of Lake Ilinalta. Though charged with protecting Little Vivec from a dangerous criminal, you may find that Little Vivec and its inhabitants are hiding more than it seems.
8. ***[The Tools of Kagrenac](https://www.nexusmods.com/skyrimspecialedition/mods/14168).*** The Tools of Kagrenac completes the story of Arniel Gane and the legendary dagger Keening; what happened to weaken Keening so thoroughly, and where are the remaining tools of the Dwemer smith Kagrenac? Delve through sprawling new dungeons and face challenging new obstacles, in order to uncover these secrets and claim the most legendary Dwarven artifacts for yourself.
9. ***[The Forgotten City](https://www.nexusmods.com/skyrimspecialedition/mods/1179).*** The only mod so far to win a National Writers' Guild award, The Forgotten City offers a unique and enthralling mystery, set in its titular city in the far reaches of Skyrim. Investigate the inhabitants of the Forgotten City, solve intricate new puzzles, and travel through time to uncover a murder plot and escape back to the surface.
10. ***[Moonpath to Elsweyr](https://www.nexusmods.com/skyrimspecialedition/mods/4341).*** One of the great classics of Skyrim modding, but remastered for a modern experience, Moonpath to Elsweyr brings you south to the heart of the Khajiiti homeland in order to recover the legendary _Staff of Indarys_. Along the way, explore the alien jungles of Elsweyr, join forces with the Khajiiti rebellion, and gain access to the airship _Dev Aveza_.
11. ***[The Wheels of Lull](https://www.nexusmods.com/skyrimspecialedition/mods/748).*** Return to Sotha Sil's mysterious clockwork city, and take a trip through the stranger side of Elder Scrolls lore. Along the way, solve new puzzles and tread through Zelda-esque dungeons, unlock the fantastical weapons and equipment of Sotha Sil's Chronographers, and explore alien landscapes, all in the labyrinthian expanse of Sotha Sil.
12. ***[Teldryn Serious](https://www.nexusmods.com/skyrimspecialedition/mods/5541).*** Teldryn Serious heavily expands the backstory of the mercenary Teldryn Sero, taking you around Solstheim once more in order to uncover a dangerous plot and defend Raven Rock.
13. ***[Death Consumes All](https://www.nexusmods.com/skyrimspecialedition/mods/41910).*** Death Consumes All changes the game drastically, adding a spreading plague to the game world. Find and recruit the excellent companion Livia Salvian, fight the forces of the undead, and try to stop the plague and its mysterious source before it lays all of Skyrim to rest. ***The plague will have no in-game consequences until you first talk to Livia.***
14. ***[Helgen Reborn](https://www.nexusmods.com/skyrimspecialedition/mods/5673).*** A classic among Skyrim mods, Helgen Reborn gives you an opportunity to rebuild and revive the town of Helgen. Uncover a Thalmor plot, recruit and train your town guard, and participate in a ~bewildering and not-very-apropos~ secret fighting ring to reclaim the town and its legacy.

![Alt Text](Resources/sotha.jpg?raw=true "Trainwiz's work, at its finest.")

Now, one of my all-time favorite Elder Scrolls experiences is Daggerfall's dungeon delving. Despite the numerous inaccessible areas and inescapable portal networks, there was something distinctly adventurous, epic, and psychologically rewarding about making your way through one of the game's gargantuan dungeons. Librum attempts to recreate this feeling with its own suite of dungeon mods. Together, the following mods fill Skyrim (and Solstheim, and other game areas) with a healthy number of new caverns, ruins, and more -- ranging from slightly-more-involved-than-vanilla to Daggerfall-style labyrinthine dungeons.

15. ***[Skyrim Underground](https://www.nexusmods.com/skyrimspecialedition/mods/131).*** Skyrim Underground adds a _gigantic_ network of dungeons below Skyrim's surface. You can now travel from Solitude to Riften on foot, for instance, though you'll have to uncover secret passages and face many new and powerful opponents to do so. Fit for its scope, it also adds many secrets to discover, from ancient artifacts to undead merchants and impromptu underground settlements. *Skyrim Underground has been patched to be more lore-friendly, but I will continue this work in future versions*.
16. ***[Forgotten Dungeons](https://www.nexusmods.com/skyrimspecialedition/mods/449).*** Forgotten Dungeons adds many (dare-I-say) Daggerfall-style dungeons to the Skyrim and Solstheim landscapes. They can be explored independently, for their own prizes, but many have also been enabled for Skyrim's radiant quest system. *I have renamed many of the dungeons in Forgotten Dungeons, to better fit Skyrim's theme*.
17. ***[Konahrik's Accoutrements](https://www.nexusmods.com/skyrimspecialedition/mods/22206).*** This mod adds a great deal of new content surrounding Skyrim's Dragon Priests. Use the forgotten field of Abjuration magic to collect and cleanse the Dragon Priests' powerful new relics, and go back in time to explore the lost Dragon Priest temple of Revakheim.
18. ***[Skyrim Sewers](https://www.nexusmods.com/skyrimspecialedition/mods/9320).*** Skyrim Sewers adds sewer systems below Windhelm, Solitude, and Whiterun (and a few forts), bringing back the age-old Elder Scrolls experience of murdering rats, discovering secrets, and getting lost in the sewers.
19. ***[The Lost Wonders of Mzark](https://www.nexusmods.com/skyrimspecialedition/mods/40674).*** Far beyond Skyrim's northern border, the great Dwemer lord Mzark left his final projects and greatest artifacts -- but also his most clever traps and puzzles.
20. ***[Bleak Falls Barrow Revisited](https://www.nexusmods.com/skyrimspecialedition/mods/33251).*** Bleak Falls Barrow has been redone and significantly expanded, turning it from a cookie-cutter linear Skyrim dungeon into a mysterious and labyrinthine dungeon worthy of its in-game reputation.

![Alt Text](Resources/map.jpg?raw=true "Skyrim Underground Map")

Finally, Librum adds several _follower_ mods, to make the game world a little less lonely. Though some of these mods add quests, their primary role within Librum is to allow you to (a) connect with your followers as real people and (b) effectively run a party-style playthrough. Think _Fallout: New Vegas_ or _Dragon Age_, but in Skyrim.

21. ***[Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194).*** Interesting NPCs adds a ton of new quests, matching even Bruma for size. It also adds, of course, _interesting NPCs_, breathing new life into many of Skyrim's familiar locations. In particular, some of the new NPCs are "super followers", meaning that they comment on your quests, choices, and locations, and they generally behave like real people. An interesting aspect of Interesting NPCs is, many of the new quests and questlines tie several NPCs together -- this gives the game more of a "Dragon Age" feel, in terms of how characters are relatable and recurrent in your adventures.
22. ***[Inigo](https://www.nexusmods.com/skyrimspecialedition/mods/1461).*** Inigo is Skyrim's most popular follower mod, for good reason. Not only is he an effective combatant and willing to roll with whatever moral code you're comfortable with, Inigo is as close to a real companion as any Skyrim follower has come. Importantly, he responds dynamically to most situations, and he talks naturally with you and with other NPCs. Inigo can talk dynamically with vanilla and Interesting NPCs followers.
23. ***[Lucien](https://www.nexusmods.com/skyrimspecialedition/mods/20035).*** Lucien has all the benefits of Inigo, but instead of a burglarizing cat-man, he is a scholar from the Arcane University. Lucien can talk dynamically with Inigo, as well as with vanilla and Interesting NPCs followers.
24. ***[Song of the Green](https://www.nexusmods.com/skyrimspecialedition/mods/11278).*** Song of the Green adds the excellent follower Auri, who is a female Bosmer from Valenwood. Although she does not have as much dialogue as the above followers, this reflects her character naturally. Further, she can talk dynamically with Lucien, as well as with vanilla and Interesting NPCs followers.
25. ***[Hoth](https://www.nexusmods.com/skyrimspecialedition/mods/16137).*** One of the most visually unique follower mods available, Hoth is a grizzled bounty hunter and a new sort of companion to your character. Uniquely, he can provide bounty quests radiantly, dependent on your current area. He can talk dynamically with Auri.
26. ***[Serana Dialogue Edit](https://www.nexusmods.com/skyrimspecialedition/mods/16222) and [Serana Dialogue Addon](https://www.nexusmods.com/skyrimspecialedition/mods/32161).*** Together, these mods turn Dawnguard's beloved vampire follower into the sort of "super follower" introduced by the above mods. She is now aware of most quests and situations you find yourself in, and she speaks naturally with you and with others.
27. ***[Useful Dogs](https://www.nexusmods.com/skyrimspecialedition/mods/1666).*** Although a minor addition relative to the follower mods above, Useful Dogs allows you to give commands to your canine companion. You can send them looking for food, weapons, ammunition, keys, and more, in the style of Fallout 3 and 4.
28. ***[Shezarrine -- The Fate of Tamriel](https://www.nexusmods.com/skyrimspecialedition/mods/15866).*** In its current iteration, _Shezarrine_ overhauls the College of Winterhold's Onmund as a "super follower" of the above sort. In addition to greatly improved behavior and world interactions for Onmund, it adds a signifant amount to the end of the College's questline, completing the story of Onmund's family. 

### Graphics and Ambience
Last but not least, Librum includes a full graphical makeover of Skyrim. The goal is to match the photorealism we are used to these days, but with a bend towards realizing Librum's dark, gritty, and foreboding nature in Skyrim's atmosphere.Perhaps most important for this end, Librum includes a suite of literal atmosphere mods, centered around a Frankenstein-ing of [Obsidian Weathers](https://www.nexusmods.com/skyrimspecialedition/mods/12125) and [True Storms](https://www.nexusmods.com/skyrimspecialedition/mods/2472):

![Alt Text](Resources/rain.jpg?raw=true "Rain.")

We top this off with several lighting mods:

 - ***[Relighting Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/8586).*** This mod changes the position and characteristics of existing light sources in dungeons, to match where light should actually be emitted. It sounds like a simple change, but it makes a huge atmospheric difference, and it's critical to being able to sneak around.
 - ***[Enhanced Lighting for ENB](https://www.nexusmods.com/skyrimspecialedition/mods/1377).*** This is our "general purpose" lighting overhaul, and it makes a _big_ difference. In short, it makes light sources look much nicer and more natural, with a side effect of making dungeons and nights very dark.
 - ***[High Fidelity ENB](https://www.nexusmods.com/skyrimspecialedition/mods/27308).*** "But wait!" you say, "don't ENBs trash your framerate?" The answer, in this case, is _no_. High Fidelity ENB accomplishes all of the things you've come to expect from your ENB, but it's highly performance-friendly for a better VR experience. Furthermore, it pairs very nicely with the mods listed above, to give Skyrim the bleak, hopeless feel you've been waiting for.

The above only gives a small taste of the various atmosphere and ambience mods included in Librum -- you can visit the manifest for a complete list, but Librum includes everything from [new dust effects](https://www.nexusmods.com/skyrimspecialedition/mods/2407) to [better cloud textures](https://www.nexusmods.com/skyrimspecialedition/mods/2393) and even [better sound dynamics](https://www.nexusmods.com/skyrimspecialedition/mods/701).

![Alt Text](Resources/lights.png?raw=true "ELE + RS")

As we have become accustomed to, Librum also overhauls everything graphical about Skyrim, its world, and its inhabitants. Although I will not cover every detail of this graphical redux (see the manifest for a complete list), I will touch on some of the points that add to Librum's unique, gritty feel.

First of all, as mentioned earlier in the [Combat and Enemies](#combat-and-enemies) section, Librum uses [Savage Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/37768) (along with several texture-enhancing mods) to redesign many of Skyrim's creatures. Some, like Spriggans, Seekers, and Lurkers, have been made significantly creepier and more imposing, befitting their supernatural nature. Ice Wraiths have been made more serpent-like, Netches have been given longer tentacles, and Rieklings have been made larger and more muscular. Hardy animals, from mammoths to horkers, have been made to look hardier; more slender animals, such as wolves and skeevers, have been made to look hungrier, more vicious, and wild-eyed. Dragons, vampire lords, and gargoyles have been given larger wings, Dwemer automata have been given better and scarier-looking proportions, and the new insects have been called "pure nightmare fuel".

![Alt Text](Resources/treedude.jpg?raw=true "Spriggans, in all their creepy-ass glory.")

Another interesting addition to Librum comes in the form of [Frozen Electrocuted Combustion](https://www.nexusmods.com/skyrimspecialedition/mods/3532). This mod adds bodily repurcussions to magic and elemental effects of all kinds. Fire may burn an opponent's skin right off, or just leave a nasty scar. Shock can cause spasms, or many worse effects. Frost can freeze an opponent solid -- striking a frozen foe will break them into several pieces. Effects have been added to everything from Fear to Soul Trap, so see the mod page for more information. In general, these new effects make the battlefield a grisly sight, and they make you think twice before zapping a fellow human person with _Lightning Storm_.

![Alt Text](Resources/oof.png?raw=true "Oof.")

Finally, one of my major goals of Librum was to make the existing Skyrim content feel new and different. As such, Librum completely redoes every town and city in Skyrim, from large-scale architecture and layout changes to a re-imagining of citizens' AI, all towards the end of making Skyrim a natural-but-exciting place to be.

On the town-and-city level, Librum combines the [Great City series](https://www.nexusmods.com/skyrimspecialedition/mods/20272) (except for Rorikstead and Winterhold, for compatibility) with [Dawn of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/9074) and Cities of the North: [Dawnstar](https://www.nexusmods.com/skyrimspecialedition/mods/28952), [Winterhold](https://www.nexusmods.com/skyrimspecialedition/mods/40088), and [Morthal](https://www.nexusmods.com/skyrimspecialedition/mods/34168). It also includes the minor mods in the Great City series: [Solitude (docks)](https://www.nexusmods.com/skyrimspecialedition/mods/22243), [Karthwasten](https://www.nexusmods.com/skyrimspecialedition/mods/33032), [Old Hroldan](https://www.nexusmods.com/skyrimspecialedition/mods/33189), [Ivarstead](https://www.nexusmods.com/skyrimspecialedition/mods/34505), [Shor's Stone](https://www.nexusmods.com/skyrimspecialedition/mods/35977), [Mixwater Mill](https://www.nexusmods.com/skyrimspecialedition/mods/36350), and [Kynesgrove](https://www.nexusmods.com/skyrimspecialedition/mods/42639). For Solstheim, I have included [Better Tel Mithryn](https://www.nexusmods.com/skyrimspecialedition/mods/643) and [Quaint Raven Rock](https://www.nexusmods.com/skyrimspecialedition/mods/20851).

Not only do these city improvements make the cities denser, livelier, and more realistic -- they also give each city, town, and hamlet its own unique character. Instead of the "see one, see them all" nature of the towns in vanilla Skyrim, each of Skyrim's villages has its own architectural style, its own industry, and its own landscape.

![Alt Text](Resources/karthwasten.jpg?raw=true "The Great Town of Karthwasten")

Importantly, Librum also includes the changes from [Open Cities](https://www.nexusmods.com/skyrimspecialedition/mods/281), allowing you to seamlessly transition from a city interior to the world of Skyrim. This pairs nicely with mods like [Sneak Tools](https://www.nexusmods.com/skyrimspecialedition/mods/1863) and [Magistrate Levitate](https://www.nexusmods.com/skyrimspecialedition/mods/24695), which allow you to climb over or float above city walls, respectively.

These architectural changes are matched with AI improvements for the citizens of Skyrim. Using [AI Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/21654), Librum makes townspeople act like real townspeople. People will spend the day hunting, farming, traveling, shopping, or cooking (or whatever else they want to do), depending on their profession and the circumstances. Friends and family may gather at the local tavern or for shared meals, for instance. People will more realistically mourn the loss of a friend or loved one. They'll pray at temples associated to their faith. They may even act realistically during combat (and sometimes run away). In addition, [Wet and Cold](https://www.nexusmods.com/skyrimspecialedition/mods/644) forces NPCs to respond correctly to weather events. They'll put on hoods or masks in snow- and ash-storms, respectively, and they'll try to get home as quickly as possible. Wet and Cold makes a number of more graphical improvements, as well, such as visible breath when cold or snow/ash accumulation on people's clothes. Of course, the AI effects of the above mods are magnified by [Realistic Conversations](https://www.nexusmods.com/skyrimspecialedition/mods/1717), [Relationship Dialogue Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/1187), and [Guard Dialogue Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/20791), which make normal citizens and guards not sound like robots or maniacs.

Librum overhauls specific buildings, as well, with [Palaces and Castles Enhanced](https://www.nexusmods.com/skyrimspecialedition/mods/1819), [Distinct Interiors](https://www.nexusmods.com/skyrimspecialedition/mods/6130), [Immersive College of Winterhold](https://www.nexusmods.com/skyrimspecialedition/mods/17004), and [Immersive Fort Dawnguard](https://www.nexusmods.com/skyrimspecialedition/mods/40436). Overall, these mods give a more hand-crafted feel to the world of Skyrim; many of Skyrim's interiors have been totally redesigned, with hand-placed objects, furniture, and lighting, and with elements unique to their location or purpose. Stores will now have goods on display, for instance, and inns and other regional establishments will be decorated according to their respective regions.

![Alt Text](Resources/stendarr.jpg?raw=true "Fort Dawnguard's Temple of Stendarr")

Last but not least, Skyrim's wilderness has also seen some improvements. Along with the hundreds of new dungeons and locations mentioned in the preceding section, several existing locations have been redone. For one, [Nordic Ruins of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/20382) improves the exteriors of several key ruins around Skyrim: Forelhost, High Gate Ruins, Korvanjund, Labyrinthian, Ragnvald, Rannveig's Fast, Saarthal, Valthume, and Volskygge. These legendary ruins now _look_ legendary, and they can all be seen as such from a great distance. The same has been done for Dwemer ruins, using [Better Dwemer Exteriors](https://www.nexusmods.com/skyrimspecialedition/mods/27618) -- as with the new Nordic ruins, these now have greatly expanded (and much more imposing) exteriors.

Librum also includes [Man Those Borders](https://www.nexusmods.com/skyrimspecialedition/mods/681), [Unique Border Gates](https://www.nexusmods.com/skyrimspecialedition/mods/4819), [Hold Border Banners](https://www.nexusmods.com/skyrimspecialedition/mods/1737), and [Immersive Dawnguard Dayspring Pass](https://www.nexusmods.com/skyrimspecialedition/mods/4126), to make the transitions between different holds and the journeys through wilderness zones a little more unique. Guards will now be stationed where they ought to be, and each hold can be identified by its flags and architectural styles upon arrival. Also, the entrance to the Dawnguards' territory is no longer a stupid piece-of-shit hole in a cliff wall.

![Alt Text](Resources/whiterun.jpg?raw=true "Whiterun Crossroads Keep")

## Getting Started in Librum

## Frequently Asked Questions
Here are some questions that you might want to ask:

***I have enough XP to level up, but opening the skills menu isn't working!*** Sleep 8 hours to level up. You need to wait a full day before leveling again.

***I can't switch between buying and selling.*** You can switch between buying and selling by using the cursor. Sometimes it takes exiting the menu once and re-entering, but the idea is to click outside the bounds of the menu to activate the cursor.

***Why is campfire/tent placement not working?*** In Campfire's MCM, turn off _advanced placement_.

***When I level up, I still get a perk!*** Check your ~Librum/overwrite~ folder for a ~plugins/sumwunn/skyrimuncapper.ini~ file. If that exists, delete it. If not, let me know.

***What the hell are these new enemies below [insert city name]?*** You've encountered _Skyrim Underground_, and, honestly, I'm with you. Although I've applied a patch to make Underground more lore-friendly, there is a little more work to be done. I will sort this out in future versions.

***The game is crashing!*** While I've done my best to mitigate crashing and poor performance, we all know that Skyrim's engine is not a perfect one. Let me know where and when the game crashes, and I'll try to figure it out.

***I don't like [insert feature]!*** Please let me know! I'm open to suggestions, especially as Librum is getting off the ground. Whether you think something is unbalanced, not fun, or only gives off the wrong _vibe_, please shoot me a DM over Discord.

***I've found a bug!*** Let me know about bugs, as well! I'll try to help you figure it out -- of course, if you modified Librum in any fashion, you may be on your own.

***I think [insert mod] should be added/removed!*** As before, let me know of any suggestions you have. There are many cases where I made specific choices for compatibility's sake (i.e., Dawn of Skyrim over JK's Skyrim, or excluding EFF/NFF/AFT), but there are many others where I may have overlooked an excellent candidate for inclusion in Librum.

## Credits and Thanks
Of course, I can only take a small slice of the credit for this modlist. I compiled the list and Frankenstein-ed many of these mods together, but the mod authors themselves did most of the work. If you particularly like a certain quest, location, or gameplay mechanic, please go thank the mod authors!

## Contact
For any questions, comments, or suggestions, please join my modding Discord server:

[<img src="Resources/discord.png" width="150">](https://discord.gg/3f8vPYFmJX)


