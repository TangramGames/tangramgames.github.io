---
layout: post
title: Tobu Tobu Girl Deluxe development update
author: Tangram Games
twitter: TangramGames
screenshots:
 - /img/ttgdx_dev_intro_gb.png
 - /img/ttgdx_dev_intro_gbc.png
 - /img/ttgdx_dev_plains_gb.png
 - /img/ttgdx_dev_plains_gbc.png
sgbmockups:
 - /img/ttgdx_dev_sgb_mainmenu.png
 - /img/ttgdx_dev_sgb_space.png
 - /img/ttgdx_dev_sgb_pause.png
 - /img/ttgdx_dev_sgb_dream.png
infbgs:
 - /img/ttgdx_dev_inf1.png
 - /img/ttgdx_dev_inf5.png
 - /img/ttgdx_dev_inf6.png
---
Today we would like to give you a small update on the development of Tobu Tobu Girl Deluxe, showing off some of the changes to the game and talk a bit about some of the new features we are working on.

## Colorization and updated assets

We recently wrapped up work on adding Game Boy Color support to the game. Besides colorizing the old assets, we have also remade a lot of the graphics. We felt like many of these changes were necessary because the old graphics didn’t translate well into color. Other assets, such as the main menu banner, were redone to better fit into the overall style of the game.

Here are some comparisons between the original version (left) and the Deluxe version (right):

<div class="row">
{% for img in page.screenshots %}
<div class="col-xs-6">
<a href="{{ img }}">
<img src="{{ img }}" class="img-responsive thumbnail">
</a>
</div>
{% endfor %}
</div>

And here are the new main menu banners:

<video controls autoplay loop>
<source src="/img/ttgdx_dev_menucomp.mp4" type="video/mp4">
Your browser does not support video playback.
</video>

## Super Game Boy

Since we are expecting to hit the Super Game Boy stretch goal on Kickstarter, we have started preliminary work on Super Game Boy border and colorization.

Lukas just finished up this mockup of the Super Game Boy border. Keep in mind this is just a mockup and it may look different in the finished game.

<img src="/img/ttgdx_dev_sgb_mockup.png" class="img-responsive thumbnail">

We have also started mocking up the SGB palettes. Here are some initial mockups:

<div class="row">
{% for img in page.sgbmockups %}
<div class="col-xs-6">
<a href="{{ img }}">
<img src="{{ img }}" class="img-responsive thumbnail">
</a>
</div>
{% endfor %}
</div>

Colorization on the Super Game Boy is quite limited compared to what is possible on the Game Boy Color, but we still think these changes make the game look a lot more vibrant.

## Infinite game mode

We have also been pondering the possibility of adding an “infinite” game mode. Due to the arcadey nature of the game it is, in its current state, a rather short one, inviting the player to strive for the coveted S-rank through multiple playthroughs. We would like for this extra game mode to provide a extra challenge for those who have already mastered the game, while also providing a new experience for those who would rather overcome new challenges than to strive for that one perfect score.

<div class="row">
{% for img in page.infbgs %}
<div class="col-xs-4">
<a href="{{ img }}">
<img src="{{ img }}" class="img-responsive thumbnail">
</a>
</div>
{% endfor %}
</div>

Due to the infinite nature of this game mode we want the background images to change as you progress progress, while adhering to a coherent theme. Following are some mockups of backgrounds.

<a href="/img/ttgdx_dev_inf_banner.png">
<img src="/img/ttgdx_dev_inf_banner.png" class="img-responsive thumbnail" >
</a>

Please note that if the stretch goal should be reached, the backgrounds will of course be colorized.
