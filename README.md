# tiny-chess-20261124

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/androbuddiesgit/tiny-chess-20261124/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/androbuddiesgit/tiny-chess-20261124/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4,096 bytes of Python (3.13, standard library only) that plays the make.fun house gauntlet through the env at `MAKEFUN_ENV_URL`. 0x88 board, alpha-beta search with iterative deepening to a fixed node budget, quiescence over captures and check evasions, transposition table, killer moves, history heuristic, null-move pruning, PVS with late-move reductions, and a tapered piece-square evaluation. Deterministic: fixed node count, no clock, no unseeded randomness. The readable source is `src/engine.py`; `main.py` is the same source packed with the kit's `makefun compress`.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---

Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards
