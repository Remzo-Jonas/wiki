# Konfiguration

| Parameter | Beschreibung |
| :--- | :--- |
| license | Die erhaltene Lizenz. Siehe [_Gettings started_](getting-started.md)\_\_ |
| inv-clear | Gibt an, ob das Inventar gecleart werden soll, wenn es sich updated |
| jumpboost-plates | Aktiviert die Jump-Boost Platten. \(Gold Platte und 2 Blöcke dadrunter ein Smaragtblock\) |
| save-location | Gibt an, ob /savelocation aktiviert werden soll |
| level | Gibt an welches Level den Spielern beim Joinen gesetzt wird |
| rewards | Gibt die Einstellungen der Täglichen Belohnungen an \(Nur mit BungeeSystem\) |
| mysql | Gibt die MySQL Verbindungsdaten an |
| animations | Stellt die Anymation beim Öffnen eines Inventars ein. Mögliche Types: LEFT\_FILLER, LEFT, CLOCKWISE, STAR |
| score | Gibt das Scoreboard an |
| lobby | Gibt Einstellungen für das Scoreboard an |



{% hint style="warning" %}
### Scoreboard

Ein Eintrag darf nicht doppelt existieren! Wenn ihr mehrere leere Zeilen haben wollt, müsst ihr unterschiedliche Farbcodes angeben!
{% endhint %}

```text
license: lizenz
settings:
  inv-clear: true
  jumpboost-plates: true
  save-location: true
  level: 2020
  rewards:
    '1':
      amount: 1000
      waitInHours: 24
    '2':
      amount: 2500
      waitInHours: 24
      permission: lobby.premium
  mysql:
    host: 127.0.0.1:3306
    database: lobbysystem
    user: root
    password: password
  animations:
    use: true
    type: STAR
    sound:
      tick: CLICK
      finished: LEVEL_UP
    tick:
      lenght: 50
  score:
    title: '&7« &eServer.de &7»'
    content:
    - '&7&1            '
    - '&7TeamSpeak:'
    - '&8➥ &ets.server.de'
    - '&7&3            '
    - '&7Forum:'
    - '&8➥ &eforum.server.de'
    - '&7&4            '
    - '&7Discord:'
    - '&8➥ &ediscord.server.de'
    - '&7&5            '
    use: true
lobby:
  cloud:
    group-name: Lobby
    item:
      current-lobby:
        [...]
      other-lobby:
        [...]
  silenthub: SilentHub
```

