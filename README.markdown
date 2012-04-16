Call of Cthulhu LCG plugin for OCTGN
====================================

Call of Cthulhu is a "Live Card Game" published by Fantasy Flight Games which tries to capture the feeling and theme of the Lovecraftian Mythos.
Find more details about it [on the official page](http://www.fantasyflightgames.com/edge_minisite.asp?eidm=11) or even at [Board Game Geek](http://boardgamegeek.com/boardgame/40270/call-of-cthulhu-the-card-game).

[![](http://i.imgur.com/waxe6l.jpg)](http://www.commissionedcomic.com/?p=4555)

Changelog
---------

### 1.0.9

* Removed unused backgrounds to reduce the game def size
* Fixed a few actions not working in OCTGN 3.0.1.0

### 1.0.8

* Fixed the game complaining about Char to String errors

### 1.0.7

* Fixed bug where using the "drain" function on a drained domain would not refresh it. Renamed "Drain Domain" to "Drain/Refresh" Domain
* Fixed bug where your stories counters in the tab summary would show a question mark instead of the number.
* Play Card is now the default hand group action. I.e. double-click on a card will play it.
* Changed the text in "refresh all" to mention "all cards" rather than "all characters".
* Fixed a bug where playing a resource card as the second player in an inverted table whould play it in other side. Now it will play it at the appropriate location according to the player's location in an inverted table.
* RestoreAll now turns straight all the cards owned by the player except tokens, resources and stories.
* Cards played as Resources now get a special marker which you can use to filter them out when going through the cards in the table. Playing a resource now also mentions only the type of the resource, instead of the card name which is irrelevant.
* Cards turned sane are now automatically exhausted.
* Removed highlighting from committing or exchausting. They are superfluous since cards are turned 90 degrees anyway.
* Made draining a domain add a special token on top of it instead of adding a highlight to be more thematic. The token will be removed during the table refresh all function or with a second drain action if necessary.
* Modified the "Add Domain" function. Now it is "Setup Starting Domains" and it immediately places 3 domain cards on your table side to the left.
* Changed some shortcuts to be more consistent. For example, you add markers with Alt+ a button and you remove counter with Alt+Shift+ same button.
