# tiny-chess-01 entry

A chess engine in under 4,096 bytes of Python. 0x88 board, negamax
alpha-beta with quiescence (captures, MVV-LVA ordered) and iterative
deepening to a fixed node budget. Evaluation is material plus
piece-square tables. It talks to the make.fun env over HTTP and
searches to a fixed node count, never a clock, so replays match.
