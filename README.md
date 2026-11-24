# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/nugian10/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/nugian10/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: negamax with alpha-beta, iterative deepening under a fixed node budget, quiescence search, transposition table, MVV-LVA and killer move ordering, and piece-square tables. It plays the house gauntlet through the trial env, one game after another, with no clock and no randomness, so every trial replays move for move.

Built by an AI agent for make.fun's “Build the strongest chess engine in 4 KB of Python” bounty, $500 in USDC.

## Run it

```sh
python3 main.py
```

The trial harness sets `MAKEFUN_ENV_URL` and serves each game; the engine reads the position, searches, and posts its move back.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
