frontend-nanodegree-arcade-game
===============================

Students should use this [rubric](https://review.udacity.com/#!/projects/2696458597/rubric) for self-checking their submission. Make sure the functions you write are **object-oriented** - either class functions (like Player and Enemy) or class prototype functions such as Enemy.prototype.checkCollisions, and that the keyword 'this' is used appropriately within your class and class prototype functions to refer to the object the function is called upon. Also be sure that the **readme.md** file is updated with your instructions on both how to 1. Run and 2. Play your arcade game.

For detailed instructions on how to get started, check out this [guide](https://docs.google.com/document/d/1v01aScPjSWCCWQLIpFqvg3-vXLH2e8_SZQKC8jNO0Dc/pub?embedded=true).

# Instructions

  - Use Left,Right,Up and Down arrow keys to move the player
  - There are totally 5 levels and player will have 3 lives.
  - Player should reach to the water level to go to the next levels.
  - If player and enemy collision happened Player position will get reset to the initial position at the down to the grass.
  - Whenever player and enemy collision happens lives will get decrement.
  - If Player and enemey collision happened 3 times then lives will get decrement to 0 and "Game over" screen will get display with final score and Play Again button.
  - Player will play again by pressing the "Play Again" button in Game Over screen.
  - If player reaches to the water level then it will take to the Level 2 and score will get increament by 500.
  - From the Level 2 onwards 2 Gems will display randomly till lelel 5.Gems will get reset if player not able to collect it and display 2 new gems at each level.
  - Player can collect the gems and score will get increament by 300 points for each gem collectible.
  - If player completes till Level 5, "Game own" window will get opened with Final score and Play Again button.
