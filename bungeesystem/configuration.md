---
description: 'Hier erfährst du, was die einzelnen Sachen in der settings.yml bedeuten'
---

# Konfiguration

## Einzelne Felder

<table>
  <thead>
    <tr>
      <th style="text-align:left">Parameter</th>
      <th style="text-align:left">Beschreibung</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">ServerName</td>
      <td style="text-align:left">Name des Servers. Wird an einigen Stellen angezeigt</td>
    </tr>
    <tr>
      <td style="text-align:left">LizenzKey</td>
      <td style="text-align:left">Deine Lizenz. Siehe <a href="getting-started.md#schritt-2-lizenz">hier</a>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Prefix</td>
      <td style="text-align:left">Der Perfix. Siehe <a href="messages-bearbeiten.md">messages</a>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">keepReportsOnLogout</td>
      <td style="text-align:left">Ein erstellter Report bleibt bestehen, wenn der Spieler offline geht</td>
    </tr>
    <tr>
      <td style="text-align:left">keepReportsOnRestart</td>
      <td style="text-align:left">Reports werden gespeichert, wenn der Server neu startet</td>
    </tr>
    <tr>
      <td style="text-align:left">motd</td>
      <td style="text-align:left">Motd in der Serverliste</td>
    </tr>
    <tr>
      <td style="text-align:left">joinmessage</td>
      <td style="text-align:left">Eine Rundnachricht beim ersten Joinen auf das Netzwerk</td>
    </tr>
    <tr>
      <td style="text-align:left">loginStatusOnJoin</td>
      <td style="text-align:left">Beim Joinen Informationen &#xFC;ber /login</td>
    </tr>
    <tr>
      <td style="text-align:left">autobc</td>
      <td style="text-align:left">Autobroadcast de/aktivieren (siehe unten)</td>
    </tr>
    <tr>
      <td style="text-align:left">clearchatOnJoin</td>
      <td style="text-align:left">Chat leeren wenn Spieler das Netzwerk betritt</td>
    </tr>
    <tr>
      <td style="text-align:left">titleOnJoin</td>
      <td style="text-align:left">Sende dem Spieler einen Title wenn er joint</td>
    </tr>
    <tr>
      <td style="text-align:left">warnsOnJoin</td>
      <td style="text-align:left">Informiere den Spieler &#xFC;ber die Anzahl seiner warns</td>
    </tr>
    <tr>
      <td style="text-align:left">autoIPBan</td>
      <td style="text-align:left">Wenn jemand gebannt wird, wird automatisch seine IP gebannt. (Manuell
        pro Ban deaktivierbar)</td>
    </tr>
    <tr>
      <td style="text-align:left">backlist.reason</td>
      <td style="text-align:left">Automute vom Chatfilter Grund</td>
    </tr>
    <tr>
      <td style="text-align:left">blacklist.timeInDays</td>
      <td style="text-align:left">Automute vom Chatfilter L&#xE4;nge in Tagen</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>auth</b>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">use</td>
      <td style="text-align:left">/verify benutzen</td>
    </tr>
    <tr>
      <td style="text-align:left">permission</td>
      <td style="text-align:left">Permission um /verify zu nutzen</td>
    </tr>
    <tr>
      <td style="text-align:left">force</td>
      <td style="text-align:left">Alle Spieler mit der Permission <b>m&#xFC;ssen </b>/verify aktivieren</td>
    </tr>
    <tr>
      <td style="text-align:left">onlyOnIpChange</td>
      <td style="text-align:left">Frage nur nach Verifizierung wenn sich die IP &#xE4;ndert</td>
    </tr>
    <tr>
      <td style="text-align:left">qrServer</td>
      <td style="text-align:left">Der qrServer, auf dem der Key hochgeladen wir zum einscannen</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>coins</b>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">startgeld</td>
      <td style="text-align:left">Startkapital f&#xFC;r neue Spieler</td>
    </tr>
    <tr>
      <td style="text-align:left">pay</td>
      <td style="text-align:left">Aktiviere /coins pay &lt;spieler&gt; &lt;amount&gt;</td>
    </tr>
    <tr>
      <td style="text-align:left">exeption</td>
      <td style="text-align:left">Eine Liste von Server-namen auf denen /coins nicht funktioniert</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>slowchat/slowcommand/repeatmessage</b>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">use</td>
      <td style="text-align:left">Aktiviere das entsprechende Modul</td>
    </tr>
    <tr>
      <td style="text-align:left">count</td>
      <td style="text-align:left">Cooldown in Sekunden f&#xFC;r das entsprechende Modul</td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">joinme cooldown</td>
      <td style="text-align:left">Eine Liste f&#xFC;r /joinme cooldowns. (permission:cooldownInMinutes)</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>reports</b>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">usetemplates</td>
      <td style="text-align:left">
        <p>false: Beim Reporten irgendeinen Grund angeben</p>
        <p>true: Nur die folgenden Gr&#xFC;nde akzeptieren</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">reasons</td>
      <td style="text-align:left">Liste der Gr&#xFC;nde</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>wartung</b>
      </td>
      <td style="text-align:left">Wartungsmodul an/aus</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>motd</b>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">normal</td>
      <td style="text-align:left">Normale Motd (Zeile 1 &amp;2)</td>
    </tr>
    <tr>
      <td style="text-align:left">wartung</td>
      <td style="text-align:left">Motd, wenn Wartungen aktiviert sind (Zeile 1 &amp; 2)</td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Slots</td>
      <td style="text-align:left">Maximale Anzahl an Spielern auf dem Netzwerk</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>adaptiveSlots</b>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">use</td>
      <td style="text-align:left">true: Angezeigte Slots passen sich der aktuellen Spieler Zahlen um amount
        stellen an</td>
    </tr>
    <tr>
      <td style="text-align:left">amount</td>
      <td style="text-align:left">Anzahl der &#xC4;nderung</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Lobby</b>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">name</td>
      <td style="text-align:left">
        <p>Wenn nur eine Lobby: Name der Lobby</p>
        <p>Wenn mehrere Lobbies: Name der Gruppe mit dem Minuszeichen</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">amount</td>
      <td style="text-align:left">Anzahl an Lobbys</td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">TeamSpeakMSG</td>
      <td style="text-align:left">Nachricht f&#xFC;r /ts</td>
    </tr>
    <tr>
      <td style="text-align:left">DiscordMSG</td>
      <td style="text-align:left">Nachricht f&#xFC;r /dc</td>
    </tr>
    <tr>
      <td style="text-align:left">ShopMSG</td>
      <td style="text-align:left">Nachricht f&#xFC;r /shop</td>
    </tr>
    <tr>
      <td style="text-align:left">ForumMSG</td>
      <td style="text-align:left">Nachricht f&#xFC;r /forum</td>
    </tr>
    <tr>
      <td style="text-align:left">BauServerName</td>
      <td style="text-align:left">Name vom Bauserver</td>
    </tr>
    <tr>
      <td style="text-align:left">Tablist</td>
      <td style="text-align:left">Die Tablist die anzeigt wird</td>
    </tr>
    <tr>
      <td style="text-align:left">youtuber</td>
      <td style="text-align:left">Eine Liste von Nachrichten f&#xFC;r /yt</td>
    </tr>
    <tr>
      <td style="text-align:left">ApplyMSG</td>
      <td style="text-align:left">Nachrichten Listen f&#xFC;r /apply</td>
    </tr>
    <tr>
      <td style="text-align:left">autobc</td>
      <td style="text-align:left">Automatischer Broadcast</td>
    </tr>
    <tr>
      <td style="text-align:left">messages</td>
      <td style="text-align:left">Einzelne bearbeitbare Nachrichten</td>
    </tr>
  </tbody>
