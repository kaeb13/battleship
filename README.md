
#  Battleship 

* A Python written game placed in a mock terminal in Herouku, provided by Code Institute. Battleship is a stratergy game with orgins from World War 1.
For more information regarding the History or idea of the game. Please visit Wikipedia- link <a href=https://en.wikipedia.org/wiki/Battleship_(game)>here</a>

* All written code is located in the run.py file. 

* Link to live project <a href=https://battleshipebkalola.herokuapp.com> link </a>

<img width="1280" alt="Screen Shot 2023-01-06 at 10 27 17" src="https://user-images.githubusercontent.com/117651816/210972451-6428f21e-95a3-4aad-be2a-0aa8a7438e49.png">

## Game rules 

To play written version of the game you start by simple entering your first guess of row followed by users first guess of column. The board is marked
with 8 rows written in numbers and 8 letters which marks the columns. 
 
A miss is marked with a "-" and when user hits one of the boards ships it's marked with a simple "X".

The game is a single version of the orginally duo game and the user is displayed every game of the 10 turns provided. 
                
.

## Features

* Random placements of the ships. There are 5 ships place randomily on the board. The location of these ships are not avaible for 
user. 

* Feedback- the user is provided information about provided input is valid or not. The printed feedback is also with information regarding what exact 
input the game is requested. For example which letters or numbers are asked. If the user signed in an already used combination of rows and columns- a error message pops up. The user is also updated with a print message every time a ship is hit or missed. If user lost- it's printed game over and if the user is a winner a congratulations message is printed. 

* Due to that the game is a single player game, every turn of the 10 provided is stacked on top of each other. For the player to easy see game history. And to see how many turns that are left. 

## Data Model 

I followed a tutorial for the structure of the game and board and the actual battleships is based on classes. The rest of the game have loops and functions. 

## Testing 

I tested the game with the CI Python Linter and my written code had syntax problems and I had to rewrite and re order the code. One of the issues is and 
stack overflow had several solution with breaking code. See <a href=https://stackoverflow.com/questions/53162/how-can-i-do-a-line-break-line-continuation-in-python
>link</a> These solutions led to a non functional game. Also used: https://www.pythonchecker.com/. 

## Bugs 
Too long lines in python. This I was not able to fix- therefor left in the code. The code is functional in the Herouku App.

## Deployment 

Game was deployed with a mock terminal from Code Institute in Heroku. Following these steps: 
1. Create a new Heroku App
2. Create buildpacks Python to start with and finish off with NodeJS. 
3. Link Heroku App to Github repository. 
4. Press deploy. 

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






