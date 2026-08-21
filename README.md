# ExpeditionSaveManager

Peak mod ExpeditionSaveManager: Multiplayer load and save from any location! Complete state including player inventory and all world items saved and restored. Expeditions are grouped together to allow simultaneously Expeditions with different players!

*Open luggage and Scout Statue states only reset after restarting from the Airport.

A new Expedition is created automatically when the first save occurs upon hosting a new game.
All new saves will be saved to the Expedition when an Expedition is loaded or created.

Autosave option and configurable interval. Autosave might cause pauses to the host when saving depending on computer speed. 

Configurable from the Settings option in the mod or from BepInEx/config/com.scr.peakexpeditionsavemanager.cfg

Save files are saved in the folder: TSaves in the Peak folder. Configurable from BepInEx/config/com.scr.peakexpeditionsavemanager.cfg.
All save files are stored in json.

Known issues:  
There are 2 loading methods. Fast Load and Kiosk. Kiosk mode is not functional at this time since Peak 2 was release. Kiosk mode was a complete slower load that reset everything including luggage. Fast Load does not reset luggage or Scout Statue but is a faster load.  
Do not open any luggage until all players have loaded or the luggage might not be accessible after all players sync.

*Manual Installation:  
1. Download and install BepInEx.
2. Run Peak to Generate BepINEx plugins folder.  

3. Download ExpeditionSaveManager.
4. Open PEAK Installation: Steam -> PEAK -> Manage -> Browse Local Files
5. Goto BepInEx -> plugins folder.
6. Copy the TSave.dll to the plugins folder ex: BepInEx/plugins/TSave.dll
7. Run PEAK and Host Game.
8. Press ESC and there will be a new menu option below Settings called Expedition Save Manager.

Report Bugs:
https://github.com/scottcruss/ExpeditionSaveManager/issues
