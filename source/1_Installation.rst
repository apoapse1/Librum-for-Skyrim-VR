Installation
============
Video Tutorial
--------------

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/ZcN0fZG4_hI" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
    </div>

\_

Text Guide
----------
Librum is relatively lightweight, with most of the graphical draw coming from the ENB you select. Your mileage will certainly vary -- I can only provide my own specs, but I imagine you will find good performance on a weaker system.

**Space Requirements.** Librum requires 38 GB of space for its downloads, and 70 GB of space for the installation. In total, you will need 118 GB free on your computer.

**Recommended Specs.** This was the machine I compiled Librum on. I get a very smooth 40 FPS, which gives quite smooth gameplay along with Oculus/SteamVR motion smoothing.


* **CPU**\ : Intel Core i7-7700HQ, 4 cores at 2.80 GHz.
* **GPU**\ : NVIDIA GeForce GTX 1060, 6 GB of VRAM
* **RAM**\ : 16 GB DDR4

Librum makes use of the excellent `Wabbajack <https://www.wabbajack.org/#/>`_ program to make its installation as fast and painless as possible. That said, there are a few, very easy steps involved in setting up Librum. We will go over each in detail, but they are summarized as follows:


#. Clean your Skyrim folder and disable the Steam overlay.
#. Load Skyrim, let it set your graphics, open it to main menu, then close it.
#. Install the Wabbajack desktop client from `here <https://github.com/wabbajack-tools/wabbajack/releases>`_.
#. Navigate to Librum under the *Browse for Modlists* tab.
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


* **Disable the Steam Overlay** - The Steam Overlay can cause issues with ENB and is recommended to be turned off. Open the Properties window (right click the game in your ``Library -> Properties``\ ), navigate to the *General* tab and un-tick the *Enable the Steam Overlay while in-game* checkbox.

* **Set the Game language to English** - Librum is entirely in English, as many excellent mods are English-exclusive. This may change in the future, but for now, I highly recommend playing the game in English. Open the Steam Properties window, navigate to the *Language* tab and select *English* from the dropdown menu.

* **Clean Skyrim** - If your Skyrim VR or SE installation is not newly installed, I recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the ``Skyrim VR`` or ``Skyrim SE`` folder in ``Documents/My Games/`` by deleting the contents in it. 

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

#. (Option 1) Open Wabbajack, browse for the modlist in the Wabbajack client, and click to download it.
#. (Option 2) Download the Librum SE or VR file from the main page on `our website <https://librum-modpack.com>` , and open it up in the "Install From Disk" option in the Wabbajack client. Do not place the .wabbajack file in the folder you want to install Librum to.
#. Once the download is complete, set the installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, or Desktop. Put it somewhere easy like ``C:/Modlists/Librum``\ ). The downloads path should automatically fill in the installation path, but this can be changed if needed. 
#. Click the Go/Begin button.
#. Wait for Wabbajack to finish.
#. If you run into any issues, see the next section. If the installation is successful, proceed to `Post-Installation <#post-installation>`_.

