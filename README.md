# Overview
Due to academic integrity policies, the source code is not publicly available. A collaborative project aimed at designing and implementing a 2D tile-based world exploration engine. The engine allows users to explore dynamically generated worlds, interact through an avatar, and save or load their progress, ensuring a robust and engaging user experience.

# Features
### Procedural World Generation:
Employs algorithms to generate sufficiently random and diverse worlds, ensuring a unique exploration experience every time.
### Deterministic Pseudo-Randomness:
Ensures reproducible world generation through the use of pseudo-random number generation with seed inputs.
### Interactive Avatar Control:
Users can seamlessly navigate the generated world using an intuitive avatar control system.
### Comprehensive Save and Load System:
Allows users to save their progress and load previous states through a reliable .txt file system, enhancing the user experience by providing continuity.

# How It Works
### World Generation
The world generator employs an algorithm to create random worlds based on tile structures. The use of a seed input maintains deterministic behavior, allowing the same world to be recreated with the same seed. Walls, hallways, and rooms are generated that will always follow the boundaries.
### User Interaction
Users control an avatar within the generated world, enabling exploration and interaction with various elements. There is a key to turn on the line of sight; when pressed, the world disappears except for the area around the avatar.
### Save and Load
Users can save the state of their world at any point, stored in a .txt file. This functionality captures the current state of the world and the avatar's position. Users can load previously saved worlds, allowing them to continue their exploration from where they left off.
