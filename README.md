# Treasure Hunt 2D Game (Console-based C++)

This is a console-based 2D treasure hunt game written in C++. The player (`P`) navigates through a grid to collect treasures (`T`) while avoiding traps (`X`). Grid blocks (`*`) disappear one by one every few seconds, increasing the challenge and urgency.

## Features

- 3 difficulty levels: Easy, Medium, Hard
- Real-time player movement using arrow keys
- Treasures and traps placed at random positions
- Grid blocks progressively vanish during gameplay
- Game ends on collecting 6 treasures (win) or hitting 3 traps (lose)
- Multithreaded gameplay using `std::thread`

---

## Prerequisites

To compile and run this project, ensure the following tools and environment are available:

### OS and Compiler
- **Operating System**: Windows 10 or later
- **Compiler**: `g++` (MinGW-w64) version **9.0 or later** with POSIX thread model

### Tools Required
- Visual Studio Code or any other C++-compatible IDE
- g++ (MinGW-w64) with `std::thread` support
- Windows terminal (e.g., Command Prompt or PowerShell)

### Confirm Compiler Version
```bash
g++ --version
