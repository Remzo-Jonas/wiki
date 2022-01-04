---
description: Hier lernst du wie du das Nicksystem einrichtest
---

# Getting started

#### Schritt 1: Dateien hochladen

Lade die Datei `NickSystem[...].jar` auf deinen Spigot Server hoch.

{% hint style="info" %}
Lade die Datei erst nur auf einen Server hoch und kopiere den erstellten Ordner und die Datei nach der Einrichtung auf die verbleibenden Spigot Server.
{% endhint %}



#### Schritt 2: MySQL Daten angeben

Trage nun im neu erstellen Ordner `primeplugins` in der `accessdata.yml` deine MySQL Daten ein.

Wenn du die CoreAPI bereits installiert hast, kannst du diesen Schritt überspringen!

#### Schritt 3: Lizenz eintragen

Es hat sich nun ein weiterer Ordner im Verzeichnis `primeplugins` erstellt, dieser heißt `nicksystem`. Dort musst du deine Lizenz eintragen, solltest du noch keine Lizenz haben, melde dich auf meinem [Discord](https://discord.com/invite/XAGYh3BUkY) Server.

#### Schritt 4: Config einstellen

In der Config sind noch folgende weitere Einstellungen zu treffen:\
`autonick.apply` gibt an, ob auf diesem Unterserver ein Spieler genickt werden soll oder nicht. Das GUI zum einstellen der Nick-Einstellungen öffnet sich nur, wenn diese Einstellung auf `false` gestellt ist.\
`nicknames` gibt eine Liste an, aus welcher ein Name rausgesucht wird, sollte ein Spieler eingestellt haben er möchte einen Zufällig-Generierten Nickname haben!

{% hint style="info" %}
Wenn du den Hinweis bei Schritt 1 befolgt hast, kannst du jetzt den Ordner und die Datei auf alle anderen Spigot Server hochladen.
{% endhint %}



{% hint style="success" %}
Du hast das Plugin erfolgreich eingerichtet und kannst nun im Spiel mit der Nutzung des NickSystems beginnen.

Nutze /nick um dich zu Nicken oder zum öffnen des Nick-GUIs
{% endhint %}
