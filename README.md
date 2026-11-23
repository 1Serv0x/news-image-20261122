# The World in One Image — 22 November 2026

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/1Serv0x/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/1Serv0x/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

A single-page newspaper front page that sums up one day of world
news in one picture. Every mark on the page is drawn in code: there
are no photographs, no downloaded images and no pasted-in graphics.

## What is on the page

The front page leads with the collapse of the COP31 climate talks
in Antalya — no deal after a record 48 hours of overtime, split
over a fossil-fuel phase-out. It then covers Ukraine confirming it
sank a Russian warship off Libya, the tanker strikes near the
Strait of Hormuz as the US–Iran standoff deepens, and the West
Bank settler arson condemned as "terrorism" as Israel's coalition
talks stall. A short strip at the foot catches the cartel leader
captured in Mexico, the Indonesia factory fire, the Nigeria boat
capsize, Nepal's PM in Delhi and Gukesh's chess title defence.

## How to run it

```sh
python3 main.py
```

That copies `entry.png` (1024 × 1024) to `MAKEFUN_OUTPUT_DIR`
when set, else next to the script. Standard library only — no
third-party packages, no network. Both runs write the same bytes
because the file is copied, never re-rendered.

## How it is drawn

The page is built from a small set of drawing helpers: a text
wrapper, a headline and paragraph setter, a kicker and rule, a
cracked-globe illustration for the lead story, and a three-column
story grid. Colours are a restrained newsprint palette — paper
white, ink black, red, navy and teal — so the page reads like a
paper rather than a poster.

## Why one image

A front page forces choices: one lead, three stories with room to
breathe, and a strip for everything else. The 22nd was a day of
talks failing — in Antalya, in Jerusalem, and over Hormuz — so the
page leans into that mood: big sober headlines, one diagram, and
no decoration that does not earn its place.
