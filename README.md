# Chess_pygame

A simple **Chess** game built using **Pygame**.  
This project was created as a learning experience to dive into game development, chess logic, and Python programming.

---

## 🎯 Project Overview

This is a playable chess game supporting two human players on the same machine.  
It features:

- Standard chess rules and piece movements  
- Interactive graphical board and pieces using Pygame  
- Click-to-select and click-to-move mechanics  
- Basic move validation ensuring only legal moves are allowed  
- Turn-based gameplay with game state management and end detection  

---

## 💡 Purpose & Learning Experience

This project served as a **hands-on learning journey** to:

- Understand how to build games using Pygame's event loop and graphics  
- Implement chess logic such as piece movements and move validation  
- Manage game state including turns and detecting check/checkmate  
- Improve Python programming skills through a complex, interactive project  
- Learn debugging and problem-solving in a graphical application context  

The code is kept **simple, clear, and readable** to prioritize learning and maintainability over advanced features or AI.

---

## 🛠 Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/i0Ta07/Chess_pygame.git
   cd Chess_pygame

2. **Install dependencies:**
   
   ```bash
   pip install pygame

3. **Run the Game:**
---

## 🎮 Controls

- Click on a piece to select it  
- Click on a valid destination square to move the selected piece  
- The game automatically alternates turns between players  
- Only legal moves are allowed; invalid moves are ignored  

---

## 📂 Code Structure

- **main.py**  
  Entry point containing the game loop and event handling.

- **game.py**  
  Core logic managing the board state, move validation, and turns.

- **graphics.py**  
  Handles rendering the chessboard and pieces with Pygame.

- **pieces.py**  
  Defines chess pieces, their movement rules, and validation.

- Additional utility modules supporting chess rules and game mechanics.

---

## 🚀 Future Improvements

- Add AI opponent with algorithms like minimax or alpha-beta pruning  
- Implement special moves such as castling, en passant, and pawn promotion  
- Improve UI with move highlighting, animations, and sound effects  
- Enhance graphics for a more polished appearance  
- Add networked multiplayer functionality to play online  

---

## 📝 License

This project is open source and available for educational and personal use.

---

## 🙏 Acknowledgments

Inspired by classic chess programming tutorials and Pygame examples.  
Special thanks to open source communities and contributors who made this possible.

---

## 📢 Developer Note

This project was a valuable step in mastering Python game development and exploring the complexities of chess programming.  
The focus was on clarity and fundamental concepts to build a solid foundation for future enhancements.
