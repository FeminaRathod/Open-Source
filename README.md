# 🟡 Pac-Man-Style Arcade Game (C++ & OpenGL)
Get ready to chomp your way through a maze of retro fun! This Pac-Man-inspired game is a visually-enhanced, modernized version of the arcade classic — built using C++ and OpenGL. From ghostly monsters to glowing food pellets, this game is packed with excitement and nostalgia. Can you outmaneuver the monsters and clear the maze?

# 🚀 Features
✅ Classic Maze Gameplay – Navigate the maze, collect food, and avoid ghosts!

👻 Ghost-Shaped Monsters – Custom-designed ghost enemies add spooky charm.

😮 Animated Pac-Man – Watch Pac-Man's mouth open and close as he moves!

🌈 Color-Shifting Food – Food pulses and changes color to catch your eye.

🏆 Score Display – Real-time score shown on screen as you play.

🧱 Maze Walls & Obstacles – Movement logic based on a bitmap structure for accurate collision.

🎯 Chase & Escape Mechanics – Ghosts pursue Pac-Man intelligently based on pathfinding logic.

# 🎮 Controls
🕹 Arrow Keys – Move Pac-Man in the maze

⏹ ESC – Quit the game

🔁 (Optional) Additional controls for debugging or restarting can be added

# 🛠 Installation & Running
1️⃣ Clone the repository or download the source code:
bash, 
Copy,
Edit,
git clone https://github.com/your-username/pacman-opengl.git

2️⃣ Open the project in your favorite C++ development environment (e.g., Visual Studio, Code::Blocks)

3️⃣ Make sure you have OpenGL and GLUT libraries set up (see prerequisites below)

4️⃣ Compile and run the program

5️⃣ Start playing and try to beat your high score! 🎯

# 📌 Prerequisites
A C++ compiler with OpenGL support (e.g., MinGW, MSVC)

OpenGL Utility Toolkit (GLUT) or FreeGLUT installed

Windows OS (currently tested and developed for Windows)

#include <windows.h> and #include <GL/glut.h> dependencies used

# 📂 File Structure
bash
Copy
Edit

# 📁 /src
📄 main.cpp            – Main game loop and logic
 
📄 draw.cpp            – Rendering functions (Pac-Man, ghosts, food, etc.)
 
📄 map.cpp             – Bitmap layout for walls and food logic
 
📄 utils.h/.cpp        – Helper functions and common utilities
 
📄 bitmap.txt             – Maze structure defined using characters

# 🌟 Future Enhancements
💡 Ghost AI Improvements – Smarter chasing and scatter behaviors

🎨 Visual Effects – Power-ups, lighting, and particle effects

🎮 Lives System – Add multiple lives and game-over conditions

🔊 Sound Effects – Munching, ghost chase, and game over sounds

🧩 Modular Levels – Load different maps and challenges
