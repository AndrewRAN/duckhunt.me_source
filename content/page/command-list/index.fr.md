---
title: "Liste des commandes"
date: 2002-01-00T00:00:00+00:00
draft: false

categories: []
tags: []

slug: "liste-commandes"

alert: "Fin traduction requise"
---

Toutes les commandes sont écrites ici avec le préfixe `dh!`.
Vous pouvez aussi utiliser le préfixe réglé sur votre serveur, par défaut `!`, qui peut etre changé par vos administrateurs de serveur.
 
Les arguments des commandes sont spécifiés entre `<>` si ils sont obligatoires, et entre `[]` si ils sont facultatifs.
C'est juste une indication, il ne faut évidemment pas taper les crochets :)
 
 
Un joueur peut etre spécifié avec son ID, une mention, leur pseudo, ou son nom d'utilisateur et leur #TAG discord.
 
Ci-dessous, vous pouvez trouver deux listes :
*   une pour les commandes accessibles aux joueurs et 
*   une pour les commandes réservées aux administrateurs.
 
 
Pour plus d'informations, vous pouvez consulter la liste des objets du magasin ou des [préférences du bot](https://duckhunt.me/fr/parametres/).

## Commandes pour les joueurs

{{< table >}}
|Commande|Description|
|--- |--- |
|dh!bang|Commande utilisée pour tirer sur un canard.|
|dh!reload|Recharge ou décoince votre arme. Il doit vous rester des chargeurs si vous voulez recharger. Ils sont donnés gratuitement chaque jour (voir dh!freetime), et vous pouvez aussi les acheter dans le shop.|
|dh!help|Vous envoie le message d'aide|
|dh!wiki|Vous donne le lien de ce site web|
|dh!stats [player]|Récupère vos statistiques, ou celles d'un autre joueur|
|dh!shop <item number> [argument]|Command used to buy things from the shop. For more information, see the Shop Items page. You can also use the dh!shop list command to show the link to the shop items page.|
|dh!top --sort-by [time/missed/exp/killed]|See the best players on the channel. You can choose a criteria to sort by if needed.|
|dh!send_exp <player> <amount>|Sends some of your experience points to another player on the game. A tax can be applied to the transfer, dependings on the server settings.|
|dh!freetime|This command willl display the time left to wait for the free giveback of chargers and weapons.|
|dh!settings list|Lists every possible setting that can be modified.|
|dh!settings modified|See settings that were modified and their new value.|
|dh!ping|Pings the bot to see if it is online.|
|dh!uptime|Shows the bot's uptime.|
{{< /table >}}


## Commandes Administrateur

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
