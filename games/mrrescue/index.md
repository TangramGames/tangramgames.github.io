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

The game features fast paced fire extinguishing action and lots of throwing people around.

## Screenshots ##
<div style="text-align: center">
{% for image in page.images %}
<a href="{{ image }}">
	<img src="{{ image }}" width="200" class="game-thumb" />
</a>
{% endfor %}
</div>

## Downloads ##

### Windows

* [**32 bit version**](https://bitbucket.org/SimonLarsen/tangram-files/downloads/mrrescue-1.0-win-x86.zip)

### Linux / Mac OS X

First go get the awesome [LÖVE framework]() here (it only takes a second), then download
the LÖVE archive below.

* [**LÖVE archive**](https://bitbucket.org/SimonLarsen/tangram-files/downloads/mrrescue-1.0.love)

### Source code ###

The zlib'ed source code is available on [GitHub](https://github.com/SimonLarsen/mrrescue).

## How to play ##

We highly recommend check out the ingame how-to but here's the basics:

* Your job is to rescue civilians from a burning building.
* You rescue people by picking them up and throwing them out the window.
* Equipped with a water gun you must fight your way through flames and fire sprites but remember: your job is to rescue people!
* When being near fire your suit will accumulate heat. Collect coolants to keep it from overheating.
* You water tank only has limited capacity. Emptying it will make you water gun overheat so watch your water usage.
