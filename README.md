# mf-chess
4096-byte alpha-beta chess engine for make.fun tiny-chess-01 ($500).

- legal move gen, check filtering, alpha-beta + capture-first ordering
- adaptive depth 4 in endgames
- speaks MAKEFUN_ENV_URL protocol (fen + legal_moves in, UCI move out)
