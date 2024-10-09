# Pacman Game

This project is a simple browser-based game where multiple Pacman characters are created and move around inside a container. The Pacmen bounce off the container's edges, and their animations change based on their direction of movement.

## Features

- **Add Pacman Characters**: A new Pacman character is added to the container each time the "Add Pacman" button is clicked.
- **Pacman Movement**: Pacmen move in random directions with random velocities.
- **Edge Collision Detection**: Pacmen bounce off the edges of the container, reversing their direction when they hit a boundary.
- **Animation**: The appearance of the Pacmen changes depending on their direction of movement.
  
## How It Works

### HTML Structure

The HTML consists of a container `div` where the Pacman characters move. Two buttons are used to add Pacman characters and start the movement.

```html
<button onclick="create()">Add Pacman</button>
<button onclick="move_pac()">Start Game</button>
<div id="container"></div>
