# Card Clash (Java)

A Java-based card game simulation that models a turn-based battle between a player and a computer opponent.
The project emphasizes object-oriented design, clean class structure, and program control flow.

## Motivation
This project was created to practice object-oriented programming concepts in Java, including class design, state management, and debugging through a complete game simulation.

## Description
Card Clash simulates a shuffled deck of cards that is split evenly between two players.
Each round, both players play a card and game logic determines the winner of the round.
The simulation continues until a win condition is met or a maximum round limit is reached.

## Tech Stack
- Java
- Object-Oriented Programming (OOP)
- Java Collections (`ArrayList`)

## Class Structure
- `Card` – Represents a playing card with a value and suit
- `Deck` – Creates, stores, and shuffles the deck
- `Player` – Manages a player’s card pile and game state
- `CardClash` – Controls the game loop, round logic, and win conditions

## How It Works
1. A deck of cards is created and shuffled.
2. Cards are evenly distributed between the player and the computer.
3. Each round:
   - Both players play a card
   - Cards are compared
   - The winner collects the cards
4. The game ends when a player runs out of cards or a round limit is reached.

