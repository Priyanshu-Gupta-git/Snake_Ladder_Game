# Snakes and Ladders Game

This is a simple implementation of the classic Snakes and Ladders game in Python.

## How to Play

1. **Roll the Dice**: Players take turns to roll a six-sided dice.
2. **Move your Counter**: Move forward by the number shown on the dice.
3. **Snakes and Ladders**: If you land on a snake, you slide down to its tail. If you land on a ladder, you climb up to the top.
4. **Win the Game**: The first player to reach square 100 wins!

## Code Description

Here's a quick overview of the code:
- **roll_dice()**: This function simulates rolling a six-sided dice.
- **move_players(player, position)**: This function checks if the player has landed on a snake or a ladder and moves them accordingly.
- **play_game()**: This function handles the main game loop, including welcoming players, handling input, rolling the dice, moving players, and checking for a winner.

## Snakes and Ladders

The positions of snakes and ladders are as follows:
- **Snakes**: {16:6, 47:26, 49:11, 56:45, 62:19, 64:50, 87:24, 93:73, 95:75, 99:2}
- **Ladders**: {1:38, 4:14, 9:31, 21:42, 28:84, 36:44, 51:67, 71:91, 80:90}

## Usage

To play the game, run the `play_game()` function. You can choose to play against a computer or a friend.

## Example

Here's a quick example of what the output might look like:

```python
OK, let's start the game!
Player 1 Enter name: Alice
If you want to play with the computer enter <C> and if you want to play with a friend enter <F>: C
Alice's rolled a 5....
Alice is now at position=>5
Computer  's rolled a 3....
Computer  is now at position=>3
...
Congratulations
Alice is victory 🥇
