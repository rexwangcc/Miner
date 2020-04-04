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

## Detailed information for the mods

**Credit: @helgridly**

- **TechReborn** appears to add new items and ores to the world. As far as I can tell this ultimately boils down to more powerful mining tools / weapons but in order to do so it introduces some "energy" mechanics (think batteries and such). The wiki has more details on specifics but no general overview.
https://wiki.techreborn.ovh/doku.php?id=getting_started

- **Simple BC Pipes** appears to help move items around. It's literally pipes. For moving things.
https://www.curseforge.com/minecraft/mc-mods/simplepipes It is a compromise before the BC (BuildCraft) is fully ported to v1.15.2 (https://www.mod-buildcraft.com/pages/roadmap.html). BC is a really complex mod system that can help you basically automate everything you could do in Minecraft. Adding this simple pipe right now can benefit us on things like: I want to send some items from the chest in my place to A's place but I’m lazy, so I throw that in the pipe and it will be transported to A.

- **AppleSkin** exposes a visual indicator of Minecraft's hunger mechanics. It doesn't change them.
https://www.curseforge.com/minecraft/mc-mods/appleskin

- **VoxelMap** provides an extremely detailed world map.
Really obnoxious video review: https://www.youtube.com/watch?v=0zNtL3a79iE

- **LightOverlay** shows how well the world is lit so you know if monsters will spawn.

- **Roughly Enough Items** shows you crafting recipes in-game.
http://www.mc-mod.net/roughly-enough-items-mod/

- **AutoFish** automatically recasts and reels in your fishing rod for you.
https://www.curseforge.com/minecraft/mc-mods/autofish

- **Here's What You're Looking At (HWYLA)** is an overlay that gives you detailed information about what's under your crosshair, for instance showing you the contents of a furnace.
https://www.curseforge.com/minecraft/mc-mods/hwyla/screenshots

- **Vanilla Hammers** adds the "hammer" mining tool, which mines out a 3x3 area in front of you.
https://www.curseforge.com/minecraft/mc-mods/vanilla-hammers

- **ToroHealth** damage indicator adds a health damage visualisation when you hit something, and an indication on your screen of how much health the entity under your crosshair has.
https://www.curseforge.com/minecraft/mc-mods/torohealth-damage-indicators

- **Yet Another Gravestone** saves your items in a chest when you die, so you can go back and retrieve them.

- **Item Scroller** provides shortcuts for item selection so you can easily move things between e.g. your inventory and chests.
https://www.curseforge.com/minecraft/mc-mods/item-scroller

- **Extra Bows** adds more types of bows and arrows.
https://www.curseforge.com/minecraft/mc-mods/extra-bows

- **EquipZ** adds new weapons.
https://www.curseforge.com/minecraft/mc-mods/equipz

- **Extra doors** adds new types of door.
https://www.curseforge.com/minecraft/mc-mods/extradoors

- **Soul Shards** Respawn lets you build your own spawner cages.
https://www.curseforge.com/minecraft/mc-mods/soul-shards-respawn

- **leafmealone** makes leaves decay MUCH faster.
https://www.curseforge.com/minecraft/mc-mods/leaf-me-alone