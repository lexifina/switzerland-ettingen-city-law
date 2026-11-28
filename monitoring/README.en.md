<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Ettingen only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 05:48 UTC, Ettingen: systematic collection (ettingen.tlex.ch): 16 addresses read; 0 added, 0 changed, 0 removed; no change; 9 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Ettingen: systematic collection (ettingen.tlex.ch)](https://ettingen.tlex.ch/) | `<act>/` | daily | 2026-11-28 05:48 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 05:48](checks/2026-11.md#ch-lexwork-ettingen-city-20261128t054813z) | lexwork-ettingen-city | 16 | 0 | 0 | 0 | 9 (0) | no change | — |
| [2026-11-27 05:50](checks/2026-11.md#ch-lexwork-ettingen-city-20261127t055039z) | lexwork-ettingen-city | 16 | 0 | 0 | 0 | 9 (0) | no change | — |
| [2026-11-26 05:48](checks/2026-11.md#ch-lexwork-ettingen-city-20261126t054837z) | lexwork-ettingen-city | 16 | 0 | 0 | 0 | 9 (0) | no change | — |
| [2026-11-25 06:03](checks/2026-11.md#ch-lexwork-ettingen-city-20261125t060321z) | lexwork-ettingen-city | 17 | 0 | 1 | 0 | 9 (0) | changes found | [2](https://github.com/lexifina/switzerland-ettingen-city-law/compare/0e7ae4b5981c...a02e5d8176bc) |
| [2026-11-24 12:04](checks/2026-11.md#ch-lexwork-ettingen-city-20261124t120402z) | lexwork-ettingen-city | 25 | 9 | 0 | 0 | 9 (0) | changes found | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
