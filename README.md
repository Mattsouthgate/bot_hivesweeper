# bot_hivesweeper
A Python Juypter notebook for automated play of the Hivesweeper game.
The game is online at: https://iogames.space/hivesweeper-io and is a multiplayer minesweeper variant based on a hexagon grid - the same geometry as a bee hive.

To use the code launch a Jupter notebook and load the code and assets.

RUNTIME REQUIREMENTS
Team colour to be orange: the HSV filters have been set to recognise this colour as your own.
Browser scaling set to 50%: first to allow more of the board to be seen and second the kernals in 2D convolution of the screen were captured at this scaling factor.

TO USE
In the web browser of the game scale the content to 50% and choose your name.  By default the game assigns your hive a random colour, so in the option pick orange.
Now run the code and start the game manually.  The bot will identify trapped and safe cells and claim them based on local logic.

Why I wrote this?
I have been learning Python for a while now, initially with CodeCombat, but mostly writing utilities and as an alternative to Matlab - entirely due to the license cost.
I stumbled across this game after playing starblast.io, a very good, fun and often challenging/frustrating multiplayer space resource collect and battle game, looking for something a little less frantic.  After playing for a bit I thought it would be interesting to write a bot to play the game, because it is relatively simple and the graphics are undynamic - except for you bee that follows the cursor. 
