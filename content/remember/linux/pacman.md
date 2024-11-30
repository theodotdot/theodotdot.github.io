---
title: Pacman
draft: false
tags:
  - linux
  - cachyos
  - pacman
  - arch
---

# Autoremove unused dependencies/packages
```bash
pacman -R $(pacman -Qdtq)
```
