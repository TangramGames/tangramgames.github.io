---
layout: game
title: Duck Marines
header: images/header.png
images:
  - images/teaser.png
  - images/duckbeat.png
  - images/leveleditor.png
  - images/vacuum.gif
---
Duck Marines is a cross-platform free software PC remake of Sonic Team's [ChuChu Rocket](http://en.wikipedia.org/wiki/ChuChu_Rocket!).

Duck Marines attempts to recreate the magic from the local multiplayer of ChuChu Rocket while adding new elements like mini games, a level editor,
colorful pixel art and more.

## Screenshots ##

<div class="centered">
{% for image in page.images %}
<a href="{{ image }}">
	<img src="{{ image }}" width="49%" class="thumbnail" />
</a>
{% endfor %}
</div>

## Trailer ##

<iframe width="100%" height="315" src="//www.youtube.com/embed/SAz0BsTSXy4" frameborder="0" allowfullscreen>
</iframe>

## Downloads ##

<iframe src="//itch.io/embed/9383?dark=true" width="552" height="167" frameborder="0">
</iframe>

Also available from [GitHub](https://github.com/SimonLarsen/duckmarines/releases).

### Source code ###

* [GitHub](https://github.com/SimonLarsen/duckmarines)

## How to play ##

The goal of the game is to get as many ducks into the submarine of your color. Gray ducks give you one point, gold ducks give multiple points and pink ducks will trigger an event or mini game.

Guide the ducks towards your submarine by placing arrows on the ground. When walking over an arrow ducks will instead walk in the direction the arrow is pointing.

Beware of the blue predators. Predators love to eat ducks and will kill a large number of your ducks if they reach your submarine. Try instead to guide the predators to the other players' submarines
using your arrows.

### Controls ###

* Controllers: Move cursor with left analog stick. Place arrows with the four face buttons or with the right analog stick.
* Keyboard: Move cursor with arrow keys and place arrow by holding space and pressing a direction.
* Mouse: Move cursor with mouse. Click and drag in a direction to place arrow.

## License ##

All assets with the exception of all background music are copyright (c) 2013 Tangram Games and are licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

All background music is copyright (c) 2012 Philip Linde and licensed under a
[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International license](http://creativecommons.org/licenses/by-nc-nd/4.0/).

The libraries slam and Tserial are not covered by the Duck Marines license.
Please the files of equivalent basename for license information.
All other source code for Duck Marines is licensed under the zlib license.

See [LICENSE.md](https://raw.githubusercontent.com/SimonLarsen/duckmarines/master/LICENSE.md) for more information.
