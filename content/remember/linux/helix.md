---
title: Helix
draft: false
tags:
  - remember
  - linux
  - helix
  - zellij
  - tools
  - dev
---

# Navigation 

TODO: understand jumplist and go to definition (and going back)

## Jumping to next/previous character
Use `f+<char>` and `F+<char>` to jump the cursor on the next/previous \<char\>.
Use `t+<char>` and `T+<char>` to jump the cursor on the next/previous \<char\>.

> [!tip] You can repeat the last f/F/t/T
> Use `Alt+.`

# Selection

## Sorting
[Demo video](https://www.reddit.com/r/HelixEditor/comments/1b9j40u/sorting_in_helix/)
### Numbered lists
Select the list and use the `pipe:sort` or `|sort` command.
### Multiple selections
Simply use `:sort`
See [[helix#Advanced word selection]] to select words in a line
### Advanced sorting
Helix uses the `sort` Unix programme, and you can thus pass any valid argument.
> [!info] Random sorting
> Pass the -R argument to randomly sort

## Advanced word selection
To select comma or space separated words, we can use regex:
 - Select all the words in a single selection
 - enter select mode
 - Type `\w+`

## Splitting selection
`s` will search through the selection and insert a cursor at each match within the selection.
`S` will search through the selection and split the selection at each match within the selection (keeping the primary cursor as well).

> [!tip] 
> Use `Alt+,` to remove the primary cursor, also useful when selecting too many lines with x for example.

## Match mode
Match mode is used to select text in and around bracket pairs, press `m` to enter match mode.

# Text transformation

## Repeat last input
Use `.` to repeat last input. That's it 🤷‍♂

## Changing to upper or lower case
Use \` to switch text to lower case and `Alt+\`` to switch to upper case.
Use `~` to switch case for each character in the selection.
> [!hint] 
> "ThiS iS gREaT" becomes tHIs Is GreAt

# Multi-cursor
There are several ways to generate multiple cursors in Helix, [[helix#Splitting selection]] is one for example.
> [!tip] 
> Use `,` to revert to the primary cursor only

## Inserting cursor below
To insert a new cursor (and technically the whole primary selection) on the next non-empty line, use `C`. (see [[helix#Splitting selection]] on what to do to undo)

## Cycling selections
Use `(` and `)` respectively to cycle the primary selection backwards or forwards.

Use `Alt+(` and `Alt+)` respectively to cycle the selections' contents backwards or forwards.

# Language config

## Markdown
[markdown-oxide](https://oxide.md)

[simple completion language server](https://github.com/estin/simple-completion-language-server) (for custom snippets)
