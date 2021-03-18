---
description: Hier lernst du wie du das ClanSystem einrichtest
---

# Getting started

## Schritt 1: MySQL-Zugangsdaten

Nachdem du das ClanSystem auf deinem BungeeCord-Server installiert hast, musst du deine MySQL Daten in die config.yml eintragen.

{% hint style="info" %}
Alle Dateien für die Konfiguration des Plugins findest du in dem Order plugins/ClanSystem
{% endhint %}

```text
mysql:
  host: 127.0.0.1:3306
  database: database
  username: username
  password: password
```

## Schritt 2: Server neustarten

Änderungen können nur übernommen werden, wenn du den Server neu startest. Denk also immer dadran den Server neuzustarten, wenn du etwas in den Configs veränderst!

{% hint style="danger" %}
Wenn du eine Cloud benutz, stelle sicher, dass du das Template kopiert hast:  
CloudNet: `/cloud copy <ServerName>`  
CloudNet3: `/cloud copy <ServerName>`
{% endhint %}

