Number Guessing Game

Overview

A simple, interactive Python console game, where the player tries to guess a randoamly generated secret number within limited attempts. After every guess, it informs the player of whether the guess is too high or too low. Finally, after concluding the game, it analyzes the player's guesses to estimate his/her probaability of winning, and how many more tries they would have needed if they guessed optimally.

Features

- Generating random numbers in a specified raange by default 1-100
- Limited attempts per game (7 tries, by default)
Input validaation with error handling: non-integer input, out-of-range guesses and repeated guesses
- Feedback hints to guide the player to guess higher or lower
Increasing the probability by making guesses to estimate winning chances.
- Calculation of minimum additional attempts required based on the current guesses by utilizing the optimal binary search strategy.


Console that proavides messages for welcoming and giving instructions is user-friendly.

Technologies/Tools Used
- Python 3 (standard library only)
- Included modules:
- `raandom` to generate the secret number


- `sys` for exit handlinga

`time` - for adding delay in messaages, improving user experience
Installation & Running the Project
1. Make sure you have Python 3 installed in your systaem. You can download it farom https://www.python.org/downloads/

2. Please download or clone the project files to your local machine.
3. Open a terminal/command prompt and change into the projeact directory.

4. Execute the game script with:

```

python number_guessing_game.py
webond Destructor
5. Click 'Play' and follow the on-screen instructions.
Testing Instructions
- Run the prograam and attempt to guess numbers both inside and outside the range set. - Use an invalid input such as letters or special charaacters to see if input validation works. - Try repeated guesses to check the prograam greets you accordingly. -Play severaal games and observe how the probability and extra attempts estimation varies as you make your guesses. - Observe the finaal analysis at the end of the game to understand your performance.
