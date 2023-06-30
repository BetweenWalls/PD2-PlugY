# PD2-PlugY
[PlugY](http://plugy.free.fr/) v14.03 files with settings adjusted for PD2

PlugY is a singleplayer mod which adds stash pages, fixes ubers, and allows unlimited skill/stat resets as well as several other optional features.

### [Download](https://github.com/BetweenWalls/PD2-PlugY/archive/main.zip)

## Setup Guide
1. Pre-Setup - Ensure you have *Diablo II LoD* and *PD2* installed
2. Add PlugY - copy the **ProjectD2** folder included here into your **Diablo II** folder
3. Run **PlugY.exe** as administrator

You'll still need to run PD2 via the launcher to update the game to the latest season/patch.

### Troubleshooting
* PlugY may not load correctly if it is added after a fresh PD2 installation or if PD2 hasn't been updated in a while - run the game once via the launcher to fix it
* Older versions of PlugY had a different folder structure (some files were in the **Diablo II** folder instead of the **Diablo II/ProjectD2** folder) so they won't be ovewritten automatically - delete those old files manually if there are any issues
* Old characters from previous seasons may not load correctly - to update them, see [PD2-Converter](https://github.com/BetweenWalls/PD2-Converter#simple-characterstash-converter-for-pd2)

PlugY bugs:
* If a single stash page contains many items that each have many affixes (e.g. maps) then crashes can occur when accessing that page or at any time if that page was the most recently viewed page
    * FIX: Reduce the number of maps stored per page, or switch to another page before leaving the stash or saving/exiting
* Having gold in the shared stash can cause issues such as preventing oskills from working correctly
    * FIX: Ensure no "shared gold" remains in the stash during normal gameplay (the "shared gold" feature is disabled by default)
* The "toggle stash" button may be set to the wrong stash upon loading until interacting with the current stash - this happens if the most recent stash interaction prior to saving/exiting involved using a PlugY stash button instead of manipulating an item in the stash
    * FIX: Add or remove an item from the stash prior to saving/exiting (this also fixes the button at any time if it's set wrong)
* Stash navigation may be buggy if the stash pages are empty - the navigation will appear to jump between the wrong pages, but it is actually just displaying the wrong page numbers for all pages between the first page (page 1) and the first index (page 10)
    * FIX: Put an item on page 10 or higher (you'll also need to exit to the character menu and rejoin)

There are in-game commands for renaming stash pages and moving stash pages around, as well as some other useful commands such as renaming characters - checkout the PlugY [Readme](https://raw.githubusercontent.com/BetweenWalls/PD2-PlugY/main/ProjectD2/PlugY_The_Survival_Kit_-_Readme.txt) file.

All features can be enabled or disabled within the **PlugY.ini** settings file.
