# 07 Hangman

The Hangman Game is a Python project that challenges users to guess a randomly chosen word by guessing letters individually. This project is built using foundational Python programming concepts, such as loops, conditionals, list manipulation, and external modules. The game allows for a limited number of incorrect guesses, with ASCII art displaying the progress of the hangman figure as lives are lost.

## Features

- **Random Word Selection**: Uses the `random` module to select a word from a predefined list in `hangman_words.py`.
- **User Input Handling**: Captures and processes user input, ensuring consistency by converting inputs to lowercase.
- **Real-Time Feedback**: Displays correct guesses in their respective positions and indicates incorrect guesses with a message.
- **Lives and ASCII Art**: Tracks the number of incorrect guesses (lives) and updates the ASCII art in `hangman_art.py` to reflect the hangman’s progression.
- **Win and Loss Conditions**: Users win by guessing the word correctly, and the game ends in a loss if all lives are used.

## How It Works

1. A random word is selected, and an empty placeholder is created to display the word’s letters as they are guessed.
2. The player is prompted to guess one letter at a time:
   - If the guessed letter is in the word, it is revealed in the placeholder.
   - If the guessed letter is not in the word, a life is deducted, and the hangman graphic updates.
3. The game continues until either the player successfully guesses all letters in the word or loses all lives.
4. Upon completion, the player is notified of a win or a loss and shown the correct word if they did not guess it.


## Installation

1. Clone this repository to your local machine.
2. Ensure `hangman_words.py` and `hangman_art.py` are in the same directory as the main game script.
3. Run the game with:
   ```bash
   python main.py
   ```


---
<section align="center">
  <code>coderBri © 2024</code>
</section>