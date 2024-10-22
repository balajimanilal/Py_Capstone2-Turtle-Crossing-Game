# Py_Capstone2-Turtle-Crossing-Game
A fun and challenging game where you guide a turtle across a busy road full of cars. The game gets progressively harder as you advance through levels, with the cars moving faster as you succeed!

# Game Mechanics
- Cars: Randomly generated cars move horizontally across the screen. The turtle must avoid these cars while crossing the road.
- Level Up: Each time the turtle reaches the top of the screen, it advances to the next level and the car speed increases.
- Game Over: If the turtle collides with a car, the game ends, and a "Game Over" message is displayed.

# File Descriptions
- **[```1. car_manager.py```](https://github.com/balajimanilal/Py_Capstone2-Turtle-Crossing-Game/blob/main/car_manager.py):** This file defines the CarManager class, responsible for generating and moving cars, as well as increasing the car speed as the player progresses.
- **[```2. player.py```](https://github.com/balajimanilal/Py_Capstone2-Turtle-Crossing-Game/blob/main/player.py):** Contains the Player class, which manages the turtle's movement and checks if the turtle has reached the finish line.
- **[```3. scoreboard.py```](https://github.com/balajimanilal/Py_Capstone2-Turtle-Crossing-Game/blob/main/scoreboard.py):** Implements the Scoreboard class to display the current level and handle the game-over message.
- **[```4. main.py```](https://github.com/balajimanilal/Py_Capstone2-Turtle-Crossing-Game/blob/main/main.py):** The main script that initializes the game, handles key presses, and manages the game loop.

> # Features
> - **Interactive Gameplay:** Control the turtle using the keyboard to navigate across the road.
> - **Level Progression:** Each time the turtle successfully crosses the road, the game becomes more difficult with cars moving faster.
> - **Score Tracking:** The scoreboard keeps track of the current level.
