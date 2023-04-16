# Guess The Word
Guess The Word is a simple word guessing game built with HTML, CSS, and JavaScript. The game is played by guessing a word letter by letter, and the player can only guess up to a certain number of incorrect letters before losing the game. The game comes with a list of words that can be easily modified or extended.

## Features
- Simple and intuitive UI
- A list of pre-defined words to guess
- User input validation to ensure that only letters are entered
- Incorrect letter counter to limit the number of incorrect guesses
- Game restart functionality
## Installation
To use Guess The Word, simply clone or download the repository to your local machine:

```bash
    git clone https://github.com/iammeliaskhan/GuessTheWord.git
```
Once the repository is downloaded, you can simply open the `index.html` file in your browser to play the game.

## Usage
To play the game, simply open the `index.html` file in your browser. The game will start with a randomly selected word from the pre-defined list of words. The word will be displayed as underscores, with each underscore representing a letter in the word. The player can enter a letter in the input field and click the "Guess" button to submit their guess. If the letter is correct, it will be added to the corresponding underscore in the word. If the letter is incorrect, the incorrect letter counter will be incremented, and the player will lose the game if they exceed the maximum allowed incorrect guesses.

Once the player has guessed the word correctly, a message will be displayed congratulating them, and they will have the option to restart the game by clicking the "Play Again" button.

## Customization
Guess The Word comes with a pre-defined list of words that can be easily modified or extended. Simply open the `js/words.js` file and add or remove words from the list to change the set of words that can be guessed.

Future Improvements
Some potential areas for improvement in Guess The Word include:

Adding a timer to the game to add a sense of urgency
Implementing a difficulty level setting to allow players to choose the difficulty of the game
Adding a feature to allow players to input their own words to guess
Credits
Guess The Word was developed by Elias Khan as a personal project. The list of pre-defined words was sourced from various online sources.
