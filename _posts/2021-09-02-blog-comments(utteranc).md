---
title: "Adding utteranc to a Jekyll-based static website"
date: 2021-09-02 22:30:00
categories:
  - blog
tags:
  - blog
  - minimal-mistakes
  - Jekyll
  - web
  - comments
  - utteranc
---

[utteranc](https://utteranc.es/)

**_layouts\single_utteranc.html**

[minimal-mistakes](https://github.com/mmistakes/minimal-mistakes)

**_config.yml**

```yml
defaults:
  # _posts
  - scope:
      path: ""
      type: posts
    values:
      # layout: single
      layout: single_utteranc
      author_profile: true
      read_time: true
      comments: true
      share: false
      related: true
  # _pages
  - scope:
      path: "_pages"
      type: pages
    values:
      # layout: single
      layout: single_utteranc
      author_profile: true
```
