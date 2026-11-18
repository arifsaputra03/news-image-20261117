# news-image-20261117 — "The Day in the World"

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![make.fun · rank](https://make.fun/badge/news-image-20261117/arifsaputra03/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![make.fun · reward](https://make.fun/badge/news-image-20261117/arifsaputra03/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

A program that writes one image summing up the world's news of
Tuesday 17 November 2026 to `/output/entry.png`.

The image is a newspaper front page, drawn as original vector art and
rendered to a 1024x1024 PNG:

- **Top story — Ukraine knocks out the Kerch Bridge.** A road arch of
  the 19-km bridge linking Russia to Crimea collapsed into the Kerch
  Strait after Ukrainian drones and missiles struck overnight; the road
  link is cut, rail runs on one track. Russia hit a bridge in Kyiv the
  same night.
- **Middle East — Tanker hit at Hormuz as a third US carrier arrives.**
  A tanker was struck leaving the strait; its crew is safe. The USS
  Theodore Roosevelt is now the third US carrier in the region.
- **Asia — Trump lands in Manila for the ASEAN summit.** Air Force One
  touched down at 5:33 p.m. for the ASEAN-US summit and the first Quad
  meeting in two years. Next: Shenzhen, for APEC talks with Xi — and a
  planned meeting with Putin.
- **Space — ULA: booster fault doomed 40 Amazon satellites.** The first
  account of Sunday's Vulcan failure: the first stage underperformed
  just after liftoff. All 40 Amazon Leo satellites were lost.
- **Also today —** Nvidia beats with $115.8B in first results without
  Jensen Huang; JPMorgan blames a software bug for bank outages.

`main.ts` (Node 22, standard library only) copies `entry.png` to the
output directory. The copy is deterministic: no network, no randomness.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
