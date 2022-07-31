# Angular
2 versions of the application.
Aplication is simulation of service with tetris game with different functionalities.
# Version 1. 
	I. Intro page with intro text and player form
		* Form with two inputs: player name, player email (validation)
  		* Start game button - upon clicking 'start' checking name and email, and notify player, if name and email are fine then store this data and moving to the game page
	II. Game page
		* personalized welcome message (with player name)
		* 'exit game' button which move player to intro page
		* integrated ngx-tetris game
		* indication of the game status (ready, started, paused...)
		* points counting mechanism (each cleared line counts)
		* displaying current amount of points
		* displaying time spent wile playing
		* 'gameplay history' with all actions
			- timestamp
			- action name (player started the game, paused, line cleared...)
			- filterable by event type (ie. show only 'line cleared' events)
			- sortable by timestamp (latest first or oldest first)

Clon / copy project

Initialize a project npm init -y

Install dependencies npm install 

Run ng serve -o

http://localhost:4200/

https://github.com/TomaszJaniszta/Angular_Tetris-game-service-v.1/blob/main/intro.png

https://github.com/TomaszJaniszta/Angular_Tetris-game-service-v.1/blob/main/tetris1.png
