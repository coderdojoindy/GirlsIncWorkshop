# Game Template

Need to flesh out a template for the game.

The game should be a single screen game that allows all girls to build the same game play mechanics but with their own settings.  The goal is for the base game to be simple enough that they can get it done in about 4 hours and have an hour to work on embelishment.

Proposal One:

Catch some things, avoid others.

Setting: *describe where the game takes place*
Who is the player playing as?
What are they trying to catch, collect or save?
What are they trying to avoid that decreases their life?


Gameplay:  
+ Player moves their sprite back and forth across the bottom of the screen using the arrow keys or the mouse. 
+ The game displays a health meter (number of lives left), the current score, and the current high score and high scorer's initials.
+ There are two types of sprite, one you have to catch and one you have to avoid.
+ Sprites fall from the top of the screen to the bottom of the screen.
+ Catching a sprite that you are supposed to catch increases your score.
+ Missing a sprite that you are supposed to catch decreases your score.
+ Catching a sprite that you are supposed to avoid makes you lose a life and resets your character to the middle of the screen.
+ When the players lives left is 0 the game is over.  show a game over screen.
+ if the player's score is higher than the last high score, 
  + ask the player for their initials
  + then save the players initials and their high score to a "cloud variable" for highest score.
  + display new initials and new highest score on the game screen.
+ game over screen should allow player to restart the game.

Embelishments:
+ add other types of drop sprite that do things like "+1 life" "double value"
+ make more sprites fall, or the sprites fall faster as the game goes on in lenght (increase difficulty over time.)
+ add a game start screen that has instructions for how to play with a start button.
