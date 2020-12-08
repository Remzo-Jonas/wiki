---
description: Hier lernst du wie du das BungeeSystem einrichtest
---

# Getting started

### Schritt 1: MySQL-Zugangsdaten

Nachdem du das BungeeSystem auf deinem BungeeCord-Server installiert hast, musst du deine MySQL Daten in die MySQL.yml eintragen. 

{% hint style="info" %}
Alle Dateien für die Konfiguration des Plugins findest du in dem Order plugins/PrimeBungeeSystem
{% endhint %}

```text
host: localhost
dbname: bungeesystem
dbuser: root
dbpw: password
```

{% hint style="warning" %}
Achte darauf, dass du den `host` ohne Port angibst
{% endhint %}

## 

### Schritt 2: Lizenz 

Um zu verifizieren, dass du das Plugin wirklich erworben hast, musst du zunächst deine Lizenz in der settings.yml angeben.

Solltest du keine Lizenz besitzen, erhälst du diese auf meinem [Discord](https://discord.primeapi.de)

```text
LizenzKey: 25efa038-3518-11eb-adc1-0242ac120002
```

{% hint style="info" %}
Sollte es Probleme geben setze ein `'` vor und nach deine Lizenz
{% endhint %}

### 

### Schritt 3: Server neustarten

Änderungen können nur übernommen werden, wenn du den Server neu startest. Denk also immer dadran den Server neuzustarten, wenn du etwas in den Configs veränderst!

{% hint style="danger" %}
Wenn du eine Cloud benutz, stelle sicher, dass du das Template kopiert hast:  
CloudNet: `/cloud copy <ServerName>`  
CloudNet3: `/cloud copy <ServerName>`
{% endhint %}

