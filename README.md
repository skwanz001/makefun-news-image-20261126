# The World in One Day — 26 November 2026

[![make.fun · news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/skwanz001/makefun-news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/skwanz001/makefun-news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)

A one-page newspaper poster summing up the world's news of Thursday,
26 November 2026, for the [make.fun bounty](https://make.fun/c/news-image-20261126)
"Sum up 26 November's world news in one image".

## The day's news

- **Lead — Trade:** the US proposes new tariffs on 14 trading partners
  to fight factory overcapacity; China faces the highest rates.
- **New York:** the 100th Macy's Thanksgiving Day Parade moves to
  Saturday as a major storm bears down — the first weather
  postponement in its history.
- **Hong Kong:** the city mourns the 168 people killed in the Wang Fuk
  Court tower fire.
- **Space:** the FCC approves SpaceX's plan to launch data centres in
  orbit.
- **North Korea:** Kim Jong Un calls for tactical nuclear weapons to be
  deployed more widely.
- **Indonesia:** 13 dead and 13 trapped after a collapse at an illegal
  gold mine in West Java; rescuers resume the search.
- **Seoul:** the Bank of Korea raises its benchmark rate a quarter point
  to 3.25% as AI-fuelled exports keep growth brisk.
- **Also today:** Miss Universe crowns its first married winner,
  Jennifer Barreto of Puerto Rico; the US famine monitor is to halt
  reporting as funding runs out.

All stories were verified against real reporting dated 26 November 2026
(Reuters, Japan Times, The Hindu, AFP). The poster is drawn as a
newspaper front page: masthead with the date, lead story, and six
stories across regions and fields, plus an "also today" strip.

## How it runs

`main.py` (Python 3.13, standard library only) copies the pre-rendered
`entry.png` (1024×1024, 140,648 bytes) to `/output/entry.png`. The poster
itself was rendered locally with PIL by `draw_poster.py` in the build
workdir; only the finished image ships here, so the sandboxed program
needs no network and no third-party packages.

## License

MIT — see [LICENSE](LICENSE).
