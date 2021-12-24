# Tarokka
A Tarokka Card randomizer and reader; deck constructor; card constructor

12-24-21
This project is the first build of my Codecademy Python Portfolio assignment.

Inspired by the Dungeons & Dragons module "Curse of Strahd," my project aims to recreate a Tarokka session. (kinda like Tarot, but can be played with a standard deck of cards.) In the game, the players will meet one of two characters who may offer to provide a reading, aiding the heroes on their quest.  The goal of the reading is to provide the locations of three treasures, the location of an ally, and the location of the final enemy. 

Running the play_game.py file will shuffle the low and then the high decks.
In my version of the game, the medium places five stacks of three cards each around a table.
The player will choose their fate by choosing from the three cards in each stack.
Ascii art is included to provide a rudimentary visual aid.

I went through several versions of the RoundX functions, all in an effort to approximate the most authentic code in the spirit of the cards. That is to say, instead of randomly appending cards from a stack (list), this code shuffles the initial list and appends a popped card from the top of the stack (the 0 position).  It's less elegant, but classy as all get out.

My initial program idea was modified and made more specific, based on my needs. At first, my goal was to build a deck-creating card builder, implementing essentially a Tarokka "pack" that runs through the deck-building program. I knew each card would need to be its own class object with key/value pairs I could amend and reassign based on the round, hence the card_constructor. Once I had the cards built, the specifics of the Tarokka game became the focus, and the deck/game builder seemed a little overly ambitious.

Again, this project hopes to utilize the bulk of the methods taught in the Codecademy Basics of Python Course. This is the first time I'm showing my code to anyone.  If you've taught yourself from a laptop in the middle of the night, you know what it's like learning in a vacuum. Feedback is appreciated, and thank you for checking it out!


