# discordAvoidQuests
Don't start with the Quests-Screen when discord starts

## Why an URL shortcut?

Discord (as many electron apps (chrome in a box)) installs itself into AppData\Local\Discord\app-1.0.9269 as of today, but with every update the folder name changes which makes a normal windows shortcut only work until an update.

Gladly discord also has an Windows Protocoll installed like http:// but with discord:// which basically points to the current install folder which is updated during a patch install automatically.

## How to use this?

Download the git repo or the zip

When using the zip extract everything in an directory so the "Discord ME.url" and the "copy_to_autostart.bat" are in the same directory.

Just use the copy_to_autostart.bat and the link will be copied to the startup folder and the start menu so you can also run it manually

The ICON will change automatically after the first run, if not after a windows restart. Windows does Windows things.
