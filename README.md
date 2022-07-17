# Invaders
Classic Atari's Invaders game using Rust.

## Requirements
* Rust compiler and Cargo installed.
* For *Linux* users you might need to install theses dependencies for the audio package to work properly.
  * libasound2-dev
  * pkg-config
  * On Debian based distros you can run: ```sudo apt install libasound2-dev pkg-config```
  
## Usage
Once you cloned this repo go to the terminal and inside the root directory run:

        cargo run
        
This will compile everything and start the game (to see how to play go to [instructions](#instructions)).

## Instructions
The game is very simple and the set of commands to play are listed bellow:
* **q or Esc** - quit the game.
* **Left and Right arrows** - move the spaceship (A).
* **Spacebar or Enter** - shoot.

## Rules
The rules are also very simple, you need to kill all invaders before they reach the bottom of the screen
(what means that they've reached the spaceship and you were caught).
