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

There are 2 loading methods (Settings option). Fast Load (default) and Airport Kiosk mode. Airport Kiosk mode is a complete slower load that resets everything including luggage. Fast Load does not reset luggage or Scout Statue but is an incredibly faster load.  
Do not open any luggage during Fast Load until all players have loaded or the luggage might not be accessible after all players sync.

Return to Airport button to take all players back to Airport.

Correction feature button allows correcting game items offset that can occur on only older versions of Peak saves after a major Peak update. aka Apples or Coconuts floating in the air. When enabled this will fix all out of alignment objects. It does not impact new saved files. Correction should not need to be disabled at any time but added as a safe guard. It does not slow down the loading of saved games. This should allow pre update saves to continue to work until the peak is reached!

Autosave option and configurable interval. On by default for new installs. Incredibly fast!
Configurable from the Settings menu.

Save files are saved in the folder: PeakTSaves in the Peak folder. 
Configurable from BepInEx/config/com.scr.peakexpeditionsavemanager.cfg.
All save files are stored in json.

***

# Timeout (aka Multiplayer Pause)

<img width="800" alt="Image" src="https://github.com/user-attachments/assets/59b31138-3aa6-48f8-9c98-5b09f00ad5f9" />
<img width="800" alt="Image" src="https://github.com/user-attachments/assets/3bd5ec1e-5478-4905-8c40-b997901d7bd3" />

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
