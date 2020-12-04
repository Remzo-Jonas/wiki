# Spigot-Addon

## Installieren

In der runtergeladenen Datei findest du neben dem bungeesystem auch eine Datei namens BungeeSystemSpigot . Diese Datei musst du auf allen deinen Spigot-Server installieren.

## Configuration

In der Config musst du zunächst die selben MySQL Daten angeben.

Wenn `autoafk`aktiviert ist, werden Spieler die sich 30 Sekunden lang nicht bewegen in AFK gesetzt  
`Reports`gibt an, ob der Befehl /reportsgui aktiviert ist.

```text
mysql:
  host: localhost:3306
  database: bungeesystem
  username: root
  password: password
settings:
  autoafk: true
  reports: true
messages:
  afk:
    start: '&aDu wurdest als Abwesend makiert!'
    end: '&aDu nun nichtmehr als Abwesend makiert!'
```



