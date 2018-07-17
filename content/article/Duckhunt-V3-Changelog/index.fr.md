---
title: "Changements dans DuckhuntV3"
date: 2018-03-14T20:00:00+02:00
draft: false

categories: ['Changelog']
tags: []
---

Beaucoup de choses ont changé, en interne et en externe, et c'est pas fini!
 
Le journal des modifications complet est visible ci-dessous. 
<!--more-->

Veuillez, comme d'habitude, rapporter tout bug que vous pourrez trouver, cela me ferait extrêmement plaisir. Si vous voulez m'aider davantage, il y a certaines choses que j'accepterais volontiers:

*   Traduction du bot (beaucoup de phrases ont été ajoutées/modifiées, et les traductions ne sont pas complètes actuellement)
*   Création d'illustrations pour le site web: si vous avez le cœur d'un graphiste, et que vous avez du temps libre, n'hésitez pas à nous rejoindre!
*   M'aider à construire une FAQ pour le nouveau site web. Aucun codage nécessaire, et toute aide est la bienvenue!
*   Achetez-moi du thé, et soutenez le développement du bot ici: [http://ko-fi.com/duckhunt](http://ko-fi.com/duckhunt)

Si vous voulez aider, soutenir, ou si vous avez des questions concernant le bot, je suis ouvert à PM, et vous pouvez poster dans #support_english sur le serveur de support ici: [https://discord.gg/G4skWae](https://discord.gg/G4skWae) Maintenant, quoi de neuf?

*   Pour les joueurs:
    *   Des événements ont été ajoutés. Vérifiez le statut "joue à..." du bot et la commande !event. Un événement est quelque chose qui se produit sur chaque serveur à la fois et qui modifie, pour le meilleur ou pour le pire, certaines variables prédéfinies (nombre de canards, le retard d'affichage des résultats de tir, la vie des super-canards...).
    *   Ajout d'émojis globaux
    *   Des conseils ont été ajoutés pour répondre aux questions les plus courantes avant même que vous n'y pensiez.
    *   Les commandes sont maintenant insensibles à la casse: taper !bang, !bAnG ou !Bang revient au même
    *   Vous n'avez plus besoin d'entrer le numéro du magasin dans la commande shop: !shop charger, !shop bullet... fonctionnent aussi.
    *   Des fonction cachées ont été ajoutées, à vous de les trouver.
    *   D'autres statistiques sont maintenant collectées sur les chasseurs pour être utilisées ultérieurement dans le duckstats
    *   Un nouveau site Web est disponible à https://duckhunt.me. Il contient la liste des commandes et des paramètres mis à jour, ainsi qu'une toute nouvelle FAQ.
*   Pour les administrateurs de serveur:
    *   La commande !coin permet à l'utilisateur de la quantité de vie et le type de canard à faire apparaître.
    *   La commande !duckplanning à été mise à jour pour afficher les canards présents dans le channel, en plus du nombre de canards prévus
    *   Une nouvelle commande à été créée pour remplacer la commande !claimserver : !setup
    *   Les utilisateurs avec la permission "Administrator" dans discord sont considérés comme administrateurs pour le bot
    *   Le paramètre global_scores à été supprimé, car il n'était que peu utilisé et imposait une forte complexité dans le code
    *   La liste des paramétrés modifiés est maintenant affichée directement dans le chat, tout comme la liste de tous les paramètres.
    *   La commande send_exp est maintenant taxée par défaut.
*   Pour les développeurs:
    *   Le bot utilise maintenant discord.py version rewrite
    *   Il n' y a plus de fichier json (Le bot est plus rapide)
    *   Le bot est shardé (Il peut supporter plus de 2500 serveurs)
    *   Le support d'Hastebin a été remplacé par le support des messages alongés
    *   La commande ping est maintenant plus claire
    *   Quelques bugs ont été ajoutés
*   Pour les selfhosters (si vous ne savez pas ce que c'est, vous n'en êtes pas un):
    *   Un script de migration pour le fichier json a été fourni, et le nouveau schéma de la base de données sera bientôt disponible.

Arthur
