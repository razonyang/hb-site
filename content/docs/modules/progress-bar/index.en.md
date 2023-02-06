+++
title = "Progress Bar"
date = 2023-02-04T00:12:11+08:00
draft = false
categories = ["Module"]
tags = ["Progress Bar"]
series = ["Docs"]
images = []
+++

A progress bar will be shown when opening a new page in the current tab and window.

<!--more-->

## Installation

{{< bootstrap/config-toggle filename="config" >}}
[[module.imports]]
path = "github.com/razonyang/hb/modules/progress-bar"
{{< /bootstrap/config-toggle >}}

## Site Parameters

| Name            | Version  |  Type  | Require | Default | Description                                                    |
| --------------- | :------: | :----: | :-----: | :-----: | -------------------------------------------------------------- |
| `height`        | `v0.2.0` | string |    -    |  `2px`  | The height of progress bar.                                    |
| `initial_width` | `v0.3.0` | number |    -    |  `20`   | The initial width of progress bar, `0-100`.                    |
| `interval`      | `v0.3.0` | number |    -    |  `50`   | The time interval for progress bar to update, in milliseconds. |
| `time`          | `v0.3.0` | number |    -    |   `2`   | Time taken for progress bar to complete, in seconds.           |

{{< bootstrap/config-toggle filename="config" >}}
[params.hb.progress_bar]
height = "2px"
initial_width = 20
interval = 50
time = 2
{{< /bootstrap/config-toggle >}}
