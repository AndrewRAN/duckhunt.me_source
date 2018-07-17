---
title: "Duckhunt V3 changelog"
date: 2018-03-14T20:00:00+02:00
draft: false

categories: ['Changelog']
tags: []
---

A lot of things changed, internally and externally, and it's not the end of the changes :).
 
The full changelog is to be seen below. Please, as usual, report any bug you find.

<!--more-->
 
If you want to help me further, there is a few things I'd take help on :

*   Translating the bot (A lot of sentences were added/changed, and the translations aren't complete ATM)
*   Creating artwork for the website: if you have the heart of a graphic designer, and have some free time, please join us!
*   Helping me building a FAQ for the new website. No coding necessary, and any help is welcome!
*   Buy me some tea, and support the development of the bot here : [http://ko-fi.com/duckhunt](http://ko-fi.com/duckhunt "http://ko-fi.com/duckhunt")

If you want to help, support, or have any question regarding the bot, I'm open to PM, and you can post in #support_english on the support server here : [https://discord.gg/G4skWae](https://discord.gg/G4skWae) Now, what's new ?

*   For players:
    *   Events have been added. Check the bot playing status and the !event command. An event is something that happens across every server at once and changes, for the better or the worse, some pre-defined variables (number of ducks, lag, super-ducks life...).
    *   Global emoji support has been added
    *   Hints have been added to answer the most common questions before you even think of them
    *   Commands are now case insensitive: !BANg or !ReLoAD now work too
    *   You don't have to enter the shop number anymore: !shop charger, !shop bullet... works too.
    *   Some easter eggs have been added
    *   More statistics are now collected to be used later
    *   A new website is available at https://duckhunt.me. It contains the updated command list and settings list, plus a brand-new FAQ.
*   For server admins:
    *   The coin command allows the user to choose the life and the super-duck status of a spawned duck
    *   Duckplanning has been updated to show the current ducks in the channel
    *   New setup command to replace the !claimserver one (!setup)
    *   Users with the administrator permission are now admins by default
    *   global_scores has been removed, as it was rarely used
    *   settings list and setting modified now show the settings in-chat
    *   send_exp is now taxed by default
    *   emoji_ducks is now enabled by default
*   For developers:
    *   The bot now uses discord.py rewrite
    *   There is no json file anymore (As a result, the bot is faster)
    *   The bot is sharded (Can support more than 2500 servers)
    *   Hastebin support was replaced by long messages support
    *   The ping command is clearer now
    *   Bugs have been added too
*   For self-hosters (if you don't know what that is, you aren't one):
    *   A migration script for the json file has been provided, and the new database scheme will be available soon

With löve, Arthur
