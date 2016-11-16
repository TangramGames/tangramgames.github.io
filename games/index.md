---
layout: widepage
title: Games
games-indev:
    - name: Tobu Tobu Girl
      id: tobutobugirl
    - name: Rakshasa
      id: rakshasa
games-released:
    - name: 90 Second Portraits
      id: 90secondportraits
    - name: Mr. Rescue
      id: mrrescue
    - name: Safety Blanket
      id: safetyblanket
    - name: Duck Marines
      id: duckmarines
    - name: Sienna
      id: sienna
    - name: Dream Witch Erika
      id: dreamwitcherika
    - name: N.O.D.E.
      id: node
---
## In development ##

<div class="row">
	{% for game in page.games-indev %}
	<div class="col-md-3 col-sm-4 col-xs-12">
		<a href="/games/{{ game.id }}">
			<img src="/img/thumb/{{ game.id }}.png" class="center-block img-responsive">
		</a>
		<div class="caption">
			<p class="text-center">
				<a href="/games/{{ game.id }}">
					{{ game.name }}
				</a>
			</p>
		</div>
	</div>
	{% endfor %}
</div>

## Released ##

<div class="row">
	{% for game in page.games-released %}
	<div class="col-md-3 col-sm-4 col-xs-12">
		<a href="/games/{{ game.id }}">
			<img src="/img/thumb/{{ game.id }}.png" class="center-block img-responsive">
		</a>
		<div class="caption">
			<p class="text-center">
				<a href="/games/{{ game.id }}">
					{{ game.name }}
				</a>
			</p>
		</div>
	</div>
	{% endfor %}
</div>
