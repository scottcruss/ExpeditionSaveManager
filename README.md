# 10/22/26 - Regarding the new Peak co-op update:

*Timeout (pause) appears to work perfectly!

*Expedition Save Manager issues:
1. Restoring from the Airport does not work at this time.
2. Starting a new game to biome Shore and then loading a saved file appears to work for post update saves. Not all Biomes tested yet.
3. Starting a new game to biome Shore and loading old saved files unknown at this time.
4. New saves work.
5. Working on fixes.

***

***
<img width="50%" alt="Image" src="https://github.com/user-attachments/assets/8a2117ad-5238-4abd-ab38-332612facba5" />

<p>

  
# ExpeditionSaveManager
<img width="200" align="left" alt="Image" src="https://github.com/user-attachments/assets/c8f1c4bf-2850-4f89-aca2-ddf0176ad851" />

Peak mod Expedition Save Manager and Timeout (Multiplayer Pause): 

Multiplayer load and save from any location! Complete state including player inventory and all world items saved and restored. Expeditions of saved files are grouped together to allow multiple Expeditions with different players on different days! 

Now includes a Timeout feature! (aka Multiplayer Pause)
</p>
<br clear="all">









***




***

***




***

***




***
# Expeditions Listing
<img width="800" alt="Image" src="https://github.com/user-attachments/assets/8f3bd59a-2489-4f5c-bad6-5785f150fe0a" />

A new Expedition is created automatically when the first save occurs upon hosting a new game. All new saves will be saved to the Expedition when an Expedition is loaded or created. A new Expedition can be created at any time by starting a new game at the Kiosk from the Airport.

<img width="48" align="left" alt="Image" src="https://github.com/user-attachments/assets/6487da04-7e4f-4e69-b524-3074fe3106db" />
Right clicking an Expedition or clicking purple crayon allows adding a note to an Expedition.
<br clear="left" />


<img width="48" align="left" alt="Image" src="https://github.com/user-attachments/assets/43f8bab2-30ed-4c1f-8972-027b777d6dad" />
Clicking the Trashcan on the left deletes the entire Expedition including all saved files for that Expedition.
<br clear="left" />


***

# Saved Games

<img width="800" alt="Image" src="https://github.com/user-attachments/assets/4188f57a-1377-47de-b4dc-d7c54e0f99b7" />

Loading from Airport performs a full reset and load, including luggage, Altair, etc. Loading from in game performs an incredibly fast reload but luggage does not reset. 

New Return to Airport button to take all players back to Airport for a full reset and load.

New Correction feature button allows correcting game items offset that can occur on only older versions of Peak saves after a major Peak update. aka Apples or Coconuts floating in the air. When enabled this will fix all out of alignment objects. It does not impact new saved files. Correction should not need to be disabled at any time but added as a safe guard. It does not slow down the loading of saved games. This should allow pre update saves to continue to work until the peak is reached!

Autosave option and configurable interval. On by default for new installs. Incredibly fast!
Configurable from the Settings option in the mod or from BepInEx/config/com.scr.peakexpeditionsavemanager.cfg

Save files are saved in the folder: PeakTSaves in the Peak folder. 
Configurable from BepInEx/config/com.scr.peakexpeditionsavemanager.cfg.
All save files are stored in json.

***

# Timeout (aka Multiplayer Pause)

<img width="800" alt="Image" src="https://github.com/user-attachments/assets/903fb0e2-213a-4110-a573-7eac1ec4cd7a" />

NEW Timeout feature added! (Pause)
Since pausing is not possible in multiplayer mode without all the players having the mod, added a Timeout feature like a pause. All players temporary transported and restricted to the prior campfire. Fog, Time, hunger, Day/Night clocks are all suspended during Timeout. When Timeout is ended, players are restored to prior location, state and environment is reset back to prior state. 

New feature: Host controls blocking accessing items at Campfire during Timeout.

***
Known issues:  
Open luggage and Scout Statue states only reset after restarting from the Airport. Placed items like ropes, chains, shelf fungus, etc are not removed between fast loading saved files unless starting from the Airport. 

Loading a Citadel biome while in the Void does not restore correctly. Going back to Airport first is required.

If a player or backpack glitches occur, clicking 4 for backpack can reset player or loading the same saved game a 2nd time should correct issues.
A complete scene state only resets after going back to the Airport.

There are 2 loading methods. Fast Load and Kiosk. Kiosk mode is only functional at this time since Peak 2 was release from the Airport. Kiosk mode was a complete slower load that reset everything including luggage. Fast Load does not reset luggage or Scout Statue but is a faster load.  
Do not open any luggage until all players have loaded or the luggage might not be accessible after all players sync.
***
*Manual Installation:
1. Download and install BepInEx.
2. Run Peak to Generate BepINEx plugins folder.  
---
3. Download ExpeditionSaveManager.
4. Open PEAK Installation: Steam -> PEAK -> Manage -> Browse Local Files
5. Goto BepInEx -> plugins folder.
6. Copy the scr.TSave.dll to the plugins folder ex: BepInEx/plugins/scr.TSave.dll
7. Run PEAK and Host Game.
8. Press ESC and there will be a new menu option below the Settings button called Expedition Save Manager.
***
*Report Bugs:
https://github.com/scottcruss/ExpeditionSaveManager/issues
***
*Comments and suggestions:
https://github.com/scottcruss/ExpeditionSaveManager/discussions
***
*Donations:
https://ko-fi.com/scottcruss
