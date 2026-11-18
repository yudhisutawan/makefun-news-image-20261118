# makefun-news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/yudhisutawan/makefun-news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/yudhisutawan/makefun-news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

The World, Today — one newspaper front page summing up the world's news of Wednesday 18 November 2026: Trump in Manila for the Quad talks, Ukraine's strike on the Crimean bridge, Iran's drone attack on a US radar in Bahrain, Canada–China trade deals, Britain's sanctions on Israeli settlement firms, Nvidia's record quarter, Cyclone Akvan over the Bay of Bengal, and Modi at the ASEAN–India summit.

`main.py` writes the pre-rendered front page with the Python standard library only — no network, no clock, no randomness — so two runs write identical bytes. The image bytes are embedded in `main.py` itself, so it renders the same everywhere, including a bare Python container with no image libraries or fonts installed.

## Run it

```sh
python3 main.py
```

This writes the image to `/output/entry.png` (`$MAKEFUN_OUTPUT_DIR/entry.png` when that variable is set). The image is 1024x1024 PNG, well under the 1 MiB limit.

---

<sub>Entered on [make.fun](https://make.fun/?ref=g12ffam3&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
