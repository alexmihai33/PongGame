Pong game rules: this is a 2 player game where 2 paddles are controlled by 2 different players: the left paddle can move up and down with 'w' and 's' keys and the right paddle can move up and down with 'Up' and 'Down' arrows. There is a ball starting in the middle and bouncing off the walls. The goal is to hit the ball with the paddle (everytime the ball is hit, the ball speed increases), if a player misses, the other player gets a point.

This is a pong game made with turtle GUI, in python. The project contains 4 classes:

  1. ball: it defines the ball and it's movements
  2. scoreboard: it defines the writing on the screen (the score), also a method for updating the score
  3. paddle: it defines the paddle, also the methods for moving it
  4. main: it puts everything together, we initialise screen and objects for every class mentioned above, we deal with the movements, applying the movement methods for the paddles and ball, we create a loop in which the game plays, and deal with all the collisions(ball - wall, ball - paddles)
