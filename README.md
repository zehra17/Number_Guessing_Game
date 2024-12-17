# Number Guessing Game

## Description
This is a simple number guessing game where the computer randomly selects a number, and the player has to guess it. The player will receive feedback after each guess, whether their guess is too high, too low, or correct.

## Features
- The computer randomly selects a number.
- The user guesses the number within a specified range (1 to 100).
- Feedback is provided for each guess (too high, too low, or correct).

## Requirements
- Python 3.x installed on your system.

## How to Run
1. Clone or download the project to your local machine.
2. Open the project folder in your terminal or preferred IDE.
3. Run the Python script with the following command:
    ```bash
    python number_guessing_game.py
    ```
4. Follow the instructions displayed on the terminal to:
    - Enter your guess.
    - Receive feedback on whether your guess is too high, too low, or correct.
    - Keep guessing until you get the correct number.

## Code Explanation

### Functions:
- **`number_guessing_game()`**: 
  - Selects a random number between 1 and 100.
  - Prompts the player to guess the number.
  - Provides feedback after each guess (too high, too low, or correct).
  - The game continues until the player guesses correctly.

## Example Usage
```
Welcome to the Number Guessing Game!
I have selected a number between 1 and 100. Try to guess it!

Enter your guess: 50
Too low! Try again.

Enter your guess: 75
Too high! Try again.

Enter your guess: 62
Congratulations! You've guessed the number in 3 attempts.
```

## Future Improvements
- Allow the player to play again without restarting the program.
- Add difficulty levels (easy, medium, hard) with different ranges.
- Implement a graphical user interface (GUI) for a more engaging experience.

## License
This project is licensed under the MIT License.
