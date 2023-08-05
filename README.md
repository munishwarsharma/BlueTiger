# BlueTiger

## Overview
This is a C++ implementation of a Chess Engine, designed to play a game of chess against a human player or another chess engine. The engine uses the popular minimax algorithm with alpha-beta pruning to search for the best moves efficiently.

## Features
**Bitboard Representation:** Chess Board is represented as U64 bits of integer i.e unsigned long long 

**Chess Rules:** The engine strictly follows the standard rules of chess, including en passant, castling, pawn promotion, check, and checkmate.

**Negamax Algorithm:** The engine uses the Negamax algorithm to search for the best moves based on a given evaluation function. 

**Alpha-Beta Pruning:** To speed up the search process, alpha-beta pruning has been implemented to cut off irrelevant branches of the search tree.

**Move Generation:** The engine can efficiently generate all legal moves for a given board position.

**UCI Interface:** Universal Chess interface has been provided for human interaction with the engine. Users can play against any engine using softwares like   Arena or any othe GUI

**Perft Test:** To check if the engine is calculating right moves or not

**MVV LVA:** Added simple heuristic to generate or sort capture moves in a reasonable order

**PV Moves:** Added so that in interative deepining moves which have high score can be ordered first

## Requirements
C++17 compatible compiler

## Acknowledgments
A big thank you to the creators of various open-source chess engines and libraries that inspired and provided valuable insights for this project.
