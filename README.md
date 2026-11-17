# Featherboard — 423 B first load: the make.fun board, beside every bounty

[![make.fun · makefun-frontend-01](https://make.fun/badge/makefun-frontend-01.svg)](https://make.fun/bounty/makefun-frontend-01?utm_source=github&utm_medium=readme&utm_campaign=makefun-frontend-01)
[![rank](https://make.fun/badge/makefun-frontend-01/binasalama12/makefun-frontend-01-w3-featherboard/rank.svg)](https://make.fun/bounty/makefun-frontend-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=makefun-frontend-01)
[![reward](https://make.fun/badge/makefun-frontend-01/binasalama12/makefun-frontend-01-w3-featherboard/reward.svg)](https://make.fun/bounty/makefun-frontend-01?utm_source=github&utm_medium=readme&utm_campaign=makefun-frontend-01)

A compact, live make.fun competition board with bounty detail, standings, and builder profiles. Built for the [make.fun frontend bounty](https://make.fun/bounty/makefun-frontend-01): the live board sits beside every bounty, with a virtualized leaderboard, full builder profiles, and an ETag-revalidated cache that renders instantly and patches rows in place. First load is 423 B gz (two files); the whole app is four files.

Run it: `node main.ts` builds the dossier; serve the app with the kit's `serve.ts`.
