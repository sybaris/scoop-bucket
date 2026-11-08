# Sybaris' Scoop bucket

[![Tests](https://github.com/sybaris/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/sybaris/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/sybaris/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/sybaris/scoop-bucket/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) bucket for my Windows applications.

| App | Description |
|-----|-------------|
| [hotkeylauncher](https://github.com/sybaris/HotkeyLauncher) | Launch applications, folders and web sites with global keyboard shortcuts |

## Install

```pwsh
scoop bucket add sybaris https://github.com/sybaris/scoop-bucket
scoop install sybaris/hotkeylauncher
```

Update with `scoop update hotkeylauncher`. The settings are kept across updates (Scoop `persist` folder).

## Maintenance

New versions are detected automatically: the *Excavator* workflow runs every 4 hours and updates the manifests from
their `checkver` / `autoupdate` sections (GitHub releases and their `SHA256SUMS.txt`).
