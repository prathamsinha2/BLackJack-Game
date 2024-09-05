# BlackJack Game - OOP Project

This project implements a command-line BlackJack game using Object-Oriented Programming (OOP) principles in Python.

## Features

- Full implementation of BlackJack game logic
- Player vs Dealer gameplay
- Betting system with chips
- Handles Ace cards with dynamic value (1 or 11)
- Interactive command-line interface

## Classes

- `Card`: Represents a single playing card
- `Deck`: Represents a deck of 52 cards with methods to shuffle and deal
- `Hand`: Represents a hand of cards for both player and dealer
- `Chips`: Manages the player's chips for betting

## How to Play

1. Run the script in a Python environment
2. Enter the number of chips you want to bet
3. Choose to Hit (H) or Stand (S) based on your hand
4. Try to beat the dealer without going over 21

## Requirements

- Python 3.x
- No additional libraries required (uses only built-in `random` module)

## Usage

```
python blackjack_game.py
```

## Future Improvements

- Add a graphical user interface (GUI)
- Implement multiplayer functionality
- Add more advanced betting options
- Include a tutorial mode for new players

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
