# OutlastTrials-ConfigChanges
Config files changes for outlast trials optimization / personal preferences

### Engine.ini
Mostly optimizations for UE4 (documentation found at: https://pongrit.github.io/ )
As well as removing effects like fog, Chromatic Aberration and such. A fair amount of the changes are from an already existing PAYDAY 3 config that can be found on Nexus Mods, the rest was added by me.

Removing those effects make night vision look exactly like no night vision, + the green filter on. No more weird noise and distortion effect, that makes it hard to read from afar.
Also makes indoor maps look better (imo) revealing more on the roof of the maps, and make it look better when looking far ahead of you.

In case you only want to remove major cluttery effects like mentionned above (fog, film grain, etc...)
use the changes in the engine.ini file from the "remove only effects" folder.

### Game.ini
Changes FOV (Field of View) values. Default is 90, mine is on 110, put whichever you'd like

## Delete Intro Video
#### Important!
If you want to delete the loud (that jumpscares me everytime) intro when you start the game, change the "$introLoc" variable to your Outlast Trials path.
For that, go to Steam, right click Outlast Trials, and hover "Manage" then "Browse Local Files"
Copy the path into the variable. For me, it would be $introLoc = "D:\SteamLibrary\steamapps\common\The Outlast Trials"
The file already includes the default install for C: drive, if you have it there.

Run the file, it will delete the intro files. May be re-added after game updates, in which case you'd have to run it again. (Otherwise, if you wanna get the intro back, verify game files)
