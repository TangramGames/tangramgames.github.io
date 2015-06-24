---
layout: page
title: Games
games-indev:
    - name: N.O.D.E.
      id: node
    - name: Tobu Tobu Girl
      id: tobutobugirl
games-finished:
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
games-dead:
    - name: Super Catacombs
      id: supercatacombs
---
## In development ##

{% for game in page.games-indev %}
<div class="game-cell">
	<div class="game-thumb">
		<a href="/games/{{ game.id }}">
			<img src="/img/thumb/{{ game.id }}.png">
		</a>
	</div>
	<div class="game-name">
		<a href="/games/{{ game.id }}">
			{{ game.name }}
		</a>
	</div>
</div>
{% endfor %}

## Finished ##

{% for game in page.games-finished %}
<div class="game-cell">
	<div class="game-thumb">
		<a href="/games/{{ game.id }}">
			<img src="/img/thumb/{{ game.id }}.png">
		</a>
	</div>
	<div class="game-name">
		<a href="/games/{{ game.id }}">
			{{ game.name }}
		</a>
	</div>
</div>
{% endfor %}

## Dead ##

{% for game in page.games-dead %}
<div class="game-cell">
	<div class="game-thumb">
		<a href="/games/{{ game.id }}">
			<img src="/img/thumb/{{ game.id }}.png">
		</a>
	</div>
	<div class="game-name">
		<a href="/games/{{ game.id }}">
			{{ game.name }}
		</a>
	</div>
</div>
{% endfor %}
