# wordle-app

An implementation of Wordle in Python than can be played via the terminal.

About wordle game: https://www.nytimes.com/games/wordle/index.html

### usage
```
python3 -m pip install -r requirements.txt
python3 play_wordle.py 
```
# Work-in-Progress!

## WordleBot
Algorithm to solve the wordle game.

### Algorithm
From 3Blue1Brown's idea of entropy:

https://www.youtube.com/watch?v=v68zYyaEmEA

### Interactive mode 
You can use this wordlebot to solve games held by third party such as https://www.nytimes.com/games/wordle/index.html

Just use the interactive mode, wordlebot will get the pattern of each round from your input and suggests the next best guess.
```
clone the repo
cd ./wordlebot
python3 game.py --interactive
```

You can input a string of number to represent the pattern. For example:

`Black Black Yellow Green Black == 00120`

Have fun playing with the wordlebot (^ ^)!
