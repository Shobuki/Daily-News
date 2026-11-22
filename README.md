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
### Latest: [2026-11-22](archive/2026/11/2026-11-22.md)

Top 10 of 30 stories so far, last updated 2026-11-22 01:26 UTC. **24** days archived.

| # | Story | Points | Comments |
|--:|---|--:|--:|
| 1 | [Inkling 2 Mini](https://thinkingmachines.ai/news/inkling-2-mini/) <sub>thinkingmachines.ai</sub> | 1384 | [280](https://news.ycombinator.com/item?id=50581260) |
| 2 | [Lean verification of the Riemann Hypothesis](https://leanprover-community.github.io/blog/posts/riemann-hypothesis/) <sub>leanprover-community.github.io</sub> | 823 | [665](https://news.ycombinator.com/item?id=50589618) |
| 3 | [Brazil's tax authority open-sources its tax calculator on GitHub under MIT](https://www.gov.br/receitafederal/pt-br/assuntos/noticias/2026/novembro/receita-federal-publica-primeiro-codigo-fonte-aberto-no-github-e-amplia-transparencia-da-reforma-tributaria) <sub>gov.br</sub> | 745 | [239](https://news.ycombinator.com/item?id=50532613) |
| 4 | [Ask HN: I have been unemployed for 2y. 15 years of experience, US. What to do?](https://news.ycombinator.com/item?id=50583761) <sub>news.ycombinator.com</sub> | 609 | [680](https://news.ycombinator.com/item?id=50583761) |
| 5 | [Pill to treat pancreatic cancer hailed as 'biggest breakthrough in decades'](https://www.theguardian.com/society/2026/nov/20/pill-pancreatic-cancer-breakthrough-daraxonrasib) <sub>theguardian.com</sub> | 585 | [140](https://news.ycombinator.com/item?id=50582069) |
| 6 | [Detonating a pile of lead azide](https://www.science.org/content/blog-post/detonating-huge-pile-lead-azide-really) <sub>science.org</sub> | 515 | [345](https://news.ycombinator.com/item?id=50588982) |
| 7 | [My monitor was cutting my download speed by 75%](https://blog.tymscar.com/posts/studiodisplayethernet/) <sub>blog.tymscar.com</sub> | 482 | [231](https://news.ycombinator.com/item?id=50587875) |
| 8 | [Why there are still no non-WebKit browsers on iOS](https://blog.mozilla.org/en/mozilla/internet-policy/apple-ios-browser-engine-rules/) <sub>blog.mozilla.org</sub> | 481 | [269](https://news.ycombinator.com/item?id=50575644) |
| 9 | [Inkling-2-Mini in 5.4 GB Memory](https://github.com/ShinMegamiBoson/lookatmyquant) <sub>github.com</sub> | 349 | [91](https://news.ycombinator.com/item?id=50591853) |
| 10 | [RCE in Gnupg](https://lists.gnupg.org/pipermail/gnupg-announce/2026q4/000517.html) <sub>lists.gnupg.org</sub> | 231 | [93](https://news.ycombinator.com/item?id=50587208) |
<!-- digest:end -->