Problems with Wabbajack
"""""""""""""""""""""""

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off, so you lose no progress.


* 
  **Could not download X.** If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update Librum.

* 
  **X is not a whitelisted download.** This can happen when I update the modlist. Check if a new update is available and wait if there is none.

* 
  **Wabbajack could not find my game folder.** Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the `Pre-Installation <#pre-installation>`_ step and ensure you've started up Skyrim once before you open Wabbajack.exe so the scan can locate your installation.

* 
  **Windows is reporting that a virus has been detected.** Windows 10 has started to auto-quarantine the ``usvfs_proxy_x86.exe`` file from the latest version of Mod Organizer 2, saying a threat has been detected. This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for Windows Defender can be found `here <https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan>`_.

* 
  **Cyclic Redundancy Check error during installation** This could be several things, but the first thing we would recommend is confirming that Wabbajack is not installed in your Documents, Downloads or Program Files folders, then delete the contents of ``%APPDATA%/Local/Wabbajack`` and re-open the app and try again. If this does not resolve the problem, it could be related to drive corruption and you should run CHKDSK on the drive in question.

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

**Please note that if you have your Wabbajack Downloads folder outside of the** ``<Librum Install>/downloads`` **path, you will need to go to your downloads folder, copy the Librum ENB Selector and Librum UI Customizer .7z files to your** ``<Librum Install>/downloads`` **folder before you can Reinstall them in MO2 and use the FOMOD.**

**Alternatively, you can change the Librum Mod Organizer 2 Downloads directory by clicking the "Configure settings and workarounds" button in Mod Organizer 2 (it looks like a screw and wrench crossed over eachother) and changing the Downloads directory to whatever you selected when installing Librum in Wabbajack.**


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

**If you are playing Librum with Skyrim VR, don't forget to follow the** `VR Configuration <#VR-configuration>`_ **section!**

**If you don't want Survival Features:** 
You still need to active **Frostfall** and **SunHelm**\ , just deactivate them again after they've finished starting up. This is to avoid script bloat and is very important.

**If you are updating from Librum 2.0:** 
And wish to use the same save, we recommend that you open the **Traits for Skyrim** MCM, click **Uninstall**\ , and then re-select your traits with the new balanced costs and abilities by using the Medical History again.

**Base MCM Configuration for SE & VR**

#. **Follower Framework.** Under *System*\ , hit "Load from File". *Note:* Capslock is set to "Followers Attack" and Y is set to "Command Followers".
#. **Frostfall.** Enable it. Close the entire System Menu and wait for it to activate fully before moving on. 
#. **Hunterborn**. Start the mod, close the MCM and once it has finished starting up reopen it head to *Profile* and select "Load Profile".
#. **Lock Overhaul.** Activate the mod.
#. **PSDI Menu.** Make sure the mod is Active. *Optional:* Set a Hotkey.
#. **SoT Sleeping Encounters.** Uncheck "Allow Drowsy Effect".
#. **Spell Research.** Import spells. It takes a bit to import everything, but you will get a popup once it's all done.
#. **SunHelm.** Activate the mod. Close the entire System Menu and wait for it to activate fully before moving on.
#. **Trade & Barter.** Under *Barter Rates*\ , set "Barter Presets" -> "Hardcore".
#. **True Armor.** Scroll all the way down to *Save & Load* and select Load Balanced Settings (it's on the right side).
#. **Vigor.** Start the mod.

**Special Edition MCMs**


#. **A Matter of Time** Head to *Presets*\ , and under *User Settings*\ , hit GO on Load user settings. *Note:* Not every UI option in the *Librum UI Customizer* has an AMOT preset. You'll have to customize the mod yourself for the ones that don't.

VR Configuration
^^^^^^^^^^^^^^^^

If you're playing the VR edition of Librum, this section covers some important additional configuration, as well as suggesting some tweaks you will likely want to make to settings and for 3rd party tools.

(VR) MCMs
~~~~~~~~~


#. **Nemesis PCEA.** Activate both options.

**Mod Configuration Spells**


#. **VRIK.** This configuration spell is available in the *Powers* tab. Calibrate to headset height, and then to VR scale.

**Optional Voice Command MCMs**


#. **Hunterborn.** Set the "Sense Direction" hotkey to "x".
#. **Spell Research.** Set the "Spell Research" hotkey to "alt".
#. **SunHelm.** Set the "Continuance" hotkey to "y", and the "Drink Water/Fill Waterskin" hotkey to "l".

(VR) In-Game Settings
~~~~~~~~~~~~~~~~~~~~~

Note that Wabbajack will reset some of the in-game Skyrim VR settings, which you will want to fix before continuing.
Open the ``Main Menu -> Settings -> VR Performance``\ , and apply the following settings:


* Untick Dynamic Resolution
* Untick the two "Disable LOD" options
* Other options can be configured according to your hardware. In particular, note the "Actor Distance" slider -- keep this low or you will lag in towns and cities, even with the best CPU.

(VR) Natural Locomotion
~~~~~~~~~~~~~~~~~~~~~~~

If you don't plan on using Natural Locomotion, turn off "physical sneak".

This step is **not mandatory**\ , but it will significantly improve your VR experience. Download `Natural Locomotion <https://store.steampowered.com/app/798810/Natural_Locomotion/>`_ through Steam. It is an independent app, which allows you to walk around in VR games by swinging your arms (and possibly holding a hotkey). Although this sounds intrusive and unnatural, it quickly becomes a *very* natural way to move around Skyrim. As a bonus, it works for everything from Skyrim and Fallout 4 VR to *No Man's Sky*.

In terms of configuring NaLo, I recommend the following settings (although it is up to taste):

**Common Settings:**


* *Allow jumping while crouched* - off.
* *Enable strafing by tilting head* - on.
* *Sticky buttons* - off.

**Edit Profile/Configure Buttons:**


* Enable walking with one of the following two options:

  * *Hands down the hip (buttonless)*. This is newer, and may interrupt other actions, but feels more natural.
  * *Joystick touch* on right or left hand only, and *enable both hands with this button*. You will only move around when your thumb is on the joystick, but you do not need to hold any buttons down.

* *Enable jumping in place* - on, with button set to *right joystick up*. The "natural jumping" doesn't always trigger when you want it to.

**Edit Profile/Configure Speed and Trackpad Emulation:**


* *Original trackpad/joystick* - set to *combine with movement*.
* *Desired trackpad/joystick orientation* - set to *head relative*.

When you want to play, first load up NaLo and click "Start selected profile" on Skyrim VR, and then launch Skyrim normally (SKSE through MO2).

Congratulations! You've completed the Librum setup, and you are ready to play. The next several sections will explain what Librum is and does, as well as provide support.

Updating
^^^^^^^^

If Librum receives an update, please check the Changelog before doing anything. Always back up your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the updated modlist when updating!**

This means that any additional mods you have installed on top of Librum will be deleted. However, your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the *Overwrite existing modlist* button.
Note that some in-game settings will get reset when updating. Check them all again! Particularly, "dynamic resolution" and "disable lod" in the "VR Performance" settings menu. 
