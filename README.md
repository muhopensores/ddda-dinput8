# Dragon's Dogma: Dark Arisen dinput8.dll hook
## Features
### Save backups
It should find the save path automatically, if not see dinput8.ini.  
A hook is placed just before the game creates a save. When it gets there, the current save gets duplicated with a timestamp added to it.  
If you need to revert to previous save, simply rename it to "ddda.sav".  
You can limit the number of backups it keeps in dinput8.ini.

### Character customization screen
Allows you to enter the character customization screen at any time.  
It replaces the Manual menu (the one on the very first screen).

You need to enter it with keyboard (press enter), doesn't work with mouse.

### In-game clock
Displays in-game time in top right corner of the screen.  
May not work with enb, steam overlay, etc.

You need to enable it in dinput8.ini.  
You can change the font size/color in dinput8.ini.  
You can also change how often is the clock updated.

### Cheats
An option to remove stamina drain while running outside of cities.  
An option to reduce your total weight.  
See dinput8.ini.

## Installation
Copy dinput8.dll and dinput8.ini into the main DDDA folder.

## Credits
MinHook - The Minimalistic x86/x64 API Hooking Library:  
http://www.codeproject.com/Articles/44326/MinHook-The-Minimalistic-x-x-API-Hooking-Libra

inih - simple .INI file parser  
https://github.com/benhoyt/inih

Idea for entering customization screen + pointers for clock taken from:  
http://forum.cheatengine.org/viewtopic.php?p=5641841#5641841
