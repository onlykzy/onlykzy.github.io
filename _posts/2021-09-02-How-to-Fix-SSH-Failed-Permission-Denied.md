---
title: "How to Fix SSH Failed Permission Denied (publickey,gssapi-keyex,gssapi-with-mic)"
date: 2021-09-02 22:00:00
categories:
  - blog
tags:
  - ssh
  - openssl
  - publickey
---

The SSH Permission denied error appears when trying to SSH into a server:

```txt
Permission denied (publickey,gssapi-keyex,gssapi-with-mic)
```

```ini
# /etc/ssh/sshd_config
PasswordAuthentication yes
ChallengeResponseAuthentication no
PermitRootLogin no
PubkeyAuthentication yes
# GSSAPIAuthentication yes
# GSSAPICleanupCredentials no
UsePAM yes
```

restart sshd

```sh
systemctl restart sshd
```

permission

```
chmod 700 ~/.ssh
chmod 600 ~/.ssh/authorized_keys
```

[ssh-permission-denied-publickey](https://phoenixnap.com/kb/ssh-permission-denied-publickey)

[sshd_config](https://linux.die.net/man/5/sshd_config)
