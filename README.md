# 2048-ai-comparison

Comparison of different MCTS inputs to solve the 2048 game. Only AI files are part of this project, game implementation used from [kiteco GitHub](https://github.com/kiteco/python-youtube-code/tree/master/build-2048-in-python).

## Installation :
This project runs under Python 3 (tested 3.9 and 3.10)

It uses the given libraries : `numpy` and `tkinter`. Make sure there installed with `pip3 list` or `pip3 show <package>`. If they are not, use `pip3 install <package>`

## Usage :
To launch the main program, use : `python3 game_display.py`

Here is a list of the key commands that can be useful :

| Key | Command |
|-----|---------|
| `W` | UP_KEY  |
| `S` | DOWN_KEY |
| `A` | LEFT_KEY |
| `D` | RIGHT_KEY |
| `I` | INIT (re-init the board) |
| `M` | AI_MCTS (score)|
| `B` | AI_MCTS2 (sum) |
| `V` | AI_MCTS3 (max) |
| `R` | AI_RANDOM |


**Note :** Every AI Algorithm stops when the game is stuck (not when reaching 2048 !)
