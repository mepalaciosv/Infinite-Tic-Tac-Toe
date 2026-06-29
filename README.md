# Infinite Tic-Tac-Toe

Computational exploration of a tic-tac-toe variant in which, after the first six turns, players move their existing pieces instead of placing new ones.

This repository accompanies the article *El triqui infinito* (2026) and reproduces the computational results reported there. It contains a Jupyter notebook (in Spanish) that constructs the game state graph and verifies all results presented in the article.

Internally, the program represents a state as (board, player_to_move). The graph analyzed in the article is obtained by projecting these states onto board configurations.

## The notebook
- explores all reachable configurations;
- constructs the game state graph;
- identifies terminal and non-terminal configurations;
- verifies that the graph induced by the non-terminal configurations is strongly connected.
## Results

- Reachable six-piece configurations: **1520**
- Terminal configurations: **148**
- Non-terminal configurations: **1372**
- The graph induced by the non-terminal configurations is strongly connected.

## Repository contents
- `triqui_infinito.ipynb` *(Spanish)*: Jupyter notebook containing the computational exploration described in the accompanying article. It reproduces all reported counts and verifies the connectivity properties of the game graph.
