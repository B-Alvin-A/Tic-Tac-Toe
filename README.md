# Tic-Tac-Toe
This is a simple implementation of the classic game Tic Tac Toe (also known as Noughts and Crosses) using HTML, CSS, and JavaScript.

The HTML structure includes a game container that contains 9 cells, each with a unique data attribute to identify its index. There are also two headings, one for the game title and one for the game status, and a restart button.

The CSS styles define the appearance of the game container and cells, including font, box-shadow, border, and cursor styles.

The JavaScript code defines the game mechanics and behavior. It initializes the game state, including the current player, game status, and game state array to keep track of moves. It also defines the winning conditions, messages to display for a win or draw, and functions to handle cell clicks, player change, result validation, and game restart.

When a cell is clicked, the handleCellClick function is called to update the game state, display the current player's symbol on the cell, and validate the game results to determine if there is a win or draw. If the game ends, the gameActive variable is set to false, and the status display is updated to show the winning or draw message. If the game is still active, the handlePlayerChange function is called to switch to the next player's turn.

When the restart button is clicked, the handleRestartGame function is called to reset the game state and clear the board to start a new game.
