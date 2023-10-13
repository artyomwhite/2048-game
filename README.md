# 2048 Desktop Game

This project is an implementation of the 2048 game for desktop using plain JavaScript. The game field is a 4x4 grid, where each cell can be empty or contain one of the numbers: 2, 4, 8, and so on. Players can move cells using keyboard arrows.

## Features

- A 4x4 game grid.
- The ability to move numbers in the chosen direction until all empty cells are filled.
- Merging of two equal cells into a doubled number.
- Merged cells cannot merge again in a single move.
- A move is only possible if at least one cell changes after the move.
- After each move, a random empty cell receives the number 2 or 4 with a 10% probability.
- Display of a win message when the number 2048 appears in any cell.
- Display of a game over message when no more moves are available.
- Hiding the "Start" message when the game begins.
- The "Start" button changes to "Restart" after pressing "Start".
- The score increases with the sum of all merged cells in each move.

## Technology Stack

- HTML5
- CSS3
- SASS (SCSS is used)
- JavaScript

## Preview

[Try the game](https://artyomwhite.github.io/2048-game/)