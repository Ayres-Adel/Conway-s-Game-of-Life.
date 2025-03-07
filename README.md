# Conway's Game of Life

This is an implementation of **Conway's Game of Life**, a cellular automaton devised by mathematician John Conway. The game is a zero-player game, meaning its evolution is determined by its initial state, requiring no further input.

## Features
- **Interactive Controls**: Start, stop, clear, and randomize the grid.
- **Predefined Patterns**: Glider Gun, Pulsar, and PentaDecathlon.
- **Randomized Placement**: Patterns appear at random positions on the grid.
- **Responsive Design**: Works on all screen sizes.
- **Animations**: Smooth fade-in animations for the title and canvas.
- **Styling**: Modern gradient background and glassmorphism effect.

## How to Use
1. **Start/Stop**: Click the "Start" button to begin the simulation. Click "Stop" to pause it.
2. **Clear**: Click the "Clear" button to reset the grid.
3. **Randomize**: Click the "Random" button to fill the grid with random live cells.
4. **Predefined Patterns**:
   - **Glider Gun**: Click the "Glider Gun" button to place a Glider Gun at a random position.
   - **Pulsar**: Click the "Pulsar" button to place a Pulsar at a random position.
   - **PentaDecathlon**: Click the "PentaDecathlon" button to place a PentaDecathlon at a random position.

## Implementation Details
### HTML
- The structure includes a container for the title, controls, and canvas.
- Buttons are provided for controlling the simulation.

### CSS
- Responsive design using Flexbox and media queries.
- Animations using CSS keyframes.
- Modern styling with gradients and glassmorphism.

### JavaScript
- **Game Class**: Handles the grid, rules, and patterns.
- **Renderer Class**: Manages the canvas rendering.
- Event listeners for button interactions.

## Modifications
1. **Scaled-Up Patterns**:
   - The Glider Gun, Pulsar, and PentaDecathlon patterns are scaled up for better visibility.
2. **Randomized Placement**:
   - Patterns are placed at random positions on the grid.
3. **Improved Design**:
   - Added a gradient background and glassmorphism effect.
   - Enhanced button styling with hover and active effects.
4. **Added Animations**:
   - Fade-in animations for the title and canvas.
5. **Optimized Performance**:
   - Adjusted the interval time to 100ms for smoother animation.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/conways-game-of-life.git
