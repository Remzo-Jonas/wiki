---
description: Hier lernst du wie du AdvancedTeamspeak einrichtest
---

# Getting started

## Schritt 1: Lizenz

Um zu verifizieren, dass du das Plugin wirklich erworben hast, musst du zunächst deine Lizenz in der settings.yml angeben.

Solltest du keine Lizenz besitzen, melde dich per [Support](../support.md)

```text
license: '25efa038-3518-11eb-adc1-0242ac120002'
```

{% hint style="info" %}
Sollte es Probleme geben setze ein `'` vor und nach deine Lizenz
{% endhint %}

## Schritt 2: MySQL-Zugangsdaten

Nachdem du AdvancedTeamspeak auf deinem Spigot-Server installiert hast, musst du deine MySQL Daten in die config.yml eintragen.

{% hint style="info" %}
Alle Dateien für die Konfiguration des Plugins findest du in dem Order plugins/ts3channel
{% endhint %}

```text
mysql:
  host: 'localhost:3306'
  database: 'teamspeak'
  username: 'root'
  password: 'password'
```

{% hint style="warning" %}
Achte darauf den Port beim host mit anzugeben.  
Standard für MariaDB/MySQL: 3306
{% endhint %}

## Schritt 3: Teamspeak³ Query Zugangsdaten

Damit sich der Bot auf deinen Server einloggen kann, musst du einen Query Zugang hinzufügen:

#### Zugang erstellen

Erstelle dir zunächst eine neue Identität:  
Extras &gt; Identitäten &gt; Erstellen  
  

![Fenster zum erstellen einer neuen Indentit&#xE4;t](../.gitbook/assets/h6f5vkv.png)

Danach musst du dich mit dieser Identität auf deinen Server verbinden.  
Dann erstellst du dir einen Query Zugang:  
Extras &gt; ServerQuery Login  
Dort gibst du einen Namne an, und klickst auf `OK`  
  

![Fenster mit den Zugangsdaten](../.gitbook/assets/r2lnkvp.png)

Diese Daten müsst ihr nun in der config.yml eingeben

```text
connection:
  host: 'primeapi.de'
  username: 'AdvancedTeamspeak'
  password: 'password'
  port: 9987
  displayname: 'Teamspeak Bot'
```

{% hint style="warning" %}
Wenn ihr euren Ts³-Server nicht selbst hostet müsst ihr die Daten die ihr direkt von eurem Hoster erhalten habt eintragen
{% endhint %}

## Schritt 4: Server neustarten

Jetzt könnt ihr euren Server neustarten, und dann sollte der command /ts3channel funktionieren

{% hint style="danger" %}
Wenn du eine Cloud benutz, stelle sicher, dass du das Template kopiert hast:  
CloudNet: `/cloud copy <ServerName>`  
CloudNet3: `/cloud copy <ServerName>`
{% endhint %}

