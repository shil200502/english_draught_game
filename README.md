# Checkers (English Draughts) Game

A feature-rich Checkers game built with C++ and SDL2, featuring a graphical interface with real-time move validation and visual feedback.

## 🎮 Features
- **Two-player local gameplay** with intuitive graphical interface
- **Real-time move highlighting** - visual indicators for valid moves
- **Mandatory jump enforcement** - strictly follows official game rules
- **Interactive piece selection** - click to select and see available moves
- **Clean, responsive SDL2-based GUI**

## 🛠️ Technical Implementation
- **Language:** C++
- **Graphics Library:** SDL2 (Simple DirectMedia Layer)
- **Architecture:** Modular C++ with object-oriented design
- **Build System:** [Mention: CMake/Makefile/Visual Studio - if you have one]
- **Key Algorithms:** Move validation, pathfinding for jumps, game state management

## 🚀 How to Build and Run
### Prerequisites
- C++ compiler (GCC, Clang, or MSVC)
- SDL2 development libraries

### Building from Source
```bash
# Clone this repository
git clone https://github.com/shil200502/checkers-game.git

# Navigate to project directory
cd checkers-game

# Build the project
make  # or: g++ -std=c++17 *.cpp -lSDL2 -o checkers
