# Hangman Game

A classic implementation of the Hangman word guessing game, available in both Java and Python. This interactive game challenges players to guess a hidden word one letter at a time, with a limited number of allowed mistakes before the game ends. Choose your preferred programming language version to play!

## Features

- Classic Hangman gameplay
- Word selection from a curated dictionary
- Visual representation of the hangman's gallows
- Letter tracking for guessed letters
- Score tracking
- User-friendly interface
- Available in both Java and Python implementations

## Getting Started

### Prerequisites

For Python version:
- Python 3.7 or higher

For Java version:
- Java JDK 8 or higher
- Maven (for dependency management)

### Installation

#### Python Version

1. Clone the repository:
```bash
git clone https://github.com/yourusername/hangman.git
cd hangman
```

2. Set up a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

#### Java Version

1. Clone the repository (if not already done):
```bash
git clone https://github.com/yourusername/hangman.git
cd hangman
```

2. Build the project:
```bash
mvn clean install
```

## How to Play

### Python Version
1. Run the game:
```bash
python main.py
```

### Java Version
1. Run the game:
```bash
java -jar target/hangman.jar
```

Game Instructions:
1. The game will select a random word and display blank spaces for each letter
2. Guess one letter at a time
3. You have 6 lives (attempts) to guess the word correctly
4. The game ends when you either:
   - Successfully guess the word
   - Run out of lives

## Game Rules

- Each incorrect guess adds a part to the hangman drawing
- Correct guesses reveal all instances of that letter in the word
- You can't guess the same letter twice
- You lose when the hangman drawing is complete (after 6 incorrect guesses)
- You win when you reveal all letters in the word

## Project Structure

```
hangman/
├── python/           # Python implementation
│   ├── main.py
│   └── requirements.txt
├── java/            # Java implementation
│   ├── src/
│   └── pom.xml
└── README.md
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to all contributors who have helped with this project
- Inspired by the classic Hangman paper and pencil game 