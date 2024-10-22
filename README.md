# Word Guessing Game (Hangman Style)

## Project Description
This Python program is a word guessing game (similar to Hangman), where the user tries to guess a randomly selected word by guessing one letter at a time. The program displays the word with blanks for the unguessed letters and limits the number of attempts the user can make. It tracks the user's guessed letters and the remaining number of attempts.

## Features
- Randomly selects a word from a predefined list.
- Displays the word with blanks (`_`) for unguessed letters.
- Updates the displayed word state after each correct guess.
- Limits the number of incorrect attempts (default is 6).
- Tracks the letters the user has guessed so far.

## How It Works
1. The program randomly selects a word from a list of words.
2. The word is displayed as blanks (`_`) for each unguessed letter.
3. The user guesses one letter at a time.
4. After each guess, the program updates the word display:
   - If the guessed letter is in the word, it replaces the corresponding blanks with the letter.
   - If the guessed letter is not in the word, the program decreases the number of remaining attempts.
5. The game continues until:
   - The user guesses all the letters of the word correctly, or
   - The user runs out of attempts.
6. The program displays whether the user won or lost at the end of the game.

## Requirements
- Python 3.x

## How to Run the Script
1. Clone or download the project.
2. Open a terminal or command prompt in the project directory.
3. Run the following command:
   ```bash
   python word_guessing_game.py
