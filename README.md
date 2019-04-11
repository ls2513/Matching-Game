# Matching-Game
Project 5 for Udacity - Matching Game

# Project Description: 
Matching game is a game that requires player to match similar objects/cards.  This game has 16 cards. As the user selects a card the card is turned over to reveal a symbol. The user must then try to select another card with the matching symbol.  This game only allows the maximum of 2 cards to be turned over (i.e., flipped) at one time. The user must find all 8 matching sets to win the game.
After the user has matched all 8 sets, a stat window is displayed where they can choose to restart or cancel the game.  Note restart will reset the game, turning over all cards to hide the symbol.  Cancel will leave the game in the current state (all cards and symbol displayed).  The user also has an option to select the “x” in the right-hand corner of the modal / pop up window.  This will remove the modal / status window, thus only displaying all 16 card symbols. 

# Installation / Dependencies:
The below files are required in order to play/execute Matching Game.
	css/app.css
	img/geometry.png
	js/main.js

# Starting the Game:
A user must click on a card / or the deck to start the game. Note clicking on the deck will start the timer but no card will turn over. 

Card turns blue when selected to reveal symbol. If card symbols match they turn green and stay turned over.

A move is counted each time a user selects 2 cards and the cards are face up. 

The user starts off with 5-star rating and will loose a star after each 10 moves.  After 40 or more moves the user can only achieve a 1-star rating. 
The clock will stop when the user has matched all 16 cards / 8 matching sets. 

# End Of Game:
The game is complete after 8 successful matches.
