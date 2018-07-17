---
title: "Command list"
date: 2002-01-00T00:00:00+00:00
draft: false

categories: []
tags: []
---
All commands are written with the universal `dh!` prefix.

Alternatively, you can use the prefix set on your server too, (the default is `!`) which can be changed by server owners.
 
Arguments to the commands listed below are specified with `<>` if they must be specified, and with `[]` otherwise.
Please don’t type the brackets on commands, thanks :)
 
You can pass a player as an argument using his/her User ID, a mention, their nickname, or their username and Discord tag.
   
   
Below, you'll find an overview of general commands for playing DuckHunt (Player Commands)
as well as commands for setting up and managing the DuckHunt bot on your server (Administrator Commands).
 
For further info about specific commands, see the list of [shop items](https://duckhunt.me/shop-items/) or the [bot settings](https://duckhunt.me/bot-settings/).

## Player commands

{{< table >}}
|Command|Description|
|--- |--- |
|dh!bang|Command used to shoot a duck. Don't forget that sometimes, mistakes happen and you can miss the ducks... Or worse.|
|dh!reload|Reloads or unjams your weapon. You must have chargers left if you want to reload. They are given back for free everyday (check dh!freetime command), but you can also buy them in the shop.|
|dh!help|Sends you the help message.|
|dh!wiki|Sends the link to this website.|
|dh!stats [player]|Gets your or another player hunting statistics.|
|dh!shop <item number> [argument]|Command used to buy things from the shop. For more information, see the Shop Items page. You can also use the dh!shop list command to show the link to the shop items page.|
|dh!top --sort-by [time/missed/exp/killed]|See the best players on the channel. You can choose a criteria to sort by if needed.|
|dh!send_exp <player> <amount>|Sends some of your experience points to another player on the game. A tax can be applied to the transfer, dependings on the server settings.|
|dh!freetime|This command willl display the time left to wait for the free giveback of chargers and weapons.|
|dh!settings list|Lists every possible setting that can be modified.|
|dh!settings modified|See settings that were modified and their new value.|
|dh!ping|Pings the bot to see if it is online.|
|dh!uptime|Shows the bot's uptime.|
{{< /table >}}

## Administrator commands

{{< table >}}
|Command|Description|
|--- |--- |
|dh!setup|This is the first command you should use after inviting DuckHunt to a server. It create the server settings and have a configuration wizard to make it easier for you.|
|dh!add_channel|After using dh!setup, use this command on the channels you want ducks to appear in.|
|dh!del_channel|This disables a channel added by dh!add_channel.|
|dh!del_user|This removes an user from the database.|
|dh!del_user_id|This removes an user from the database. This comment is meant to be used on players that left the server.|
|dh!add_admin|Set another server administrator as an admin. Note that users with the Administrator permission in discord are considered Administrators too.|
|dh!del_admin|Deletes a server admin from the admins list.|
|dh!coin [--super-duck] [--life <life-points>]|Forces a duck to spawn.|
|dh!ducks|Shows the number of ducks that will spawn today, and the list of ducks that are on the channel. It can be considered as a cheat.|
|dh!give_exp <player> <amount>|Gives a player some exp points. This is a cheat, not to be confused with dh!send_exp.|
|dh!settings set <parameter> <value>|Modify server settings. You can go to the Bot Settings page to learn more about this command.|
|dh!settings reset <parameter>|Resets a parameter to the default value. Use this command and not dh!settings set to reset parameters, as it won't cause issues with bot upgrades.|
|dh!game_ban <player>|Bans a player from the game. You can't ban admins, so please don't try :)|
|dh!game_unban <player>|Unbans a player from the game. They will be able to play again.|
|dh!remove_all_scores_and_stats_on_this_channel|Deletes a channel scores and stats. Please be sure you really want to do this. You cannot undo this.|
{{< /table >}}



