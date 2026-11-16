# Blackjack Game Engine (TypeScript)

## Project Overview
A modular **Blackjack (21)** game engine built in **TypeScript**. Designed with clean separation of concerns across card, deck, type definitions, and utility modules, this project implements core casino game logic and serves as the foundational engine behind the [Next.js & Ant Design web version](https://github.com/m-arham-javed/black-jack-game-antd).

## Project Structure
* **`card.ts` / `card.js`:** Defines card entities, suits, ranks, and point values.
* **`deck.ts` / `deck.js`:** Handles standard 52-card deck generation, shuffling, and card dealing.
* **`types.ts` / `types.js`:** Provides strict TypeScript interfaces and type safety across game states.
* **`utils.ts` / `utils.js`:** Implements hand score calculation, dynamic Ace valuation (`1` vs. `11`), and win/bust evaluation.
* **`app.ts` / `app.js`:** Main entry point orchestrating the game loop and player/dealer turns.

## Tech Stack
* **Language:** TypeScript (compiled to JavaScript)
* **Runtime:** Node.js

## Local Setup

1. **Clone the repository:**
   ```bash
  git clone https://github.com/m-arham-javed/Black-Jack-Game.git
   cd Black-Jack-Game
