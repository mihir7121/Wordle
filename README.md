# Wordle

Wordle is a web-based word game created by Josh Wardle. The goal is to guess a random 5 letter word in 6 tries or less.

## How to Play

- The game will pick a random 5 letter word. 
- You enter a 5 letter word guess.
- The letters in your guess will turn green, yellow, or gray:
  - Green - the letter is in the word and in the correct spot.
  - Yellow - the letter is in the word but in the wrong spot. 
  - Gray - the letter is not in the word.
- Use the information from your previous guesses to narrow down what the word might be.  
- You have 6 tries to guess the word.

## Running the Game Locally

To run Wordle locally:

1. Clone this repo
2. Install live-server: `npm install -g live-server`
3. Navigate to the repo directory 
4. Run `npx live-server`
5. The game will open in your browser at [http://127.0.0.1:8080/build/](http://127.0.0.1:8080/build/)
6. Start guessing!

Good luck and have fun!
