---
description: 'Hier lernst du, wie du MLGRush richtig einrichtest'
---

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

## 

## Schritt 2: MySQL-Zugangsdaten

Nachdem du AdvancedTeamspeak auf deinem Spigot-Server installiert hast, musst du deine MySQL Daten in die config.yml eintragen.

{% hint style="info" %}
Alle Dateien für die Konfiguration des Plugins findest du in dem Order plugins/mlgrush
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
CloudNet3: `/cloud cp <ServerName>`
{% endhint %}

{% hint style="warning" %}
Danach musst du den Spawn mit `/setspawn` setzten und noch einmal neujoinen
{% endhint %}

## Schritt 4: Erstes Setup

### Erste Karte \(/setup\)

Begib dich nun auf den Server, und führe den Command `/setup` aus. Dieses führt dich durch das Setup für den Spawn & deine erste Map

Um eine weitere Map einzurichten muss man lediglich erneut das Setup mit `/setup` starten.

### Warteschlange \(/setqueue\)

Begib dich zu dem Punkt wo du die Warteschlange haben möchtest, und gib den Befehl `/setqueue` ein.

### Statswall \(/setstatswall\)

Der [_Syntax_](https://de.wikipedia.org/wiki/Syntax) für den setstatswall Befehl ist `/setstatswall <position> <sign/head>`. Um den Kopf für Platz 1 zu setzen musst auf den Kopf gucken. Dann gibst du den Befehl `/setstatswall 1 HEAD` ein. Danach musst du das dazugehörige Schild angucken, und den Befehl `/setstatswall 1 SIGN` ausführen.  
Dies kann man auf unendlich viele Positionen erweitern. 

{% hint style="danger" %}
Danach muss das Template ggf. erneut gespeichert werden!
{% endhint %}

