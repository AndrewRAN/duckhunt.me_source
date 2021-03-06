---
title: "Список доступных параметров"
date: 2001-01-00T00:00:00+00:00
draft: false

categories: []
tags: []

slug: "bot-settings"

---

Чтобы изменить значение параметра, используйте `dh!settings set <параметр> <значение>`
 
Вы можете просмотреть список изменённых параметров, написав `dh!settings modified`
 
Для установки значения параметра по умолчанию используйте `dh!settings reset <параметр>`

{{< table >}}
|Параметр|Тип значения|Значение по умолчанию|Описание|
|--- |--- |--- |--- |
|announce_level_up|boolean|True|Уведомлять/не уведомлять о повышении/понижении уровня.|
|bang_lag|число с плавающей точкой|0.5|Устанавливает задержку между выстрелом и показом его последствий. Чтобы отключить, установите значение 0.|
|chance_to_kill_on_missed|целое число|5|Устанавливает вероятность попадания в кого-либо при промахе по утке в процентах.|
|clover_max_exp|целое число|10|Устанавливает максимальное количество очков опыта, которое может быть выдано за наличие клевера.|
|clover_min_exp|целое число|1|Устанавливает минимальное количество очков опыта, которое может быть выдано за наличие клевера.|
|delete_commands|boolean|False|Удалять/не удалять сообщения с командами после их выполнения.|
|disable_decoys_when_ducks_are_sleeping|boolean|True|Делать/не делать приманки безполезными, когда утки спят (см. sleeping_ducks_start и sleeping_ducks_stop).|
|duck_frighten_chance|целое число|5|Устанавливает вероятность того, что утка испугается и улетит, когда в неё стреляют, в процентах.|
|ducks_per_day|целое число|48|Устанавливает количество уток, которые будут появляться в канале за день.|
|emoji_used|строка|:duck:|Устанавливает эмодзи, используемое ботом, если значение параметра emoji_ducks равно true.|
|exp_won_per_duck_killed|целое число|10|Устанавливает количество очков опыта, выдаваемое за одну убитую утку.|
|killed_mentions|boolean|True|Упоминать/не упоминать игроков, в которых кто-то попал. Может надоедать, можете его отключить.|
|language|строка|en_EN|Устанавливает язык, используемый ботом. Используйте формат 2-КОД-ЯЗЫКА-ИЗ-ДВУХ-БУКВ_КОД-СТРАНЫ-ИЗ-ДВУХ-БУКВ (fr_FR, hu_HU, en_US и т. д.). Если указанного языка нет в базе, то будет автоматически выставлен английский.|
|mention_in_topscores|boolean|False|Упоминать/не упоминать игроков из топа. Это НЕ влияет на отправку оповещений. Может сломаться, если в топе есть игроки с длинными никами.|
|multiplier_miss_chance|число с плавающей точкой|1|Устанавливает шанс промаха. Чем больше значение данного параметра, тем больше шанс промаха.|
|pm_most_messages|boolean|False|Отправлять/не отправлять некоторые ответы посредством личных сообщений (о перезарядке, связанные с магазином и т. д.).|
|pm_stats|boolean|False|Отправлять/не отправлять ответ на команду dh!stats посредством личных сообщений.|
|pm_top|boolean|False|Отправлять/не отправлять ответ на команду dh!top посредством личных сообщений.|
|prefix|строка|!|Устанавливает префикс, который будет использовать бот. Если команды DuckHunt есть в других ботах, то вы можете изменить префикс. Не влияет на префикс dh!, он всегда будет работать.|
|randomize_mechanical_ducks|целое число|0|Доступно 3 значения. 0 — механические утки отличаются от обычных. 1 — некоторых механических уток можно отличить от обычных, некоторых нет. 2 — механические утки не отличаются от обычных.|
|show_super_ducks_life|boolean|False|Показывать/не показывать количество здоровья суперуток, пока они живы.|
|sleeping_ducks_start|целое число|0|Используется вместе с sleeping_ducks_stop для установки периода времени (в 24-часовом формате), во время которого утки не будут появляться. Параметр ducks_per_day НЕ перестаёт иметь силу.|
|sleeping_ducks_stop|целое число|0|См. параметр sleeping_ducks_start.|
|ducks_chance|целое число|100|Устанавливает вероятность появления обычных уток.|
|super_ducks_chance|целое число|5|Устанавливает вероятность появления суперуток.|
|baby_ducks_chance|целое число|2|Устанавливает вероятность появления утят.|
|mother_of_all_ducks_chance|целое число|1|Устанавливает вероятность появления матери всех уток.|
|super_ducks_exp_multiplier|число с плавающей точкой|1.1|Устанавливает значение в формуле получения опыта за убийство суперутки. Вот формула: округлить(значение параметра exp_won_per_duck_killed * значение параметра super_ducks_exp_multiplier * кол-во жизней у суперутки).|
|super_ducks_maxlife|целое число|7|Устанавливает максимальное возможное кол-во здоровья у суперуток.|
|super_ducks_minlife|целое число|3|Устанавливает минимальное возможное кол-во здоровья у суперуток.|
|tax_on_user_give|целое число|5|Устанавливает комиссию в процентах при передаче опыта с использованием dh!send_exp. Для отключения выставите 0.|
|time_before_ducks_leave|целое число|660|Устанавливает время в секундах, по истечению которого утка уйдёт со скуки.|
|tts_ducks|boolean|False|Пытаться/не пытаться использовать text-to-speech, когда появляется утка. Экспериментальный параметр.|
|user_can_give_exp|boolean|True|Разрешить/не разрешить охотникам использовать dh!send_exp.|
|users_can_find_objects|boolean|True|Разрешить/не разрешить охотникам копаться в кустах.|
{{< /table >}}
