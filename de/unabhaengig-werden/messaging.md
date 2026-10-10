---
layout: page
lang: de
title: Messaging — Signal statt WhatsApp
translations:
  en: /en/become-independent/messaging/
---

# Messaging: Ende-zu-Ende statt Datenkrake

<p class="lead">Deine Nachrichten gehören dir — oder dem Anbieter. Der Unterschied liegt in der Architektur. Konkrete Schritte, ohne Panikmache.</p>

## Die Entscheidung: Was ist dein Bedrohungsmodell?

- **Alltagskommunikation (Familie, Freunde, Kolleg:innen):** Ende-zu-Ende-Verschlüsselung als Standard, offener Code, keine Telefonnummer-Zwang mehr als nötig.
- **Sensibles (Berufliches, Journalist:innenquellen):** Metadaten minimieren (wer mit wem wann), ggf. verschwindende Nachrichten, eigene Server für höchste Ansprüche.
- **Maximum (Aktivist:innen, Whistleblower):** Tails/QubesOS-Setup, Session-Code, keine Telefonnummer.

## Die Empfehlung (belegbar)

| Kriterium | WhatsApp | Signal | Telegram | Olvid |
|---|---|---|---|---|
| Ende-zu-Ende standard | Ja (aber Signal-Protokoll) | Ja | **Nein** (nur „geheime Chats") | Ja |
| Offener Client-Code | Teilweise | Ja | Teilweise | Ja |
| Metadaten sammeln | Ja (Facebook/Meta) | Minimal | Ja | Minimal |
| Telefonnummer-Zwang | Ja | Ja (Usernames seit 2024 optional für Chats, nicht fürs Icon) | Nein | Nein (IDs) |
| Staatlich zertifiziert | Nein | Nein | Nein | Ja (ANSSI, Frankreich) |

**Kernempfehlung für die meisten:** Signal. Es ist der konservative Wahl für E2EE + offener Code + minimale Metadaten. Der Beweis: Selbst die französische Regierung, die ihren Mitgliedern Olvid verordnet (Zirkular 6428/SG), räumt Signal technisch nichts vor — sie argumentiert mit Souveränität (siehe [Olvid-Dossier](/de/faelle/olvid-push/)).

**Für Wenig-Sync-Verweigerer:** Matrix/Element (dezentral, selbst hostbar), SimpleX Chat (keine Telefonnummer, keine zentrale Identität).

## Schritte

1. Signal installieren, Username statt Telefonnummer teilen, „Verschwindende Nachrichten" für sensible Chats.
2. Gruppen aus WhatsApp schrittweise migrieren — jede:r Einzelne entscheidet selbst.
3. Backups: Lokale verschlüsselte Backups statt Cloud-Backups von WhatsApp/Apple/Google.
4. Für Journalist:innen: SecureDrop oder Signal für Quellenschutz; Session-Codes nicht in „Meta"-Clouds sichern.

## Was du NICHT tun solltest

- Nicht von einer Datenkrake (WhatsApp) zur nächsten (Telegram-Cloud-Chats sind serverseitig lesbar) wechseln und glauben, du seiest jetzt frei.
- Kein „verbrannte-Erde"-Drama: Ein Dienst ist ein Werkzeug, kein Eheversprechen. Wenn ein anderes Werkzeug besser wird, wechsle wieder.

## Lügen ausräumen

**Falsch:** „Signal ist eine CIA-Trojaner." — Die Behauptung zirkuliert seit Signal die Signal-Protokoll-Referenzimplementierung für die US-Regierung freigab (Open Technology Fund-Förderung). Beleg für eine Hintertür: keiner. Was belegt ist: Signal ist Ende-zu-Ende, der Code ist offen, unabhängige Audits existieren. Wer mehr behauptet, braucht Belege.

**Falsch auch:** „Telegram ist sicher, weil es ‚geheime Chats' hat." — Standard-Chats auf Telegram liegen **unverschlüsselt** in der Cloud (serverseitig lesbar). „Secret Chats" sind die Ausnahme, nicht der Standard.

## Quellen

1. Signal-Dokumentation: [signal.org/docs](https://signal.org/docs/)
2. [Olvid-Dossier](/de/faelle/olvid-push/) — inkl. Vergleich Signal vs. staatliche Zertifizierung
3. EFF Surveillance Self-Defense: [ssd.eff.org](https://ssd.eff.org/)
