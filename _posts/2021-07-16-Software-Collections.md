---
title: "Use the higher version of GCC through SCL"
date: 2021-07-16 17:00:00
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

vscode cmake-tools-kits:

```bash
~/.local/share/CMakeTools
```