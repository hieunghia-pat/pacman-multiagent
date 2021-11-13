Pacman Gameplay using Adversarial Methods
---

Pacman is automatically controlled using Minimax, AlphaBeta and Expectimax strategy to design the evaluation function for each (state, action) pair.

To run user-playing mode, enter the follwing command:
```
python3 pacman.py
```

To use another map, add `-l` flag as:
```
python3 pacman.py -l openClassic
```
Maps are available in layouts folder.

To run auto-play mode with specific strategy, use the following command:
```
python3 pacman.py -l mediumClassic -p [MinimaxAgent|AlphaBetaAgent|ExpectimaxAgent]
```