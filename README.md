# gamemode-switcher
This Minecraft Skript file introduces an easy Gamemode Switcher to your server, adding 5 new commands.

## Introduction
As of Minecraft version 17w45a, the ability to use abbreviations and numeric IDs for switching gamemodes within the game has been removed. Despite the fact that the GUI Gamemode Switcher was later introduced (accessible via F3+F4), the ability to use commands such as `/gamemode 0` has greatly been missed. This Skript file introduces an abbreviated version of `/gamemode`, and some commands which originate from the Essentials Plugin.

## How to Install
### Recommended Specifications
**Minecraft Skript:** Version 2.6.4 or later.
_To install Skript, check [this article](https://dev.bukkit.org/projects/skript#:~:text=To%20install%20or%20update%20Skript,files%20and%20some%20example%20scripts.)._

### Instructions
1. Download the file "gamemode-switcher.sk"
2. Place it in your "scripts" folder (located in your server files in `~\plugins\Skript\`)
3. Join into your Minecraft Server and use the command `/sk reload gamemode-switcher.sk`. Alternatively, you can restart your server.

## Commands (and their usage)
_For legacy commands, and changes please check the [Releases](https://github.com/fleri2016/gamemode-switcher/releases) Page of this Repository._

- **/gm <0-3> \[\<player\>\]** - Switches your gamemode using an abbreviated version of `/gamemode`, whilst using 0-3 instead of the gamemode names. When `[<player>]` is specified, you can switch the gamemode of another online player.
- **/gms \[\<player\>\]** - Switches your gamemode to survival. When `[<player>]` is specified, you can switch the gamemode of another online player.
- **/gmc \[\<player\>\]** - Switches your gamemode to creative. When `[<player>]` is specified, you can switch the gamemode of another online player.
- **/gma \[\<player\>\]** - Switches your gamemode to adventure. When `[<player>]` is specified, you can switch the gamemode of another online player.
- **/gmsp \[\<player\>\]** - Switches your gamemode to spectator. When `[<player>]` is specified, you can switch the gamemode of another online player.
