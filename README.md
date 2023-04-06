# Pong Game
This is a simple implementation of the classic game Pong using Python's Turtle graphics library. The game features two paddles, a ball, and a scoreboard to keep track of the scores. The paddles can be controlled using the keyboard, and the objective is to bounce the ball off the paddles and prevent it from hitting the walls behind them. Players earn points when the opponent misses the ball.

# Installation
To run the Pong game on your local machine, follow these steps:  
  
Install 
~~~
Python 3.x
~~~  
on your computer if you haven't already.  
Clone this repository or download the main.py file.  
Make sure you have the required dependencies installed. The game uses:
~~~
Turtle graphics library
~~~
which is a standard Python library and should be included in most Python installations.  
Open a terminal or command prompt and navigate to the directory where the main.py file is located.  
Run the:
~~~
main.py
~~~

# How to Play  
* Use the up and down arrow keys to control the right paddle.  
* Use the 'w' and 's' keys to control the left paddle.  
* The objective is to bounce the ball off the paddles and prevent it from hitting the walls behind them.  
* Earn points when the opponent misses the ball.  
* The game continues until you close the game window.  

# Game Controls

~~~
Right Paddle:

Up Arrow Key: Move the paddle up  
Down Arrow Key: Move the paddle down
~~~
~~~
Left Paddle:

'w' Key: Move the paddle up
's' Key: Move the paddle down
~~~
To exit the game, simply close the game window.  

# Game Features
~~~
Paddles: The game features two paddles, one on the right side and one on the left side, which can be controlled using the keyboard.

Ball: The game features a ball that moves around the screen and bounces off the paddles and walls.

Scoreboard: The game features a scoreboard that keeps track of the scores for both players.   
The left player's score is displayed on the left side, and the right player's score is displayed on the right side.

Ball Speed: The speed of the ball increases slightly with each paddle collision, making the game more challenging as it progresses.

Game Over: The game continues until you close the game window, and there is no game over screen or restart option.   
Simply restart the game by running the main.py file again.
~~~

# Interface

![Pong Game](https://github.com/filosoho/Pong-Game/blob/8e784b251249af589acccccce9bec029db535074/1.png)  

![Pong Game](https://github.com/filosoho/Pong-Game/blob/8e784b251249af589acccccce9bec029db535074/2.png)  

![Pong Game](https://github.com/filosoho/Pong-Game/blob/8e784b251249af589acccccce9bec029db535074/3.png) 


# Acknowledgements
This Pong game implementation is inspired by the classic Atari Pong game and was created using Python's Turtle graphics library. Turtle is a standard Python library that provides an easy way to create graphics and games in Python.  

The implementation includes the following classes:
~~~
Paddle: Represents the paddles in the game.   
It has methods to move the paddles up and down.

Ball: Represents the ball in the game.   
It has methods to move the ball, detect collisions, and reset the ball's position.

Scoreboard: Represents the scoreboard in the game.   
It keeps track of the scores for both players and updates the scoreboard accordingly.
~~~

The game logic is implemented using a simple game loop that continuously updates the screen, moves the ball, and checks for collisions.   
The game loop continues until the game window is closed.

Enjoy playing the Pong game!

# Contributing
If you would like to contribute to this program, feel free to submit a pull request. Please include a detailed description of the changes made and the reasons for the changes.

# License
Feel free to use and modify the code as per your requirements.  
