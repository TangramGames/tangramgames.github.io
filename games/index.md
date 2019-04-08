---
layout: widepage
title: Games
---

## In development

<div class="row">
    {% for game in site.data.games %}
    {% if game.status == "indev" %}
    <div class="col-md-3 col-sm-4 col-xs-6">
        <a href="/games/{{ game.id }}">
            <img src="/img/thumb/{{ game.id }}.png" class="center-block img-responsive img-circle" alt="{{ game.name }}">
        </a>
        <div class="caption">
            <p class="text-center">
                <a href="/games/{{ game.id }}">{{ game.name }}</a>
            </p>
        </div>
    </div>
    {% endif %}
    {% endfor %}
</div>

## Released

<div class="row">
    {% for game in site.data.games %}
    {% if game.status == "released" %}
    <div class="col-md-3 col-sm-4 col-xs-6">
        <a href="/games/{{ game.id }}">
            <img src="/img/thumb/{{ game.id }}.png" class="center-block img-responsive img-circle" alt="{{ game.name }}">
        </a>
        <div class="caption">
            <p class="text-center">
                <a href="/games/{{ game.id }}">{{ game.name }}</a>
            </p>
        </div>
    </div>
    {% endif %}
    {% endfor %}
</div>

## Game jam games

<div class="row">
    {% for game in site.data.jamgames %}
    <div class="col-md-3 col-sm-4 col-xs-6">
        <a href="{{ game.url }}">
            <img src="/img/thumb/{{ game.id }}.png" class="center-block img-responsive img-circle" alt="{{ game.name }}">
        </a>
        <div class="caption">
            <p class="text-center">
                <a href="{{ game.url }}">{{ game.name }}</a>
            </p>
        </div>
    </div>
    {% endfor %}
</div>
