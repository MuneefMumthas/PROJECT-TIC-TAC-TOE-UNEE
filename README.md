## Game Description:
The game has been designed to provide a simple yet engaging experience of the classic Tic-Tac-Toe game, with additional features such as different game modes and difficulty levels. It is developed using **Pygame** and deployed on the web with **Pygbag**, making it accessible in any browser. The objective of the game is to complete a row, column, or diagonal of three marks ("X" or "O") before your opponent does. At the start, both players have equal opportunities, and the game continues until one player wins or the board is filled without a winner, resulting in a draw.

## Features:
1. The game includes a Main Menu with options to start a new game, adjust settings, or exit.
1. Players can choose between Player vs Player (PvP) or Player vs Computer (PvC) modes.
1. In PvC mode, players can select from three difficulty levels:
   *    **Easy**: The computer makes **random** moves.

   *    **Medium**: A combination of **random** moves and the **Minimax algorithm**, alternating between the two.
   *    **Impossible**: The AI uses the **Minimax algorithm** exclusively, ensuring the player cannot win, either forcing a draw or winning. Although the player can't win, this mode is designed to showcase the full capabilities of the **Minimax algorithm**, which analyses the game tree to make optimal decisions.
1. The game uses a **NumPy array** to manage the 3x3 grid, ensuring efficient gameplay.
1. The game includes three visually distinct themes (Cyan, Purple, and Red) that change the background and board lines.
1. Player markings are clear, with dark red (X) and dark blue (O) for easy distinction.
1. A general restart button allows players to restart the game in the current mode and difficulty.
1. Sound effects are included for marking moves, winning, and drawing, enhancing the overall experience.

## Game Screens:

**1. Main Menu:** A simple interface offering the option to start a new game and adjust settings.

**2. Settings Screen:** Provides customization for the game’s UI with theme selection to modify background and board colours.

**3. Mode Selection:** Allows players to choose between **PvP** or **PvC** modes.

**4. Difficulty Selection:** Enables players to choose between **Easy**, **Medium**, or **Impossible** difficulty levels when playing against the AI.

**5. Game Screen:** Displays the 3x3 grid and tracks the player’s moves in a clear and intuitive layout.

**6. Game Over Screen:** Shows the result (win, loss, or draw) with options to play again or return to the main menu.



---

## Screenshots - Game Screens in Different Themes:

### Main Menu

<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Cyan/Main-Menu-Cyan.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Purple/Main-Menu-Purple.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Red/Main-Menu-Red.png" width="350" />

### Settings Screen

<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Cyan/Settings-Cyan.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Purple/Settings-Purple.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Red/Settings-Red.png" width="350" />

### Mode Selection

<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Cyan/Game-Mode-Selection-Cyan.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Purple/Game-Mode-Selection-Purple.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Red/Game-Mode-Selection-Red.png" width="350" />

### Difficulty Selection

<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Cyan/Difficulty-Settings-Cyan.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Purple/Difficulty-Settings-Purple.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Red/Difficulty-Settings-Red.png" width="350" />

### Game Screen - Empty Board

<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Cyan/Empty-Board-Cyan.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Purple/Empty-Board-Purple.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Red/Empty-Board-Red.png" width="350" />

### Game Screen - With Player Markings

<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Cyan/Board-with-marking-Cyan.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Purple/Board-with-marking-Purple.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Red/Board-with-marking-Red.png" width="350" />

### Game Over Screen

<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Cyan/Game-Over-Cyan.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Purple/Game-Over-Purple.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Red/Game-Over-Red.png" width="350" />

## Screenshots - All Possible Wins and Draw:

### Horizontal Wins

<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Wins%20and%20Draws/Horizontal-win-1.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Wins%20and%20Draws/Horizontal-win-2.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Wins%20and%20Draws/Horizontal-win-3.png" width="350" />

### Diagonal Wins

<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Wins%20and%20Draws/Diagonal-win-1.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Wins%20and%20Draws/Diagonal-Win-2.png" width="350" />

### Vertical Wins

