---
title: "Style Guide"
date: 2022-12-14T20:00:32+08:00
draft: false
nav_weight: 1
series:
  - Docs
categories:
  - Style Guide
tags:
  - CSS
  - HTML
  - JavaScript
---

Undoubtedly, the same coding style helps developers to cooperate with each other.
We suggest taking a few minutes to learn about the coding style used, if you plan to join us.

<!--more-->

## Style Guides

1. [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html) for HTML and CSS.
1. [JavaScript Standard Style](https://standardjs.com/) for JavaScript.
1. [Typescript Standard Style](https://github.com/standard/ts-standard) for TypeScript.

## Hugo Style Guide

### Naming Conventions

#### Parameters Naming Convention

Since Hugo parameters are case-insensitive, [snake_case](https://en.wikipedia.org/wiki/Snake_case) are preferred.

| Parameter |
|---|---
| `FooBar` | ❎
| `fooBar` | ❎
| `foobar` | ❎
| `foo-bar` | ❎
| `foo_bar` | ✅

#### File Naming Convention

The filenames are case-sensitive on most file systems, so we recommend always using `kebab-case`.

| Filename | 
|---|---
| `fooBar.html` | ❎
| `foo-bar.html` | ✅

#### Variables Naming Conventions

1. Use `PascalCase` for exported variables, as Go does.
1. Use `camelCase` for local variables.
