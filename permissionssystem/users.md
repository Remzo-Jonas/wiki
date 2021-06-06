---
description: >-
Auf dieser Seite lernst du alles über die Einstellung von Nutzer
Berechtigungen.
---

# Nutzer Rechte vergeben

### Gruppen vergeben:

Das wohl wichtigste ist die Vergabe von Gruppen an Nutzer, wir werden in diesem Beispiel die Admin Gruppe an mich vergeben.

```text
/perms user Eric_mit_C group add admin 100
```

Mit der Zahl am Ende gebe ich dir Stärke an, sollten also zwei Personen die selbe Gruppe haben, wird nach der bei der Vergabe genannten Stärke berechnet, wer höher steht. Die Stärke wird, wenn sie nicht genannt wird, auf 1 gesetzt.

{% hint style="info" %}
Nach der Stärke kann auch optional noch eine Zeitangabe machen, um damit die Dauer des Ranges zu begrenzen. Damit kann z.B. ein Premium Rang für nur zwei Wochen vergeben werden.
{% endhint %}

### Benutzerdefinierte Berechtigungen:

Ihr könnt auch Nutzern unabhängig von ihren Gruppen gewisse Berechtigungen geben.

```text
/perms user Eric_mit_C permission add *
```

Damit kann man sich als Inhaber unabhängig von seinen Gruppen, alle Berechtigungen geben.
