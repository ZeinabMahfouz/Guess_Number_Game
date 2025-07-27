🎯 Number Guessing Game
A simple Python terminal-based game where the computer randomly picks a number, and the player has to guess it within a limited number of tries. The game features three difficulty levels, each with different number ranges and allowed attempts.

📋 Features
Three difficulty levels:

Easy: Range [1 - 10], 3 attempts

Intermediate: Range [1 - 100], 7 attempts

Hard: Range [1 - 1000], 15 attempts

Input validation for difficulty selection

Feedback for guesses: whether to guess higher or lower

Random number generation using Python's random module

🚀 How to Run
Make sure Python is installed on your system (Python 3.x).

Clone the repository or copy the code to a .py file (e.g., guess_game.py).

Run the script:

bash
Copy
Edit
🎮 How to Play
Select a difficulty level (1, 2, or 3).

Try to guess the number within the allowed number of trials.

After each guess, you'll get a hint whether the number is higher or lower.

Win if you guess the number correctly within the trials, or lose if you run out of attempts.

🛠️ Requirements
Python 3.x

No external libraries needed (uses only the built-in random module)

📌 Example
yaml
Copy
Edit
(1) Easy:
        Limits : [1 - 10]
        No. of trials : 3
(2) Intermediate:
        Limits : [1 - 100]
        No. of trials : 7
(3) Hard :
        Limits : [1 - 1000]
        No. of trials 15
please select the game level 1 ,2,3: 2
I guess a number can you guess it : 45
No, Increase!
I guess a number can you guess it : 78
No, Decrease!
...
