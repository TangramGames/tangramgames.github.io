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
Mr. Rescue is a silly, fast-paced platformer about putting out fire and throwing people out the window.

The game is currently in development, and will be released for free for Windows, Linux and OS X sometime early 2013.

## Screenshots ##
<div style="text-align: center">
{% for image in page.images %}
<a href="{{ image }}">
	<img src="{{ image }}" width="200" class="game-thumb" />
</a>
{% endfor %}
</div>

## Downloads ##

Mr. Rescue is far from done but we might upload beta versions here when we get closer to release.

If you're comfortable with the [LÖVE](http://love2d.org/) framework feel free to download the latest development version from [GitHub](https://github.com/SimonLarsen/mrrescue) at your own risk.
