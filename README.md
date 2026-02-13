# Friday Night Funkin: Extrapolator Engine
"The extrapolation of a FNF engine." - Broken Record Kid

Extrapolator Engine is essentially a generic Psych Engine fork, which is a modder-friendly version of Friday Night Funkin. (until vslice was created) This fork/engine aims to add new features and tweaks to Psych Engine 0.6.3, and ultimately make the engine more... something?

# Work In Progress Update / To Do List
My current priority for this engine is:
* Improved Chart Editor (possible haxeUI support/switches)

## Installation (taken from psych 0.6.3's description):
You must have [the most up-to-date version of Haxe](https://haxe.org/download/), seriously, stop using 4.1.5, it misses some stuff.

Follow a Friday Night Funkin' source code compilation tutorial, after this you will need to install LuaJIT.

To install LuaJIT do this: `haxelib git linc_luaji  t https://github.com/nebulazorua/linc_luajit` on a Command prompt/PowerShell

...Or if you don't want your mod to be able to run .lua scripts, delete the "LUA_ALLOWED" line on Project.xml


If you get an error about StatePointer when using Lua, run `haxelib remove linc_luajit` into Command Prompt/PowerShell, then re-install linc_luajit.

If you want video support on your mod, simply do `haxelib install hxCodec` on a Command prompt/PowerShell

otherwise, you can delete the "VIDEOS_ALLOWED" Line on Project.xml

## Credits:

## Extrapolator Engine Credits:
* Broken Record Kid - Programmer/Owner

## Special Thanks:
* Elizm on Gamebanana - Botplay & Prctice Sprites
** https://gamebanana.com/tools/10914
* Dsfan2 - Inspiraton (and some code snippets)

### Psych Engine Credits:
* Shadow Mario - Programmer
* RiverOaken - Artist
* Yoshubs - Assistant Programmer

#### Special Thanks
* bbpanzu - Ex-Programmer
* shubs - New Input System
* SqirraRNG - Crash Handler and Base code for Chart Editor's Waveform
* KadeDev - Fixed some cool stuff on Chart Editor and other PRs
* iFlicky - Composer of Psync and Tea Time, also made the Dialogue Sounds
* PolybiusProxy - .MP4 Video Loader Library (hxCodec)
* Keoiki - Note Splash Animations
* Smokey - Sprite Atlas Support
* Nebula the Zorua - LUA JIT Fork and some Lua reworks
_____________________________________

# Regarding Current and Upcoming FNF Updates
I will not be modding/porting the current and upcoming FNF updates, since this fork runs on a early build of FNF. (Psych 0.6.3, FNF 0.2.8)

If you want to port the weeks/updates yourself, go ahead. I may incorporate some of V-Slice's features, but this doesn't mean I will be porting the newer updates.

Also btw V-Slice and Codename are the all time goats at FNF modding engines.