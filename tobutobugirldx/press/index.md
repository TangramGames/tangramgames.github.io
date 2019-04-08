---
layout: wide
title: Tobu Tobu Girl Deluxe
contents:
 - 
images:
 - screens/title.png
 - screens/intro.png
 - screens/menu1.png
 - screens/plains1.png
 - screens/plains3.png
 - screens/clouds2.png
 - screens/clouds3.png
 - screens/space1.png
 - screens/space3.png
 - screens/dream1.png
 - screens/dream2.png
 - screens/scoretally.png
 - screens/rank.png
 - screens/highscores.png
 - screens/jukebox.png
 - screens/pause.png
artwork:
 - name: "Logo (color, SVG)"
   path: images/logo_color.svg
 - name: "Logo (color, 2000x1150, PNG)"
   path: images/logo_color.svg
 - name: "Logo (white, SVG)"
   path: images/logo_white.svg
 - name: "Logo (white, 2000x1150, PNG)"
   path: images/logo_white.svg
 - name: "Kickstarter product design mockup (3507x2480, PNG)"
   path: images/kickstarter_mockup.png
 - name: "Box art design mockup (1031x1300, PNG)"
   path: images/boxart_mockup.png

---

<div class="row">
<div class="col-sm-3" markdown="1">

### Contents

* [Factsheet](#factsheet)
* [Description](#description)
* [History](#history)
* [Screenshots](#screenshots)
* [Kickstarter video](#kickstarter-video)
* [Logos and artwork](#logos-and-artwork)
* [Credits](#credits)
* [Contact](#contact)

</div>
<div class="col-sm-9" markdown="1">

<img class="img-responsive" src="/img/ttgdx_screens.jpg">

## Factsheet

* **Developer**: [Tangram Games](http://tangramgames.dk). With sound and music by [potato-tan](http://potatotan.com)
* **Publisher**: [First Press Games](https://firstpressgames.com) (physical release)
* **Release date**: Summer 2019
* **Platforms**: Nintendo Game Boy and Game Boy Color
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

## Logos and artwork ##

{% for image in page.artwork %}
<div class="thumbnail">
    <div class="caption">
        <a href="{{ image.path }}">{{ image.name }}</a>
    </div>
    <a href="{{ image.path }}">
        <img class="img-responsive checkered-bg" src="{{ image.path }}" alt="{{ image.name }}">
    </a>
</div>
{% endfor %}

## Kickstarter video ##

<div class="embed-responsive embed-responsive-16by9">
    <iframe width="660" height="372" src="https://www.kickstarter.com/projects/firstpressgames/tobu-tobu-girl-deluxe-for-gb-gbc/widget/video.html" frameborder="0" scrolling="no">
    </iframe>
</div>

[Kickstarter embedding options](https://www.kickstarter.com/projects/firstpressgames/tobu-tobu-girl-deluxe-for-gb-gbc/widget)

## Credits ##

**Game design**:<br>
Simon Jonas Larsen<br>
Lukas Erritsø Hansen

**Game artwork**<br>
Lukas Erritsø Hansen

**Box and manual artwork**<br>
Lukas Erritsø Hansen<br>
chiro

**Programming**<br>
Simon Jonas Larsen

**Music and sound effects**<br>
potato-tan

## Contact ##

### Developers

**E-mail**<br>
<a href='&#109;a&#105;lto&#58;&#37;77&#101;a&#114;et&#37;6&#49;ngram&#64;gm%61il&#46;&#99;%6Fm'>w&#101;aretangram&#64;gmail&#46;co&#109;</a>

**Twitter**<br>
<a href="https://twitter.com/TangramGames">@TangramGames</a><br>
<a href="https://twitter.com/SimonLarsen">@SimonLarsen</a><br>
<a href="https://twitter.com/LukasErritsoe">@LukasErritsoe</a><br>
<a href="https://twitter.com/potatoTeto">@potatoTeto</a>

### Publisher

**E-mail**<br>
<a href='m&#97;ilt&#111;&#58;k%69c%6&#66;s%&#55;&#52;&#37;6&#49;rt%&#54;&#53;r&#64;fi&#114;s&#116;pr%&#54;5ssgames&#46;com'>kickstart&#101;r&#64;fir&#115;tp&#114;essga&#109;es&#46;co&#109;</a>

**Twitter**<br>
<a href="https://twitter.com/firstpressgames">@firstpressgames</a>

</div>
</div>

