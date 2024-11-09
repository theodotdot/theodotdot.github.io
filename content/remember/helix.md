---
title: Helix
draft: true
tags:
  - helix
  - zellij
  - tools
  - dev
---

# Navigating around

TODO: understand jumplist and go to definition (and going back)


# Sorting
[Demo video](https://www.reddit.com/r/HelixEditor/comments/1b9j40u/sorting_in_helix/)

## Numbered lists
Select the list and use the `pipe:sort` or `|sort` command.
## Multiple selections
Simply use `:sort`
See [[helix#Selecting words]] to select words in a line
## Advanced sorting
Helix uses the `sort` Unix programme, and you can thus pass any valid argument.
> [!info] Random sorting
> Pass the -R argument to randomly sort


# Advanced selection

## Selecting words
To select comma or space separated words, we can use regex:
 - Select all the words in a single selection
 - enter select mode
 - Type `\w+`

