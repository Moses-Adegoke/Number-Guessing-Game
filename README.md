# Project Title: Number Guessing Game
## Project Author: Moses Adegoke
## Peer Reviewer: Israel Oladeji

## About the Project
This is a number guessing game where the program randomly select a secret number bewteen 1 and 10. However, the user is asked to guess the secret number where is the guess is too high, too low or correct. This command is repeated until the condition is met with a congratulatory message. Therefore, the games has ended. 
## Game Algorithm
1. The program randomly choose a secret number between 1 and 10.
2. The user is prompted to guess the secret number.
3. The program verify the guess with decision control:
    - If the guess is too high, return "Too high."
    - If the guess is too low, return "Too low."
    - If the user secret number is correct, return "Congratulation you won." 
4. The program repeats step 2-3 until correct number is guessed.
5. End the program.



## Review by Israel Oladeji
### Fix a potential user error (Handle non-numeric user input)

### Description
If the user input is somthing that is not a number, for example, special character, string, etc., display a message, 'Invalid input, please enter a number between 1 and 10', and then ask the user to try again.

### Algorithm
IF the user input is not a number, 
    THEN display a message, 'Invalid input, please enter a number between 1 and 10'
    Ask the user to try again
    ELSE continue the normal guessing
END IFESLE



