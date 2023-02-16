+++
title = "Diagrams"
date = 2023-01-22T15:20:32+08:00
tags = ["Mermaid", "GoAT"]
categories = ["Diagrams"]
series = ["Docs"]
+++

HB supports GoAT and Mermaid for renderring diagrams.

<!--more-->

## Mermaid

The Mermaid is supported by the [mermaid]({{< ref "docs/modules/mermaid" >}}) module.

## GoAT

Hugo supports GoAT natively. More syntaxs and examples can be found on https://github.com/bep/goat.

````markdown
```goat
DIAGRAM
```
````

```goat
      .               .                .               .--- 1          .-- 1     / 1
     / \              |                |           .---+            .-+         +
    /   \         .---+---.         .--+--.        |   '--- 2      |   '-- 2   / \ 2
   +     +        |       |        |       |    ---+            ---+          +
  / \   / \     .-+-.   .-+-.     .+.     .+.      |   .--- 3      |   .-- 3   \ / 3
 /   \ /   \    |   |   |   |    |   |   |   |     '---+            '-+         +
 1   2 3   4    1   2   3   4    1   2   3   4         '--- 4          '-- 4     \ 4
```