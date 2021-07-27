---
title: "dnf fastest mirror"
date: 2021-07-27 14:30:00
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
