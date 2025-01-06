# RemoveGangRetaliation
Cyberpunk 2077 mod to remove gang retaliation car chase events added after patch 2.1

### Solution 
Delete `vehicleRecord =` records in the appropriate dynamicspawn tweak files corresponding to the offending gang. This appears to prevent the game (scripts?) from spawning the gang retaliation vehicle and its occupants. 
Note: this is somewhat crude tweak file based solution and may benefit from refinement (remove the actual source scripts / logic chains that spawn these events if accessible/possible instead of preventing them from functioning correctly)

### Testing 
In vanilla, make a savegame right before the offending gang retaliation event occurs. Load and confirm that it occurs in vanilla. Then enable the mod (Vortex mod manager or manual install)
and confirm that the savegame does not spawn the gang retaliation event.
