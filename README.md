# XONIX_GAME
(C++ & SFML)

A modern take on the classic Xonix arcade game, developed using C++ and SFML.
This project showcases creative gameplay design, smooth movement mechanics, and multiple difficulty levels, all implemented with C++ logic and SFML graphics handling.

## Features

1. Main Menu with interactive options

2. Multiple Levels with increasing difficulty

3. Dynamic Movements for player and enemies

4. Smooth SFML Graphics and collision effects

5. Engaging arcade-style gameplay experience

## How to Play

Run the executable or compile the project in your C++ IDE.

Use the arrow keys to move your player.

Capture areas of the screen while avoiding enemies.

Complete the target area percentage to move to the next level.

Each level becomes faster and more challenging.

## Requirements

C++ Compiler (e.g., MinGW, g++, or Visual Studio)

SFML Library
 (Graphics, Window, Audio modules)

⚙️ How to Build and Run (Linux), You can also Use VS code or Visual Studio

Follow these steps to build the game from source:

# Step 1: Update system packages
sudo apt update

# Step 2: Install build tools and SFML
sudo apt install cmake
sudo apt install build-essential
sudo apt install libsfml-dev

# Step 3: Create a build folder
mkdir build
cd build

# Step 4: Configure and build the project
cmake ..
make


== After building, an executable named xonix will appear in the build folder.
To run the game:

./xonix


== After the first successful build, you only need to run make again to recompile any code changes.

## Concepts Used

Event handling and real-time input

Object movement and boundary detection

Game loop and collision detection

Texture, sprite, and font management in SFML

Level-based logic and difficulty scaling


Author

Muhammad Tayyab
Built with passion for learning C++ and game development.
