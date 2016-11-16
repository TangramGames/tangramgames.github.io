---
layout: game
title: Tobu Tobu Girl
header: images/header.png
images:
    - images/ttg1.png
    - images/ttg2.png
    - images/ttg3.png
    - images/ttg4.png
    - images/ttg5.png
    - images/ttg6.png
---
<div class="alert alert-warning">
	<p>This game is currently in development.</p>
</div>

In Tobu Tobu Girl your cat has taken to the skies and you must bounce, jump and dash your way to the top to bring him home safely!

Tobu Tobu Girl is a simple but challenging game of vertical climbing against the clock, scheduled to release later this year on the Nintendo Game Boy. 

## Teaser trailer ##

<div class="embed-responsive embed-responsive-16by9">
	<iframe src="https://www.youtube.com/embed/mxENfVnmIuI" frameborder="0" allowfullscreen>
	</iframe>
</div>

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
