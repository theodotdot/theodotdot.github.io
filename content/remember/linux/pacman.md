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

# Auto-remove unused dependencies/packages
```bash
pacman -R $(pacman -Qdtq)
```
