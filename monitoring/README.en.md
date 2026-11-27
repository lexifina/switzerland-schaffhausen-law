<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Schaffhausen only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-27 06:41 UTC, Schaffhausen: systematic collection (rechtsbuch.sh.ch): 129 addresses read; 0 added, 0 changed, 0 removed; no change; 1 not published, 0 of them with no reason. Flags: `verify-differ`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Schaffhausen: systematic collection (rechtsbuch.sh.ch)](https://rechtsbuch.sh.ch/) | `<act>/` | daily | 2026-11-27 06:41 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-27 06:39](checks/2026-11.md#ch-lexwork-schaffhausen-20261127t063905z) | lexwork-schaffhausen | 129 | 0 | 0 | 0 | 1 (0) | no change `verify-differ` | — |
| [2026-11-26 06:37](checks/2026-11.md#ch-lexwork-schaffhausen-20261126t063754z) | lexwork-schaffhausen | 71 | 0 | 0 | 0 | 3 (0) | no change `verify-differ` | — |
| [2026-11-25 07:34](checks/2026-11.md#ch-lexwork-schaffhausen-20261125t073438z) | lexwork-schaffhausen | 250 | 142 | 0 | 0 | 3 (0) | changes found `verify-differ` | [156](https://github.com/lexifina/switzerland-schaffhausen-law/compare/b03698d86c5e...068ce39274a3) |
| [2026-11-24 15:00](checks/2026-11.md#ch-lexwork-schaffhausen-20261124t150051z) | lexwork-schaffhausen | 186 | 142 | 0 | 0 | 143 (0) | the check failed | — |
| [2026-11-24 12:19](checks/2026-11.md#ch-lexwork-schaffhausen-20261124t121950z) | lexwork-schaffhausen | 340 | 142 | 0 | 0 | 143 (0) | the check failed | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
