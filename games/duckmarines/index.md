---
layout: game
title: "Duck Marines <small>(In development)</small>"
header: images/header.png
images:
  - images/teaser.png
  - images/duckbeat.png
  - images/leveleditor.png
  - images/vacuum.gif
---
## About Duck Marines ##

Duck Marines is a cross-platform free software PC remake of Sonic Team's [ChuChu Rocket](http://en.wikipedia.org/wiki/ChuChu_Rocket!).

Duck Marines attempts to recreate the magic from the local multiplayer of ChuChu Rocket while adding new elements mini games, a level editor,
colorful pixel art and more.

## Screenshots ##
<div class="centered-div">
{% for image in page.images %}
<a href="{{ image }}">
	<img src="{{ image }}" width="300" class="game-thumb" />
</a>
{% endfor %}
</div>

## Downloads ##

* [LÖVE archive](https://github.com/SimonLarsen/duckmarines/releases/download/v1.0-rc1/duckmarines-1.0-rc1.love) [v1.0 RC1]
* [Source code](https://github.com/SimonLarsen/duckmarines)
* [Music](http://telefuturenow.com/linde-stone-soup/) by Phillip Linde

## License ##

All assets with the exception of all background music are copyright (c) 2013 Tangram Games and are licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

All background music is copyright (c) 2012 Philip Linde and licensed under a
[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International license](http://creativecommons.org/licenses/by-nc-nd/4.0/).

The libraries slam and Tserial are not covered by the Duck Marines license.
Please the files of equivalent basename for license information.
All other source code for Duck Marines is licensed under the zlib license.

See [LICENSE.md](https://raw.githubusercontent.com/SimonLarsen/duckmarines/master/LICENSE.md) for more information.
