---
title: Locale config
draft: false
tags:
  - remember
  - linux
  - locale
---

# Setting the cedilla with US intl

[Arch wiki on locale](https://wiki.archlinux.org/title/Locale)
[Random GH gist](https://gist.github.com/ericdouglas/74469cb97188751f71bfdcd7d28f75fd)

Set those two env variables:
 - GTK_IM_MODULE = cedilla
 - QT_IM_MODULE = cedilla

Edit /usr/share/X11/locale/en_US.UTF-8/ and change the <dead\_acute> <c> ... to:
<dead\_acute> <c> : "ç" U00E7 # LATIN SMALL LETTER C WITH CEDILLA
and saame for upper case:
<dead\_acute> <C> : "Ç" U00C7 # LATIN CAPITAL LETTER C WITH CEDILLA

