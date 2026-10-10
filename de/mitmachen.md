---
layout: page
lang: de
title: Mitmachen
translations:
  en: /en/contribute/
---

# Mitmachen: Freiwilligen-Pipeline

<p class="lead">STURM lebt von Contributor:innen. Ob du recherchierst, übersetzt, korrigierst oder nur einen Fehler meldest — hier ist der Weg rein.</p>

## Die vier Wege

### 1. Fehler melden (der schnellste Weg)
Du findest einen toten Link, eine falsche Zahl, ein übertriebenes Argument? [Issue öffnen](https://github.com/C-0711/sturm/issues) mit dem Titel „[FIX] <Artikel>". Belege dazu — wir korrigieren alles, was belegt ist.

### 2. Einen Fall beitragen
Das Herzstück. Du recherchierst einen Fall von Zensur, Sprachkontrolle, Überwachung — aus irgendeinem Land — und schreibst ein Dossier nach dem [Standard](https://github.com/C-0711/sturm/blob/main/CONTRIBUTING.md): Kurzfassung, Belege, Zeitleiste, Lügen ausräumen, offene Fragen, Quellen. PR gegen `main`. Maintainer prüfen auf Belegbarkeit; dann merge.

### 3. Übersetzen
Die Seite soll fünf Sprachen sprechen (DE, EN, FR, ES, PT). Wenn du eine Sprache gut beherrschst: Nimm einen englischen oder deutschen Artikel und übersetze ihn. Die Dateistruktur: `de/faelle/x.md` ↔ `en/cases/x.md` ↔ `fr/cas/x.md` ↔ `es/casos/x.md` ↔ `pt/casos/x.md`. PR mit beiden Dateien (Original-Link in front matter `translations:` nicht vergessen).

### 4. Diskutieren
Strittige Fälle, Priorisierung, neue Sektionen: [GitHub Discussions](https://github.com/C-0711/sturm/discussions). Dort wird entschieden, was als Nächstes gebaut wird.

## Der Standard eines STURM-Dossiers

```markdown
# <Titel>
<p class="lead">Ein Satz: Was ist passiert und warum ist es erschreckend.</p>
<div class="meta-line">...Land, Thema, Status...</div>
## Kurzfassung        — 3–5 Sätze, die einzeln belegbar sind
## Belege            — Links zu Primärquellen
## Zeitleiste        — datierte Fakten
## Lügen ausräumen   — korrigiert ÜBERTREIBUNGEN ALLER Seiten (auch der eigenen)
## Offene Fragen     — was unbelegt bleibt
## Quellen           — nummerierte Liste
```

**Wichtigste Regel:** Der Abschnitt „Lügen ausräumen" ist Pflicht. Ein Dossier, das nur eine Seite bestätigt, ist Propaganda, kein Dossier.

## Was wir NICHT wollen

- **Verschwörungstheorien ohne Beleg.** „Die Regierungen koordinieren mit den Medien ..." — zeig die E-Mails, den Gerichtsbeschluss, den Investigativ-Bericht. Ohne Beleg: nein.
- **Troll-Artikel.** Fälle, die nur der Provokation dienen, ohne Substanz.
- **Doxing.** Wir nennen keine Privatpersonen ohne öffentlichen Bezug (Ausnahme: öffentlich Urteilende wie Richter:innen in amtlicher Funktion).
- **Parteiwerbung.** STURM dokumentiert Zensur von links und rechts — konsequent.

## Co-Autoren-Guidelines

Wer mehr als drei Dossiers beigesteuert hat, kann Maintainer:in werden (Vorschlag im Maintainer-Kanal/Issue). Maintainer:innen mergen PRs, prüfen Belege und halten den Standard. Der Mastermind behält sich vor, Maintainer-Entscheidungen zu revidieren — hoffentlich nie.

## Rechtliches

- **Lizenz deiner Beiträge:** CC BY-SA 4.0 (siehe [Lizenz](/de/lizenz/)). Dein Text kann von anderen kopiert und weitergenutzt werden — mit Namensnennung der STURM-Community.
- **Keine vertraulichen Dokumente.** Wenn du im Besitz von geleakten Dokumenten bist: Wir sind kein Leak-Outlet. Wir arbeiten mit veröffentlichten Quellen.
