---
title: "Adding a favicon to a Jekyll-based static website"
date: 2021-09-02 22:30:00
categories:
  - blog
tags:
  - blog
  - minimal-mistakes
  - Jekyll
  - favicon
  - web
---

[reference](https://ptc-it.de/add-favicon-to-mm-jekyll-site/)

[favicon generator](https://realfavicongenerator.net/)

**_includes/head/custom.html**

[custom.html](https://github.com/onlykzy/onlykzy.github.io/blob/master/_includes/head/custom.html)

```html
<!-- start custom head snippets -->

<!-- insert favicons. use https://realfavicongenerator.net/ -->
<link rel="apple-touch-icon" sizes="180x180" href="/assets/images/favicon/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/assets/images/favicon/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/assets/images/favicon/favicon-16x16.png">
<link rel="manifest" href="/assets/images/favicon/site.webmanifest">
<link rel="mask-icon" href="/assets/images/favicon/safari-pinned-tab.svg" color="#5bbad5">
<link rel="shortcut icon" href="/assets/images/favicon/favicon.ico">
<meta name="msapplication-TileColor" content="#da532c">
<meta name="msapplication-config" content="/assets/images/favicon/browserconfig.xml">
<meta name="theme-color" content="#ffffff">

<!-- end custom head snippets -->
```
