<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für Schaffhausen: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-28 06:32 UTC, Schaffhausen: Systematische Sammlung (rechtsbuch.sh.ch): 133 Adressen gelesen; 0 hinzugefügt, 0 geändert, 0 entfernt; keine Änderung; 2 nicht veröffentlicht, davon 0 ohne Grund. Hinweise: `verify-differ`.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [Schaffhausen: Systematische Sammlung (rechtsbuch.sh.ch)](https://rechtsbuch.sh.ch/) | `<act>/` | täglich | 2026-11-28 06:32 UTC | keine Änderung | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 06:29](checks/2026-11.md#ch-lexwork-schaffhausen-20261128t062956z) | lexwork-schaffhausen | 133 | 0 | 0 | 0 | 2 (0) | keine Änderung `verify-differ` | — |
| [2026-11-27 06:39](checks/2026-11.md#ch-lexwork-schaffhausen-20261127t063905z) | lexwork-schaffhausen | 129 | 0 | 0 | 0 | 1 (0) | keine Änderung `verify-differ` | — |
| [2026-11-26 06:37](checks/2026-11.md#ch-lexwork-schaffhausen-20261126t063754z) | lexwork-schaffhausen | 71 | 0 | 0 | 0 | 3 (0) | keine Änderung `verify-differ` | — |
| [2026-11-25 07:34](checks/2026-11.md#ch-lexwork-schaffhausen-20261125t073438z) | lexwork-schaffhausen | 250 | 142 | 0 | 0 | 3 (0) | Änderungen gefunden `verify-differ` | [156](https://github.com/lexifina/switzerland-schaffhausen-law/compare/b03698d86c5e...068ce39274a3) |
| [2026-11-24 15:00](checks/2026-11.md#ch-lexwork-schaffhausen-20261124t150051z) | lexwork-schaffhausen | 186 | 142 | 0 | 0 | 143 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-24 12:19](checks/2026-11.md#ch-lexwork-schaffhausen-20261124t121950z) | lexwork-schaffhausen | 340 | 142 | 0 | 0 | 143 (0) | die Prüfung ist fehlgeschlagen | — |

## Selbst prüfen

```
python tools/checktrail.py                      # die letzte Prüfung jeder Quelle
python tools/checktrail.py --day 2026-11-23     # jede Prüfung eines Tages
python tools/checktrail.py --act <id>           # wann eine Vorschrift gesehen und veröffentlicht wurde
git log --grep='^Kind: check' --format='%ci %s'  # die Prüfungen in der Historie
```

Rechtskraft hat nur die amtliche Verkündung; die Texte hier sind Kopien zum Lesen und Suchen.
