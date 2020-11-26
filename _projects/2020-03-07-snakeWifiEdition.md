---
layout: article
title: Snake WiFi Edition
excerpt: A parody of the Google Dinosaur game!
tags: games web JavaScript
cover: /assets/images/projects/snakeWifiEdition/snake-gameplay.png
repo: kenny-designs/Snake-WiFi-Edition
article_header:
  type: overlay
  theme: dark
  background_color: '#203028'
  background_image:
    gradient: 'linear-gradient(135deg, rgba(34, 139, 87, .4), rgba(139, 34, 139, .4))'
    src: /assets/images/projects/snakeWifiEdition/snake-gameplay.png
---

# What Is Snake WiFi Edition?
I made Snake WiFi Edition (which is playable [here](https://kenny-designs.github.io/Snake-WiFi-Edition/)
but is **not** mobile friendly)
as my response to a school project in which I needed to build a website with basic
HTML and CSS. I'm more than familiar with these tools though so I decided to push
things even further by mixing in JavaScript and seeing how quickly I could build
a site with a fully functioning game (which was about a day by the way).

As for the theme, I've always been enamored with Google's Dinosaur game that
appears when one loses connection to the internet. As such, I wanted to make my
own simple game on the theme of trying to go online but being met with that oh
so painful HTTP 404 error code.

In Snake WiFi Edition, you play as a ever so hungry WiFi snake trying to gobble up
as much WiFi as possible! The more you eat before hitting a wall/your body the
more points you earn!

![Gameplay](/assets/images/projects/snakeWifiEdition/snake-gameplay.png){:.rounded.image--center}

{:.text--center}
*A hungry, hungry WiFi snake just tryna' get some WiFi's.*

![Dinosaur](/assets/images/projects/snakeWifiEdition/dino.png){:.rounded.image--center}

{:.text--center}
*Google's own Dinosaur game that inspired this project.*

# How Was It Made?
My primary goal was to make a website with a game built into it as quickly as I
possibly could. As such, I decided to keep things rather simple with vanilla
JavaScript, HTML, and CSS. In fact, the actual game portion of the site is just
pure HTML with some styling and logic. I would have preferred to use the web
game framework [Phaser3](https://phaser.io/phaser3) but emphasis on HTML and CSS
was a must as the project was being graded on my proficiency with those tools.

The majority of the site was just HTML and CSS. The snake game made use of HTML
grids to form the game board and the snake was moved around with JavaScript.

![Menu](/assets/images/projects/snakeWifiEdition/menu.png){:.rounded.image--center}

{:.text--center}
*The site's home screen.*
