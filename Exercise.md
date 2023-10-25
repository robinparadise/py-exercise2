**The Treasure Hunt**

Imagine a text-based treasure hunt game. The player starts in a room and has to find the treasure hidden in one of three rooms. You'll create functions and logic for this game.

1. **Game Initialization:**
   Create a Python program that initializes the game by randomly selecting the room where the treasure is hidden. Use a loop to continuously ask the player for their choice of room (1, 2, or 3) until they find the treasure.

2. **Functions and Input:**
   - Make changes to a file in `bugfix-branch`.
   - Create a function `choose_room()` that takes the player's input and returns their choice.
   - Create a function `check_room()` that checks if the player's choice is correct (if it matches the room where the treasure is).
   - Commit the changes in `bugfix-branch`.

3. **Files:**
   - Commit the changes in `bugfix-branch`.
   - Store the game results in a text file. Create a function `save_game_results(player_name, result)` that saves the player's name and result (e.g., "won" or "lost") in a file.

4. **Regular Expressions:**
   - Commit the changes in `main`.
   - Switch back to `main` branch and make changes to the same file.
   - Read the saved game results from the file. Use regular expressions to extract the number of games won and lost by the player.

5. **Git Branch Merging Exercises:**
   With two branches: `bugfix-branch` and `main`. Perform the following Git exercises:
   - Attempt to merge `bugfix-branch` into `main`.
   - Resolve any merge conflicts if they occur.

6. **Git publish all:**
   - Publish all branches to GitHub.
