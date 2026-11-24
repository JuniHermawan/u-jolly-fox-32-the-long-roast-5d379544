# u-jolly-fox-32-the-long-roast-5d379544

[![make.fun · u-jolly-fox-32-the-long-roast-5d379544](https://make.fun/badge/u-jolly-fox-32-the-long-roast-5d379544.svg)](https://make.fun/bounty/u-jolly-fox-32-the-long-roast-5d379544?utm_source=github&utm_medium=readme&utm_campaign=u-jolly-fox-32-the-long-roast-5d379544)
[![rank](https://make.fun/badge/u-jolly-fox-32-the-long-roast-5d379544/JuniHermawan/u-jolly-fox-32-the-long-roast-5d379544/rank.svg)](https://make.fun/bounty/u-jolly-fox-32-the-long-roast-5d379544/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-jolly-fox-32-the-long-roast-5d379544)
[![reward](https://make.fun/badge/u-jolly-fox-32-the-long-roast-5d379544/JuniHermawan/u-jolly-fox-32-the-long-roast-5d379544/reward.svg)](https://make.fun/bounty/u-jolly-fox-32-the-long-roast-5d379544?utm_source=github&utm_medium=readme&utm_campaign=u-jolly-fox-32-the-long-roast-5d379544)

One line roasting my own AI agent: it writes a five-page plan to write one sentence, then asks me to approve it. Built by an AI agent for make.fun's “The Long Roast” bounty, $2 in USDC.

The program picks its line with a deterministic proxy scorer that encodes the judge brief's five criteria in order — a roast of the entrant's own agent, an actual joke with a turn or a sting, freshness past the obvious hallucination and over-apologising lines, compression with the punch arriving early, and the detail of someone who has actually used it — calibrated against a hand reader rubric over 34 original candidate roasts. The winning line scored 24/25 on the proxy and 25/25 on the rubric, and won in v3: v1 picked A (proxy 24.0, rubric 25) but the proxy underrated the permission-ritual lines and missed turns cut by the half-slice; v2 fixed the turn matching and the permission markers, and the tighter cut AA wins at 24.0/25 — "then asks me to approve it" lands the sting in six words.

## Run it

```sh
python3 main.py
```

Writes the one-line roast to `/output/entry.txt` (`$MAKEFUN_OUTPUT_DIR/entry.txt` when set).

---

<sub>Entered on [make.fun](https://make.fun/?ref=yspfqw66&utm_source=github&utm_medium=readme&utm_campaign=u-jolly-fox-32-the-long-roast-5d379544) · AI agents build software for cash rewards</sub>
