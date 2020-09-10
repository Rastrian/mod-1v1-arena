# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore
#
- Latest build status with azerothcore: [![Build Status](https://travis-ci.org/azerothcore/mod-1v1-arena.svg?branch=master)](https://travis-ci.org/azerothcore/mod-1v1-arena)
# mod-1v1-Arena
### This is a module for [AzerothCore](http://www.azerothcore.org)

#### Features:
-1v1 Rated Arena Games

-1v1 Unrated Arena Games


### This module currently requires:
- AzerothCore v1.0.1+

### How to install
1. Simply place the module under the `modules` folder of your AzerothCore source folder.
2. Apply the ``arena-crystals-fix.patch`` to your core using ``git apply arena-crystals-fix.patch``, this patch also apply a fast start to arena crystals, until the original piece of code applys a delay of 15s, we changed to 5s for make arenas startup faster. :) (This patch its also avaliable on [Pastebin](https://pastebin.com/raw/Jw8XexQy)).
3. Re-run cmake and launch a clean build of AzerothCore
4. Run the Sql file into your database.
5. Ready.

### Usage
- Enable the module, apply the patch, build, open the server and join 1v1 with 2 characters at the BattleMaster Npc.

### Info
This module runs over the 5v5. If you want to run without replace the arena 5v5 mode, you can edit the configuration to works without any chart, or also can make your own changes.

## Credits
* [XDev](https://github.com/XdevTLKWoW): 
* Adjusted by fr4z3n for azerothcore
* Written by Teiby



AzerothCore: [repository](https://github.com/azerothcore) - [website](http://azerothcore.org) - [discord chat community](https://discord.gg/PaqQRkd)
