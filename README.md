
**Number Guessing Game (Object-Oriented Programming)**

**Overview**

This Java program implements a simple number guessing game using object-oriented programming principles. The game generates a random number between 1 and 100, and the player needs to guess the correct number. The game provides feedback on whether the guess is too high or too low until the correct number is guessed.

**How to Play**
1. Run the program.
2. You will be prompted to enter your guess for the randomly generated number.
3. The game will provide feedback on whether your guess is too high, too low, or correct.
4. Repeat the process until you correctly guess the number.
5. The game will display the number of attempts taken to guess the correct number.
   
**Code Structure**

**Game Class:**
1. number: Holds the randomly generated number.
2. numOfGuesses: Tracks the number of attempts taken by the player.
3. inputnum: Holds the user's input guess.
4. Game(): Constructor that initializes the game by generating a random number.
5. takeUserInput(): Takes input from the user for their guess.
6. isCorrectNumber(): Checks if the user's guess is correct and provides feedback.
7. setNumOfGuesses(int numOfGuesses): Sets the number of guesses.
8. getNumOfGuesses(): Gets the number of guesses.
   
**Main Class (number_guessing_game_oops):**
main(): Entry point of the program. Initializes the game and runs the game loop until the correct number is guessed.

**How to Run**
Compile and run the program using a Java compiler or an integrated development environment (IDE) supporting Java.
