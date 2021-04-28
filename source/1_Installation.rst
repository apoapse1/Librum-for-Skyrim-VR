.. role:: raw-html-m2r(raw)
   :format: html


Librum (for Skyrim SE/VR)
=========================

Wabbajack modlist installer for *Librum*.

**A small request: if you enjoy my work, please consider contributing to my Patreon page at the link below. Although I certainly don't expect any donations from users, these sorts of contributions allow me to continue improving and supporting Librum.**

`
.. raw:: html

	<img src="https://raw.githubusercontent.com/apoapse1/Librum-for-Skyrim-VR/main/Resources/patreon.png" width="150" height="50">

<https://www.patreon.com/apoapse?fan_landing=true>
`

* `Librum <#librum-for-skyrim-sevr>`_

  * `Preamble <#preamble>`_
  * `Technical Requirements <#technical-requirements>`_
  * `Installation <#installation>`_

    * `Pre-Installation <#pre-installation>`_

      * `Installing Microsoft Visual C++ Redistributable Package <#installing-microsoft-visual-c-redistributable-package>`_
      * `Steam Config <#steam-config>`_
      * `Start Skyrim <#start-up-skyrim>`_

    * `Using Wabbajack <#using-wabbajack>`_

      * `Preparations <#preparations>`_
      * `Downloading and Installing <#downloading-and-installing>`_

        * `Problems with Wabbajack <#problems-with-wabbajack>`_

    * `Post-Installation <#post-installation>`_

      * `Copy "Game Folder Files" <#copy-game-folder-files>`_
      * `Optional Plugins <#optional-plugins>`_

        * `Gameplay Customization <#gameplay-customization>`_ 
        * `UI Customization <#ui-customization>`_

      * `Starting Librum <#starting-librum>`_
      * `MCM Settings <#configure-the-mcm>`_

    * `VR Configuration <#vr-configuration>`_

  * `Updating <#updating>`_
  * `Strategy Guide <#strategy-guide>`_
  * `Features of Librum <#features-of-librum>`_

    * `General Philosophy <#general-philosophy>`_
    * `Character Creation <#character-creation>`_
    * `Leveling and Skills <#leveling-and-skills>`_
    * `User Interface <#user-interface>`_
    * `VR Experience <#vr-experience>`_
    * `Dynamic World <#dynamic-world>`_
    * `Survival and Realism <#survival-and-realism>`_
    * `Combat and Enemies <#combat-and-enemies>`_
    * `Magic <#magic>`_
    * `Quests and Adventures <#quests-and-adventures>`_
    * `Graphics and Ambience <#graphics-and-ambience>`_

  * `Frequently Asked Questions <#frequently-asked-questions>`_
  * `Credits and Thanks <#credits-and-thanks>`_
  * `Contact <#contact>`_

Preamble
--------


.. image:: _images/Resources/DoubleBanner.png?raw=true
   :target: _images/Resources/DoubleBanner.png?raw=true
   :alt: Banner



.. raw:: html

   <div align="center"><b>With big thanks to the Librum team: Mashtyx, Snidely, EllieMental, JulieChaos and NemeanLion.</b></div>
   <br/>

   _You're lost in the woods, having narrowly escaped after scaring off a pack of wolves with a summoned flame atronach. Your torch finally fades out, and it's getting cold. You can conjure basic foods, and your summoned atronach provides enough heat for the time being, but you'll need to gather wood in order to sustain a fire and survive the night. With little time to spare, you can't search far for materials -- luckily, you've fashioned a basic hatchet the night before, and you can chop down a nearby tree for lumber. You fall asleep next to your fire, having placed several runes nearby to dispatch would-be predators. Despite a few interruptions in the night, the morning comes at last, and the sun finally breaks over the horizon._

   Skyrim VR is a wonderful experience, but it's a very familiar one. Even in stunning 3D, we visit the same locales and repeat the same adventures we have since the end of 2011.

   _Librum_ is a comprehensive gameplay, graphics, and content overhaul that attempts to change all of this. Combining together some of the best and most popular mods for Skyrim SE, a suite of new quests and adventures that outnumber Skyrim's own, the tradition of great "hardcore" gameplay overhauls that have come before -- like Skyrim's _Requiem_ and _YASH_ or Oblivion's _Oscuro's Oblivion Overhaul_ -- and a host of unique-to-VR immersion improvements, Librum brings new life (and new challenge!) to Skyrim in a way that has never been experienced before.

   Librum is available for both VR and SE. 

   ***User Comments:***

   <div align="center">"This is definitely the most different playthrough I've ever done."</div>



.. raw:: html

   <div align="center">"I'm not used to the difficulty, but it was probably the most fun I had on Skyrim."</div>



.. raw:: html

   <div align="center">"It's refreshing. At this point I would have all novice spells that I wanted in a normal playthrough."</div>



.. raw:: html

   <div align="center">"I don't have enough money to pay followers 500/week."</div>



.. raw:: html

   <div align="center">"Are bandits meant to attack when you're sleeping in an inn? Kinda like it, I have to admit."</div>



.. raw:: html

   <div align="center">"Certainly seems like I'll have to treat this like a new game rather than the skyrim I've come to know."</div>



.. raw:: html

   <div align="center">"Rick Harrison from pawn stars is literally from Librum's Skyrim. [Sword worth 150 Septims] 'Best I can do is 10.'"</div>



.. raw:: html

   <div align="center">"So far I've had a blast with the modlist. Makes Skyrim feel like a new game."</div>


Technical Requirements
----------------------

Librum is fairly technically intensive, but in line with standard Skyrim VR graphics enhancements. Your mileage will certainly vary -- I can only provide my own specs, but I imagine you will find good performance on a weaker system.

**\ *Space Requirements.*\ ** Librum requires 38 GB of space for its downloads, and 70 GB of space for the installation. In total, you will need 118 GB free on your computer.

**\ *Recommended Specs.*\ ** This was the machine I compiled Librum on. I get a very smooth 40 FPS, which gives quite smooth gameplay along with Oculus/SteamVR motion smoothing.


* **CPU**\ : Intel Core i7-7700HQ, 4 cores at 2.80 GHz.
* **GPU**\ : NVIDIA GeForce GTX 1060, 6 GB of VRAM
* **RAM**\ : 16 GB DDR4

Installation
------------

Librum makes use of the excellent `Wabbajack <https://www.wabbajack.org/#/>`_ program to make its installation as fast and painless as possible. That said, there are a few, very easy steps involved in setting up Librum. We will go over each in detail, but they are summarized as follows:


#. Clean your Skyrim folder and disable the Steam overlay.
#. Install the Wabbajack desktop client from `here <https://github.com/wabbajack-tools/wabbajack/releases>`_.
#. (VR) Navigate to Librum under the *Browse for Modlists* tab.
#. (SE) Download the Librum_SE.wabbajack file from the "Releases" tab on this GitHub.
#. Install Librum to a new folder outside of ``Program Files`` using Wabbajack.
#. Copy the ``Game Folder Files`` folder to your Skyrim VR or SE directory.
#. Start a new game, and wait until mod installation notes finish appearing in the top left.
#. Configure the Mod Configuration Menu (MCM) according to the `instructions that follow <#mcm>`_.

Pre-Installation
^^^^^^^^^^^^^^^^

These steps are only needed if you are installing Librum for the first time. If you only want to update Librum, jump straight to `Updating <#updating>`_.

Installing Microsoft Visual C++ Redistributable Package
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from `Microsoft <https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads>`_. Download the x64 version under "Visual Studio 2015, 2017 and 2019". `Direct link <https://aka.ms/vs/16/release/vc_redist.x64.exe>`_ if you can't find it.

Steam Config
~~~~~~~~~~~~


* 
  **Disable the Steam Overlay** - The Steam Overlay can cause issues with ENB and is recommended to be turned off. Open the Properties window (right click the game in your ``Library -> Properties``\ ), navigate to the *General* tab and un-tick the *Enable the Steam Overlay while in-game* checkbox.

* 
  **Set the Game language to English** - Librum is entirely in English, as many excellent mods are English-exclusive. This may change in the future, but for now, I highly recommend playing the game in English. Open the Steam Properties window, navigate to the *Language* tab and select *English* from the dropdown menu.

* 
  **Clean Skyrim** - If your Skyrim VR or SE installation is not newly installed, I recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the ``Skyrim VR`` or ``Skyrim SE`` folder in ``Documents/My Games/`` by deleting the contents in it. 

Start up Skyrim
~~~~~~~~~~~~~~~

After you have done everything above and have a clean Skyrim VR/SE installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about the graphics settings at this point, as the Librum installation will replace them. 
Start the game and exit once you're in the main menu.

Using Wabbajack
^^^^^^^^^^^^^^^

Preparations
~~~~~~~~~~~~

Grab the latest release of Wabbajack from `here <https://github.com/wabbajack-tools/wabbajack/releases>`_ and place the ``Wabbajack.exe`` file in a *working folder*. This folder **must not** be in a *common folders* like your Desktop, Downloads, or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like ``C:/Wabbajack``.

Downloading and Installing
~~~~~~~~~~~~~~~~~~~~~~~~~~

The download and installation process can take a very long time, depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.


#. Open Wabbajack.
#. (VR) Browse for the modlist in the Wabbajack client, and click to download it.
#. (SE) Download the Librum_SE.wabbajack file from the "Releases" tab on this GitHub, and open it up in the "Install From Disk" option in the Wabbajack client. Do not place the .wabbajack file in the folder you want to install Librum to.
#. Once the download is complete, set the installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, or Desktop. Put it somewhere easy like ``C:/Modlists/Librum``\ ). The downloads path should automatically fill in the installation path, but this can be changed if needed. 
#. Click the Go/Begin button.
#. Wait for Wabbajack to finish.
#. If you run into any issues, see the next section. If the installation is successful, proceed to `Post-Installation <#post-installation>`_.

Problems with Wabbajack
"""""""""""""""""""""""

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off, so you lose no progress.


* 
  **\ *Could not download X.*\ ** If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update Librum.

* 
  **\ *X is not a whitelisted download.*\ ** This can happen when I update the modlist. Check if a new update is available and wait if there is none.

* 
  **\ *Wabbajack could not find my game folder.*\ ** Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the `Pre-Installation <#pre-installation>`_ step and ensure you've started up Skyrim once before you open Wabbajack.exe so the scan can locate your installation.

* 
  **\ *Windows is reporting that a virus has been detected.*\ ** Windows 10 has started to auto-quarantine the ``usvfs_proxy_x86.exe`` file from the latest version of Mod Organizer 2, saying a threat has been detected. This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for Windows Defender can be found `here <https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan>`_.

* 
  **\ *Cyclic Redundancy Check error during installation*\ ** This could be several things, but the first thing we would recommend is confirming that Wabbajack is not installed in your Documents, Downloads or Program Files folders, then delete the contents of ``%APPDATA%/Local/Wabbajack`` and re-open the app and try again. If this does not resolve the problem, it could be related to drive corruption and you should run CHKDSK on the drive in question.

Post-Installation
^^^^^^^^^^^^^^^^^

Now that Librum is installed, it is time to start the game up for real and create your character. The character creation process has changed with Librum, so we will give details below. Moreover, it is highly recommended that you **configure the MCM after race selection** as described below.

Copy "Game Folder Files"
~~~~~~~~~~~~~~~~~~~~~~~~

Navigate to the installed Librum folder, where you will find a folder titled ``Game Folder Files``. Copy the contents of this folder to the Skyrim root folder.
If you don't want 3D sound, do not copy over ``x3audio1_7.dll`` and the ``hrtf`` folder.

**(VR) Optional: CAS Sharpener for VR.** If you find that the game is too blurry with the default ENB preset, I have included `CAS Sharpener <https://www.nexusmods.com/skyrimspecialedition/mods/38219>`_ Note that it will compromise the "ominous" look of the default ENB.

Optional Plugins
~~~~~~~~~~~~~~~~

Navigate back to the installed Librum folder, and launch the program ``ModOrganizer.exe``. Before launching the game itself, take a look at the *Optional* category at the bottom of the Mod Organizer 2 mod list - you may need to expand the category to view the mods. I will go over each below and indicate if they are *(Enabled)* or *(Disabled)* by default.

Gameplay Customization
""""""""""""""""""""""


