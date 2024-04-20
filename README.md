w and s for player1

UP and DOWN for player2

Pong process work.
- I first needed to tackle the objects, so I created the sprite renderers and customized
the size and positions they start in this was for all walls, the ball, and paddles.
- I then attached 2d colliders to all the objects. This allowed me to make the paddles
and ball not go off screen.
- Added scripts like ball, paddle, game manager, and goal.
- I had to change inputs to allow for 2 players (google helped with that one)
- I added some variables including a bool to check while im in unity so that I can
define what paddle is player 1 and use the inputs accordingly.
- The goal function works by checking if the collision with the ball tagged “ball”
encounters the walls I have designed to be the goal.
- The ball was a little tricky, I had trouble figuring out how to make it move off start, I
had to use google again to help me figure it out.
- The Game Manager script allows me to control the score and reset of both paddles
and the ball position to go back to their original position also keeps track of all the
objects in use.
- I then added the scripts to the according objects and set the values like speed for
the paddles and balls.
- I had trouble with the ball not bouncing properly and moving the paddles, to fix this I
had to lock the paddles X and Z and for the ball it took some time but after some
googling I attached a physics material 2D to it and set friction to 0 and bounciness to
1 and that seem to fix the issue.
After all that I was able to play the game as intended, it is a 2-player version of pong
using “w” and “s” for player 1 and the arrow keys “up” and “down” for player 2.
