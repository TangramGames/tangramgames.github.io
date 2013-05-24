---
layout: game
title: "Mr. Rescue"
header: images/header.png
images:
  - images/1.png
  - images/2.png
  - images/3.png
  - images/4.png
  - images/5.png
  - images/6.png
---
## About Mr. Rescue ##
Mr. Rescue is an arcade styled 2d action game centered around evacuating civilians from burning buildings.

The game features fast paced fire extinguishing action, intense boss battles,
a catchy soundtrack and lots of throwing people around in pseudo-randomly generated buildings.

As of version 1.02 we have added XBox 360 controller support and fullscreen modes.

## Screenshots ##
<div style="text-align: center">
{% for image in page.images %}
<a href="{{ image }}">
	<img src="{{ image }}" width="200" class="game-thumb" />
</a>
{% endfor %}
</div>

## Gameplay video ##

<iframe width="620" height="300" src="http://www.youtube.com/embed/5k7ctkHAURw" frameborder="0">
</iframe>

## Downloads ##

### Windows ###

* [**32 bit binary**](https://bitbucket.org/SimonLarsen/tangram-files/downloads/mrrescue-1.02-win-x86.zip) 1.02
* [**64 bit binary**](https://bitbucket.org/SimonLarsen/tangram-files/downloads/mrrescue-1.02-win-x64.zip) 1.02

### Mac OS X ###

* [**Universal .app**](https://bitbucket.org/SimonLarsen/tangram-files/downloads/mrrescue-1.02.app.zip) 1.02

### Linux / Mac OS X ###

First go get the awesome [LÖVE framework](http://love2d.org/) (it only takes a second), then download
the LÖVE archive below.

* [**LÖVE archive**](https://bitbucket.org/SimonLarsen/tangram-files/downloads/mrrescue-1.02-love.zip) 1.02

### Source code ###

The zlib'ed source code is available on [GitHub](https://github.com/SimonLarsen/mrrescue).

### Soundtrack ###

You can download the soundtrack on [Bandcamp](http://simonlarsen.bandcamp.com/).

## How to play ##

We highly recommend checking out the ingame how-to but here's the basics:

* Your job is to rescue civilians from a burning building.
* You rescue people by picking them up and throwing them out the window.
* Equipped with a water gun you must fight your way through flames and fire sprites but remember: your job is to rescue people!
* When being near fire your suit will accumulate heat. Collect coolants to keep it from overheating.
* You water tank only has limited capacity. Emptying it will make you water gun overheat so watch your water usage.

## Licence ##

* All assets (graphics, music, text) are licensed under a
Creative Commons BY-NC-SA 3.0 Unported License.
See [http://creativecommons.org/licenses/by-nc-sa/3.0/deed.en_US](http://creativecommons.org/licenses/by-nc-sa/3.0/deed.en_US) for more info.

* All source code for Mr. Rescue with the exception of the modules
slam, AnAL and TSerial, is licensed under the zlib license.
Check the [LICENSE](https://github.com/SimonLarsen/mrrescue/blob/master/LICENSE) file for more info.
