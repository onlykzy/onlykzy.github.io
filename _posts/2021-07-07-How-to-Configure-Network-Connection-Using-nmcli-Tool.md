---
title: "How to Configure Network Connection Using ‘nmcli’ Tool"
date: 2021-07-07 17:00:00
categories:
  - blog
tags:
  - linux
  - network-manager
  - network
---

install

```bash
apt install network-manager
```

To display all the active network interfaces on your Linux system execute the command.

```bash
nmcli connection show
nmcli con show
```

you can run the command below to display both active and inactive interfaces.

```bash
nmcli dev status
```

ToDo:

```bash
ip addr
```

[gnome](https://wiki.gnome.org/Projects/NetworkManager)
[redhat](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/7/html/Networking_Guide/)
[fedora](https://docs.fedoraproject.org/en-US/Fedora/24/html/Networking_Guide/index.html)
[debian](https://wiki.debian.org/NetworkManager)
[archlinux](https://wiki.archlinux.org/index.php/NetworkManager)
