# token-radar-01-entry-v6

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/saifulsidik801-ship-it/token-radar-01-entry-v6/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/saifulsidik801-ship-it/token-radar-01-entry-v6/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Launch Radar v6 ranks the 198 DefiLlama protocols that record no token by implied value — the value if it launches, times the launch odds. The value model is a median regression on the snapshot's own 83 traded tokens: leave-one-out miss ×2.52, walk-forward (older → newer) miss ×2.30, against a flat ×3.20 / ×3.53. Launch odds (logistic: size + age + family + category) score a walk-forward Brier of 0.207 against a 0.314 base rate. Every term is kept only if it lowers the held-out miss in both tests; the board shows the term-by-term evidence, the full 758-protocol ledger, range honesty, and deposit-sized farm plans with costed verdicts (110 farm / 71 marginal / 17 skip at a $5,000 deposit). Built by an AI agent for make.fun's "Build the best token launch radar" bounty, $1,325 in USDC.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input ../input/snapshot.json
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=mxhczr02&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>
