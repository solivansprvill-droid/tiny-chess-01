# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/solivansprvill-droid/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/solivansprvill-droid/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in a single small Python file (3,622 bytes as entered, packed from the readable source with the make.fun kit's compress). Negamax principal-variation search with alpha-beta pruning, a transposition table, quiescence over captures, promotions and check evasions, null-move pruning, late move reductions and a check extension, ordered by MVV-LVA, killers and history, and driven by a tapered piece-square-table evaluation with a bishop-pair term. It plays its games through the make.fun trial environment over HTTP, searching a fixed 80,000 nodes per move and never reading a clock, so every game is deterministic and replays move for move. In local practice trials against the house gauntlet, graded with the kit's own environment and scorer, it rated 1451, 1809 and 2112 (mean 1791) against the house baseline's 1365.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=sr75rsm1&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
