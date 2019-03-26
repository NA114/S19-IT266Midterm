The desktop shortcut must have a Target property containing the filepath for the original Quake 4 executable in the game's Steam folder. The Target field must also contain the following properties, followed by the name of the mod folder:

+disconnect (This skips the game's opening cutscenes)
+set fs_game (This tells the game to start up using the mod folder, instead of q4base)

In other words, the desktop shortcut's Target field must have the following format:

"Filepath_In_Quotations" +disconnect +set fs_game metalwolfquake

**Current Working Deliverables**
Main:
Third-person camera
Common:
Mod setup as a separate folder
Desktop shortcut that automatically launches mod
Readme