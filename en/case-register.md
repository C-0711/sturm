---
layout: page
lang: en
title: Case Register — Church Incidents 2024–2026
translations:
  de: /de/fallregister/
---

# Case Register: Church Incidents 2024–2026

<p class="lead">A case register verified by 9 parallel research tracks: 840 documented incidents at churches and Christian sites across 11 countries (2024–2026) — every line with date, location, offence type, motive status, source and source class. Raw data public, recomputable.</p>

<div class="meta-line"><span class="tag">Scope</span> 840 cases · 11 countries <span class="tag">Base</span> OIDAC + police + local press <span class="tag red">Standard</span> Every case with source · raw data as JSON</div>

## Methodology

This register was built on 24 Oct 2026 by **9 parallel research tracks** (8 regions, UK restarted after a fix):

1. **OIDAC incident database read directly** — all entries per country (Germany 139 cases 2024, France 60, Southern Europe 454, UK/Ireland complete via country filter) — and **individually verified**
2. **Police press releases** screened (presseportal.de, state police services, police.uk, berlin.de, medienservice.sachsen.de …)
3. **Local/regional press** as a second filter per region (all 16 German states, French départements, Spanish/Italian/Austrian/Swiss regions, British regional press)
4. **Cross-check of official balances** (BMI-PMK, French Interior Ministry, OPR/Sénat) against the case counts
5. **Date check on every case** — several cases circulating virally turned out to be from 2018–2020 or 2026 and were excluded

**Source classes:** `PRIMARY` = police/court/authority · `WATCHDOG` = OIDAC/OPR/christianophobie.fr · `INDICATION` = local press (upgradeable)

## The numbers at a glance

| Region | Verified cases | of which in OIDAC register | PRIMARY sources | INDICATION |
|---|---|---|---|---|
| Germany 2024 (16 states) | ~118 | 139 screened | 55 | 68 |
| France 2024 | ~81 | 62 | 2 | 75 |
| France 2025–26 | ~72 | 56 | 7 | 21 |
| Southern Europe (ES/PT/IT/AT/CH) | ~508 | 454 | 3 | 47 |
| UK & Ireland 2024–26 | 61 | 60 | 36 | 30 |
| **Total** | **~840** | **697** | **103** | **241** |

## The five main findings

### 1. The OIDAC list is solid — but not complete and not error-free

Of 139 German OIDAC cases 2024, samples were individually verified against police and local sources — **confirmed at the core**, with documented errors:

- **Dating error:** case "Weihenlinden" dated by OIDAC as 12 Jan 2024 — the police press release shows 29 Dec 2023
- **Country mis-tagging:** case 9117 "Withington" tagged as Ireland — it is in Herefordshire/England · case 9451 (Limavady) is Northern Ireland/UK, not Ireland
- **Case 9124 "Tunbridge, Wales"** comes, per the source article, from Tunbridge/Vermont/**USA** — not included
- **Press gap of ~50 %** for small attempted arsons (especially in overseas départements: only christianophobie.fr documents them)

### 2. The real Germany number sits between the poles

The official PMK statistics count **0–2** church arsons for 2024 (motive definition gap), OIDAC counts **33**. Verification shows: the 33 include series and dangerous small fires; the real number sits **between both poles**. Moreover, the research found **cases missing from OIDAC** (e.g. Dormagen 14–16 Jan 2024, 2× church break-in, police PR; Zülpich 4 Mar 2024, arson in a chapel, police PR).

### 3. Damage sums escalate faster than case counts

Baden-Württemberg (state parliament document 17/9782, PRIMARY): offences in church facilities fell 1,287 (2023) → 1,128 (2024), **but the damage sum tripled to €1.2m** — theft pattern: fewer, larger, more organised acts.

### 4. Motives are almost universally undetermined by police

In the UK register (61 cases): documented motives in only 3 cases (New Forest/court, Leyland/hate crime, Swansea/far-right symbols). France the same: "motive open" dominates massively. **The motive openness is itself the scandal** — it makes statistical "anti-Christian" numbers a lower bound.

### 5. Viral recycling of old cases as "current"

Excluded from the register (with evidence): Heiligenhafen (2018), Golzwarden (2019), Reinberg (2020), Mühlhausen/Divi-Blasii (2023) — circulating on social media as "church fires 2024". **And the opposite direction:** "Bringolo as an attack" was, per an expert assessment, an **accident**.

## The gravest individual cases (selection, all sourced in the register)

| Date | Location | Offence | Source class |
|---|---|---|---|
| 09 Nov 2024 | Gilet (Valencia, ES), Monasterio Espíritu Santo | **Monk (76) dead**, 7 injured | INDICATION (El Mundo) + OIDAC |
| 26–29 May 2024 | Leipzig-Mockau (DE), Stephanuskirche | Organ looted, **>€100,000** | PRIMARY (PD Leipzig 257/24) + OIDAC |
| 02 Jan 2024 | Cologne Cathedral | Bomb attack plan, 5 arrests (thwarted) | OIDAC + press |
| 19 Dec 2024 | Elche (ES), Basilica of Santa María | Islamist attack thwarted, 4 teens arrested | INDICATION + OIDAC |
| 14 May 2024 | Poitiers (FR), Ste-Thérèse | Pews set on fire + Mary beheaded; migrant rumour debunked | INDICATION+WATCHDOG |
| 03 May 2024 | Cuenca (ES), convent | Arson; perpetrator sentenced to 5 years; "migrant" hoax debunked | INDICATION (verdict) |

## Raw data & recomputability

All raw data is public in this repository:

- `_data/oidac-fallregister/oidac_de_2024_full.json` — Germany 2024, 139 OIDAC cases (machine-extracted)
- `_data/oidac-fallregister/oidac_france_2024_full.json` — France 2024
- `_data/oidac-fallregister/oidac_faelle_suedeuropa_2024_2026.json` — ES/PT/IT/AT/CH, 454 cases
- `quellen/fallregister/*.md` — the 7 regional registers in full (with exclusion lists, statistics blocks, all URLs)

Whoever doubts a number on this page: the JSONs contain case ID, date, location, source URL — every line is a verification instruction.

## Open questions

- The state-level gaps: how many church offences 2024/2025 in the 16 German states (all motives)? Only obtainable via 16 state parliament inquiries — Baden-Württemberg (document 17/9782) shows the data exists. **Inquiry template for contributors wanted.**
- Portugal: why are police bias motives not recorded? (10 OIDAC cases total, 6 property offences — below any plausibility threshold)
- How many of the "undetermined motives" would be "anti-Christian" if consistently pursued? Either would be speculation — only the openness itself is documented.

---

*This register is a working tool, not truth itself: it lists what is documented — and shows where documentation is missing. Additions and corrections via pull request, with source.*
