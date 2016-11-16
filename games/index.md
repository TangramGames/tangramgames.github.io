---
layout: widepage
title: Games
---

## In development ##

<div class="row">
	{% for game in site.data.games %}
	{% if game.status == "indev" %}
	<div class="col-md-3 col-sm-4 col-xs-12">
		<a href="/games/{{ game.id }}">
			<img src="/img/thumb/{{ game.id }}.png" class="center-block img-responsive img-circle">
		</a>
		<div class="caption">
			<p class="text-center">
				<a href="/games/{{ game.id }}">
					{{ game.name }}
				</a>
			</p>
		</div>
	</div>
	{% endif %}
	{% endfor %}
</div>

## Released ##

<div class="row">
	{% for game in site.data.games %}
	{% if game.status == "released" %}
	<div class="col-md-3 col-sm-4 col-xs-12">
		<a href="/games/{{ game.id }}">
			<img src="/img/thumb/{{ game.id }}.png" class="center-block img-responsive img-circle">
		</a>
		<div class="caption">
			<p class="text-center">
				<a href="/games/{{ game.id }}">
					{{ game.name }}
				</a>
			</p>
		</div>
	</div>
	{% endif %}
	{% endfor %}
</div>
