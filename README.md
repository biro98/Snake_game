# Snake_game
This is a fun project to experiment the pygame library. The project is inspired to the article at: https://www.geeksforgeeks.org/snake-game-in-python-using-pygame-module/.

The code proposed is divided in 3 jupyter notebook:
1) Set_up.ipynb contains the initialization of the game and the definition of the window, snake initial position, fruit and snake initial movement direction
2)Score_game_over_speed.ipynb contains the definition of 3 function which respectively define the score and the score window, the game over condition and the increase of the speed of the snake while eating.
3) main.ipynb contain the main function to run and play the game.

The implementation presented compared to the article includes a function that allows to progressively increase the speed of the snake while eating to a max speed of 50.
In addition, once reached the score 50 it is added a red obstacle static each time the score increase of 10. Once reached 100 as score the obstacles added are moving also. A new moving obstacles appears each time the score increases of 10.
