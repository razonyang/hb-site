---
title: "Prerequisites"
date: 2022-12-19T14:53:42+08:00
draft: false
tags:
categories:
series:
nav_weight: 2
---

Please make sure you meet the prerequisites prior to using or developing the HB and its modules.

## Configuration

```toml
[build]
  writeStats = true
```

## Build Tools

> We recommend using the latest version of those tools as possible.

| Name | Min Version | Recommended Version | Description
|:-:|:-:|:-:|---
| [Hugo](https://gohugo.io/installation/) | `>=extended-0.109.0` | Extended version.
| [Go](https://go.dev/dl/) | `>=1.12` | Required by [Hugo Modules](https://gohugo.io/hugo-modules/use-modules/#prerequisite).
| [Git](https://git-scm.com/downloads) | `>=2.39.0` | Version Control Systems.
| [NPM](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm/) | `>=8.19.2` | Used install third-party tools listed below.
| [POSTCSS CLI](https://github.com/postcss/postcss-cli) | `>=8.0.0` | 

## Notes

### Avoid changing `hb.*` parameters via language-scoped configurations


