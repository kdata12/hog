# Game of Hog

In Hog, two players alternate turns trying to be the first to end a turn with at least 100 total points. On each turn, the current player chooses some number of dice to roll, up to 10. That player's score for the turn is the sum of the dice outcomes.
* Sow Sad. If any of the dice outcomes is a 1, the current player's score for the turn is 1.

In a normal game of Hog, those are all the rules. To spice up the game, we'll include some special rules:
* Picky Piggy. A player who chooses to roll zero dice scores the nth digit of the decimal expansion of 1/7 (0.14285714...), where n is the opponent's score. As a special case, if n is 0, the player scores 7 points.
* Hog Pile. After points for the turn are added to the current player's score, if the players' scores are the same, the current player's score doubles.


To initialize, run the following command: python hog_gui.py
