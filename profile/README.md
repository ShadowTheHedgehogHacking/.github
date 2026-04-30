# Red Westopolis - Shadow the Hedgehog Hacking / Modding

Tools/Mods for Shadow the Hedgehog 2005.

## Game Mods

### GameCube
* [Widescreen-ShadowTH](https://github.com/ShadowTheHedgehogHacking/Widescreen-ShadowTH) - A standalone widescreen mod that can be applied to the original NTSC-U and PAL versions for GameCube
* [ShdTH-Reloaded](https://github.com/ShadowTheHedgehogHacking/ShdTH-Reloaded) - Shadow the Hedgehog: Reloaded is an improvement mod of Shadow the Hedgehog designed to make the game less tedious, increase challenge, fix bugs and oversights, restore some unused content, and generally remix levels
* [2P-ShdTH](https://github.com/ShadowTheHedgehogHacking/2P-ShdTH) - A 2P multiplayer mod for the original Shadow the Hedgehog GameCube NTSC-U
* [2P-Reloaded](https://github.com/ShadowTheHedgehogHacking/2P-Reloaded) - 2P multiplayer version of the Shadow the Hedgehog: Reloaded v1.2 Mod
* [ShadowRando](https://github.com/ShadowTheHedgehogHacking/ShadowRando) - A randomizer for Shadow the Hedgehog (GameCube NTSC-U), allowing you to randomize stage routing, enemy types, weapons, subtitles, audio, and more

# Tools

## Formats
* .ONE - [ShadowONE](https://github.com/ShadowTheHedgehogHacking/ShadowONE) or [HeroesONE-Reloaded](https://github.com/Sewer56/HeroesONE-Reloaded)
* .TXD - [MagicTXD v1.1](https://gtaforums.com/topic/851436-relopensrc-magictxd/) or [ShadowTXD](https://github.com/ShadowTheHedgehogHacking/ShadowTXD)
* .DFF - [DragonFF for Blender](https://github.com/Parik27/DragonFF) or [RWIO plugin for 3DSMax](https://github.com/aap/rwio)
* .MTP & .BON - [ShadowMTPSharp](https://github.com/Sewer56/ShadowMTPSharp) & [Blender-3D-STH-Mtn-plugin](https://github.com/Psycrow101/Blender-3D-STH-Mtn-plugin)
* .FNT - Subtitles and Linked Audio Triggers - [ShadowTH Text Editor / FNT Editor](https://github.com/ShadowTheHedgehogHacking/ShadowTHTextEditor)
* .AFS - Audio archive containing .ADX with all the voice lines - [ShadowTH Text Editor / FNT Editor](https://github.com/ShadowTheHedgehogHacking/ShadowTHTextEditor), [SimpleAFSExtractor](https://github.com/ShadowTheHedgehogHacking/SimpleAFSExtractor), [PAFS](https://github.com/ShadowTheHedgehogHacking/PAFS)
* .ADX - Game Music, Event Audio, Voicelines - [VLC Media Player](https://www.videolan.org/vlc/) and [MPV](https://mpv.io/) can preview these without converting. For converting to/from consider [radx](https://github.com/Isaac-Lozano/radx) or [VGAudio](https://github.com/Thealexbarney/VGAudio)
* stgXXXX geometry, visibility, collision / layout _cmn / layout _hrd / layout _ds1 / layout _nrm / lighting file _light - [Heroes Power Plant](https://github.com/igorseabra4/HeroesPowerPlant)
* .BNR & .TP - GameCube save data banner - [GC-TP-BNR-Tool](https://github.com/BlazinZzetti/GC-TP-BNR-Tool)
* .MLT - GameCube Sound Effect Archives - Not cracked / no tools available. You can [manually replace some data with Hex Editing](https://youtu.be/DbUlOpuYJjc)
* .PAC - Xbox Sound Effect Archives - [PACTool](https://github.com/Sewer56/PACTool)
* .GNCP / .XNCP / .SNCP (CSD Files) - [kunai](https://github.com/NextinMono/kunai) or [Shuriken](https://github.com/SKmaric/Shuriken) - Warning: Both of these tools can not write/save properly for Shadow the Hedgehog
* Docs on format endian and other quirks regarding formats [shadow-docs](https://github.com/ShadowTheHedgehogHacking/shadow-docs)

## Models
* [CharacterMods](https://github.com/ShadowTheHedgehogHacking/CharacterMods) - repo containing model swaps and custom models
* [ShadowMTPSharp](https://github.com/Sewer56/ShadowMTPSharp) - library for importing/exporting MTP data (Animation archives)
* [ShadowMotionSwapper](https://github.com/ShadowTheHedgehogHacking/ShadowMotionSwapper) - program to accelerate making "Custom BON" type Character Mods from swapping 
* [shadow-model-fixes](https://github.com/ShadowTheHedgehogHacking/shadow-model-fixes) - Fixes for some oversights in the original game

## Custom Level Creation / Layout Editing
* [Heroes Power Plant](https://github.com/igorseabra4/HeroesPowerPlant)

## Custom Feature Creation / Code
* [Dolphin](https://github.com/dolphin-emu) - Enable Debugging UI, import our GameCube symbol map, and utilize the Dolphin Branch Watch feature
* [Dolphin Memory Engine / DME](https://github.com/aldelaro5/dolphin-memory-engine) - Program similar to Cheat Engine but built for Dolphin
* [GameCube Memory watchlists (.dmw) and our symbol maps](https://github.com/ShadowTheHedgehogHacking/shadow-symbols-and-dmw)
* [BlazinZzetti's Memory watchlists (.dmw)](https://github.com/BlazinZzetti/ShadowMemoryWatchList)
* [CodeWrite](https://github.com/TheGag96/CodeWrite) - for creating Gecko Codes from PPC ASM. You can also use Dolphin's built in Assembler instead.
* [Melee Code Manager](https://github.com/DRGN-DRC/Melee-Code-Manager) - for injecting codes directly into DOL/Disc. Requires edited settings.py to work with Shadow The Hedgehog. You can get the required [settings.py from ShdTH-Reloaded repo](https://github.com/ShadowTheHedgehogHacking/ShdTH-Reloaded/blob/master/code/MCM/settings.py).

## Patch Creation (VCDIFF/XDELTA)
* [VCDiffGUI](https://github.com/ShadowTheHedgehogHacking/VCDiffGUI)
* [xdelta-wasm by kotcrab](https://github.com/ShadowTheHedgehogHacking/xdelta-wasm)

## Speedrunning
* [Shadow SX / Shadow: Speedrunner's Cut](https://github.com/ShadowSpeedrun/ShadowSX) and [Shadow SX Launcher](https://github.com/ShadowSpeedrun/ShadowSXLauncher)
* [LiveSplit ASL Auto Splitter for Dolphin](https://github.com/ShadowSpeedrun/LiveSplit-ASL-Scripts)
* [ShadowPractice](https://github.com/BlazinZzetti/ShadowPractice) - A gecko code that helps learning about point routing in Shadow the Hedgehog
* [Saves](https://github.com/ShadowSpeedrun/Resources/tree/main/Save%20Files) - Additional save files