* 
  **End Times** [\ `Nexus <https://www.nexusmods.com/skyrimspecialedition/mods/39201>`_\ ] *(Enabled)* This plugin adds a sense of urgency to the Main Quest, and it ties in nicely with Librum's re-centering of Skyrim around being the Dragonborn. Specifically, if you do not defeat Alduin within a certain amount of time (365 days by default, but configurable in the MCM), he will swallow the world (accompanied by a nice visual), and you will have to reload and try again. You will have a *Doomsday Clock* spell available, as well as configurable regular updates, to tell you how much time you have left. If you do not want this plugin, disable it in MO2.

* 
  **Dragons from the Start** [\ `Nexus <https://www.nexusmods.com/skyrimspecialedition/mods/41453>`_\ ] *(Enabled)* This plugin enables dragon encounters from the very beginning of the game (keep in mind there are no random dragons as of 2.0). This is highly recommended for Librum's Dragonborn-centric play, and it is especially important if you use the next optional plugin. If you do not want this plugin, disable it in MO2.

* 
  **No Perks on Level-Up** *(Enabled)* This is a core feature of Librum, so it is highly recommended. With this plugin, you will no longer earn perks when you level up; rather, you will have to spend dragon souls or discover special Librums (books) in order to earn perk points. This accomplishes two things. First, along with other mods from the core modlist, this re-centers the Skyrim experience on you *actually being the Dragonborn*. You will not progress without hunting dragons and advancing major questlines. Secondly, this reframes the role of perks in the Librum experience - because (especially at the beginning) they are much harder to obtain, they will form a much smaller part of your character's identity, and your character will spend a longer time being a "normal person". If you do not want this plugin, disable it in MO2 - but keep in mind that we've still implemented 1 perk every 2 levels instead of 1 for 1 to help maintain some semblance of balance with our vision.

* 
  **Morrowind-Style Beast Races** *(Enabled)* This mod liberates the paws and claws of Argonians and Khajiits. Plan accordingly for their inability to wear boots! If you do not want this plugin, disable it in MO2.

* 
  **(VR) New Voice Commands** *(Enabled)* This adds several new voice commands, to automate many of the features you'll be using frequently: *Open Map* and *Close Map*\ , *Call Horse*\ , *Spell Research*\ , *Drink Water* and *Fill Waterskin*\ , *Continuance* or *Get Status* (for general health and hunger/thirst/fatigue status), and *Sense Direction*. If you do not want this plugin, disable it in MO2.

* 
  **(VR) VRIK Controller Bindings** [\ `Nexus <https://www.nexusmods.com/skyrimspecialedition/mods/23416>`_\ ] *(Enabled)* These are recommended controller bindings to go along with VRIK. If you are using an Index, you will need the latest community bindings. Unfortunately, some in-game button prompts will not align with these bindings. If you do not want this plugin, disable it in MO2.

* 
  **(VR) Left-handed Settings** *(Disabled)* Self-explanatory. Make sure to also enable "Left-Handed Mode" in the in-game settings. If you are left-handed, enable this in MO2.

* 
  **(VR) Auto Sneak and Jump** [\ `Nexus <https://www.nexusmods.com/skyrimspecialedition/mods/23649>`_\ ] *(Disabled)* Automatic sneak and jump functionality for VR. You will need to edit the .ini file for the mod, please see the Nexus page for details.

