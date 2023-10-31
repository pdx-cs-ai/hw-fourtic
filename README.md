# Fourtic problems
Bart Massey 2023-10-23

This repository contains 12 Fourtic problems. Fourtic is a
4×4 Tic-Tac-Toe variant designed as an AI homework
problem.

The six `rand` problems are from randomly-generated board
positions. The six `play` problems are positions from real
computer-vs-computer games. (The player played with depth-4
negamax, but that is somewhat irrelevant here.)

The solutions (all 14 evaluated with unlimited depth) are:

    rand-2: X 3
    rand-3: O 0
    rand-4: X 3
    rand-5: O 0
    rand-6: X 0
    rand-7: O 1
    play-2: X 3
    play-3: O -3
    play-4: X 3
    play-5: O 0
    play-6: X 4
    play-7: O -2

Note the first-player bias in games from real play. It is
unknown how large this bias is with strong play.  Fourtic is
currently unsolved, so it is not known whether the game is a
first-player win or a draw.
