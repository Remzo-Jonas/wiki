---
description: >-
  Die Plugins sind auf Java 8 getestet. Somit können wir nur mit Java 8 die
  volle Funktionalität garantieren. Neuere Java Versionen können auch
  funktionieren.
---

# Java Installation (Debian 10/11)

## Java 8

Falls Sie gerne Java-8 installieren möchten, führen Sie bitte folgende Befehle durch:

```
apt install apt-transport-https ca-certificates wget dirmngr gnupg software-properties-common -y
wget -qO - https://adoptopenjdk.jfrog.io/adoptopenjdk/api/gpg/key/public | apt-key add -
add-apt-repository --yes https://adoptopenjdk.jfrog.io/adoptopenjdk/deb/
apt update
apt install adoptopenjdk-8-hotspot -y
```

## Java 17

```
apt install gnupg curl dirmngr nano unzip -y
apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 73C3DB2A
echo "deb http://ppa.launchpad.net/linuxuprising/java/ubuntu focal main" | tee /etc/apt/sources.list.d/java.list
apt update
apt install oracle-java17-installer -y
```

## Auswahl der Version

Wenn du mehrere Versionen installiert hast, kannst du die standartversion mit dem folgenden Befehl auswählen

```
sudo update-alternatives --config java
```
