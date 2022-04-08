---
description: >-
  Das Einrichten des Discord Bots kann einem schwierig vorkommen. Mit der
  richtigen Anleitung ist es jedoch Kinderleicht.
---

# Discord Bot

## Vorbereitung

### Discord Applikation

#### Schritt 1: Erstellen

Begib dich auf und erstelle eine Applikation

![Erstellen einer neuen Applikation](<../.gitbook/assets/r2ikovq (2) (2) (2).png>)

#### Schritt 2: Name vergeben

![Vergabe eines Namens für die Applikation](../.gitbook/assets/theeqnq.png)

#### Schritt 3: Bot erstellen

![Der Applikation einen Bot hinzufügen](<../.gitbook/assets/vs8orlo (1) (1).png>)

#### Schritt 4: Bot-Token kopieren

![](../.gitbook/assets/UYvmAhY.png)

{% hint style="danger" %}
Speichere dir diesen Token ab! Wir brauchen diesen token später.
{% endhint %}

#### Schritt 5: Bot auf deinen Server einladen

![](../.gitbook/assets/3kyftVu.png)

Unter OAuth2 musst du nun bei `SCOPES` `bot` auswählen und unter `BOT PERMISSIONS` musst du `Administartor` auswählen. Nun kopierst du den Link, und öffnest ihn in einem neuen Tab.

![](../.gitbook/assets/mvGrFAs.png)

Wähle hier nun deinen Server aus und klicke auf Weiter. Du autorisierst deinen Bot nun mit deinem Server zu interagieren. Der Bot wird anschließend deinen Discord-Server automatisch betreten!

![](../.gitbook/assets/oH2eeHj.png)

Nun kannst du den Bot auf deinem Server betrachten

### Developer Modus

Damit du die Config richtig einstellen kannst, musst du bei deinem Discord den Entwickler Modus aktivieren.\
In deinen Einstellungen kannst du unter dem Punkt Erweitert den Entwickler-Modus aktivieren.

![](../.gitbook/assets/hE5S7hO.png)

## Einrichtung der Config

### Connection

Unter connection findest du verschiedene Einstellmöglichkeiten. \
**key** -  Hier gibst du den Token den du dir vorher kopiert hast an\
**status** - Hier gibst du den OnlineStatus des Bots an. (grüner, gelber oder roter Kreis) (Liste aller möglichen Status: [_JDA Wiki_](https://ci.dv8tion.net/job/JDA/javadoc/net/dv8tion/jda/api/OnlineStatus.html) __ )\
**activity.type** - Hier gibst du die Art der Activity an. (Spielt..., Schaut.., etc...) (Liste aller möglichen Types: [_JDA Wiki_](https://ci.dv8tion.net/job/JDA5/javadoc/net/dv8tion/jda/api/entities/Activity.ActivityType.html) )\
**activity.value** - Die Aktivität die angezeigt wird nach dem Typ. Bspw. \[Spielt] verifizieren\
**guild** - Guild steht hier für deinen Discord-Server. Hier musst du die ID deines Servers angeben. Diese erhälst du indem du Rechtsklick auf dein Server-Icon machst, und dort die ID kopierst

![](<../.gitbook/assets/cbnttim (1) (1).png>)

### Verifikation

**command** - Hier gibst du den Befehl ein, mit dem sich Spieler verifizieren Können. Bei !link können sich Spieler dann mit `!link <Code>` verifizieren\
**channel** - Die ID des Channels in dem sich Spieler verifizieren können. Diese erhälst du indem du Rechtsklick auf den Channel machst, und dort ID kopieren auswälst. (Wie bei dem Server)\
**deleteAllMessages** - Wenn du hier true angibst, werden alle Nachrichten die in diesen Channel geschrieben werden automatisch gelöscht.\
\
_**groups**_ Hier kannst du Einstellen, ob und welche Gruppen beim verifizieren vergeben werden.\
**verify** Diese Gruppe wird jedem der sich verifiziert gegeben, egal welchen Rang er hat.\
**apply** Aktiviert bzw. deaktiviert diese Funktion.\
**id** ID der Verify-Rolle. Diese erhältst du, indem du in den Rollen Einstellungen in der Servereinstellungen einen Rechtsklick auf die Rolle machst, und dort ID kopieren auswählst:

![](../.gitbook/assets/48Ue2db.png)

**roles** Vergibt Rollen je nach einer Permission die ein Spieler haben muss\
**apply** Aktiviert bzw. deaktiviert die Funktion\
**id** Eine Liste von permissions und der dazugehörigen Rollen-ID (siehe oben). Format: `permssion:Rollen-ID`.&#x20;

### Notify & Report

Wenn du Notify aktivierst erhälst du in deinem Discord immer wenn jemand einen **Spieler bannt** eine Nachricht in einen angegebenen Channel.

Wenn du Report aktivierst, behälst du in deinem Discord immer wenn jemand einen **Spieler reported** einen Nachricht in einen angegebenen Channel.

Du musst bei beiden die ChannelID angeben. Die ID gibst du genauso wie bei dem Channel von der [Verifikation](discord-bot.md#verifikation) an.
