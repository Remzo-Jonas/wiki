---
description: 'Hier lernst du, wie du die Bangründe änderst'
---

# Ban Gründe ändern

## Was bedeutet was?

Am Anfang der Datei siehst du eine Liste mit allen bereits bestehenden ban Gründen. Es funktionieren nur ban Gründe, die dort angegeben sind..

```text
reasons:
- '1'
- '2'
- '3'
- '4'
- ...
```

Dadrunter siehst du die einzelnen Gründe.   
Die `'1'` steht hier für den ban Grund, der auch oben in die Liste eingetragen werden muss.   
`Reason` stellt den Grund dar.  
`Type` stellt den Typ der Bestrafung dar. Hier kann man nur `Ban`oder `Mute` angeben  
`FirstBan` gibt die länge für den ersten Ban für einen Spieler mit diesem Grund an.  
`int` gibt die Anzahl an, während `s` die Einzeig angibt. 

| s | Einheit |
| :--- | :--- |
| P | Permanent \(int muss hier auf -\) |
| d | Tage |
| h | Stunden |
| m | Minuten |

Also wird jemand der zum ersten mal wegen Hacking gebannt wird zunächst für 30 Tage gebannt, beim nächsten mal jedoch Permanent.

```text
Reason:
  '1':
    Reason: Hacking
    Type: Ban
    FirstBan:
      int: 30
      s: d
    SecondBan:
      int: -1
      s: P
  [...]
```

{% hint style="danger" %}
Wenn du bei einem [`String`](https://de.wikipedia.org/wiki/Zeichenkette) eins der folgenden Zeichen angibst, musst du ein `'` vor und nach dem String angeben.  
 `: { } [ ] , & * # ? | - < > = ! % @ \ ä ö ü`
{% endhint %}

## Eignen ban Grund hinzufügen

Ich werde ich spam als Abkürzung für Spamming konfigurieren.

```text
Reason:
  'spam':
    Reason: Spamming
    Type: Mute
    FirstBan:
      int: 10
      s: m
    SecondBan:
      int: 2
      s: d
  [...]
```

Natürlich müssen wir jetzt noch 'spam' in die Liste oben hinzufügen

```text
reasons:
- 'spam'
- '1'
- '2'
- '3'
- '4'
- ...
```

![](../.gitbook/assets/13hut50.png)

