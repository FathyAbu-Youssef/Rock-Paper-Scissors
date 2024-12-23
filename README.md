# Rock Paper Scissors Game

This is a simple implementation of the "Rock, Paper, Scissors" game in C++. The game allows a player to compete against the computer in multiple rounds, and at the end of the game, the overall winner is declared based on the number of rounds won by each player.

## How to Play

1. The game prompts the user to choose between three options: Stone (Rock), Paper, and Scissors.
2. The computer also randomly selects one of the three options.
3. The winner of each round is determined by the following rules:
   - Rock beats Scissors.
   - Scissors beat Paper.
   - Paper beats Rock.
   - If both players choose the same option, it results in a draw.
4. The game keeps track of the number of wins, losses, and draws.
5. At the end of the game, the player can choose to play again or exit.

## Features

- **Multiple rounds:** You can play between 1 and 10 rounds in a single game session.
- **Round results:** After each round, the game shows the choices of both the player and the computer, and the winner of that round.
- **Game results:** At the end of the game, the total wins for both the player and the computer, as well as the number of draws, are displayed.
- **Screen colors:** The game screen changes colors based on the outcome of each round (Green for the player’s win, Red for the computer’s win, and Yellow for a draw).

## How to Run

1. **Compile the program**:
   - Open the code in your preferred C++ IDE (e.g., Visual Studio).
   - Build the project.

2. **Run the program**:
   - Execute the program.
   - Follow the on-screen prompts to choose your options and play the game.

## Example Output
How Many Rounds 1 to 10? 
3

Round [1] begins:
Your Choice: [1]:Stone, [2]:Paper, [3]:Scissors? 1
Player1 Choice: Stone
Computer Choice: Paper
Round Winner: Computer

Round [2] begins:
Your Choice: [1]:Stone, [2]:Paper, [3]:Scissors? 2
Player1 Choice: Paper
Computer Choice: Scissors
Round Winner: Computer

Round [3] begins:
Your Choice: [1]:Stone, [2]:Paper, [3]:Scissors? 3
Player1 Choice: Scissors
Computer Choice: Stone
Round Winner: Computer

Game Over

Game Results:
- Game Rounds: 3
- Player1 Wins: 0
- Computer Wins: 3
- Draws: 0
- Final Winner: Computer

Do you want to play again? Y/N?
