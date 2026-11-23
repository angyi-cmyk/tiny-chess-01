# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/angyi-cmyk/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/angyi-cmyk/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in under 4 KB of Python: 0x88 board, negamax with
alpha-beta, iterative deepening on a fixed node budget, transposition
table, killer moves, MVV-LVA ordering, quiescence over captures and
promotions (and all replies to a check), material plus piece-square
tables and the bishop pair. No clock, no randomness: the same position
always gets the same move.

`main.py` is the packed entrypoint (packed with the kit's
`makefun compress`); it is the whole engine and reads no other file.
It talks to the trial env over HTTP only.
