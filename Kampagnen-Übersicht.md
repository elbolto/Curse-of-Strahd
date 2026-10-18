---
typ: übersicht
tags:
  - übersicht
---
# 🦇 Curse of Strahd

> [!danger] Wo wir gerade stehen (Ende S04, 18.10.2026)
> Wir haben [[Irena]] im [[Herrenhaus des Bürgermeisters|Herrenhaus]] gefunden. Bevor sie mit nach [[Vallaki]] kommt, soll ihr Vater begraben werden. Narri, Aethren, der Charakter von Özgür und [[Ismark]] haben den Sarg zur [[Kirche von Barovia|Kirche]] gebracht. Priester [[Donawitsch]] hat dort seinen Sohn im Keller eingesperrt. Wir sind gerade **in die Krypta hinabgestiegen**, und in der Ecke kauert eine **ausgemergelte Gestalt**. Der Rest der Gruppe ist **mit Irena** vom Herrenhaus aus unterwegs zur Kirche.
>
> ⚠️ **Stimmung in der Gruppe:** angespannt. [[Helena Aldric - Anna|Helenas]] Dark Gift ist erwacht, und der Streit darüber, ob wir ihr trauen können, ist nur vertagt.

## 🎯 Aktive Quests
- [[Den Bürgermeister begraben]]: für [[Irena]]. Der Sarg ist in der Kirche, Donawitsch soll bestatten.
- [[Irena nach Vallaki bringen]]: für [[Ismark]]. Irena wurde von Strahd zweimal gebissen.
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
| 4 | 18.10.2026 | [[S04 – 2026-10-18 – Ein Auftrag von Ismark\|Ein Auftrag von Ismark]] | Ismarks Auftrag, Zombiekampf, Helenas Dark Gift, Herrenhaus, Kirche und Krypta |
| 3 | 04.10.2026 | [[S03 – 2026-10-04 – Abschluss im Durst-Haus\|Abschluss im Durst-Haus]] | Kampf gegen Walter (Fleischmonster), Aethren sieht Strahd |
| 2 | 20.09.2026 | [[S02 – 2026-09-20 – Die Geister der Durst-Kinder\|Die Geister der Durst-Kinder]] | Geister-Companions, Altar im Keller |
| 1 | 31.08.2026 | [[S01 – 2026-08-31 – Das Durst-Haus\|Das Durst-Haus]] | Ankunft in Barovia, Strahds Brief |

## 🧙 Die Gruppe
| Charakter                                   | Spieler | Kurz                                              |
| ------------------------------------------- | ------- | ------------------------------------------------- |
| [[Narri - Elbolto\|Narri]]                  | Elbolto | Aasimar-Grabkleriker, sucht seinen Glauben        |
| [[Aethren - René\|Aethren]]                 | René    | Hochelf mit goldener Maske, Pakt mit einer Göttin |
| [[Herr Guphry - Castor\|Herr Guphry]]       | Castor  | Viktorianischer Schnösel, geldgeil                |
| [[Helena Aldric - Anna\|Helena Aldric]]     | Anna    | Junge Dame, groß und mager, ⚠️ Dark Gift, [[Magischer Mantel\|mag. Mantel]] |
| [[Charakter von Sophia\|*noch ohne Namen*]] | Sophia  | Riesige Gestalt mit Hellebarde                    |
| [[Charakter von Özgür\|*noch ohne Namen*]]  | Özgür   | Wild, weiß-grünes Haar, „scheint anders“          |

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
- Wer ist die Gestalt in der Krypta, und was ist mit [[Sohn von Donawitsch|Donawitschs Sohn]] los?
- Welchen Trick nutzt [[Strahd]], um Häuser zu betreten?
- Was passiert mit [[Irena]] nach Strahds Bissen?
- Was ist Helenas Dark Gift?
- Was steht im [[Brief mit D-Siegel]]?
- Wer oder was sind die [[Priester von Osybus]]?
- Wo ist die Windmühle der [[Familie Durst]]? → [[Windmühlen-Symbol]]

## 🗺️ Schnellzugriff
**Orte:** [[Barovia]] · [[Durst-Haus]] · [[Taverne in Barovia]] · [[Bildraths Laden]] · [[Herrenhaus des Bürgermeisters]] · [[Kirche von Barovia]] · [[Vallaki]]
**Lore:** [[Morgenfürst und Mutter Nacht]] · [[Priester von Osybus]]
**Hinweise:** [[Brief von Strahd an seinen Diener]] · [[Brief von Klara]] · [[Notiz von Elisabeth an Drasha]] · [[Bernsteinsplitter]] · [[Magischer Mantel]] · [[Testament der Familie Durst]]
