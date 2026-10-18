---
typ: übersicht
tags:
  - übersicht
---
# 🦇 Curse of Strahd

> [!danger] Wo wir gerade stehen (nach S04, 18.10.2026)
> Wir sind in [[Barovia]] und haben gerade zwei Aufträge angenommen: [[Irena]] nach [[Vallaki]] bringen und [[Gertruda]] suchen. Auf dem Weg hörten wir einen Schrei aus einem Haus. Drinnen wurden wir **von Zombies überrascht**. *Die nächste Session beginnt mitten im Kampf.*

## 🎯 Aktive Quests
- [[Irena nach Vallaki bringen]]: für [[Ismark]]. Irena wurde von Strahd gebissen.
- [[Gertruda finden]]: für die [[Irre Marie]]. Gertruda ist 14 und verschwunden.

```base
filters:
  and:
    - file.inFolder("04 Quests")
views:
  - type: table
    name: Alle Quests
    order:
      - file.name
      - status
      - auftraggeber
      - start
```

## 📜 Sessions
| # | Datum | Session | Kurz |
|---|---|---|---|
| 4 | 18.10.2026 | [[S04 – 2026-10-18 – Ein Auftrag von Ismark\|Ein Auftrag von Ismark]] | Ismarks Auftrag, Irre Marie, Zombieangriff |
| 3 | 04.10.2026 | [[S03 – 2026-10-04 – Abschluss im Durst-Haus\|Abschluss im Durst-Haus]] | Tutorial beendet, Aethren sieht Strahd |
| 2 | 20.09.2026 | [[S02 – 2026-09-20 – Die Geister der Durst-Kinder\|Die Geister der Durst-Kinder]] | Geister-Companions, Altar im Keller |
| 1 | 31.08.2026 | [[S01 – 2026-08-31 – Das Durst-Haus\|Das Durst-Haus]] | Ankunft in Barovia, Strahds Brief |

## 🧙 Die Gruppe
| Charakter | Spieler | Kurz |
|---|---|---|
| [[Narri - Elbolto\|Narri]] | Elbolto | Aasimar-Grabkleriker, sucht seinen Glauben |
| [[Aethren - René\|Aethren]] | René | Hochelf mit goldener Maske, Pakt mit einer Göttin |
| [[Herr Guphry - Castor\|Herr Guphry]] | Castor | Viktorianischer Schnösel, geldgeil |
| [[Helena Aldric - Anna\|Helena Aldric]] | Anna | Junge Dame, groß und mager |
| [[Sophia]] | ? | Riesige Gestalt mit Hellebarde |
| [[Özgür]] | ? | Wild, weiß-grünes Haar, „scheint anders“ |

Dazu kommen **die Geister der beiden Durst-Kinder** als Companions (seit S02).

## 👥 Wichtige NPCs
```base
filters:
  and:
    - file.inFolder("02 Charaktere/NPCs")
views:
  - type: table
    name: NPCs
    order:
      - file.name
      - status
      - beziehung
      - ort
      - erstes_auftreten
```

## ❓ Große offene Fragen
- Was passiert mit [[Irena]] nach Strahds Biss?
- Was steht im [[Brief mit D-Siegel]]?
- Wer oder was sind die [[Priester von Osybus]]?
- Wo ist die Windmühle der [[Familie Durst]]? → [[Windmühlen-Symbol]]

## 🗺️ Schnellzugriff
**Orte:** [[Barovia]] · [[Durst-Haus]] · [[Taverne in Barovia]] · [[Bildraths Laden]] · [[Vallaki]]
**Hinweise:** [[Brief von Strahd an seinen Diener]] · [[Brief von Klara]] · [[Notiz von Elisabeth an Drasha]] · [[Bernsteinsplitter]] · [[Testament der Familie Durst]]
