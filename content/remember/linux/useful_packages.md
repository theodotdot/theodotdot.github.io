---
title: Useful packages
draft: false
tags:
  - remember
  - linux
  - tools
  - dev
---

# yazi file explorer

## plugins

[git.yazi](https://github.com/yazi-rs/plugins/tree/main/git.yazi)
[jump-to-char](https://github.com/yazi-rs/plugins/tree/main/jump-to-char.yazi)
[mount](https://github.com/yazi-rs/plugins/tree/main/mount.yazi) not used


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

# udisks: un/mounting disks

[Arch wiki page](https://wiki.archlinux.org/title/Udisks)

Use `udisksctl mount -b /path/to/disk` to mount and `unmount` to... you get it.

# selectdefaultapplication

[Github link](https://github.com/magnus-ISU/selectdefaultapplication)

Used to select default applications to open stuff through the xdg-open/mime protocols

# blueman: bluetooth utility

[Github link](https://github.com/blueman-project/blueman)

Simple bluetooth manager

# qimgv: simple image viewer

[Github link](https://github.com/easymodo/qimgv)

## ⌨️ Key Bindings

Check out the Github for all keybindings

| Action                    | Shortcut                                 |
| --------------------------| -----------------------------------------|
| Next image                | Right arrow / MouseWheel                 |
| Previous image            | Left arrow / MouseWheel                  |
| Goto first image          | Home                                     |
| Goto last image           | End                                      |
| Zoom in                   | Ctrl+MouseWheel / Crtl+Up                |
| Zoom out                  | Ctrl+MouseWheel / Crtl+Down              |
| Zoom (alt. method)        | Hold right mouse button & move up / down |
| Toggle fullscreen mode    | DoubleClick / F / F11                    |
| Crop image                | X                                        |
| Resize image              | R                                        |
| Rotate left               | Ctrl+L                                   |
| Rotate Right              | Ctrl+R                                   |
| Open containing directory | Ctrl+D                                   |
| Quick copy                | C                                        |
| Quick move                | M                                        |
| Move to trash             | Delete                                   |
| Folder view               | Enter / Backspace                        |
| Open                      | Ctrl+O                                   |
| Settings                  | P                                        |

# lutgen-rs: applying LUTS to images

[Github link](https://github.com/ozwaldorf/lutgen-rs)

Used to catppuccinify wallpapers but can be used to apply any LUT to any image.

# sioyek: PDF viewer

[Github link](https://github.com/ahrm/sioyek)

Multi platform PDF viewer, simple and solid

# presenterm

Lightweight programmee to create markdown presentations in the terminal

[Github link](https://github.com/mfontanini/presenterm)

Just read the [docs](https://mfontanini.github.io/presenterm/introduction.html) to get started.

