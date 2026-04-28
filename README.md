#Python Hangman Game

A classic terminal-based Hangman game built with Python. This project features a modular design, separating game logic from data and visual assets, making it easy to read and expand.

🔍 Overview
This implementation of Hangman challenges players to guess a hidden word, one letter at a time, before the "hangman" is fully drawn. It utilizes Python's random module for word selection and demonstrates effective use of dictionary/list structures for state management.

📂 Project Structure
The code is split into three main modules:

Hangman.py: The main engine that handles user input, move validation, and the game loop.

hangman_visual.py: Contains the ASCII art representations for each stage of the hangman.

words.py: A large library of potential words used for the game.

✨ Features
Modular Codebase: Easy to update the word list or visual style without touching the core logic.

Dynamic ASCII Visuals: The hangman figure grows with every incorrect guess.

Word Randomization: Uses a dedicated word bank to ensure a fresh experience every round.

Clean Terminal UI: Clearly displays guessed letters, remaining lives, and the current progress of the hidden word.

🕹 How to Play
1. The computer selects a random secret word.

2. You will see a series of underscores (_) representing each letter of the word.

3. Type a letter and press Enter.

   i. If correct: The letter is revealed in its correct position.

   ii. If incorrect: You lose a life, and a piece of the hangman is drawn.

4. Keep guessing until you complete the word or run out of lives!

**Author**

**Suffisant Madhikarmi**
