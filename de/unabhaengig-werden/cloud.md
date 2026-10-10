---
layout: page
lang: de
title: Cloud &amp; Dienste
translations:
  en: /en/become-independent/cloud/
---

# Cloud &amp; Dienste: Daten aus der Miete holen

<p class="lead">Nextcloud statt Dropbox, Bitwarden statt 1Password-Cloud, KeePassXC lokal. Wo Selber-Hosten lohnt — und wo es Overkill ist.</p>

## Die Stufen der Cloud-Unabhängigkeit

**Stufe 0 (Miete):** Dropbox, Google Drive, iCloud. Bequem, aber der Anbieter hat die Schlüssel (mit Ausnahme verschlüsselter Clients wie Cryptomator davor).

**Stufe 1 (Verschlüsselte Miete):** Cryptomator oder rclone+Crypt vor der Cloud. Bequem plus: Der Anbieter sieht nur Chiffre. Kosten: ein Setup-Schritt.

**Stufe 2 (Selbst hosten):** Nextcloud auf eigenem Server oder Heim-NAS. Du hast die Schlüssel UND die Infrastruktur. Kosten: Wartung.

**Stufe 3 (Community):** Vereins- oder Co-op-Clouds, z. B. die deutschen „Berglappe"-Anbieter oder Disroot. Kompromiss zwischen Selber-Hosten und Kommerz.

## Empfehlung nach Anwendungsfall

| Anwendung | Empfehlung | Grund |
|---|---|---|
| Dateien | Nextcloud (selbst) oder Cryptomator + beliebige Cloud | E2EE-Kontrolle |
| Passwörter | KeePassXC (lokal) oder Bitwarden (self-hosted Vaultwarden) | Kein Cloud-Zwang |
| Kalender/Kontakte | Nextcloud (CalDAV/CardDAV) | Export + Selbstkontrolle |
| Fotos | Immich (selbst) oder verschlüsselte Sync-Ordner | Keine AI-Training-Klauseln |
| Notizen | Joplin oder Obsidian (Lokal) | Markdown = Export-Sicherheit |
| KI-Assistenten | Lokale Modelle (LM Studio, Ollama) | keine Chat-Logs bei Dritten |

## Lügen ausräumen

**Falsch:** „Selbst hosten ist für alle das Richtige." — Nein. Ein falsch konfigurierter Server ist schlimmer als Dropbox: Er hat auch deine Daten, aber du bist für die Sicherheitsupdates verantwortlich. Wer nicht patchen will, soll verschlüsselt mieten.

**Falsch auch:** „Meine Cloud-Daten sind verschlüsselt, also ist alles gut." — Client-side verschlüsselt? Gut. „Verschlüsselt" im Marketing-Sinn (serverseitig, mit vom Anbieter verwalteten Schlüsseln)? Dann kann der Anbieter (und jeder mit Jurisdiktion über ihn) mitlesen.

## Quellen

1. [Nextcloud](https://nextcloud.com/) (Open Source, selbst hostbar)
2. [Cryptomator](https://cryptomator.org/) (Client-side E2EE für jede Cloud)
3. [KeePassXC](https://keepassxc.org/) / [Bitwarden](https://bitwarden.com/)
