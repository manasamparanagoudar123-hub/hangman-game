# Hangman Word Guessing Game (Console)

A terminal-based Hangman game built in Python. Guess the hidden word one letter at a time before you run out of attempts.

## Features

- Random word selection from a built-in word list
- ASCII gallows art that updates with each wrong guess
- Masked word display (e.g. `_ o f t _ a r e`)
- Tracks previously guessed letters
- No penalty for repeating a letter
- Input validation (single letters only)
- Victory and defeat screens
- Play again option
- 6 attempts per game

## Requirements

- Python 3
- No external libraries (uses only the standard library `random`)

## How to Run

1. Download or clone this repository.
2. Open a terminal in the project folder.
3. Run:

   python hangman.py

## How to Play

1. A word is chosen at random and shown as blanks.
2. Type one letter and press Enter.
3. Correct letters appear in the word. Wrong letters add a part to the hangman.
4. Win by guessing the whole word. Lose after 6 wrong guesses.

## Concepts Used

- String manipulation
- Sets for tracking guessed letters
- Loops and control flow
- Functions and modular code
- User input validation

