# AI-Based-Number-Guessing-Game_202401100300168
Introduction:
AI-based number guessing games uƟlize arƟficial 
intelligence techniques to enhance tradiƟonal 
gameplay, making it more interacƟve and engaging. 
These games oŌen involve the AI aƩempƟng to 
deduce a number chosen by the player through a 
series of guesses, leveraging algorithms to improve its 
guessing strategy over Ɵme.Overview of AI-Based 
Number Guessing Game.

Methodology:

The game employs a binary search algorithm, a highly efficient method for finding a target value within a sorted range. The algorithm works as follows:

Initialization:
The user selects a number within a predetermined range (e.g., 1 to 100).
The computer initializes two variables, low and high, representing the lower and upper bounds of the search range.
Guessing:
The computer calculates the midpoint of the current search range: guess = (low + high) // 2.
The computer presents this guess to the user.
Feedback and Adjustment:
The user provides feedback:
"C" (Correct): The computer has guessed the number. The game ends.
"H" (High): The user's number is lower than the computer's guess. The computer updates the high variable to guess - 1.
"L" (Low): The user's number is higher than the computer's guess. The computer updates the low variable to guess + 1.
The process repeats from the "Guessing" step until the correct number is found.
