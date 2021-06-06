---
description: >-
  Auf dieser Seite findest du eine detaillierte Beschreibung, wie du
  Gruppenerstellen und einrichten kannst.
---

# Gruppen einstellen

## Gruppen einrichten

{% hint style="warning" %}
Sollte der Befehl `/perms` nicht funktionieren, nutze stattdessen `/perm`, in der Beschreibung wird ausschließlich `/perms` benutzt, aber beide Befehle funktionieren.
{% endhint %}

#### Schritt 1: Gruppe erstellen

Wir werden uns in diesem Beispiel die Administrator-Gruppe erstellen. Dazu führen wir als erstes den entsprechenden Befehl aus:

```text
/perms create admin Administrator
```

Das erste Argument gibt den internen Gruppen Namen an, dieser sollte möglichst simpel gehalten werden, da alle späteren Erwähnungen der Gruppe über diesen laufen werden.

Das zweite Argument ist der Name, welcher bei einer Abfrage angezeigt wird \(bspw. im Scoreboard\), dieser muss nur einmal eingegeben werden und kann daher auch umfangreicher sein.

{% hint style="info" %}
Der Anzeigename kann nachträglich mit dem Befehl `/perms group <Name der Gruppe> setdisplay <Anzeigename>` geändert werden.
{% endhint %}

#### Schritt 2: Farbe & Präfix vergeben

Wir werden nun der Gruppe eine Farbe und einen Präfix geben. Der Anzeigename \(das zweite Argument von Schritt 1\) wird dann in dieser Farbe angezeigt. Der Präfix wird im Chat und in der Tabliste angezeigt.

```text
/perms group admin setcolor &4
```

Mit diesem Befehl setzen wir die Farbe des Anzeigenamens auf rot, hier kann jeder beliebige Minecraft Farbcode angegeben werden.

```text
/perms group admin setprefix &4Admin &8: &4
```

Mit diesem Befehl stellen wir den Präfix der Gruppe ein, dieser wird in der Tabliste und im Chat angezeigt. Hierbei sind jegliche Minecraft Farbcodes zulässig.

#### Schritt 3: Rechte und Gewichtung vergeben

Nun müssen wir der Gruppe Rechte und ein Gewicht zu weisen. Das Gewicht gibt an, welche Position der Rang hat, umso höher das Gewicht, umso höher die Position. Es empfiehlt sich hierbei bei 100 zu beginnen und dann abzusteigen, selbstverständlich sind auch alle anderen Zahlen möglich.

```text
/perms group admin setweight 100
```

Mit diesem Befehl geben wir unserer Admin Gruppe das Gewicht 100, sie wird jetzt über allen Gruppen angezeigt, die ein niedrigeres Gewicht haben.

```text
/perms group admin permission add *
```

Mit diesem Befehl geben wir unserer Admin Gruppe nun auch die `*`-Berechtigung, mit diesem Befehl kann optional jede Berechtigung vergeben werden, den Namen dieser müsst ihr in der Dokumentation des entsprechenden Plugins nachschauen.

#### Nice to have: Vererbung

Umso mehr Gruppen man hat, umso wichtiger wird die Vererbung, damit erbt eine Gruppe alle Berechtigungen einer anderen Gruppe. Eine Inhaber Gruppe könnte so alle Berechtigungen der Admin Gruppe erben. Dies erspart euch den Aufwand Standard-Rechte unnötig oft einzugeben.

```text
/perms group owner setinherit admin
```

In diesem Beispiel habe ich mir nun eine Inhaber Gruppe erstellt, die alle Berechtigungen der Admin Gruppe erbt. Sollte die Admin Gruppe bereits die Berechtigungen einer anderen Gruppe erben, erbt die Inhaber Gruppe diese nun auch.

{% hint style="success" %}
**Interessant**  
Wenn du keine Vererbung angibst, werden immer die Berechtigungen der default Gruppe vererbt!
{% endhint %}

