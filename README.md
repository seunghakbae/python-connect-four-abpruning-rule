# Python connect_four game program

## Contents
* About Project
* Motivation
* About connect four
* Structure
* Algorithm
* Tech/framework used

&nbsp;

## About Project

Connect_Four game that uses min-max algorithm, alpha-beta-prunng algorithm and rule-based algorithm.

&nbsp;

## Motivation
School Artificial Intelligence project.

&nbsp;

## About connect four
Connect Four (also known as Four Up, Plot Four, Find Four, Four in a Row, Four in a Line, Drop Four, and Gravitrips (in Soviet Union)) is a two-player connection board game in which the players first choose a color and then take turns dropping one colored disc from the top into a seven-column, six-row vertically suspended grid. The pieces fall straight down, occupying the lowest available space within the column. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs. Connect Four is a solved game. The first player can always win by playing the right moves.

refernece : [wikepedia](https://en.wikipedia.org/wiki/Connect_Four)

&nbsp;

## Structure
consists of board.py, game.py and player.py files.

**Game class**
game class records which algorithm was used between rule-based and minmax. Creates board instance and runs until game ends.

- def beginGame

**Board class**
board class that prints each move that player or AI makes.

- def insertColumn
- def printBoard
- def checkResult
- def children
- def heuristic

**Player class**
player class that plays the game. It can be either player or AI.

- def makeMove
- def minmax

&nbsp;

## Results

![](./gif_file.gif)

## Tech/framework used
<b>Built with</b>
- python

&nbsp;
