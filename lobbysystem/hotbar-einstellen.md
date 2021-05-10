# Hotbar einstellen

## Vorgegebene Items

Hier könnt ihr das Material der Items bestimmen. Bei Type könnt ihr dies einstellen.  
Wenn ihr `active` als `false` setzt, wird das Item nicht in die Hotbar gesetzt.  
`slot` gibt den Slot von dem Item an. Der erste Slot ist `0`.

{% hint style="info" %}
[Material-Liste 1.8.x-1.12.x](https://helpch.at/docs/1.8/org/bukkit/Material.html)  
Material-Liste 1.13.x - 1.16.x
{% endhint %}

## Eigene Items

Das `slot` wird durch die Nummer des Slots ersetzt, in den das Item soll.  
item gibt das Item an, welches in die Hotbar hinzugefügt wird.  
`action-type` gibt den Typ von der Aktion an, wenn das Item angeklickt wird. \(`COMMAND`,`MESSAGE`,`TELEPORT`,`NONE`\)  
`action-value` gibt den Wert an. \(Bei `COMMAND` den Befehl ohne `/`, bei `MESSAGE` die nachricht, bei `TELEPORT` die `Location`, die mit `/setup setlocation` gesetzt   
Wenn `permission-use`  aktiviert ist wir das Item nur Spielern mit der Permission `value` gegeben

```text
own:
  slot:
    item:
      ==: org.bukkit.inventory.ItemStack
      type: PAPER
      meta:
        ==: ItemMeta
        meta-type: UNSPECIFIC
        display-name: §6Dies ist ein Beispiel-Item
        lore:
        - Dies ist eine Beispiel-Lore
    action:
      type: COMMAND
      value: reportsgui
    permission:
      use: false
      value: lobby.example
```

