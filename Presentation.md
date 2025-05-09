# 📌-- Pacman Codebase Overview

This code implements a Pac-Man-inspired game in C++ with OpenGL, featuring a maze, food items, and dynamic monster characters.

Players control Pac-Man using keyboard inputs (W, A, S, D) while avoiding collisions with randomly moving monsters.

The game includes clear win conditions (collecting all food items) and lose conditions (collision with monsters).

It uses efficient rendering techniques, including trigonometric calculations for drawing circular characters and a bitmap system to represent obstacles in the maze.

The code is modular, making it easy to extend and refine for enhanced gameplay features like animations, sound effects, or AI-driven monster behavior.

---

## **Introduction**
This Pac-Man game is a classic implementation built using C++ and OpenGL. The game includes:
- A fully structured maze.
- A playable Pac-Man character controlled by the player.
- Dynamic, unpredictable monsters to challenge the player.
- Food scattered across the maze for the player to collect.
- Win and lose conditions based on food collection and collision detection



# ❓ Questions & Answers
## 1. What is the Purpose of this Project?
   The Pac-Man game project aims to recreate the classic gameplay experience using C++ and OpenGL. It demonstrates fundamental game development principles:
   - Visual rendering of a maze and characters.
   - Handling player input for controlling Pac-Man.
   - Introducing randomness and unpredictability through monster behavior.
   - Establishing win/lose conditions for an engaging gameplay loop.
  
## 2. What are the Core Features of the Game?
   
   - Monster:
      Four Monster with random movement make the game challenging.
   
   - Points system:
       Players collect food scattered across the maze, earning points.
   
   - Win and Loses status:
        The game ends when Pac-man collides with monsters or collects all food items.

## 3. How is the Maze Designed and Rendered?

   - The maze is represented using a 2D bitmap array:
       true values denote obstacles, while false values are walkable paths.
   
   - Rendering:
       Borders and obstacles are drawn using glRectf() for rectangular shapes.
       Food items are displayed as points using glPoints().

## 4. How are Characters Drawn?
   
   Pac-Man:  Pac-Man is drawn dynamically using a circle algorithm and trigonometric functions (sin, cos) for smooth rendering.
   
   Monsters: Monsters are represented by circles and rectangles, with distinct colors to differentiate them.
   
## 5. What are the Key Graphical Features?
   
- Welcome Screen: Displays instructions and game controls.
  
- Gameplay: Smooth graphics for maze, characters, and food, Dynamic resizing ensures compatibility across window sizes.
  
- Results Screen: Displays victory or loss messages with points earned.

## 6. How Does the Project Showcase Game Development Principles?
   
   This project illustrates key principles:
    
     - Input Handling:- Responsive controls for the player.
     
     - Collision Detection:- Ensures smooth gameplay and logical transitions between states.
     
     - Rendering:- Combines basic shapes and dynamic updates for an engaging visual experience.
     
     - Replayability:- Incorporates mechanics for resetting the game.



# 🔍 Code Structure Overview:
- init() : Sets up the game environment with maze, monsters and ket states.
- drawLaberynth() : Draws the maze.
- drawfood() : food
- updateMonster() : manages monster movement randomly
- resetGame() : Resets all game variables for reply
- reshape() : Adjusts elements for different windoe sizes
- main() : Runs the game and manages transitions  


# 🧱 Data Types Used
    - bool: Used for flags like replay, over, and keyStates to track game state and keypress
    - string: Used for dynamic text rendering of scores and massages
    - vector: Stores coordinates for borders, obstacles and food items.
    - deque: Tracks food positions, allowing efficient additiona and removals.
    - array: Dynamically allocates positions and directions for monsters 



# 🔍 Findings & Observations

   Strengths 
       
       1. Readable and Modular Code:
          - Functions are well-organized and clearly defined for initialization, rendering, and gameplay logic.
       
       2. Graphics Integration:
          - OpenGL is effectively utilized to create a visually appealing game.
       
       3. Dynamic Gameplay:
          - Randomized monster behavior and well-defined collision detection enhance replayability.
       
       4. Game States:
          - Smooth transitions between welcome, gameplay, and results screens.

# 🚀How It Works

   Flowchart
    
    1. Welcome Screen:
       - Displays instructions and waits for user input (space key).
    
    2. Gameplay:
       - Pac-Man collects food and avoids monsters.
       - Updates are rendered continuously.
    
    3. Game Over:
       - Displays results based on collision or food completion.

# 🧱Conclusion
This project demonstrates a solid understanding of game development, C++ programming, and OpenGL rendering. With potential enhancements, it could evolve into a more polished and feature-rich Pac-Man clone.

# 🔗Reference
https://github.com/FeminaRathod/Pacman





















        
    



