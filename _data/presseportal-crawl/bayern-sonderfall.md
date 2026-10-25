# Bayern-Sonderfall im presseportal-Crawl

## Befund

Von 286 kirchen-relevanten Polizeipressemitteilungen (2020–2026, 6 Suchbegriffe) stammen nur **10 aus Bayern** — trotz 13,1 Mio. Einwohnern (größtes Flächenland nach NRW). NRW (17,9 Mio.) lieferte 83 PMs.

## Ursache (verifiziert)

1. **Bayerns Polizei publiziert auf eigenem Kanal:** pressestelle.polizei.bayern.de + PD-Websites + ots direkt an Lokalredaktionen. Presseportal listet Bayern-Dienststellen (ds 6xxx: PP Mittelfranken 6013 mit 914 News 2026), aber die Kirchen-/Opferstock-Fälle erreichen presseportal nur in Ausnahmen.
2. **Beispiel:** Die Schwachkopf-Fälle 2024 (Habeck-Memes) und Opferstock-Serien (Grafing, Dettelbach, Gutenstetten, Senden, Lindenberg, Sorghof — alle Jan./Feb. 2024) stehen bei katholisch.de/OIDAC mit Lokalquellen (rosenheim24, mainpost, fraenkischer), aber NICHT im presseportal-Feed.
3. **Konsequenz für die Vollzählung:** Die bayerische Zahl ist im Crawl um einen Faktor ~5–10 unterschätzt. Bayern-PMs müssen aus der Eigen-Pressestelle gecrawlt werden (pressestelle.polizei.bayern.de/meldungen) — eigener Crawler-Abschnitt.

## Korrektur der regionalen Verteilung

Ohne die Bayern-Untererfassung wäre die Verteilung realistischer:
- NRW 83 (29 %), BW 59 (21 %), RP 44 (15 %), HE 32 (11 %), NI 29 (10 %)
- Bayern real: geschätzt 30–60 PMs (wie NRW/BW — nicht gemessen, aus der oidac_de_2024_full.json: Bayern ist unter den Top-3-Ländern für christenfeindliche PMK)

Die West/Süd-Konzentration (75 %) ist also teilweise ein **Publikations-Artefakt**: Wo Polizei auf presseportal publiziert, wird gezählt. Wo nicht (Bayern, teilweise Berlin/Brandenburg), bleibt sie unsichtbar — genau die Erfassungs-Lücke, die das Wiki dokumentiert.

## Lösung für künftige Crawls

Stufe 1 erweitern um:
- pressestelle.polizei.bayern.de (eigener Feed, RSS vorhanden)
- polizei-beratung.de (BY/BB Gemeinschaftsportal)
- lka.bayern.de (Lagebilder)

Danach: Bayern im Index-Crawl als eigener Zweig, dann ist die Bundes-Verteilung vollständiger.
