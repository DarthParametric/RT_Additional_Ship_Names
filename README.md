# Additional Ship Names
A mod for Owlcat's Rogue Trader cRPG. Adds additional random names for the player's ship in the character creator.

## Overview
This mod expands the available pool of randomly generated names for the player's ship in the character creator. This mod adds a number of additional names taken from/inspired by the tabletop Rogue Trader material by [Fantasy Flight](https://www.fantasyflightgames.com) as well as various suitably grimdark pseudo-Latin names. This results in 100 names vs 30 vanilla.

## Installation
This is an Owlmod, made using the Unity template supplied by Owlcat. Currently the game has a bug that prevents Owlmods from working. To fix this, you ***must*** install the Unity Mod Manager-based mod [MicroPatches](https://github.com/microsoftenator2022/MicroPatches/releases) by microsoftenator2022. You can install it manually or via [ModFinder](https://www.nexusmods.com/warhammer40kroguetrader/mods/146).

To install this mod, first make sure you have run the game at least once. Download the archive and extract it into:

%LocalAppData%Low\Owlcat Games\Warhammer 40000 Rogue Trader\Modifications\
Each Owlmod needs to be in its own sub-folder in the Modifications folder.

Afterwards, you need to edit OwlcatModificationManagerSettings.json in the base Warhammer 40000 Rogue Trader folder in a text editor (Notepad++ recommended). It should look something like this:

```
{
"$id": "1",
"SourceDirectories": [],
"EnabledModifications": ["DPAdditionalShipNames"],
"ActiveModifications": ["DPAdditionalShipNames"],
"DisabledModifications": []
}
```

If you have other mods, list them in quotes separated by commas. For example:

```
"EnabledModifications": ["DPAdditionalShipNames", "ModName2", "ModName3"],
"ActiveModifications": ["DPAdditionalShipNames", "ModName2", "ModName3"],
```

You can move individual mods from the ActiveModifications section to the DisabledModifications section if you want to disable them without physically removing them.

Alternatively, use [ModFinder](https://www.nexusmods.com/warhammer40kroguetrader/mods/146) to install the mod.

It should be fine to install the mod in an existing game at any point, although obviously it's primarily intended for new games.

## Known Issues
This mod replaces the vanilla localisation string for the player ship names. As such, it is not compatible with any other mod that also replaces the same string. GUID: `d79789cb-a035-4a4c-9551-adf8633cad4d`.

Currently the mod only replaces the names for the English localisation. Other languages will continue to use the vanilla set of names. If anyone wants to contribute localised versions in another language, let me know.

## Acknowledgements
Many thanks to the modders on the Owlcat Dicord, but particularly microsoftenator2022 and Kurufinve.
