---
layout: article
title: My Pet Acadamia
excerpt: A Pokemon Styled Online Pet Collecting Game!
tags: games java jsp mysql
cover: /assets/images/projects/myPetAcadamia/battle-screen.png
repo: kenny-designs/my-pet-acadamia
article_header:
  type: overlay
  theme: dark
  background_color: '#203028'
  background_image:
    gradient: 'linear-gradient(135deg, rgba(34, 139, 87, .4), rgba(139, 34, 139, .4))'
    src: /assets/images/projects/myPetAcadamia/pet-select.png
---

# What Is My Pet Acadamia?
My Pet Acadamia is a battle pets styled game that is heavily inspired by games like
[Pokemon](https://en.wikipedia.org/wiki/Pok%C3%A9mon) and [Neopets](http://www.neopets.com/).
The goal of the game is to form a team of pets and have them battle in the safari.
Your pets slowly grow more powerful as they fight and you can even catch new pets
to add to your collection!

# How Does It Work?
Much like Neopets, you start the game by creating an account or logging into an
old one.

![LoginScreen](/assets/images/projects/myPetAcadamia/login-screen.png){:.rounded.image--center}

{:.text--center}
*A screenshot of the login screen.*

For new users, they select a username, password, and one of three starting pets.

![PetSelect](/assets/images/projects/myPetAcadamia/pet-select.png){:.rounded.image--center}

{:.text--center}
*New users get to choose between the starting pets Cat, Weezer, and Chuck.*

After creating your account, you are then greeted by the home screen. Here, you can
check out your stats, manage your team, go fight in the safari, view the pet wiki,
logout of your account, or even read a little blurb about what inspired the game.

![HomeScreen](/assets/images/projects/myPetAcadamia/home-screen.png){:.rounded.image--center}

{:.text--center}
*After logging in, players are taken to the homepage to decide what they want to do.*

# What Can You Do?
After logging in, players have a few options. Perhaps the most exciting is getting
to battle with your pets and earning experience points for levels! To do this,
simply Enter Safari from the home screen.

![BattleScreen](/assets/images/projects/myPetAcadamia/battle-screen.png){:.rounded.image--center}

{:.text--center}
*An ongoing battle between the player's team and an enemy from the safari.*

After catching a new pet, you can then Manage Team from the homescreen to go and
add that pet to your team. Or perhaps even remove a pet from your team or just
delete them from your collection entirely (that's kinda mean though...)

![PetCollection](/assets/images/projects/myPetAcadamia/pet-collection.png){:.rounded.image--center}

{:.text--center}
*A player managing their team.*

If you're curious what other pets exist in the world of My Pet Acadamia, you can
always visit the PetWiki from the homescreen. Here, you can read about different
pets and get an idea of what kind of team you'd like to make!

![PetWiki](/assets/images/projects/myPetAcadamia/pet-wiki.png){:.rounded.image--center}

{:.text--center}
*A wiki of all available pets along with some silly descriptions of them*

After playing for a while, you might wonder just how often you've been winning
(or losing). You can always check out how you're doing on the Stats screen!

![stats-screen](/assets/images/projects/myPetAcadamia/stats-screen.png){:.rounded.image--center}

{:.text--center}
*My current stats. Look how well I'm doing!*

# What Was This All Made With?
This web application was developed with Java Server Pages (JSP), Java Servlets,
MySQL, and Apache Tomcat. The Apache Tomcat server is hosted on my very own
Raspberry Pi gifted to me by my good friend [Matt](https://github.com/mattlol85).
The MySQL database I have running on a spare laptop.

# Why This Tech Stack?
This isn't my usual stack for developing websites. I typically go with NodeJS,
Express, and some mixture of more JavaScript related technologies. However, I was
attending a college class in which for my final project I was asked to create a website
with a backend to it. I considered my usual tech stack but the professor mentioned
using Java itself. Outside of my intro to programming classes, I have never really
used Java for anything all that noteworthy. As such, I thought it would be a fantastic
challenge to see if I could learn something brand new and push out a completed
project by a given deadline. I'm proud to say I was successful in this endeavor
and My Pet Acadamia was the result of this challenge! The project even earned a
perfect score.