</table>

```text
ServerName: ServerName
LizenzKey: RequestOnTheDiscord
Prefix: '&8[>] &cServer.de &7[>>]'
report:
  keepReportsOnLogout: false
  keepReportsOnRestart: false
toggle:
  motd: true
  joinmessage: true
  loginStatusOnJoin: true
  autobc: true
  clearchatOnJoin: true
  titleOnJoin: true
  warnsOnJoin: true
  autoIPBan: true
settings:
  blacklist:
    reason: Chatverhalten
    timeInDays: 1
  auth:
    use: true
    permission: bungee.team
    force: false
    onlyOnIpChange: true
    qrServer: https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=%data%
Coins:
  startgeld: 1000
  pay: false
  exeption:
  - EXAMPLE
chatmanager:
  slowchat:
    use: true
    count: 3
  slowcommand:
    use: true
    count: 3
  repeatmessage:
    use: true
    count: 300
joinme:
  cooldown:
  - rank.admin:5
  - rank.youtube:15
reports:
  usetemplates: false
  reasons:
  - HACKING
  - BUGUSING
  - BELEIDIGUNGEN
Wartung: false
Motd:
  normal:
    '1': '&8[x] &bDeinServer&7.&3de &8[x] &7network &8[>>]&71.8.x - 1.13&8[<<]'
    '2': '&7[>] &e&lNEU: &6&l/coins'
  wartung:
    '1': '&8[x] &bDeinServer&7.&3de &8[x] &7network &8[>>]&71.8.x - 1.13&8[<<]'
    '2': '&c[x] &4&lWartungsarbeiten &c[x] §6Status§8: §e50%'
Slots: 50
adaptiveSlots:
  use: true
  amount: 1
Lobby:
  name: Lobby-
  amount: 2
TeamSpeakMSG: '&7Unseren &eTeamSpeak &7erreicht du unter&8:&b Server.de'
DiscordMSG: '&7Unseren &eDiscord &7erreicht du unter&8:&b discord.gg/fhdsj'
ShopMSG: '&7Unseren &eShop &7erreicht du unter&8:&b shop.server.de'
ForumMSG: '&7Unser &eForum &7erreicht du unter&8:&b forum.server.de'
BauServerName: BuilderServer
TabList:
  aktive: true
  header:
  - '&8[>>] &bDeinServer.de &8[<<]'
  - '&3%players%&8/&7%max%'
  footer:
  - '&8[>>] &bForum&8: &3Server.de'
  - '&8[>>] &bTeamSpeak&8: &3Server.de'
UnbanbareSpieler: []
YouTuber:
  msg:
  - '&8&m-------------[&r &5&lYouTuber &7| &eAnforderungen &8&m]-------------'
ApplyMSG:
  dev:
  - '&8&m-------------[&r &e&lBewerbung &7| &bDeveloper &8&m]-------------'
  sup:
  - '&8&m-------------[&r &e&lBewerbung &7| &9Supporter &8&m]-------------'
  build:
  - '&8&m-------------[&r &e&lBewerbung &7| &aBuilder &8&m]-------------'
  overview:
  - '&8&m-------------[&r &e&lBewerbung &7| &6Übersicht &8&m]-------------'
autobc:
  list:
  - <br>&7[>>]<br>&8[>] &cServer.de &7[>>] &7Joine unserem Teamspeak &8[>] &e/ts<br>&7[>>]<br>
  - <br>&7[>>]<br>&8[>] &cServer.de &7[>>] &7Joine unserem Discord &8[>] &e/discord<br>&7[>>]<br>
  - <br>&7[>>]<br>&8[>] &cServer.de &7[>>] &7Wir suchen Teammitglieder &8[>] &e/apply<br>&7[>>]<br>
  timeInMinutes: 30
messages:
```

settings.yml \(gekürtzt\)

## Sonderzeichen

{% hint style="danger" %}
Wenn du bei einem [`String`](https://de.wikipedia.org/wiki/Zeichenkette) eins der folgenden Zeichen angibst, musst du ein `'` vor und nach dem String angeben.  
 `: { } [ ] , & * # ? | - < > = ! % @ \ ä ö ü`
{% endhint %}

