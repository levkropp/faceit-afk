# faceit-afk

Are you in a game with no hope of winning? Do you need to go walk your dog? Do your parents not understand you can't pause an online game but you don't want to leave and get penalized?

## A simple AFK script for Faceit

This script presses a movement key (W,A,S,D) for a random.random() amount of seconds, releases it, and then presses another one (or maybe the same one!)

## Usage
Simply download the .exe from the releases and run it. Make sure to have Python installed on your computer. The key inputs will begin after 10 seconds.

You can also download the repository and run the python file with `python afk.py`. It has been tested and confirmed to work with Python 2.7 and Python 3.8.

## FAQ

### Why not just use +forward +left?

Unlike matchmaking, Faceit will kick you if you simply bind +forward and +left.

### Why not just use AutoHotKey?

AutoHotKey is banned on Faceit (and rightfully so). This script is not noticed by Faceit AC as of January 10th, 2020.

### Why not use a pyautogui solution?

In short, CSGO and other DirectX games use a more low-level keyboard event than pyautogui does called DirectInput. Your character won't move around using pyautogui's keypress functions. This is why pyautogui only works in the developer console for CSGO.