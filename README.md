# Number Guesser

A simple game where a one player must guess a number from 1 to n defined by another player.

### Tech

Java, Swing

### System Level Architecture

Client-Server

### Features and Use Cases

1) Gameplay
  - Set game options - max number to guess, try count  (player)
  - Randomly choose the starting player (system)
  - Guess the number (player)
  - Show the guess result (system)

2) Gameplay Replay
 - Replay the game

### Non-Functional Attributes

- UI - simple window/frames with basic buttons, labels or readonly text fields
- Data Persistence - after each significant system or user actions an event is stored to a file, allowing whole gameplay replay later

