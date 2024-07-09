# **F.A.Q.**
## Black Textures on Armor/Weapons/Faces <br />
   Download this bat file from [here](https://www.nexusmods.com/starfield/mods/6371?tab=files) and run it. Restart your PC to be safe.<br />
   If that doesn't work, delete your Data folder in steamapps/common/Starfield and repair the game via Steam<br />
## Planets/Dialogue not changed <br />
   Make sure your language for Starfield is set to English on Steam
## "Half the modlist isn't working" etc
   Go look at the bottom of ur plugin order and see if there's any mods from Bethesda Creations down there. Disable them all and try again. Multiple people have had issues where certain Creations mods break the modlist.
## The game is crashing on startup/isn't launching <br />
   Delete starfield.exe in your steamapps folder and then verify your game files through Steam. 
## ModOrganizer.exe in the Star Wars Genesis folder is not opening<br />
   Download [Mod Organizer 2.5.2dev4](https://onedrive.live.com/?authkey=!ACOOWjZT3MUR068&id=371272C49A37CC4A!151853&cid=371272C49A37CC4A&parId=root&parQt=sharedby&o=OneUp) and drag all it's contents into the Star Wars Genesis folder and replace all files
## ModOrganizer.exe is missing<br />
   Under Virus and Threat Protection Settings (Windows Security), go to "Manage Controlled Folder Access" whitelist the Starfield folder in both Documents/My Games/Starfield and steamapps/common/starfield.
## Certain NPC's are missing their heads/hands/weapons <br />
   This happens when you mod existing saves. There are 2 possible solutions. First, save your game. Then open the console, click them (make sure it says NPC), and do resetinventory. If that doesn't work, try using "disable" on them closing the console for them to disappear. Then open console and without clicking anything, do "enable". IF that still doesn't work, then please kindly report it as a bug in my [Discord](https://discord.gg/sqKTwGRwwY)
## Failed to save game<br />
   1. Check Documents\My Games\Starfield\Saves. If any of these folders don't exist, create them in that order.
   2. Under Virus and Threat Protection Settings (Windows Security), go to "Manage Controlled Folder Access" whitelist the Starfield folder in both Documents/My Games/Starfield and steamapps/common/starfield.
   3. Disable OneDrive Sync on your Documents folder
## Baka Hold to Sprint Disabled Popup
   Update VC++ on the drive that you installed this modlist on. You can find the link to the latest version [here](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170). Just put the .exe anywhere in the same drive
## Jetpack Mod Not Working
   First, make sure you don't have a controller plugged into your PC, which blocks the F1 hotkey from functioning. <br />
   Open the **_Star Wars Genesis - Root Pack_** mod and delete these folders/files:<br />
   - Hotkeys folder
   - disable_hotkeys.cmd
   - enable_hotkeys.cmd<br />
   
1. Manually download [Starfield Hotkeys](https://www.nexusmods.com/starfield/mods/1578?tab=files) and drag the files in the archive into steamapps/common/Starfield. <br />
2. Manually download [Extended Jetpack (Less Fuel Drain)](https://www.nexusmods.com/starfield/mods/3800?tab=files) and drag the files in the archive into steamapps/common/Starfield. Now run the enable_hotkeys.cmd file in your Starfield directory<br />
## Starfield is stuck minimized
1. Open your Nvidia Controll Panel on the Desktop, go to 3d settings and then to Program Settings.
2. Search for Starfield in the first tab, if its not there, add it.
3. If Starfield is selected go to tab 2 and search for Vsync and deactivate it.
4. Try to start the game again.
5. If game still doesn't maximize, try turning off Steam Overlay
