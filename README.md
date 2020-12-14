# Librum (for Skyrim VR)
Wabbajack modlist installer for Librum

- [Librum](#librum-for-skyrim-vr)
  - [Preamble](#preamble)
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
    - [Post-Installation](#pnost-installation)
      - [Copy "Game Folder Files"](#copy-game-folder-files)
      - [Starting Librum and Choosing Optional Plugins](#starting-librum-and-choosing-optional-plugins)
      - [Start Skyrim... again](#start-up-skyrim-again)
      - [MCM Settings](#configure-the-mcm)
  - [Updating](#updating)
  - [Features of Librum](#features-of-librum)
    - [Leveling and Experience](#leveling-and-experience)
    - [Survival and Realism](#survival-and-realism)
    - [Combat, Loot, and Challenge](#combat-loot-and-challenge)
    - [Magic](#magic)
    - [Quests and Adventures](#quests-and-adventures)
    - [Followers](#followers)
    - [Graphics and Ambience](#graphics-and-ambience)
  - [Getting Started in Librum](#getting-started-in-librum)
  - [Frequently Asked Questions](#frequently-asked-questions)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Contributing](#contributing)
  - [Changelog](#changelog)
  - [Discussions](#discussions)
 
## Preamble

_You're lost in the woods, having narrowly escaped after scaring off a pack of wolves with a summoned flame atronach. Your torch finally fades out, and it's getting cold. You can conjure basic foods, and your summoned atronach provides enough heat for the time being, but you'll need to gather wood in order to sustain a fire and survive the night. With little time to spare, you can't search far for materials -- luckily, you've fashioned a basic hatchet the night before, and you can chop down a nearby tree for lumber. You fall asleep next to your fire, having placed several runes nearby to dispatch would-be predators. Despite a few interruptions in the night, the morning comes at last, and the sun finally breaks over the horizon._

Skyrim VR is a wonderful experience, but it's a very familiar one. Even in stunning 3D, we visit the same locales and repeat the same adventures we have since the end of 2011.

_Librum_ is a comprehensive gameplay, graphics, and content overhaul that attempts to change all of this. Combining together some of the best and most popular mods for Skyrim SE, a suite of new quests and adventures that outnumber Skyrim's own, the tradition of great "hardcore" gameplay overhauls that have come before -- like Skyrim's _Requiem_ and _YASH_ or Oblivion's _Oscuro's Oblivion Overhaul_ -- and a host of unique-to-VR immersion improvements, Librum brings new life (and new challenge!) to Skyrim in a way that has never been experienced before.

## Installation

Librum makes use of the excellent [Wabbajack](https://www.wabbajack.org/#/) program to make its installation as fast and painless as possible. That said, there are a few, very easy steps involved in setting up Librum. We will go over each in detail, but they are summarized as follows:

1. Clean your Skyrim folder and disable the Steam overlay.
2. Install the Wabbajack desktop client from [here](https://github.com/wabbajack-tools/wabbajack/releases).
3. Navigate to Librum under the _Browse for Modlists_ tab.
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
2. Download the modlist from [here](must update link) and choose the  _Install from Drive_ option in Wabbajack.
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
Navigate to the installed Librum folder, where you will find a folder titled `Game Folder Files`. Copy the contents of this folder to the Skyrimv root folder.

#### Starting Librum and Choosing Optional Plugins
Navigate back to the installed Librum folder, and launch the program `ModOrganizer2.exe`. Before launching the game itself, take a look at the _Optional_ category at the bottom of the Mod Organizer 2 mod list. I will go over each below.

***End Times*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/39201)]. This plugin adds a sense of urgency to the Main Quest, and it ties in nicely with Librum's re-centering of Skyrim around being the Dragonborn. Specifically, if you do not defeat Alduin within a certain amount of time (365 days by default, but configurable in the MCM), he will swallow the world (accompanied by a nice visual), and you will have to reload and try again. You will have a _Doomsday Clock_ spell available, as well as configurable regular updates, to tell you how much time you have left.

If you do not want this plugin, disable it in MO2.

***Dragons from the Start*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/41453)]. This plugin enables dragon encounters from the very beginning of the game. This is highly recommended for Librum's Dragonborn-centric play, and it is especially important if you use the next optional plugin. 

If you do not want this plugin, disable it in MO2.

***No Perks on Level-Up***. This is a core feature of Librum, so it is highly recommended. With this plugin, you will no longer earn perks when you level up; rather, you will have to spend dragon souls in order to earn perk points. This accomplishes two things. First, along with other mods from the core modlist, this re-centers the Skyrim experience on you _actually being the Dragonborn_. You will not progress without hunting dragons and progressing the main quest. Secondly, this reframes the role of perks in the Librum experience. Because (especially at the beginning) they are much harder to obtain, they will form a much smaller part of your character's identity, and your character will spend a longer time being a "normal person".

If you do not want this plugin, disable it in MO2.

***High Fidelity ENB - LCD vs OLED*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/27308)]. Librum makes use of the excellent _High Fidelity ENB_, which fixes Skyrim's lighting while retaining the high framerates necessary for a good experience. If you have an LCD-based headset (Valve Index, Rift S), enable only the LCD version. If you have an OLED-based headset (Vive, Rift CV1), enable only the OLED version.

Choose the appropriate plugin.

***WICO Non-Nude Meshes*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/2136)]. Librum uses WICO as a base, in order to overhaul character appearances in a natural-looking way. If you do not want nudity in your game, enable this plugin.

If you want this plugin, enable it in MO2.

#### Start up Skyrim... again
To start the game for real, start SKSE through Mod Organizer 2. This will be necessary every time you start the game; if you try to launch Skyrim through its default folder or through Steam, the game will be entirely vanilla.

Start a new game once you get to the main menu. The "yes/no" dialogue in the _New Game_ menu does not always indicate which you are selecting, but the buttons will work as expected. You will start in the character creation area from [Realm of Lorkhan](https://www.nexusmods.com/skyrimspecialedition/mods/18223). Here are some things to know as you create your character:

1. Race and gender differences are changed in accordance with [Race Abilities Enhanced](https://www.nexusmods.com/skyrimspecialedition/mods/23223) and [Genders are Boringly Indistinct](https://www.nexusmods.com/skyrimspecialedition/mods/23145), but with the modifications made by [Elemental Destruction Magic](https://www.nexusmods.com/skyrimspecialedition/mods/440). Namely, Orcs are 50% resistant to earth magic, and Argonians are 50% resistant to water magic.
2. Standing stones are changed in accordance with [Andromeda](https://www.nexusmods.com/skyrimspecialedition/mods/14910). However, **the standing stone you choose in the Realm of Lorkhan is final**. That is, you will not be able to change it without first returning to the Realm of Lorkhan.
3. Be particular with the items, spells, and powers you bring back from the Realm of Lorkhan. Much moreso than in vanilla Skyrim, having additional weapons, armors, spell tomes, gold, or even food items can start you out with a significant advantage. If you do not want this advantage, do not take anything with you.

#### Configure the MCM
Once you have created your character, open up the in-game settings and navigate to the _Mod Configuration Menu_ (MCM). You will need to make several changes here to adhere to the suggested Librum setup. Unfortunately, very few of the mods used in Librum support FISS, so you will need to do this each time you create a new character.

The suggested MCM options are as follows:
1. **Bounty Gold.** In the left column, set "Bandits" to 300, "Forsworn" to 350, "Giants" to 400, and "Dragons" to 500. These match the default values of The Notice Board.
2. **Campfire.** Under the _Advanced_ tab, disable "Advanced Object Placement". It conflicts with VR.
3. **Clockwork.** Turn off "Recall Spell Fast-travel Check". This makes the Clockwork Recall spell a very good reward, which fits new difficulty of surviving during Clockwork's questline.
4. **Cobb Encumbrance.** In the _Presets_ tab, apply the preset "Classic (SEM)".
5. **Complete Alchemy and Crafting Overhaul.** Apply the following changes:
  - _Alchemy_ tab: change all potion/poison durations to 10s. 
  - _Harvest_ tab: change _Food containers_ frequency to "scarce", and quantity to "reduced".
6. **Dynamic Things.** Apply the following changes:
  - _Containers/Activators_ tab: deactvivate "Dynamic Safe Containers".
  - _Advanced Options_ tab: activate "Containers are destructible", "Realistic amount of wood per tree", "Realistic chopping time", and "No food containers".
7. **End Times.** Adjust to taste -- I leave this at 365 days.
8. **Frostfall**. Apply the following changes:
  - _Overview_ tab: Activate the mod. 
  - _Gameplay_ tab: "At max exposure" -> "death", and disable fast travel and waiting while outdoors.
  - _Meters_ tab: "Layout preset" -> "bottom left" recommended.
9. **Hunterborn**. Start the mod, and then under the _Enable_ tab, disable the Hunterborn config power.
10. **iNeed.** Apply the following settings:
  - _Basics_ tab: Automate eating and drinking, and set the timescale to 8.
  - _Difficulty_ tab: "Food spoilage" -> "numbers".
  - _Notifications_ tab: "Widget style" -> "disabled".
11. **MageVR.** Spawn MageVR backpack, and "Archery Mode" -> "Realistic".
12. **OBIS - Bandits.** Apply the following settings:
  - _Settings_ tab: Enable extra spawns.
  - _Special_ tab: Enable minotaurs and spiders.
13. **OBIS - Patrols.** Enable under _Settings_.
14. **SkyUI.** Under _General_, disable the Active Effects HUD.
15. **SkyVoice.** Remove the Skyvoice Options Spell.
16. **Sleep to Level Up.** Disable "Require Sleep to spend Perk Points".
17. **Smart Training.** Disable "Training Perk Points" and activate the mod.
18. **Sneak Tools.** Under the _Patch_ tab, disable Horstar's extra dialogue. It is not voiced, unfortunately.
19. **Sounds of Skyrim.** Adjust to taste, but I don't disable anything.
20. **Sands of Time Sleeping Encounters.** In the left column, disable home invasions, set "Jorrvaskr Hall HQ" and "College Ambush Odds" to 0, set "Dungeon Ambush Odds" and "Draugr Keep Ambush Odds" to 50, and set "All Other Places" to 25.
21. **Souls Do Things 2.** Under _Settings_, enable "Conversion Spell Learned" if and only if you disabled perk points on level-up earlier.
22. **Spell Research.** Import all spells.
23. **Tentapalooza.** The tents _should_ provide Frostfall support without changing these settings, but let me know if this fails.
24. **Trade & Barter.** Under _Barter Rates_, enable "Modify Barter Settings" and set "Barter Presets" -> "Hardcore".
25. **WeaponThrowVR.** Under _Presets_, enable either "Cangar's Selection" or "Classic Medium", depending on whether you think the awesome auto-return animation is worth a slight lack of realism.
26. **Wildcat Combat.** Enable "Allow Wildcat to manage difficulty".

Further, there are a few settings to change using mod configuration spells:
1. **Destructible Skyrim.** Simply click "remove spell".
2. **Obsidian Weathers.** Enable seasonal effects, and choose the "Bleak" preset.

Congratulations! You've completed the Librum setup, and you are ready to play. The next several sections will explain what Librum is and does, as well as provide support.

%% Updating
If Librum receives an update, please check the Changelog before doing anything. Always back up your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the updated modlist when updating!**

This means that any additional mods you have installed on top of Librum will be deleted. However, your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _Overwrite existing modlist_ button.

%% Features of Librum
Librum significantly affects nearly every aspect of gameplay; in this section, I explain all of the significant changes that have been made, and how they change the Skyrim experience. I will separate it here into various "modules" for ease of explanation -- however, this does not reflect any clean-cut separations of Librum mechanics. Changes from the various modules overlap, affect one another, and work together to create a consistent Librum experience. For instance, _Spell Research_ forces mages to interact with the survival elements of Librum, and these survival elements turn a quest like _Clockwork_ into a precarious and time-sensitive escape mission.

With this in mind, here is a rough breakdown of what Librum accomplishes.

%%% General Philosophy
With every change, Librum attempts to adhere to the points of its _core philosophy_:

1. Librum is a game about _being Dragonborn_. Your dragon soul is a fundamental part of your character's development, and there is no way to indefinitely avoid this destiny.
2. The world is static in ways that make sense, but dynamic in all others. The world is not centered around you, but it reacts realistically to the actions you take and the choices you make. In particular, the ways in which you interact with the world change as you become more powerful.
3. Magic in all forms is a dangerous, arcane, and powerful force. Magic can solve most any problem you have, but -- as an example -- acquiring a single Master-level spell might take a whole playthrough.

We will reference these points by number in the sections that follow. 

%%% Leveling and Skills
Librum makes several major changes to the skill system, described by the following comparison table:

 Vanilla Skyrim | Librum
 -------------- | ------
 Sucks ass	| Is good



