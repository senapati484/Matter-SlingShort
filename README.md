# Matter-SlingShot

This is a simple physics-based slingshot game made using the Matter.js physics engine. The game allows you to interact with objects using the mouse, launching a ball at a stack of polygons. The game simulates realistic physics, including gravity, collision, and constraints.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How It Works](#how-it-works)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

**Matter-SlingShot** is a browser-based physics simulation project that demonstrates how to create a slingshot mechanism using the Matter.js physics engine. The project involves launching a ball at a stack of polygons to knock them over. The ball can be dragged and released with the mouse to simulate a slingshot. The simulation includes dynamic visuals with random colors for the polygons and consistent colors for the ball.

## Features

- **Realistic Physics**: The simulation accurately models gravity, collision detection, and constraints.
- **Interactive Mouse Controls**: The ball can be dragged and released using the mouse to simulate a slingshot action.
- **Dynamic Visuals**: The polygons have random colors, making each session visually unique.
- **Responsive Design**: The simulation is designed to run in full-screen mode and adjusts to different screen sizes, including a horizontal layout on mobile devices.

## Technologies Used

- **Matter.js**: A 2D physics engine for the web that helps with creating physics-based simulations.
- **HTML5**: The structure of the webpage.
- **JavaScript**: The logic and functionality of the game.
- **CSS3**: Basic styling to ensure the game runs full screen and looks visually appealing.

## How It Works

1. **Engine Creation**: The Matter.js engine is created to handle the physics simulation.
2. **Renderer Setup**: The renderer displays the simulation on a canvas element in the browser. It is set up to occupy the entire viewport.
3. **Objects Creation**: 
   - A ball is created with a consistent color, which acts as the projectile.
   - A stack of polygons with random colors is created to act as the targets.
   - A ground body is created to stop objects from falling infinitely.
4. **Mouse Interaction**: The mouse constraint allows the user to click and drag the ball, simulating a slingshot. When the ball is released, it is launched at the polygons.
5. **Simulation**: The Matter.js engine continuously updates the positions of the objects based on the physics simulation, and the renderer displays these updates in real-time.

## Getting Started

### Prerequisites

To run the project, you need:

- A modern web browser (Chrome, Firefox, Safari, Edge).
- A basic text editor if you wish to modify the code (VS Code, Sublime Text, etc.).

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/matter-slingshot.git
