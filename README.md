# Quoridor - Local PvP Game

A local multiplayer implementation of the classic Quoridor board game, featuring a modern UI inspired by Chess.com.

## How to Play

1. **Objective**: Be the first player to reach the opposite side of the board
   - Player 1 (dark blue) starts at the bottom and aims for row 0
   - Player 2 (red) starts at the top and aims for row 8

2. **Gameplay**:
   - **Moving**: Click "Move Pawn" mode, then click on a highlighted valid move
   - **Placing Walls**: Click "Place Wall" mode, then click on a cell to place a wall
   - Walls block opponent movement but cannot completely block their path to the goal
   - Each player starts with 10 walls

3. **Controls**:
   - **New Game**: Start a fresh game
   - **Undo**: Undo the last move
   - **Move/Wall Mode**: Toggle between moving your pawn and placing walls

## Features

- Clean, modern interface
- Visual feedback for valid moves
- Turn indicators
- Wall placement validation
- Pathfinding to ensure walls don't block paths
- Win detection
- Undo functionality

## Running Locally

Simply open `index.html` in a modern web browser. No build process or server required!

