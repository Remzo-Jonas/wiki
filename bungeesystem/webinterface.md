---
description: 'Hier lernst du, wie du das Webinterface aufsetzt'
---

# Webinterface

## Schritt 1: Dateien kopieren

In dem ZIP-Archive welches du heruntergeladen hast findest du einen Ordner namens `Webinterface`. Den Inhalt davon musst du auf deinen Webserver ziehen.

## Schritt 2: Einstellungen treffen

Alle Einstellungen die du treffen musst findest du unter dem Ordner `inc` in der Datei `settings.php`. Dort musst du zunächst die Website mit der selben Datenbank wie das Plugin verbinden.

Ebenfalls musst du die IP-Adresse & Port des Minecraft-Servers angeben.

Du kannst du nun auch die Namen den Ränge innerhalb des Webinterfaces ändern.

## Schritt 3: Einstellungen auf dem Server treffen

Nun musst du erneut die `settings.yml` bearbeiten. \(Siehe [_Konfiguration_](configuration.md)\)  
Bei dem Paramenter `link` unter `webpannel` musst du nun den Link zu der Website eintragen.  


{% hint style="danger" %}
Gib keine Datei an!  
Richtig: `link: 'https://meinedomain.de/bungee`  
~~Falsch~~: `link: 'https://meinedomain.de/bungee/index.php`
{% endhint %}

## Schritt 4: Einen Account erstellen

Um dir einen Account zu erstellen musst du dich zunächst mit deinem Minecraft-Account auf den Server einloggen. Danach gibst du den Befehl `/webaccount` ein. Dann klickst du entweder auf die Nachricht, oder du begibst dich auf die Website, und registrierst dich dort mit dem Register-Key, den du erhalten hast.

## Schritt 5: Admin-Rechte vergeben

Zuletzt musst du dir Admin-Rechte auf dem Webinterface geben. Um dies zu tun, gibst du den Befehl `/webaccount setadmin <Dein Name>` ein. Nun hast du alle Berechtigungen im Webinterface.

