![FAQ General Questions](https://github.com/user-attachments/assets/6255a0ed-1e52-412a-9030-c9a8ef00d545)
### Can I update outdated mods in the list? Can I use LOOT on the list? <br />
I will lose my shit if you come to my Discord asking for help with an obscure bug and I found out you used LOOT on my modlist or updated a mod that I left purposely outdated
### Can I add more mods to the list?<br />
Yes, but it is not something the average person is gonna have much success in, depending on the complexity of the mods involved. You MUST refer to my guide on how to add additional mods to Star Wars Genesis [here](https://github.com/DeityVengy/Star-Wars-Genesis-Modified-Install) and you MUST only ask for help in channels marked for modified installs.
### Xbox Version? <br />
As of V5, this modlist is beyond the mod limit of Starfield and only functions due to thousands of custom patches I've done. That means that it is now impossible to replicate without using a modlist auto-installer like Wabbajack, which consoeles don't have. All of my personal mods on Nexus are open permission and free to be ported over by others through. i've noticed some already have been. You can get something similar on Xbox, but not to this level unfortunately, atleast for awhile. 
### How do I get X Weapon/Armor/Item/Ship?<br />
Every single thing in this modlist can be acquired ingame through natural progression. If you want to skip that, then look at the [Star Wars Genesis Encyclopedia](https://docs.google.com/spreadsheets/d/10nsfWMzfDtFHDXaNGmyb3dDeQLnNtfgh/edit?gid=319705241#gid=319705241) and find the base game equivalent or location of the Weapon/Armor you want. Google the ID of that item and spawn it in with console commands. I DO NOT SUPPORT ANYTHING IN THE WORKBENCHES. You are free to use stuff in the workbenches but they are not balanced around Star Wars Genesis and may even be buggy.
### Why no lightsabers?<br />
There are a few lightsaber and Jedi/Sith mods out there but it just doesn't really work or feel immersive, especially with this game's poor melee combat. I will add lightsabers when they are ready with proper animations, deflection, and dismemberment. To be fair, the odds of the average person in Star Wars encountering a Jedi/Sith in this era is pretty low anyway. Just make it part of your headcannon lol.
#   
![FAQ General Questions (3)](https://github.com/user-attachments/assets/6ce910a5-b41e-4ffa-904e-87039ddde8c1)

### Download Error OR OAuth Token Error
Relog on Nexus in the Wabbajack app. If you got IP banned, just wait 10 minutes and relog. This happened because your login expired.
### Stuck on Downloading Last File or "Unable to download x file"
  - Just close the installer and restart it again, pointing to the exact same location as last time. Make sure "overwrite installation" is UNCHECKED. This will resume your download/install as normal. <br />
  - If the above doesn't work, then go into your downloads folder and delete everything inside there. Then, close Wabbajack if it's open and press Windows + R on your keyboard. Type in %localappdata%. You should see a Windows Explorer window pop up. Find and delete the folder called Wabbajack inside.
  - Now close and open Wabbajack around 3-5 times and try again to download the modlist
### Unable to hash AAAAA something
This is an old fashioned corrupted file error. You must delete the downloads folder and create a new one, then reinstall.
### Access Denied Error
This is usually caused by some sort of Anti-Virus software. I recommend disabling it while you install or adding the Star Wars Genesis folders to the whitelist. Known antiviruses that cause this issue include AVG, Avast, BitDefender, Webroot, Kaspersky, Norton, McAfee, etc.

#
![FAQ General Questions (5)](https://github.com/user-attachments/assets/2d634095-9483-43ed-bd2b-c2c9058a0878)
### ModOrganizer.exe is missing<br />
Under Virus and Threat Protection Settings (Windows Security), go to "Manage Controlled Folder Access" whitelist the Starfield folder in both Documents/My Games/Starfield and steamapps/common/starfield.
### Mod Organizer Failed to Load the Plugin or is Failing to Launch
   1. Make sure you have installed the latest version of [.NET Framework](https://dotnet.microsoft.com/en-us/download/dotnet-framework)
   2. Start Powershell
   3. CD your install location. Example would be: _cd "C:\Star Wars Genesis"_
   4. Run this command: _dir -Recurse | Unblock-File_
### Baka Hold to Sprint Disabled Popup
Update VC++ on the drive that you installed this modlist on. You can find the link to the latest version [here](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170). Just put the .exe for the x64 version anywhere in the same drive that the modlist is on
### How to reset the plugin order after it got jumbled up?
At the top of your plugins tab, there's a button you can press to load a backup of the vanilla V5 plugin order.
#   
![FAQ General Questions (7)](https://github.com/user-attachments/assets/ece3c367-c40a-4bc6-b89a-f83c6a1f30b0)
### Game Crashing on Startup or not Loading at All <br />
Delete starfield.exe in your steamapps/common/Starfield folder and then verify your game files through Steam. 
### Stuck/Crash on Main Menu after Launching New Game
This is almost always caused by having additional mods in your game, including mods from creation store, nexus, or manually installed ones. YES THIS INCLUDES **_BAKA ACHIEVEMENT ENABLER_** <br />
If you can't figure it out, just delete the Data folder in steamapps/common/Starfield and repair your game through Steam
### Starfield is Stuck Minimized
1. Open Task Manager. Under process, expand Starfield. Right click the Starfield subprocess and select maximize.<br />
If that doesn't work:<br />
1. Open your Nvidia Controll Panel on the Desktop, go to 3d settings and then to Program Settings.
2. Search for Starfield in the first tab, if its not there, add it.
3. If Starfield is selected go to tab 2 and search for Vsync and deactivate it.
4. Try to start the game again.
5. If game still doesn't maximize, try turning off Steam Overlay
6. If that doesn't work, then try these next steps: <br />
    - Go to C:\Users\USERNAME\Documents\My Games\Starfield\StarfieldPrefs.ini
    - Edit the ini file and add these lines under Display:<br />
    [Display] <br />
    bBorderless=0 <br />
    iLocation Y=0 <br />
    iLocation X=0 <br />
### RealTimeFormPatcher Error or Unsupport Address Library Format
Install this in the same drive that you have the modlist and game: https://aka.ms/vs/17/release/vc_redist.x64.exe
#
![FAQ General Questions (4)](https://github.com/user-attachments/assets/ec3ac80f-710c-4ca9-ae55-aa91232914d9)
### Black Textures on Armor/Weapons/Faces <br />
   - Download this bat file from [here](https://www.nexusmods.com/starfield/mods/6371?tab=files) and run it. Restart your PC to be safe.<br />
   - If that doesn't work, delete your Data folder in steamapps/common/Starfield and repair the game via Steam<br />
   - If that still doesn't work, then try this:<br /> ![image](https://github.com/user-attachments/assets/e88e4bc5-34c3-4b38-8469-3a8ae2c2e6f5)

### Ship Missing in Alternate Start
Just talk to the technician and briefly enter the build menu and it should spawn.
### Failed to save game<br />
   1. Check Documents\My Games\Starfield\Saves. If any of these folders don't exist, create them in that order.
   2. Under Virus and Threat Protection Settings (Windows Security), go to "Manage Controlled Folder Access" whitelist the Starfield folder in both Documents/My Games/Starfield and steamapps/common/starfield.
   3. Disable OneDrive Sync on your Documents folder
### Planets/Dialogue not changed <br />
   Make sure your language for Starfield is set to English on Steam
### Half of the Mods Aren't Working
   1. Make sure you followed "IMPORTANT POST-STEP" in the guide, involving the ini file.
   2. Go look at the bottom of ur plugin order and see if there's any mods from Bethesda Creations down there. Disable them all and try again. Multiple people have had issues where certain Creations mods break the modlist
   3. If you've used Vortex before, delete all the mods in it's folders.
### Certain NPC's are missing their heads/hands/weapons <br />
This happens when you mod existing saves. There are 2 possible solutions. First, save your game. Then open the console, click them (make sure it says NPC), and do resetinventory. If that doesn't work, try using "disable" on them closing the console for them to disappear. Then open console and without clicking anything, do "enable". IF that still doesn't work, then please kindly report it as a bug in my [Discord](https://discord.gg/sqKTwGRwwY)
### The Game is Too Hard
Check out the optional difficulty section in the install guide. <br />
### Low FPS on Good PC
This could be a ton of issues. If you simply google it, you'll find dozens of possible solutions to it online. Here are the most successful ones:
- Disable fullscreen optimizations for Starfield.exe
- Turn off auto-save in-game
- Turn off upscaling in-game
- **Delete Starfield.exe from game directory and verify files through Steam**
- Double check if you have low FPS on Vanilla Starfield or not
### Long Loading Times
Make sure both the modlist and game is installed on SSD
Make sure you're not using an external SSD for god's sake
### Can't Fast Travel
1. Open the Console and type ‘DumpInputEnableLayers’ then hit Enter.
2. You should see a list of three or four numbered Layers, find the Layer that has Fast Travel listed.
3. Type ‘ResetInputEnableLayer NUMBER’ with the number of the layer where it says NUMBER, then hit Enter.
### Jetpack Mod Not Working
1. First, make sure you don't have a controller plugged into your PC, which blocks the F1 hotkey from functioning.
2. Open the **_Star Wars Genesis - Root Pack_** mod and delete these folders/files:<br />
   - Hotkeys folder
   - disable_hotkeys.cmd
   - enable_hotkeys.cmd<br />   
3. In Mod Organizer 2 at the bottom of your modlist tab, double click the overwrite folder and delete everything inside it.
4. Manually download [Starfield Hotkeys](https://www.nexusmods.com/starfield/mods/1578?tab=files) and drag the files in the archive into steamapps/common/Starfield. <br />
5. Manually download [Extended Jetpack (Less Fuel Drain)](https://www.nexusmods.com/starfield/mods/3800?tab=files) and drag the files in the archive into steamapps/common/Starfield. Now run the enable_hotkeys.cmd file in your Starfield directory<br />
### HK-47 Just Punches People
Trade with him and make him equip his weapon in his inventory.
