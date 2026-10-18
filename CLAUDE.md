# Arbeitsregeln für diesen Vault

Obsidian-Vault für eine **Curse of Strahd**-Kampagne. Der Nutzer (Elbolto) ist **Spieler**, nicht DM, und spielt [[Narri - Elbolto|Narri]], einen Aasimar-Grabkleriker. Alle Notizen sind auf Deutsch.

## Auslöser: „Inbox verarbeiten“
Wenn der Nutzer das (oder Ähnliches) schreibt:
1. Alle Notizen in `00 Inbox/` lesen (außer `Hier reinschreiben.md`). Falls der Nutzer Notizen woanders abgelegt hat, sind auch neue oder geänderte Dateien außerhalb der Struktur gemeint (`git status` prüfen).
2. **Session-Notiz** in `01 Sessions/` nach `_Vorlagen/Session.md` anlegen oder ergänzen:
   - Dateiname: `SNN – JJJJ-MM-TT – Kurzer Titel.md` (Nummer fortlaufend, Datum = Spieltag)
   - TL;DR in 2–3 Sätzen, Ablauf ausformuliert und nach Szenen gegliedert, „Neu kennengelernt“, Quests (🆕/🔄/✅), offene Fragen
   - Rohtext **unverändert** in `> [!abstract]- Originalnotizen` am Ende
3. Für jede neue Person, jeden Ort, jede Quest und jeden wichtigen Gegenstand oder Hinweis eine Notiz nach Vorlage anlegen. Bestehende Notizen ergänzen („Was wir wissen“, „Auftritte“, Status in den Properties).
4. Alle Erwähnungen verlinken. Session-Links mit Alias: `[[S04 – 2026-10-18 – Ein Auftrag von Ismark|S04]]`.
5. `Kampagnen-Übersicht.md` aktualisieren: „Wo wir gerade stehen“, aktive Quests, Session-Tabelle, große offene Fragen.
6. Verarbeitete Inbox-Notizen löschen. Der Rohtext steckt in der Session-Notiz, und git hat die Historie.
7. Prüfen, dass keine Links ins Leere zeigen. Dann committen und zu GitHub pushen (vom Nutzer so gewünscht).
8. Dem Nutzer kurz berichten: was neu ist, welche Rückfragen offen sind (Widersprüche, unklare Namen).

## Inhaltliche Regeln
- **Keine Spoiler aus dem offiziellen Abenteuer.** Nur verwenden, was die Gruppe selbst erlebt hat. Kein Modulwissen ergänzen, auch nicht als Vermutung.
- **Nichts erfinden.** Ausformulieren ja, neue Fakten nein. Eigene Schlussfolgerungen nur aus Spielerwissen und immer als `> [!question] Vermutung (nicht bestätigt)` markieren.
- Unklare Stellen im Rohtext (z. B. ein unverständliches Wort) wörtlich nennen und als offene Frage aufnehmen, statt sie zu raten.
- **Charakter-Backstorys** (v. a. Narri) nicht umschreiben, nur gliedern. Der Originaltext bleibt erhalten.
- Schreibweisen vereinheitlichen und die abweichende Variante als `aliases` eintragen (z. B. Barovia/Borovia, Ismark/Issmark).
- Feste Schreibweisen: **Strahd von Zarovich** (nie „Zarowitsch“), **Barovia**, **Ismark**.
- Gertruda ist **14** (vom Nutzer bestätigt).
- Spielercharaktere heißen `Charaktername - Spieler.md`. Solange ein Charakter keinen Namen hat: `Charakter von <Spieler>.md` (derzeit Sophia und Özgür). Sobald der Name bekannt ist, umbenennen, Property `charaktername` setzen und die Übersicht anpassen.
- Eine Inbox-Notiz kann eine laufende Session fortsetzen (z. B. „sind immer noch in Session 4“). Dann die bestehende Session-Notiz ergänzen und den Rohtext an ihre Originalnotizen anhängen.
- Briefe und Dokumente bekommen eine eigene Notiz in `05 Gegenstände & Hinweise/` mit dem Text in einem `> [!quote]`-Callout.
- Perspektive: „wir“ = die Gruppe. „Ich“ im Rohtext = Narri.

## Struktur
| Ordner | Inhalt | Wichtige Properties |
|---|---|---|
| `00 Inbox/` | Rohnotizen des Nutzers | – |
| `01 Sessions/` | eine Notiz pro Spielabend | `typ: session`, `nummer`, `datum`, `tldr`, `orte`, `npcs`, `quests` |
| `02 Charaktere/Spielercharaktere/` | Gruppe (Narri mit Charakterbogen im Unterordner) | `typ: spielercharakter`, `spieler` |
| `02 Charaktere/NPCs/` | NPCs | `typ: npc`, `status` (lebendig/tot/untot/vermisst/unbekannt), `beziehung` (verbündet/neutral/feindlich/unbekannt), `ort`, `erstes_auftreten` |
| `03 Orte/<Region>/` | Orte, gruppiert nach Ortschaft | `typ: ort`, `region` |
| `04 Quests/` | eine Notiz pro Quest | `typ: quest`, `status` (offen/erledigt/gescheitert), `auftraggeber`, `start`, `ende` |
| `05 Gegenstände & Hinweise/` | Briefe, Dokumente, Items, Symbole | `typ: hinweis`/`gegenstand`, `gefunden_in`, `fundort`, `besitzer` |
| `06 Lore & Fraktionen/` | Fraktionen, Götter, Geschichte | `typ: fraktion`/`lore` |
| `_Vorlagen/` | Obsidian-Vorlagen | – |
| `_Anhänge/` | Bilder und PDFs | – |

Links in Properties immer in Anführungszeichen: `ort: "[[Barovia]]"`.

## Narris Charakterbogen
`02 Charaktere/Spielercharaktere/Narri/Narri.json` ist ein DiceCloud-V2-Archiv. Wenn der Nutzer einen neuen Export ablegt, den Abschnitt „Charakterbogen“ in Narris Notiz neu daraus erzeugen (Werte, Zauber, Ausrüstung, Geld, Stand-Datum).
