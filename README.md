# Infinite Tic-Tac-Toe

Computational exploration of a tic-tac-toe variant in which, after the first six turns, players move their existing pieces instead of placing new ones.

This repository accompanies the article "El triqui infinito" (2026) and reproduces the computational results reported there.

The notebook:
  - explores all reachable configurations;
  - constructs the graph of legal positions;
  - identifies terminal and non-terminal states;
  - verifies that the graph induced by non-terminal positions is strongly connected.

Results
  - Reachable six-piece configurations: 1520
  - Terminal configurations: 148
  - Non-terminal configurations: 1372
  - The induced graph on non-terminal configurations is strongly connected.
