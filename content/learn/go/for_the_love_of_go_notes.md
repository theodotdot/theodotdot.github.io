---
title: For the love of Go
draft: false
tags:
  - learn
  - go
  - dev
---

# For the love of Go, my notes

## Importing modules from the internet

In the project's or module's directory, run `go get <module>`
| e.g. run `go get github.com/google/go-cmp/cmp`
| the `go.mod` file will be updated and you can reference this module in your imports

## Wrapping types

When wanting to modify an external/non-local type to add a method for example, we can wrap it in a local type using a struct

> [!tip] 
```go
 type MyLocalType struct {
     MyField MyExternalType
} 
```
