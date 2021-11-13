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

P/s: my evaluation function works best with -a depth=1 which means the pacman calculate 1 step before moving (it knows where the ghost will go).

Some gameplay videos:

- [![Open classic map, depth=1](videos_gameplay/pacman_openClassic_depth_1.webm)](videos_gameplay/pacman_openClassic_depth_1.webm)
- [![Trapped classic map, depth=1](videos_gameplay/pacman_trappedClassic_depth_1.webm)](videos_gameplay/pacman_trappedClassic_depth_1.webm)
- [![Original classic map, depth=1](videos_gameplay/pacman_originalClassic_depth_1.webm)](videos_gameplay/pacman_originalClassic_depth_1.webm)
- [Power classic map, depth=1](videos_gameplay/pacman_powerClassic_depth_1.webm)](videos_gameplay/pacman_powerClassic_depth_1.webm)
