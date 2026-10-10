---
layout: page
lang: en
title: Contribute
translations:
  de: /de/mitmachen/
---

# Contribute: the volunteer pipeline

<p class="lead">STURM lives from contributors. Research, translate, correct, or just report a bug — here's the way in.</p>

## The four paths

### 1. Report an error (fastest)
Dead link, wrong number, overstated argument? [Open an issue](https://github.com/C-0711/sturm/issues) titled "[FIX] <article>". Add evidence — we correct everything that's documented.

### 2. Contribute a case
The core. Research a censorship/surveillance case from any country and write a dossier following the [standard](https://github.com/C-0711/sturm/blob/main/CONTRIBUTING.md). PR against `main`. Maintainers check evidence, then merge.

### 3. Translate
The site aims at five languages (DE, EN, FR, ES, PT). File structure: `de/faelle/x.md` ↔ `en/cases/x.md` ↔ `fr/cas/x.md` ↔ `es/casos/x.md` ↔ `pt/casos/x.md`. PR with both files; don't forget the `translations:` front matter.

### 4. Discuss
Contested cases, priorities, new sections: [GitHub Discussions](https://github.com/C-0711/sturm/discussions).

## The STURM dossier standard

```markdown
# <Title>
<p class="lead">One sentence: what happened and why it's alarming.</p>
## Summary        — 3–5 sentences, each individually evidenced
## Evidence       — links to primary sources
## Timeline       — dated facts
## Debunking      — corrects oversimplifications on ALL sides (including our own)
## Open questions — what remains unevidenced
## Sources        — numbered list
```

**The key rule:** the "Debunking" section is mandatory. A dossier that only confirms one side is propaganda, not a dossier.

## What we don't want

- **Unevidenced conspiracy claims.** "Governments coordinate with media…" — show the emails, the court order, the investigative report. Without evidence: no.
- **Troll pieces** without substance.
- **Doxing** of private persons without public role (exception: officials acting in office).
- **Party advertising.** STURM documents censorship from left and right — consistently.

## Co-author guidelines

Three merged dossiers qualify you for maintainer status (propose in an issue). Maintainers merge PRs, check evidence, hold the standard. The Mastermind retains a final say — hopefully never needed.
