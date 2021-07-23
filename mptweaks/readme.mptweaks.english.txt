-------------------------------------------------
---            Multiplayer Tweaks             ---
---               for IE Games                ---
-------------------------------------------------


------------------------------------------------------------------------
GENERAL
------------------------------------------------------------------------
This mod is compatible with all IE games except the first component cannot be installed on IWD2.

The MPTweaks mod fixes a couple of issues in multiplayer sessions.

------------------------------------------------------------------------
DESCRIPTION
------------------------------------------------------------------------

------------------------------------------------------------------------
Take it outside
------------------------------------------------------------------------
Up to 5 mobs in combat might follow a group member outside through a door.  
This is a one-way trip only and is dependent upon timing so it may take more than one attempt to lure them out.
The script is only applied to indoor areas whose travel regions are usable by NPCs.

------------------------------------------------------------------------
Pause game when NPCs turn hostile during dialogue
------------------------------------------------------------------------
The pause is not instant.
There has to be a period of time between the dialogue ending and the game being paused when in multiplayer.
The script waits the shortest amount of time possible before pausing the game.
The functionality is tied to the player's AI.  If AI is turned off, the game won't pause.

------------------------------------------------------------------------
COMPATABIITY NOTES
------------------------------------------------------------------------
There are no known compatibility issues at this time

------------------------------------------------------------------------
INSTALLATION
------------------------------------------------------------------------
Installation using Project Infinity (https://forums.beamdog.com/discussion/74335/project-infinity-mod-manager-for-baldurs-gate-icewind-dale-planescape-torment-and-eet) will ensure this and other mods are installed in the correct order. Generally though, the mod should be installed after all dialogue and areas have been added and can safely be added after EET_end.

NOTE: If you've previously installed the mod, remove it before extracting a new version. To do this, uninstall all previously installed components and delete the mod folder and executables. 

When installing or uninstalling, do not close the DOS window by clicking on the X button! Instead, press the Enter key when instructed to do so.

General (Windows, Mac OS X, and Linux)

Extract the contents of the mod archive to your game's main directory. 

Windows
On successful extraction, there should be a mptweaks folder and a setup-mptweaks.exe file in your game folder. To install, simply double-click setup-mptweaks.exe and follow the instructions on screen.
Run setup-mptweaks.exe in your game folder to reinstall, uninstall or otherwise change components.

Mac OS X
The mod is packaged and installed with WeiDU. To install, extract the mod archive, then copy of the contents of the folder into your game folder (the folder which contains the CHITIN.KEY file). If properly extracted, you should have an "mptweaks" folder, setup-mptweaks, and setup-mptweaks.command in your game folder. To install, simply double-click setup-mptweaks.command and follow the instructions on screen.

Linux
Extract the contents of the mod to the folder of the game you wish to modify. Download the latest version of WeiDU for Linux from https://github.com/WeiDUorg/weidu/releases and copy WeiDU and WeInstall to /usr/bin. Following that, open a terminal and cd to your EET installation directory, run 'tolower' and answer Y to both queries. You can avoid running the second option (linux.ini) if you've already run it once in the same directory. If you're unsure, running tolower and choosing both options is the safest bet.
Run WeInstall mptweaks in your game folder to install the mod. Then run wine BGMain.exe and start playing. 

If you have installation problems or encounter any bugs, please post your bug report in the forum thread: https://www.gibberlings3.net/forums/topic/32809-multiplayer-tweaks-fixes-for-multiplayer-sessions/

------------------------------------------------------------------------
CREDITS
------------------------------------------------------------------------
* BeamDog / Overhaul Games: for the Infinity Engine and inspiring this mod
* K4thos: for EET - even though it's not required for this mod, I just really like EET
* DavidW: for his guidance on encapsulation and immutability
* Bubb and CamDawg - LOVE YOU FOREVER!!!  I mean it.  Forevah!
* Bubb for discovering the reason why mobs don't normally follow through exits in a multiplayer session
^ CamDawg for his help with INNER_ACTION and SOURCE_RES
* jastey: for everything you've done and continue to do. :)
* Grammarsalad: for idea for allowing a spell to override mobs ability to pass
* lynx: for help with using LastTrigger
* kjeron: for help with long area names 
* The folks at The Gibberlings Three forums: for never failing to answer my many many questions

------------------------------------------------------------------------
USED TOOLS AND RESSOURCES
------------------------------------------------------------------------
The Multiplayer Tweaks mod was created using the resources provided by the IESDP (https://gibberlings3.github.io/iesdp/index.htm) and with the following software:

* Near Infinity			https://github.com/Argent77/NearInfinity/releases/latest
* WeiDU					http://www.weidu.org

Modding communities, tutorials and technical assistance:

The Gibberlings Three	http://gibberlings3.net

------------------------------------------------------------------------
HISTORY
------------------------------------------------------------------------
* v1 - initial public release
* v1.1 - simplification of region script, bug fix for long area names and added a variable check before allowing the transfer
* v2 - implemented Designated tags in the TP2 file and added a new component (Pause game when NPCs turn hostile during dialogue)

------------------------------------------------------------------------
LEGAL INFORMATION
------------------------------------------------------------------------
This mod is copyright (c) Lauriel.

Multiplayer Tweaks is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards. Portions of the materials used are property of Wizards of the Coast. ©Wizards of the Coast LLC.

This mod is also not developed, supported, or endorsed by BioWare, Black Isle Studios, Interplay Entertainment Corp., Overhaul Games or Beamdog. All other trademarks and copyrights are property of their respective owners.

