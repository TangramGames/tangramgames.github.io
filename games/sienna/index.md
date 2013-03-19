---
layout: game
title: "Sienna"
header: images/header.png
images:
  - images/1.png
  - images/2.png
  - images/3.png
---
## About Sienna ##
**Sienna** is a simple, albeit frustrating, one-button platformer.

## Screenshots ##
{% for image in page.images %}
<a href="{{ image }}">
	<img src="{{ image }}" width="200" class="game-thumb" />
</a>
{% endfor %}

## Gameplay video ##

<iframe width="620" height="300" src="http://www.youtube.com/embed/EZF071lxkwM" frameborder="0">
</iframe>

## Downloads ##

* [Windows binary](https://github.com/downloads/SimonLarsen/sienna/sienna-win-x86.zip) \[Win x86\]
* [LÖVE package](https://github.com/downloads/SimonLarsen/sienna/sienna.love) \[Win/Linux/OS X\] (requires [LÖVE](http://love2d.org/))
* [Source code](http://github.com/SimonLarsen/sienna) \[GitHub\] (ZLIB licensed)

## How to play ##

* Press **space** to jump or wall jump when touching a wall. The longer you hold the button the higher you jump. It will often be necessary to press the button for only a splitsecond.
* Press **R** to restart from last checkpoint (counts as a death).
* Press **return** to restart from the beginning of the level.
* Oh, and the **blue orbs** are checkpoints. You're gonna need those.
* That and patience. Lots of patience.

## Licence / credits ##

Sienna uses the LÖVE framework licensed under the terms of the ZLIB licence. See [https://love2d.org/wiki/License](https://love2d.org/wiki/License) for more information.

The background music is 'A Scent of Europe' by [Rugar](http://www.8bitpeoples.com/artist/rugar) and is licensed under the [CC BY-NC-ND 3.0](http://creativecommons.org/licenses/by-nc-nd/3.0/) license.

All other assets (sprites, textures, sound effects etc.) are licensed under the [CC BY-NC 3.0](http://creativecommons.org/licenses/by-nc/3.0/) licence.

All source code for Sienna with the exception of the modules TSerial.lua, slam.lua, and AdvTiledLoader are licensed under the [ZLIB](https://github.com/SimonLarsen/sienna/blob/master/LICENCE.txt) license.
