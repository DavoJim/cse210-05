# cse210-05
Gem catcher

# Cycle Game
Cycle is a game where the players try to cut each other off using cycles that leave a trail behind them.

## Getting Started
---
Make sure you have Python 3.8.0 or newer installed and running on your machine. Open a terminal and browse to the project's root folder. Start the program by running the following command.
```
python3 -m pip install raylib
```
You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the project folder. Select the main module inside the hunter folder and click the "run" icon.

## Project Structure
---
The project files and folders are organized as follows:
```
root                        (project root folder)
+--game
    +-- casting                 (source code for game)
        +--actor.py
        +--cast.py
        +--player1.py
        +--player2.py
        +--score.py
    +-- directing               (source code for game)
        +--director.py
    +--scripting                (source code for game)
        +--action.py
        +--control_player1_action.py
        +--control_player2_action.py
        +--draw_actors_action.py
        +--handle_collisions_action.py
        +--move_actors_action.py
        +--script.py
    +-- services                 (source code for game)
        +--keyboard_service.py
        +--video_service.py
    +-- shared                  (source code for game)
        +--color.py
        +--point.py
+-- __main__.py             (entry point for program)
+-- constants.py
README.md               (genral info)
    ```


## Required Technologies
---
* Python 3.8.0
* Raylib Python CFFI 3.7

## Authors
---
David Larsen

## Contributions
---
David Larsen