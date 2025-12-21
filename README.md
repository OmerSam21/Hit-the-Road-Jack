# Hit the Road, Jack

A road-crossing game built in Jack programming language for the Nand2Tetris course.
The game is a mini-replica of the game "Crossy-Road"


## Game Overview

Hit-the-Road-Jack is an arcade-style game where you play as a character trying to cross a busy road filled with moving cars. Your goal is to navigate through traffic, reach safe zones, and achieve the highest score possible.

## Features

- **Multiple Game States**: Menu, Instructions, Credits, Leaderboard, Game, and Game Over screens
- **Progressive Difficulty**: Traffic speed and density increase with each level
- **Score System**: Points are awarded for forward movement and level completion
- **Leaderboard**: Top 5 high scores are saved and displayed
- **Animated Menu**: Wave animation on the main menu
- **Collision Detection**: Real-time collision checking between player and traffic
- **HUD Display**: Shows current level and score during gameplay
- **Pseudo-Randomness**: Integrated pseudo-randomness to make each run of the game different

## Controls

- **Arrow Up** / **Arrow Down**: Move player up or down
- **Arrow Right** / **Space**: Move player forward (awards points)
- **ESC**: Exit current game and return to menu
- **1-4**: Navigate menu options
- **Any Key**: Return to menu from Instructions, Credits, or Leaderboard screens

## Project Structure

The project consists of the following Jack classes:

- **Main.jack**: Entry point that initializes sprites and starts the game
- **Game.jack**: Main game loop managing all game states and logic
- **Player.jack**: Player character with movement and collision handling
- **Traffic.jack**: Manages multiple cars, their movement, and collision detection
- **Car.jack**: Individual car entity with position, speed, and direction
- **Sprites.jack**: Handles all drawing operations (player, cars, road, etc.)
- **Leaderboard.jack**: Manages high score storage and display
- **Animation.jack**: Handles animated wave and level-up effects

## How to Run

1. Compile all `.jack` files using the Jack compiler
2. Run the compiled `.vm` files in the Nand2Tetris VM emulator
3. Use the keyboard controls to navigate and play

## Credits

Created by Omer Samson, Alon Levy, and Ofek Marciano

**Nand2Tetris Project 9**

## Technical Details

This project is implemented in Jack, a high-level object-oriented language designed for the Nand2Tetris course. The game runs on the Hack computer platform and uses the Jack OS for screen output, keyboard input, and memory management.
