
# TargetFury-Aim_Trainer_Game-

Aim Trainer is a simple game built with Python and Pygame to help players improve their mouse precision and reaction time. The goal of the game is to click on red targets that appear randomly on the screen. Each target grows and shrinks, and you need to click on it before it disappears. The game tracks your hits, misses, and overall speed.

## Features

- **Growing Targets**: Red targets that increase and decrease in size.
- **Time Tracking**: Displays elapsed time and target shooting speed.
- **Lives System**: You have a limited number of lives, and each missed target reduces them.
- **Statistics**: Shows your performance with stats such as hits, speed, and accuracy.
- **End Screen**: Displays a summary of your performance when the game ends.

## Installation

To play the game, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/aim-trainer.git
2.Navigate into the project folder:
 cd aim-trainer
 
3.Install the required dependencies:
pip install pygame

Usage
Once the dependencies are installed, run the game by executing the following:
python aim_trainer.py

The game window will open. You can click on the targets to score points. The game ends when you run out of lives.

Controls
Mouse: Click on the targets to score points.
Keyboard: Press any key or close the window to end the game and view the final score.

Gameplay
Targets: Red circles appear on the screen at random locations. The circles grow and shrink.
Objective: Click on the targets to score points. Each target that is clicked counts as a "hit."
Lives: You start with 3 lives. If a target disappears without being clicked, you lose a life.
End Game: The game ends when you lose all your lives, and the final statistics (speed, hits, accuracy) are displayed.

Key Variables
WIDTH: Width of the game window (800 pixels).
HEIGHT: Height of the game window (600 pixels).
TARGET_INCREMENT: Time interval (in milliseconds) at which a new target appears (400ms).
LIVES: Number of lives the player starts with (3 lives).
BG_COLOR: Background color of the game window (dark blue).

Customization
You can modify the following parameters to adjust the difficulty or appearance:

TARGET_INCREMENT: Adjust the speed at which new targets appear.
TARGET_PADDING: Modify the padding between the targets and the edges of the window.
MAX_SIZE: Change the maximum size of the targets.
GROWTH_RATE: Adjust the rate at which targets grow or shrink.

Technologies Used
Python 3.x
Pygame (for graphical display and event handling)

Contributing
If you'd like to contribute to the project, feel free to fork the repository and submit a pull request with your changes. You can also open an issue to suggest new features or improvements.

Acknowledgements
Pygame for the graphical and event-handling library.
Inspiration from various aiming and reaction time games.

Happy training! 🏆

This `README.md` file provides a brief overview of the game, instructions for installing and running the game, as well as details about the gameplay mechanics, variables, and technologies used. Feel free to customize any part of it to better fit your project!
