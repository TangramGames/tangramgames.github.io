---
layout: game
title: Tobu Tobu Girl
header: images/header.png
images:
    - images/ttg1.png
    - images/ttg2.png
    - images/ttg3.png
---
> Tobu Tobu Girl is currently in development.

Tobu Tobu Girl simple but challenging platform game for the Nintendo Game Boy.

## Screenshots ##

<div class="centered">
	{% for image in page.images %}
	<a href="{{ image }}">
		<img src="{{ image }}" width="160" class="thumbnail">
	</a>
	{% endfor %}
</div>
