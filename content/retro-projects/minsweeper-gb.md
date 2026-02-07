+++
title = 'MineSweeper for the GameBoy'
summary = 'This is a port/demake of the Microsoft game Minesweeper. The game works both for the Gameboy and the Gameboy color, with enhanced colors for the latter.'
+++

This is a port/demake of the Microsoft game Minesweeper. The game works both for the Gameboy and the Gameboy colors, with enhanced colors for the latter.

## Play

<!-- Doesn't work... -->
<!-- <iframe src="https://wasmboy.app/iframe/?rom-name=MineSweeper&rom-url=https://api.github.com/repos/roddyrap/Minesweeper_Gameboy/releases/assets/221152385"></iframe> -->

[Download ROM](https://github.com/roddyrap/Minesweeper_Gameboy/releases/latest/download/Minesweeper.gb)

## Gameplay (from Wikipedia)

In Minesweeper, mines (that resemble naval mines in the classic theme) are scattered throughout a board, which is divided into cells. Cells have three states: uncovered, covered and flagged. A covered cell is blank and clickable, while an uncovered cell is exposed. Flagged cells are those marked by the player to indicate a potential mine location.

A player left-clicks a cell to uncover it. If a player uncovers a mined cell, the game ends, as there is only 1 life per game. Otherwise, the uncovered cells displays either a number, indicating the quantity of mines diagonally and/or adjacent to it, or a blank tile (or “0”), and all adjacent non-mined cells will automatically be uncovered. Right-clicking on a cell will flag it, causing a flag to appear on it. Flagged cells are still considered covered, and a player can click on them to uncover them, although typically they must first be unflagged with an additional right-click.

The first click in any game will never be a mine.

To win the game, players must uncover all non-mine cells, at which point, the timer is stopped. Flagging all the mined cells is not required.

## GB Modifications (rules)

Instead of using the mouse and left/right clicks the player uses the d-pad and the A and B buttons to navigate.

 - A is used to open tiles.
 - B is used to flag and unflag tiles
 - All mines need to be flagged to win.
 - Start is used to restart the game.
 - Select opens a difficulty select screen.

### Board sizes

 - Easy: 10x10 with 10 bombs.
 - Intermediate (Inter): 16x16 with 40 bombs.
 - Expert: 22x22 with 99 bombs.
 - Nightmare (NiMare): 32x32 with 200 bombs.

## Images

### GBC

![GameExpertEnd](https://github.com/roddyrap/Minesweeper_Gameboy/blob/master/Images/GBC/GameExpertEnd.png?raw=true)

![GameMidEasy](https://github.com/roddyrap/Minesweeper_Gameboy/blob/master/Images/GBC/GameMidEasy.png?raw=true)

![GameStartEasy](https://github.com/roddyrap/Minesweeper_Gameboy/blob/master/Images/GBC/GameStartEasy.png?raw=true)

![GameSelectMenu](https://github.com/roddyrap/Minesweeper_Gameboy/blob/master/Images/GBC/SelectMenu.png?raw=true)

### GB

![GameExpertEnd](https://github.com/roddyrap/Minesweeper_Gameboy/blob/master/Images/GB/GameExpertEnd.png?raw=true)

![GameMidEasy](https://github.com/roddyrap/Minesweeper_Gameboy/blob/master/Images/GB/GameMidEasy.png?raw=true)

![GameStartEasy](https://github.com/roddyrap/Minesweeper_Gameboy/blob/master/Images/GB/GameStartEasy.png?raw=true)

![GameSelectMenu](https://github.com/roddyrap/Minesweeper_Gameboy/blob/master/Images/GB/SelectMenu.png?raw=true)

## Bug reports and support

Feel free to submit all bug reports and code changes ideas and requests to the corresponding tabs in GitHub. GitHub Link
License

## Attribution

This project is licensed under the Apache License 2.0.

Gameplay section provided by Wikipedia under the “Creative Commons Attribution-ShareAlike” license. This is not endorsed by Wikipedia or its writers.

