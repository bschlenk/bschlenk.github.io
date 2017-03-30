---
layout: post
title: Unfinished Business
---

I'm the kind of person who starts a project and never gets around to finishing it.
I'd like to change that this year, so I'm creating a list of all the projects I've ever started,
with a bit of description for each one. Later I'll go through this list and prioritize them based on
how long I think it would take to productionize, how exciting it would be to finish, etc.


## Wik-E-Books
This was an idea at an angelhack that never took off. It's supposed to be a program that
takes a wiki page link as input, and generates an e-book. The catch is that the e-book 
will contain all the data for all the referenced links as well, making it ideal for taking
on trips and stuff. The depth of folowed links should be configurable.

## Asciiflow
This is an ascii art editor that I forked. I really like the way it is written using
jsdoc annotations everywhere intended for the google closure compiler. I have some ideas for
this, like ways to make it more like photoshop with layers and stuff. We'll see how this goes
as I'm trying to submit pull requests for all the changes I've made so far.

## bschlenk.github.io
This blog! I want to figure out jekyll and put my other javascript projects on here as pages.

## Chip8 Emulator
A javascript chip8 emulator. Mostly finished, I never got input working though.
Could be fun to revisit this and add jsdoc and compile it.

## Cloudnes
This was supposed to be a web based NES tracker similar to [famitracker](http://famitracker.com/).
The features include sharable instruments and tracks, allowing for collaboration 
when creating music. This ended up spawning a few other projects in the research faze.

### [Pynsf](https://github.com/bschlenk/pynsf)
A NES emulator core, focusing on music. This was to try and understand how NES music 
was saved to be able to break them down into modifiable tracker data.

### Theramin
Messing around with the web audio api

## [GSSPP](https://github.com/bschlenk/gsspp)
A C++ wrapper around sspi kerberos auth. Thought I'd use it at lakeside software,
only partially completed it so never was used.

## Serial.h
A header only library for enforcing thread safety on an object.

## MathDodgerPro
A game where numbers are flying at you and you have to catch the one that solves
the given equation. So far I have the numbers flying around, but there is zero interaction.
This one can potentially be added as a page on the blog.

## Snake
My attempt at creating snake with canvas. Got the snake and growing logic down,
but never programmed any endgame handling.

## Space
An oldschool asteroids style screen saver. Another one I'd like to include
as a page on the blog.

## [Hound](https://github.com/bschlenk/hound)
Another forked project. Not a lot of action in terms of incorporated pull requests.
I want to add some useful ui features, like collapsing a project's results
and a hovering sidebar with a list of all the matched packages.

## Home
This was supposed to be a suite of web pages meant to be used on a raspberry pi
within a home. Things like torrent navigation searching, hue light controlling, etc.

## Language of Ab
A language similar to piglatin. This worked at one point, with text to speech,
but that stopped working becasue google shut down the public api.

## Blockit
Take an image and convert it into minecraft blocks.

## Boggle
The game of boggle, + solver for generated games or newspaper games.

## Mapcraft
Not sure how this got named, but it's currently a 3d viewer of all minecraft
block types. It would be cool to make this work for all block types and enemies.

## Set
The game of set! In the browser, with multiplayer and stuff.

## TicTacToe
Wow, tic tac toe. This could be something unique, maybe increase the size of the board
every time there is a  stalemate.

## Negative No No
An online diary of sorts to keep track of negive thoughts and combat them.
There is something like this out there now that looks interesting. I tried
contacting the creator but got no response.

## Procon
Create a list of pros and cons on a given topic. I made this when my girlfriend
was deciding whether she wanted to come to seattle or not.

## Karaoke
Source lyrics for a band's youtube videos and sync it to the music for some
"karaoke" (not really becasue the voices will still be there). I wanted this
to learn lyrics for songs.

## Lumifoo
Python library for phillips hue. I used it during the france bombings to set
the lights to the France flag colors. It could take any flag as input and
change the lights.

## Minecraft Firework Generator
Generate fireworks and inject them into someone's inventory or a chest.

## SmileyHouse
A rewrite of the old game [SmileyHouse](http://www.puchisoft.com/smileyhouse.php).
Original code in jmagic, rewritten in Node. Put on hold because it became hard
to test the actual server. It makes a call to a hardcoded server and it doesn't
seem to be running anymore.

## Homebridge Roku
Homekit integration for roku devices.

## Mantis
Create 360 images from minecraft locations.

## Soundtropes
A music organization site with tags and friends, the idea is to categorize music
at every grain. Female/Male singer, blueberry, anything.

## These Things Are Annoying
Unwind those annoying clickbait websites.

## This or That
Show two images, user chooses one. Cathartic and simple. 

--------------------------------------------------------------------------------

### Things that distracted me during this blog post
* Trying to figure out directory specific vim settings, so I could make it auto wrap text in my jekyll posts
* Starting this list of things that distracted me
* Started tmux for split screen and got error: Unknown ruby interpreter version (do not know how to handle): RUBY\_VERSION.
* How do I escape literal underscore??
* Had this in my .zshrc: 
``` bash
# Automatically workon the current virtualenv when creating new tmux windows
if [ -n "$VIRTUAL_ENV" ]; then
    . "$VIRTUAL_ENV/bin/activate"
fi
```
* Started adding jsdoc to my game projects
