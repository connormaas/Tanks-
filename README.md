# Tanks Game

Welcome to the Tanks Game repository! Navigate your tank in 8 different directions to shoot and destroy CPU opponents in a competetive battle that only gets more difficult as you progress. Don't forget: gameplay is always unique because obstacles are periodically randomized.

## Demo

A video demo for the game can be found [here](https://www.youtube.com/watch?v=44Ij5p1PsN0&t=14s).

## Creators Note

I am proud of all my work, but this program can be buggy depending on your device. It was implemtmneted in 2020 when my programming practices were relatively poor (as compared to know), and I am definitely too lazy to make major changes at this point 😂 Regardless, enjoy the repository!

## Overview

This Python-based application brings to life a 2D virtual tank battle taking place within a displayed window. The ultimate goal for the user is to survive as long as possible. You navigate your tank around randomized barreirs and try to shoot down enemy CPU tanks. However, CPU tanks have the ability to avoid your shots and also fire back through predictive algorithms. There are multipel tanks types. You have the ability to shoot missles off the wall which is your distinct advantage over CPU enemy tanks.

### Key Features:

1. **Tank Movement**: Tanks can move in 8 different directions (veritcal, horizontal, diagonal), providing players with the flexibility to navigating the battlefield.
2. **Shooting Mechanism**: Tanks can shoot missles to destroy enemy tanks using mouse or mouse pad.
3. **Level Progression**: As you continue to eliminate tanks, you will be advanced to higher levels in which more difficult game play is introduced, along with other varieties of CPU tanks. Specifically, CPU tanks become faster and more agile, also fire missles at higher rates.
4. **Randomized Obstacles**: At the end of each level, obstacles are randomized in size, shape, and location to enable more dynamic game play and map navigation.
7. **Tank Variety**:
   - The user tank: This is the tank you control, which has the ability to navigate the map, and fire missles at enemy tanks to elimnate them. An added bonus is that it is able to bouce it's missles off the wall.
   - The shooter tank: This is a CPU tank which is able to navigate the map, dodge your missles, and target fire missles at you. It's disadvantage against you is that it cannot bounce it's missles off the wall.
   - The attack tank: The attack tank is a extra speedy tank which is charges directly at the user tank, while also having the ability to dodge shots. While it does not have the ability to shoot missles, if it is able to make contact with the user tank, it explodes and eliminates it.

## Implementation Details

- **tanks.py**: This is the main game file. It contains the implementation of the game logic, including tank movement, shooting mechanisms, and the game loop. This file initializes a window using the `graphics.py` and then continuously checks for user input to move the tank or shoot missles . The game also checks for collisions between missles and enemy tanks to determine if a tank is destroyed.
- **graphics.py**: This file contains the implementation of the graphics used in the game. It provides various classes and functions to handle graphical elements, such as windows, points, lines, circles, and text. The game uses this library to render the battlefield, tanks, and missles.
- **images**: This folder stores the images used and displayed in the game window.

## Installation and Dependencies

General:
- **Python**: The app can successfully run on `Python 3.7.9`, but should work on most versions of Python.
- **[pyautogui](https://pyautogui.readthedocs.io)**: Mouse and keyboard assistance for more interactive gameplay.

Step-by-step:
1. Clone the repository to your local machine.
2. Navigate to the repository's main directory.
3. Make sure to install `pip` and `Python` to your device.
4. Run `pip install -r requirements.txt`.
5. Run the `tanks.py` file using Python.

## Contributing

Feel free to fork the repository and submit pull requests for any enhancements or bug fixes. Contributions are always welcome!

