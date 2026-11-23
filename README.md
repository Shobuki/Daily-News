# hn-daily-digest

A daily archive of the [Hacker News](https://news.ycombinator.com) front page.

Every 3 hours a GitHub Actions job takes a snapshot of the front page and merges it into that day's archive. Stories that have dropped off are kept, and stories still on the page get fresh points and comment counts. By the end of the day the archive holds every story that reached the front page:

- `archive/YYYY/MM/YYYY-MM-DD.md`: a readable table of the day's stories, sorted by points
- `archive/YYYY/MM/YYYY-MM-DD.json`: the same data, ready for analysis

It uses the public [Algolia HN API](https://hn.algolia.com/api), falls back to the [official Firebase API](https://github.com/HackerNews/API), and has no dependencies beyond the Python standard library.

## Run it locally

```sh
python scripts/digest.py
```

<!-- digest:start -->
### Latest: [2026-11-23](archive/2026/11/2026-11-23.md)

Top 10 of 45 stories so far, last updated 2026-11-23 12:40 UTC. **25** days archived.

| # | Story | Points | Comments |
|--:|---|--:|--:|
| 1 | [Toyota, Nissan, and Honda to standardize parts to lower costs](https://www.caranddriver.com/news/a74490092/toyota-nissan-honda-standardize-parts-lower-costs/) <sub>caranddriver.com</sub> | 1327 | [710](https://news.ycombinator.com/item?id=50596133) |
| 2 | [What Happened to Silicon Valley?](https://www.oreilly.com/radar/what-happened-to-silicon-valley/) <sub>oreilly.com</sub> | 711 | [382](https://news.ycombinator.com/item?id=50602947) |
| 3 | [Perplexity and Intelligence](https://openai.com/index/perplexity-and-intelligence/) <sub>openai.com</sub> | 613 | [407](https://news.ycombinator.com/item?id=50601525) |
| 4 | [Free alternative TV network built from the Internet Archive's forgotten videos](https://spelunkr.tv) <sub>spelunkr.tv</sub> | 608 | [110](https://news.ycombinator.com/item?id=50606192) |
| 5 | [A Beginner's Guide to Local AI with Inkling, Qwen, and Unsloth](https://www.gpupartner.com/blog/beginners-guide-local-ai-inkling-qwen-unsloth) <sub>gpupartner.com</sub> | 571 | [238](https://news.ycombinator.com/item?id=50603845) |
| 6 | [The Birds of GTA 6: A Field Guide to Vice City and Leonida's Wildlife](https://www.audubon.org/magazine/birds-of-gta-6-field-guide-vice-city-wildlife) <sub>audubon.org</sub> | 535 | [282](https://news.ycombinator.com/item?id=50602843) |
| 7 | [XNU Linux: Full OS X GUI Userspace on Linux](https://github.com/AFK-surf/xnulinux) <sub>github.com</sub> | 400 | [186](https://news.ycombinator.com/item?id=50607261) |
| 8 | [Show HN: I built a game where you are an LLM's subagent](https://github.com/gulivan/worker755) <sub>github.com</sub> | 331 | [79](https://news.ycombinator.com/item?id=50599762) |
| 9 | [A miniature San Francisco with live buses, planes and boats](https://smallsf.com/) <sub>smallsf.com</sub> | 296 | [96](https://news.ycombinator.com/item?id=50603589) |
| 10 | [Cathedral floor emerges in Sudan, revealing one of the biggest medieval churches](https://apnews.com/article/sudan-antiquities-nubia-cathedral-1b16f67da881ee5592de4481ee55c527) <sub>apnews.com</sub> | 274 | [85](https://news.ycombinator.com/item?id=50547698) |
<!-- digest:end -->
