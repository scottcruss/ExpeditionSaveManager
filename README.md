<img width="50%" alt="Image" src="https://github.com/user-attachments/assets/2a16d211-285a-4ad6-b4b3-420fe269d01c" />

# ExpeditionSaveManager

Peak mod Expedition Save Manager: Multiplayer load and save from any location! Complete state including player inventory and all world items saved and restored. Expeditions of saved files are grouped together to allow multiple Expeditions with different players!

A new Expedition is created automatically when the first save occurs upon hosting a new game. All new saves will be saved to the Expedition when an Expedition is loaded or created.
***
Autosave option and configurable interval. On by default for new installs.
Configurable from the Settings option in the mod or from BepInEx/config/com.scr.peakexpeditionsavemanager.cfg

Save files are saved in the folder: PeakTSaves in the Peak folder. 
Configurable from BepInEx/config/com.scr.peakexpeditionsavemanager.cfg.
All save files are stored in json.
***
Known issues:  
Open luggage and Scout Statue states only reset after restarting from the Airport. Placed items like ropes, chains, shelf fungus, etc are not removed between loading saved files. Dead Host requires returning to the Airport to reset. 
Complete scene states only reset after going back to the Airport.

There are 2 loading methods. Fast Load and Kiosk. Kiosk mode is not functional at this time since Peak 2 was release. Kiosk mode was a complete slower load that reset everything including luggage. Fast Load does not reset luggage or Scout Statue but is a faster load.  
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
Report Bugs and comments:
https://github.com/scottcruss/ExpeditionSaveManager/issues
