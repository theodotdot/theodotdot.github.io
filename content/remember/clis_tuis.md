---
title: CLIs and TUIs
draft: false
tags:
  - tools
  - dev
---

# mdtt: markdown table editor

[LINK](https://github.com/szktkfm/mdtt)
Simple CLI markdown table editor.
Use `mdtt -i filename.md` to edit a table from a file (in place).

## ⌨️ Key Bindings

| Key            | Action            |
| -------------- | ----------------- |
| `↑`/`k`        | Move up           |
| `↓`/`j`        | Move down         |
| `←`/`h`        | Move left         |
| `→`/`l`        | Move right        |
| `b`/`pgup`     | Page up           |
| `f`/`pgdn`     | Page down         |
| `ctrl+u`       | Half page up      |
| `ctrl+d`       | Half page down    |
| `g`/`home`     | Go to start       |
| `G`/`end`      | Go to end         |
| `i`            | Insert mode       |
| `I`            | Open `$EDITOR`    |
| `esc`/`ctrl+c` | Normal mode       |
| `o`/`vo`       | Add row/column    |
| `dd`/`vd`      | Delete row/column |
| `yy`/`vy`      | Copy row/column   |
| `p`            | Paste             |
| `q`            | Quit              |
| `?`            | Toggle help       |

# vhs: terminal gifs as code

[LINK](https://github.com/charmbracelet/vhs)

Easy way to generate gifs of the terminal

> [!note] Great for documentation
> This is pretty elegant solution to document and show how programmes run


# gtrash: rm replacement

[LINK](https://github.com/umlx5h/gtrash)

I aliased it to rm.

Notable features:
 - Recursive by default (no need to use `-r` for folders)
 - `gtrash summary` to view the trash
 - `gtrash find` to list the files in the trash
 - **`gtrash restore` for the TUI to restore files**
