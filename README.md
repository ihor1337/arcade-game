frontend-nanodegree-arcade-game
===============================

Rubric : https://www.udacity.com/course/viewer/#!/c-nd001/l-2696458597/m-2687128535

Steps to play this game:
1) Click the "Start Game" button.
2) Start moving the player up/down/left/right using the arrow keys in your keyboard.
3) The goal is to try to reach the top water tile without colliding with the bugs all within the 30 sec. timer limit , that will increase your score
4) Once the timer limit of 30 seconds is over, click "Restart the Game" button and repeat steps 1 to 3

Scoring Rules:
If the player reaches the water without any collision with the bugs(enemies):
	- The score is incremented each time the player manages to reach the water tile without colliding with any of the Enemies.
If the player collides with any of the Enemies:
 	- The player is reset back to the original square.
 	- And the score is decremented.

When is the game done? :
Once the timer of 30secs is over,
	- It means the player's game time is done
	- The player is brought back to the original tile position
	- The score gets displayed to the user
	- A message "Sorry,Game is over." is also displayed indicating the player's time is up.

Restart the game:
The user can restart a new game by clicking the "Restart the Game" button.
	- Once again, the timer is started counting down from 30secs to 0.
The same game rules as above apply.

Resources:
http://www.html5canvastutorials.com/tutorials/html5-canvas-element/
Udacity : HTML5 Game development course https://www.udacity.com/course/viewer#!/c-cs255
http://www.webplatform.org/
http://www.phpied.com/3-ways-to-define-a-javascript-class/
http://www.ibm.com/developerworks/library/wa-oojavascript/
