---
title: Pacman
draft: false
tags:
  - remember
  - linux
  - cachyos
  - pacman
  - arch
---

# Autoremove unused dependencies/packages
```bash
pacman -R $(pacman -Qdtq)
```
