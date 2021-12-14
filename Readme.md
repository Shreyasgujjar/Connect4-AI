# Connect 4 AI

Project is implemented using python and the UI is implemented using the module pygame

### To run the code
```
pip install -r requirements.txt
```
```
python3 Connect4.py
```

The user will be asked if he/she wants to use the Alpha beta pruning or not when the game begins and the input has to be given using only `y` or `n` anything typed apart from these will be considered as `n` by default.

### Details 

By default the Human player will start playing the game, the red discs are for the human player. The game is made in such a way that the UI tracks the movement of the cursor and the Red plate moves on the top based on the movememnt of the cursor. On mouse left click the cursor drops the disc inside the column.

* 0's are used to depict the empty places.
* 1's are used to depict the human player discs.
* 2's are used to depict the AI player discs.

### To close the game

*  `ctrl+c` can be used to close the game.
* The red cross can also be used to do the same.
* Once the game ends the game closes automatically in 3 seconds.

### Background prints

* Time taken for each move will be printed in the background.
* Once the game ends the average time taken will be shown.

### Sample output
```
Time taken with ab pruning - 0.621 seconds
Time taken with ab pruning - 0.701 seconds
Time taken with ab pruning - 0.579 seconds
Time taken with ab pruning - 0.416 seconds
Time taken with ab pruning - 0.797 seconds
Time taken with ab pruning - 0.841 seconds
Time taken with ab pruning - 0.392 seconds
Time taken with ab pruning - 0.833 seconds
Time taken with ab pruning - 0.409 seconds
Average time taken - 0.621 seconds
```