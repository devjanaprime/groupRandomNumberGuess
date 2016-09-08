Team Random Number Guess
========================

Tech: Node, Express, and JQuery

Overview
========
The final version of this project will have two modes:
* setup mode
* play mode

Setup Mode
----------
Inputs on the web page:
* Maximum Number selector (at least 3 options)
* Start Game button

Play Mode
---------
* Input for a guess for each of the four Players
* submit guesses button
* total guesses made indicator
* maximum number indicator
* details area for the last guess of each player (low/high)
* "abandon game" button that goes back to setup mode

if a guess is correct
---------------------
* PROMINENTLY Display which player won (make 'em FEEL it)
* restart button that leads to Setup Mode

Necessary Ingredients
=====================
AKA Client Demands...

All random number stuff should happen on the server. Generation of the random number upon game start as well as comparisons between guesses and the random correct answer.

Take a moment to discuss with your team members why this is something that a client may demand.  

Once you get it working, style it up, yo!


Stretch Goals
=============
If you've got time and bandwidth, why not add some special sauce?


* disallow two users two submit the same guess at the same time
* disallow any guess to be entered more than once
* hot/cold indicators
* Allow users to create "profiles" that can include their name and also how many matches they have played/won (win percentage)
* Add a "bot" player that guesses a random number each time in addition to the players
* what are your ideas?
