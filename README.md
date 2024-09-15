# Turtle Crossing Game
Welcome to the Turtle Crossing Game! 🐢🚗 This is a simple Python game where the player controls a turtle character that must navigate through a stream of moving cars to reach a finish line. The game is built using the `turtle` module for graphics and basic game mechanics.

## Features
- **Player Movement:** Move the turtle character up using the "Up" arrow key.
- **Car Management:** Randomly spawn and move cars across the screen.
- **Collision Detection:** The game detects collisions between the turtle and cars.
- **Level Progression:** Successfully crossing the finish line advances the game to the next level.
- **Scoreboard:** Track and display the current level of the game.

## Code Overview
```bash
main.py
```
The main script that initializes the game screen, sets up the player, car manager, and scoreboard, and handles the game loop.

Player Movement: Listens for the "Up" arrow key to move the player.
Car Management: Creates and moves cars on the screen.
Collision Detection: Ends the game if the player collides with a car.
Level Progression: Advances the level when the player crosses the finish line.
player.py
Contains the Player class, which defines the player's turtle character and its behavior.

```bash
car_manager.py
```
Contains the CarManager class, responsible for creating and moving cars.

```bash
ScoreBoard.py
```
Contains the Scoreboard class, which manages and displays the current game level.

## Usage
- Use the "Up" arrow key to move the turtle up.
- Avoid colliding with moving cars.
- Reach the finish line to advance to the next level.
