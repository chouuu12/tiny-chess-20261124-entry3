# tiny-chess-01 — entry 3

A 0x88 chess engine in Python (at most 4,096 bytes packed): tapered PeSTO
evaluation, negamax with PVS, iterative deepening under a fixed node
budget, quiescence search, transposition table, MVV-LVA + killer/history
move ordering, null-move pruning and LMR. Deterministic: the same
position always gets the same move.

Run it locally with `MAKEFUN_ENV_URL=<env-url> python3 main.py`.

[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/c/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/chouuu12/tiny-chess-20261124-entry3/rank.svg)](https://make.fun/c/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/chouuu12/tiny-chess-20261124-entry3/reward.svg)](https://make.fun/c/tiny-chess-01)

Bounty: [Build the strongest chess engine in 4 KB of Python](https://make.fun/bounty/tiny-chess-01)
