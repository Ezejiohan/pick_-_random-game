Hangman – Python Word Guessing Game

Hangman is a classic word guessing game implemented in Python. The player tries to guess a hidden word by suggesting letters one at a time. Incorrect guesses reduce the player’s lives until the word is guessed or lives run out.

This version includes ASCII art visuals for the hangman and tracks lives remaining.

🎯 Objective

The goal is to guess the hidden word correctly before running out of lives.

🧠 How the Game Works

A word is randomly selected from a predefined list (word_list from hangman_words.py).

The player sees the Hangman logo and a series of underscores representing each letter in the word.

The player guesses one letter at a time:

Correct guesses reveal the letter in the word.

Incorrect guesses reduce lives by 1.

Repeated guesses are acknowledged, but don’t penalize the player.

The game displays ASCII art stages from hangman_art.py to visualize remaining lives.

The game ends when:

All letters are correctly guessed (win)

Lives reach 0 (lose), showing the correct word.

🧠 Concepts Used

Random selection with random.choice()

Loops (while) and iteration (for)

Conditional statements (if, elif, else)

Lists for tracking correct letters

String manipulation and concatenation

Modular code with imports (hangman_words, hangman_art)

ASCII art display
