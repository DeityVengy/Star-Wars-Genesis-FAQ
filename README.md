# Wabbajack Issues
## Error downloading on every single file OR OAuth Token Error
   Relog on Nexus in the Wabbajack app. If you got IP banned, just wait 10 minutes and relog. This happened because your login expired.
## Stuck on Downloading Last File or "Unable to download x file"
  - Just close the installer and restart it again, pointing to the exact same location as last time. Make sure "overwrite installation" is UNCHECKED. This will resume your download/install as normal. <br />
  - If the above doesn't work, then go into your downloads folder and delete everything inside there. Then, close Wabbajack if it's open and press Windows + R on your keyboard. Type in %localappdata%. You should see a Windows Explorer window pop up. Find and delete the folder called Wabbajack inside.
  - Now close and open Wabbajack around 3-5 times and try again to download the modlist
## Unable to hash AAAAA something
- This is an old fashioned corrupted file error. You must delete the downloads folder and create a new one, then reinstall.
<br /><br /><br />
# Mod Organizer 2 Issues
## ModOrganizer.exe in the Star Wars Genesis folder is not opening<br />
   Download [Mod Organizer 2.5.2dev4](https://onedrive.live.com/?authkey=!ACOOWjZT3MUR068&id=371272C49A37CC4A!151853&cid=371272C49A37CC4A&parId=root&parQt=sharedby&o=OneUp) and drag all it's contents into the Star Wars Genesis folder and replace all files
## ModOrganizer.exe is missing<br />
   Under Virus and Threat Protection Settings (Windows Security), go to "Manage Controlled Folder Access" whitelist the Starfield folder in both Documents/My Games/Starfield and steamapps/common/starfield.
## Mod Organizer Failed to Load the Plugin XXX
   1. Make sure you have installed the latest version of [.NET Framework](https://dotnet.microsoft.com/en-us/download/dotnet-framework)
   2. Start Powershell
   3. CD your install location. Example would be: _cd "C:\Star Wars Genesis"_
   4. Run this command: _dir -Recurse | Unblock-File_
## Baka Hold to Sprint Disabled Popup
   Update VC++ on the drive that you installed this modlist on. You can find the link to the latest version [here](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170). Just put the .exe for the x64 version anywhere in the same drive that the modlist is on
<br /><br /><br />   
# Launch Issues
## Game Crashing on Startup or not Loading at All <br />
   Delete starfield.exe in your steamapps/common/Starfield folder and then verify your game files through Steam. 
## Stuck/Crash on Main Menu after Launching New Game
   This is almost always caused by having additional mods in your game, including mods from creation store, nexus, or manually installed ones. YES THIS INCLUDES **_BAKA ACHIEVEMENT ENABLER_** <br />
   If you can't figure it out, just delete the Data folder in steamapps/common/Starfield and repair your game through Steam
## Starfield is Stuck Minimized
1. Open Task Manager. Under process, expand Starfield. Right click the Starfield subprocess and select maximize.<br />
If that doesn't work:<br />
1. Open your Nvidia Controll Panel on the Desktop, go to 3d settings and then to Program Settings.
2. Search for Starfield in the first tab, if its not there, add it.
3. If Starfield is selected go to tab 2 and search for Vsync and deactivate it.
4. Try to start the game again.
5. If game still doesn't maximize, try turning off Steam Overlay<br />
If that doesn't work:<br />
1. Go to C:\Users\USERNAME\Documents\My Games\Starfield\StarfieldPrefs.ini
2. Input this under Display:<br />
   [Display] <br />
   bBorderless=0 <br />
   iLocation Y=0 <br />
   iLocation X=0 <br />

<br /><br /><br />
# Ingame Issues
## Black Textures on Armor/Weapons/Faces <br />
   Download this bat file from [here](https://www.nexusmods.com/starfield/mods/6371?tab=files) and run it. Restart your PC to be safe.<br />
   If that doesn't work, delete your Data folder in steamapps/common/Starfield and repair the game via Steam<br />
## Ship Missing in Alternate Start
   Just talk to the technician and briefly enter the build menu and it should spawn.
## Failed to save game<br />
   1. Check Documents\My Games\Starfield\Saves. If any of these folders don't exist, create them in that order.
   2. Under Virus and Threat Protection Settings (Windows Security), go to "Manage Controlled Folder Access" whitelist the Starfield folder in both Documents/My Games/Starfield and steamapps/common/starfield.
   3. Disable OneDrive Sync on your Documents folder
## Planets/Dialogue not changed <br />
   Make sure your language for Starfield is set to English on Steam
## Half of the Mods Aren't Working
   1. Make sure you followed "IMPORTANT POST-STEP" in the guide, involving the ini file.
   2. Go look at the bottom of ur plugin order and see if there's any mods from Bethesda Creations down there. Disable them all and try again. Multiple people have had issues where certain Creations mods break the modlist
## Certain NPC's are missing their heads/hands/weapons <br />
   This happens when you mod existing saves. There are 2 possible solutions. First, save your game. Then open the console, click them (make sure it says NPC), and do resetinventory. If that doesn't work, try using "disable" on them closing the console for them to disappear. Then open console and without clicking anything, do "enable". IF that still doesn't work, then please kindly report it as a bug in my [Discord](https://discord.gg/sqKTwGRwwY)
## The Game is Too Hard
   Check out the optional difficulty section in the install guide. <br />
## Low FPS When Opening Menus
This could be a ton of issues. If you simply google it, you'll find dozens of possible solutions to it online. Here are the most successful ones:
- Disable fullscreen optimizations for Starfield.exe
- Turn off auto-save in-game
- Turn off upscaling in-game
# Low FPS on Good PC
- Delete Starfield.exe from game directory and verify files through Steam
- Double check if you have low FPS on Vanilla Starfield or not
# Can't Fast Travel
1. Open the Console and type ‘DumpInputEnableLayers’ then hit Enter.
2. You should see a list of three or four numbered Layers, find the Layer that has Fast Travel listed.
3. Type ‘ResetInputEnableLayer NUMBER’ with the number of the layer where it says NUMBER, then hit Enter.
## Jetpack Mod Not Working
   First, make sure you don't have a controller plugged into your PC, which blocks the F1 hotkey from functioning. <br />
   Open the **_Star Wars Genesis - Root Pack_** mod and delete these folders/files:<br />
   - Hotkeys folder
   - disable_hotkeys.cmd
   - enable_hotkeys.cmd<br />   
1. Manually download [Starfield Hotkeys](https://www.nexusmods.com/starfield/mods/1578?tab=files) and drag the files in the archive into steamapps/common/Starfield. <br />
2. Manually download [Extended Jetpack (Less Fuel Drain)](https://www.nexusmods.com/starfield/mods/3800?tab=files) and drag the files in the archive into steamapps/common/Starfield. Now run the enable_hotkeys.cmd file in your Starfield directory<br />
## HK-47 Just Punches People
   Trade with him and make him equip his weapon in his inventory.
