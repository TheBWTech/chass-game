# ♟️ Grandmaster Chess Game

A fully functional, responsive, and feature-rich single-file Chess game built with **HTML5**, **Tailwind CSS**, and vanilla **JavaScript**. Designed for seamless gameplay directly in the browser or mobile devices without any external dependencies or complex build tools.

---

## ✨ Key Features

- **Complete Chess Rules Engine:**
  - Full legal move generation for all pieces.
  - **Castling** (Kingside & Queenside with attack validation).
  - **En Passant** pawn captures.
  - **Pawn Promotion** modal selector (Queen, Rook, Bishop, Knight).
  - **Check, Checkmate, and Stalemate** detection.
  - **Draw Conditions:** Threefold repetition, 50-move rule, and insufficient material.
- **Game Modes:**
  - **Play vs. AI:** Challenge an intelligent AI powered by the **Minimax algorithm with Alpha-Beta pruning** and Piece-Square Tables (PST). Includes **Easy** and **Medium** difficulty levels.
  - **Pass & Play (2P):** Local two-player mode on the same screen.
- **Polished UI & User Experience:**
  - High-contrast SVG chess pieces with smooth hover scaling and drop shadows.
  - Valid move dots and capture rings.
  - King-in-check pulse warning animation.
  - Real-time algebraic move history (SAN notation) with scrollable log.
  - Captured pieces tracker with dynamic material advantage counter (`+1`, `+3`, etc.).
  - Board flipping toggle and move **Undo** support.
  - Built-in **Web Audio API sound effects** (moves, captures, checks, castling, and game over) requiring zero external audio files.

---

## 🚀 Getting Started (Quick Run)

Since this project is contained entirely within a single `index.html` file, you don't need Node.js, npm, or any build setup!

1. Clone or download this repository:
   ```bash
   git clone [https://github.com/TheBWTech/chess-game.git](https://github.com/TheBWTech/chess-game.git)
