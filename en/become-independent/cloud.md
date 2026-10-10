---
layout: page
lang: en
title: Cloud &amp; services
translations:
  de: /de/unabhaengig-werden/cloud/
---

# Cloud &amp; services: take your data out of the rental

<p class="lead">Nextcloud instead of Dropbox, Bitwarden instead of cloud-only password safes, KeePassXC locally. Where self-hosting pays — and where it's overkill.</p>

## The ladder of cloud independence

**Level 0 (rental):** Dropbox, Google Drive, iCloud — convenient, provider holds the keys (unless you encrypt client-side with Cryptomator first).

**Level 1 (encrypted rental):** Cryptomator or rclone+crypt in front of any cloud. Provider sees ciphertext only.

**Level 2 (self-hosted):** Nextcloud on your own server/NAS. You hold keys AND infrastructure. Cost: maintenance.

**Level 3 (community):** co-op clouds, Disroot etc. A compromise between self-hosting and commercial.

| Use | Recommendation |
|---|---|
| Files | Nextcloud (self) or Cryptomator + any cloud |
| Passwords | KeePassXC (local) or Bitwarden (self-hosted Vaultwarden) |
| Calendar/contacts | Nextcloud (CalDAV/CardDAV) |
| Photos | Immich (self) or encrypted sync |
| Notes | Joplin or local Markdown |
| AI assistants | Local models (LM Studio, Ollama) — no chat logs with third parties |

## Debunking

**False:** "Everyone should self-host." — No. A misconfigured server is worse than Dropbox: it also holds your data, but you're responsible for security patches. Don't want to patch? Rent encrypted.

**Also false:** "My cloud is encrypted, so all is well." — Client-side encrypted? Good. "Encrypted" in the marketing sense (server-side, provider-held keys)? Then the provider — and anyone with jurisdiction over them — can read along.

## Sources
1. [Nextcloud](https://nextcloud.com/) · [Cryptomator](https://cryptomator.org/) · [KeePassXC](https://keepassxc.org/)
