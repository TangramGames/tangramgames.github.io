---
layout: page
title: Tobu Tobu Girl Deluxe
images:
 - screens/title.png
 - screens/menu1.png
 - screens/menu2.png
 - screens/plains1.png
 - screens/plains2.png
 - screens/clouds1.png
 - screens/clouds2.png
 - screens/clouds3.png
 - screens/space1.png
 - screens/space2.png
 - screens/space3.png
 - screens/dream1.png
 - screens/dream2.png
 - screens/rank.png
 - screens/highscores.png
 - screens/jukebox.png
 - screens/pause.png
artwork:
 - name: "Logo (color, SVG)"
   path: images/logo_color.svg
 - name: "Logo (white, SVG)"
   path: images/logo_white.svg
 - name: "Kickstarter product design mockup"
   path: images/kickstarter_mockup.png
 - name: "Box art front (PNG)"
   path: images/box_art_front.png
 - name: "Cover image (PNG)"
   path: images/cover_image.png

---
## Factsheet ##

* **Developer**: [Tangram Games](http://tangramgames.dk). With sound and music by [potato-tan](http://potatotan.com)
* **Publisher**: [First Press Games](https://firstpressgames.com) (physical release)
* **Release date**: Summer 2019
* **Platforms**: Nintendo Game Boy
* **Distribution**:
  - Physical edition published by First Press Games
  - ROM download on itch.io
  - Source code on GitHub.com ([MIT license](https://opensource.org/licenses/MIT))
* **Website**: [tangramgames.dk/tobutobugirldx](http://tangramgames.dk/tobutobugirldx)
* **Kickstarter page**: [http://kck.st/2OPmDGl](http://kck.st/2OPmDGl)
* **Price**:
  - Download: Free
  - Physical release:
    - Regular edition: 49€ + shipping
    - Limited edition: 64€ + shipping

## Description ##

Your cat is floating into the atmosphere and you are the only one who can save it. Jump, dash, and flap your arms to maneuver around perilous obstacles racing against the clock to retrieve your pet friend before it is too late!

Tobu Tobu Girl Deluxe is a Game Boy/Game Boy Color full-color remaster of [Tobu Tobu Girl](/tobutobugirl) (2017).
It is a hectic and fast-paced arcade-style platformer with a heavy emphasis on speed and twitch movement.
It features an original soundtrack by potato-tan.

## History ##

Tobu Tobu Girl was originally created for the [third GBJam game jam](http://jams.gamejolt.io/gbjam3/). The initial prototype featured a more puzzle-like design. After the game jam, the game went through several iterations gradually moving towards a more action-oriented design. Early during development potato-tan joined the team to do sound design and music composition. The original, Game Boy-only version was released December 3rd 2017.

In 2018, First Press Games reached out to Tangram Games and proposed a cooperation on a larger physical run with a further improved game, inspired by the popular Deluxe remakes for Game Boy Color® from the late 90s. After some initial planning, the concept began to materialize in the course of the same year.
On April 4 2019 a Kickstarter campaign was launched in order to gather funding for a physical release. The campaign is scheduled to end on May 4.

## Screenshots ##

<div class="alert alert-info">
Note: The game is currently in development and these images may not fully represent the game in its finished state.
</div>

<div class="row">
	{% for image in page.images %}
	<div class="col-sm-4">
		<a href="{{ image }}">
			<img src="{{ image }}" class="img-responsive thumbnail">
		</a>
	</div>
	{% endfor %}
</div>

## Kickstarter video ##

<div class="embed-responsive embed-responsive-16by9">
    <iframe width="660" height="372" src="https://www.kickstarter.com/projects/firstpressgames/tobu-tobu-girl-deluxe-for-gb-gbc/widget/video.html" frameborder="0" scrolling="no">
    </iframe>
</div>

## Credits ##

**Game design**:<br>
Simon Jonas Larsen<br>
Lukas Erritsø Hansen

**Game artwork**<br>
Lukas Erritsø Hansen

**Box and manual artwork**<br>
Lukas Erritsø Hansen<br>
[Credits for new design]

**Programming**<br>
Simon Jonas Larsen

**Music and sound effects**<br>
potato-tan

## Contact ##

### Developers

**E-mail**<br>
<a href="mailto:&#119;&#101;&#097;&#114;&#101;&#116;&#097;&#110;&#103;&#114;&#097;&#109;&#064;&#103;&#109;&#097;&#105;&#108;&#046;&#099;&#111;&#109;">wearetangram@gmail.com</a>

**Twitter**<br>
<a href="https://twitter.com/TangramGames">@TangramGames</a><br>
<a href="https://twitter.com/SimonLarsen">@SimonLarsen</a><br>
<a href="https://twitter.com/LukasErritsoe">@LukasErritsoe</a><br>
<a href="https://twitter.com/potatoTeto">@potatoTeto</a>

### Publisher

**E-mail**<br>
[FPG email here?]

**Twitter**<br>
<a href="https://twitter.com/firstpressgames">@firstpressgames</a>

## Logos and artwork ##

{% for image in page.artwork %}
<div class="well">
    <a href="{{ image.path }}">
        {{ image.name }}
        <img class="img-responsive checkered-bg" src="{{ image.path }}" alt="{{ image.name }}">
    </a>
</div>
{% endfor %}
