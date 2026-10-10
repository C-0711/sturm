---
layout: page
lang: en
title: Messaging
translations:
  de: /de/unabhaengig-werden/messaging/
---

# Messaging: end-to-end instead of datakrake

<p class="lead">Your messages belong to you — or to the provider. The difference is architecture. Concrete steps, no fearmongering.</p>

## What is your threat model?

- **Everyday (family, friends, colleagues):** end-to-end encryption by default, open code, minimal data collection.
- **Sensitive (work, journalistic sources):** minimise metadata, disappearing messages, own servers for the highest bar.
- **Maximum (activists, whistleblowers):** Tails/QubesOS setups, no phone number.

## The comparison (evidenced)

| Criterion | WhatsApp | Signal | Telegram | Olvid |
|---|---|---|---|---|
| E2EE by default | Yes | Yes | **No** (secret chats only) | Yes |
| Open client code | Partial | Yes | Partial | Yes |
| Metadata collection | Yes (Meta) | Minimal | Yes | Minimal |
| State-certified | No | No | No | Yes (ANSSI, France) |

**Core recommendation for most:** Signal — the conservative choice for E2EE + open code + minimal metadata. Even the French government's Olvid circular (6428/SG) doesn't claim Signal is technically weaker; it argues sovereignty (see [the Olvid dossier](/en/cases/france-olvid-push/)).

**For decentralists:** Matrix/Element (self-hostable), SimpleX Chat (no phone number, no central identity).

## Steps

1. Install Signal; share username rather than phone number; enable disappearing messages for sensitive chats.
2. Migrate WhatsApp groups step by step — everyone decides for themselves.
3. Backups: local encrypted, not cloud backups.
4. Journalists: SecureDrop or Signal for sources.

## Debunking

**False:** "Signal is a CIA Trojan." — The claim circulates because Signal's protocol work received US funding (OTF). Evidence of a backdoor: none. Evidence: E2EE, open code, independent audits.

**Also false:** "Telegram is secure because it has secret chats." — Standard Telegram chats sit **unencrypted** on servers. Secret chats are the exception, not the default.

## Sources
1. [Signal docs](https://signal.org/docs/)
2. [EFF Surveillance Self-Defense](https://ssd.eff.org/)
