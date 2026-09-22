# My_hunter

A 2D graphical game project inspired by Nintendo's classic **Duck Hunt**, developed in **C** using the **CSFML** (C Simple and Fast Multimedia Library) library as part of the **Epitech** curriculum.

## Project Overview

This repository contains a functional recreation of the iconic Duck Hunt game. It focuses on managing a window, handling events, rendering sprites, and animating elements smoothly at a consistent frame rate.

Please note that this is currently an ongoing project. The core gameplay mechanics are implemented, but advanced systems such as score tracking, win/lose conditions, and custom crosshairs are still in development.

## Features

* **Parallax / Animated Background:** A visually faithful environment inspired by the original game using CSFML textures and sprites.
* **Target Management:** A responsive duck that spawns, moves across the screen, and updates its frame animation.
* **Hit Detection:** Basic mouse interaction and window event handling to shoot the moving target.

## Future Roadmap

The project will be updated as time permits. Future iterations plan to include:
* Score tracking and high-score systems.
* Win, lose, and game-over conditions.
* Custom in-game cursors/crosshairs to replace the system mouse.
* Sound effects and audio feedback using the CSFML audio module.

## Getting Started

### Prerequisites

To compile and run this project, you need a C compiler (`gcc`), `make`, and the **CSFML** development packages installed on your system.

On Fedora/RedHat (Epitech environment):
```bash
sudo dnf install CSFML-devel
```

### Installation & Execution

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Ry0s43b4/My_hunter.git
   ```
2. Navigate into the project directory:
   ```bash
   cd My_hunter
   ```
3. Compile the project using the provided Makefile:
   ```bash
   make
   ```
4. Run the game:
   ```bash
   ./my_hunter
   ```

## Contributing

Feel free to fork or clone this repository if you want to test the game, experiment with CSFML, or implement the missing features yourself. Pull requests and suggestions are always welcome!

---
Enjoy playing! 🎯
