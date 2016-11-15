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
Mr. Rescue is an arcade styled 2d action game centered around evacuating civilians from burning buildings.

The game features fast paced fire extinguishing action, intense boss battles,
a catchy soundtrack and lots of throwing people around in pseudo-randomly generated buildings.

As of version 1.02 we have added XBox 360 controller support and fullscreen modes.

## Screenshots ##

<div class="row">
	{% for image in page.images %}
	<div class="col-sm-4">
		<a href="{{ image }}">
			<img src="{{ image }}" class="thumbnail img-responsive">
		</a>
	</div>
	{% endfor %}
</div>

## Gameplay video ##

<div class="embed-responsive embed-responsive-16by9">
	<iframe src="http://www.youtube.com/embed/5k7ctkHAURw" frameborder="0" allowfullscreen>
	</iframe>
</div>

## Downloads ##

### Windows / Mac OS X / Linux ###

<iframe src="//itch.io/embed/522?dark=true" width="552" height="167" frameborder="0">
</iframe>

Also available from [GitHub](https://github.com/SimonLarsen/mrrescue/releases).

### Source code ###

* [GitHub](https://github.com/SimonLarsen/mrrescue)

## How to play ##

We highly recommend checking out the ingame how-to but here's the basics:

* Your job is to rescue civilians from a burning building.
* You rescue people by picking them up and throwing them out the window.
* Equipped with a water gun you must fight your way through flames and fire sprites but remember: your job is to rescue people!
* When being near fire your suit will accumulate heat. Collect coolants to keep it from overheating.
* You water tank only has limited capacity. Emptying it will make you water gun overheat so watch your water usage.

## Licence ##

All assets (graphics, music, text) are licensed under a
Creative Commons BY-SA 3.0 Unported License.
See [http://creativecommons.org/licenses/by-sa/3.0/deed.en_US](http://creativecommons.org/licenses/by-sa/3.0/deed.en_US) for more info.

All source code for Mr. Rescue with the exception of the modules
slam, AnAL and TSerial, is licensed under the zlib license.
Check the [LICENSE](https://github.com/SimonLarsen/mrrescue/blob/master/LICENSE) file for more info.
