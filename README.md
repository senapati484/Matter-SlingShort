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
   git clone https://github.com/senapati484/Matter-SlingShort.git
2. **Open the index.html file in your web browser:**:
   - You can double-click the index.html file or open it through your browser's "Open File" dialog.

## Usage

Once you open the project in a web browser:

1. **Interact with the Ball**: Click and drag the ball with your mouse. The ball will follow your mouse movement.
2. **Release the Ball**: Let go of the mouse button to launch the ball towards the stack of polygons.
3. **Watch the Simulation**: The ball will interact with the polygons, knocking them over based on the physics simulation.
4. **Reset and Try Again**: After each launch, a new ball will automatically appear, allowing you to try again.

## Customization

You can customize the project to fit your needs:

- **Change the Ball Color**: Modify the `ballColor` variable in the JavaScript code to change the ball's color.
- **Modify Polygon Stack**: Change the number of rows, columns, and shape of polygons by adjusting the `Matter.Composites.stack` parameters.
- **Alter Physics Properties**: Adjust properties like `stiffness`, `restitution`, or `density` of the objects to change how they behave during the simulation.

## Contributing

If you'd like to contribute to the project:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bugfix.
3. **Make your changes** and commit them with descriptive messages.
4. **Push your changes** to your forked repository.
5. **Submit a pull request** with a detailed explanation of your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

