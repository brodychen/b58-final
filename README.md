# b58-final
Final Project For CSCB58 - Tron Lightcycle Game	

Group:

	Adnan Shahid, 	1002385741
	
	Brody Chen, 	  1002262115
	
	Salman Sharif,  1002575331

<b>Video was recorded by TA Faisal </b>

Project Description
Originally, our objective was to recreate the classic snake games, but due to difficulties figuring out how to randomly generate coordinates for food to spawn, we decided to change the project to a 2 player game.

For our project, we used the DE2 board along with the breadboards and some buttons to create  a game similar to the Tron Lightcycle game. 
In the game, both players must hit the reset button (on the breadboard) at the same time to begin. Immediately upon start, the two player objects constantly keep moving, drawing blocks behind them for a trail going indefinitely. The players may use any of four directional buttons (button on the breadboard) to move their snake object in a desired direction (up, down, left, right). If either player connects to the trail of another player (including their own trail), or connects with the border (drawn border on edges of the screen), the game will end and a colored screen will appear. In addition to this, on start of the game, a counter is shown using the HEX display to show the score or game length. The counter is stopped when either player loses and is reset upon each start of the game. The players may hit the reset button at any time to restart the game

The speed of the players are determined by a a module that works similarly to a rate divider.

The VGA code works by refreshing every single pixel each clock tick. As the VGA goes through each pixel, it checks what object that pixel is a part of, and it displays a different colour depending on the pixel’s state. The coordinates of each object(border, player 1, player2) are stored in different arrays. A number of always blocks determined what object the pixel is depending on its coordinate.

We have also attached a design for the breadboards we used as controllers.
