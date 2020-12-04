# Getting started



## Schritt 1: Lizenz

Um zu verifizieren, dass du das Plugin wirklich erworben hast, musst du zunächst deine Lizenz in der settings.yml angeben.

Solltest du keine Lizenz besitzen, melde dich per [Support](../other/support.md)

```text
license: '25efa038-3518-11eb-adc1-0242ac120002'
```

{% hint style="info" %}
Sollte es Probleme geben setze ein `'` vor und nach deine Lizenz
{% endhint %}

## Schritt 2: MySQL-Zugangsdaten

Nachdem du AdvancedTeamspeak auf deinem Spigot-Server installiert hast, musst du deine MySQL Daten in die config.yml eintragen.

{% hint style="info" %}
Alle Dateien für die Konfiguration des Plugins findest du in dem Order plugins/LobbySystem
{% endhint %}

```text
  mysql:
    host: 127.0.0.1:3306
    database: lobbysystem
    user: root
    password: password
```

{% hint style="warning" %}
Achte darauf den Port beim host mit anzugeben.  
Standard für MariaDB/MySQL: 3306
{% endhint %}

## Schritt 3: Server neustarten

Jetzt könnt ihr euren Server neustarten

{% hint style="danger" %}
Wenn du eine Cloud benutz, stelle sicher, dass du das Template kopiert hast:  
CloudNet: `/cloud copy <ServerName>`  
CloudNet3: `/cloud copy <ServerName>`
{% endhint %}

{% hint style="warning" %}
Danach musst du den Spawn mit `/setspawn` setzten und noch einmal neujoinen
{% endhint %}

