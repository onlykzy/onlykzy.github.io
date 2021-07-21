---
title: "Use the higher version of GCC through SCL"
date: 2021-07-21 10:00:00
categories:
  - blog
tags:
  - linux
  - dnf
  - yum
  - mirror
---

/etc/dnf/dnf.conf

```ini
[main]
fastestmirror=true
```

update

```bash
sudo dnf clean all
sudo dnf makecache
```
