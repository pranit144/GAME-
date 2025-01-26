# Maze Game

## Overview
Maze Game is an interactive web application where users can generate and navigate through a randomly generated maze. Players can select difficulty levels and use keyboard controls to guide the player sprite to the finish point. The game offers dynamic visuals, animations, and a responsive design for an immersive experience.

## Features
- Randomly generated mazes with increasing difficulty levels.
- Smooth animations and visually appealing gradient background.
- Keyboard controls for player movement.
- Victory message display upon successful maze completion.
- Fully responsive design.

## Technologies Used
- **HTML5**: Markup structure for the game interface.
- **CSS3**: Styling with animations, transitions, and responsive design.
- **JavaScript (ES6)**: Maze generation, rendering, and user interactions.
- **Canvas API**: Rendering the maze and player sprite dynamically.
- **jQuery**: Simplified DOM manipulation.

## How It Works
1. **Maze Generation**:
   - The maze is generated using a depth-first search algorithm to ensure a solvable path.
   - Walls and paths are dynamically drawn on a canvas element.

2. **Player Movement**:
   - Users control the player sprite using arrow keys.
   - Movement is restricted by maze walls, and the game ends when the player reaches the finish point.

3. **Victory Condition**:
   - The game displays a victory message when the player successfully completes the maze.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/maze-game.git
   ```

2. Navigate to the project folder:
   ```bash
   cd maze-game
   ```

3. Open the `index.html` file in a web browser:
   ```bash
   open index.html
   ```

## Usage
1. Open the game in your browser.
2. Choose a difficulty level from the menu.
3. Click the "Generate Maze" button.
4. Use the arrow keys to move the player sprite through the maze.
5. Reach the finish point to complete the maze and see the victory message.

## Folder Structure
```
maze-game/
├── index.html       # Main HTML file
├── style.css        # Styling for the game
├── script.js        # JavaScript for maze generation and player interaction
├── assets/          # Images and other static assets
└── README.md        # Project documentation
```

## Future Enhancements
- Add touch controls for mobile devices.
- Implement a timer to challenge players to complete mazes faster.
- Introduce scoring based on performance.
- Add sound effects and background music.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.


