# PD2-PlugY
[PlugY](http://plugy.free.fr/) v14.03 files with settings adjusted for PD2

PlugY is a singleplayer mod which adds stash pages, fixes ubers, and allows unlimited skill/stat resets as well as several other optional features.

### [Download](https://github.com/BetweenWalls/PD2-PlugY/archive/main.zip)

## Setup Guide
1. Pre-Setup - Ensure you have *Diablo II LoD* and *PD2* installed
3. Add PlugY - copy the *ProjectD2* folder included here into your *Diablo II* folder
3. Run PlugY.exe as administrator

You'll still need to run PD2 via the launcher occasionally to get the latest patch/update.

### Troubleshooting
* PlugY may not load correctly if it is added after a fresh PD2 installation or if PD2 hasn't been updated in a while - run the game once via the launcher to fix it
* Older versions of PlugY had a different folder structure (some files were in the *Diablo II* folder instead of the *Diablo II/ProjectD2* folder) so they won't be ovewritten automatically - delete those old files manually if there are any issues
* Old s1/s2 characters may not load correctly - to update them, see [PD2-Converter](https://github.com/BetweenWalls/PD2-Converter#simple-characterstash-converter-for-pd2)

PlugY bugs:
* Having many maps in a single stash page can cause a crash if it is the most recently visited page
* Having gold in the shared stash can cause issues such as preventing CtA oskills from working correctly
* The "toggle stash" button may be set to the wrong stash upon loading until interacting with the current stash - putting an item on a higher page (such as page 200) in whichever stash is loaded first seems to fix it in some cases

There are in-game commands for renaming stash pages and moving stash pages around, as well as some other useful commands such as renaming characters - checkout the PlugY [Readme](https://raw.githubusercontent.com/BetweenWalls/PD2-PlugY/main/ProjectD2/PlugY_The_Survival_Kit_-_Readme.txt) file.

All features can be enabled or disabled within the PlugY.ini settings file.