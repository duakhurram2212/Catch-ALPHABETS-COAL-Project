# Catch-ALPHABETS-COAL-Project
"Catch the falling alphabets before they hit the ground!"  CatchAlphabets is an interactive game built in Assembly Language for DOSBox.
Players control a moving box at the bottom of the screen to catch randomly falling alphabets (A-Z). The box can be moved left or right using arrow keys (or 'A'/'D' keys in multiplayer mode). 

📌 Project Overview
This project is a game titled 'CatchAlphabets', built using Assembly Language. The game simulates falling alphabets that need to be caught using a movable box at the bottom of the screen.
🎮 Game Features & Requirements
•	➡ The game starts on launching the program in DOSBox.
•	🧹 Clears the screen and places a box (ASCII 0xDC) in the center of the bottom row.
•	↔ The box can be moved left and right using arrow keys (Left: 0x4B, Right: 0x4D) using keyboard interrupt (9h).
•	🔡 Random alphabets (A-Z) fall from the top using a provided random subroutine, managed via timer interrupt (8h).
•	⏬ At least 5 alphabets fall simultaneously, each at different speeds.
•	🎯 When an alphabet touches the box, it's caught and 1 point is added to the score.
•	🧮 Score is displayed on the top right, with a timer below or above the score.
•	⚡ Holding SHIFT while moving the box increases movement speed to 2x.
•	⏱️ As score reaches 8 or more, the falling speed of alphabets increases.
•	👥 Multiplayer Mode: Player 2 uses 'A' (left) and 'D' (right) keys. Points are combined for both players.
•	❌ Game ends after missing 10 alphabets. Players are then asked to exit or replay.
•	🏆 Win Conditions:
•	   - Single Player: Score 10 to win.
•	   - Multiplayer: Combined score of 20 to win.


