# multiport-ws update for Debian 10 only for first run

```
apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
```

# multiport-ws

```
apt update -y && apt install sudo -y && sudo apt install -y wget && sudo apt install -y bzip2 gzip coreutils screen curl && wget -q https://raw.githubusercontent.com/vpnlegasi/multiport-ws/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh

```
