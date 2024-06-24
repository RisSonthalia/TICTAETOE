# AI-Powered Tic-Tac-Toe Game

Welcome to the AI-Powered Tic-Tac-Toe game! This classic game is implemented using HTML, CSS, and JavaScript, featuring an intelligent AI opponent that uses the Minimax algorithm for decision-making.

## Live Demo

Experience the game live: [Play Tic-Tac-Toe](https://rissonthalia.github.io/TICTAETOE/)

## Features

- **AI Opponent**: Play against a challenging AI that uses the Minimax algorithm.
- **Responsive Design**: Enjoy smooth gameplay on various devices and screen sizes.
- **Real-Time Interaction**: Experience immediate responses from the AI.
- **Choice of Symbols**: Select your preferred symbol (X or O) before starting the game.
- **Win Detection**: Automatic detection and display of game outcomes (win, lose, or draw).

## Technologies Used

- **HTML5**: Structures the game board and UI elements.
- **CSS3**: Styles the game for an appealing and responsive design.
- **JavaScript (ES6+)**: Implements game logic, AI algorithm, and interactive features.

## How to Play

1. Open the game in your web browser.
2. Choose your symbol (X or O).
3. Click on an empty cell to make your move.
4. The AI will automatically respond with its move.
5. Continue playing until there's a winner or the game ends in a draw.
6. Restart the game to play again!

## Installation

To run the game locally:

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge recommended)
- Git (optional, for cloning)

### Steps

1. **Get the Code**:
   - Option 1: Clone the repository
     ```
     git clone https://github.com/RisSonthalia/TICTAETOE.git
     ```
   - Option 2: Download the ZIP file and extract it

2. **Navigate to the Project Directory**:
   ```
     cd TICTAETOE
     ```
3. **Launch the Game**:
- Double-click on `index.html`, or
- Open `index.html` with your preferred web browser

## Project Structure
TICTAETOE/
├── index.html
├── css/
│   └── styles.css
└── js/
    └── script.js
- `index.html`: Main game structure and layout
- `css/styles.css`: Styling and responsive design
- `js/script.js`: Game logic and AI implementation

## The Minimax Algorithm

The AI opponent utilizes the Minimax algorithm, a recursive decision-making algorithm used in two-player games. Here's how it works:

1. **Recursive Exploration**: The algorithm explores all possible future moves and their outcomes.
2. **Scoring**: Each possible end game state is assigned a score (+10 for AI win, -10 for player win, 0 for draw).
3. **Backtracking**: The algorithm works backwards from end states to determine the best move.
4. **Optimal Decision**: The AI chooses the move that leads to the best possible outcome, assuming the player also plays optimally.

This implementation ensures that the AI is always making the best possible move, making it a formidable opponent.

## Contributing

Contributions are welcome! If you'd like to improve the game:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Developer

- **Name**: [Your Name]
- **GitHub**: [@YourGitHubUsername](https://github.com/YourGitHubUsername)
- **Email**: your.email@example.com

## Acknowledgements

- Inspiration for the Minimax algorithm implementation from various online resources.
- Thanks to the open-source community for providing valuable learning materials on game development and AI algorithms.
- Gratitude to all beta testers who provided feedback during the development process.

---

Enjoy playing Tic-Tac-Toe against the AI! If you encounter any issues or have suggestions for improvements, please open an issue on the GitHub repository. Happy gaming!
