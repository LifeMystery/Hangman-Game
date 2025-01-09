# Hangman Game

This is a simple Hangman game implemented in Python. Players attempt to guess a randomly selected word by guessing its letters one at a time. The game includes features like random word selection, fetching words from an API, and drawing a hangman figure.

## Features

- Randomly selects a word from a file or fetches words from an API.
- Allows players to guess missing letters of the word.
- Tracks the number of incorrect guesses with a visual representation of a hangman.
- Exits the game when the player types `exit` or `quit`.
- Provides an option to use default or user-provided words.

## Requirements

The following Python packages are required to run the program:

- `requests`

Install dependencies using:

```bash
pip install -r requirements.txt


## How to Run
1. Clone or download this repository to your local machine.
2. Open a terminal and navigate to the project directory.
3. Run the program using Python: 
python3 game.py

## Follow the prompts:
* Enter a word category or leave it blank to use default words.
* Guess the missing letters of the word.
* Type exit or quit to leave the game.

## File Structure

Hangman-Game/
│
├── game.py              # Main program file
├── words.txt            # Default words list
├── requirements.txt     # Dependencies
└── README.md            # Project description


## Sample Gameplay

Enter any word, [leave empty to use default words]:
Guess the word: _ _ e d
Guess the missing letter: f
Correct! The word is: f _ e d
Guess the missing letter: e
Wrong! Number of guesses left: 4
/----
|   0
|
|
|
_______
...


Custom Word List
If you'd like to use your own word list, create a text file (e.g., my_words.txt) with one word per line and provide its name when prompted.

API Word Fetching
You can fetch words related to a specific category using the Datamuse API. Enter a category (e.g., "animals" or "technology") when prompted, and the program will retrieve and use those words for the game.

Future Improvements
* Add a graphical interface.
* Improve word categorization and validation.
* Enhance user experience with more detailed instructions.
