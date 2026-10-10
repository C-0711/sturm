# Mitmachen — der Dossier-Standard

Danke, dass du beitragen willst. STURM lebt von Contributor:innen. Lies die vier Regeln in der [README](README.md) — besonders: **keine Zeile ohne Quelle.**

## Der Ablauf

1. **Issue öffnen** (optional, aber hilfreich): „Ich möchte den Fall X dokumentieren."
2. **Fork / Branch**: `git checkout -b fall/<slug>`
3. **Dossier schreiben** nach der Vorlage unten.
4. **PR gegen `main`** mit einer Kurzbegründung: Warum ist der Fall relevant für dieses Wiki?
5. Maintainer prüfen auf Belegbarkeit; dann wird gemerged.

## Die Dossier-Vorlage

```markdown
---
layout: page
lang: de            # oder en / fr / es / pt
title: <Titel>
translations:
  en: /en/cases/<slug>/   # wenn vorhanden
---

# <Titel>

<p class="lead">Ein Satz: Was ist passiert und warum ist es erschreckend.</p>

<div class="meta-line"><span class="tag">Land</span> ... <span class="tag">Thema</span> ... <span class="tag red">Status</span> ...</div>

## Kurzfassung
3–5 Sätze, die einzeln belegbar sind.

## Belege
Links zu Primärquellen (Gerichtsurteile, Behördendokumente, etablierte Recherchen).

## Zeitleiste
- **DD.MM.YYYY** — datiertes Faktum

## Lügen ausräumen
**Falsch:** „<Übertreibung, die über den Fall kursiert>." — <Korrektur mit Beleg>.
Diese Sektion korrigiert Übertreibungen ALLER Seiten — einschließlich der eigenen.

## Offene Fragen
Was unbelegt bleibt. Ehrlichkeit schlägt Vollständigkeit.

## Quellen
1. [Titel](URL) — Datum
```

## Wo stehen die Dateien?

```
de/faelle/<slug>.md      Fälle (deutsch)
en/cases/<slug>.md       Fälle (englisch)
de/usa/<slug>.md         USA-Artikel
de/laender/…             Staaten-Index
de/unabhaengig-werden/…  Leitfaden
fr/cas/… es/casos/… pt/casos/…   Übersetzungen
_data/                   Rohdaten (JSON) mit Quell-URLs
```

## Übersetzen

- Neue Sprache = gleiche Struktur, `translations:`-Map in beiden Dateien pflegen.
- Fachbegriffe im Zweifel original belassen (z. B. „Vereinsverbot", „SLAPP").
- Führende Anführungszeichen der Zielsprache verwenden.

## Was abgelehnt wird

- Behauptungen ohne Quelle („Man weiß doch, dass …").
- Doxing von Privatpersonen.
- Parteizeugs: Zensur wird von allen Seiten dokumentiert, konsequent.
- Ganztextkopien fremder Artikel — wir zitieren fair und verlinken.

## Co-Autorenschaft

Nach drei gemergten Dossiers kannst du Maintainer:in werden (Vorschlag im Issue). Maintainer:innen mergen, prüfen Belege, halten den Standard.

— Der Mastermind
