# 🐪 Camel Up — Multiplayer Edition

A digital multiplayer implementation of the classic board game **Camel Up** for **2–5 players**, where players bet on racing camels to earn the most coins and win!

---

## 📖 Table of Contents

- [Overview](#overview)
- [How to Play](#how-to-play)
- [Game Components](#game-components)
- [Rules](#rules)
- [Betting](#betting)
- [Leg vs. Race Bets](#leg-vs-race-bets)
- [Desert Tiles](#desert-tiles)
- [Winning the Game](#winning-the-game)
- [Multiplayer Setup](#multiplayer-setup)
- [Tips & Strategy](#tips--strategy)

---

## Overview

Camel Up is a betting and racing game for **2–5 players**. Five camels race around a desert track, stacking on top of each other when they land on the same space. Players earn coins by correctly predicting which camel will be in the lead at the end of each **leg** (round) and which camel will **win or lose** the overall race.

The player with the **most coins** at the end of the game wins!

---

## How to Play

Each player's turn, they must choose **one** of the following actions:

### 1. 🎲 Roll the Dice (Move a Camel)
- Shake the pyramid and reveal a die.
- The corresponding camel moves forward by the shown number of spaces (1–3).
- You earn **1 coin** for rolling.
- A leg ends when **all 5 camel dice** have been rolled (one per camel per leg).

### 2. 🎟️ Take a Leg Bet Card
- Pick a betting card for the camel you think will be **leading at the end of the current leg**.
- Cards are worth **5, 3, or 2 coins** (first come, first served — earlier bets pay more).
- If your camel isn't in first or second place at leg's end, you **lose 1 coin**.

### 3. 🏁 Make a Race Bet
- Bet on which camel will finish **first or last** overall in the entire race.
- Place your ticket face-down on the Winner or Loser stack.
- Resolved at the end of the game (see [Winning the Game](#winning-the-game)).

### 4. 🏜️ Place a Desert Tile
- Place your player tile on an **empty space** (not on the first space or on another tile).
- Choose **Oasis** (green) or **Mirage** (sand):
  - **Oasis**: Camels landing here move **1 space forward**. You earn 1 coin.
  - **Mirage**: Camels landing here move **1 space backward**. You earn 1 coin.
- You can reposition your tile each turn.

---

## Game Components

| Component | Description |
|---|---|
| 🐪 5 Camels | White, Yellow, Green, Blue, Orange — each with their own die |
| 🎲 Pyramid & Dice | 5 coloured dice (1–3 values each), shaken and drawn one at a time |
| 🏟️ Race Track | 16 spaces in a loop |
| 🎟️ Leg Bet Cards | 3 cards per camel (worth 5, 3, 2 coins) |
| 🏆 Race Bet Tickets | Winner and Loser tickets per player |
| 🏜️ Desert Tiles | One Oasis/Mirage double-sided tile per player |
| 💰 Coins | Starting amount: **3 coins** per player |
| 🖥️ Server | A running game server is required for multiplayer |

---

## Rules

### Camel Stacking
- When a camel lands on a space **already occupied**, it stacks **on top** of the camels there.
- The camel **on top** of a stack is considered to be in the lead within that group.
- When a stack moves, **all camels in that stack move together**.

### Leg End
- A leg ends once **all 5 dice** have been drawn from the pyramid.
- Leg bet cards are resolved: check which camel is in **1st and 2nd place**.
  - 1st place card holders earn full value (5, 3, or 2 coins).
  - 2nd place card holders earn **1 coin**.
  - All other card holders **lose 1 coin**.
- All dice return to the pyramid and a new leg begins.

### Track Layout
- The track is **16 spaces** long and loops around.
- The race ends when **any camel crosses or lands on space 16**.

---

## Betting

### Leg Bets
Each camel has **3 betting cards** worth 5, 3, and 2 coins. Players race to grab the high-value cards first. At the end of a leg:

- **Your camel is 1st** → Earn the card's face value
- **Your camel is 2nd** → Earn 1 coin
- **Your camel is anywhere else** → Lose 1 coin

### Race Bets (Overall Winner/Loser)
Players can bet on who will **win or lose** the entire race by placing tickets face-down.

At game end, tickets are revealed in the order they were placed:
- **Correct prediction**: Earn coins based on when you bet (earlier = more coins: 8, 5, 3, 2, 1...)
- **Wrong prediction**: Lose 1 coin

---

## Desert Tiles

Your desert tile can be placed once per turn on any **unoccupied, non-starting space**.

- **Oasis side (green ✅)**: Camels that land here are boosted **+1 space forward**. You collect 1 coin.
- **Mirage side (🌵)**: Camels that land here are pushed **1 space backward**. You collect 1 coin.

> ⚠️ If a camel is pushed backward onto a stack, it goes **underneath** those camels.

---

## Winning the Game

The game ends immediately when **any camel crosses space 16**.

1. Resolve all **Race Bet** tickets (Winner and Loser stacks).
2. Add up all your **coins**.
3. The player with the **most coins wins!**

In case of a tie, the tied players share the victory. 🎉

---

## Multiplayer Setup

> ⚠️ **The game server must be running before any client can connect.** Make sure the host has started the server first, otherwise players will not be able to join.

1. **Host** starts the server and creates a game room, then shares the room code.
2. **Players** join using the room code (2–5 players supported).
3. Each player starts with **3 coins**.
4. Randomly determine who goes first (or let the host decide).
5. Play proceeds **clockwise** (or as configured in-game).

> 💡 The game supports real-time multiplayer — all players see the board update live after each action!

---

## Tips & Strategy

- **Roll early in a leg** when many dice remain — it's a safe 1 coin with low risk.
- **Grab leg bet cards quickly** — the 5-coin card goes fast!
- **Stack awareness is key** — a camel buried under others is unlikely to win a leg.
- **Desert tiles are powerful** — placing a Mirage in front of the leader can flip the race.
- **Race bets pay big** — but wait for more information before committing.
- **Watch what others bet** — if everyone bets on the same camel, the cards dry up fast.

---

## 📜 Credits

Based on the board game **Camel Up** by Steffen Bogen, published by eggertspiele / PD-Verlag.

This is a fan-made digital multiplayer implementation for personal use.

---

*Good luck, and may the fastest camel win! 🐪🏆*