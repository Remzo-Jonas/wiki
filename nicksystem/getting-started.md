---
description: Hier lernst du wie du das Nicksystem einrichtest
---

# Getting started
{% hint style="info" %}
Du musst nach jedem Schritt den Server neustarten.
{% endhint %}
### Schritt 1: Vorbereitung

Lade die Datei ```NickSystem-1.0.0_2.jar``` auf deinen Spigot Server hoch.

{%hint style ="info" %}
Lade die Datei erst nur auf den Hauptserver (z.b Lobby-1) und erst danach auf die
verbleibenden Spigot Server!
{% endhint %}
## 

### Schritt 2: MySQL Verbindung 

Nun musst du deine MySQL Verbindung einrichten. Dies tust du unter diesem Pfad ```plugins/primeapi/config.yml```


So sollte deine Config.yml aussehen.
```
mysql:
  host: localhost:3306 
  database: primeapi
  username: root
  password: passwort
```
Erklärung zu der Config
```
Host = IP / Domain deiner Datenbank
Database = Name der Datenbank
username = Name des Datenbanknutzers
password = Password des Nutzers


{% hint style="warning" %}
Achte darauf, dass du den `host` mit Port angibst
{% endhint %}
### 

### Schritt 3: Lizenz eintragen.
Es hat sich nun ein weiterer Ordner in `primeplugins` erstellt, dort musst du nun in den Ordner `nicksystem` deine Lizenz eintragen. Solltest du noch keine Lizenz haben, melde dich auf meinem Discord Server.

### Schritt 4: Abschluss der Installation

Du kannst nun noch mehrere Namen in der Config einstellen, und das GUI mit mit der Option `apply: true` deaktivieren, oder mit `apply: false` aktivieren.

### Schritt 5: Autonick & übernehmen von Nicknamen auf mehreren Servern.
Wenn du einen Bungeecord Server hast, und möchtest das wenn sich eine Person nickt, das dieser auf den anderen unterservern noch behalten wird, musst du ganz einfach
das Nicksystem mit der Coreapi auf den jeweiligen unterserver installieren.

{% hint style="info" %}
Wenn du probleme bei der Installation hast, kannst du gerne auf unserem Discord nach Hilfe fragen.
{% endhint %}