---
description: Hier findest du Fehler die oft auftreten & wie du sie behebst
---

# Common errors

## Das Plugin funktioniert nicht

Stelle sicher, dass du alle schritte in [Getting started](getting-started.md) befolgt hast.  
Sollte dies der Fall sein sichte deinen Log. Dort steht schon oft was der Fehler sein könnte.  
Wenn du alle der folgenden Punkte überprüft hast, melde dich bitte im [Support](../other/support.md).

* MySQL-Daten auf Richtigkeit überprüft
* Lizenz überprüft
* Log überprüft
* [Configuration Überprüft](configuration.md#sonderzeichen)

## Die Configuration wird nicht gespeichert

Stell sicher, dass du die Datei nach dem Bearbeiten wieder hochgeladen hast.  
Wenn du eine Cloud nutzt musst du den temporären Server in das Template laden.  
\(/cloud copy &lt;Server&gt; bzw. /cloud cp &lt;Server&gt;\)

## Permissions

Funktioniert eine Permission nicht, stelle sicher, dass sie 100%ig richtig geschrieben ist. Bei einigen Permissionssystemen spielt die Groß- und Kleinschreibung eine Rolle. Versuche es mit einem großen B.  
Beispiel: `Bungee.amute`

{% hint style="warning" %}
Für /ban:  
Es wird zunächst `Bungee.ban` benötigt und dazu noch `Bungee.ban.<banid>`!
{% endhint %}

