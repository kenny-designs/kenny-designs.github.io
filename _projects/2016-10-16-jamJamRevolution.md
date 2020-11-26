---
layout: article
title: Jam Jam Revolution
excerpt: Rhythm game entry to GBJAM 5
tags: games C++ DirectX Win32
cover: /assets/images/projects/jamJamRevolution/main-menu.png
repo: kenny-designs/JamJamRevolution
article_header:
  type: overlay
  theme: dark
  background_color: '#203028'
  background_image:
    gradient: 'linear-gradient(135deg, rgba(34, 139, 87, .4), rgba(139, 34, 139, .4))'
    src: /assets/images/projects/jamJamRevolution/gameplay-1.png
---

# What Is Jam Jam Revolution?
Jam Jam Revolution (JJR) is a rhythm game based on one of my favorite childhood
games called [Dance Dance Revolution](https://en.wikipedia.org/wiki/Dance_Dance_Revolution) (DDR).
Just like the game it's based on, JJR is a simple game in which you listen to music
and hit the buttons corresponding to the sprites on screen. The better you time
your button presses the higher score you get! 

If you're interested in playing, the game is available on itch.io
[here](https://kenny-designs.itch.io/jam-jam-revolution)!

![Gameplay1](/assets/images/projects/jamJamRevolution/gameplay-1.png){:.rounded.image--center}

{:.text--center}
*A game of Jam Jam Revolution in action!*

![Results](/assets/images/projects/jamJamRevolution/results-screen.png){:.rounded.image--center}

{:.text--center}
*After a song finishes playing, players are presented with their final score.*


# What Is GBJAM 5?
GBJAM is a [game jam](https://en.wikipedia.org/wiki/Game_jam) in which the goal
is to create a game in around a week with *only* four colors. The GB in GBJAM
is short for Game Boy and, much like the original [Game Boy](https://en.wikipedia.org/wiki/Game_Boy),
participants must use a very limited color pallete.

In the spirit of the greenish tint of the Game Boy, I designed Jam Jam
Revolution to only use green colors.

![Menu](/assets/images/projects/jamJamRevolution/main-menu.png){:.rounded.image--center}

{:.text--center}
*The main menu to JJR. Look at all that green!*


# How Was It Made?
Perhaps the most difficult part of making this game was that it used an engine
I cooked up myself instead of something premade like Unity. I had just finished
the entirety of the book [Beginning Game Programming Fourth Edition](https://www.cengage.com/c/beginning-game-programming-4e-harbour/9781305258952/) by Jonathan S. Harbour in which I learned to make games from
scratch with C++ and DirectX. With this new found knowledge, I decided to test
my skills by entering GBJAM 5.

Altogether, I utilized the following:
- C++
- DirectX
- Win32 API
- Visual Studio
- Audacity
- Pyxel Edit

The engine itself is comprised of C++ code, DirectX for graphics, and the Win32 API
for displaying windows and the like. In addition to writing all the code, I also
did all the art with my favorite pixel art program [Pyxel Edit](https://pyxeledit.com/).
Music was edited with [Audacity](https://www.audacityteam.org/) and originally made
and given to me by my good friend Trey (who unfortunately does not have a website or
social media I can link to).