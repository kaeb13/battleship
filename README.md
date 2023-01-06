
#  Battleship 

* Battleship is wellknown board game where the player can guess the location of
ships hidden on the board. You can read more specefics about the game on <a href=https://en.wikipedia.org/wiki/Battleship_(game)>Wikipedia.</a>


* All written code is located in the run.py file. 

* Link to live project <a href=https://battleshipebkalola.herokuapp.com> PRESS HERE </a>

## Creating the Heroku app

When you create the app, you will need to add two buildpacks from the _Settings_ tab. The ordering is as follows:

1. `heroku/python`
2. `heroku/nodejs`

You must then create a _Config Var_ called `PORT`. Set this to `8000`

If you have credentials, such as in the Love Sandwiches project, you must create another _Config Var_ called `CREDS` and paste the JSON into the value field.

Connect your GitHub repository and deploy as normal.

## Constraints

The deployment terminal is set to 80 columns by 24 rows. That means that each line of text needs to be 80 characters or less otherwise it will be wrapped onto a second line.

-----
Happy coding!