---
title: Keyboard layout
draft: false
tags:
  - linux
  - hyprland
  - dev
  - lafayette
---

# Layouts

I use ~~US international with dead keys~~ Ergo-L for my ergo split keyboards and Qwerty Lafayette for the rest.

# Lafayette

[Information](https://qwerty-lafayette.org/)

## Installation

I used [kalamine](https://github.com/OneDeadKey/kalamine) to install it.

Simply run those commands:
```
  wget https://qwerty-lafayette.org/layouts/lafayette.toml
  pip install --user --upgrade kalamine  # ou `pipx install kalamine`
  xkalamine install lafayette.toml
```

Then, the layout `fr, lafayette` will be available.


# Ergo-L

[ergol.org](https://ergol.org/)

It is available for any distro running xkeyboard-config<=2.42!
