# Pallanguzhi (Pallankuzhi) — A Traditional Indian Game

A complete, playable two-player Pallanguzhi board game built with **Python** and **Pygame**, packaged for Windows using **PyInstaller**. Built as a college game-development project.

---

## How to Play (Rules Implemented)

- The board has **14 pits**: 7 belong to Player 1 (bottom row), 7 belong to Player 2 (top row). Each pit starts with **6 seeds**.
- On your turn, click one of **your own** pits that has seeds in it.
- All seeds from that pit are picked up and dropped one at a time into the following pits, moving around the board (through both players' pits).
- If the **last seed** you drop lands in a pit that then holds **exactly 4 seeds**, you **capture** those 4 seeds (added to your score). If the pit right before it also has exactly 4, you capture that one too — capturing can chain backwards.
- If a player has no seeds left in any of their pits at the start of their turn, the game ends and all remaining seeds on the board go to the other player.
- **Highest score wins.** Equal scores = a draw.

You cannot:
- Select your opponent's pits
- Select an empty pit
- Click another pit while a move is animating
- Make any move after the game has ended

The in-app **"How to Play"** screen explains all of this in simple language, and there's an **"About"** screen describing Pallanguzhi's cultural background.

---

## Running the Game


Double-click `Pallanguzhi.exe`.
The main menu appears — click **Start Game** to play.



