# Deathmatch

[![Latest Version](https://img.shields.io/thunderstore/v/JaredIsCoding/Deathmatch?logo=thunderstore&logoColor=white)](https://thunderstore.io/c/lethal-company/p/JaredIsCoding/Deathmatch)
[![Total Downloads](https://img.shields.io/thunderstore/dt/JaredIsCoding/Deathmatch?logo=thunderstore&logoColor=white)](https://thunderstore.io/c/lethal-company/p/JaredIsCoding/Deathmatch)

A Lethal Company mod for deathmatch! Remove enemies, infinite sprint, infinite ammo, instant respawn, and more.

## Gameplay Modifications

- Order yourself a shotgun in the terminal
- Time of Day clock always visible
- Inverse teleporter is on the ship at the beginning of the game
- Inverse teleporter does not remove player inventory
- Keys are not removed from inventory after use
- Remove inverse teleporter cooldown
- Remove all facility enemies
- Remove beehives
- Infinite quota deadline
- Infinite sprinting
- Infinite shotgun ammo
- Infinite flashlight battery
- Infinite boombox battery

## Recommended Additional Mods

Here's an r2modman profile code for your convenience, if you prefer: ``

- [MoreCompany](https://thunderstore.io/c/lethal-company/p/notnotnotswipez/MoreCompany/) - Put more players in the arena!
- [LethalThings](https://thunderstore.io/c/lethal-company/p/Evaisa/LethalThings/) - Add teleporters in the facility!
- [FasterItemDropship](https://thunderstore.io/c/lethal-company/p/FlipMods/FasterItemDropship/) - Get your shotguns faster!
- [LateCompany](https://thunderstore.io/c/lethal-company/p/anormaltwig/LateCompany/) - Allow players to join late!
- [LC FastStartup](https://thunderstore.io/c/lethal-company/p/flerouwu/LC_FastStartup/) - Quicker game launch!
- [HideModList](https://thunderstore.io/c/lethal-company/p/Sv_Matt/HideModList/) - Hide that pesky mod list popup!
- [AdditionalSuits](https://thunderstore.io/c/lethal-company/p/AlexCodesGames/AdditionalSuits/) - Play with teams, or just colorful suits!

## Suggested Free-for-All Deathmatch Rules

## Suggested Team Deathmatch Rules

## To-Do

- Add built in points tracking
- Add overlay for points display
- Allow configuration of mod adjustments in settings menu

## Code Environment Setup

Want to extend or modify this repository? Here's some steps to get set up.

1. Clone this repository
2. In `...\Deathmatch\Deathmatch`, create a copy of `Deathmatch.csproj.example` named `Deathmatch.csproj`
3. Modify the newly copied file and replace the placeholder directory roots with your relevant file locations
    - `%GAME_LOCATION%` - Where your copy of Lethal Company is installed
    - `%USER%` - Your `C:\Users` directory
4. Install [Evaisa's UnityNetcodePatcher](https://github.com/EvaisaDev/UnityNetcodePatcher)
5. You should now be able to compile the project