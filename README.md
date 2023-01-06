
#  Battleship 

* The following describes a Python-written game placed in a mock terminal in Heroku, provided by Code Institute. Battleship is a strategy game with origins from World War 1. For more information regarding the History or idea of the game. Please visit Wikipedia-link <a href=https://en.wikipedia.org/wiki/Battleship_(game)>here</a>

* All written code is located in the run.py file. 

* Link to live project <a href=https://battleshipebkalola.herokuapp.com> link </a>

![pp3ebka](https://user-images.githubusercontent.com/117651816/211003213-d041c220-1e18-4c4e-a7a3-475605fe5fce.png)

## Game rules 

To play a written version of the game you start by simply entering your first guess of the row followed by the user's first guess of the column. The board is marked with 8 rows written in numbers and 8 letters which mark the columns.
A miss is marked with a "-" and when the user hits one of the boards ships it's marked with a simple "X"
The game is a single version of the original duo game. The user is every game of the 10 turns provided. 
                
.

## Features

* Random placements of the ships. There are five ships placed randomly on the board. The location of these ships is not available to the user.

* Feedback- the user is provided information about whether provided input is valid or not. The printed feedback is also with information regarding what exact input the game is requested. For example which letters or numbers are asked? If the user signed in an already used combination of rows and columns- an error message pops up. The user is also updated with a print message every time a ship is hit or missed. If the user lost- it's printed game over and if the user is a winner a congratulations message is printed.

* Due to that, the game is a single-player game, every turn of the 10 provided is stacked on top of each other. For the player to easily see game history. And to see how many turns are left.

## Data Model 

I followed a tutorial for the structure of the game and board and the actual battleships are based on classes. The rest of the game has loops and methods and functions.

## Testing 

I tested the game with the CI Python Linter and my written code had syntax problems so I had to rewrite and re-order the code. One of the issues is stack overflow had several solutions for breaking code. See <a href=https://stackoverflow.com/questions/53162/how-can-i-do-a-line-break-line-continuation-in-python
link These solutions led to a nonfunctional game. Also used: https://www.pythonchecker.com/.

## Bugs 
Too long lines in python. This I was not able to fix- therefore left it in the code. The code is functional in the Heroku App.

## Deployment 

Deployment
The game was deployed with a mock terminal from Code Institute in Heroku. Following these steps:
Create a new Heroku App
Create buildpacks Python to start with and finish off with NodeJS.
Link Heroku App to the Github repository.
Press deploy.
Finish.

## Credits 

* https://www.youtube.com/watch?v=MgJBgnsDcF0&ab_channel=CSStudents
* <strong>Biggest credit to following tutorial:</strong> https://www.youtube.com/watch?v=alJH_c9t4zw&ab_channel=KnowledgeMavens
* https://copyassignment.com/battleship-game-code-in-python/
* https://stackoverflow.com/questions/53162/how-can-i-do-a-line-break-line-continuation-in-python
* https://sabe.io/blog/python-print-line-break
* https://en.wikipedia.org/wiki/Battleship_(game)
* https://developer.rhino3d.com/guides/rhinopython/python-statements/
* https://discuss.codecademy.com/t/excellent-battleship-game-written-in-python/430605
* https://www.javatpoint.com/python-random-module






