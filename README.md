
# 2048 game
- ua [Українська версія](README.ua.md)
 - [DEMO LINK](https://OlegMysko.github.io/js_2048_game/)


## Description
A classic implementation of the 2048 game built with vanilla JavaScript.
The game logic is encapsulated in a `Game` class, which manages the board state, score, and game status.
Players can move tiles using keyboard arrow keys to combine equal numbers and reach the 2048 tile.

## Technologies
- JavaScript (ES6)
- HTML5
- CSS3
- OOP principles

## Features
- Keyboard controls (Arrow keys)
- Tile merging logic
- Score tracking
- Win and lose conditions
- Restart game functionality
- Random tile spawning (2 or 4)

## Controls
- ⬅️ Arrow Left — move tiles left
- ➡️ Arrow Right — move tiles right
- ⬆️ Arrow Up — move tiles up
- ⬇️ Arrow Down — move tiles down

## Game Logic Overview
- The game field is represented as a 4×4 matrix
- After each valid move, a new tile (2 or 4) appears in a random empty cell
- Tiles with the same value merge into one
- The game ends when no moves are possible
- The player wins when a tile with value **2048** appears

## How to run locally
- Clone the repository
- Run `npm install`
- Run `npm start`


