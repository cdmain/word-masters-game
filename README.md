# Word Masters

A Wordle-inspired word-guessing game where players try to guess a secret five-letter word in six attempts. Built using HTML, CSS, and JavaScript.

## Getting Started

Click here to try the game: [Word Masters Game](https://cdmain.github.io/word-masters-game/)

## How to Play

1. A secret five-letter word is chosen.
2. Players have six guesses to figure out the secret word. After six guesses, they lose.
3. Feedback for each guess is provided:
   - **Green**: The letter is in the correct position.
   - **Yellow**: The letter is in the word but in the wrong position.
   - **Gray**: The letter is not in the word.
4. The game accounts for the exact number of letters in the word. For example:
   - If the player guesses "SPOOL" and the word is "OVERT," one "O" is marked yellow, and the second "O" is not.
5. If the player guesses the correct word, they win, and the game ends with a celebratory animation.

## Features

- **Interactive Gameplay**: Real-time feedback on guesses.
- **Dynamic Styling**: Correct, close, and incorrect guesses are visually distinguished.
- **Responsive Design**: Works on various screen sizes (keyboard is necessary).
- **Loading Animation**: Spinner appears while fetching the word of the day.

## Future Enhancements

- Add keyboard input visualization.
- Track player statistics (e.g., win/loss record).
- Allow custom word input for multiplayer mode.
- Add error handling for the API if the fetch call fails
- Mobile friendly

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- External API for word validation and daily word.

## Notes

- The secret word is fetched from an external API (`https://words.dev-apis.com/word-of-the-day`).
- Validation checks ensure only five letter real words are accepted.
