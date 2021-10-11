---
description: >-
  Auf dieser Seite findest du eine detaillierte Beschreibung zur Einrichtung des
  Plugins
---

# Loslegen

## Getting Started

{% hint style="info" %}
Nach jedem Schritt muss der Server neu gestartet werden.
{% endhint %}

#### Schritt 1: Dateien hochladen

Lade die Datei `PermissionsSystem-1.0.0.jar` auf deinen Spigot Server hoch.

{% hint style="info" %}
Lade die Datei erst nur auf einen Server hoch und kopiere den erstellten Ordner und die Datei nach der Einrichtung auf die verbleibenden Spigot Server.
{% endhint %}

Solltest du ein Proxy-basierendes System nutzen, musst du die Datei `PermissionsSystem-Bungee-1.0.0.jar` auf deinen Proxy-/Bungeecord Server hochalden.

#### Schritt 2: MySQL Daten angeben

Trage nun im neu erstellen Ordner `primeplugins` in der `accessdata.yml` deine MySQL Daten ein.

#### Schritt 3: Lizenz eintragen

Es hat sich nun ein weiterer Ordner im Verzeichnis `primeplugins` erstellt, dieser heißt `permissions`. Dort musst du deine Lizenz eintragen, solltest du noch keine Lizenz haben, melde dich auf meinem [Discord](https://discord.com/invite/XAGYh3BUkY) Server.

{% hint style="info" %}
Wenn du den Hinweis bei Schritt 1 befolgt hast, kannst du jetzt den Ordner und die Datei auf alle anderen Spigot Server hochladen.
{% endhint %}

#### Schritt 4: Admin Rechte erhalten

Gehe nun in die Konsole deines Spigot Servers und führe den Befehl `perms setadmin <Dein Name>` aus, damit erhältst du die `*`-Berechtigung.

{% hint style="success" %}
Du hast das Plugin erfolgreich eingerichtet und kannst nun im Spiel mit der Nutzung des Permissionsystems beginnen.

Nutze hierfür den Befehl `/perms`, um eine Übersicht aller Befehle zu erhalten.

Lies dir den Beitrag zu unserem Webinterface durch, um das Permissionsystem mit dem Webinterface zu verbinden.
{% endhint %}
