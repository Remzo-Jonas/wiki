# Teleporter einstellen

## Generelle Einstellungen

`title` gibt den Namen des Inventars an  
`size` gibt die Größe des Inventars an  
`filler` gibt das Item an mit welchem nicht befüllte Slots ausgefüllt werden

```text
global:
  title: §eTeleporter
  size: 45
  filler:
    use: true
    item:
      ==: org.bukkit.inventory.ItemStack
      type: STAINED_GLASS_PANE
      damage: 8
      meta:
        ==: ItemMeta
        meta-type: UNSPECIFIC
        display-name: ' '
```

{% hint style="warning" %}
`size` **muss** ein vielfaches von 9 sein!
{% endhint %}

## Einzelne Items

Die `4` repräsentiert den Slot. Der erste Slot fängt bei 0 an.  
`item` gibt das Item an, welches in den slot gelegt wird  
`action` Siehe [_Hotbar einstellen_](hotbar-einstellen.md#eigene-items)   
`cloud` Wenn aktiv wird ein %count% in der Lore durch die Anzahl von Spieler in der von value definierten Gruppe/Task

{% hint style="info" %}
Aktuell wird nur CloudNet und CoudNetv3 unterstützt
{% endhint %}

```text
'4':   
   item:
      ==: org.bukkit.inventory.ItemStack
      type: STICK
      meta:
        ==: ItemMeta
        meta-type: UNSPECIFIC
        display-name: §eMLGRush
        lore:
        - '§7Spieler-Online: §e%count%'
    action:
      type: TELEPORT
      value: mlgrush
    cloud:
      use: true
      value: MLGRush
```

