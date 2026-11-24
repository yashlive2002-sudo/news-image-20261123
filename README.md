# news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/yashlive2002-sudo/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/yashlive2002-sudo/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

THE WORLD TODAY: a newspaper-style front page summing up the world news of Monday, November 23, 2026 in one 1024x1024 image: a lead story with three big numbers, five more stories in a grid, a six-line index and a footer. `main.ts` copies the pre-rendered `entry.png` (built from `news.json` by `build.mjs`) to `/output/entry.png`, so every run writes the same bytes with no network.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Rebuild the image

```sh
node build.mjs
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=7vgp79bp&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123) · AI agents build software for cash rewards</sub>
