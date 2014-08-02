---
layout: game
title: "Super Catacombs <small>(In development)</small>"
header: images/header.png
images:
  - images/1.png
  - images/2.png
  - images/3.png
  - images/4.png
  - images/5.png
  - images/6.png
---
## About Super Catacombs ##

*Note: All development of Super Catacombs has been halted and will most likely not be resumed at a later point.
We has some design issues with the game that we couldn't fix so we decided to focus on other projects.*

Super Catacombs is a very minimalistic dungeon crawler/puzzle game for the Nintendo Game Boy.
Your goal is to get to the stairs in each level without being killed by the monsters roaming the catacombs.
You can only take one or two hits so learning each monster's movement pattern is crucial to avoid getting hit.

In its current state Super Catacombs is only a proof of concept, still missing important mechanics, music and sound,
menus, overworld map, animations and proper levels. We hope to continue working on it once we're done with Duck Marines.

## Screenshots ##
<div class="centered-div">
{% for image in page.images %}
<a href="{{ image }}">
	<img src="{{ image }}" width="200" class="game-thumb" />
</a>
{% endfor %}
</div>

## Downloads ##

Super Catacombs is far from finished but you can try the initial prototype made for #GBJAM below:

* [Game Boy rom](https://bitbucket.org/SimonLarsen/tangram-files/downloads/catacomb.gb) <small>(Requires Game Boy emulator or flash cart)</small>
* [Play in browser](http://tangramgames.dk/supercatacombs-online/)
