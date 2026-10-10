# Mitmachen — der Dossier-Standard

Danke, dass du beitragen willst. STURM lebt von Contributor:innen. Lies die vier Regeln in der [README](README.md) — besonders: **keine Zeile ohne Quelle.**

## Der Ablauf

1. **Issue öffnen** (optional, aber hilfreich): „Ich möchte den Fall X dokumentieren."
2. **Fork / Branch**: `git checkout -b fall/<slug>`
3. **Dossier schreiben** nach der Vorlage unten.
4. **PR gegen `main`** mit einer Kurzbegründung: Warum ist der Fall relevant für dieses Wiki?
5. Maintainer prüfen auf Belegbarkeit; dann wird gemerged.

## Die Dossier-Vorlage (mit Zitierweise wie in einer Doktorarbeit)

Zitate laufen über **kramdown-Fußnoten**: Im Text `[^1]`, am Ende die Definition `[^1]: Quelle...`. Der Renderer baut daraus automatisch hochgestellte Verweiszahlen und den Fußnotenblock „Fußnoten" am Seitenende. Damit jede Quelle im Fließtext steht UND das Quellenverzeichnis entsteht, ist die Fußnote selbst die vollständige Quellenangabe (Titel, Datum, URL, Abrufdatum).

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
3–5 Sätze, jede behauptungsrelevante Aussage mit Fußnote: `...verboten.[^1]`

## Belege
Links zu Primärquellen — im Text als Fußnoten[^2], hier zusätzlich als Liste mit Kommentar.

## Zeitleiste
- **DD.MM.YYYY** — datiertes Faktum[^1]

## Lügen ausräumen
**Falsch:** „<Übertreibung, die über den Fall kursiert>." — <Korrektur mit Beleg[^3]>.
Diese Sektion korrigiert Übertreibungen ALLER Seiten — einschließlich der eigenen.

## Offene Fragen
Was unbelegt bleibt. Ehrlichkeit schlägt Vollständigkeit.

## Quellenverzeichnis

[^1]: Autor/Institution: *Titel*, Ort/Datum. Online: <URL> (abgerufen TT.MM.JJJJ).
[^2]: ...
```

**Zitierregeln:**
- Fußnotennummerierung einfach `[^1]`, `[^2]`, ... je Artikel (kramdown nummeriert selbst).
- Vollständige Angabe: **Autor/Institution, Titel (kursiv), Datum, URL, Abrufdatum** — wie im Musterartikel [`de/faelle/compact-verbot.md`](de/faelle/compact-verbot.md).
- Jede Zahl, jedes Zitat, jedes datierte Faktum im Fließtext trägt eine Fußnote.
- Sekundärquellen nur, wenn Primärquellen fehlen — dann kenntlich machen („zitiert nach").

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
