---
title: "Préférences du bot"
date: 2001-01-00T00:00:00+00:00
draft: false

categories: []
tags: []

slug: "preferences"

---

Pour définir un paramètre, utilisez `dh!settings set <paramètre> <valeur>`

Vous pouvez voir les paramètres ayant étés modifiés avec la commande `dh!settings modified`

Note : Un booléen est un type de variable pouvant être défini par "vrai" ou "faux". Les valeurs "oui" et "non" peuvent aussi être utilisées.

{{< table >}}
|Paramètre|Type|Valeur par défaut|Commentaire|
|--- |--- |--- |--- |
|announce_level_up|booléen|Oui|Activer ou pas les messages de montée de niveau.|
|bang_lag|décimal|0.5|Temps en seconde entre le tir et ce qu'il se passe après. Peut être mis à 0 pour être désactivé.|
|chance_to_kill_on_missed|entier|5|Probabilité en pourcentage qu'un chasseur tue quelqu'un lors d'un tir raté.|
|clover_max_exp|entier|10|Expérience bonus maximale donnée par un trèfle|
|clover_min_exp|entier|1|Expérience bonus minimale donnée par un trèfle|
|delete_commands|booléen|Non|Paramètre anti-spam : supprimer les messages contenant les commandes|
|disable_decoys_when_ducks_are_sleeping|booléen|Oui|Empêche l'utilisation de leurres quand les canards dorment. (Voir les paramètres sleeping_ducks_start et sleeping_ducks_stop)|
|duck_frighten_chance|entier|5|Probabilité qu'un canard s'enfuit lors d'un tir, en pourcentage.|
|ducks_per_day|entier|48|Nombre de canards par jour dans un salon textuel.|
|emoji_ducks|booléen|Oui|Utilise un emoji quand le canard apparaît à la place d'un texte.|
|emoji_used|texte|:duck:|Emoji utilisé si le paramètre emoji_ducks est activé.|
|exp_won_per_duck_killed|entier|10|Points d’expérience gagnés lorsque un chasseur a tué un canard.|
|killed_mentions|booléen|Non|Mentionner ou pas les personnes se faisant tirer dessus par un chasseur.|
|language|texte|en_EN|Langage utilisé, sous le format international de pays (par exemple, fr_FR pour le français de France). Si aucun langage correspondant est trouvé, il sera par défaut en anglais.|
|mention_in_topscores|booléen|Non|Mentionner les chasseurs dans le tableau de score (Cela ne notifiera personne).|
|multiplier_miss_chance|décimal|1|Changer la probabilité pour un chasseur de rater son tir. Plus la valeur est évevée, plus la probabilité de rater est haute.|
|pm_most_messages|booléen|Non|Envoyer les informations non de commandes importantes en message privé (reload, shop...).|
|pm_stats|booléen|Non|Envoyer les statistiques (!duckstats) par message privé.|
|pm_top|booléen|Non|Envoyer le tableau de scores (!top) par message privé.|
|prefix|texte|!|Préfixe utilisé. Si un autre bot utilise le même préfixe que DuckHunt, vous pouvez le changer. Peu importe le paramètre, le bot répondra tout le temps au préfixe "dh!"|
|randomize_ducks|booléen|Oui|Changer aléatoirement les canard envoyés par textes (Pour le paramètre emoji_ducks = non)|
|randomize_mechanical_ducks|entier|0|Paramètre à trois niveaux. À 0, un canard mécanique ressemblera et aura un cri pré défini. Si défini à 1, le cri du canard mécanique sera comme un canard normal. À 2, le canard mécanique sera exactement comme un canard normal.|
|show_super_ducks_life|booléen|Non|Affiche la vie des super canards lorsqu'ils ne sont pas tués|
|sleeping_ducks_start|entier|0|À utiliser avec "sleeping_ducks_stop", pour définir une intervalle avec le système horaire militaire (format 24) où les canard dormiront, et donc n’apparaîtront pas. Le paramètre "ducks_per_day" sera toujours pris en compte. Important : L'heure utilisé par le bot est en UTC+0. Tapez la commande dh!time pour voir l'heure actuelle pour le bot.|
|sleeping_ducks_stop|entier|0|Voir le paramètre "sleeping_ducks_start".|
|super_ducks_chance|entier|5|Probabilité qu'un nouveau canard soit un super canard.|
|super_ducks_exp_multiplier|décimal|1.1|L'experience gagnée quand un super canard est tué se calcule par la formule "arrondi(exp_won_per_duck_killed * super_ducks_exp_multiplier * vie_du_supercanard)" Voir aussi le paramètre "exp_won_per_duck_killed" : expérience gagnée lorsque un chasseur tue un canard.|
|super_ducks_maxlife|entier|7|Vie maximale d'un super canard.|
|super_ducks_minlife|entier|3|Vie minimale d'un super canard.|
|tax_on_user_give|entier|5|Pourcentage de points d’expérience supprimé lorsque un joueur en envoi avec la commande "dh!send_exp". Mettre à 0 pour désactiver la taxe.|
|time_before_ducks_leave|entier|660|Temps avant qu'un canard parte s'il n'est pas tué.|
|tts_ducks|booléen|Non|Essaye de parler avec la commande /tts quand un canard apparaît. Paramètre expérimental.|
|user_can_give_exp|booléen|Oui|Défini si la commande "dh!send_exp", qui permet d'envoyer des points d'expérience, est autorisée.|
|users_can_find_objects|booléen|Oui|Défini si des objets peuvent être trouvés aléatoirement dans un buisson quand un chasseur tue un canard|
{{< /table >}}
