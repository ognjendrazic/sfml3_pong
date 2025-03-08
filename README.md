# Pong Game

A simple Pong game implementation using **SFML 3** in **C++** with player controls, scoring, AI opponent, and sound effects.

## Features

- **Graphical Window**: A game window with a defined size.
- **Player Controls**: Players can control paddles to move up and down.
- **Screen Boundaries**: Prevents paddles from moving outside the screen.
- **Ball Mechanics**: A ball that bounces off walls and paddles.
- **Random Ball Movement**: The ball starts with a random direction.
- **Scoring System**: Tracks and displays player scores, resetting the ball after scoring.
- **Winning Condition**: Defines a winning score and displays a victory message.
- **Increasing Difficulty**: Ball speed gradually increases after each paddle collision.
- **AI Opponent**: A simple AI that follows the ball.
- **Sound Effects**: Adds sound effects for collisions and scoring.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/ognjendrazic/sfml3_pong.git
   ```
2. Navigate to the project directory:
   ```sh
   cd pong-game
   ```
3. Install **SFML 3**:
   - On Windows:
     - Download and install SFML from [SFML's official website](https://www.sfml-dev.org/).
     - Link SFML libraries in your project.
   - On Linux/macOS:
     ```sh
     sudo apt install libsfml-dev  # Linux
     brew install sfml  # macOS
     ```
4. Compile the project:
   ```sh
   g++ -o pong pong.cpp -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
   ```
5. Run the game:
   ```sh
   ./pong
   ```

## Controls

- **Player 1 (Left Paddle)**:
  - `W` - Move up
  - `S` - Move down

- **Player 2 / AI (Right Paddle)**:
  - `Up Arrow` - Move up
  - `Down Arrow` - Move down

## Scoring & Winning

- Players score when the opponent fails to hit the ball.
- The ball resets after a score.
- The first player to reach the defined winning score wins the game.

## AI Opponent

- The AI follows the ball's Y-axis movement with a slight delay.

## Sound Effects

- Sounds play for ball collisions and scoring events.

## Future Enhancements

- Power-ups or special effects.
- Multiplayer online mode.
- Enhanced AI difficulty levels.

## License

This project is open-source and available under the MIT License.

---

Enjoy playing Pong! 🏓

