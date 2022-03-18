---
description: Hier lernst du, wie du das Webinterface einrichtest
---

# Loslegen

## Voraussetzungen

* Core-API auf BungeeCord ebene installiert ([_wiki_](../core-api/loslegen.md)_ _)
* Einen Webserver

## Schritt 1: Dateien kopieren

Zunächst musst du die Dateien des Webinterfaces auf deinen Server hochladen. Achte darauf, dass du jede Datei und jeden Ordner kopierst!

## Schritt 2: Config einstellen

In dem Ordner `config` findest du die `config.php`. Dort musst du einige Einstellungen vornehmen

### MySQL-Daten

Als erstes musst du deine MySQL-Daten angeben. Achte darauf, dass du hier die selben wie in Minecraft angibst. 

{% hint style="warning" %}
Wichtig!\
Sollte der Webserver nicht auf dem selben Server wie dein Minecraft-Netzwerk, musst du ggf. bei deiner SQL-Datenbank den remote-access aktivieren.\
Mehr Informationen hier: [_\*klick\*_](https://stackoverflow.com/questions/21664091/mariadb-not-allowing-remote-connections)__
{% endhint %}

### Module

Je nach dem, welche Produkte du erworben hast, kannst du verschiedene Funktionen in deinem Webinterface freischalten. Lies dir dazu am besten genau die Beschreibung innerhalb der Config durch.

## Berechtigungen

Die Ränge die du dort erstellst, sind nur innerhalb des Webinterfaces gültig. Du kannst so viele Ränge erstellen wie du möchtest.\
Alle Ränge **unter 0** (ab -1) gelten als gesperrt, und man kann sich nicht einloggen.'\
**Rang 100** wird einem Teammitglied immer gegeben, wenn es beim registrieren die Permission '**bungee.webadmin**' besitzt.