UI Customization
""""""""""""""""

The UI and UX of your game is a very personal and subjective choice, so we've included a few options for you to choose from:


* 
  **Librum UI Customizer** *(Defaults to Magic Cards)* Right-clicking and selecting Reinstall Mod on the Librum UI Customizer will allow you to choose between several pre-installed fonts, compatibility patches/replacers, and UI/HUD Presets. When prompted by MO2, select **Replace Mod**. The fonts can be previewed `here <https://i.imgur.com/a/QhGuCU9>`_\ , as well as in the FOMOD installer. A massive thanks to all the authors who have given permission for us to include these!

* 
  **Librum ENB Selector** (Defaults to Ominous ENB) Right-clicking and selecting Reinstall Mod on the Librum ENB Selector will allow you to choose between several included ENB options with various quality presets. If playing Skyrim VR, we’ve also included some reshade options for better sharpening.

**\ *Please note that if you have your Wabbajack Downloads folder outside of the ``<Librum Install>/downloads`` path, you will need to go to your downloads folder, copy the Librum ENB Selector and Librum UI Customizer .7z files to your ``<Librum Install>/downloads`` folder before you can Reinstall them in MO2 and use the FOMOD.*\ **


* 
  **Undiscovered Means Unknown** *('GPS' disabled by default)* Right-clicking and selecting *Reinstall Mod* for Undiscovered Means Unknown in MO2 will allow you to restore the 'GPS' functionality that shows the player on your map. 

* 
  **Darker Night Sky** *(Enabled)* This is SGS's night sky texture, to go alongside the ENB preset we're using. It is a darker texture with reddish auroras, and it fits in very nicely with Librum's theme. If you do not use this, you will have the brighter and arguably prettier textures from `Ethereal Cosmos <https://www.nexusmods.com/skyrimspecialedition/mods/5728>`_. If you want Ethereal Cosmos textures instead, disable this in MO2.

* 
  **SkyUI The Adventurer Theme Mod SE** *(Enabled)* If you want a nicer cursor and Oblivion-style inventory icons, this is the plugin for you. If you do not want this plugin, disable it in MO2.

* 
  **Frenchsworn, Kitties Speak Spanish, Nords speak Deutsch, Italian for Tullius** *(Disabled)* These mods replace the voice and lip-syncing for the appropriate NPCs with alternate languages. Forsworn will speak French, Khajiit will speak Spanish, Nords (and some non-Nords) will speak German, and Imperials (not just Tullius) will speak Italian. Subtitles will remain in English, so make sure you have them turned on if you choose to use some or all of these optional mods!

Starting Librum
~~~~~~~~~~~~~~~

To start the game for real, start SKSE or "Play Librum" through Mod Organizer 2. This will be necessary every time you start the game; if you try to launch Skyrim through its default folder or through Steam, the game will be entirely vanilla.

Start a new game once you get to the main menu. You will start in the character creation area from `Nightmare of Lorkhan <https://www.nexusmods.com/skyrimspecialedition/mods/46649>`_. For more information on character creation, please read the `Strategy Guide <Strategy_Guide.md>`_ (but come back here after!).

If you want to read up on your character creation options, please see the `Character Creation <https://librum-modpack.com/?page_id=296>`_ page.

Configure the MCM
~~~~~~~~~~~~~~~~~

Once you have created your character, wait until all the messages in the top left of the screen stop appearing and click Yes/OK to all message pop-ups that appear, and then open up the in-game settings and navigate to the *Mod Configuration Menu* (MCM). You will need to make several changes here to adhere to the suggested Librum setup. Unfortunately, very few of the mods used in Librum support FISS, so you will need to do this each time you create a new character. 

**\ *If you are playing Librum with Skyrim VR, don't forget to follow the `VR Configuration <#VR-configuration>`_ section!*\ **

**f you don't want Survival Features:** 
You still need to active **Frostfall** and **SunHelm**\ , just deactivate them again after they've finished starting up. This is to avoid script bloat and is very important.

**If you are updating from Librum 2.0:** 
And wish to use the same save, we recommend that you open the **Traits for Skyrim** MCM, click **Uninstall**\ , and then re-select your traits with the new balanced costs and abilities by using the Medical History again.

**Base MCM Configuration for SE & VR**


#. **AGO** Disable "Arrow Wounds (Player)", "Arrow Wounds (NPC)", "Persistent Arrows" and *Optionally* "Arm Fatigue".
#. **Cobb Encumbrance.** In the *Presets* tab, apply the preset "Classic (SEM)".
#. **Follower Framework.** Under *System*\ , hit "Load from File". *Note:* Capslock is set to "Followers Attack" and Y is set to "Command Followers".
#. **Frostfall.** Enable it. Close the entire System Menu and wait for it to activate fully before moving on. Once it gives you the "fully loaded" message, re-open the MCM and ensure that it's set to "On Exposure: Death"
#. **Hunterborn**. Start the mod, close the MCM and once it has finished starting up reopen it head to *Profile* and select "Load Profile", and also disable the Hunterborn config power in the *Enable* tab.
#. **Lock Overhaul.** Activate the mod.
#. **PSDI Menu.** Confirm the mod is Activated. *Optional:* Set up a Hotkey to easily activate and deactivate the mod.
#. **SoT Sleeping Encounters.** Uncheck "Allow Drowsy Effect".
#. **Spell Research.** Import spells. It takes a bit to import everything, several pop ups will appear, hit Yes for all.
#. **SunHelm.** Activate the mod. Close the entire System Menu and wait for it to activate fully before moving on. *Note:* Cannibalism is enabled by default.
#. **Tentapalooza.** Change all settings to "Rain and Snow".
#. **Trade & Barter.** Under *Barter Rates*\ , set "Barter Presets" -> "Hardcore".
#. **True Armor.** Scroll all the way down to *Save & Load* and select Load Balanced Settings (it's on the right side).
#. **Vigor.** Start the mod.

**Special Edition MCMs**


#. **A Matter of Time** Head to *Presets*\ , and under *User Settings*\ , hit GO on Load user settings. *Note:* Not every UI option in the *Librum UI Customizer* has an AMOT preset. You'll have to customize the mod yourself for the ones that don't.

VR Configuration
----------------

If you're playing the VR edition of Librum, this section covers some important additional configuration, as well as suggesting some tweaks you will likely want to make to settings and for 3rd party tools.

(VR) MCMs
^^^^^^^^^


#. **Nemesis PCEA.** Activate both options.

**\ *Mod Configuration Spells*\ **


#. **VRIK.** This configuration spell is available in the *Powers* tab. Calibrate to headset height, and then to VR scale.

**\ *Optional Voice Command MCMs*\ **


#. **Hunterborn.** Set the "Sense Direction" hotkey to "x".
#. **Spell Research.** Set the "Spell Research" hotkey to "alt".
#. **SunHelm.** Set the "Continuance" hotkey to "y", and the "Drink Water/Fill Waterskin" hotkey to "l".

(VR) In-Game Settings
^^^^^^^^^^^^^^^^^^^^^

Note that Wabbajack will reset some of the in-game Skyrim VR settings, which you will want to fix before continuing.
Open the ``Main Menu -> Settings -> VR Performance``\ , and apply the following settings:


* Untick Dynamic Resolution
* Untick the two "Disable LOD" options
* Other options can be configured according to your hardware. In particular, note the "Actor Distance" slider -- keep this low or you will lag in towns and cities, even with the best CPU.

(VR) Natural Locomotion
^^^^^^^^^^^^^^^^^^^^^^^

If you don't plan on using Natural Locomotion, turn off "physical sneak".

This step is **\ *not mandatory*\ **\ , but it will significantly improve your VR experience. Download `Natural Locomotion <https://store.steampowered.com/app/798810/Natural_Locomotion/>`_ through Steam. It is an independent app, which allows you to walk around in VR games by swinging your arms (and possibly holding a hotkey). Although this sounds intrusive and unnatural, it quickly becomes a *very* natural way to move around Skyrim. As a bonus, it works for everything from Skyrim and Fallout 4 VR to *No Man's Sky*.

In terms of configuring NaLo, I recommend the following settings (although it is up to taste):

**\ *Common Settings:*\ **


* *Allow jumping while crouched* - off.
* *Enable strafing by tilting head* - on.
* *Sticky buttons* - off.

**\ *Edit Profile/Configure Buttons:*\ **


* Enable walking with one of the following two options:

  * *Hands down the hip (buttonless)*. This is newer, and may interrupt other actions, but feels more natural.
  * *Joystick touch* on right or left hand only, and *enable both hands with this button*. You will only move around when your thumb is on the joystick, but you do not need to hold any buttons down.

* *Enable jumping in place* - on, with button set to *right joystick up*. The "natural jumping" doesn't always trigger when you want it to.

**\ *Edit Profile/Configure Speed and Trackpad Emulation:*\ **


* *Original trackpad/joystick* - set to *combine with movement*.
* *Desired trackpad/joystick orientation* - set to *head relative*.

When you want to play, first load up NaLo and click "Start selected profile" on Skyrim VR, and then launch Skyrim normally (SKSE through MO2).

Congratulations! You've completed the Librum setup, and you are ready to play. The next several sections will explain what Librum is and does, as well as provide support.

Updating
--------

If Librum receives an update, please check the Changelog before doing anything. Always back up your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the updated modlist when updating!**

This means that any additional mods you have installed on top of Librum will be deleted. However, your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the *Overwrite existing modlist* button.
Note that some in-game settings will get reset when updating. Check them all again! Particularly, "dynamic resolution" and "disable lod" in the "VR Performance" settings menu. 

Strategy Guide
--------------

Although Librum gameplay is largely detailed below, I have included somewhat more detail in the (currently WIP) `Strategy Guide <Strategy_Guide.md>`_.

Features of Librum
------------------

Librum significantly affects nearly every aspect of gameplay; in this section, I explain all of the significant changes that have been made, and how they change the Skyrim experience. I will separate it here into various "modules" for ease of explanation -- however, this does not reflect any clean-cut separations of Librum mechanics. Changes from the various modules overlap, affect one another, and work together to create a consistent Librum experience. For instance, *Spell Research* forces mages to interact with the survival elements of Librum, and these survival elements turn a quest like *Clockwork* into a precarious and time-sensitive escape mission.

With this in mind, here is a rough breakdown of what Librum accomplishes.

General Philosophy
^^^^^^^^^^^^^^^^^^

With every change, Librum attempts to adhere to the points of its *core philosophy*\ :


#. Librum is a game about *being Dragonborn*. Your dragon soul is a fundamental part of your character's development, and there is no way to indefinitely avoid this destiny.
#. The world is static in ways that make sense, but dynamic in all others. The world is not centered around you, but it reacts realistically to the actions you take and the choices you make. In particular, the ways in which you interact with the world change as you become more powerful.
#. Magic in all forms is a dangerous, arcane, and powerful force. Magic can solve most any problem you have, but -- as an example -- acquiring a single Master-level spell might take a whole playthrough.

Character Creation
^^^^^^^^^^^^^^^^^^

Though they are expanded upon in more detail below, the following changes and mods are core to your character creation and are included here for ease of reference:


* **Races** - `Legacy <https://www.nexusmods.com/skyrimspecialedition/mods/36415>`_ not only significantly changes your race's abilities, but it also affects NPCs in the world. The race of a bandit you're fighting is no longer just a cosmetic distinction, but will significantly impact how you approach the fight. 
* **Standing Stones** - `Curse of the Firmament <https://www.nexusmods.com/skyrimspecialedition/mods/28419>`_ overhauls the familiar vanilla standing stone buffs into more interesting trade-offs and decisions. You cannot interact with Standing Stones out in the world anymore, so if you want to change your stone once you leave Nightmare of Lorkhan you must head to the Curse of the Firmament MCM page and change your Stone there. Standing Stone abilities have also been distributed to NPCs in the world, so much as with Legacy it's worth becoming familiar with these and considering how they will affect the way you fight.
* **Magicka** - Starts at 10. In the low magic setting of Librum, nobody is a mage at level 1 -- however, those who are prepared to invest the time and effort into their magical studies will be greatly rewarded. See the `Magic <#magic>`_ section for (much) more detail.  

Leveling and Skills
^^^^^^^^^^^^^^^^^^^

Librum makes several major changes to character progression, described by the following comparison table:

.. list-table::
   :header-rows: 1

   * - Vanilla Skyrim
     - Librum
   * - Character progression happens primarily as you level, and primarily through the allocation of perk points.
     - Character progression occurs through four unrelated aspects of your character: spell/equipment progression, character level, collected dragon souls, and the discovery of *Librum Antiquums* in various places around the world.
   * - Available equipment and enemies depend exclusively on your level.
     - Librum's loot distribution is based on `Morrowloot Ultimate <https://www.nexusmods.com/skyrimspecialedition/mods/3058>`_\ , so equipment and enemies (with the exception of dragons) are entirely unleveled.
   * - Higher level equipment can be made and improved at any time, mitigating any effect of leveled weapons and armor
     - Smithing now requires more knowledge than just a perk point; for instance, you need to acquire the _\ `Ancient Knowledge <http://en.uesp.net/wiki/Skyrim:Powers#Ancient_Knowledge>`_\ _ effect to make any Dwarven equipment, and Daedric smithing requires uncovering the secret of its construction. Improving equipment is no longer as effective.
   * - Available spell tomes depend exclusively on your skill level, but are readily available at spell merchants.
     - Spell tomes do not exist, by and large, with the exception of select hand-placed tomes. Rather, all spell progression is done through `Spell Research <https://www.nexusmods.com/skyrimspecialedition/mods/20983>`_.
   * - Perk points are gained when you level up.
     - You do not gain perk points through leveling. Using `Souls Do Things 2 <https://www.nexusmods.com/skyrimspecialedition/mods/33518>`_\ , you will have a power to convert one dragon soul to one perk point. Leveling will continue to grant you 10 Health, Magicka, or Stamina.
   * - Dragon souls are exclusively used to unlock dragon shouts.
     - Dragon souls have three purposes. They can be used to unlock shouts, they can be used to unlock perk points (as mentioned above), and finally, you will have passive buffs applied depending on the number of unspent souls in your collection.
   * - You can level up at any time by opening the Skills menu.
     - You must sleep for 8 hours in order to level up, in order to prevent level-ups in dangerous locations.
   * - Perks are typically straight buffs to your existing skills, and form the core part of your character's identity.
     - Librum uses `Vokrii <https://www.nexusmods.com/skyrimspecialedition/mods/26176>`_ to mix up perk benefits and to help balance around having only a small handful of perks; a single perk investment in any tree replaces vanilla's "20/40/60/80/100%" improvement perks or "Novice/Apprentice/Adept/Expert/Master" perks.
   * - Standing Stones provide moderate benefits to an existing character build, and can be changed at any time.
     - Standing Stones entirely change your character's make-up, thanks to `Curse of the Firmament <https://www.nexusmods.com/skyrimspecialedition/mods/28419>`_\ , but they can only be chosen during character creation.
   * - Your race typically gives you a once-a-day power, as well as some moderate resistances.
     - Through `Legacy <https://www.nexusmods.com/skyrimspecialedition/mods/36415>`_\ , your race confers significant passive abilities. These typically change gameplay drastically.
   * - You can open your map whenever you want.
     - Thanks to `Helps To Have A Map <https://www.nexusmods.com/skyrimspecialedition/mods/37238>`_ you must have a Map of [Location] equipped in your shield hand to open the map menu. Maps eventually break the more you use them, and if you take damage with your map equipped.


User Interface
^^^^^^^^^^^^^^

Librum makes a few changes to the default user interface, to (a) create a unique visual experience and (b) to improve the VR experience. For the first point, Librum uses `SkyUI <https://www.nexusmods.com/skyrimspecialedition/mods/12604>`_ along with the excellent `Dear Diary UI <https://www.nexusmods.com/skyrimspecialedition/mods/23010>`_ and pieces of the `Adventurer Theme Mod <https://www.nexusmods.com/skyrimspecialedition/mods/35568>`_ in order to blend a Skyrim-style modern UI with touches of a more Oblivion-style classic visual theme:


.. image:: Resources/UI.jpeg?raw=true
   :target: Resources/UI.jpeg?raw=true
   :alt: Alt text


We recognize that UIs, HUDs, Fonts and ENBs are all very personal and subjective choices, so as of 2.0 we've begun to look deeper at providing bundled options so you don't need to go rogue just to make things look the way you like! To start, we've provided a Font Selector to switch between several different options along with two different HUD presets. We hope to provide many more options to come in future releases.

VR Experience
^^^^^^^^^^^^^

Librum makes larger changes in terms of controls. For one, it includes `Dual Wield Block VR <https://www.nexusmods.com/skyrimspecialedition/mods/28456>`_\ , `Weapon Throw VR <https://www.nexusmods.com/skyrimspecialedition/mods/31374>`_\ , `Sprint Jump VR <https://www.nexusmods.com/skyrimspecialedition/mods/28354>`_\ , `VR Power Attack Fix <https://www.nexusmods.com/skyrimspecialedition/mods/28004>`_\ , `Haptic Skyrim VR <https://www.nexusmods.com/skyrimspecialedition/mods/20364>`_\ , and `Realistic Mining VR <https://www.nexusmods.com/skyrimspecialedition/mods/16692>`_ in order to better match player motions to character actions. With this suite of mods, VR combat is a much more natural experience, and you have all the options -- such as blocking with an off-hand weapon or throwing your weapon -- that you would expect. In particular, as we will further discuss in the next section, you can swing your pickaxe at *any* in-game rock (including, but not limited to standard ore veins) and swing your woodcutter's axe at (most) any in-game tree or wooden object to get the resources you expect.

A big change in this direction is `HIGGS VR <https://www.nexusmods.com/skyrimspecialedition/mods/43930>`_\ , which allows you to use your hands to truly interact with the world. You can pick up items naturally and turn them in your hand, throw them at NPCs, or put them over your shoulder to put them in your inventory. You can drag bodies around (finally) to hide your crimes from the law, or grab armor pieces directly off of corpses without entering a menu. Finally, you have gravity-glove-like abilities, as in *Half-Life: Alyx*.


.. image:: Resources/hands.jpg?raw=true
   :target: Resources/hands.jpg?raw=true
   :alt: Alt Text
 

In a similar vein, Librum includes `Dragonborn Speaks Naturally <https://www.nexusmods.com/skyrimspecialedition/mods/16514>`_ and `SkyVoice <https://www.nexusmods.com/skyrimspecialedition/mods/17840>`_ to have the world respond naturally to your voice. Namely, when you begin reciting a dialogue option, the game will select it for you, and when you say the words of a learned dragon shout, you will use that shout in game. Not to worry, of course -- thanks to `Shout Pronunciations <https://www.nexusmods.com/skyrimspecialedition/mods/18572>`_\ , the dragon language words of each shout will be shown in your shout menu.

Librum also includes `MageVR <https://www.nexusmods.com/skyrimspecialedition/mods/21297>`_\ , which generally overhauls the way you interact with spells and equipment. I recommend thoroughly reading its mod page for more information, but in short, it adds the following features:


#. Spells can be slotted to drawn "glyphs". You can re-draw the glyph later to either equip or auto-cast the slotted spell, all without entering your menu.
#. Archery is realistic. You will need to manually retrieve an arrow from your quiver in order to fire another shot.
#. You can quickslot shouts and powers, usable through a gesture and hotkey press.
#. You are able to "immersively" loot a container, in which you manually drag loot from the container to your backpack.
#. You are able to "immersively" lockpick, in a way resembling the real procedure for a tumbler lock.

Last but not least, Librum includes the fan-favorite `VRIK Player Avatar <https://www.nexusmods.com/skyrimspecialedition/mods/23416>`_\ , which allows you to see your character in-game. Not only that, but VRIK provides several visible weapon holsters around your body -- your calves, thighs, hips, forearms, upper arms, chest, stomach, and shoulders. To use these, hold your weapon over the appropriate holster (you should feel a haptic signal) and press "grip". Hold "grip" and pull away to unsheathe. VRIK also allows you to go into "selfie mode", by lifting your right hand above your head and rotating; you can finally see your VR character in his/her full glory!


.. image:: Resources/hands.png?raw=true
   :target: Resources/hands.png?raw=true
   :alt: Alt Text


Dynamic World
^^^^^^^^^^^^^

Continuing on with the theme of the last section, Librum includes a suite of mods designed to make static objects react to your actions. Along with the mods mentioned before, the key players here are `Dynamic Things <https://www.nexusmods.com/skyrimspecialedition/mods/19520>`_\ , `Dynamic Things Enhanced <https://www.nexusmods.com/skyrimspecialedition/mods/19521?tab=posts>`_\ , `Incognito <https://www.nexusmods.com/skyrimspecialedition/mods/20929>`_ and `Sneak Tools <https://www.nexusmods.com/skyrimspecialedition/mods/1863>`_ (which will come up again later).

The combined effects of these mods are as follows:


#. Any haypile or stack of wood you find in the game can be looted, and will decrease in size as you loot them.
#. Almost all "static" containers in Skyrim -- crates, barrels, and others -- can now be looted. They can also be destroyed with a woodcutter's axe, which will drop all of their contents and firewood.
#. Most rocks can be mined with a pickaxe, giving you Hearthfire resources.
#. Most trees can be cut down with any axe, giving you firewood and other resources. *(VR Note) You may need to power attack (hold the trigger) and reach "into" the tree with your axe.*
#. You can drink or bottle liquids from mead barrels and similar containers.
#. Using your weapons or Destruction magic on training dummies and archery targets will yield experience.
#. You can harvest mammoth tusks from mammoth skulls you find.
#. Most "standard" objects, like barrels, urns, and small furniture, will be destroyed if you hit them.
#. Changing your face at The Face Sculptor in the Ragged Flagon will remove all crime and bounties from you. You can also hide your identity with hoods, face masks, or the Gray Cowl of Nocturnal.
#. Light sources around Skyrim can be ignited and put out, either by standard fire/frost effects or by the fire/water arrows included in Sneak Tools.

Survival and Realism
^^^^^^^^^^^^^^^^^^^^

On the flip side, *you* have to appropriately react to Skyrim's environment. The core of this, of course, is `Campfire <https://www.nexusmods.com/skyrimspecialedition/mods/667>`_ and `Frostfall <https://www.nexusmods.com/skyrimspecialedition/mods/671>`_. Along with some more resource-adding mods (notably, `Tentapalooza <https://www.nexusmods.com/skyrimspecialedition/mods/652>`_\ ), these mods add a complete cold-weather survival system to Skyrim. Your character will be subject to Skyrim's harsh climate, and you will need to bundle up, set up camp frequently, and avoid frigid water and inclement weather in order to survive. Mages will have various options to escape the cold (all compatible with Librum's `Spell Research <https://www.nexusmods.com/skyrimspecialedition/mods/20983>`_ mechanics!): summoning cloaks or various tents and shelters, transmuting or summoning materials, summoning a Fire Atronach for heat, or teleporting to safety, among others. Finally, your character's survival skills will improve over time, unlocking various survival-themed perks available at a campfire.


.. image:: Resources/Campfire.jpg?raw=true
   :target: Resources/Campfire.jpg?raw=true
   :alt: Alt text


You will also need to keep track of your hunger, thirst, and fatigue, thanks to `SunHelm Survival and needs <https://www.nexusmods.com/skyrimspecialedition/mods/39414>`_. You will need to maintain a supply of water (or alcohol!) and fresh or salted food in order to survive. Thankfully, these resources can be obtained from many sources. You can get water from snowbanks, wells, rivers, or the ocean -- although it may have to be boiled for hygiene's sake -- and many NPCs are happy to share or sell water, if you ask nicely. Innkeepers will sell you bottles of water in their normal merchant menu, and refill your empty bottles and waterskin for a price. You can also add a hotkey in SunHelm's MCM to drink and fill your empty bottles at water sources.

Getting food is a more involved process, thanks to `Hunterborn <https://www.nexusmods.com/skyrimspecialedition/mods/7900>`_. When you hunt an animal, you now need to properly dress and skin the carcass, using a hunting knife. On the other hand, you will have access to many more resources when you harvest from an animal carcass: more kinds of meats and animal products, pelts from each animal, and animal bones. Your hunting, foraging, bone-carving, and cooking skills will improve with each use, improving your harvests and giving access to new recipes over time.

*Sleep* is also more complicated than it may seem. Although it is necessary both for general survival and to `level up <https://www.nexusmods.com/skyrimspecialedition/mods/32357>`_\ , it is fairly dangerous to fall asleep in Skyrim's wilderness or in its dungeons. Thanks to `Sands of Time Sleeping Encounters <https://www.nexusmods.com/skyrimspecialedition/mods/8257>`_\ , any time you fall asleep, you will have a location-dependent chance of being attacked during the night. This is particularly true in dungeons, making it imperative to either (a) quickly get to safety or (b) bring along a follower or lay traps.
Finally, through *Sunhelm*\ , diseases have become much more dangerous. Instead of applying a minor debuff to your stats, each disease will now progress through various stages, with many becoming deadly if left untreated. To avoid this all-new danger, you will need to take care to apply *Resist Disease* effects, properly prepare your foods and water, and try not to get bitten or scratched in fights with wild animals. If you *do* contract a disease, and it doesn't go away on its own, you will have to rest up, find an alchemical cure (unique to each disease), or pay through the nose for a priest to dispel your illness.

Combat and Enemies
^^^^^^^^^^^^^^^^^^

Librum uses a slew of mods to improve the combat experience overall, with a strong focus on making each fight (within reason) a dangerous and harrowing experience.

For general combat, Librum combines its many `new VR options <#user-interface-and-controls>`_ with `Blade and Blunt <https://www.nexusmods.com/skyrimspecialedition/mods/34549>`_\ , `Vigor - Enhanced Combat <https://www.nexusmods.com/skyrimspecialedition/mods/38075>`_\ , `Mortal Enemies <https://www.nexusmods.com/skyrimspecialedition/mods/4881>`_\ , `Skyrim Revamped - Complete Enemy Overhaul <https://www.nexusmods.com/skyrimspecialedition/mods/14598>`_\ , `Know Your Enemy <https://www.nexusmods.com/skyrimspecialedition/mods/13807>`_\ , and `Morrowloot Ultimate <https://www.nexusmods.com/skyrimspecialedition/mods/3058>`_. The former two mods add an element of dynamism to combat -- instead of standing and swinging your Touch controllers wildly (or spamming the LMB), you will need to duck, weave, and carefully time both your attacks and your blocks. Knowing when to press your advantage and attack when an enemy is staggered or off-balance will grant significant damage bonuses -- but these bonuses also apply to your opponents, so make every attack count and don't leave yourself vulnerable!

Managing your Stamina (and therefore carry weight, thanks to Cobb Encumbrance) is more important than ever, and you will be rewarded for learning how each weapon handles in terms of speed and reach. Blocking will consume stamina first (before overflowing into health) and may not always be the best option compared to dodging and positioning. Vigor also introduces the concept of "Poise" which is a hidden stat that's based off of your armor weight and stamina total. As you lose health your poise will decrease, and when it reaches 0 you'll be staggered and your Stamina reduced based on how far past 0 poise was surpassed. 

Know Your Enemy and Morrowloot Ultimate step in before you've even started a fight, with the latter deleveling all enemies, so you'll have to make sure you're properly prepared to be wherever you're going. The former drastically changes enemies' resistances and weaknesses, forcing you to plan in advance before a difficult fight. It adds a variety of traits to armor and creatures to provide different resistance levels to various attack types -- for example, arrows will be able to pierce through most light armors, but will be significantly weaker against metal/heavy armors. These changes combined with AI tweaks and minor mods (like `Multiple Floors Sandboxing <https://www.nexusmods.com/skyrimspecialedition/mods/4524>`_\ ) will make any fight a life-or-death experience that rewards careful planning and intelligence. There are no one-size-fits-all solutions to combat.

Potions are no longer instantaneous and spammable, instead drawing their effects out over 10 seconds. No longer can you pause the game seconds before a power attack hits you and spring back to full health to survive the hit! Potions have also been distributed to most NPCs and they will use them intelligently to restore their health/magicka/stamina, boost resistances and utilize invisibility.

Pay close attention to the passive bonuses given through `Legacy <https://www.nexusmods.com/skyrimspecialedition/mods/36415>`_ and remember that they *now apply to NPCs as well as the player*. NPCs have also had Standing Stone passives distributed to them through `Curse of the Firmament <https://www.nexusmods.com/skyrimspecialedition/mods/28419>`_\ , potentially creating some tricky and unpredictable combinations to overcome. If you're fighting an Orc and they suddenly burst into 'flames' and dramatically increase in power, that's Legacy at work.


.. image:: Resources/Trident.png?raw=true
   :target: Resources/Trident.png?raw=true
   :alt: Alt Text


Combining nicely with these AI and combat tweaks, Librum adds several new classes of weapons through `Heavy Armory <https://www.nexusmods.com/skyrimspecialedition/mods/6308>`_ and other, smaller weapon mods. You can now wield anything from spears and tridents to staves and clubs, and all of the new weapons control smoothly under VR. In particular, a spear will "feel" like a spear, instead of the slightly-more-awkward-sword it was consigned to being in 2D Skyrim. You can also throw any of these weapons, allowing you to finally play the javelineer you've dreamed of.

Special attention has been given to wild animals, combining `SkyTEST - Realistic Animals and Predators <https://www.nexusmods.com/skyrimspecialedition/mods/1104>`_ with `Savage Skyrim <https://www.nexusmods.com/skyrimspecialedition/mods/37768>`_. Animals will go about normal animal behaviors: hunting prey, running from predators or competing with other predators, raising cubs, and finding mates. Bears will hibernate in the winter, animals will search for food and water, and, importantly, they will not report your crimes. There will also be significantly more variety in different animals, with many animals now sporting different colorations:


.. image:: Resources/Wolves.jpeg?raw=true
   :target: Resources/Wolves.jpeg?raw=true
   :alt: Alt Text


Savage Skyrim goes one step further, however, combining the several graphical mods from Rougeshot over the years. Many enemies now have more unique, more characteristic, and (often) more terrifying body structures. Dragons and vampire lords have gotten larger wings; Dwemer constructs, spriggans, and spiders have become more imposing; and *many* other animals and creatures have undergone similar changes.

Of course, dragon combat still forms the foundation of Librum, and dragons are not excluded from our tweaks here. Firstly, there is now a *much* wider variety of dragon types available, thanks to `Splendor <https://www.nexusmods.com/skyrimspecialedition/mods/9670>`_ and `Diverse Dragons Collection <https://www.nexusmods.com/skyrimspecialedition/mods/695>`_. They have all each been given unique names through `Zim's Dragon Improvements <https://www.nexusmods.com/skyrimspecialedition/mods/38693>`_\ , and they all `talk to you <https://www.nexusmods.com/skyrimspecialedition/mods/26955>`_ during your fights. Along with changes to make dragon combat more difficult and dynamic, this combination turns each dragon fight into a unique boss fight, rather than another generic Skyrim opponent.


.. image:: Resources/Dragon.jpeg?raw=true
   :target: Resources/Dragon.jpeg?raw=true
   :alt: Alt Text


Finally, Librum turns Skyrim's half-baked sneaking mechanic into a stealth experience worthy of the *Thief* franchise. With the many thoroughly researched changes from `Realistic AI Detection <https://www.nexusmods.com/skyrimspecialedition/mods/2345>`_\ , you will now need to use darkness and silence to your advantage. Many dungeons have undergone `significant lighting improvements <https://www.nexusmods.com/skyrimspecialedition/mods/8586>`_\ , which you need to make use of as you sneak around enemies' now-more-realistic detection skills. Speaking of the *Thief* franchise, Librum adds many new tools of the trade to aspiring rogues, courtesy of `Sneak Tools <https://www.nexusmods.com/skyrimspecialedition/mods/1863>`_. You can now knock unsuspecting opponents out with your bare hands or a blackjack, ignite and extinguish light sources with fire/frost magic or fire/water arrows, and better navigate your environment with rope arrows. You can also set things ablaze after hitting them with oil arrows, fool opponents with noisemaker arrows, and conceal your identity with various masks and hoods (a la Grey Cowl of Nocturnal). 

Magic
^^^^^

When you start Librum, you need to change your fundamental expectations of what being a mage looks like in Skyrim. Though the magic of Librum can be described as **\ *low magic*\ **\ , it is equally apt to call it **\ *deep magic*\ **. As you'll see below, the systems surrounding magic have been expanded upon greatly to introduce new schools and nuance to the casting of spells. Not only that, the process of *becoming* a mage isn't assumed to have happened sometime before level 1, but rather will be a core focus of your playthrough should you intend to take up the esoteric arts. No longer will you be shooting flames from your hands from the moment you step into the world, instead you'll be hitting the books (or paper rolls, in this case) to study magical artifacts and painstakingly research your spells. Did I mention you start with 10 Magicka? Better bring some bodyguards along!

The process for obtaining new spells adheres to the `Spell Research <https://www.nexusmods.com/skyrimspecialedition/mods/20983>`_ format. In short, **\ *spell tomes no longer exist*\ **\ , by and large, with the exception of certain hand-placed tomes. This means that you will need to *research* to discover each new spell, in one of three general fashions:


#. *Researching existing spells*. Using your research journal, you can spend time studying any spell already in your possession, in order to increase your knowledge of the spell's various archetypes. For instance, studying *Lesser Ward* would improve your knowledge of Restoration magic, of shielding spells, of "magical force" inducing spells, of self-targeting spells, and of concentration spells. This is slow, but a very straightforward method of progression for existing mages.
#. *Distilling and studying alchemical ingredients*. Using an alembic or a cauldron, you can distill alchemy ingredients into concentrated serums, which you can then (a) use for interesting crafting recipes or (b) study to improve your knowledge of their effects. This is relatively fast, but expensive and terribly confusing.
#. *Beating the shit out of valuable artifacts*. Along your adventures, you will come across all manner of new magical artifacts, ranging from the relatively commonplace enchanted weapon fragments to the dangerous and rare *Grimoires*. By studying magical items, translating old tomes, or destroying all of these artifacts, you can learn a huge amount about various spell archetypes, or even gain new spells automatically. However, these methods can be finnicky and dangerous, and they may harm you more than they help.

Once you've learned enough about the spell archetypes you're interested in, you can attempt to write "magical theses" and apply them towards gaining a new spell. If you are skillful, lucky, and not mentally drained, you may discover a new spell that fits the archetypes of the theses you wrote.

Now, there are several important gameplay consequences of this system. Existing mages will have an easier time learning new spells than new apprentices -- if you don't have any spells to start with (which may well be the case), you must study alchemical ingredients or artifacts in order to improve. Furthermore, as spell tomes are largely unavailable, you will have to make do with lower level magic than is otherwise the case; learning your first *Adept* or *Expert* spell, for instance, is a very difficult process.

On the other hand, Librum adds many new spells and classes of magic, organized loosely around the `Mysticism <https://www.nexusmods.com/skyrimspecialedition/mods/27839>`_ framework. Mysticism itself rebalances all of the vanilla spells, and it adds a wide swath of new spells corresponding to those of "legacy" Elder Scrolls games. The list below gives some examples, but is *noncomprehensive*\ :


* **\ *Open X Lock.*\ ** Instantly open any lock of the corresponding level.
* **\ *Mark and Recall.*\ ** Set a location with *Mark*\ , and instantly teleport there with *Recall*.
* **\ *Absorb Health.*\ ** Drain a target's health pool, and restore your own the same amount.
* **\ *Weakness to X.*\ ** Inflict a target with weakness to a given spell type.
* **\ *Reflect Damage.*\ ** For X seconds, a percentage of received melee damage is reflected back at your attacker.
* **\ *Command.*\ ** For X seconds, targets up to a given level are placed under your control.
* **\ *Slow Time.*\ ** For X seconds, the caster's perception of time is slowed by a given percentage.

Mysticism makes these effects -- and many more -- available in a number of different formats. This pairs particularly nicely with Spell Research, because each spell type is available in a variety of archetypes, and so the spells you discover are truly unique to your character. For instance, each elemental effect is now available in cloak, bolt, "stream", on-touch, wall, and rune formats, each at several different magic levels. This means that, where vanilla only had the novice "Flames" spell in the stream format, Mysticism gives the novice "Flames", the adept "Greater Flames", and the (very well-animated) master "Flames of Oblivion" spells.

In addition, unique spells from previous games make a comeback. These range from Destruction spells like "Finger of the Mountain" and the fan-favorite "Enemies Explode" to unique Conjuration spells, allowing you to summon any type of weapon as well as various types of Dremora, Skeletons, and other creatures. Notably, through `Magistrate Levitate <https://www.nexusmods.com/skyrimspecialedition/mods/24695>`_\ , Morrowind-style levitation has also been reintroduced to the game.


.. image:: Resources/Shield.jpeg?raw=true
   :target: Resources/Shield.jpeg?raw=true
   :alt: Alt Text


This is just the core of Librum's magic offerings, however. Through the addition of several curated spell packs, Librum opens up many more-specific branches of magic:


* **\ *Earth, Wind, and ~Fire~ Water Magic.*\ ** Cast the same Mysticism-style destruction spells for the elements of earth, wind, water, and poison, thanks to `Elemental Destruction Magic <https://www.nexusmods.com/skyrimspecialedition/mods/440>`_. Certain enemies will resist or be weak to these elements, and Vokrii perks have been changed to reflect these new additions. You can also summon earth, wind, and water atronachs, in the same style as the vanilla elements, and you can apply enchantments that make use of these new elements.
* **\ *Shadow Magic.*\ ** Teleport through shadows, cloak areas in darkness or reveal important items in existing darkness, and draw power from the shadows around you, with `Triumvirate's <https://www.nexusmods.com/skyrimspecialedition/mods/39170>`_ expansive Shadow magic options.
* **\ *Blood Magic.*\ ** Use your health in place of your Magicka to cast spells, with `Ace Blood Magic <https://www.nexusmods.com/skyrimspecialedition/mods/16995>`_. You can also manipulate blood in the environment, with bleeding effects, blood-mists that can infect opponents, and defensive orbs or pools of blood.
* **\ *Nature Magic.*\ ** Follow the path of the druid, using nature-themed spell schools from Triumvirate and `Forgotten Magic Redone <https://www.nexusmods.com/skyrimspecialedition/mods/12711>`_. Draw power or healing from the environment, infect your target with damaging spores or poisons, or grow various damaging brambles, vines, or mushrooms around your opponent. You can also call unique animals to aid you in combat, or take the form of these animals to gain unique abilities.
* **\ *Expanded Fire/Frost/Shock Magic.*\ ** Use Forgotten Magic Redone's heavily expanded elemental options to add new combat mechanics to your Destruction mage. Teleport around the battlefield through shock gates, surround yourself with a glacial fortress or freeze would-be attackers solid, or drop meteors on distant opponents. 
* **\ *Holy Magic.*\ ** Call upon the Divines to aid you in your quest, using spells from `Dawnguard Arsenal <https://www.nexusmods.com/skyrimspecialedition/mods/25094>`_ as well as Triumvirate and Forgotten Magic Redone. Sun spells have been expanded to match the other elements, but you can also bless your weapons in combat, protect and buff nearby allies, or summon divine weapons or guardians to fight on your behalf.
* **\ *Shaman Magic.*\ ** Triumvirate offers something for the follower of the ancient Nordic pantheon, as well. Summon Nordic totems to heal you or damage your opponents, consecrate your surroundings to gain an easily-accessible sanctuary, or look upon the land from the eye of a bird. 
* **\ *Celestial Magic.*\ ** Applying the two spell schools from *Cosmic Spells*\ , you can unlock the powers of the Magna-Ge. Teleport targets through wormholes or draw them with gravitational force toward a summoned body, place "Umbral Orbs" or "Luminous Crescents" around the battlefield to extend your cosmic powers, or deal *lunar* or *void* damage to your opponents. 
* **\ *Daedric Magic.*\ ** Through Triumvirate, Forgotten Magic Redone, and `Zim's Dremora Improvements <https://www.nexusmods.com/skyrimspecialedition/mods/12128>`_\ , unlock the magic of the Daedra. Cast the same (now heavily-expanded) fire-based protection and Destruction spells as Dremora, summon all manner of new Daedra, or banish targets to Oblivion. You can also apply a whole selection of new curses, or bind enemy spirits into your summons for stronger effects. 

In addition to the above list, Librum includes a ton of new "miscellaneous" spells -- for instance, from `Tentapalooza <https://www.nexusmods.com/skyrimspecialedition/mods/652>`_\ , `Caranthir Tower Reborn <https://www.nexusmods.com/skyrimspecialedition/mods/4269>`_ or `Immersive College of Winterhold <https://www.nexusmods.com/skyrimspecialedition/mods/17004>`_\ , or from any of Librum's many quest mods -- that do not fit neatly into these categories. It also includes mods like `Thunderchild <https://www.nexusmods.com/skyrimspecialedition/mods/1460>`_\ , `Summermyst <https://www.nexusmods.com/skyrimspecialedition/mods/6285>`_\ , and `Complete Alchemy and Crafting Overhaul <https://www.nexusmods.com/skyrimspecialedition/mods/19924>`_\ , which, along with some of the mods from Librum's other "modules", allow for mage-tangent playstyles utilizing enchantments, alchemy, or shouts primarily.

Note that almost all of the above spells must be discovered on your own, through Spell Research. Because of this, you will naturally tend toward a specific magical niche (which may not align at all with the spell "classes" listed above), dependent on your experience in the different magic archetypes. In this fashion, Librum turns Skyrim's vanilla "eat a book" magic system into a truly immersive research experience; you will be able to discover nearly any sort of magic you can imagine, but you need to dedicate yourself to studying the secrets of magic.

When it comes to actually *casting* spells, Librum also adds a new element of challenge in the form of `FIZZLE <https://www.nexusmods.com/skyrimspecialedition/mods/18180>`_. If your magic skill isn't high enough to comfortably cast a certain spell, there is a chance that it will fail on the spot (but still drain your Magicka!). This is affected by other environmental factors, forcing mages to adapt appropriately to Skyrim's harsh climate; for instance, if you are suffering from frostbite, your magic skills will be significantly reduced, and most of your spells will fail. 

Even after all this effort to acquire materials and research a spell, it will be very weak to begin -- as you cast them and begin to specialize in schools of magic, you will organically grow more powerful thanks to `Better Magic Progression <https://www.nexusmods.com/skyrimspecialedition/mods/16269>`_ allowing your abilities to develop through use. 

When it comes to Enchanting your own magical items of power, the list includes `Enchanting Awakened <https://www.nexusmods.com/skyrimspecialedition/mods/18558>`_ to further provide avenues of specialization and complexity to the experience. There are now three schools of Enchantment: **\ *Aether*\ **\ , **\ *Chaos*\ ** and **\ *Corpus*\ **\ , and a fledgling enchanter must choose which path they will go down carefully as they are mutually exclusive. Soul Trapping has become a more central focus to the life of an enchanter, with the vast majority of soul gems in the world now coming unfilled. Several additional tweaks have been made to enchantments themselves, and if you wish to produce powerful items you will need to invest valuable perks in your chosen specialization.

Leveling and Encounter Zones
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

In regards to world-leveling mechanics, Librum primarily takes inspiration from D&D and similar tabletop games. The core point here is, the type of adventure you go on changes as you become more and more powerful -- while you may just be hunting wildlife at low levels, you progress to the point where you can go into certain dungeons and abandoned forts, and next to the point where you can handle more fantastical opponents: for instance, automata, undead, or otherworldly beings. After that point, the player starts doing really crazy stuff: going to planes of Oblivion, traveling outside of Skyrim, and truly saving the world. The world is largely *entirely unleveled*\ , so be prepared to run away a lot at the start of your journey!

The Dragonborn Story
^^^^^^^^^^^^^^^^^^^^

Librum is designed around your character being the legendary Dovahkiin. However, the vanilla experience didn't fit our vision for what it means to be Dragonborn, and what the The Dragonborn's story holds. To handle this, we have `Dragon souls are free <https://www.nexusmods.com/skyrimspecialedition/mods/46794/>`_ and `True Teacher Durnehviir <https://www.nexusmods.com/skyrimspecialedition/mods/44969>`_.

Quests and Adventures
^^^^^^^^^^^^^^^^^^^^^

For all its strengths, Skyrim never got the questing aspect quite right. The game's many questlines are fairly straightforward and predictable, and most of its dungeons are as well. Librum only touches the worst offenders among Skyrim's vanilla quests, but it adds a great deal of new content to experience. Putting together dozens of curated quest and adventure mods, Librum's new content totals to hundreds of new quests and new areas to explore, including more questlines than are in the vanilla game, and several extensive dungeon systems and expansive new lands. In compiling these mods, there were a few specific requirements I upheld (excluding many otherwise fantastic mods, unfortunately):


#. Every line of dialogue is voiced, and always of high quality.
#. Every addition is lore-friendly, at least within the limits of artistic license.
#. Every addition is balanced (within reason), interesting, and natural within the existing game world.


.. image:: Resources/molag.jpg?raw=true
   :target: Resources/molag.jpg?raw=true
   :alt: Alt Text


With that in mind, here are the major new quest mods included in Librum:


#. **\ *\ `Legacy of the Dragonborn <https://www.nexusmods.com/skyrimspecialedition/mods/11802>`_.*\ ** Legacy of the Dragonborn is, without a doubt, the largest museum curator simulator available for Skyrim.  Legacy adds a large museum -- the *Dragonborn Gallery* -- to Solitude, in which you can store and display nearly any artifact from your collection (including those from the following mods). Not only that, Legacy adds a ton of new artifacts hidden around Skyrim, and it comes complete with a new *archaeology guild* and an expansive questline. Though it is hard to explain here, Legacy typically becomes the center of any playthrough that involves it.
#. **\ *\ `Beyond Skyrim: Bruma <https://www.nexusmods.com/skyrimspecialedition/mods/10917>`_.*\ ** The first release of the ambitious and far-reaching *Beyond Skyrim* project, Bruma allows you to explore the titular region in the north of Cyrodiil, which you may remember from *The Elder Scrolls IV: Oblivion*. Bruma is feature-complete, with a collection of excellent quests, locations, and characters; top-notch voice-acting; and a level of polish matching Bethesda's own.
#. **\ *\ `Vigilant <https://www.nexusmods.com/skyrimspecialedition/mods/11849>`_.*\ ** Join forces with the Vigilant of Stendarr, to face a growing threat from the *Harvester of Souls* himself, Molag Bal. Vigilant features a huge, branching main quest, steeped in the darker sides of Elder Scrolls lore, with many secrets to uncover and difficult choices to make.
#. **\ *\ `Project AHO <https://www.nexusmods.com/skyrimspecialedition/mods/15996>`_.*\ ** Working with (or against!) the hidden Telvanni outpost of Sadrith Kegran, discover one of the best-kept secrets of Dwarven invention. Project AHO offers a beautifully-rendered DLC-sized area to explore, as well as a branching main quest and many Dwemeri secrets to unlock.
#. **\ *\ `Carved Brink <https://www.nexusmods.com/skyrimspecialedition/mods/24351>`_.*\ ** From the makers of Project AHO, Carved Brink offers a look at two new planes of Oblivion: Peryite's *Pits* and the all-new *Faceted Stones*. Explore the excellent world design of the *Haem Projects* team through two main questlines, using puzzle-solving and new forms of transportation to traverse these otherwise un-transversable alien landscapes.
#. **\ *\ `Clockwork <https://www.nexusmods.com/skyrimspecialedition/mods/4155>`_.*\ ** Clockwork offers a fully-featured player home -- the Chlodovech family's *Clockwork Castle*\ , high in the Velothi mountains. Though it has not been touched in two centuries, you may lay claim to it as soon as you arrive. However, once in, the castle's inhabitants may not let you leave. Uncover the secrets of the castle's founding, and of its mysterious inhabitants, through a fleshed-out and horror-themed questline.
#. **\ *\ `Moon and Star <https://www.nexusmods.com/skyrimspecialedition/mods/4301>`_.*\ ** Explore the quaint Dunmeri village of *Little Vivec*\ , floating in the center of Lake Ilinalta. Though charged with protecting Little Vivec from a dangerous criminal, you may find that Little Vivec and its inhabitants are hiding more than it seems.
#. **\ *\ `The Tools of Kagrenac <https://www.nexusmods.com/skyrimspecialedition/mods/14168>`_.*\ ** The Tools of Kagrenac completes the story of Arniel Gane and the legendary dagger Keening; what happened to weaken Keening so thoroughly, and where are the remaining tools of the Dwemer smith Kagrenac? Delve through sprawling new dungeons and face challenging new obstacles, in order to uncover these secrets and claim the most legendary Dwarven artifacts for yourself.
#. **\ *\ `The Forgotten City <https://www.nexusmods.com/skyrimspecialedition/mods/1179>`_.*\ ** The only mod so far to win a National Writers' Guild award, The Forgotten City offers a unique and enthralling mystery, set in its titular city in the far reaches of Skyrim. Investigate the inhabitants of the Forgotten City, solve intricate new puzzles, and travel through time to uncover a murder plot and escape back to the surface.
#. **\ *\ `Moonpath to Elsweyr <https://www.nexusmods.com/skyrimspecialedition/mods/4341>`_.*\ ** One of the great classics of Skyrim modding, but remastered for a modern experience, Moonpath to Elsweyr brings you south to the heart of the Khajiiti homeland in order to recover the legendary *Staff of Indarys*. Along the way, explore the alien jungles of Elsweyr, join forces with the Khajiiti rebellion, and gain access to the airship *Dev Aveza*.
#. **\ *\ `The Wheels of Lull <https://www.nexusmods.com/skyrimspecialedition/mods/748>`_.*\ ** Return to Sotha Sil's mysterious clockwork city, and take a trip through the stranger side of Elder Scrolls lore. Along the way, solve new puzzles and tread through Zelda-esque dungeons, unlock the fantastical weapons and equipment of Sotha Sil's Chronographers, and explore alien landscapes, all in the labyrinthian expanse of Sotha Sil.
#. **\ *\ `Teldryn Serious <https://www.nexusmods.com/skyrimspecialedition/mods/5541>`_.*\ ** Teldryn Serious heavily expands the backstory of the mercenary Teldryn Sero, taking you around Solstheim once more in order to uncover a dangerous plot and defend Raven Rock.
#. **\ *\ `Helgen Reborn <https://www.nexusmods.com/skyrimspecialedition/mods/5673>`_.*\ ** A classic among Skyrim mods, Helgen Reborn gives you an opportunity to rebuild and revive the town of Helgen. Uncover a Thalmor plot, recruit and train your town guard, and participate in a ~bewildering and not-very-apropos~ secret fighting ring to reclaim the town and its legacy.
#. **\ *\ `Wyrmstooth <https://www.nexusmods.com/skyrimspecialedition/mods/45565>`_.*\ ** Now that it's back and purged of bugs, Wyrmstooth allows you to travel to the island of *Wyrmstooth*\ , north of Solitude, to rid the island of its dragon menace.
#. **\ *\ `Midwood Isle <https://www.nexusmods.com/skyrimspecialedition/mods/28120>`_. New as of 2.0.*\ ** A large new land with plenty of exciting features to explore, including a player home, two new shouts and eight spells. 
#. **\ *\ `The Notice Board <https://www.nexusmods.com/skyrimspecialedition/mods/3218>`_.*\ ** The Notice Board overhauls radiant questing in Skyrim. In short, it adds two notice boards outside each major inn in Skyrim, which detail (a) miscellaneous quests you can undergo and (b) goings-on in the area.


.. image:: Resources/sotha.jpg?raw=true
   :target: Resources/sotha.jpg?raw=true
   :alt: Alt Text


On top of these new quests and dungeons, Librum makes *tons* of improvements to vanilla quests and questlines:


#. **\ *\ `Civil War Overhaul <https://www.nexusmods.com/skyrimspecialedition/mods/37906>`_.*\ ** Finally, the civil war is hard to ignore. CWO restores all of the cut civil war battles Bethesda had planned, as well as improving the scope and AI of these battles, adding random sieges, and generally totally rewriting the civil war. Importantly, joining one side will cause the hold guards of the other to be hostile towards you.
#. **\ *\ `Cutting Room Floor <https://www.nexusmods.com/skyrimspecialedition/mods/276>`_.*\ ** Less a quest mod than an overall content-restoration project, CRF reintroduces several cut locations and towns, small or miscellaneous quests, and general improvements to vanilla quests.
#. **\ *\ `The Choice Is Yours <https://www.nexusmods.com/skyrimspecialedition/mods/3850>`_.*\ ** Most quests now have an opt-out option, in case you *don't* actually want to go beat a priest to death three times in an obviously-haunted house.
#. **\ *\ `Even Better Quest Objectives <https://www.nexusmods.com/skyrimspecialedition/mods/159>`_.*\ ** Vanilla Skyrim relies entirely on its map markers to get you places. In fact, they go so far as to *not provide enough information* to do any quests without blindly following the map markers. EBQO fixes this, by providing Morrowind-level (except actually correct) descriptions of your quest objectives.
#. **\ *\ `Finding Derkeethus <https://www.nexusmods.com/skyrimspecialedition/mods/19550>`_.*\ ** Loosely an addon to EBQO, *Finding Derkeethus* fixes several conceptual problems with the quest to rescue Derkeethus from Darkwater Pass. Now the quest is completable without using the UESP.
#. **\ *\ `Somebody Else's Problem <https://www.nexusmods.com/skyrimspecialedition/mods/43850>`_.*\ ** When Eltrys tells you to meet him to discuss the Forsworn Conspiracy, you can now tell him where to shove it.
#. **\ *\ `Finding Helgi and Laelette <https://www.nexusmods.com/skyrimspecialedition/mods/28973>`_.*\ ** This mod fixes what would havebeen an interesting investigative mission. You can now truly investigate the burnt house, for instance, and the quest involves more questioning and dialogue with NPCs.
#. **\ *\ `Better College Application <https://www.nexusmods.com/skyrimspecialedition/mods/5272>`_.*\ ** When Faralda asks you why you want to enter the college, your response now actually determines the spell you're tested on. This is critical for Librum's spell system, because it gives you a headstart in whatever school you want to focus on.
#. **\ *\ `Save the Icerunner <https://www.nexusmods.com/skyrimspecialedition/mods/34681>`_.*\ ** This fits into the general TCIY framework -- if you don't want to brutally murder a ship full of people, now you don't have to.
#. **\ *\ `Chill Out Aela <https://www.nexusmods.com/skyrimspecialedition/mods/31949>`_.*\ ** When Aela asks you why you didn't help fight the giant, you now have a third option to choose from (instead of just "Screw you!" and "I'm just a wimp!").
#. **\ *\ `Not So Fast - Main Quest <https://www.nexusmods.com/skyrimspecialedition/mods/2475>`_.*\ ** You've got no idea how often this mod's features are reported as bugs. In short, NSFMQ changes a number of the narrative beats of the main quest. The dragon sighting is no longer immediately after you recover the Dragonstone, Delphine no longer steals the Horn of Jurgen Windcaller, and Season Unending can largely be skipped.
#. **\ *\ `End Times <https://www.nexusmods.com/skyrimspecialedition/mods/39201>`_ (optional).*\ ** To double down on the NSFMQ pacing, you now need to kill Alduin within a set amount of time, or he will literally eat the world (and your game will be over). Good luck.


.. image:: Resources/Alduin.jpeg?raw=true
   :target: Resources/Alduin.jpeg?raw=true
   :alt: Alt Text


Now, one of my all-time favorite Elder Scrolls experiences is Daggerfall's dungeon delving. Despite the numerous inaccessible areas and inescapable portal networks, there was something distinctly adventurous, epic, and psychologically rewarding about making your way through one of the game's gargantuan dungeons. Librum attempts to recreate this feeling with its own suite of dungeon mods. Together, the following mods fill Skyrim (and Solstheim, and other game areas) with a healthy number of new caverns, ruins, and more -- ranging from slightly-more-involved-than-vanilla to Daggerfall-style labyrinthine dungeons.


#. **\ *\ `Skyrim Underground <https://www.nexusmods.com/skyrimspecialedition/mods/131>`_.*\ ** Skyrim Underground adds a *gigantic* network of dungeons below Skyrim's surface. You can now travel from Solitude to Riften on foot, for instance, though you'll have to uncover secret passages and face many new and powerful opponents to do so. Fit for its scope, it also adds many secrets to discover, from ancient artifacts to undead merchants and impromptu underground settlements. *Skyrim Underground has been patched to be more lore-friendly, but I will continue this work in future versions*.
#. **\ *\ `Forgotten Dungeons <https://www.nexusmods.com/skyrimspecialedition/mods/449>`_.*\ ** Forgotten Dungeons adds many (dare-I-say) Daggerfall-style dungeons to the Skyrim and Solstheim landscapes. They can be explored independently, for their own prizes, but many have also been enabled for Skyrim's radiant quest system. *I have renamed many of the dungeons in Forgotten Dungeons, to better fit Skyrim's theme*.
#. **\ *\ `Hammet's Dungeon Pack <https://www.nexusmods.com/skyrimspecialedition/mods/12186>`_ and `Hammet's Dungeons - More Rewards <https://www.nexusmods.com/skyrimspecialedition/mods/23455>`_. New as of 2.0.*\ **
#. **\ *\ `EasierRider's Dungeon Pack <https://www.nexusmods.com/skyrimspecialedition/mods/23455>`_. New as of 2.0.*\ ** 
#. **\ *\ `Land of Vominheim <https://www.nexusmods.com/skyrimspecialedition/mods/31472>`_. New as of 2.0.*\ ** With several islands to explore as well as plenty of dungeons and caves, you'll find yourself immersed in Vominheim as you're led primarily with written notes.
#. **\ *\ `Darkend <https://www.nexusmods.com/skyrimspecialedition/mods/10423>`_. New as of 2.0.*\ ** Expect to see beautiful environments and architecture, as well as terrifying foes that test your skills. 
#. **\ *\ `Konahrik's Accoutrements <https://www.nexusmods.com/skyrimspecialedition/mods/22206>`_.*\ ** This mod adds a great deal of new content surrounding Skyrim's Dragon Priests. Use the forgotten field of Abjuration magic to collect and cleanse the Dragon Priests' powerful new relics, and go back in time to explore the lost Dragon Priest temple of Revakheim.
#. **\ *\ `Skyrim Sewers <https://www.nexusmods.com/skyrimspecialedition/mods/9320>`_.*\ ** Skyrim Sewers adds sewer systems below Windhelm, Solitude, and Whiterun (and a few forts), bringing back the age-old Elder Scrolls experience of murdering rats, discovering secrets, and getting lost in the sewers.
#. **\ *\ `The Lost Wonders of Mzark <https://www.nexusmods.com/skyrimspecialedition/mods/40674>`_.*\ ** Far beyond Skyrim's northern border, the great Dwemer lord Mzark left his final projects and greatest artifacts -- but also his most clever traps and puzzles.
#. **\ *\ `Bleak Falls Barrow Revisited <https://www.nexusmods.com/skyrimspecialedition/mods/33251>`_.*\ ** Bleak Falls Barrow has been redone and significantly expanded, turning it from a cookie-cutter linear Skyrim dungeon into a mysterious and labyrinthine dungeon worthy of its in-game reputation.


.. image:: Resources/map.jpg?raw=true
   :target: Resources/map.jpg?raw=true
   :alt: Alt Text


Followers
^^^^^^^^^

Librum adds several *follower* mods, to make the game world a little less lonely. Though some of these mods add quests, their primary role within Librum is to allow you to (a) connect with your followers as real people and (b) effectively run a party-style playthrough. Think *Fallout: New Vegas* or *Dragon Age*\ , but in Skyrim. Librum is designed with followers in mind. Gather your party and venture forth!


#. **\ *\ `Nether's Follower Framework <https://www.nexusmods.com/skyrimspecialedition/mods/18076>`_. New as of 2.0.*\ ** As our follower framework.
#. **\ *\ `Interesting NPCs <https://www.nexusmods.com/skyrimspecialedition/mods/29194>`_.*\ ** Interesting NPCs adds a ton of new quests, matching even Bruma for size. It also adds, of course, *interesting NPCs*\ , breathing new life into many of Skyrim's familiar locations. In particular, some of the new NPCs are "super followers", meaning that they comment on your quests, choices, and locations, and they generally behave like real people. An interesting aspect of Interesting NPCs is, many of the new quests and questlines tie several NPCs together -- this gives the game more of a "Dragon Age" feel, in terms of how characters are relatable and recurrent in your adventures.
#. **\ *\ `Interesting Follower Requirements for 3DNPC (Soft Requirements) NPCs <https://www.nexusmods.com/skyrimspecialedition/mods/45646>`_. New as of 2.0.*\ ** This mod adds requirements to various Followers that must be met before you can recruit them to join your party. For example, Hjoromir may be clueless and inexperienced, but he's savvy enough not to follow someone *completely* inexperienced as he is. You will now need to be at least Level 5 to recruit him to join you.
#. **\ *\ `Inigo <https://www.nexusmods.com/skyrimspecialedition/mods/1461>`_.*\ ** Inigo is Skyrim's most popular follower mod, for good reason. Not only is he an effective combatant and willing to roll with whatever moral code you're comfortable with, Inigo is as close to a real companion as any Skyrim follower has come. Importantly, he responds dynamically to most situations, and he talks naturally with you and with other NPCs. Inigo can talk dynamically with vanilla and Interesting NPCs followers.
#. **\ *\ `Lucien <https://www.nexusmods.com/skyrimspecialedition/mods/20035>`_.*\ ** Lucien has all the benefits of Inigo, but instead of a burglarizing cat-man, he is a scholar from the Arcane University. Lucien can talk dynamically with Inigo, as well as with vanilla and Interesting NPCs followers.
#. **\ *\ `Song of the Green <https://www.nexusmods.com/skyrimspecialedition/mods/11278>`_.*\ ** Song of the Green adds the excellent follower Auri, who is a female Bosmer from Valenwood. Although she does not have as much dialogue as the above followers, this reflects her character naturally. Further, she can talk dynamically with Lucien, as well as with vanilla and Interesting NPCs followers.
#. **\ *\ `Hoth <https://www.nexusmods.com/skyrimspecialedition/mods/16137>`_.*\ ** One of the most visually unique follower mods available, Hoth is a grizzled bounty hunter and a new sort of companion to your character. Uniquely, he can provide bounty quests radiantly, dependent on your current area. He can talk dynamically with Auri.
#. **\ *\ `Special Edition Followers <https://www.nexusmods.com/skyrimspecialedition/mods/7622>`_. New as of 2.0.*\ **
#. **\ *\ `Serana Dialogue Edit <https://www.nexusmods.com/skyrimspecialedition/mods/16222>`_ and `Serana Dialogue Addon <https://www.nexusmods.com/skyrimspecialedition/mods/32161>`_.*\ ** Together, these mods turn Dawnguard's beloved vampire follower into the sort of "super follower" introduced by the above mods. She is now aware of most quests and situations you find yourself in, and she speaks naturally with you and with others.
#. **\ *\ `Useful Dogs <https://www.nexusmods.com/skyrimspecialedition/mods/1666>`_.*\ ** Although a minor addition relative to the follower mods above, Useful Dogs allows you to give commands to your canine companion. You can send them looking for food, weapons, ammunition, keys, and more, in the style of Fallout 3 and 4.
#. **\ *\ `Meeko Reborn <https://www.nexusmods.com/skyrimspecialedition/mods/17572>`_ and `Vigilance Reborn <https://www.nexusmods.com/skyrimspecialedition/mods/17571>`_. New as of 2.0.*\ ** Giving some extra love to two of the most loyal of companions.

Graphics and Ambience
^^^^^^^^^^^^^^^^^^^^^

Last but not least, Librum includes a full graphical makeover of Skyrim. The goal is to match the photorealism we are used to these days, but with a bend towards realizing Librum's dark, gritty, and foreboding nature in Skyrim's atmosphere.Perhaps most important for this end, Librum includes a suite of literal atmosphere mods, centered around a Frankenstein-ing of `Obsidian Weathers <https://www.nexusmods.com/skyrimspecialedition/mods/12125>`_ and `True Storms <https://www.nexusmods.com/skyrimspecialedition/mods/2472>`_\ :


.. image:: Resources/rain.jpg?raw=true
   :target: Resources/rain.jpg?raw=true
   :alt: Alt Text


We top this off with several lighting mods:


* **\ *\ `Relighting Skyrim <https://www.nexusmods.com/skyrimspecialedition/mods/8586>`_.*\ ** This mod changes the position and characteristics of existing light sources in dungeons, to match where light should actually be emitted. It sounds like a simple change, but it makes a huge atmospheric difference, and it's critical to being able to sneak around.
* **\ *\ `Enhanced Lighting for ENB <https://www.nexusmods.com/skyrimspecialedition/mods/1377>`_.*\ ** This is our "general purpose" lighting overhaul, and it makes a *big* difference. In short, it makes light sources look much nicer and more natural, with a side effect of making dungeons and nights very dark.
* **\ *\ `Ominous ENB <https://www.nexusmods.com/skyrimspecialedition/mods/27333>`_.*\ ** Ominous ENB gives a grim, atmospheric look to Skyrim, without sacrificing framerate. It is the core of Librum's graphics overhaul. 

  * *Please note there is a known issue with Ominous ENB that causes many hands and arms to look pale. Unfortunately we can't change this, so if it bothers you we recommend finding an ENB that meets your visual standards.*

The above only gives a small taste of the various atmosphere and ambience mods included in Librum -- you can visit the manifest for a complete list, but Librum includes everything from `new dust effects <https://www.nexusmods.com/skyrimspecialedition/mods/2407>`_ to `better cloud textures <https://www.nexusmods.com/skyrimspecialedition/mods/2393>`_ and even `better sound dynamics <https://www.nexusmods.com/skyrimspecialedition/mods/701>`_.


.. image:: Resources/lights.png?raw=true
   :target: Resources/lights.png?raw=true
   :alt: Alt Text


As we have become accustomed to, Librum also overhauls everything graphical about Skyrim, its world, and its inhabitants. Although I will not cover every detail of this graphical redux (see the manifest for a complete list), I will touch on some of the points that add to Librum's unique, gritty feel.

First of all, as mentioned earlier in the `Combat and Enemies <#combat-and-enemies>`_ section, Librum uses `Savage Skyrim <https://www.nexusmods.com/skyrimspecialedition/mods/37768>`_ (along with several texture-enhancing mods) to redesign many of Skyrim's creatures. Some, like Spriggans, Seekers, and Lurkers, have been made significantly creepier and more imposing, befitting their supernatural nature. Ice Wraiths have been made more serpent-like, Netches have been given longer tentacles, and Rieklings have been made larger and more muscular. Hardy animals, from mammoths to horkers, have been made to look hardier; more slender animals, such as wolves and skeevers, have been made to look hungrier, more vicious, and wild-eyed. Dragons, vampire lords, and gargoyles have been given larger wings, Dwemer automata have been given better and scarier-looking proportions, and the new insects have been called "pure nightmare fuel".


.. image:: Resources/treedude.jpg?raw=true
   :target: Resources/treedude.jpg?raw=true
   :alt: Alt Text


Another interesting addition to Librum comes in the form of `Frozen Electrocuted Combustion <https://www.nexusmods.com/skyrimspecialedition/mods/3532>`_. This mod adds bodily repurcussions to magic and elemental effects of all kinds. Fire may burn an opponent's skin right off, or just leave a nasty scar. Shock can cause spasms, or many worse effects. Frost can freeze an opponent solid -- striking a frozen foe will break them into several pieces. Effects have been added to everything from Fear to Soul Trap, so see the mod page for more information. In general, these new effects make the battlefield a grisly sight, and they make you think twice before zapping a fellow human person with *Lightning Storm*.


.. image:: Resources/oof.png?raw=true
   :target: Resources/oof.png?raw=true
   :alt: Alt Text


Finally, one of my major goals of Librum was to make the existing Skyrim content feel new and different. As such, Librum completely redoes every town and city in Skyrim, from large-scale architecture and layout changes to a re-imagining of citizens' AI, all towards the end of making Skyrim a natural-but-exciting place to be.

On the town-and-city level, Librum combines the `Great City series <https://www.nexusmods.com/skyrimspecialedition/mods/20272>`_ (except for Winterhold, for compatibility) with `Dawn of Skyrim <https://www.nexusmods.com/skyrimspecialedition/mods/9074>`_ and Cities of the North: `Dawnstar <https://www.nexusmods.com/skyrimspecialedition/mods/28952>`_\ , `Winterhold <https://www.nexusmods.com/skyrimspecialedition/mods/40088>`_\ , and `Morthal <https://www.nexusmods.com/skyrimspecialedition/mods/34168>`_. It also includes the minor mods in the Great City series: `Solitude (docks) <https://www.nexusmods.com/skyrimspecialedition/mods/22243>`_\ , `Karthwasten <https://www.nexusmods.com/skyrimspecialedition/mods/33032>`_\ , `Old Hroldan <https://www.nexusmods.com/skyrimspecialedition/mods/33189>`_\ , `Ivarstead <https://www.nexusmods.com/skyrimspecialedition/mods/34505>`_\ , `Shor's Stone <https://www.nexusmods.com/skyrimspecialedition/mods/35977>`_\ , `Mixwater Mill <https://www.nexusmods.com/skyrimspecialedition/mods/36350>`_\ , and `Kynesgrove <https://www.nexusmods.com/skyrimspecialedition/mods/42639>`_. We also have `Kato's Riverwood <https://www.nexusmods.com/skyrimspecialedition/mods/7031>`_\ , and `Rorikstead Basalt Cliffs <https://www.nexusmods.com/skyrimspecialedition/mods/25718>`_. For Solstheim, I have included `Better Tel Mithryn <https://www.nexusmods.com/skyrimspecialedition/mods/643>`_ and `Quaint Raven Rock <https://www.nexusmods.com/skyrimspecialedition/mods/20851>`_.

Not only do these city improvements make the cities denser, livelier, and more realistic -- they also give each city, town, and hamlet its own unique character. Instead of the "see one, see them all" nature of the towns in vanilla Skyrim, each of Skyrim's villages has its own architectural style, its own industry, and its own landscape.


.. image:: Resources/karthwasten.jpg?raw=true
   :target: Resources/karthwasten.jpg?raw=true
   :alt: Alt Text


Importantly, Librum also includes the changes from `Open Cities <https://www.nexusmods.com/skyrimspecialedition/mods/281>`_\ , allowing you to seamlessly transition from a city interior to the world of Skyrim. This pairs nicely with mods like `Sneak Tools <https://www.nexusmods.com/skyrimspecialedition/mods/1863>`_ and `Magistrate Levitate <https://www.nexusmods.com/skyrimspecialedition/mods/24695>`_\ , which allow you to climb over or float above city walls, respectively.

These architectural changes are matched with AI improvements for the citizens of Skyrim. Using `AI Overhaul <https://www.nexusmods.com/skyrimspecialedition/mods/21654>`_\ , Librum makes townspeople act like real townspeople. People will spend the day hunting, farming, traveling, shopping, or cooking (or whatever else they want to do), depending on their profession and the circumstances. Friends and family may gather at the local tavern or for shared meals, for instance. People will more realistically mourn the loss of a friend or loved one. They'll pray at temples associated to their faith. They may even act realistically during combat (and sometimes run away). Of course, the AI effects of the above mods are magnified by `Realistic Conversations <https://www.nexusmods.com/skyrimspecialedition/mods/1717>`_\ , `Relationship Dialogue Overhaul <https://www.nexusmods.com/skyrimspecialedition/mods/1187>`_\ , and `Guard Dialogue Overhaul <https://www.nexusmods.com/skyrimspecialedition/mods/20791>`_\ , which make normal citizens and guards not sound like robots or maniacs.

Librum overhauls specific buildings, as well, with `Palaces and Castles Enhanced <https://www.nexusmods.com/skyrimspecialedition/mods/1819>`_\ , `Distinct Interiors <https://www.nexusmods.com/skyrimspecialedition/mods/6130>`_\ , `Immersive College of Winterhold <https://www.nexusmods.com/skyrimspecialedition/mods/17004>`_\ , and `Immersive Fort Dawnguard <https://www.nexusmods.com/skyrimspecialedition/mods/40436>`_. Overall, these mods give a more hand-crafted feel to the world of Skyrim; many of Skyrim's interiors have been totally redesigned, with hand-placed objects, furniture, and lighting, and with elements unique to their location or purpose. Stores will now have goods on display, for instance, and inns and other regional establishments will be decorated according to their respective regions.


.. image:: Resources/stendarr.jpg?raw=true
   :target: Resources/stendarr.jpg?raw=true
   :alt: Alt Text


Last but not least, Skyrim's wilderness has also seen some improvements. Along with the hundreds of new dungeons and locations mentioned in the preceding section, several existing locations have been redone. For one, `Nordic Ruins of Skyrim <https://www.nexusmods.com/skyrimspecialedition/mods/20382>`_ improves the exteriors of several key ruins around Skyrim: Forelhost, High Gate Ruins, Korvanjund, Labyrinthian, Ragnvald, Rannveig's Fast, Saarthal, Valthume, and Volskygge. These legendary ruins now *look* legendary, and they can all be seen as such from a great distance. The same has been done for Dwemer ruins, using `Better Dwemer Exteriors <https://www.nexusmods.com/skyrimspecialedition/mods/27618>`_ -- as with the new Nordic ruins, these now have greatly expanded (and much more imposing) exteriors.

Librum also includes `Man Those Borders <https://www.nexusmods.com/skyrimspecialedition/mods/681>`_\ , `Unique Border Gates <https://www.nexusmods.com/skyrimspecialedition/mods/4819>`_\ , `Hold Border Banners <https://www.nexusmods.com/skyrimspecialedition/mods/1737>`_\ , and `Immersive Dawnguard Dayspring Pass <https://www.nexusmods.com/skyrimspecialedition/mods/4126>`_\ , to make the transitions between different holds and the journeys through wilderness zones a little more unique. Guards will now be stationed where they ought to be, and each hold can be identified by its flags and architectural styles upon arrival. Also, the entrance to the Dawnguards' territory is no longer a stupid piece-of-shit hole in a cliff wall.


.. image:: Resources/whiterun.jpg?raw=true
   :target: Resources/whiterun.jpg?raw=true
   :alt: Alt Text


Frequently Asked Questions
--------------------------

For an updated list of FAQs, please see the Librum Discord server:

`\ :raw-html-m2r:`<img src="Resources/discord.PNG" width="300">` <https://discord.gg/3f8vPYFmJX>`_

Credits and Thanks
------------------

First of all, I couldn't have done it without the Librum team: *Algeddon*\ , *Mashtyx*\ , *NemeanLion*\ , *Capell* and *Snidely*. They have been a huge part of this process, both creatively and in developing the modlist and its associated resources.

Of course, I can only take a small slice of the credit for this modlist. I've spent the past several months compiling, reviewing, and properly patching together all of these mods, but the mod authors themselves did most of the work. If you particularly like a certain quest, location, or gameplay mechanic, please go thank the mod authors!

Contact
-------

For any questions, comments, or suggestions, please join my modding Discord server:

`\ :raw-html-m2r:`<img src="Resources/discord.PNG" width="300">` <https://discord.gg/3f8vPYFmJX>`_
