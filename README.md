# DSPMine Industrioelectrotrainplainboatcraft Mod Pack 

## Instructions

The server will be made sure to have all server-side mods installed. As a player, you will need to
follow the instructions to install the mod loader and mods to your Minecraft client so you can 
connect to the server smoothly.

1. Install the “Fabric” mod loader following instructions here: https://fabricmc.net/use/. Choose 
the launcher you are using (usually you choose between Universal/Windows and Minecraft Launcher/MultiMC).
Note on OSX you might need to allow the execution of the JAR from preferences panel.
2. The default values for the above JAR should be just fine, make sure it’s targeting the 
version **1.15.2** and pointing to your Minecraft install location.
3. If you know where is your Minecraft installation folder, navigate there; otherwise just go straight to
start your client. **The trick for the Official Launcher is that you will see something like 
**"fabric-loader-1.15.2" on the lowerleft of the panel**. If Fabric is installed correctly, you should 
see an option to see the mods and open your "Mods Folder" in game now. _Usually on OSX the place would be somewhere like: `$HOME/Library/Application Support/minecraft`_

### For MultiMC Launcher
Click 'Add Instance' from MultiMC, then select "Import from zip" and import the zip under `vendor/MultiMC`.

### For the Official Launcher
Copy all of the JAR files under `vendor/Official` from this repo to your `mods/` directory. Restart your Minecraft
client and you should be able to see how many mods are properly loaded by Fabric loader. The magic number is

**25**

as of today.

## Inventory

### Core

- [x] Fabric API: API mod required by the Fabric mod loader
- [x] **[CLient ONLY]** ModMenu: show list of mods for Fabric
- [x] Lithium: Improve server performance
- [x] malilib: A library mod containing some shared code for masa's client-side Liteloader, Rift and Fabric mods.
- [ ] Optifine + OptiFabric: Display tweaks (Conflicting with SimplePipes)

### Tech

- [x] TechReborn: A reborn and simplified version of the famous IndustrialCraft2 and GregTech in previous versions
- [x] RebornCore: Core module for TechReborn.
- [x] Simple BC Pipes: transport items between chests and machines

### Quality Of Life
- [x] AppleSkin - Shows hunger & saturation on your HUD & how much each item of food provides in a tooltip
- [x] VoxelMap - Built-in map with HUD minimap & waypoints
- [x] **[CLient ONLY]** LightOverlay - Press F7 to show block where the light level is low enough to allow mobs to spawn
- [x] ChunkBorders - Press F9 to draw the border of each chunk (very useful when working with Redstone circuitry across chunk borders)
- [x] Roughly Enough Items (REI): view Items and Recipes
- [x] AutoFish: Fish and then AFK
- [x] Hwyla: UI improvement mod aimed at providing block information directly ingame, without the need of opening an UI.
- [x] Vanilla Hammers: Adds 13 New Hammers
- [x] ToroHealth Damage Indicators: show health damage
- [x] Yet Another Grave Stone: RIP
- [x] **[CLient ONLY]** ItemScroller: Scroll to play with your inventory items


### Others

- [x] Extra Bows: Give us more types of bows
- [x] EquipZ:  Armor and weapons with effects
- [x] ExtraDoors: Provide more modern-look doors
- [x] Soul Shards Respawn: Spawner mechanics
- [x] leafmealone: A faster leaf decay mod
