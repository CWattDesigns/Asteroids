# Asteroids
Using vanilla JavaScript, I was able to recreate the game Asteroids with the help of a tutorial by freeCodeCamp. I extended this tutorial by adding randomly generated stars to the map, changing the way the audio files are accessed and handled, and adjusting smaller features throughout the code.

The HTML generates a space canvas in a browser window that is then populated with player lives, the previous highscore (stored locally), the current player score, the spaceship, and the first round of asteroids. The game also accounts for the edge of the screen, allowing objects such as the ship, asteroids, and lasers to reappear on the other side of the screen when they cross the boundary.

CONTROLS:
Thrust: Up arrow key
Rotate ship: left and right arrow keys
Shoot: Spacebar

As a player progresses through the level, they will experience sounds tied to thrusting, ship collisions, lasers being fired, and laser collisions with the asteroids. The game is also set up to get increasingly harder with each round. The number of asteroids and how fast they move increases with each level the player beats.

***The sounds folder needs to exist in the same directory as the HTML file in order to play this game with the audio.
