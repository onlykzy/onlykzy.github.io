---
title: "Use the higher version of GCC through SCL"
date: 2021-08-27 16:00
categories:
  - blog
tags:
  - linux
  - gcc
  - build system
  - dnf
  - yum
  - cmake
  - vscode
  - c++
  - cpp
---

install

```bash
dnf install centos-release-scl
dnf install devtoolset-9
```

usage

```bash
scl enable devtoolset-9 zsh
```

cmake

```bash
export CC=`which gcc`
export CXX=`which g++`
```

default

```bash
# /etc/profile
source /opt/rh/devtoolset-9/enable
export CC=`which gcc`
export CXX=`which g++`
```

vscode cmake-tools-kits:

```bash
~/.local/share/CMakeTools
```
