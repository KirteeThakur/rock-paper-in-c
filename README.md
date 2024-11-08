
# Rock-Paper-Scissors Game in C

This repository contains a simple command-line implementation of the classic "Rock-Paper-Scissors" game in C. Play against the computer and test your luck and strategy!

## Features

- **Single-player mode**: Enjoy the game against the computer.
- **Randomized outcomes**: The computer makes its choice randomly each round.
- **Simple gameplay**: A lightweight, terminal-based game that’s easy to play.

## Getting Started

### Prerequisites

- A C compiler, such as GCC

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/rock-paper-scissors.git
   cd rock-paper-scissors
   ```

2. Compile the code:
   ```bash
   gcc rock-paper.c -o rock-paper-scissors
   ```

3. Run the game:
   ```bash
   ./rock-paper-scissors
   ```

## How to Play

- Select one of the three options: Rock, Paper, or Scissors.
- The computer will also randomly select an option.
- The winner is determined using the following rules:
  - Rock beats Scissors
  - Scissors beat Paper
  - Paper beats Rock
- If both selections are the same, it’s a tie.

## Example Gameplay

```plaintext
Choose your option (1 for Rock, 2 for Paper, 3 for Scissors): 2
You chose Paper
Computer chose Rock
You win! Paper beats Rock.
```

## Code Overview

- **rock-paper.c**: The main C program file implementing the game logic.

## License

This project is open-source and available under the [MIT License](LICENSE).
