# tic-tac-toe-with-python
Creating Tic-tac-toe using Python Language from scratch.  Tic-tac-toe is a two-player game, that is played on a 3×3 square grid. Each player occupies a cell in turns, with the objective of placing three marks in a horizontal, vertical, or diagonal pattern. One player uses cross 'X' as his marker, while the other uses a naught 'O'.

-----------------------------------
Step 1: Creating the board
  In order to choose a position the player must enter the corresponding number shown in the grid
  
![Image of Grid](https://gurmeet.net/Images/puzzles/fifteen_sum.gif)

-----------------------------------
Step 2: Storing the information
  At all time we must know the status of the board and the players movement

-----------------------------------
Step 3: Game Loop
  Our game loop runs until some player wins or the game ends in a draw. In tic-tac-toe, each loop iteration refers to a single move any player makes.
  
-----------------------------------
Step 4: Handeling Players move
  In every game iteration, a player must input his move.
  We can create a try block, in case a player enters some wrong value. Such an event must not stop the game, therefore, we handle the exception of ValueError and continue with our game.
  
-----------------------------------
Step 5: Updating the Data
  We need to update the data according to the player's input
  
-----------------------------------
Step 6: Check for win or draw:
  After each move, we have to check whether any player won the game or the game has been drawn.
  
-----------------------------------
Step 7: Switch the current player
  Since each player only moves once at a time, therefore after every successful move, we have to swap the current player.
  
-----------------------------------
Step 8: Create scoreboard
  The scoreboard is stored as a dictionary, where keys are the player names and values are their win number.
  
-----------------------------------
Step 9: Updating  the scoreboard
  We need to update the scoreboard after each match of Tic-tac-toe.
  If the game has not ended in a draw, then we update the scoreboard.
  
