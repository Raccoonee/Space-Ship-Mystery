# Space Ship Mystery

A text-based interactive fiction murder mystery game set aboard a spaceship.

## About the Game

In "Space Ship Mystery," you play as the ship's electrician who wakes up from a nap in the cafeteria to discover that something is wrong. Your initial task is to fix the navigation systems due to damaged wiring, but you soon discover a murdered crew member and must investigate to find the killer before they strike again.

### Key Features:
- Explore multiple areas of the spaceship including the Cafeteria, Electrical Room, Navigation Room, Security Room, and Medical Bay
- Interact with crew members through a questioning system using who, what, when, where, how, and why
- Collect evidence and solve puzzles to uncover the murderer's identity
- Multiple endings based on your choices and discoveries
- Classic text adventure gameplay with modern web-based interface

## Technologies Used

This project combines several technologies to create an interactive fiction experience:

- **Inform 7**: A design system for interactive fiction based on natural language. The game's logic, narrative, and puzzles are written in Inform 7, which is specifically designed for creating text adventures.

- **Glulx/Glk**: The underlying virtual machine and I/O system that runs the compiled Inform 7 code (the .gblorb file).

- **Quixe**: A JavaScript interpreter for Glulx games that allows the game to run in a web browser without additional software.

- **HTML/CSS/JavaScript**: The web interface that hosts the Quixe interpreter and provides the visual presentation of the game.

- **jQuery**: Used by the interpreter for DOM manipulation and event handling.

## How to Play

1. Open `index.html` in a web browser
2. Read the text descriptions and type commands to interact with the game world
3. Use simple verb-noun commands like "examine locker" or "open cabinet"
4. Question characters using "ask [character] [topic]" with who/what/when/where/how/why
5. Explore the ship, gather evidence, and solve the mystery

## Credits

- **Game Design and Writing**: Devin
- **Inform 7**: Created by Graham Nelson
- **Quixe Interpreter**: Created by Andrew Plotkin
- **Cover Art**: "Space Ship" (included as Cover.png)

## License

All rights reserved.
