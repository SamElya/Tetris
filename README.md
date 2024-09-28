# Tetris

## Overview
Tetris is a popular puzzle game where the player must stack pieces of different shapes (called "tetriminos") that descend from the top of the screen. The objective is to completely fill a horizontal line with blocks, which causes that line to disappear and the remaining blocks to move down. The game ends when the stacked blocks reach the top of the screen.

## Features
- Graphical user interface using Qt.
- Customization of game settings (level, height, width, random rotation).
- Display of score, level, and number of completed lines.
- Timer to track elapsed time during the game.
- Handling of keyboard events to control game pieces.
- To Win: survive 5min or clear 200 rows or achieve score = 9999.

## Installation
1. Clone the repository to your local machine.
   ```
   https://git.esi-bru.be/60731/dev4_tetris_60731_61692.git
   ```
2. Open the project in Qt Creator.
3. Build and run the project.

## Usage

1. Launch the application.
2. Configure game settings in the settings dialog.
3. Press arrow keys to move game pieces.
4. Press "D" key to drop the piece down.
5. Press "R" key to rotate the piece clockwise.
6. Press "C" key to rotate the piece counterclockwise.
7. The game ends when game pieces reach the top of the screen or no new piece can be placed or with the above-mentioned victory conditions.