# FAQ

### Wie deaktiviere ich das CoinSystem?&#x20;

Das CoinsSystem ist teil der CoreAPI. Daher muss dieses dort deaktiviert werden. In der Konfigurationsdatei 'commands.yml', welche unter \`plugins/primeplugins/core/commands.yml\` zu finden ist, must du bei den&#x20;

### Das PermissionsSystem funktioniert nicht auf BungeeCord!

Damit die Permissions auch auf BungeeCord übernommen werden, musst du die CoreAPI für BungeeCord installieren. Wenn du diese korrekt einrichtest, werden deine Permissions direkt übernommen!

### Das PermissionsSystem übernimmt die Permissions nicht

Um das PermissionsSystem möglichst performant zu gestalten werden die Permissions gecached. Demnach kann es bis zu 15 Minuten dauern bis eine Änderung der Permissions oder Gruppen auf allen Servern übernommen wird.

### Die Placeholder funktionieren nicht

Damit die Placeholder funktionieren muss Folgendes zutreffen:

* Die [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/) muss installiert sein
* Die CoreAPI muss installiert sein
* Es muss sich um einen Spigot-Server handeln
* Das Plugin welches den Placeholder anzeigt muss die PlaceholderAPI unterstützen

&#x20;
