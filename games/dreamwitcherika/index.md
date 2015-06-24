---
layout: game
title: "Dream Witch Erika"
header: images/header.png
images:
    - images/1.png
    - images/2.png
    - images/3.png
    - images/4.png
---
Dream Witch Erika is a metroidvania platformer developed for the Ludum Dare 30 competition.

See [Ludum Dare submission page](http://ludumdare.com/compo/ludum-dare-30/?action=preview&uid=1980).

## Screenshots ##

<div class="centered">
	{% for image in page.images %}
	<a href="{{ image}}">
		<img src="{{ image }}" width="45%" class="thumbnail">
	</a>
	{% endfor %}
</div>
