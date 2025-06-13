---
title: LSP config
draft: false
tags:
  - remember
  - linux
  - lsp
  - helix
  - tools
  - dev
---

> [!tip] Helix LSP config wiki page
> https://github.com/helix-editor/helix/wiki/Language-Server-Configurations

# Markdown
 - marksman
 - [markdown-oxide](https://oxide.md)
 - [simple completion language server](https://github.com/estin/simple-completion-language-server) (for custom snippets)

# Go
 - go install golang.org/x/tools/gopls@latest                            # LSP
 - go install github.com/go-delve/delve/cmd/dlv@latest                   # Debugger
 - go install golang.org/x/tools/cmd/goimports@latest                    # Formatter
 - go install github.com/nametake/golangci-lint-langserver@latest        # Linter
 - go install github.com/golangci/golangci-lint/cmd/golangci-lint@latest # Linter cli
