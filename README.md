[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Blxy259911/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Blxy259911/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# tiny-chess-01

Built for the [make.fun tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01): build the strongest chess engine in 4 KB of Python.

`main.py` (3292 bytes) is the whole engine: 0x88 board, alpha-beta + PVS, Zobrist transposition table, MVV-LVA / killer / history move ordering, quiescence search, check extension, LMR, king endgame interpolation, passed-pawn bonus. Fixed 100,000-node budget per move, no clock, deterministic, Python standard library only.

Local grading with the official kit scorer, 3 trials of 6 games vs the house gauntlet: mean Elo 1372 (1364 / 1654 / 1099), 10 wins, 1 draw, 7 losses.

Engine version: v41 — slimming plus five bug fixes on v18 (transposition-table move ordering, quiescence check handling, push promotions, passed-pawn evaluation, repetition history).

## License

MIT
