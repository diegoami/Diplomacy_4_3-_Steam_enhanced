# DIPLADO (DIPLomacy desperADO) 

Yet another clone of the Diplomacy Mod for Mount and Blade - Warband.

## SOURCE

Forked from 
[1.174 Updates](https://steamcommunity.com/workshop/filedetails/discussion/285119009/451850849180281143/).
Note that the base version has not been released from the author yet (Somebody). 

__There might be serious issues in this mod, so use at your own risk.__

## Installation

As described [here](https://steamcommunity.com/sharedfiles/filedetails/?id=285119009), make a copy of Modules\Native and name it Diplado or as you wish. 

Then download one of the latest release from **https://github.com/diegoami/Diplado/releases/** and extract it into said directory.

**minimal** just contains fixes. **master** releases contain changes which do not break compatibility with future releases of 4.3+ Steam for 1.174, while **develop** releases contain features that might end up have incompatible saves with future releases of the base version **develop**, however, contains more features and life improvements.  I advise you choose a **develop** release.

## KNOWN ISSUES

* Multiplayer seems to be broken in many places

## FIXES / FEATURES

Some fixes:

* Lords return reliably from exiles
* Constable's menu to sell prisoners from the garrison is shown when there are prisoners in the dungeon
* Patrols' prisoners are put in the dungeon and not into the garrison
* Travellers now keep track of ransom brokers
* The companions' dialog when they are sent on a spy mission to a town owned by the player's kingdom is correct
* Changing minister will not abort a quest you did not start
* Removed menu option to delegate quest, as this does not seem to work
* Exiled ladies do not appear in courts
* The dialog for quest to delivery food shows the right quantity of food

Some additions:

* Can spar with your army in the arena
* No crazy charge in battle of your party (they await your orders)
* Body guards
* Import / Export companions
* Whistle for your horse (key M)
* Taunt your opponents, so that they will attack you (key O)
* Main screen informs you how many lords are in town / castle hall

Features removed

* Training on the training ground, including trainer, does not cause injuries
* Relation changes during tournaments

Also on the **development** branch

* Option to turn the hold ground command on or off
* Option to assign allied lords to a default control group
* Minimap, troop ratio and kill count in the battle screen, with the option to turn it off 

**master** releases' save files are backwardly compatible, but **develop** releases may contain more interesting features.

## Credits

Many to keep track of

* the Diplomacy mod maintainers (Waihti, hessuu, fisheye, rubik, jrider, Mjollnir, Akmar Nibelung, Parsifal, Somebody) 
* and other Taleworlds  forum users: Dj_FRedy, Jinnai, lazeras, Caba`dr, Glabrezu, Efe Karaca


## COMPILING

1. Install a release from **https://github.com/diegoami/Diplado/releases/** as described above.
2. Set up Python 2.7 
* Edit `source/build_module_lav.bat` to point to the location of your Python 2
* Execute `source/build_module_lav.bat`
* Copy the full content of the directory into the Mod's module directorzy

## LEGACY

A stabler (and more boring) mod, with fewer features, can be found [here](https://github.com/diegoami/diplomacy-plus-for-warband/).
