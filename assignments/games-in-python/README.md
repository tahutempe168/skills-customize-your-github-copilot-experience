
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a Hangman game in Python that uses strings, loops, and user input to let players guess a hidden word before their attempts run out.

## 📝 Tasks

### 🛠️  Game Setup and Word Selection

#### Description
Create the game setup so it randomly chooses a secret word from a predefined list and initializes the game state for guesses and remaining attempts.

#### Requirements
Completed program should:
- Select a secret word at random from a list of choices
- Start with a masked version of the word (e.g. `_ _ _ _`)
- Track guessed letters separately from remaining attempts
- Allow the player to guess letters until the game ends

### 🛠️  Gameplay and Win/Lose Logic

#### Description
Implement the main game loop that accepts guesses, updates the displayed word progress, counts incorrect guesses, and ends with a win or lose message.

#### Requirements
Completed program should:
- Reveal correct letters in their positions when guessed
- Reduce remaining attempts for incorrect guesses
- Display the current word progress after each guess
- Show a win message if the word is fully guessed
- Show a lose message if the player runs out of attempts

#### Example
```text
Secret word: python
Guess: p
Progress: p _ _ _ _ _
Remaining attempts: 6
```