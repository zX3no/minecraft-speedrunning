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

<sup>[Source](piglin_bartering.json)</sup>

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

> TODO: I remember seeing an aggro timer mod but I can't find it.


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

## How to read the source code.

1. Run minecraft 1.16.1 using the vanilla launcher.
2. Install [JDK 8](https://adoptium.net/download/)
3. Open a terminal and run `java -version` to confirm you're on version 8.
4. Download [MCP-Reborn for 1.16.1](https://github.com/Hexeption/MCP-Reborn/releases/download/1.16.1-20200514/MCP-Reborn-1.16.1.zip)
5. Extract into folder and open
6. Shift + right click `Open powershell window here`.
7. `./gradlew setup`

The source code will be in `src/main/java/net/minecraft/`.

---

> TODO: Basic structure, would prefer pages, but can't be bothered setting up a SSG just yet.

## Overworld

### Village

### Shipwrek

### Cave

### Mapless

### Ruined Portals

### Ocean Monument

### Stronghold

Forsen's law

Preemptive nav: https://docs.google.com/document/d/1NEJ_BaQOqyDlt-h2GiUg4zXlqBHv8YfMVdGpQhDLD8U/edit

Calculator: https://github.com/Ninjabrain1/Ninjabrain-Bot/releases

Rings: https://imgur.com/gallery/i3fIanf

## Nether

### Bastion

### Fortress

## End

### One-Cycle

### Zero-Cycle