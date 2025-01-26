# Game Instruction
The computer chooses a secret number: The computer will secretly select a random whole number between 1 and 100 (inclusive).
You make guesses: You will try to guess the computer's secret number. You'll be given a limited number of attempts (usually 7 in the provided code).
Feedback: After each guess, the computer will tell you if your guess was too high, too low, or correct.
Win or Lose: If you guess the correct number before running out of attempts, you win! If you run out of attempts without guessing the correct number, you lose. The computer will then reveal the secret number.

# Game Variables
Comparing the guess to the secret number: The core function of the if statement in this game is to compare the player's guess to the computer's randomly generated secret number. This comparison determines whether the guess is too high, too low, or correct.
Providing feedback: Based on the comparison, the if statement directs the program to provide appropriate feedback to the player. This feedback ("Too high!", "Too low!", or "Congratulations!") guides the player towards the correct answer.
Controlling game flow: The if statement, often used within a while loop, controls the progression of the game. The loop continues as long as the player hasn't guessed the correct number and still has attempts remaining. The if statement within the loop decides whether to continue the loop, end the game with a win, or end the game with a loss.
In essence, the if statement is the decision-making engine of the game. It directs the program's behavior based on the player's input, providing feedback and managing the game's progression until a win or loss condition is met. Without if statements, the game wouldn't be able to compare the guess to the secret number and provide the necessary feedback to the player.
