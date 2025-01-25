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

## File Handling

The game also involves file handling to keep track of player data. Here's how it works:
- **Opening File**: The game opens a file named `Player_data.txt` in append mode to store player information and game results.
- **Writing Data**: Player names, game duration, and the date and time are written to the file.
- **Closing File**: The file is closed after writing all necessary data.

## Time Tracking

The game tracks the duration and logs the current date and time:
- **start_time**: The game records the start time using `time.time()` at the beginning of the game.
- **end_time**: The game records the end time when a player wins.
- **Game Duration**: The duration is calculated by subtracting `start_time` from `end_time` and is displayed in seconds.
- **Current Date and Time**: The game logs the current date and time using `time.strftime("%d-%m-%Y  %H:%M:%S")` when a player wins.

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
⏳ Game_time=> 120.45 Seconds
Current_Data_and_time=25-01-2025  08:34:00
**Linkedin:** https://www.linkedin.com/posts/priyanshu-gupta-a37464309_python-gameabrdevelopment-blazeforge-activity-7288754568627179520-lfa5?utm_source=share&utm_medium=member_android  
