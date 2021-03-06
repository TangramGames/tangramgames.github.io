---
layout: game
title: Safety Blanket
header: images/header.png
images:
  - images/1.png
  - images/2.png
  - images/3.png
---
Safety Blanket was developed in 48 hours for the Ludum Dare 29 game jam.

It's bed time, the monsters are out to get you, and your blanket is just too small to cover your body! 

Cover your exposed limbs to fend off the approaching tentacles. 

The tentacles will only go for your feet, hands and head. 

If the tentacles reach you it's game over!

**SURVIVE TILL 7 AM**

## Screenshots ##

<div class="row">
	{% for image in page.images %}
	<div class="col-sm-4">
		<a href="{{ image }}">
			<img src="{{ image }}" class="img-responsive thumbnail">
		</a>
	</div>
	{% endfor %}
</div>

## Trailer / Timelapse ##

<iframe width="100%" height="300" src="//www.youtube.com/embed/9ZszqcVc6fU" frameborder="0" allowfullscreen>
</iframe>

## Downloads ##

<iframe src="//itch.io/embed/7913?dark=true" width="552" height="167" frameborder="0">
</iframe>

Also available from [GitHub](https://github.com/SimonLarsen/safetyblanket/releases)
and [Ludum Dare submission page](http://www.ludumdare.com/compo/ludum-dare-29/?action=preview&amp;uid=1980).

## License ##

All assets (images, sound, text) made by Tangram Games.
Licensed under [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) license.

All source code with the exception of [slam.lua](https://raw.githubusercontent.com/SimonLarsen/90-Second-Portraits/master/slam.lua) made by Tangram Games.

Source code licensed under ZLIB license. See [LICENSE.txt](https://raw.githubusercontent.com/SimonLarsen/safetyblanket/master/LICENSE.txt).
