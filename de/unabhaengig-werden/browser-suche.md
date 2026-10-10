---
layout: page
lang: de
title: Browser &amp; Suche
translations:
  en: /en/become-independent/browser-search/
---

# Browser &amp; Suche: Der erste Schritt zur Selbstbestimmung

<p class="lead">Der Browser ist dein Fenster zur Welt — und die Suche deine Landkarte. Wer beide kontrolliert, kontrolliert, was du siehst. Drei Schritte, keine Dogmatik.</p>

## Browser

**Empfehlung: Firefox oder ein Firefox-Derivat (LibreWolf).** Warum? Unabhängige Engine (Gecko, nicht Chromium), konfigurierbarer Tracking-Schutz, Container-Tabs für Identitätstrennung. Chrome ist der Marktanteils-König — und ein Google-Produkt.

| Browser | Engine | Google-frei | Tracking-Schutz |
|---|---|---|---|
| Firefox | Gecko | Ja | Verbessert (ETP, Total Cookie Protection) |
| LibreWolf | Gecko | Ja | Hart (kein Telemetrie, Fingerprints widerstehen) |
| Brave | Chromium | Ja (aber Chromia-Ökosystem) | Hart |
| Chrome | Chromium | **Nein** | Werbung: „privat" — Praxis: Google-Datenverknüpfung |

**Schritte:**

1. Firefox installieren; als Standard setzen.
2. `about:config` → `privacy.resistFingerprinting` aktivieren für hartes Setup (kostet manche Website-Komfort).
3. Erweiterungen: uBlock Origin (Werbung + Tracking), optional ClearURLs (Track-Parameter raus).

## Suche

**Empfehlung: Startpage oder SearXNG.** Startpage liefert Google-Ergebnisse, ohne deine IP/Suchhistorie an Google zu senden. SearXNG ist selbst hostbar und aggregiert viele Quellen. DuckDuckGo ist der Mittelweg (Microsoft-Bing-Ergebnisse, weniger Datensammeln als Google, aber nicht tracking-frei).

**Nische:** Mojeek (eigener Index, UK) — weniger gute Ergebnisse, aber echter Alternativ-Index. Das ist der eigentliche Punkt: Die Frage ist nicht nur „Welche Daten sammelt die Suche?", sondern „Wessen Index?" Nur wer einen eigenen Index hat, ist wirklich unabhängig von Google/Bing.

## Lügen ausräumen

**Falsch:** „Chrome im Inkognito-Modus ist privat." — Inkognito versteckt deine Historie vor anderen Nutzern desselben Geräts, nicht vor Google, dem Website-Betreiber oder dem ISP.

**Falsch auch:** „DuckDuckGo ist totally tracking-frei." — DDG speichert keine Suchhistorie, aber Bing-Ergebnisse kommen über Microsoft, und der DDG-Browser hatte 2022 einen Microsoft-Tracking-Skandal (Browser-Verträge mit Redmond). Es ist ein Kompromiss, kein Ausweg.

## Quellen

1. [EFF: Panopticlick](https://coveryourtracks.eff.org/) — Teste deinen Browser-Fingerprint
2. [Mozilla: Firefox-Datenschutzhinweise](https://www.mozilla.org/de/privacy/firefox/)
3. [Startpage: How it works](https://www.startpage.com/en/how-startpage-works.html)
