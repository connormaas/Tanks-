# Tanks Game

## Demo

A video demo for the game can be found [here](https://www.youtube.com/watch?v=44Ij5p1PsN0).

## Creator's Note

I'm proud of this work, but please note that this program was developed back in 2020, at an earlier stage in my programming journey. As such, it might exhibit some bugs or performance issues. While I've grown and improved since then, I'm currently focusing on other projects and won't be making major updates to this one. So, this way it shall stay. 😂 Regardless, enjoy the repository!

## Overview

This Python-based application brings to life a 2D virtual tank battle in a dedicated window. The ultimate goal is for the user to survive as long as possible, while navigating their tank in 8 directions amidst randomized obstacles. While users have the distinct advantage to bounce missiles off walls to target CPU enemy tanks, it's not a one-sided fight. CPU tanks come in two varieties and possess the ability to attack the user and avoid incoming missiles through predictive algorithms.

### Key Features:

1. **Tank Movement**: All tanks can move in 8 different directions (vertical, horizontal, diagonal), providing players with the flexibility in navigating the battlefield.
2. **Shooting Mechanism**: The user can shoot missiles to destroy enemy tanks using their mouse or mouse pad.
3. **Level Progression**: As the user continues to eliminate tanks, they will be advanced to higher levels in which more difficult game play is introduced, along with other varieties of CPU tanks. Specifically, CPU tanks become faster and more agile, and fire missiles at higher speeds.
4. **Randomized Obstacles**: At the end of each level, obstacles are randomized in size, shape, and location to enable more dynamic game play and map navigation.
5. **Tank Variety**:
   - The user tank: This is the tank the user controls. It has the ability to navigate the map, and fire missiles at enemy tanks in order to elimnate them. An added bonus is that it can bounce it's missiles off the walls and obstacles.
   - The shooter tank: This is a CPU tank which is able to navigate the map, avoid the user tank's missiles, and fire missiles at the user.
   - The attack tank: The attack tank is a extra speedy tank which charges directly at the user tank, while also having the ability to avoid the user's missiles. While it does not have the ability to shoot missiles itself, if it comes into contact with the user tank, it explodes and eliminates it.

### Implementation

1. **`tanks.py`**: This is the main game file. It contains the implementation of the game logic, including tank movement, shooting mechanisms, and the game loop. This file initializes a window using `graphics.py` that contains both the home page and gameplay screen. During gameplay, it checks for user input to move the tank or shoot missiles, navigates the CPU tanks in effort to destory the user, checks for collisions between missiles and tanks to determine if a tank is destroyed, updates levels and keeps track of multiple ongoing factors, and much more.
2. **`graphics.py`**: This file is a modified version of the tkinter-based [cmu_112_graphics](https://www.cs.cmu.edu/~112/notes/notes-graphics.html) package and contains the implementation for the graphics used in the game. It provides various classes and functions to handle graphical elements, such as windows, points, lines, circles, and text.
3. **`images`**: This folder stores the images used and displayed in the game window.

## Installation and Dependencies

General:
- **Python**: The app can successfully run on `Python 3.7.9`, but should work on most versions of Python.
- **[pyautogui](https://pyautogui.readthedocs.io)**: Mouse and keyboard assistance for more interactive gameplay.

Step-by-step:
1. Clone the repository to your local machine.
2. Navigate to the repository's main directory.
3. Make sure to have `pip` and `Python` installed on your device.
4. Run `pip install -r requirements.txt`.
5. Run the `tanks.py` file using Python.

## Contributing

Feel free to fork the repository and submit pull requests for any enhancements or bug fixes. Contributions are always welcome!

