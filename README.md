# Minecraft Speedrunning 1.16.1 Random Seed Glitchless

## Piglins

### Bartering

After dropping a gold ingot to a piglin, the piglin will examin it for 6 seconds.
It will then drop a random item from the drop table.

| Item given                                    | Quantity | Chance          | Weight |
|-----------------------------------------------|----------|-----------------|--------|
| Enchanted Book with Soul Speed (random level) | 1        | 5⁄423 (~1.18%)  | 5      |
| Iron Boots with Soul Speed (random level)     | 1        | 8⁄423 (~1.89%)  | 8      |
| Iron Nugget                                   | 9–36     | 10⁄423 (~2.36%) | 10     |
| Splash Potion of Fire Resistance              | 1        | "               | "      |
| Potion of Fire Resistance                     | 1        | "               | "      |
| Nether Quartz                                 | 8–16     | 20⁄423 (~4.73%) | 20     |
| Glowstone Dust                                | 5–12     | "               | "      |
| Magma Cream                                   | 2–6      | "               | "      |
| Ender Pearl                                   | 4–8      | "               | "      |
| String                                        | 8–24     | "               | "      |
| Fire Charge                                   | 1–5      | 40⁄423 (~9.46%) | 40     |
| Gravel                                        | 8–16     | "               | "      |
| Leather                                       | 4–10     | "               | "      |
| Nether Brick                                  | 4–16     | "               | "      |
| Obsidian                                      | 1        | "               | "      |
| Crying Obsidian                               | 1–3      | "               | "      |
| Soul Sand                                     | 4–16     | "               | "      |

<sup>[Bartering - Minecraft Wiki](https://minecraft.fandom.com/wiki/Bartering?oldid=1626556)</sup>

### Aggravation

Piglins will become aggravated for the following reasons:

#### Player is not wearing any gold-armor
- 15 block radius range from the player
- Requires line of sight
- Light aggravation
- Can be de-aggravated by putting on gold-armor, losing line of sight
- Can be distracted with gold
- Will lose aggrevation in x seconds

#### Player has broken a chest or gold block
- 16 block radius range from the player
- Does not require line of sight
- Medium aggravation
- Can be distracted with gold
- Will lose aggrevation in x seconds
- If a piglin was already aggrevated by not wearing gold-armor, their aggrevation state will not be upgraded to medium.

#### Player has damaged a piglin
- All piglins in a 16 block radius range of the damaged piglin will gain medium aggravation
- Heavy aggravation
- Cannot be bartered with or distracted with gold.
- Will lose aggrevation in x seconds.

> TODO: I remember seeing an aggro timer mod but I can't find it. 😢


### Training maps

- Bastion - [Llama's Bastion Practice](https://github.com/LlamaPag/bastion/releases)

- End - [Ryguy2k4's End Practice](https://github.com/ryguy2k4/ryguy2k4endpractice/releases)

- Overworld - [OW Practice by 7rowl](https://github.com/7rowl/OWPractice/releases)

- Portal - [Portal Practice Map by ItzToxic & Semperzz](https://github.com/Semperzz/Portal-Practice/releases)


### Mods

Automatic Installer for mods - [ModCheck by RedLime](https://github.com/RedLime/ModCheck/releases)

- Performance/Fixes
    - AntiResourceLoad
    - BiomeLocalThreadFix
    - LazyDFU
    - Lazystronghold
    - Sodium 1.16.1
    - Lithium 1.16.1 Backport
    - Starlight
    - Voyager
- Speedrunning
    - Atum
    - World Preview
    - Fast Reset
- Multiplayer
    - Force Port Mod
- Debug/Testing
    - Carpet
    - MiniHub
    - Tweakeroo

## How to read the source code

1. Run minecraft 1.16.1 using the vanilla launcher.
2. Install [JDK 8](https://adoptium.net/download/)
3. Open a terminal and run `java -version` to confirm you're on version 8.
4. Download [MCP-Reborn for 1.16.1](https://github.com/Hexeption/MCP-Reborn/releases/download/1.16.1-20200514/MCP-Reborn-1.16.1.zip)
5. Extract into folder and open
6. Shift + right click `Open powershell window here`.
7. `./gradlew setup`

The source code will be in `src/main/java/net/minecraft/`.

## How to find loot tables

1. Install 7zip.
2. Run 7zip and navigate to `C:\Users\<user_name>\AppData\Roaming\.minecraft\versions\1.16.1\`
3. Open `1.16.1.jar`
4. Navigate to `data/minecraft/loot_tables`
5. Open any of the `.json` files or drag and drop any file/folder.

They are also avaliable on this repository in [loot tables](/loot_tables/).

## Divine Travel

https://www.youtube.com/watch?v=IKo-jrZSgWU
https://www.youtube.com/watch?v=SXem01c44-I

---

Mega Doc, mostly covers the speedrun rather than more specific mechanics.
https://docs.google.com/document/d/1zDC0n38EhvcMaXVFVeZwONszmdXonXlFO1rBXqvhxE4/edit#heading=h.s2x5zxnc4jn3


---

> TODO: Basic structure, would prefer pages, but can't be bothered setting up a SSG just yet.

# Mechanics

## Perl Hang

## Blaze Bed

## Hunger Reset

# Overworld

## Lava

https://minecraft.fandom.com/wiki/Lava?oldid=1950804

Lava replaces air blocks generated in caves and ravines between y 1-10.
Lava does not replace air blocks inside mineshafts, dungeons or strongholds.
This is why mineshafts often lack the lava you might expect.

## Structures

> I'll want the loot tables for every structure. So it's clear what can be worth going to.
> Basic structure should be: Biomes, use in a speedrun, loot table.

### Lava Lake (Lava Pool)

Lava lakes can generate in any biome at any level.

They are easiest to find in flat biomes such as desert or plains.

<sup>https://minecraft.fandom.com/wiki/Lava_lake</sup>

### Village

### Ruined Portals

### Stronghold

Forsen's law

Preemptive nav: https://docs.google.com/document/d/1NEJ_BaQOqyDlt-h2GiUg4zXlqBHv8YfMVdGpQhDLD8U/edit

Calculator: https://github.com/Ninjabrain1/Ninjabrain-Bot/releases

Rings: https://imgur.com/gallery/i3fIanf

### Buried Treasure (Mapless)

### Pillager Outpost

### Jungle Temple

### Swamp Hut

### Woodland Mansion


As of `v1.11` Lava generates in woodland mansions: two blocks of lava generate in the "blacksmith room", and 25 blocks of lava generate in a secret "lava room".

Source: https://minecraft.fandom.com/wiki/Lava?oldid=1950804



### Shipwrek

### Ocean Monument

### Ocean Ruins

## Caves

Lava Dowsing:
https://www.youtube.com/watch?v=SzNbVxDj-do
https://www.youtube.com/watch?v=rCzqTc6Tvt0




# Nether

## Bastion

## Fortress

# End

## One-Cycle

## Zero-Cycle