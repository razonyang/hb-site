{{- $name := .Get 0 }}
| Module Path | Version |
| ---- | ------- |
| `{{ $name }}` | ![Version](https://img.shields.io/badge/dynamic/json?color=blue&label=version&query=name&url=https://api.razonyang.com/v1/github/tag/{{ replace $name "github.com/" "" }}/) |
