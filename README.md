# 11/01/26 - The new Peak v3 crossplay update:

*Expedition Save Manager 2:
- Now version 2 for full support of Peak v3 crossplay.
- New saves and loads fully functional.
- Pre Peak v3 crossplay saves and load fully functional with closest Biome match.
- "Airport Kiosk load" mode now fully functional again. 

*Timeout (Multiplayer pause) works perfectly for all Biomes!

***

***
<img width="50%" alt="Image" src="https://github.com/user-attachments/assets/f51a522a-2283-427c-a123-c54e12895571" />

<p>

  
# ExpeditionSaveManager
<img width="200" align="left" alt="Image" src="https://github.com/user-attachments/assets/c8f1c4bf-2850-4f89-aca2-ddf0176ad851" />

Peak v3 mod Expedition Save Manager and Timeout (Multiplayer Pause): 

Multiplayer load and save from any location! Stop and continue the game at any time. Complete state including player inventory and all world items saved and restored. Expeditions of saved files are grouped together to allow multiple Expeditions with different players on different days! 

Also includes a Timeout feature! (aka Multiplayer Pause)
</p>
<br clear="all">









***




***

***




***

***




***
# Expeditions Listing
Expeditions are grouped saved files.

<img width="800" alt="Image" src="https://github.com/user-attachments/assets/e4c12b3f-2dca-46e1-8063-0b34a405d5fc" />

A new Expedition is created automatically when the first save occurs upon hosting a new game. All new saves will be saved to the Expedition when an Expedition is loaded or created. A new Expedition can be created at any time by starting a new game at the Kiosk from the Airport.

<img width="48" align="left" alt="Image" src="https://github.com/user-attachments/assets/6487da04-7e4f-4e69-b524-3074fe3106db" />
Right clicking an Expedition or clicking purple crayon allows adding a note to an Expedition.
<br clear="left" />


<img width="48" align="left" alt="Image" src="https://github.com/user-attachments/assets/43f8bab2-30ed-4c1f-8972-027b777d6dad" />
Clicking the Trashcan on the left deletes the entire Expedition including all saved files for that Expedition.
<br clear="left" />


***

# Saved Games

<img width="800" alt="Image" src="https://github.com/user-attachments/assets/105db60c-75b9-421e-8ba3-3afa16c07a7b" />

There are 2 loading methods (Settings option). Fast Load (default) and Airport Kiosk mode. Airport Kiosk mode is a complete slower load that resets everything including luggage and Scout Statue Altar. Fast Load does not reset luggage or Scout Statue but is an incredibly faster load.  
Do not open any luggage during Fast Load until all players have loaded or the luggage might not be accessible after all players sync.

New Added option for Host to select Biome when loading an old unsupported Biome group. Feature enabled in Load Settings. Changing Replacement Level Picked Automatically to Host Picks Replacement Level from List.
<img width="400" alt="Image" src="https://github.com/user-attachments/assets/3e089b21-7d95-4379-bfee-2778e47e143e" />

New added popup notifications when loading saved files.
<img width="800" alt="Image" src="https://github.com/user-attachments/assets/51994ca9-9c47-42c1-8f22-a466ea5c6cba" />
<img width="800" alt="Image" src="https://github.com/user-attachments/assets/7d5df4a7-d128-41eb-bcde-7802380c16bb" />

New added popup shows the players saved in the Expedition and if any players are missing.
<img width="800" alt="Image" src="https://github.com/user-attachments/assets/1c925146-54f9-4976-8cc1-8e8708c439f2" />


Return to Airport button to take all players back to Airport.

Correction feature button allows correcting game items offset that can occur on only older versions of Peak saves after a major Peak update. aka Apples or Coconuts floating in the air. When enabled this will fix all out of alignment objects. It does not impact new saved files. Correction should not need to be disabled at any time but added as a safe guard. It does not slow down the loading of saved games. This should allow pre update saves to continue to work until the peak is reached!

Autosave option and configurable interval. On by default for new installs. Incredibly fast!
Configurable from the Settings menu.

Save files are saved in the folder: PeakTSaves in the Peak folder. 
Configurable from BepInEx/config/com.scr.peakexpeditionsavemanager.cfg.
All save files are stored in json.

***

# Timeout (aka Multiplayer Pause)

<img width="800" alt="Image" src="https://github.com/user-attachments/assets/c1104426-4c70-4408-b70f-f75ab166710a" />
<img width="800" alt="Image" src="https://github.com/user-attachments/assets/502fae7a-0ae2-4563-af98-830f361f6628" />

Since pausing is not possible in multiplayer without all players having the mod, added a Timeout feature like a pause controlled by the Host. All players temporary transported and restricted to the prior campfire. Fog, Time, hunger, Day/Night clocks are all suspended during Timeout. When Timeout is ended, players are restored to prior location, state and environment is reset back to prior state. 
Timeout Host (Settings) controlled feature blocking accessing items at Campfire during Timeout is available.

***
Known issues:  
Only using Airport Kiosk Mode (Settings option) for loads completely resets the entire original state.
Fast Mode does not reset open luggage and Scout Statue states. Placed items like ropes, chains, shelf fungus, etc are not removed between fast loading saved files. 

Loading a Citadel biome while in the Void does not restore correctly. Going back to Airport first is required.

If a player or backpack glitches occur during Fast load, clicking 4 for backpack can reset player or loading the same saved game a 2nd time should correct issues.


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