<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Wins%20and%20Draws/Vertical-win-1.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Wins%20and%20Draws/Vertical-win-2.png" width="350" />
<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Wins%20and%20Draws/Vertical-win-3.png" width="350" />

### Draw - Full Board

<img src="https://github.com/MuneefMumthas/CO536-Muneef-22206529/blob/main/Screenshots/Wins%20and%20Draws/Draw-Full-Board.png" width="350" />


---
## BlackBox Testing:


| Test Number | Input                                      | Expected Output                                                               | Actual Output                                                              | Status  |
|-----------|--------------------------------------------|-------------------------------------------------------------------------------|-----------------------------------------------------------------------------|---------|
| Test 1    | Start the game from the Main Menu          | Main menu shows options: Start Game and Settings                            | Main menu appears with all options                                          | Pass    |
| Test 2    | Select PvP mode from the Mode Selection    | The game switches to Player vs Player mode                                    | Game switches to PvP mode                                                   | Pass    |
| Test 3    | Select PvC mode from the Mode Selection    | The game switches to Player vs Computer mode                                  | Game switches to PvC mode                                                   | Pass    |
| Test 4    | Choose Easy, Medium, or Impossible difficulty in PvC mode | The game selects the correct difficulty level for the computer               | AI difficulty level is selected correctly (Easy, Medium, Impossible)        | Pass    |
| Test 5    | Start the game with a NumPy array grid     | The grid starts as an empty 3x3 array                                          | The grid appears with empty cells                                           | Pass    |
| Test 6    | Player 1 (X) makes a move in an empty spot | The move is placed correctly as "X"                                           | Player 1's move ("X") is placed on the grid                                 | Pass    |
| Test 7    | Player 2 (O) makes a move in an empty spot | The move is placed correctly as "O"                                           | Player 2's move ("O") is placed on the grid                                 | Pass    |
| Test 8    | Player tries to mark a spot already taken  | The game prevents marking in an already filled spot                           | The game does not allow marking in a spot that's already filled             | Pass    |
| Test 9    | Easy mode (PvC), AI makes a move           | The computer makes a random move                                              | The computer places its mark randomly in an empty spot                      | Pass    |
| Test 10   | Medium mode (PvC), AI makes a move         | The AI alternates between random moves and strategic moves                    | The computer alternates between random and strategic moves                  | Pass    |
| Test 11   | Impossible mode (PvC), AI makes a move     | AI plays optimally to win or force a draw, showing the full power of Minimax | The AI plays the best move to win or force a draw                           | Pass    |
| Test 12   | Game over after win, loss, or draw         | The game shows the correct result after a short delay, then moves to the Game Over screen | The game shows the result after a brief delay, then shows the Game Over screen | Pass    |
| Test 13   | Click the Restart button                   | The game restarts with the current mode and difficulty                        | The game restarts with the correct mode and difficulty                      | Pass    |
| Test 14   | Change the theme to Cyan, Purple, or Red   | The game changes the background and lines to match the selected theme        | The theme changes correctly with different background and line colours      | Pass    |
| Test 15   | Player wins by completing a row, column, or diagonal | The game detects the win and ends correctly                                    | The game correctly detects the win and ends the game                        | Pass    |
| Test 16   | Draw condition (all cells filled)          | The game detects a draw when all cells are filled without a winner           | The game correctly detects a draw and ends the game                         | Pass    |
| Test 17   | Player marks an empty cell                 | The grid updates with the player's mark in the selected cell                 | The grid updates correctly after the player makes a move                    | Pass    |
| Test 18   | Sound effects for button clicks, marking a move, winning, and drawing | The correct sound effects play for each event (button click, marking a move, win, draw) | The correct sound effects play for each action                              | Pass    |

---


## Future Implementations:
1. Implement a new game mode, where players can matchmake from different devices and play against each other.

1. Implement a new mode called ULTIMATE TIC TAC TOE, where players take turns marking squares on a 3x3 grid of smaller Tic Tac Toe boards, trying to get three in a row on the larger board to win. 

***
