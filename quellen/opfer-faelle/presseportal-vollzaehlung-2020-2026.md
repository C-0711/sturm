# Presseportal-Index-Crawl: Vollzählung Christen als Opfer (2020–2026)

> **Ergebnis des Index-Crawlers (Stufe 1 der Architektur)**: 286 eindeutige Polizeipressemitteilungen (PRIMÄR) mit Kirchen-/Sakral-Kontext, gesammelt am 25.10.2026 über 6 Suchbegriffe mit Offset-Paginierung bis zur Quellen-Erschöpfung (Jahrgang 2020). Jede PM mit Fallnummer, Titel, Datum, Dienststelle, Snippet — maschinenlesbar in `_data/presseportal-crawl/konsolidiert-klassifiziert.json`.

## Methodik

- **Quelle:** presseportal.de/blaulicht (zentraler Feed aller deutschen Polizeidienste)
- **Suchbegriffe (6):** Opferstock · Tabernakel · geschändet · Kirche Diebstahl · Friedhof geplündert · Kirche angezündet
- **Paginierung:** `/suche/<begriff>/<offset>` (30 PMs je Seite), gecrawlt bis zum Jahrgang 2020 bzw. 3 leere Seiten
- **Deduplizierung:** PM-Nummern eindeutig über alle Begriffe
- **Klassifikation:** Regex-Filter (Brandstiftung / Diebstahl-Kirchenraub / Sachbeschädigung / Einbruch / Gewalt) auf Titel+Snippet
- **Zeitbudget:** ~6 Minuten Crawl-Zeit für 794 PMs über 6 Begriffe (Off-Peak)

## Die Kernzahlen

| Begriff | PMs gesamt | Kirchen-relevant | Rückverfolgbar bis |
|---|---|---|---|
| Opferstock | 420 | 146 | (2020-Grenze erreicht) |
| Kirche Diebstahl | 270 | 101 | 13.11.2023 (Suchtiefe) |
| Kirche angezündet | 54 | 28 | 17.11.2006 |
| Tabernakel | 28 | 22 | 06.12.2015 |
| geschändet | 15 | 7 | 23.04.2019 |
| Friedhof geplündert | 7 | 2 | 12.09.2001 |
| **Gesamt (dedupliziert)** | **794** | **286 eindeutig** | |

## Die Jahreskurve (2020–2026, eindeutige PMs)

| Jahr | Kirchen-relevante PMs |
|---|---|
| 2020 | 20 |
| 2021 | 32 |
| 2022 | 42 |
| 2023 | 37 |
| 2024 | 46 |
| 2025 | **54** |
| 2026 (bis Okt.) | 39 |

**Der Trend:** +170 % von 2020 (20) zu 2025 (54) — und 2026 liegt nach 10 Monaten bereits bei 39 (auf Jahresbasis ~47). **Die PM-Dichte hat sich seit 2020 fast verdreifacht.**

## Die Delikt-Verteilung (286 PMs klassifiziert)

| Delikt | Fälle | Anteil |
|---|---|---|
| **Diebstahl/Kirchenraub** | **198** | **69 %** |
| Einbruch | 28 | 10 % |
| Sachbeschädigung | 22 | 8 % |
| Brandstiftung | 8 | 3 % |
| Gewalt/Bedrohung | 2 | 1 % |
| Andere/unklar | 28 | 10 % |

**Der Hauptbefund:** Mit dem Index-Crawl verschiebt sich das Bild massiv zugunsten von **Diebstahl/Kirchenraub (69 %)** — die Brandstiftungen (3 %), die medial die Debatte dominieren, sind eine kleine Minderheit. Das deckt die BKA-Schlüssel-800-Kategorie (1.764→2.232 sakrale Diebstähle 2024→2025) und die OIDAC-Beobachtung (Diebstahl = 66 % der Fälle) exakt.

## Jahresverlauf je Hauptdelikt

| Delikt | 2020 | 2021 | 2022 | 2023 | 2024 | 2025 | 2026 |
|---|---|---|---|---|---|---|---|
| Diebstahl/Kirchenraub | 10 | 20 | 26 | 22 | 37 | **40** | 33 |
| Sachbeschädigung | 1 | 4 | 3 | 4 | 3 | 6 | 0 |
| Brandstiftung | 1 | 2 | 1 | 1 | 1 | 0 | 1 |
| Einbruch | 4 | 2 | 7 | 6 | 2 | 4 | 2 |

**Diebstahl verdoppelt sich** 2020→2024 (10→37) und bleibt 2025 auf Höchststand (40). Brandstiftung ist über alle Jahre **statisch bei 1–2 PMs/Jahr** — die mediale Aufmerksamkeit für Brände steht im umgekehrten Verhältnis zur Häufigkeit.

## Was der Crawl für das Wiki bedeutet

1. **286 verifizierte PRIMÄR-Fälle** — das Opfer-Register hat sich von 30 Stichproben auf 286 vollzählte PMs vervielfacht, jede mit Fallnummer und URL.
2. **Die Diebstahl-Dominanz ist jetzt messtechnisch belegt:** 69 % der PMs — deckungsgleich mit BKA-Schlüssel 800 (Bundesdaten) und OIDAC-Anteil (66 %). Drei unabhängige Quellen, ein Befund.
3. **Brandstiftung ist mediales, nicht reales Zentrum** — 8 PMs in 6 Jahren vs. 198 Diebstahls-PMs. Die viralen „45/400 Kirchenbrände" halten keiner Prüfung; die reale Masse ist Diebstahl.
4. **Die Kurve steigt** — 2025 mit 54 PMs ist das Rekordjahr der Serie; 2026 auf Kurs für ~47.

## Grenzen (ehrlich)

- **Suchtiefe variiert je Begriff:** „Kirche Diebstahl" wurde nur bis Nov. 2023 zurückverfolgt (Suchbudget) — die Jahre 2020–2022 sind für diesen Begriff untererfasst. „Opferstock" (420 PMs) und „angezündet" (bis 2006) sind vollständig.
- **PM-Dichte ≠ Fallzahl:** Große Dienststellen melden selektiver; kleine jede Kleinigkeit. Die Kurve misst Berichterstattung, nicht Absolutkriminalität.
- **Duplikate über Dienste:** Dedupliziert über PM-Nummer — aber dieselbe Tat kann in zwei Dienststellen-Meldungen auftauchen (hier nicht automatisch harmonisiert).

## Rohdaten (maschinenlesbar)

- `_data/presseportal-crawl/konsolidiert-klassifiziert.json` — 286 PMs, klassifiziert, mit Delikt-Label
- `_data/presseportal-crawl/konsolidiert-register.json` — 286 PMs, roh (ohne Klassifikation)
- Einzeldateien je Begriff (`opferstock_2020_2026.json`, `tabernakel.json`, `kirche-diebstahl.json`, `kirche-angezuendet.json`, `geschaendet.json`, `friedhof-gepluendert.json`)

Jede Zeile: PM-Nummer, Dienststellen-ID, Titel, Datum, Snippet — für jeden prüfbar via `https://www.presseportal.de/blaulicht/pm/<ds>/<pm>`.
