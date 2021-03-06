# y_commands

The most fully featured command processor for SA:MP.  Includes:

* Full internationalisation - type commands in any language.
* Native permissions support, dynamically change who can use a command at any time with no code required within the command.
* y_groups support to further extend the permissions system to teams etc.
* Integrated help, so that each command can easilly have its help text defined along side its code.
* Multiple other checks for hidden/disabled/errored commands.
* Change the command prefix from `/`.
* `OnPlayerCommandReceived` and `OnPlayerCommandPerformed`.
* Rename commands at a per-player level (e.g. to have the same command in multiple languages).
* Alternate names for the same command.
* Multi-script (filterscript) support.
* `Command()` and `PlayerCommand()` Iterators to use with `foreach`.


[![sampctl](https://shields.southcla.ws/badge/sampctl-y_commands-2f2f2f.svg?style=for-the-badge)](https://github.com/YSI-Visual/y_commands)

## Installation

To install just this one library:

```bash
sampctl package install YSI-Visual/y_commands
```

Include in your code and begin using the library:

```pawn
#include <YSI-Visual/y_commands>
```

## Documentation

* [Quick Start](y_commands/quick-start.md) - One very simple example of getting started with this library.
* [Features](y_commands/features.md) - More features and examples.
* [FAQs](y_commands/faqs.md) - Frequently Asked Questions, including errors and solutions.
* [API](y_commands/api.md) - Full list of all functions and their meaning.
* [Internal](y_commands/internal.md) - Internal developer documentation for the system.

## Testing

To test, simply run the package:

```bash
sampctl package run
```

# YSI

## General Information

* [Installation](../installation.md)
* [Troubleshooting](../troubleshooting.md)
* [YSI_COMPATIBILTY_MODE](../YSI_COMPATIBILTY_MODE.md)
* [What does YSI stand for?](../acronym.md)

## Libraries

### Coding

PAWN scripting improvements (i.e. new language features).

* [y_functional](https://github.com/YSI-Coding/y_functional)
* [y_hooks](https://github.com/YSI-Coding/y_hooks)
* [y_inline](https://github.com/YSI-Coding/y_inline)
* [y_malloc](https://github.com/YSI-Coding/y_malloc)
* [y_remote](https://github.com/YSI-Coding/y_remote)
* [y_stringhash](https://github.com/YSI-Coding/y_stringhash)
* [y_timers](https://github.com/YSI-Coding/y_timers)
* [y_unique](https://github.com/YSI-Coding/y_unique)
* [y_va](https://github.com/YSI-Coding/y_va)

### Core

Core libraries, used almost everywhere else.

* [y_als](https://github.com/YSI-Core/y_als)
* [y_cell](https://github.com/YSI-Core/y_cell)
* [y_debug](https://github.com/YSI-Core/y_debug)
* [y_master](https://github.com/YSI-Core/y_master)
* [y_profiling](https://github.com/YSI-Core/y_profiling)
* [y_testing](https://github.com/YSI-Core/y_testing)
* [y_utils](https://github.com/YSI-Core/y_utils)

### Data

Data structures and algorithms.

* [y_bintree](https://github.com/YSI-Data/y_bintree)
* [y_bit](https://github.com/YSI-Data/y_bit)
* [y_iterate](https://github.com/YSI-Data/y_iterate)
* [y_hashmap](https://github.com/YSI-Data/y_hashmap)
* [y_jaggedarray](https://github.com/YSI-Data/y_jaggedarray)
* [y_playerarray](https://github.com/YSI-Data/y_playerarray)
* [y_playerset](https://github.com/YSI-Data/y_playerset)
* [y_sortedarray](https://github.com/YSI-Data/y_sortedarray)
* [y_sparsearray](https://github.com/YSI-Data/y_sparsearray)

### Extra

Optional features.

* [y_extra](https://github.com/YSI-Extra/y_extra)
* [y_files](https://github.com/YSI-Extra/y_files)
* [y_streamer_plugin](https://github.com/YSI-Extra/y_streamer_plugin)

### Game

Libraries that provide information about the game.

* [y_vehicledata](https://github.com/YSI-Game/y_vehicledata)

### Players

Libraries for managing players.

* [y_groups](https://github.com/YSI-Players/y_groups)
* [y_languages](https://github.com/YSI-Players/y_languages)
* [y_text](https://github.com/YSI-Players/y_text)
* [y_users](https://github.com/YSI-Players/y_users)

### Server

Libraries for controlling the server.

* [y_colours](https://github.com/YSI-Server/y_colours)
* [y_flooding](https://github.com/YSI-Server/y_flooding)
* [y_lock](https://github.com/YSI-Server/y_lock)
* [y_punycode](https://github.com/YSI-Server/y_punycode)
* [y_scriptinit](https://github.com/YSI-Server/y_scriptinit)
* [y_stringise](https://github.com/YSI-Server/y_stringise)
* [y_td](https://github.com/YSI-Server/y_td)

### Storage

Libraries for interacting with persistent data.

* [y_amx](https://github.com/YSI-Storage/y_amx)
* [y_bitmap](https://github.com/YSI-Storage/y_bitmap)
* [y_ini](https://github.com/YSI-Storage/y_ini)
* [y_php](https://github.com/YSI-Storage/y_php)
* [y_svar](https://github.com/YSI-Storage/y_svar)
* [y_uvar](https://github.com/YSI-Storage/y_uvar)
* [y_xml](https://github.com/YSI-Storage/y_xml)

### Visual

Libraries that have in-game visible effects.

* [y_areas](https://github.com/YSI-Visual/y_areas)
* [y_classes](https://github.com/YSI-Visual/y_classes)
* [y_commands](https://github.com/YSI-Visual/y_commands)
* [y_dialog](https://github.com/YSI-Visual/y_dialog)
* [y_loader](https://github.com/YSI-Visual/y_loader)
* [y_properties](https://github.com/YSI-Visual/y_properties)
* [y_races](https://github.com/YSI-Visual/y_races)
* [y_zonenames](https://github.com/YSI-Visual/y_zonenames)
* [y_zonepulse](https://github.com/YSI-Visual/y_zonepulse)

